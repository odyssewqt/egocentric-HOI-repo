## Egocentric HOI Datasets

| Dataset | Year | Scale | Annotations | Tasks | Paper | Project |
|---------|------|-------|-------------|-------|-------|---------|
| **HOT3D** | 2025 | 833 分钟视频（约 370 万张图像），19 名参与者，33 个物体 | 3D 相机/手部/物体姿态；眼动；手部标注（UmeTrack, MANO）；物体网格（PBR 材质）；动作捕捉 GT | 3D 手部追踪；6 自由度物体姿态估计；未知手中物体的 3D 提升 | [论文](https://arxiv.org/abs/2411.19167) | [项目](https://facebookresearch.github.io/hot3d/) |
| **EgoPressure** | 2025 | 5 小时（约 21 名参与者，8 摄像机设备） | 接触点位置；压力强度；3D 手部网格 | 估计施加压力；手部网格与压力联合估计；手-物交互理解 | [论文](https://arxiv.org/abs/2409.02224) | [项目](https://yiming-zhao.github.io/EgoPressure/) |
| **Ego-IRGBench** | 2025 | 超过 2 万张自我中心图像 | 160 万查询，文本与像素级多模态标注 | 自我中心交互推理与像素级定位 | [论文](https://arxiv.org/abs/2504.01472) | [项目](https://yuggiehk.github.io/annexe/) |
| **EgoMe** | 2025 | 15,804 个视频（7,902 对第一/第三视角） | 视频（第一/第三视角）、眼动（exo-ego 注视）、IMU、多层级标注 | 模仿学习：通过自我中心视角跟随动作 | [论文](https://arxiv.org/abs/2501.19061) | [项目](https://huggingface.co/datasets/HeqianQiu/EgoMe) |
| **HUMOTO** | 2025 | 736 个序列（约 7,875 秒，30 fps） | 人体动作 + 多物体交互，Mocap + 摄像机记录 | 高精度人-物交互用于动作生成、计算机视觉与机器人研究 | [论文](https://arxiv.org/abs/2504.10414) | [项目](https://jiaxin-lu.github.io/humoto/) |
| **HOIGen-1M** | 2025 | 超过 100 万个视频 | 高质量 HOI 视频 + 文本描述 | 大规模人-物交互视频生成 | [论文](https://arxiv.org/abs/2503.23715) | [项目](https://liuqi-creat.github.io/HOIGen.github.io) |
| **HD-EPIC** | 2025 | 41 小时第一视角厨房视频 | 59K 细粒度动作、51K 音频事件、20K 物体移动、37K 物体 mask、数字孪生 3D 对齐 + 注视信息 | 高精度多任务评测：动作识别、视觉问答、声音识别、3D 感知、视频对象分割 | [论文](https://arxiv.org/abs/2502.04144) | [项目](http://hd-epic.github.io/) |
| **IT3DEgo** | 2024 | RGB + 深度视频；逐帧相机位姿；实例级标注（2D & 3D 坐标） | 2D 相机与 3D 世界坐标的实例级标注；每帧相机位姿 | 自我中心视频中的 3D 实例跟踪 | [论文](https://arxiv.org/abs/2312.04117) | [项目](https://github.com/IT3DEgo/IT3DEgo) |
| **VISOR-NVOS** | 2024 | 来自 VISOR 的自我中心视频片段 + 14.6k 叙述 | 分割 mask + 叙述标注的物体标签 | 弱监督叙述驱动的视频对象分割 | [论文](https://openaccess.thecvf.com/content/CVPR2024/papers/Shen_Learning_to_Segment_Referred_Objects_from_Narrated_Egocentric_Videos_CVPR_2024_paper.pdf) | [项目(❌)](https://projectpage.url/) |
| **HOI-Synth** | 2024 | 基于 VISOR、EgoHOS、ENIGMA-51 扩展生成 | 手-物接触状态、边界框、像素级分割掩码 | 自我中心手-物交互检测 | [论文](https://arxiv.org/abs/2312.02672) | [项目](https://fpv-iplab.github.io/HOI-Synth/) |
| **Ego-Exo4D** | 2024 | 1,286 小时视频，740 名参与者，123 个场景 | 第一/第三视角视频、多通道音频、眼动注视、3D 点云、相机位姿、IMU、多种语言描述（含专家讲解） | 精细动作理解、熟练度估计、视角转换、3D 手/身体姿态预测 | [论文](https://arxiv.org/abs/2311.18259) | [项目](http://ego-exo4d-data.org/) |
| **EgoBody3M** | 2024 | 300 万帧，30+ 小时视频 | VR 头显视角视频、多视角隐特征 | 自我中心身体姿态追踪 | [论文](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/10261.pdf) | [项目](https://github.com/facebookresearch/EgoBody3M) |
| **MMG-Ego4D** | 2023 | 源自 Ego4D，包含视频、音频和 IMU 数据，重新标注 | 视频、音频、IMU 数据，多模态对齐标注 | 自我中心动作识别；多模态泛化与跨模态零样本识别 | [论文](https://arxiv.org/abs/2305.07214) | [项目](https://github.com/facebookresearch/MMG_Ego4D) |
| **DogThruGlasses** | 2023 | 150 个视频，73K 帧 | 可变形多目标标注 | 可变形物体多目标跟踪 | [论文](https://mingzhenhuang.com/projects/detracker.html) | [项目](https://mingzhenhuang.com/projects/detracker.html) |
| **AssemblyHands** | 2023 | 300 万图像，49 万自我中心图像 | 高精度 3D 手部关键点标注、动作分类 | 3D 手部姿态估计、动作分类 | [论文](https://arxiv.org/abs/2304.12301) | [项目](https://assemblyhands.github.io/) |
| **EgoGTA / EgoPW-Scene** | 2023 | EgoGTA: 32 万帧，101 个序列 / EgoPW-Scene: 9.2 万帧，30 个序列，5 名参与者 | 3D 人体姿态标注；场景深度图 | 自我中心 3D 人体姿态估计；人体-场景交互评测 | [论文](https://arxiv.org/abs/2212.11684) | [项目](https://people.mpi-inf.mpg.de/~jianwang/projects/sceneego/) |
| **EgoTracks** | 2023 | 长时视频，来自 Ego4D，包含多物体与手部交互 | 物体边界框、身份标签、长时跟踪关联信息 | 自我中心长期视觉对象跟踪 | [论文](https://arxiv.org/abs/2301.03213) | [项目](https://github.com/EGO4D/episodic-memory/tree/main/EgoTracks) |
| **EgoObjects** | 2023 | Pilot: 9K+ 视频，250 名参与者，4 台设备 | 65 万+ 物体标注，368 类别，14K+ 独立实例，实例级 ID | 自我中心对象理解、实例级 & 类别级检测、持续学习检测 | [论文](https://arxiv.org/abs/2309.08816) | [项目](https://github.com/facebookresearch/EgoObjects) |
| **EgoPCA** | 2023 | 大规模预训练集 + 平衡测试集 | 手-物交互标注、动作标签 | 自我中心手-物交互理解 | [论文](https://arxiv.org/abs/2309.02423) | [项目](https://mvig-rhos.com/ego_pca) |
| **HoloAssist** | 2023 | 166 小时，350 对指导员-参与者 | 多模态标注：动作、对话、手部位置 | 错误检测、干预类型预测、手部轨迹预测 | [论文](https://arxiv.org/abs/2309.17024) | [项目](https://holoassist.github.io/) |
| **EgoPAT3D** | 2022 | 超过 100 万帧 RGB-D + IMU 数据 | 2D/3D 目标位置；动作标签 | 自我中心动作目标预测（3D） | [论文](https://arxiv.org/abs/2203.13116) | [项目](https://ai4ce.github.io/EgoPAT3D/) |
| **Ego4D** | 2022 | 3,670 小时视频，931 名参与者，74 个地点，9 个国家 | 视频帧，音频，环境 3D 网格，眼动，立体视觉，多视角同步 | 记忆查询；手-物体操作分析；音视频对话；社交交互；动作预测 | [论文](https://arxiv.org/abs/2110.07058) | [项目](https://ego4d-data.org/) |
| **HOI4D** | 2022 | 240 万 RGB-D 帧，4000 个序列，610 个房间，4 名参与者，800 个对象实例，16 类 | 全景分割；动作分割；3D 手部姿态；类别级物体姿态；手部动作；物体网格；场景点云 | 4D 动态点云语义分割；类别级物体姿态跟踪；自我中心动作分割 | [论文](https://arxiv.org/abs/2203.01577) | [项目](https://hoi4d.github.io/) |
| **N-EPIC-Kitchens** | 2022 | 扩展自 EPIC-Kitchens，事件摄像机数据 | RGB 视频 + 事件摄像机数据 | 自我中心动作识别 | [论文](https://arxiv.org/abs/2112.03596) | [项目](https://github.com/EgocentricVision/N-EPIC-Kitchens) |
| **EgoPW** | 2022 | 大规模 in-the-wild 数据，头戴鱼眼相机 + 外部辅助相机 | 3D 人体姿态 | 自我中心 3D 人体姿态估计 | [论文](https://arxiv.org/abs/2201.07929) | [项目](https://opendatalab.com/OpenDataLab/EgoPW) |
| **EgoHOS** | 2022 | 11,243 张图像 | 像素级手-物分割及接触边界 | 手-物分割，手部状态分类，视频活动识别，3D 重建 | [论文](https://arxiv.org/abs/2208.03826) | [项目](https://github.com/owenzlz/EgoHOS) |
| **H2O** | 2021 | 多视角 RGB-D 视频，双手操作物体 | 左/右手 3D 姿态、物体 6D 姿态、交互标签、物体类别、相机位姿、物体网格、场景点云 | 自我中心手-物交互识别、双手姿态估计、6D 物体姿态估计 | [论文](https://arxiv.org/abs/2104.11181) | [项目](https://taeinkwon.com/projects/h2o/) |
| **MECCANO** | 2021 | 工业场景：20 名参与者，100+ 个视频（摩托车装配）| 动作时间段；活跃物体边界框 | 动作识别；活跃物体检测；活跃物体识别；自我中心 HOI 检测 | [论文](https://arxiv.org/abs/2010.05654) | [项目](https://iplab.dmi.unict.it/MECCANO) |

## Egocentric HOI Datasets by Modalities

根据数据集模态类别对数据集进行整理并粗略分类，因任务不同，数据集包含的数据模态也不同，可以发现数据集主要集中在以下几个模态：

- `RGB/Video`：图像RGB数据或视频帧数据，主要做检测、识别、分割、生成等任务  
- `Depth/PointCloud`：深度数据，RGB-D、相机位姿、动态点云、场景深度、手/物体6D位姿，主要做3D重建、位姿估计、跟踪等任务  
- `3D Pose/Mesh`：3D手/人体姿态数据，物体交互数据，比如HOT3D包括3D手、物体、mesh等，强调手/身体/物体的三维姿态标注。  
- `Multimodel`：图像和视频数据、音频数据、gaze数据、IMU数据、文本及其语音数据(比如对话数据)，数据集规模大，做感知、理解、推理等任务。
- `other`：其他的数据，如EgoPressure数据集使用压力传感器，包含压力数据。N-EPIC-Kitchens数据集使用Event camera，捕捉运动物体数据。

---

| Dataset | RGB/Video | Depth/PointCloud | 3D Pose/Mesh | Audio | Eye Gaze | IMU | Text |
|---------|-----------|------------------|--------------|-------|----------|-----|---------------|
| HOT3D (2025)        | ✅ | ❌ | ✅ (hand/object mesh) | ❌ | ✅ | ❌ | ❌ |
| EgoPressure (2025)  | ✅ | ❌ | ✅ (hand mesh) | ❌ | ❌ | ❌ | ❌ |
| Ego-IRGBench (2025) | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| EgoMe (2025)        | ✅ | ❌ | ❌ | ❌ | ✅ | ✅ | ❌ |
| HUMOTO (2025)       | ✅ | ❌ | ✅ (motion capture) | ❌ | ❌ | ❌ | ❌ |
| HOIGen-1M (2025)    | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| HD-EPIC (2025)      | ✅ | ✅ (3D align) | ✅ | ✅ | ✅ | ❌ | ✅ |
| IT3DEgo (2024)      | ✅ | ✅ | ✅ (2D+3D coords) | ❌ | ❌ | ❌ | ❌ |
| VISOR-NVOS (2024)   | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| HOI-Synth (2024)    | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| Ego-Exo4D (2024)    | ✅ | ✅ (point cloud) | ✅ (pose) | ✅ | ✅ | ✅ | ✅ |
| EgoBody3M (2024)    | ✅ | ❌ | ✅ (body pose) | ❌ | ❌ | ❌ | ❌ |
| MMG-Ego4D (2023)    | ✅ | ❌ | ❌ | ✅ | ❌ | ✅ | ❌ |
| DogThruGlasses (2023)| ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| AssemblyHands (2023)| ✅ | ❌ | ✅ (hand pose) | ❌ | ❌ | ❌ | ❌ |
| EgoGTA/EgoPW-Scene (2023)| ✅ | ✅ (depth) | ✅ (pose) | ❌ | ❌ | ❌ | ❌ |
| EgoTracks (2023)    | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| EgoObjects (2023)   | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| EgoPCA (2023)       | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| HoloAssist (2023)   | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ |
| EgoPAT3D (2022)     | ✅ | ✅ (RGB-D) | ❌ | ❌ | ❌ | ✅ | ❌ |
| Ego4D (2022)        | ✅ | ✅ (3D env mesh) | ✅ (pose) | ✅ | ✅ | ✅ | ✅ |
| HOI4D (2022)        | ✅ | ✅ (RGB-D+point cloud) | ✅ (hand pose, object pose) | ❌ | ❌ | ❌ | ❌ |
| N-EPIC-Kitchens (2022)| ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| EgoPW (2022)        | ✅ | ❌ | ✅ (human pose) | ❌ | ❌ | ❌ | ❌ |
| EgoHOS (2022)       | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |
| H2O (2021)          | ✅ | ✅ (RGB-D+point cloud) | ✅ (hand+object pose) | ❌ | ❌ | ❌ | ❌ |
| MECCANO (2021)      | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ❌ |


## 4 Datasets and Evaluation Metrics for Egocentric HOI
The validity of vision-based egocentric human-computer interaction (HOI) research methods depends heavily on the quality and diversity of datasets, as well as robust evaluation metrics. This chapter explores public datasets that have played a key role in the development of the field. We then present some evaluation metrics for assessing the performance of various methods, focusing on interaction detection, prediction and reconstruction tasks. This chapter provides an important foundation for understanding how datasets and metrics influence progress in self-centered HOI research.

**4.1 Datasets**

The effectiveness of self-centered vision-based human-computer interaction (HOI) research methods is highly dependent on the quality and diversity of datasets and robust evaluation metrics. In this part of the narrative, we begin with a listing of some classic datasets that have been validated on a wide range of methods, as shown in **Table 1**, and for some completely new methods, we summarize them afterwards.

**Table 1 Dataset**

---

| Dataset | Year | Data Size(h/frames) | Action Classes | Action Instances | Bounding Boxes | Includes Video | Participants | Ego |
|---------|------|---------------------|----------------|------------------|----------------|----------------|--------------|-----|
| HOT3D | 2025 | 13.9h | - | - | -  | ✅ | 19 | ✅ |
| EgoPressure | 2025 | 5h | - | - | - | ✅ | 21 | ✅ |
| EgoMe | 2025 | 82.8h | 184 | - | - | ✅ | 37 | ✅ |
| HD-EPIC | 2025 | 41h | 69 | 59k | 37k | ✅ | 9 | ✅ |
| Ego-IRGBench | 2025 | 120h | 32 | - | 1.5M | ✅ | 152 | ✅ |
| HOIGen-1M | 2025 | 2.2k h | 7k+ | - | - | ✅ | - | ✅ |
| IT3DEgo | 2024 | 4.2h | - | - | 100k | ✅ | 3 | ✅ | 
| Ego-Exo4D | 2024 | 1286h | 689 | 5035 | 13M | ✅ | 740 | ✅ |
| EgoExoLearn | 2024 | 120h | 95 | - | - | ✅ | 20 | ✅ |
| EgoBody3M | 2024 | 30+h | - | - | - | ✅ | - | ✅ |
| EgoTracks | 2023 | 602h | - | - | - | ✅ | - | ✅ |
| EgoObjects | 2023 | 9K+ frames | 368 | 14k | 650k | ✅ | 250 | ✅ |
| Ego4D | 2022 | 3670h | 113 | - | - | ✅ | 931 | ✅ |
| HOI4D | 2022 | 2.4M frames | 16 | 500 | - | ✅ | 9 | ✅ |
| EgoHOS | 2022 | 11k frames | 300+ | - | - | ✅ | 37 | ✅ |
| Assembly101 | 2022 | 513h | 1380 | 1M | - | ✅ | 53 | ✅ |
| H2O | 2021 | 158.8h | - | - | 571645 | ✅ | - | ✅ |
| EGTEA Gaze+ | 2020 | 28h | 106 | 10321 | - | ✅ | 32 | ✅ |
| EPIC-KITCHENS | 2018 | 55h | 149 | 50 | 454255 | ✅ | 32 | ✅ |

1. **EPIC-KITCHENS**

EPIC-KITCHENS is a large-scale egocentric video dataset capturing natural daily activities in kitchen environments. Recorded by 32 participants across 4 countries, representing 10 nationalities, the dataset spans 55 hours of video (11.5M frames) and reflects diverse cooking habits and styles. The recordings are nonscripted, capturing interactions with objects and fine-grained actions from a first-person viewpoint. The dataset is densely annotated with 39.6K action segments and 454.2K object bounding boxes, with participants narrating their own actions post-recording to capture true intention. EPIC-KITCHENS supports multiple benchmarks, including action recognition, object interaction, and action anticipation, and provides evaluation splits for both seen and unseen kitchens. Its multimodal nature and temporal annotations make it a key resource for studying egocentric perception and fine-grained human-object interactions.

2. **EGTEA Gaze+**

EGTEA Gaze+ is a large-scale first-person (FPV) video dataset designed to support research on gaze estimation, hand segmentation, and action recognition. It contains 86 recording sessions from 32 participants performing 7 different cooking tasks, totaling approximately 28 hours of video at a resolution of 1280×920 and a frame rate of 24 Hz. Each session includes synchronized HD video, 44 kHz audio, 30 Hz binocular gaze tracking data, frame-level action annotations, and sparsely sampled hand masks. The dataset comprises 15,000 hand masks and 10,321 action instances covering 106 action categories, with an average action duration of 4.2 seconds, totaling over 1 million frames with gaze annotations. EGTEA Gaze+ is distinguished by its simultaneous annotations of hand poses, gaze, and actions, offering a comprehensive benchmark for first-person visual perception and interaction modeling tasks.

3. **H2O**

H2O is a large-scale egocentric RGB-D dataset collected in indoor environments, focusing on bimanual human-object interactions. The dataset contains 571,645 frames captured from four participants performing 36 distinct action classes across three different environments. Each frame is annotated with accurate left and right hand poses, 6D object poses, camera poses, and action labels. Additionally, MANO hand fits are provided for both hands, along with high-quality object meshes and scene point clouds reconstructed from the synchronized RGB-D data. H2O enables comprehensive study of egocentric manipulation, including hand-object dynamics, object tracking, and scene understanding.

4. **Assembly101**

Assembly101 is a large-scale procedural activity dataset capturing 4,321 videos of participants assembling and disassembling 101 “take-apart” toy vehicles. The recordings feature rich, natural variations in action ordering, mistakes, and corrections, as participants perform tasks without fixed instructions. Assembly101 provides both multi-view data (8 static cameras and 4 egocentric cameras) and dense annotations, including over 100K coarse and 1M fine-grained action segments, as well as 18M 3D hand poses. The dataset supports benchmarks for action recognition, anticipation, temporal segmentation, and a novel task of mistake detection. Its unique design and diverse annotations enable research on cross-view generalization, long-tailed action distributions, and pose versus appearance modeling.

5. **EgoHOS**

EgoHOS is a labeled egocentric image dataset containing 11,243 frames with per-pixel segmentation of hands and objects involved in interactions during diverse daily activities. The dataset uniquely provides detailed hand-object contact boundaries, enabling fine-grained understanding of human-object interactions. A context-aware compositional data augmentation technique is introduced to improve generalization to out-of-distribution egocentric videos, such as YouTube content. EgoHOS supports downstream applications including hand state classification, video activity recognition, 3D mesh reconstruction of hand-object interactions, and video inpainting of hand-object foregrounds, making it a foundational resource for egocentric vision research.

6. **HOI4D**

HOI4D is a large-scale 4D egocentric dataset designed to advance research on category-level human-object interactions. The dataset contains 2.4 million RGB-D frames spanning 4,000 sequences, collected from 4 participants interacting with 800 object instances across 16 categories in 610 indoor environments. Each frame is annotated with panoptic segmentation, motion segmentation, 3D hand poses, category-level object poses, and hand actions. Additionally, reconstructed object meshes and scene point clouds are provided. HOI4D supports benchmarking on three tasks: semantic segmentation of 4D dynamic point clouds, category-level object pose tracking, and egocentric action segmentation with diverse interaction targets.

7. **Ego4D**

Ego4D is a large-scale egocentric video dataset and benchmark suite designed to advance first-person perception research. It contains 3,670 hours of daily-life activity videos captured by 931 participants across 74 locations in 9 countries, covering a wide range of scenarios including household, workplace, outdoor, leisure, and more. The dataset follows strict privacy and ethics protocols, with consenting participants and robust de-identification procedures. Ego4D provides rich multimodal data, including audio, 3D environment meshes, eye gaze, stereo, and synchronized multi-camera egocentric views. The benchmark suite includes tasks for understanding past experiences (episodic memory queries), present interactions (hand-object manipulation, audio-visual conversation, social interactions), and future activities (activity forecasting).

8. **EgoObjects**

EgoObjects is a large-scale egocentric dataset designed for fine-grained object understanding in first-person vision. The pilot version consists of more than 9,000 videos recorded by 250 participants across 50+ countries using four wearable devices. It includes over 650,000 object annotations spanning 368 categories and more than 14,000 unique object instances. Unlike prior datasets that focus only on object category labels, EgoObjects provides instance-level identifiers, enabling the study of the same object under diverse backgrounds, lighting, distances, camera motions, and surrounding contexts. A multi-stage federated annotation process was developed to ensure high-quality labeling while accommodating the dataset’s growth.

9. **EgoTracks**

EgoTracks is a large-scale dataset for long-term egocentric visual object tracking, derived from Ego4D. It contains 22,028 annotated tracks from 5,708 videos, following the Ego4D Visual Queries split. Unlike conventional third-person datasets, EgoTracks emphasizes the unique challenges of egocentric video, including frequent occlusions, large viewpoint changes, and long-term re-detection. It provides a new benchmark for robust egocentric tracking, together with a baseline model, EgoSTARK.

10. **EgoBody3M**

EgoBody3M is the first large-scale real-image dataset for egocentric body tracking in VR/AR settings. Collected with realistic VR headset configurations, it contains over 30 hours of recordings and 3 million frames with diverse subjects and motions. Unlike prior methods that either rely on under-constrained signals (e.g., headset and controller poses) or impractical multi-camera setups, EgoBody3M enables controllerless egocentric tracking using only the headset’s SLAM cameras. It serves as a benchmark for accurate and smooth full-body pose estimation, supporting real-time applications on VR devices.

11. **EgoExoLearn**

EgoExoLearn is a large-scale dataset designed to explore cross-view activity learning, where egocentric executions are guided by exocentric demonstrations. The dataset contains 120 hours of egocentric and demonstration videos, captured across 5 types of daily tasks (e.g., cooking in 4 different kitchens) and 3 types of specialized laboratory tasks (e.g., solid-phase peptide synthesis in 3 labs). Alongside the videos, the dataset provides high-quality gaze data and multimodal annotations, supporting benchmarks on cross-view association, action planning, and skill assessment.

12. **Ego-Exo4D**

Ego-Exo4D is a large-scale multimodal and multiview dataset capturing skilled human activities from both egocentric and exocentric perspectives. The dataset comprises 1,286 hours of video recorded from 740 participants across 13 cities and 123 natural scene contexts, covering activities such as sports, music, dance, and bike repair. Each recording ranges from 1 to 42 minutes, providing long-form interactions. Ego-Exo4D includes multimodal signals such as multichannel audio, eye gaze, 3D point clouds, camera poses, IMU data, and multiple paired language descriptions, including expert commentary tailored to the activity domain. The dataset supports benchmark tasks for fine-grained activity understanding, skill/proficiency estimation, cross-view translation, and 3D hand/body pose estimation.

13. **IT3DEgo**

IT3DEgo is a multimodal egocentric dataset captured in ten diverse indoor environments, including kitchens, garages, offices, and laboratories. Three participants performed naturalistic tasks such as cooking, repairing, and writing, interacting with multiple object instances. The dataset contains 50 recordings, each lasting over 5 minutes (~10K frames) and featuring at least five object instances appearing at multiple 3D locations. Videos were captured using HoloLens2, equipped with an RGB camera, a depth sensor, and four grayscale cameras, with all sensor streams synchronized to 30 fps. Coarse 3D scene meshes are provided for each environment.

14. **HOIGen-1M**

HOIGen-1M is the first large-scale dataset specifically designed for human-object interaction (HOI) video generation, addressing the scarcity of accurately captioned HOI videos for text-to-video (T2V) models. The dataset is curated from both HOI-specific and general video sources: initially, three HOI perception datasets—BEHAVE, InterCap, and HOI4D—are selected for their high-resolution clips containing at least one HOI instance, yielding 22K valid videos. To further expand the dataset, the collection is augmented with five large-scale general video datasets used in T2V generation: Panda-70M, ViSR, Mixkit, Pixabay, and Pexels (as introduced in OpenSoraPlan), resulting in roughly 80 million raw videos. Videos are first curated automatically using a multimodal large language model (MLLM) framework and then manually cleaned to ensure quality.

15. **Ego-IRGBench**

Ego-IRGBench is a large-scale egocentric RGB-D action recognition dataset containing 1.2 million frames from 152 participants performing 32 daily activities (e.g., cooking, cleaning, social interactions). Videos are captured at 30 FPS with RGB-D alignment (640×480), totaling 120 hours of recordings. The dataset provides dense annotations for object bounding boxes (1.5M+ instances), hand poses (21 keypoints per hand), and action segments (avg. 8.7 s). It also includes 3D scene point clouds from depth data across 15 indoor environments and aligned IMU signals at 100 Hz. Ego-IRGBench supports multi-modal learning and enables evaluation under real-world challenges such as occlusion (~23% frames) and viewpoint variations.

16. **HD-EPIC**

HD-EPIC is a high-detail egocentric kitchen dataset containing 41 hours of unscripted video from 9 home kitchens, capturing 69 recipes. The dataset includes 59K fine-grained actions, 51K audio events, 20K object movements, and 37K object masks lifted to 3D, with 263 annotations per minute on average. All annotations are 3D-grounded via digital twins of kitchen fixtures, object locations, and gaze information. HD-EPIC also provides a challenging VQA benchmark with 26K questions evaluating recipe understanding, ingredients and nutrition recognition, fine-grained actions, object motion, gaze reasoning, and 3D perception. This makes HD-EPIC the first in-the-wild egocentric kitchen dataset combining natural recordings with lab-quality detailed annotations.

17. **EgoMe**

EgoMe is a large-scale egocentric dataset designed for human imitation learning from the imitator’s perspective. It contains 7,902 paired exo-ego videos (15,804 total videos) covering diverse daily behaviors in real-world scenarios. Each pair consists of an exocentric view of the demonstrator and an egocentric view of the imitator performing the same actions. EgoMe provides exo-ego eye gaze, IMU data, and multi-level annotations to support modeling the correlation between observation and imitation. The dataset also includes a suite of benchmarks to advance research in robotic imitation learning, demonstrating clear advantages over existing ego-exo datasets.

18. **EgoPressure**

EgoPressure is a novel egocentric dataset designed to study touch contact and applied pressure in human-object interactions. The dataset contains 5 hours of recordings from 21 participants, captured with an 8-camera rig (1 head-mounted, 7 stationary Kinect cameras) providing RGB images and depth maps at 30 Hz. It includes high-resolution pressure intensity annotations at contact points and accurate hand pose meshes reconstructed via a multi-view, sequence-based optimization method. Baseline models are provided for estimating pressure from RGB images, with and without hand pose information, as well as for joint hand pose and pressure estimation. EgoPressure enables detailed analysis of hand-object interactions and is valuable for research in AR/VR and robotic manipulation.

19. **HOT3D**

HOT3D is a publicly available egocentric dataset for 3D hand and object tracking, comprising 19 participants interacting with 33 rigid objects over 833 minutes of recordings (3.7M+ images). The dataset provides synchronized multi-view RGB/monochrome images, eye gaze signals, scene point clouds, and 3D poses of cameras, hands, and objects. Hand annotations are provided in UmeTrack and MANO formats, while objects are represented as high-quality 3D meshes.