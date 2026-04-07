# prd-to-system-analysis-skill

基于 PRD + 工程现状，按 SDD 流程产出系分文档的 Skill。

## 文件结构

- `SKILL.md`：主流程与约束
- `templates/系分模版.md`：默认系分模板
- `examples.md`：历史样本“输入 PRD -> 输出骨架”示例

## 默认行为（极简版）

- 默认模板：`templates/系分模版.md`
- 大 PRD：先 `SPLIT`（切片映射）再出文档
- 方案阶段：必须给至少 A/B 两案并等待用户选择
- 图形语法：统一 `PlantUML`

## 最小使用示例

```text
请使用 prd-to-system-analysis skill 生成系分：
- prd: /path/to/【PRD】xxx.md
- project_root: /path/to/project
- historical_docs_dir: /path/to/history_docs
```

## 常见场景

### 1) 微粒贷（大 PRD，多系统）

```text
请用该 skill 处理【PRD】微粒贷.md：
先按系统边界拆分（如 lcs / instloancore），
给出 SPLIT 映射表后再继续方案对比和文档产出。
```

### 2) 费率计算器升级（规则密集）

```text
请用该 skill 处理【PRD】费率计算器升级.md：
重点输出规则矩阵（Xcap、未来预估应收、预估减免等）、
灰度开关和兼容策略，再生成系分正文。
```

## 备注

- 若信息不足，文档中应标注 `待确认（原因）`，不得编造。
- 更多输出骨架请看 `examples.md`。
