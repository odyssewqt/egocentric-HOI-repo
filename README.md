# Egocentric HOI Repo

📚 本仓库系统整理了 **近 5 年（2020–2025）Egocentric Human-Object Interaction (HOI)** 领域的论文和数据集。

---

## 目录

- [概述](#概述)
- [论文列表](#论文列表)
- [数据集列表](#数据集列表)

---

## 概述

Egocentric HOI 研究聚焦于 **第一视角的人-物交互**，主要研究方向包括：

1. **姿态估计（Pose Estimation）**：预测手部或身体关键点  
2. **动作识别（Action Recognition）**：识别用户当前动作  
3. **HOI检测（HOI Detection）**：判断人-物交互关系 `(person, verb, object)`  
4. **交互预测（Anticipation and Motion Forecasting Model）**：手-物空间的位置和轨迹预测以及预测接下来的动作  
5. **多模态融合（Multimodal Fusion）**：整合 RGB、深度、光流、手部关键点等信息  
6. **高级任务**：三维重建（3D Reconstruction）、交互建模（Interaction Modeling）

---

## 论文列表

论文列表保存在 `papers/papers.csv`，包含字段：

- `year`：发表年份  
- `title`：论文题目  
- `venue`：发表期刊/会议  
- `publisher`：出版方  

示例表格：

| Year | Title | Venue | Publisher |
|------|-------|-------|-----------|
| 2023 | Egocentric HOI Recognition via Hand-Object Modeling | CVPR | IEEE |
| 2022 | First-Person Action Detection with Multimodal Fusion | ICCV | IEEE |

---

## 数据集列表

数据集列表保存在 `datasets/datasets.csv`，包含字段：

- `name`：数据集名称  
- `year`：发布年份  
- `size`：数据规模  
- `annotation`：标注类型  
- `task`：适用任务（动作识别 / HOI检测 / 姿态估计）  
- `paper_link`：论文链接  
- `official_link`：官方数据集链接  

示例表格：

| Name | Year | Size | Annotation | Task | Paper Link | Official Link |
|------|------|------|------------|------|------------|---------------|
| EPIC-KITCHENS | 2018 | 55 hrs video | Action + Object | HOI Detection | [Paper](https://arxiv.org/abs/1806.04458) | [Dataset](http://epic-kitchens.github.io) |

---
