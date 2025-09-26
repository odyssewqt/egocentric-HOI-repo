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

