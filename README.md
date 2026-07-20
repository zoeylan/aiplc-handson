# AI-PLC with Amazon Quick Hands-on

使用 Amazon Quick Desktop，通过 Deep Research、Brainstorm、Plan 和 Execute 四个阶段创建并测试业务 Skill。

本 README 是仓库内容导览。首次使用请从 Training 完整实操开始；完成后，可通过扩展场景了解同一方法在不同业务中的应用。

## 内容导航

| 类型 | 场景 | 入口 | 测试数据 |
|---|---|---|---|
| 完整实操 | 年度员工培训供应商初筛 | [Step-by-step 指南](./user-guide.md) | [供应商报价](./hands-on-data/training/training-supplier-quotes.csv) |
| 扩展场景 | 企业客户成功经理候选人初筛 | [场景说明](./scenarios/recruitment.md) | [候选人资料](./hands-on-data/recruitment/candidate-profiles.csv) |
| 扩展场景 | SaaS 采购初筛 | [场景说明](./scenarios/saas-procurement.md) | [厂商方案](./hands-on-data/saas-procurement/saas-proposals.csv) |
| 扩展场景 | 渠道合作伙伴初筛 | [场景说明](./scenarios/channel-partner.md) | [合作伙伴资料](./hands-on-data/channel-partner/channel-partner-profiles.csv) |
| 扩展场景 | 企业客户支持工单分级 | [场景说明](./scenarios/support-triage.md) | [支持工单](./hands-on-data/support-triage/support-tickets.csv) |

## 推荐阅读顺序

1. 打开 [Training Hands-on User Guide](./user-guide.md)，完成安装、Skill 导入和完整实操。
2. 阅读 `scenarios/` 下的扩展场景说明，了解业务背景、实验资料、Skill 目标和预期结果。
3. 使用场景对应的需求、政策和测试数据，自行复用 Training 中的四阶段方法。

## 通用流程

```text
① Deep Research  →  ② Brainstorm  →  ③ Plan  →  ④ Execute
   研究报告            PRD              实施计划       业务 Skill
```

完整的安装、Skill 导入、四阶段操作、测试和优化步骤均以 [Training Hands-on User Guide](./user-guide.md) 为准。

## 通用 Skills

| Skill | 作用 | 文件 |
|---|---|---|
| `deepresearch` | 研究业务方法和规则 | [SKILL.md](./skills/deepresearch/SKILL.md) |
| `brainstorm` | 明确需求并生成 PRD | [SKILL.md](./skills/brainstorm/SKILL.md) |
| `plan` | 将 PRD 拆分为实施计划 | [SKILL.md](./skills/plan/SKILL.md) |
| `execute` | 按计划生成业务 Skill | [SKILL.md](./skills/execute/SKILL.md) |

## 仓库结构

```text
.
├── README.md
├── user-guide.md                 # Training 完整实操指南
├── scenarios/                    # 其他业务场景说明
│   ├── recruitment.md
│   ├── saas-procurement.md
│   ├── channel-partner.md
│   └── support-triage.md
├── hands-on-data/
│   ├── training/
│   ├── recruitment/
│   ├── saas-procurement/
│   ├── channel-partner/
│   └── support-triage/
├── skills/                       # 四个通用 Skills
└── images/                       # Training 指南截图
```

## 使用说明

- `hands-on-data/` 中的数据均为 Hands-on 演示数据。
- 生成的业务 Skill 仅提供辅助建议，最终业务决定应由相应负责人完成。
- 请勿在测试时上传真实凭证、个人敏感信息或未经授权的业务数据。
