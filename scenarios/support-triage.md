# 企业客户支持工单分级

> 完整的 Amazon Quick 操作步骤参见 [Training Hands-on User Guide](../user-guide.md)。本页仅说明业务场景，不重复 Step-by-step 流程。

## 场景背景

企业支持团队需要对新进入队列的工单统一分级，优先识别安全、数据丢失和大范围服务不可用事件。

Skill 应先识别强制升级条件，再对其他工单评估业务影响、紧急程度、SLA 风险、替代方案和可复现性。

## 实验资料

- [服务要求](../hands-on-data/support-triage/support-service-requirements.md)
- [分级政策](../hands-on-data/support-triage/ticket-triage-policy.md)
- [支持工单](../hands-on-data/support-triage/support-tickets.csv)

## Skill 目标

- 识别必须立即升级的安全或重大可用性事件。
- 对非 P0 工单评估优先级、建议队列和首响目标。
- 引用原始字段，标记缺失信息并提出必要的澄清事项。
- 输出供值班经理和支持团队复核的分级建议。

## 预期结果

| 工单 | 预期处理 |
|---|---|
| `T001` | 低优先级处理 |
| `T002` | 立即升级 |
| `T003` | 立即升级 |
| `T004` | 高优先级处理 |

## 人工决策边界

- Skill 不得关闭工单、对外发送通知或承诺修复时间。
- P0 强制升级规则优先于评分，不得通过评分降低重大事件等级。
- 信息不足时不得假设影响范围；值班经理可根据新增证据调整建议等级。
- 安全事件是否成立以及最终响应措施由安全团队和值班负责人判断。
