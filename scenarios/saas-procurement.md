# SaaS 采购初筛

> 完整的 Amazon Quick 操作步骤参见 [Training Hands-on User Guide](../user-guide.md)。本页仅说明业务场景，不重复 Step-by-step 流程。

## 场景背景

公司计划为约 800 名员工采购统一的企业项目管理 SaaS，需要综合核查功能、安全、集成、服务、预算和上线时间。

Skill 应优先执行强制条件检查，再形成有证据支持的评估建议，避免仅按价格或厂商自述排序。

## 实验资料

- [采购需求](../hands-on-data/saas-procurement/saas-procurement-requirements.md)
- [评估政策](../hands-on-data/saas-procurement/saas-evaluation-policy.md)
- [厂商方案](../hands-on-data/saas-procurement/saas-proposals.csv)

## Skill 目标

- 检查数据存储、身份管理、安全认证、数据使用、SLA、预算和上线日期。
- 识别安全、集成、商务和交付风险，并引用原始字段。
- 区分正式评分、参考评分和强制门槛结论。
- 输出供 IT、采购、安全、法务和业务负责人复核的候选建议。

## 预期结果

| 方案 | 预期处理 |
|---|---|
| `S001` | 优先进入下一轮 |
| `S002` | 暂不进入下一轮 |
| `S003` | 暂不进入下一轮 |
| `S004` | 待澄清后决定 |

## 人工决策边界

- Skill 不得批准采购、签署合同或代表相关部门接受风险。
- 最低价格不能替代安全、合规、功能和实施能力评估。
- 厂商声明不等于已验证事实，缺失材料必须标记为“未知”或“待澄清”。
- 最终采购决定由 IT、采购、安全、法务和业务负责人共同完成。
