# SPLIT 阶段模板

固定文案单一来源：SPLIT 阶段输出骨架请仅使用本文件对应语言模板。

## zh-CN

```markdown
# SPLIT（切片与输出规划）

## 切片原则
- 维度：业务场景 / 期数 / 系统边界
- 变更类型：复用 / 改造 / 新增

## 需求切片映射表
| 切片ID | PRD章节 | 场景/能力点 | 目标系统 | 变更类型 | 外部触发方/调用边界 | 模板/配置依赖 | 输出文档 |
| --- | --- | --- | --- | --- | --- | --- | --- |
| S1 | {prd_section} | {capability} | {system} | {change_type} | {external_caller} | {template_or_config_dependency} | {doc_name} |

## 输出策略
- 单文档 / 多文档：{single_or_multi}
- 多文档边界说明：{boundary_rules}
- 跨系统依赖：{cross_system_dependencies}

## 历史样本对齐结论
- 参考样本：{historical_samples}
- 对齐项：{alignment_points}
- 差异项：{diff_points}

## ❓待确认项
- ❓{open_question_1}
```

## en

```markdown
# SPLIT (Slicing and Output Planning)

## Slicing Principles
- Dimensions: business scenario / phase / system boundary
- Change type: reuse / modification / new

## Requirement Slice Mapping
| Slice ID | PRD Section | Scenario / Capability | Target System | Change Type | External Caller / Boundary | Template or Config Dependency | Output Document |
| --- | --- | --- | --- | --- | --- | --- | --- |
| S1 | {prd_section} | {capability} | {system} | {change_type} | {external_caller} | {template_or_config_dependency} | {doc_name} |

## Output Strategy
- Single or multiple docs: {single_or_multi}
- Boundary rule for multi-doc output: {boundary_rules}
- Cross-system dependencies: {cross_system_dependencies}

## Historical Alignment
- Reference samples: {historical_samples}
- Alignment points: {alignment_points}
- Difference points: {diff_points}

## ❓Open Questions
- ❓{open_question_1}
```
