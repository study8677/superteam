# 新时代超级个体与超级团队教程

这个仓库是一套面向个人、团队负责人和创业小团队的中文教程，目标是说明：在 AI 成为基础生产力之后，如何从“会用工具的人”升级为“能组织智能系统的人”，再进一步组成可持续交付的超级团队。

内容状态：`0.1.0` 初版，核心教程、模板和示例已经可读可用，后续适合继续补真实案例、工具矩阵和场景 SOP。

本仓库不把超级个体理解为一个人无限加班，也不把超级团队理解为一群人堆满 AI 工具。这里的核心判断是：

> 超级个体决定产出上限，超级团队决定组织复利。

## 适合谁

- 想用 AI 系统提升个人生产力的人
- 正在从个人创作者、独立开发者升级为小团队的人
- 希望重构研发、内容、运营、产品流程的团队负责人
- 需要建立 AI 协作规范、验证机制和复盘机制的组织

## 不适合谁

- 只想看 AI 工具排行榜的人
- 只想复制提示词、不想改变工作流的人
- 希望用 AI 绕过审核、隐私或权限边界的人
- 只追求短期效率、不关心质量和责任的人

## 前置基础

不要求编程背景，但需要你能拿出一个真实工作场景来练习，例如写报告、做需求、改流程、整理客户反馈、开发一个小功能或运营一个内容项目。

## 30 分钟开始

如果你只想先快速试一轮：

1. 打开 [30 分钟个人工作流改造](playbooks/30-minute-personal-workflow.md)。
2. 选择一个你本周一定要完成的任务。
3. 用 [个人 AI 操作系统模板](templates/personal-ai-operating-system.md) 写出目标、上下文和验证方式。
4. 做完后用 [每周复盘模板](templates/weekly-review.md) 记录一次可复用经验。

## 你会学到什么

| 模块 | 解决的问题 | 输出物 |
| --- | --- | --- |
| 超级个体 | 个人如何建立 AI 工作系统 | 个人 AI 操作系统模板 |
| 超级团队 | 多个高产个体如何避免互相制造混乱 | 团队章程模板 |
| AI 原生流程 | 传统流水线如何变成连续证据流 | 工作流规格模板 |
| 治理与风险 | 如何让 AI 高速产出可验证、可回滚、可负责 | 风险检查清单 |
| 30 天落地 | 从零开始如何推进团队改造 | 30 天实施路线 |

## 快速开始

1. 先读 [从这里开始](docs/00-start-here.md)，理解本教程的边界和学习路径。
2. 如果你是个人，进入 [超级个体](docs/01-super-individual.md)，并填写 [个人 AI 操作系统模板](templates/personal-ai-operating-system.md)。
3. 如果你在带团队，进入 [超级团队](docs/02-super-team.md)，并填写 [团队章程模板](templates/team-charter.md)。
4. 如果你要改造现有业务流程，阅读 [AI 原生工作流](docs/03-ai-native-workflow.md)，再使用 [工作流规格模板](templates/ai-workflow-spec.md)。
5. 最后用 [30 天落地路线](docs/06-30-day-playbook.md) 做第一轮实践。

## 学习路径

学习路径图见 [assets/learning-path.mmd](assets/learning-path.mmd)。

### 路径 A：个人升级

适合独立开发者、内容创作者、产品经理、运营、研究员。

阅读顺序：

1. [从这里开始](docs/00-start-here.md)
2. [超级个体：从工具使用者到智能系统组织者](docs/01-super-individual.md)
3. [团队操作系统：让高产出变成稳定复利](docs/04-team-operating-system.md)
4. [每周复盘模板](templates/weekly-review.md)

### 路径 B：团队改造

适合 3 到 20 人的小团队、创业团队、产品研发团队。

阅读顺序：

1. [超级团队：不是更多人，而是更高责任密度](docs/02-super-team.md)
2. [AI 原生工作流：从阶段交接到连续证据流](docs/03-ai-native-workflow.md)
3. [治理与风险：让速度可控](docs/05-governance-and-risk.md)
4. [30 天落地路线](docs/06-30-day-playbook.md)

### 路径 C：组织评估

适合管理者、负责人、顾问或教练。

阅读顺序：

1. [成熟度模型](docs/07-maturity-model.md)
2. [团队操作系统](docs/04-team-operating-system.md)
3. [小型产品团队示例](examples/small-product-team.md)

## 可执行材料

- [30 分钟个人工作流改造](playbooks/30-minute-personal-workflow.md)
- [工具选型矩阵](tools/selection-matrix.md)
- [Prompt 使用原则](prompts/README.md)

## 核心概念

| 概念 | 简明定义 |
| --- | --- |
| 超级个体 | 能用 AI 扩展研究、执行、验证和表达能力的人 |
| 超级团队 | 围绕明确用户结果，把人、AI、上下文、验证和责任重新组织起来的团队 |
| 连续证据流 | 每个需求从目标、假设、实现、测试、指标到复盘都留下可检查证据 |
| 团队操作系统 | 团队共用的目标、上下文、权限、节奏、模板和复盘机制 |
| 责任密度 | 单位人数承担的判断、交付、验证和长期维护责任 |

## 仓库结构

```text
.
├── README.md
├── SUMMARY.md
├── playbooks/
│   └── 30-minute-personal-workflow.md
├── docs/
│   ├── 00-start-here.md
│   ├── 01-super-individual.md
│   ├── 02-super-team.md
│   ├── 03-ai-native-workflow.md
│   ├── 04-team-operating-system.md
│   ├── 05-governance-and-risk.md
│   ├── 06-30-day-playbook.md
│   └── 07-maturity-model.md
├── templates/
│   ├── personal-ai-operating-system.md
│   ├── team-charter.md
│   ├── ai-workflow-spec.md
│   └── weekly-review.md
├── tools/
│   └── selection-matrix.md
├── prompts/
│   └── README.md
├── assets/
│   └── learning-path.mmd
└── examples/
    └── small-product-team.md
```

## 使用原则

- 先定义目标，再选择工具。
- 先建立验证，再放大执行。
- 先沉淀上下文，再追求规模。
- 先明确责任，再引入自动化。

## 贡献方式

欢迎提交改进建议、案例和模板优化。提交前请阅读 [贡献指南](CONTRIBUTING.md)。
