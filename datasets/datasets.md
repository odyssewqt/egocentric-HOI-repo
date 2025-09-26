## Egocentric HOI Datasets

| Dataset | Year | Scale | Annotations | Tasks | Paper | Project |
|---------|------|-------|-------------|-------|-------|---------|
| **HOT3D** | 2025 | 833 min video (~3.7M images), 19 subjects, 33 objects | 3D camera/hand/object poses; Eye gaze; Hand annotations (UmeTrack, MANO); Object meshes with PBR; Motion-capture GT | 3D hand tracking; 6DoF object pose estimation; 3D lifting of unknown in-hand objects | [Paper](https://arxiv.org/abs/2411.19167) | [Project](https://facebookresearch.github.io/hot3d/) |
| **EgoPressure** | 2025 | 5 hours (~21 participants, 8-camera rig) | Touch contact points; Pressure intensity; 3D hand meshes | Estimating applied pressure; Joint hand mesh and pressure estimation; Hand-object interaction understanding | [Paper](https://arxiv.org/abs/2409.02224) | [Project](https://yiming-zhao.github.io/EgoPressure/) |
| **Ego-IRGBench** | 2025 | 20k+ egocentric images | 1.6M queries，文本与像素级多模态标注 | Egocentric interaction reasoning and pixel grounding | [Paper](https://arxiv.org/abs/2504.01472) | [Project](https://yuggiehk.github.io/annexe/) |
| **EgoMe** | 2025 | 15,804 videos (7,902 exo-ego pairs) | 视频（第一/第三视角）、眼动（exo-ego gaze）、IMU、多层级标注 | Imitation learning: following via egocentric view | [Paper](https://arxiv.org/abs/2501.19061) | [Project](https://huggingface.co/datasets/HeqianQiu/EgoMe) |
| **HUMOTO** | 2025 | 736 sequences (~7,875秒, 30 fps) | 人体动作 + 多物体交互，Mocap + 相机记录 | High-fidelity human-object interaction for motion generation, CV, and robotics | [Paper](https://arxiv.org/abs/2504.10414) | [Project](https://jiaxin-lu.github.io/humoto/) |
| **HOIGen-1M** | 2025 | 1M+ 视频 | 高质量 HOI 视频 + 文本描述 | Large-scale dataset for human-object interaction video generation | [Paper](https://arxiv.org/abs/2503.23715) | [Project](https://liuqi-creat.github.io/HOIGen.github.io) |
| **HD-EPIC** | 2025 | 41 小时第一视角厨房视频 | 59K 细粒度动作、51K 音频事件、20K 物体移动、37K 物体 mask、数字孪生 3D 对齐 + 注视信息 | 高精度多任务评测，包括动作识别、VQA、声音识别、3D 感知和视频对象分割 | [Paper](https://arxiv.org/abs/2502.04144) | [Project](http://hd-epic.github.io/) |
| **IT3DEgo** | 2024 | RGB + Depth 视频；逐帧相机位姿；实例级标注（2D & 3D 坐标） | Instance-level annotations in 2D camera & 3D world coordinates; Camera pose per frame | 3D Instance Tracking from egocentric video | [Paper](https://arxiv.org/abs/2312.04117) | [Project](https://github.com/IT3DEgo/IT3DEgo) |
| **VISOR-NVOS** | 2024 | Egocentric video clips from VISOR + 14.6k narrations | Segmentation masks (from VISOR) + narration-based object labels | Weakly-supervised Narration-based Video Object Segmentation (NVOS) | [Paper](https://openaccess.thecvf.com/content/CVPR2024/papers/Shen_Learning_to_Segment_Referred_Objects_from_Narrated_Egocentric_Videos_CVPR_2024_paper.pdf) | [Project(❌)](https://projectpage.url/) |
| **HOI-Synth** | 2024 | 基于 VISOR、EgoHOS、ENIGMA-51 扩展生成 | 手-物接触状态、边界框、像素级分割掩码 | Egocentric Hand-Object Interaction Detection | [Paper](https://arxiv.org/abs/2312.02672) | [Project](https://fpv-iplab.github.io/HOI-Synth/) |
| **Ego-Exo4D** | 2024 | 1,286 小时视频，740 名参与者，123 场景 | Egocentric & Exocentric 视频、多通道音频、眼动注视、3D 点云、相机位姿、IMU、多种语言描述（含专家讲解） | 精细动作理解、熟练度估计、视角间转换、3D 手/身体姿态预测 | [Paper](https://arxiv.org/abs/2311.18259) | [Project](http://ego-exo4d-data.org/) |
| **EgoBody3M** | 2024 | 3,000,000 帧，30+ 小时视频 | VR 头显视角视频、多视角隐特征 | Egocentric 身体姿态追踪 | [Paper](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/10261.pdf) | [Project](https://github.com/facebookresearch/EgoBody3M) |
| **MMG-Ego4D** | 2023 | 源自 Ego4D，包含视频、音频和IMU数据，重新标注 | 视频、音频、惯性测量（IMU）数据，多模态对齐标注 | Egocentric action recognition；多模态泛化（missing modality/generalization & cross-modal zero-shot） | [Paper](https://arxiv.org/abs/2305.07214) | [Project](https://github.com/facebookresearch/MMG_Ego4D) |
| **DogThruGlasses** | 2023 | 150 视频, 73K 帧 | 可变形多目标标注 | 可变形物体多目标跟踪 | [Paper](https://mingzhenhuang.com/projects/detracker.html) | [Project](https://mingzhenhuang.com/projects/detracker.html) |
| **AssemblyHands** | 2023 | 3.0M 图像，49万自我中心图像 | 3D手部姿态标注（高精度关键点）、动作分类 | 3D手部姿态估计、动作分类 | [Paper](https://arxiv.org/abs/2304.12301) | [Project](https://assemblyhands.github.io/) |
| **EgoGTA / EgoPW-Scene** | 2023 | 320 K frames in 101 different sequences / 92 K frames in total, which are distributed in 30 sequences performed by 5 actors | 3D人体姿态标注；场景深度图 | 自我中心3D人体姿态估计；人体-场景交互评测 | [Paper](https://arxiv.org/abs/2212.11684) | [Project](https://people.mpi-inf.mpg.de/~jianwang/projects/sceneego/) |
| **EgoTracks** | 2023 | 长时视频，来自 Ego4D，包含多物体与手部交互 | 物体边界框、身份标签、长时跟踪关联信息 | 第一视角长期视觉物体跟踪 | [Paper](https://arxiv.org/abs/2301.03213) | [Project](https://github.com/EGO4D/episodic-memory/tree/main/EgoTracks) |
| **EgoObjects** | 2023 | Pilot: 9K+ videos, 250 participants, 4 devices | 650K+ object annotations, 368 categories, 14K+ unique instances, instance-level IDs | Egocentric object understanding, instance-level & category-level detection, continual learning detection | [ICCV 2023](https://arxiv.org/abs/2309.08816) | [Project](https://github.com/facebookresearch/EgoObjects) |
| **EgoPCA** | 2023 | 大规模预训练集 + 平衡测试集 | 手-物交互标注、动作标签 | 第一视角手-物交互理解 (Ego-HOI) | [Paper](https://arxiv.org/abs/2309.02423) | [Project](https://mvig-rhos.com/ego_pca) |
| **HoloAssist** | 2023 | 166 hours, 350 instructor-performer pairs | 多模态标注：动作、对话、手部位置 | 错误检测、干预类型预测、手部轨迹预测 | [Paper](https://arxiv.org/abs/2309.17024) | [Project](https://holoassist.github.io/) |
| **EgoPAT3D** | 2022 | >1M frames RGB-D + IMU | 2D/3D目标位置；动作标签 | 自我中心动作目标预测（3D） | [Paper](https://arxiv.org/abs/2203.13116) | [Project](https://ai4ce.github.io/EgoPAT3D/) |
| **Ego4D** | 2022 | 3,670小时视频，931名参与者，74地点，9国家 | 视频帧，音频，环境3D网格，眼动，立体视觉，多视角同步 | 记忆查询；手-物体操作分析；音视频对话；社交交互；动作预测 | [Paper](https://arxiv.org/abs/2110.07058) | [Project](https://ego4d-data.org/) |
| **HOI4D** | 2022 | 2.4M RGB-D帧，4000序列，610房间，4参与者，800对象实例，16类别 | 全景分割；动作分割；3D手部姿态；类别级物体位姿；手部动作；物体网格；场景点云 | 4D动态点云语义分割；类别级物体位姿跟踪；自我中心动作分割 | [Paper](https://arxiv.org/abs/2203.01577) | [Project](https://hoi4d.github.io/) |
| **N-EPIC-Kitchens** | 2022 | 扩展自 EPIC-Kitchens，事件摄像机数据 | RGB 视频 + Event Camera 事件流 | Egocentric Action Recognition | [Paper](https://arxiv.org/abs/2112.03596) | [Project](https://github.com/EgocentricVision/N-EPIC-Kitchens) |
| **EgoPW** | 2022 | 大规模 in-the-wild 数据，头戴鱼眼相机 + 外部辅助相机 | 3D 人体姿态 | Egocentric 3D Human Pose Estimation | [Paper](https://arxiv.org/abs/2201.07929) | [Project](https://opendatalab.com/OpenDataLab/EgoPW) |
| **EgoHOS** | 2022 | 11,243 images | Pixel-wise hand-object segmentation with contact boundaries | Hand-object segmentation, hand state classification, video activity recognition, 3D reconstruction | [Paper](https://arxiv.org/abs/2208.03826) | [Project](https://github.com/owenzlz/EgoHOS) |
| **H2O** | 2021 | 多视角 RGB-D 视频，双手操作物体 | 左/右手 3D 姿态、物体 6D 姿态、交互标签、物体类别、相机位姿、物体网格、场景点云 | 第一视角手-物体交互识别、双手姿态估计、6D 物体姿态估计 | [Paper](https://arxiv.org/abs/2104.11181) | [Project](https://taeinkwon.com/projects/h2o/) |
| **MECCANO** | 2021 | 工业场景: 20 participants, 100+ videos (motorbike assembly) | Temporal action segments; Active object bounding boxes | Action recognition; Active object detection; Active object recognition; Egocentric HOI detection | [Paper](https://arxiv.org/abs/2010.05654) | [Project](https://iplab.dmi.unict.it/MECCANO) |

## Egocentric HOI Datasets by Modalities

根据数据集模态类别对数据集进行整理并粗略分类，因任务不同，数据集包含的数据模态也不同，可以发现数据集主要集中在以下几个模态：

- `RGB/Video`：图像RGB数据或视频帧数据，主要做检测、识别、分割、生成等任务  
- `Depth/PointCloud`：深度数据，RGB-D、相机位姿、动态点云、场景深度、手/物体6D位姿，主要做3D重建、位姿估计、跟踪等任务  
- `3D Pose/Mesh`：3D手/人体姿态数据，物体交互数据，比如HOT3D包括3D手、物体、mesh等，强调手/身体/物体的三维姿态标注。  
- `Multimodel`：图像和视频数据、音频数据、gaze数据、IMU数据、文本及其语音数据(比如对话数据)，数据集规模大，做感知、理解、推理等任务。
- `other`：其他的数据，如EgoPressure数据集使用压力传感器，包含压力数据。N-EPIC-Kitchens数据集使用Event camera，捕捉运动物体数据。


| Dataset | RGB/Video | Depth/PointCloud | 3D Pose/Mesh | Audio | Eye Gaze | IMU | Text |
|---------|-----------|------------------|--------------|-------|----------|-----|---------------|
| HOT3D (2025)        | ✅ | ❌ | ✅ (hand/object mesh) | ❌ | ✅ | ❌ | ❌ |
| EgoPressure (2025)  | ✅ | ❌ | ✅ (hand mesh) | ❌ | ❌ | ❌ | ❌ |
| Ego-IRGBench (2025) | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ (text queries) |
| EgoMe (2025)        | ✅ (exo-ego) | ❌ | ❌ | ❌ | ✅ | ✅ | ❌ |
| HUMOTO (2025)       | ✅ | ❌ | ✅ (motion capture) | ❌ | ❌ | ❌ | ❌ |
| HOIGen-1M (2025)    | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ (text) |
| HD-EPIC (2025)      | ✅ | ✅ (3D align) | ✅ | ✅ | ✅ | ❌ | ✅ |
| IT3DEgo (2024)      | ✅ | ✅ | ✅ (2D+3D coords) | ❌ | ❌ | ❌ | ❌ |
| VISOR-NVOS (2024)   | ✅ | ❌ | ❌ | ❌ | ❌ | ❌ | ✅ (narrations) |
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

