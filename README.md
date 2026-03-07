<div align="center">

# 🎯 Awesome Dichotomous Image Segmentation

**🔥 A curated list of awesome resources for dichotomous image segmentation (DIS)**

[![GitHub Stars](https://img.shields.io/github/stars/Tennine2077/Awesome-Dichotomous-Image-Segmentation?style=social)](https://github.com/Tennine2077/Awesome-Dichotomous-Image-Segmentation)
[![License](https://img.shields.io/badge/License-MIT-blue.svg)](LICENSE)
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

**[🇨🇳 中文版](README_CN.md)** | **English**

</div>

---

## 📢 Latest Updates

| Date | News |
|------|------|
| 🔥 2026/03/05 | CVPR2026: **PDFNet** - High-Precision DIS via Depth Integrity-Prior |
| 🔥 2026/03/05 | ICLR: **S3OD** - Generalizable SOD with Synthetic Data |
| 🔥 2026/02/26 | Sensors: **PMG-SAM** - Boosting SAM with Pre-Mask Guidance |
| 🔥 2025/11/19 | arXiv: **S3OD** - Towards Generalizable Salient Object Detection |
| 🔥 2025/10/24 | arXiv: **M2N2V2** - Multi-Modal Unsupervised Interactive Segmentation |

<details>
<summary>📜 View More Updates</summary>

| Date | News |
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
| 🔥 2024/08/27 | 🎉 Created the list |

</details>

---

## 🛠️ ComfyUI Integration

Want to try these models in ComfyUI? Check out **[ComfyUI-RemoveBackground_SET](https://github.com/set-soft/ComfyUI-RemoveBackground_SET)** by [Salvador E. Tropea](https://github.com/set-soft)! 

Big thanks to him for making this possible! ❤️

---

## 🎨 What is DIS?

**Dichotomous Image Segmentation (DIS)** aims to segment objects from natural images with **high precision**. Unlike traditional segmentation, DIS focuses on extracting fine-grained details and accurate boundaries.

<p align="center">
  <img src="imgs/model_comparison.png" alt="DIS Model Comparison" width="80%">
</p>

---

## 📚 Table of Contents

- [🤖 Non-Promptable Methods](#-non-promptable-methods)
  - [Preprint](#preprint)
  - [2026](#2026)
  - [2025](#2025-1)
  - [2024](#2024-1)
  - [2023](#2023-1)
  - [2022](#2022)
- [🚀 Promptable Methods](#-promptable-methods)
  - [Preprint](#preprint-1)
  - [2026](#2026-1)
  - [2025](#2025-2)
  - [2024](#2024-2)
  - [2023](#2023-2)

---

## 🤖 Non-Promptable Methods

### Preprint

| Year | Pub. | 🏗️ Network | Title | Author | Links |
|------|------|-------------|-------|--------|-------|
| 2025 | arXiv | **BEN** | Using Confidence-Guided Matting for DIS | Maxwell Meyer, Jack Spruyt | [Paper](https://arxiv.org/abs/2501.06230) / [Code](https://github.com/PramaLLC/BEN) [![Stars](https://img.shields.io/github/stars/PramaLLC/BEN?style=social)](https://github.com/PramaLLC/BEN) |
| | | | *Leverages confidence-guided matting techniques to improve segmentation quality in ambiguous boundary regions.* | | |

### 2026

| Year | Pub. | 🏗️ Network | Title | Author | Links |
|------|------|-------------|-------|--------|-------|
| 2026 | CVPR | **PDFNet** | High-Precision DIS via Depth Integrity-Prior and Fine-Grained Patch Strategy | Xianjie Liu, Keren Fu, Qijun Zhao | [Paper](https://arxiv.org/abs/2503.06100) / [Code](https://github.com/Tennine2077/PDFNet) [![Stars](https://img.shields.io/github/stars/Tennine2077/PDFNet?style=social)](https://github.com/Tennine2077/PDFNet) |
| | | | *Introduces depth integrity prior and fine-grained patch strategy to achieve high-precision segmentation for complex objects.* | | |
| 2026 | ICLR | **S3OD** | Towards Generalizable Salient Object Detection with Synthetic Data | Orest Kupyn, Hirokatsu Kataoka, Christian Rupprecht | [Paper](https://arxiv.org/abs/2510.21605) / [Project](https://s3odproject.github.io/) |
| | | | *Addresses the generalization problem in salient object detection by leveraging high-quality synthetic training data.* | | |

### 2025

| Year | Pub. | 🏗️ Network | Title | Author | Links |
|------|------|-------------|-------|--------|-------|
| 2025 | ICLR | **DiffDIS** | High-Precision DIS via Probing Diffusion Capacity | Qian Yu, Peng-Tao Jiang, Hao Zhang, et al. | [Paper](https://arxiv.org/abs/2410.10105) / [Code](https://github.com/qianyu-dlut/DiffDIS) [![Stars](https://img.shields.io/github/stars/qianyu-dlut/DiffDIS?style=social)](https://github.com/qianyu-dlut/DiffDIS) |
| | | | *Explores the inherent capacity of pre-trained diffusion models for high-precision dichotomous image segmentation.* | | |
| 2025 | ICLR | **GenPercept** | What Matters When Repurposing Diffusion Models for General Dense Perception Tasks? | Guangkai Xu, Yongtao Ge, Mingyu Liu, et al. | [Paper](https://arxiv.org/abs/2403.06090) / [Code](https://github.com/aim-uofa/GenPercept) [![Stars](https://img.shields.io/github/stars/aim-uofa/GenPercept?style=social)](https://github.com/aim-uofa/GenPercept) |
| | | | *Systematically investigates key factors when adapting diffusion models for dense prediction tasks including DIS.* | | |
| 2025 | PR | **S2DiNet** | Towards Lightweight and Fast High-Resolution DIS | Shuhan Chen, Haonan Tang, Yuan Huang, et al. | [Paper](https://www.sciencedirect.com/science/article/pii/S0031320325001669) / [Code](https://github.com/m0ho/S2DiNet-Towards-Lightweight-and-Fast-High-Resolution-Dichotomous-Image-Segmentation) [![Stars](https://img.shields.io/github/stars/m0ho/S2DiNet-Towards-Lightweight-and-Fast-High-Resolution-Dichotomous-Image-Segmentation?style=social)](https://github.com/m0ho/S2DiNet-Towards-Lightweight-and-Fast-High-Resolution-Dichotomous-Image-Segmentation) |
| | | | *Proposes a lightweight and efficient network architecture for high-resolution DIS with fast inference speed.* | | |

### 2024

| Year | Pub. | 🏗️ Network | Title | Author | Links |
|------|------|-------------|-------|--------|-------|
| 2024 | NeurIPS | **MaskFactory** | Towards High-quality Synthetic Data Generation For DIS | Haotian Qian, Yinda Chen, Shengtao Lou, et al. | [Paper](https://openreview.net/pdf?id=iM5i289eqt) / [Code](https://github.com/ydchen0806/MaskFactory) [![Stars](https://img.shields.io/github/stars/ydchen0806/MaskFactory?style=social)](https://github.com/ydchen0806/MaskFactory) |
| | | | *Generates high-quality synthetic training data for DIS by combining image compositing and mask refinement techniques.* | | |
| 2024 | CVPR | **MVANet** | Multi-view Aggregation Network for DIS | Qian Yu, Xiaoqi Zhao, Youwei Pang, et al. | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Yu_Multi-view_Aggregation_Network_for_Dichotomous_Image_Segmentation_CVPR_2024_paper.html) / [Code](https://github.com/qianyu-dlut/MVANet) [![Stars](https://img.shields.io/github/stars/qianyu-dlut/MVANet?style=social)](https://github.com/qianyu-dlut/MVANet) |
| | | | *Proposes multi-view aggregation strategy to capture both global context and local details for accurate segmentation.* | | |
| 2024 | CAAI AIR | **BiRefNet** | Bilateral Reference for High-Resolution DIS | Peng Zheng, Dehong Gao, Deng-Ping Fan, et al. | [Paper](https://arxiv.org/abs/2401.03407) / [Code](https://github.com/ZhengPeng7/BiRefNet) [![Stars](https://img.shields.io/github/stars/ZhengPeng7/BiRefNet?style=social)](https://github.com/ZhengPeng7/BiRefNet) |
| | | | *Introduces bilateral reference mechanism to handle high-resolution images efficiently while preserving fine details.* | | |
| 2024 | TNNLS | **FSANet** | High-Precision DIS With Frequency and Scale Awareness | Qiuping Jiang, Jinguang Cheng, Zongwei Wu, et al. | [Paper](https://ieeexplore.ieee.org/abstract/document/10638122) / [Code](https://github.com/chasecjg/FSANet) [![Stars](https://img.shields.io/github/stars/chasecjg/FSANet?style=social)](https://github.com/chasecjg/FSANet) |
| | | | *Incorporates frequency domain analysis and multi-scale features to achieve high-precision boundary segmentation.* | | |
| 2024 | CVIU | **DCENet** | Dual Cross-enhancement Network for Highly Accurate DIS | Hongbo Bi, Yuyu Tong, Pan Zhang, et al. | [Paper](https://www.sciencedirect.com/science/article/pii/S1077314224002030) / [Code](https://github.com/tongyuyu/DCENet) [![Stars](https://img.shields.io/github/stars/tongyuyu/DCENet?style=social)](https://github.com/tongyuyu/DCENet) |
| | | | *Designs dual cross-enhancement modules to mutually reinforce feature representations for accurate segmentation.* | | |
| 2024 | TVC | **BA-DIS** | Boundary-aware Dichotomous Image Segmentation | Haonan Tang, Shuhan Chen, Yang Liu, et al. | [Paper](https://link.springer.com/article/10.1007/s00371-024-03295-5) / [Code](https://github.com/m0ho/Boundary-Aware-Dichotomous-Image-Segmentation) [![Stars](https://img.shields.io/github/stars/m0ho/Boundary-Aware-Dichotomous-Image-Segmentation?style=social)](https://github.com/m0ho/Boundary-Aware-Dichotomous-Image-Segmentation) |
| | | | *Focuses on boundary-aware learning to improve edge accuracy in dichotomous image segmentation.* | | |
| 2024 | PR | **DC-Net** | Divide-and-conquer for Salient Object Detection | Jiayi Zhu, Xuebin Qin, Abdulmotaleb Elsaddik | [Paper](https://www.sciencedirect.com/science/article/pii/S003132032400654X) / [Code](https://github.com/PiggyJerry/DC-Net) [![Stars](https://img.shields.io/github/stars/PiggyJerry/DC-Net?style=social)](https://github.com/PiggyJerry/DC-Net) |
| | | | *Adopts divide-and-conquer strategy to handle objects at different scales for robust salient object detection.* | | |

### 2023

| Year | Pub. | 🏗️ Network | Title | Author | Links |
|------|------|-------------|-------|--------|-------|
| 2023 | ACM MM | **UDUN** | Unite-Divide-Unite: Joint Boosting Trunk and Structure for High-accuracy DIS | Jialun Pei, Zhangjun Zhou, Yueming Jin, et al. | [Paper](https://arxiv.org/abs/2307.14052) / [Code](https://github.com/PJLallen/UDUN) [![Stars](https://img.shields.io/github/stars/PJLallen/UDUN?style=social)](https://github.com/PJLallen/UDUN) |
| | | | *Proposes unite-divide-unite paradigm to jointly optimize trunk features and structural details for high accuracy.* | | |
| 2023 | IJCAI | **FP-DIS** | Dichotomous Image Segmentation with Frequency Priors | Yan Zhou, Bo Dong, Yuanfeng Wu, et al. | [Paper](https://www.ijcai.org/proceedings/2023/202) / [Code](https://github.com/dongbo811/FP-DIS) [![Stars](https://img.shields.io/github/stars/dongbo811/FP-DIS?style=social)](https://github.com/dongbo811/FP-DIS) |
| | | | *Leverages frequency domain priors to enhance boundary perception and segmentation accuracy.* | | |

### 2022

| Year | Pub. | 🏗️ Network | Title | Author | Links |
|------|------|-------------|-------|--------|-------|
| 2022 | ECCV | **IS-Net** | Highly Accurate Dichotomous Image Segmentation | Xuebin Qin, Hang Dai, Xiaobin Hu, et al. | [Paper](https://arxiv.org/abs/2203.03041) / [Code](https://github.com/xuebinqin/DIS) [![Stars](https://img.shields.io/github/stars/xuebinqin/DIS?style=social)](https://github.com/xuebinqin/DIS) |
| | | | *🌱 The pioneering work that defines the DIS task and proposes a baseline with a large-scale dataset.* | | |

---

## 🚀 Promptable Methods

> 🤖 Methods based on SAM or other foundation models with interactive prompts

### Preprint

| Year | Pub. | 🏗️ Network | Title | Author | Links |
|------|------|-------------|-------|--------|-------|
| 2025 | arXiv | **M2N2V2** | Multi-Modal Unsupervised and Training-free Interactive Segmentation | Markus Karmann, Peng-Tao Jiang, Bo Li, et al. | [Paper](https://arxiv.org/abs/2503.16254) |
| | | | *Proposes a training-free approach for interactive segmentation using multi-modal information without additional training.* | | |
| 2025 | arXiv | **SAM2-UNeXT** | An Improved High-Resolution Baseline for Adapting Foundation Models | Xinyu Xiong, Zihuang Wu, Lei Zhang, et al. | [Paper](https://arxiv.org/abs/2508.03566) / [Code](https://github.com/WZH0120/SAM2-UNeXT) [![Stars](https://img.shields.io/github/stars/WZH0120/SAM2-UNeXT?style=social)](https://github.com/WZH0120/SAM2-UNeXT) |
| | | | *Develops an improved high-resolution baseline for adapting SAM2 to downstream segmentation tasks.* | | |
| 2025 | arXiv | **MGD-SAM2** | Multi-view Guided Detail-enhanced SAM 2 for High-Resolution Segmentation | Haoran Shen, Peixian Zhuang, Jiahao Kou, et al. | [Paper](https://arxiv.org/abs/2503.23786) / [Code](https://github.com/sevenshr/MGD-SAM2) [![Stars](https://img.shields.io/github/stars/sevenshr/MGD-SAM2?style=social)](https://github.com/sevenshr/MGD-SAM2) |
| | | | *Enhances SAM2 with multi-view guidance and detail enhancement for high-resolution class-agnostic segmentation.* | | |
| 2023 | arXiv | **SU-SAM** | A Simple Unified Framework for Adapting SAM in Underperformed Scenes | Yiran Song, Qianyu Zhou, Xuequan Lu, et al. | [Paper](https://arxiv.org/abs/2401.17803) / [Code](https://github.com/zongzi13545329/SimAda) [![Stars](https://img.shields.io/github/stars/zongzi13545329/SimAda?style=social)](https://github.com/zongzi13545329/SimAda) |
| | | | *Proposes a simple unified framework to adapt SAM for challenging scenes where the original model underperforms.* | | |

### 2026

| Year | Pub. | 🏗️ Network | Title | Author | Links |
|------|------|-------------|-------|--------|-------|
| 2026 | Sensors | **PMG-SAM** | Boosting Auto-Segmentation of SAM with Pre-Mask Guidance | Xinyu Yan, Meijun Sun, Ge-Peng Ji, et al. | [Paper](https://www.mdpi.com/1424-8220/26/2/365) |
| | | | *Introduces pre-mask guidance mechanism to boost SAM's auto-segmentation capability for better initial predictions.* | | |

### 2025

| Year | Pub. | 🏗️ Network | Title | Author | Links |
|------|------|-------------|-------|--------|-------|
| 2025 | ICCV | **LawDIS** | Language-Window-based Controllable DIS | Xinyu Yan, Meijun Sun, Ge-Peng Ji, et al. | [Paper](https://arxiv.org/abs/2508.01152) / [Code](https://github.com/XinyuYanTJU/LawDIS) [![Stars](https://img.shields.io/github/stars/XinyuYanTJU/LawDIS?style=social)](https://github.com/XinyuYanTJU/LawDIS) |
| | | | *Enables controllable DIS through language and window-based interaction for flexible user control.* | | |
| 2025 | ICLR | **OrderIS** | Order-aware Interactive Segmentation | Bin Wang, Anwesa Choudhuri, Meng Zheng, et al. | [Paper](https://arxiv.org/abs/2410.12214) |
| | | | *Incorporates order-aware learning into interactive segmentation to model the sequential nature of user interactions.* | | |
| 2025 | ICME | **DIS-SAM** | Promoting SAM towards Highly Accurate DIS | Xianjie Liu, Keren Fu, Yao Jiang, et al. | [Paper](https://arxiv.org/abs/2401.00248) / [Code](https://github.com/Tennine2077/DIS-SAM) [![Stars](https://img.shields.io/github/stars/Tennine2077/DIS-SAM?style=social)](https://github.com/Tennine2077/DIS-SAM) |
| | | | *Adapts SAM specifically for high-precision DIS with enhanced boundary awareness and detail preservation.* | | |
| 2025 | ESWA | **EG-SAM** | An Edge-Guided SAM for Effective Complex Object Segmentation | Longyi Chen, Xiandong Wang, Fengqin Yao, et al. | [Paper](https://www.sciencedirect.com/science/article/pii/S0957417425001824) / [Code](https://github.com/code-797/EG-SAM) [![Stars](https://img.shields.io/github/stars/code-797/EG-SAM?style=social)](https://github.com/code-797/EG-SAM) |
| | | | *Integrates edge guidance into SAM for more effective segmentation of complex objects with intricate boundaries.* | | |

### 2024

| Year | Pub. | 🏗️ Network | Title | Author | Links |
|------|------|-------------|-------|--------|-------|
| 2024 | ACM MM | **PI-SAM** | Segment Anything with Precise Interaction | Mengzhen Liu, Mengyu Wang, Henghui Ding, et al. | [Paper](https://openreview.net/pdf?id=lD9A7SS4BP) |
| | | | *Improves SAM's interaction mechanism for more precise user control and better segmentation accuracy.* | | |
| 2024 | CVPR | **SegNext** | Rethinking Interactive Image Segmentation with Low Latency High Quality | Qin Liu, Jaemin Cho, Mohit Bansal, et al. | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Liu_Rethinking_Interactive_Image_Segmentation_with_Low_Latency_High_Quality_and_CVPR_2024_paper.html) / [Code](https://github.com/uncbiag/SegNext) [![Stars](https://img.shields.io/github/stars/uncbiag/SegNext?style=social)](https://github.com/uncbiag/SegNext) |
| | | | *Rethinks the trade-off between latency and quality in interactive segmentation for practical applications.* | | |
| 2024 | ECCV | **CAT-SAM** | Conditional Tuning for Few-Shot Adaptation of SAM | Aoran Xiao, Weihao Xuan, Heli Qi, et al. | [Paper](https://arxiv.org/abs/2402.03631) / [Code](https://github.com/weihao1115/cat-sam) [![Stars](https://img.shields.io/github/stars/weihao1115/cat-sam?style=social)](https://github.com/weihao1115/cat-sam) |
| | | | *Proposes conditional tuning approach for few-shot adaptation of SAM to new domains with limited samples.* | | |
| 2024 | ICCV | **BA-SAM** | Scalable Bias-Mode Attention Mask for SAM | Yiran Song, Qianyu Zhou, Xiangtai Li, et al. | [Paper](https://openaccess.thecvf.com/content/CVPR2024/html/Song_BA-SAM_Scalable_Bias-Mode_Attention_Mask_for_Segment_Anything_Model_CVPR_2024_paper.html) |
| | | | *Introduces bias-mode attention mask to improve SAM's segmentation quality with scalable design.* | | |
| 2024 | ECCV | **OVSAM** | Mamba or RWKV: Exploring High-Quality and High-Efficiency SAM | Haobo Yuan, Xiangtai Li, Lu Qi, et al. | [Paper](https://arxiv.org/abs/2406.19369) / [Code](https://github.com/HarborYuan/ovsam) [![Stars](https://img.shields.io/github/stars/HarborYuan/ovsam?style=social)](https://github.com/HarborYuan/ovsam) |
| | | | *Explores Mamba and RWKV architectures as alternatives to transformers for efficient high-quality segmentation.* | | |
| 2024 | ICME | **PA-SAM** | Prompt Adapter SAM for High-Quality Image Segmentation | Zhaozhi Xie, Bochen Guan, Weihao Jiang, et al. | [Paper](https://arxiv.org/abs/2401.13051) / [Code](https://github.com/xzz2/pa-sam) [![Stars](https://img.shields.io/github/stars/xzz2/pa-sam?style=social)](https://github.com/xzz2/pa-sam) |
| | | | *Designs a prompt adapter to enhance SAM's capability for high-quality image segmentation tasks.* | | |
| 2024 | PRICAI | **BSRNet** | Prior Mask-Guided Highly Accurate DIS | Shanfeng Zhou, Bo Yuan, Keren Fu, et al. | [Paper](https://link.springer.com/chapter/10.1007/978-981-96-0125-7_10) / [Code](https://github.com/firewoodcutter/BSRNet) [![Stars](https://img.shields.io/github/stars/firewoodcutter/BSRNet?style=social)](https://github.com/firewoodcutter/BSRNet) |
| | | | *Utilizes prior mask guidance to achieve highly accurate dichotomous image segmentation.* | | |

### 2023

| Year | Pub. | 🏗️ Network | Title | Author | Links |
|------|------|-------------|-------|--------|-------|
| 2023 | NeurIPS | **SAM-HQ** | Segment Anything in High Quality | Lei Ke, Mingqiao Ye, Martin Danelljan, et al. | [Paper](https://arxiv.org/abs/2306.01567) / [Code](https://github.com/SysCV/SAM-HQ) [![Stars](https://img.shields.io/github/stars/SysCV/SAM-HQ?style=social)](https://github.com/SysCV/SAM-HQ) |
| | | | *🌟 Enhances SAM with high-quality output for finer boundaries and more accurate segmentation masks.* | | |
| 2023 | NeurIPS | **SegRefiner** | Towards Model-Agnostic Segmentation Refinement with Discrete Diffusion | Mengyu Wang, Henghui Ding, Jun Hao Liew, et al. | [Paper](https://arxiv.org/abs/2312.12425) / [Code](https://github.com/MengyuWang826/SegRefiner) [![Stars](https://img.shields.io/github/stars/MengyuWang826/SegRefiner?style=social)](https://github.com/MengyuWang826/SegRefiner) |
| | | | *Proposes a model-agnostic refinement approach using discrete diffusion to improve segmentation quality.* | | |

---

## ⭐ Star History

If you find this repository useful, please consider giving it a star ⭐!

<p align="center">
  <a href="https://star-history.com/#Tennine2077/Awesome-Dichotomous-Image-Segmentation&Date">
    <img src="https://api.star-history.com/svg?repos=Tennine2077/Awesome-Dichotomous-Image-Segmentation&type=Date" alt="Star History Chart">
  </a>
</p>

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

<div align="center">

**Made with ❤️ for the DIS community**

</div>
