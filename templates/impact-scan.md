# IMPACT_SCAN 阶段模板

固定文案单一来源：IMPACT_SCAN 阶段输出骨架请仅使用本文件对应语言模板。

## zh-CN

```markdown
# IMPACT_SCAN（PRD 范围内深扫 + 历史影响评估）

> 现状画像（目录/技术栈/入口/命名等）请直接引用 `context.<lang>.md`，本文件只覆盖 SPLIT 切片范围内的深扫。

## 切片范围（来自 SPLIT）
- {slice_1}
- {slice_2}

## 现状能力清单（深扫，引用 context 模块 ID）
| 能力点 | 现状结论 | 证据（文件/模块/context 模块ID） | 与 PRD 关系 |
| --- | --- | --- | --- |
| {capability} | {status} | {evidence_path} | 复用/改造/新增/缺失 |

## 接口与数据现状（具体签名 / 表结构 / 迁移脚本）
- 接口现状：{api_status}
- 数据模型现状：{data_model_status}
- 非功能现状：{nfr_status}

## 历史逻辑影响盘点（字段/类型演进场景必填）
| 影响域 | 历史逻辑/任务 | 风险点 | 处理建议 |
| --- | --- | --- | --- |
| {impact_domain} | {legacy_logic} | {risk_point} | {mitigation} |

## 缺口分析
- {gap_1}
- {gap_2}

## 规则矩阵（规则密集场景必填）
| 规则项 | 公式/逻辑 | 输入字段 | 边界条件 | 告警/兜底 |
| --- | --- | --- | --- | --- |
| {rule_item} | {formula} | {inputs} | {boundary} | {fallback} |

## ❓待确认项
- ❓{open_question_1}
```

## en

```markdown
# IMPACT_SCAN (Deep Scan within PRD Scope + Legacy Impact)

> Reference `context.<lang>.md` for project-wide profile (directory / stack / entry / naming); this file only covers deep scan within the SPLIT slices.

## Slice Scope (from SPLIT)
- {slice_1}
- {slice_2}

## Capability Inventory (deep scan, referencing context module IDs)
| Capability | Current Conclusion | Evidence (file/module/context module ID) | Relation to PRD |
| --- | --- | --- | --- |
| {capability} | {status} | {evidence_path} | reuse/modification/new/missing |

## API and Data Baseline (concrete signatures / schemas / migrations)
- API baseline: {api_status}
- Data model baseline: {data_model_status}
- NFR baseline: {nfr_status}

## Legacy Impact Inventory (required for field/type evolution)
| Impact Area | Legacy Logic/Jobs | Risk | Suggested Handling |
| --- | --- | --- | --- |
| {impact_domain} | {legacy_logic} | {risk_point} | {mitigation} |

## Gap Analysis
- {gap_1}
- {gap_2}

## Rule Matrix (required for rule-heavy scenarios)
| Rule Item | Formula/Logic | Input Fields | Boundary | Alert/Fallback |
| --- | --- | --- | --- | --- |
| {rule_item} | {formula} | {inputs} | {boundary} | {fallback} |

## ❓Open Questions
- ❓{open_question_1}
```
