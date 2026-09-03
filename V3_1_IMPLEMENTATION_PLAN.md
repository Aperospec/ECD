# ECD V3.1 修改与实现方案

状态：实施完成后进入重新安装与测试
目标分支：`v3-department-architecture`
冻结基线：`v2.1-legacy`

## 一、问题定义

当前 V3.0-alpha 完成了部门组织图，但没有完成可运行系统所需的三件事：

1. V2 已经验证过的阶段状态、ECD 决策对象、硬停止条件和权限规则没有完整迁移到 V3 Core；
2. 多数 Department Director 只列出了职业名称，相关 Specialist Skill 并不存在或未注册；
3. V3 分支仍保留完整 V2 Runtime，造成旧规则和新规则并存。

实际后果是：系统可以声称“已按 V3 审核”，但没有可检查的部门产物；普通肯定回复被误当成 Greenlight；Development 尚未完成便直接写最终正文；Editorial 阶段提前决定颜色、字体、构图和主体位置。

## 二、修改原则

### 1. 组织责任与专业方法分离

- Creative Producer：项目集成、状态、权限、跨部门协调和 ECD 接口；
- Department Director：本部门专业质量、能力选择、返工和签字；
- Specialist Skill：一项真实存在、可注册、可检查的方法；
- ECD：重大创意决定和最终接受。

### 2. 不允许虚构能力

只有 `core/CAPABILITY_REGISTRY.md` 中标记为 `Implemented` 且拥有有效 `SKILL.md` 的能力才能被调用或声称使用。

### 3. 不允许虚构审核

任何 `Department Cleared` 必须引用实际 Specialist Return、实际产物和 Director Review Record。任何 `Producer Cleared` 必须引用 Department Cleared Package 和 Producer Integrated Review。

### 4. 权限只能绑定明确决策对象

普通的“可以”“继续”“这个方向不错”只有在它直接回答当前待决、完整、命名明确的 ECD Decision Object 时才改变 Authority State。

### 5. 阶段边界恢复为硬约束

- Discovery：只推荐和比较，不产生 Treatment 或审批；
- Development：只定义项目、角度、依据、边界和 Treatment；
- Editorial：只定义传播逻辑、页序、Frame Script、准确文案和证据语言；
- Visual：才决定构图、颜色、字体、图文关系、镜头和视觉系统；
- Production：只忠实完成最终资产。

## 三、实施范围

### A. 重建 V3 Core

新增或重写：

- `core/CAPABILITY_REGISTRY.md`
- `core/RUNTIME_STATE_MACHINE.md`
- `core/AUTHORITY_AND_DECISION_OBJECTS.md`
- `core/STAGE_CAPABILITY_MATRIX.md`
- `core/DEPARTMENT_CONTROL_LOOP.md`
- `core/HANDOFF_AND_REWORK.md`
- `core/PROJECT_STATE.md`
- `core/creative-producer/SKILL.md`

### B. 建立最小完整专业链

#### Development

- Creative Strategy
- Concept Development
- Research Verification
- Claims / Rights Review
- Development Director

#### Editorial

- Content Architecture
- Frame Script
- Copywriting
- Copy Editing
- Proofreading
- Editorial Director

#### Visual

- Visual Concept
- Storyboard / Sequence
- Editorial Design
- Typography
- Image Direction
- Design Critique
- Art Director

#### Production

- Image Production
- Finished Art
- Production Typesetting
- Technical QA
- Production Director

所有以上能力必须有独立、带 `name` 和 `description` 的 `SKILL.md`。

### C. 恢复 Social Editorial 的完整决策界面

新增：

- `profiles/social-editorial/ENTRY_ROUTER.md`
- `profiles/social-editorial/DECISION_OBJECTS.md`
- 更新 `profiles/social-editorial/PROFILE.md`

### D. 清理 V3 分支

从 V3 物理删除以下 V2 Runtime：

- `art-director/`
- `creative-producer/`
- `editorial-director/`
- `production-artist/`
- `shared/`
- 旧 `ORGANIZATION.md`
- V3 中被替代的 `DIRECTOR.md` 与 `ROLE.md`

V2 历史继续由 `v2.1-legacy` 保存。

### E. 建立回归测试

- Discovery 推荐不得冒充 Greenlight；
- 普通“可以”不得绑定不存在的决策对象；
- Treatment 未 Greenlight 不得写完整 Script；
- Script 未 Alignment 不得决定颜色、构图、字体和图像；
- 不存在的 Skill 不得声称已调用；
- 没有实际产物不得声称 Department Cleared；
- 概念创作不得被误写成真实经历后再靠结尾声明补救；
- Visual Alignment 必须同时提供全序列覆盖和代表性高保真证明；
- Final Acceptance 必须有三部门签字和 Producer Final Review。

## 四、目标运行行为

以“从书签中挑一个值得发的小红书主题”为例：

```text
用户要求选题
→ Producer 进入 Discovery / Advisory
→ 返回一项推荐及依据，并明确这不是 Treatment
→ 用户表示认可并要求制作
→ Producer 激活 Development
→ Development 完成 Treatment、部门审核
→ Producer 提交完整 Greenlight 对象
→ ECD 明确批准
→ Editorial 完成完整 Creative Script、部门审核
→ Producer 提交 Script Alignment 对象
→ ECD 明确批准
→ Visual 才开始决定颜色、构图、字体和图像
```

## 五、完成验收标准

V3.1 只有同时满足下列条件才允许重新测试：

1. V3 分支不再包含 V2 Runtime；
2. Capability Registry 中所有 Implemented 技能路径真实存在；
3. 每个 Specialist Skill 都能独立注册；
4. 根 Skill 明确加载所有 Core 合同；
5. Director 不得声明未实现能力；
6. 权限状态只能由绑定 Decision Object 的回复改变；
7. Social Editorial 四个 ECD Gate 均有固定可见模板；
8. 回归测试覆盖 Discovery、Greenlight、Script、Visual、Production 和 Final Acceptance；
9. 新项目中用户不再承担内部调度或第一线 QA。
