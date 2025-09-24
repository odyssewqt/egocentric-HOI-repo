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
- `Abstract`：简洁摘要
- `Contribution`：贡献类型

示例表格：

| Year | Title | Venue |  Abstract | Contribution |
|------|-------|-------|-----------|-------------|
| 2022 | **HOI4D: A Large-Scale 4D Egocentric Dataset for Category-Level Human-Object Interaction** | CVPR | 提出 HOI4D，一个大规模4D自我中心数据集，旨在推动类别级人体-物体交互研究。数据集包含2.4M RGB-D视频帧，4000序列，4名参与者与800个不同物体实例（16类）在610个室内房间中的交互。提供帧级全景分割、动作分割、3D手部姿态、类别级物体位姿及手部动作标注，并附物体网格与场景点云。基于HOI4D，建立了三类基准任务：4D 动态点云序列语义分割、类别级物体位姿跟踪和自我中心动作分割。分析显示HOI4D对现有方法提出挑战并提供丰富研究机会。 | 数据集发布 |

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
