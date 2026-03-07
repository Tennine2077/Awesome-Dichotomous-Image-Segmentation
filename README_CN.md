<div align="center">

# 🎯 二分图像分割资源精选

**🔥 精心整理的二分图像分割 (DIS) 优质资源汇总**

[![GitHub Stars](https://img.shields.io/github/stars/Tennine2077/Awesome-Dichotomous-Image-Segmentation?style=social)](https://github.com/Tennine2077/Awesome-Dichotomous-Image-Segmentation)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**🇬🇧 English** | **中文版**

</div>

---

## 📢 最新动态

| 日期 | 新闻 |
|------|------|
| 🔥 2026/03/05 | CVPR2026: **PDFNet** - High-Precision DIS via Depth Integrity-Prior |
| 🔥 2026/03/05 | ICLR: **S3OD** - Generalizable SOD with Synthetic Data |
| 🔥 2026/02/26 | Sensors: **PMG-SAM** - Boosting SAM with Pre-Mask Guidance |
| 🔥 2025/11/19 | arXiv: **S3OD** - Towards Generalizable Salient Object Detection |
| 🔥 2025/10/24 | arXiv: **M2N2V2** - Multi-Modal Unsupervised Interactive Segmentation |

<details>
<summary>📜 查看更多更新</summary>

| 日期 | 新闻 |
|------|------|
| 🔥 2025/09/15 | arXiv: **SAM2-UNeXT** - Adapting Foundation Models to Downstream Segmentation |
| 🔥 2025/08/05 | ICCV: **LawDIS** - Language-Window-based Controllable DIS |
| 🔥 2025/07/15 | PR: **DC-Net** - Divide-and-conquer for salient object detection |
| 🔥 2025/05/25 | arXiv: **MGD-SAM2** - Multi-view Guided Detail-enhanced SAM 2 |
| 🔥 2025/04/19 | ICLR: **OrderIS** - Order-aware Interactive Segmentation |
| 🔥 2025/03/24 | ICME: **DIS-SAM** - Promoting SAM towards Highly Accurate DIS |
| 🔥 2025/03/15 | arXiv: High-Precision DIS via Depth Integrity-Prior |
| 🔥 2025/03/10 | PR: **S2DiNet** - Lightweight and Fast High-Resolution DIS |
| 🔥 2025/02/20 | ESWA: **EG-SAM** - Edge-Guided SAM for Complex Object Segmentation |
| 🔥 2025/01/17 | arXiv: **BEN** - Confidence-Guided Matting for DIS |
| 🔥 2024/12/15 | Diffusion Models paper updated |
| 🔥 2024/11/16 | arXiv: High-Precision DIS via Probing Diffusion Capacity |
| 🔥 2024/10/12 | NeurIPS: **MaskFactory** - Synthetic Data Generation For DIS |
| 🔥 2024/09/11 | CVIU: **DCENet** - Dual cross-enhancement network |
| 🔥 2024/08/27 | 🎉 创建此列表 |

</details>

---

## 🛠️ ComfyUI 集成

想在 ComfyUI 中尝试这些模型？查看 **[ComfyUI-RemoveBackground_SET](https://github.com/set-soft/ComfyUI-RemoveBackground_SET)**，由 [Salvador E. Tropea](https://github.com/set-soft) 开发！

非常感谢他的贡献！❤️

---

## 🎨 什么是 DIS？

**二分图像分割 (Dichotomous Image Segmentation, DIS)** 旨在从自然图像中**高精度**地分割物体。与传统的分割任务不同，DIS 专注于提取精细的细节和准确的边界。

<p align="center">
  <img src="imgs/model_comparison.png" alt="DIS 模型对比" width="80%">
</p>

---

## 📚 目录

- [🤖 非提示式方法](#-非提示式方法)
  - [预印本](#预印本)
  - [2026年](#2026年)
  - [2025年](#2025年)
  - [2024年](#2024年)
  - [2023年](#2023年)
  - [2022年](#2022年)
- [🚀 提示式方法](#-提示式方法)
  - [预印本](#预印本-1)
  - [2026年](#2026年-1)
  - [2025年](#2025年-1)
  - [2024年](#2024年-1)
  - [2023年](#2023年-1)

---

## 🤖 非提示式方法

> 📌 传统自动分割方法，无需用户交互

### 预印本

| 年份 | 期刊 | 🏗️ 网络 | 标题 | 作者 | 链接 |
|------|------|-------------|-------|--------|-------|
| 2025 | arXiv | **BEN** | Using Confidence-Guided Matting for DIS | Maxwell Meyer, Jack Spruyt | [论文](https://arxiv.org/abs/2501.06230) / [代码](https://github.com/PramaLLC/BEN) [![Stars](https://img.shields.io/github/stars/PramaLLC/BEN?style=social)](https://github.com/PramaLLC/BEN) |
| | | | *利用置信度引导的抠图技术，改善边界模糊区域的分割质量。* | | |

### 2026年

| 年份 | 期刊 | 🏗️ 网络 | 标题 | 作者 | 链接 |
|------|------|-------------|-------|--------|-------|
| 2026 | CVPR | **PDFNet** | High-Precision DIS via Depth Integrity-Prior and Fine-Grained Patch Strategy | Xianjie Liu, Keren Fu, Qijun Zhao | [论文](https://arxiv.org/abs/2503.06100) / [代码](https://github.com/Tennine2077/PDFNet) [![Stars](https://img.shields.io/github/stars/Tennine2077/PDFNet?style=social)](https://github.com/Tennine2077/PDFNet) |
| | | | *引入深度完整性先验和细粒度补丁策略，实现对复杂物体的高精度分割。* | | |
| 2026 | ICLR | **S3OD** | Towards Generalizable Salient Object Detection with Synthetic Data | Orest Kupyn, Hirokatsu Kataoka, Christian Rupprecht | [论文](https://arxiv.org/abs/2510.21605) / [项目](https://s3odproject.github.io/) |
| | | | *通过利用高质量合成训练数据，解决显著目标检测中的泛化问题。* | | |

### 2025年

| 年份 | 期刊 | 🏗️ 网络 | 标题 | 作者 | 链接 |
|------|------|-------------|-------|--------|-------|
| 2025 | ICLR | **DiffDIS** | High-Precision DIS via Probing Diffusion Capacity | Qian Yu, Peng-Tao Jiang, Hao Zhang, et al. | [论文](https://arxiv.org/abs/2410.10105) / [代码](https://github.com/qianyu-dlut/DiffDIS) [![Stars](https://img.shields.io/github/stars/qianyu-dlut/DiffDIS?style=social)](https://github.com/qianyu-dlut/DiffDIS) |
| | | | *探索预训练扩散模型的内在能力，实现高精度二分图像分割。* | | |
| 2025 | ICLR | **GenPercept** | What Matters When Repurposing Diffusion Models for General Dense Perception Tasks? | Guangkai Xu, Yongtao Ge, Mingyu Liu, et al. | [论文](https://arxiv.org/abs/2403.06090) / [代码](https://github.com/aim-uofa/GenPercept) [![Stars](https://img.shields.io/github/stars/aim-uofa/GenPercept?style=social)](https://github.com/aim-uofa/GenPercept) |
| | | | *系统性地研究了将扩散模型适配于密集预测任务（包括DIS）的关键因素。* | | |
| 2025 | PR | **S2DiNet** | Towards Lightweight and Fast High-Resolution DIS | Shuhan Chen, Haonan Tang, Yuan Huang, et al. | [论文](https://www.sciencedirect.com/science/article/pii/S0031320325001669) / [代码](https://github.com/m0ho/S2DiNet-Towards-Lightweight-and-Fast-High-Resolution-Dichotomous-Image-Segmentation) [![Stars](https://img.shields.io/github/stars/m0ho/S2DiNet-Towards-Lightweight-and-Fast-High-Resolution-Dichotomous-Image-Segmentation?style=social)](https://github.com/m0ho/S2DiNet-Towards-Lightweight-and-Fast-High-Resolution-Dichotomous-Image-Segmentation) |
| | | | *提出轻量化高效的网络架构，实现高分辨率DIS的快速推理。* | | |

### 2024年

| 年份 | 期刊 | 🏗️ 网络 | 标题 | 作者 | 链接 |
|------|------|-------------|-------|--------|-------|
| 2024 | NeurIPS | **MaskFactory** | Towards High-quality Synthetic Data Generation For DIS | Haotian Qian, Yinda Chen, Shengtao Lou, et al. | [论文](https://openreview.net/pdf?id=iM5i289eqt) / [代码](https://github.com/ydchen0806/MaskFactory) [![Stars](https://img.shields.io/github/stars/ydchen0806/MaskFactory?style=social)](https://github.com/ydchen0806/MaskFactory) |
| | | | *通过结合图像合成和掩码细化技术，为DIS生成高质量的合成训练数据。* | | |
| 2024 | CVPR | **MVANet** | Multi-view Aggregation Network for DIS | Qian Yu, Xiaoqi Zhao, Youwei Pang, et al. | [论文](https://openaccess.thecvf.com/content/CVPR2024/html/Yu_Multi-view_Aggregation_Network_for_Dichotomous_Image_Segmentation_CVPR_2024_paper.html) / [代码](https://github.com/qianyu-dlut/MVANet) [![Stars](https://img.shields.io/github/stars/qianyu-dlut/MVANet?style=social)](https://github.com/qianyu-dlut/MVANet) |
| | | | *提出多视图聚合策略，同时捕获全局上下文和局部细节以实现精确分割。* | | |
| 2024 | CAAI AIR | **BiRefNet** | Bilateral Reference for High-Resolution DIS | Peng Zheng, Dehong Gao, Deng-Ping Fan, et al. | [论文](https://arxiv.org/abs/2401.03407) / [代码](https://github.com/ZhengPeng7/BiRefNet) [![Stars](https://img.shields.io/github/stars/ZhengPeng7/BiRefNet?style=social)](https://github.com/ZhengPeng7/BiRefNet) |
| | | | *引入双边参考机制，在保持精细细节的同时高效处理高分辨率图像。* | | |
| 2024 | TNNLS | **FSANet** | High-Precision DIS With Frequency and Scale Awareness | Qiuping Jiang, Jinguang Cheng, Zongwei Wu, et al. | [论文](https://ieeexplore.ieee.org/abstract/document/10638122) / [代码](https://github.com/chasecjg/FSANet) [![Stars](https://img.shields.io/github/stars/chasecjg/FSANet?style=social)](https://github.com/chasecjg/FSANet) |
| | | | *结合频域分析和多尺度特征，实现高精度边界分割。* | | |
| 2024 | CVIU | **DCENet** | Dual Cross-enhancement Network for Highly Accurate DIS | Hongbo Bi, Yuyu Tong, Pan Zhang, et al. | [论文](https://www.sciencedirect.com/science/article/pii/S1077314224002030) / [代码](https://github.com/tongyuyu/DCENet) [![Stars](https://img.shields.io/github/stars/tongyuyu/DCENet?style=social)](https://github.com/tongyuyu/DCENet) |
| | | | *设计双交叉增强模块，相互强化特征表示以实现精确分割。* | | |
| 2024 | TVC | **BA-DIS** | Boundary-aware Dichotomous Image Segmentation | Haonan Tang, Shuhan Chen, Yang Liu, et al. | [论文](https://link.springer.com/article/10.1007/s00371-024-03295-5) / [代码](https://github.com/m0ho/Boundary-Aware-Dichotomous-Image-Segmentation) [![Stars](https://img.shields.io/github/stars/m0ho/Boundary-Aware-Dichotomous-Image-Segmentation?style=social)](https://github.com/m0ho/Boundary-Aware-Dichotomous-Image-Segmentation) |
| | | | *专注于边界感知学习，提升二分图像分割的边缘精度。* | | |
| 2024 | PR | **DC-Net** | Divide-and-conquer for Salient Object Detection | Jiayi Zhu, Xuebin Qin, Abdulmotaleb Elsaddik | [论文](https://www.sciencedirect.com/science/article/pii/S003132032400654X) / [代码](https://github.com/PiggyJerry/DC-Net) [![Stars](https://img.shields.io/github/stars/PiggyJerry/DC-Net?style=social)](https://github.com/PiggyJerry/DC-Net) |
| | | | *采用分治策略处理不同尺度的物体，实现鲁棒的显著目标检测。* | | |

### 2023年

| 年份 | 期刊 | 🏗️ 网络 | 标题 | 作者 | 链接 |
|------|------|-------------|-------|--------|-------|
| 2023 | ACM MM | **UDUN** | Unite-Divide-Unite: Joint Boosting Trunk and Structure for High-accuracy DIS | Jialun Pei, Zhangjun Zhou, Yueming Jin, et al. | [论文](https://arxiv.org/abs/2307.14052) / [代码](https://github.com/PJLallen/UDUN) [![Stars](https://img.shields.io/github/stars/PJLallen/UDUN?style=social)](https://github.com/PJLallen/UDUN) |
| | | | *提出统一-分治-统一范式，联合优化主干特征和结构细节以实现高精度。* | | |
| 2023 | IJCAI | **FP-DIS** | Dichotomous Image Segmentation with Frequency Priors | Yan Zhou, Bo Dong, Yuanfeng Wu, et al. | [论文](https://www.ijcai.org/proceedings/2023/202) / [代码](https://github.com/dongbo811/FP-DIS) [![Stars](https://img.shields.io/github/stars/dongbo811/FP-DIS?style=social)](https://github.com/dongbo811/FP-DIS) |
| | | | *利用频域先验增强边界感知能力和分割精度。* | | |

### 2022年

| 年份 | 期刊 | 🏗️ 网络 | 标题 | 作者 | 链接 |
|------|------|-------------|-------|--------|-------|
| 2022 | ECCV | **IS-Net** | Highly Accurate Dichotomous Image Segmentation | Xuebin Qin, Hang Dai, Xiaobin Hu, et al. | [论文](https://arxiv.org/abs/2203.03041) / [代码](https://github.com/xuebinqin/DIS) [![Stars](https://img.shields.io/github/stars/xuebinqin/DIS?style=social)](https://github.com/xuebinqin/DIS) |
| | | | *🌱 开创性工作，定义了DIS任务并提出了基线模型和大规模数据集。* | | |

---

## 🚀 提示式方法

> 🤖 基于 SAM 或其他基础模型的交互式分割方法

### 预印本

| 年份 | 期刊 | 🏗️ 网络 | 标题 | 作者 | 链接 |
|------|------|-------------|-------|--------|-------|
| 2025 | arXiv | **M2N2V2** | Multi-Modal Unsupervised and Training-free Interactive Segmentation | Markus Karmann, Peng-Tao Jiang, Bo Li, et al. | [论文](https://arxiv.org/abs/2503.16254) |
| | | | *提出一种无需训练的方法，利用多模态信息实现交互式分割。* | | |
| 2025 | arXiv | **SAM2-UNeXT** | An Improved High-Resolution Baseline for Adapting Foundation Models | Xinyu Xiong, Zihuang Wu, Lei Zhang, et al. | [论文](https://arxiv.org/abs/2508.03566) / [代码](https://github.com/WZH0120/SAM2-UNeXT) [![Stars](https://img.shields.io/github/stars/WZH0120/SAM2-UNeXT?style=social)](https://github.com/WZH0120/SAM2-UNeXT) |
| | | | *开发了改进的高分辨率基线，用于将SAM2适配到下游分割任务。* | | |
| 2025 | arXiv | **MGD-SAM2** | Multi-view Guided Detail-enhanced SAM 2 for High-Resolution Segmentation | Haoran Shen, Peixian Zhuang, Jiahao Kou, et al. | [论文](https://arxiv.org/abs/2503.23786) / [代码](https://github.com/sevenshr/MGD-SAM2) [![Stars](https://img.shields.io/github/stars/sevenshr/MGD-SAM2?style=social)](https://github.com/sevenshr/MGD-SAM2) |
| | | | *通过多视图引导和细节增强机制，提升SAM2在高分辨率类别无关分割中的表现。* | | |
| 2023 | arXiv | **SU-SAM** | A Simple Unified Framework for Adapting SAM in Underperformed Scenes | Yiran Song, Qianyu Zhou, Xuequan Lu, et al. | [论文](https://arxiv.org/abs/2401.17803) / [代码](https://github.com/zongzi13545329/SimAda) [![Stars](https://img.shields.io/github/stars/zongzi13545329/SimAda?style=social)](https://github.com/zongzi13545329/SimAda) |
| | | | *提出简单统一的框架，将SAM适配到原始模型表现不佳的挑战性场景。* | | |

### 2026年

| 年份 | 期刊 | 🏗️ 网络 | 标题 | 作者 | 链接 |
|------|------|-------------|-------|--------|-------|
| 2026 | Sensors | **PMG-SAM** | Boosting Auto-Segmentation of SAM with Pre-Mask Guidance | Xinyu Yan, Meijun Sun, Ge-Peng Ji, et al. | [论文](https://www.mdpi.com/1424-8220/26/2/365) |
| | | | *引入预掩码引导机制，提升SAM的自动分割能力以获得更好的初始预测。* | | |

### 2025年

| 年份 | 期刊 | 🏗️ 网络 | 标题 | 作者 | 链接 |
|------|------|-------------|-------|--------|-------|
| 2025 | ICCV | **LawDIS** | Language-Window-based Controllable DIS | Xinyu Yan, Meijun Sun, Ge-Peng Ji, et al. | [论文](https://arxiv.org/abs/2508.01152) / [代码](https://github.com/XinyuYanTJU/LawDIS) [![Stars](https://img.shields.io/github/stars/XinyuYanTJU/LawDIS?style=social)](https://github.com/XinyuYanTJU/LawDIS) |
| | | | *通过语言和窗口交互实现可控的DIS，提供灵活的用户控制方式。* | | |
| 2025 | ICLR | **OrderIS** | Order-aware Interactive Segmentation | Bin Wang, Anwesa Choudhuri, Meng Zheng, et al. | [论文](https://arxiv.org/abs/2410.12214) |
| | | | *将序列感知学习融入交互式分割，建模用户交互的顺序特性。* | | |
| 2025 | ICME | **DIS-SAM** | Promoting SAM towards Highly Accurate DIS | Xianjie Liu, Keren Fu, Yao Jiang, et al. | [论文](https://arxiv.org/abs/2401.00248) / [代码](https://github.com/Tennine2077/DIS-SAM) [![Stars](https://img.shields.io/github/stars/Tennine2077/DIS-SAM?style=social)](https://github.com/Tennine2077/DIS-SAM) |
| | | | *专门将SAM适配于高精度DIS，增强边界感知和细节保留能力。* | | |
| 2025 | ESWA | **EG-SAM** | An Edge-Guided SAM for Effective Complex Object Segmentation | Longyi Chen, Xiandong Wang, Fengqin Yao, et al. | [论文](https://www.sciencedirect.com/science/article/pii/S0957417425001824) / [代码](https://github.com/code-797/EG-SAM) [![Stars](https://img.shields.io/github/stars/code-797/EG-SAM?style=social)](https://github.com/code-797/EG-SAM) |
| | | | *将边缘引导集成到SAM中，更有效地分割具有复杂边界的物体。* | | |

### 2024年

| 年份 | 期刊 | 🏗️ 网络 | 标题 | 作者 | 链接 |
|------|------|-------------|-------|--------|-------|
| 2024 | ACM MM | **PI-SAM** | Segment Anything with Precise Interaction | Mengzhen Liu, Mengyu Wang, Henghui Ding, et al. | [论文](https://openreview.net/pdf?id=lD9A7SS4BP) |
| | | | *改进SAM的交互机制，实现更精确的用户控制和更好的分割精度。* | | |
| 2024 | CVPR | **SegNext** | Rethinking Interactive Image Segmentation with Low Latency High Quality | Qin Liu, Jaemin Cho, Mohit Bansal, et al. | [论文](https://openaccess.thecvf.com/content/CVPR2024/html/Liu_Rethinking_Interactive_Image_Segmentation_with_Low_Latency_High_Quality_and_CVPR_2024_paper.html) / [代码](https://github.com/uncbiag/SegNext) [![Stars](https://img.shields.io/github/stars/uncbiag/SegNext?style=social)](https://github.com/uncbiag/SegNext) |
| | | | *重新思考交互式分割中延迟与质量的权衡，面向实际应用场景。* | | |
| 2024 | ECCV | **CAT-SAM** | Conditional Tuning for Few-Shot Adaptation of SAM | Aoran Xiao, Weihao Xuan, Heli Qi, et al. | [论文](https://arxiv.org/abs/2402.03631) / [代码](https://github.com/weihao1115/cat-sam) [![Stars](https://img.shields.io/github/stars/weihao1115/cat-sam?style=social)](https://github.com/weihao1115/cat-sam) |
| | | | *提出条件调优方法，实现SAM在有限样本下对新领域的少样本适配。* | | |
| 2024 | ICCV | **BA-SAM** | Scalable Bias-Mode Attention Mask for SAM | Yiran Song, Qianyu Zhou, Xiangtai Li, et al. | [论文](https://openaccess.thecvf.com/content/CVPR2024/html/Song_BA-SAM_Scalable_Bias-Mode_Attention_Mask_for_Segment_Anything_Model_CVPR_2024_paper.html) |
| | | | *引入偏置模式注意力掩码，以可扩展的设计提升SAM的分割质量。* | | |
| 2024 | ECCV | **OVSAM** | Mamba or RWKV: Exploring High-Quality and High-Efficiency SAM | Haobo Yuan, Xiangtai Li, Lu Qi, et al. | [论文](https://arxiv.org/abs/2406.19369) / [代码](https://github.com/HarborYuan/ovsam) [![Stars](https://img.shields.io/github/stars/HarborYuan/ovsam?style=social)](https://github.com/HarborYuan/ovsam) |
| | | | *探索Mamba和RWKV架构作为Transformer的替代方案，实现高效高质量分割。* | | |
| 2024 | ICME | **PA-SAM** | Prompt Adapter SAM for High-Quality Image Segmentation | Zhaozhi Xie, Bochen Guan, Weihao Jiang, et al. | [论文](https://arxiv.org/abs/2401.13051) / [代码](https://github.com/xzz2/pa-sam) [![Stars](https://img.shields.io/github/stars/xzz2/pa-sam?style=social)](https://github.com/xzz2/pa-sam) |
| | | | *设计提示适配器，增强SAM在高质量图像分割任务中的能力。* | | |
| 2024 | PRICAI | **BSRNet** | Prior Mask-Guided Highly Accurate DIS | Shanfeng Zhou, Bo Yuan, Keren Fu, et al. | [论文](https://link.springer.com/chapter/10.1007/978-981-96-0125-7_10) / [代码](https://github.com/firewoodcutter/BSRNet) [![Stars](https://img.shields.io/github/stars/firewoodcutter/BSRNet?style=social)](https://github.com/firewoodcutter/BSRNet) |
| | | | *利用先验掩码引导实现高精度的二分图像分割。* | | |

### 2023年

| 年份 | 期刊 | 🏗️ 网络 | 标题 | 作者 | 链接 |
|------|------|-------------|-------|--------|-------|
| 2023 | NeurIPS | **SAM-HQ** | Segment Anything in High Quality | Lei Ke, Mingqiao Ye, Martin Danelljan, et al. | [论文](https://arxiv.org/abs/2306.01567) / [代码](https://github.com/SysCV/SAM-HQ) [![Stars](https://img.shields.io/github/stars/SysCV/SAM-HQ?style=social)](https://github.com/SysCV/SAM-HQ) |
| | | | *🌟 增强SAM的输出质量，实现更精细的边界和更准确的分割掩码。* | | |
| 2023 | NeurIPS | **SegRefiner** | Towards Model-Agnostic Segmentation Refinement with Discrete Diffusion | Mengyu Wang, Henghui Ding, Jun Hao Liew, et al. | [论文](https://arxiv.org/abs/2312.12425) / [代码](https://github.com/MengyuWang826/SegRefiner) [![Stars](https://img.shields.io/github/stars/MengyuWang826/SegRefiner?style=social)](https://github.com/MengyuWang826/SegRefiner) |
| | | | *提出基于离散扩散的模型无关细化方法，提升分割质量。* | | |

---

## ⭐ Star 趋势

如果您觉得这个仓库有用，请考虑点个 star ⭐！

<p align="center">
  <a href="https://star-history.com/#Tennine2077/Awesome-Dichotomous-Image-Segmentation&Date">
    <img src="https://api.star-history.com/svg?repos=Tennine2077/Awesome-Dichotomous-Image-Segmentation&type=Date" alt="Star History Chart">
  </a>
</p>

---

## 📜 许可证

本项目采用 MIT 许可证 - 详情请见 [LICENSE](LICENSE) 文件。

---

<div align="center">

**为 DIS 社区用 ❤️ 制作**

</div>