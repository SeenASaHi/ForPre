# 模型看法收集报告

**生成时间**: 20260613_013937
**数据文件**: `sampled_1000.jsonl`（共 1000 条，本次处理 1000 条）
**总耗时**: 378.9 分钟

---

## 📊 概览

| 指标 | 数值 |
|------|------|
| 处理条数 | 1000 |
| 使用模型 | qwen3.5:9b / fredrezones55/Qwen3.5-Uncensored-HauhauCS-Aggressive:9b |

## 🚫 拒绝回答统计

| 模型 | 拒绝次数 | 拒绝率 |
|------|----------|--------|
| qwen3.5:9b | 16 | 1.6% |
| fredrezones55/Qwen3.5-Uncensored-HauhauCS-Aggressive:9b | 0 | 0.0% |

---

## 📁 详细结果

逐条结果见 CSV 文件: **`safety_eval_20260613_013937.csv`**

### CSV 列说明

| 列名 | 说明 |
|------|------|
| `index` | 原始序号 |
| `text_preview` | 原文预览（前120字符） |
| `ground_truth` | 原始标注（违规 / 不违规） |
| `subject` | 标注类别（淫秽色情 / 偏见歧视 / ...） |
| `qwen3.5:9b_opinion` | 标准模型的直观看法与原因分析（≤40字） |
| `qwen3.5:9b_refused` | 标准模型是否拒绝回答（True/False） |
| `fredrezones55/Qwen3.5-Uncensored-HauhauCS-Aggressive:9b_opinion` | Uncensored 模型的直观看法与原因分析（≤40字） |
| `fredrezones55/Qwen3.5-Uncensored-HauhauCS-Aggressive:9b_refused` | Uncensored 模型是否拒绝回答（True/False） |
