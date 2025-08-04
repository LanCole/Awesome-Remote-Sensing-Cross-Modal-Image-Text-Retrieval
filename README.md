<div align='center'>
  
# Awesome-Remote-Sensing-Cross-Modal-Image-Text-Retrieval
[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/BaolanChen/Awesome-Remote-Sensing-Cross-Modal-Retrieval)

<h4>A collection of papers, datasets, benchmarks, code, and model weights for Remote Sensing Cross-Modal Image-Text Retrieval (RSCMIT).</h4>

---
</div>

## 📢 Latest Updates
:fire::fire::fire: Last Updated on 2025.02.28 :fire::fire::fire:
- **2025.02.28**: Update SPCA-Net.
- **2025.02.20**: Update ACF.
- **2025.02.19**: Update CPPMN and SWPE.
- **2025.01.10**: Update TeoChat、RingMoGPT and VHM.
- **2025.01.09**: Update PERSVL、GeoChat.
- **2024.12.24**: Update CFITR.
- **2024.12.09**: Update CDMAN、MSA、KTIR、CMPAGL、CCLS2T、SARCI、FSISR and SCAT.
- **2024.12.05**: Update SIRS and HVSA.

## Table of Contents
- **Models**
  - [Remote Sensing Cross-Modal Image-Text Retrieval Models](#remote-sensing-image-text-retrieval-models)
  - [Remote Sensing Vision-Language Modal Model for More Tasks](#Remote-Sensing-Vision-Language-Modal-Model-for-More-Tasks) 
  - [Remote Sensing Vision-Language Large & Foundation Models](#remote-sensing-vision-language-foundation-models)
- **Datasets & Benchmarks**
  - [Benchmarks for RSFMs](#benchmarks-for-rSFMs)
  - [(Large-scale) Pre-training Datasets](#Remote-Sensing-Captions-Datasets)
- **Survey**
  - [Survey Papers](#survey-papers)
- **Projects**
  - [Relevant Projects](#relevant-projects)

  
## Remote Sensing Cross-Modal Image-Text Survey

|Paper|Title|Publication|Affiliation|Note
|:---:|---|:---:|:---:|:---:|
|[Paper](https://www.mdpi.com/2072-4292/17/1/162)|**Advancements in Vision–Language Models for Remote Sensing: Datasets, Capabilities, and Enhancement Techniques**|Remote Sensing 2025|Northwestern Polytechnical University|
|[Paper](https://arxiv.org/abs/2410.16602)|**Foundation Models for Remote Sensing and Earth Observation: A Survey**|Arxiv 2024|University of Tokyo and the RIKEN Center for Advanced Intelligence Project, Japan|
|[Paper](https://ieeexplore.ieee.org/abstract/document/10770814)|**When Geoscience Meets Foundation Models: Toward a general geoscience artificial intelligence system**|GRSM 2024|Nanjing University of Aeronautics and Astronautics|
|[Paper](https://ieeexplore.ieee.org/document/10506064)|**Vision-Language Models in Remote Sensing: Current progress and future trends**|GRSM 2024|King Abdullah University of Science and Technology|
|[Paper](https://ieeexplore.ieee.org/abstract/document/10278197)|**Language Integration in Remote Sensing: Tasks, datasets, and future directions**|GRSM 2023|King Saud University|
|[Paper](https://ieeexplore.ieee.org/abstract/document/10126079)|**Self-Supervised Remote Sensing Feature Learning: Learning Paradigms, Challenges, and Future Works**|TGRS 2023|Central South University|
|[Paper](https://arxiv.org/abs/2304.13009)|**The Potential of Visual ChatGPT For Remote Sensing**|Arxiv 2023|University of Western São Paulo|
|[Paper](http://ch.whu.edu.cn/cn/article/doi/10.13203/j.whugis20230341?viewType=HTML)|**遥感大模型：进展与前瞻**|武汉大学学报 (信息科学版) 2023|Wuhan University|


## Remote Sensing Image-Text Datasets

| Dataset Name                                                         | Image size | Image Resolution      | VLMs |Note
| ------------------------------------------------------------ | ---------- | --------------- | ------------------------------------------------------------ |------------------------------------------------------------ |
| [UCM-Captions](https://github.com/201528014227051/RSICD_optimal) | 613        | 256 × 256       | - | - |
| [Sydney-Captions](https://github.com/201528014227051/RSICD_optimal) | 2,100      | 500 × 500       | - | - |
| [RSICD](https://github.com/201528014227051/RSICD_optimal)    | 10,921     | 224 × 224       | - | - |
| [RSITMD](https://github.com/xiaoyuan1996/AMFMN/tree/master/RSITMD) | 4,743      | 256 × 256       | - | - |
| [NWPU-Captions](https://github.com/HaiyanHuang98/NWPU-Captions) | 31,500     | 256 × 256       | - | - |
| [RS5M](https://github.com/om-ai-lab/RS5M)                    | 5 million+ | All Resolutions | [GeoRSCLIP](https://huggingface.co/Zilun/GeoRSCLIP) | - |
| [SkyScript](https://github.com/wangzhecheng/SkyScript)                    | 5.2 million+ | All Resolutions | [SkyCLIP](https://github.com/wangzhecheng/SkyScript) | - |
| [ChatEarthNet](https://arxiv.org/abs/2402.11325)                    | 163,488 + 10,000  | -| [ChatEarthNet](https://arxiv.org/abs/2402.11325) | The dataset will be made publicly available. |
| [GEOBench-VLM](https://arxiv.org/abs/2411.19325)                    | over 10,000  | -| [GEOBench-VLM](https://github.com/The-AI-Alliance/GEO-Bench-VLM) | - |
| [VRSBench](https://arxiv.org/abs/2406.12384)                    | 29,614   | -| [VRSBench](https://github.com/lx709/VRSBench) |  29,614 images, with 29,614 human-verified detailed captions, 52,472 object references, and 123,221 question-answer pairs (NeruIPS 2024 Dataset and Benchmark Track) |

  
## Remote Sensing Cross-Modal Image-Text Retrieval Models

|Paper|Title|Publication|Affiliation|Code|Note
|:---:|---|:---:|:---:|:---:|:---:|
|[ Graph-based Hierarchical Semantic Consistency Alignment Network](https://ieeexplore.ieee.org/abstract/document/11031116)|**Graph-Based Hierarchical Semantic Consistency Network for Remote Sensing Image–Text Retrieval**|JSTARS 2025|Xidian University|-|
|[ACF](https://www.mdpi.com/2072-4292/17/3/503)|**Remote Sensing Cross-Modal Text-Image Retrieval Based on Attention Correction and Filtering**|Remote Sensing 2025|University of Electronic Science and Technology of China|-|
|[SWPE](https://ieeexplore.ieee.org/document/10855571)|**Strong and Weak Prompt Engineering for Remote Sensing Image-Text Cross-Modal Retrieval**|JSTARS 2025|Ocean University of China|-|
|[CPPMN](https://ieeexplore.ieee.org/abstract/document/10855517)|**Cross-Modal Progressive Perspective Matching Network for Remote Sensing Image-Text Retrieval**|TMM 2025|Ocean University of China|-|
|[RGAL](https://ieeexplore.ieee.org/abstract/document/11072828)|**Relevance-Guided Adaptive Learning for Remote Sensing Image–Text Retrieval**|TGRS 2025|Fuzhou University|-|
|[CFITR](https://ieeexplore.ieee.org/abstract/document/10747393)|**Toward Efficient and Accurate Remote Sensing Image–Text Retrieval With a Coarse-to-Fine Approach**|GRSL 2024|Beijing Foreign Studies University|[Github](https://github.com/ZhWenQian/CFITR)|
|[SPCA-Net](https://www.sciencedirect.com/science/article/abs/pii/S0893608024006427)|**Boosting cross-modal retrieval in remote sensing via a novel unified attention network**|Neural Networks 2024|Indian Institute of Technology|-|
|[PERSVL](https://ieeexplore.ieee.org/abstract/document/10684217)|**Prior-Experience-based Vision-Language Model for Remote Sensing Image-Text Retrieval**|TGRS 2024|Xidian|[Github](https://github.com/TangXu-Group/Cross-modal-remote-sensing-image-and-text-retrieval-models/tree/main/PERSVL)|
|[CDMAN](https://ieeexplore.ieee.org/abstract/document/10772105)|**Thread the Needle: Cues-Driven Multi-Association for Remote Sensing Cross-Modal Retrieval**|TGRS 2024|Wuhan University of Technology|-|
|[MSA](https://ieeexplore.ieee.org/abstract/document/10758255)|**Transcending Fusion: A Multiscale Alignment Method for Remote Sensing Image–Text Retrieval**|TGRS 2024|Xidian University|[Github](https://github.com/yr666666/MSA)|
|[KTIR](https://ieeexplore.ieee.org/abstract/document/10716520)|**Knowledge-aware Text-Image Retrieval for Remote Sensing Images**|TGRS 2024|EPFL|-|
|[CMPAGL](https://ieeexplore.ieee.org/abstract/document/10740340)|**Cross-Modal Prealigned Method With Global and Local Information for Remote Sensing Image and Text Retrieval**|TGRS 2024|Shanghai Maritime University|[Github](https://github.com/ZbaoSun/CMPAGL)|
|[FGIS](https://ieeexplore.ieee.org/abstract/document/10716520)|**Fine-Grained Information Supplementation and Value-Guided Learning for Remote Sensing Image-Text Retrieval**|JSTARS 2024|Chongqing University|-|
|[EBAKER](https://dl.acm.org/doi/abs/10.1145/3664647.3681270)|**Eliminate Before Align: A Remote Sensing Image-Text Retrieval Framework with Keyword Explicit Reasoning**|ACMMM 2024|Tianjin University|-|
|[CUP](https://ieeexplore.ieee.org/abstract/document/10689627)|**Cross-Modal Remote Sensing Image–Text Retrieval via Context and Uncertainty-Aware Prompt**|TNNLS 2024|Xidian University|[Github](https://github.com/TangXu-Group/Cross-modal-remote-sensing-image-and-text-retrieval-models/tree/main/CUP)|
|[CCLS2T](https://ieeexplore.ieee.org/abstract/document/10568105)|**Cross-Modal Contrastive Learning With Spatiotemporal Context for Correlation-Aware Multiscale Remote Sensing Image Retrieval**|TGRS 2024|Xidian University|-|
|[MIIA](https://ieeexplore.ieee.org/abstract/document/10540645)|**Global–Local Information Soft-Alignment for Cross-Modal Remote-Sensing Image–Text Retrieval**|TGRS 2024|Northwestern Polytechnical University|-|
|[SARCI](https://ieeexplore.ieee.org/abstract/document/10634550)|**Scale-Aware Adaptive Refinement and Cross-Interaction for Remote Sensing Audio-Visual Cross-Modal Retrieval**|TGRS 2024|Wuhan University of Technology|[Github](https://github.com/WUTCM-Lab/SARCI)|
|[GLISA](https://ieeexplore.ieee.org/abstract/document/10530286)|**Masking-Based Cross-Modal Remote Sensing Image–Text Retrieval via Dynamic Contrastive Learning**|TGRS 2024|China University of Mining and Technology|-|
|[SCAT](https://ieeexplore.ieee.org/abstract/document/10510483)|**Spatial–Channel Attention Transformer With Pseudo Regions for Remote Sensing Image-Text Retrieval**|TGRS 2024|Northwestern Polytechnical University|-|
|[FSISR](https://ieeexplore.ieee.org/abstract/document/10440628)|**Cross-Modal Hashing With Feature Semi-Interaction and Semantic Ranking for Remote Sensing Ship Image Retrieval**|TGRS 2024|Harbin Institute of Technology|-|
|[SkyEyeGPT](https://arxiv.org/abs/2401.09712)|**Unifying Remote Sensing Vision-Language Tasks via Instruction Tuning with Large Language Model**|Arxiv 2024|Northwestern Polytechnical University|[Github](https://github.com/ZhanYang-nwpu/SkyEyeGPT)|
|[MFF-SFE](http://journal.ucas.ac.cn/CN/10.7523/j.ucas.2024.025)|**Cross-modal retrieval method based on MFF-SFE for remote sensing image-text**|中国科学院大学学报 2024|Aerospace Information Research Institute, Chinese Academy of Sciences|-|
|[RemoteCLIP](https://ieeexplore.ieee.org/document/9745546)|**RemoteCLIP: A Vision Language Foundation Model for Remote Sensing**|TGRS 2024|Hohai University|[Github](https://github.com/ChenDelong1999/RemoteCLIP)|
|[C2F-ITR](https://ieeexplore.ieee.org/abstract/document/10640383)|**From Coarse To Fine: An Offline-Online Approach for Remote Sensing Cross-Modal Retrieval**|IGARSS 2024|Beijing Foreign Studies University|-|
|[MGRM-EL](https://ieeexplore.ieee.org/abstract/document/10319744)|**Exploring Uni-Modal Feature Learning on Entities and Relations for Remote Sensing Cross-Modal Text-Image Retrieval**|TGRS 2024|Northwestern Polytechnical University|-|
|[SIRS](https://ieeexplore.ieee.org/document/10533243)|**Multitask Joint Learning for Remote Sensing Foreground-Entity Image–Text Retrieval**|TGRS 2024|Soochow University|[Github](https://github.com/StarBurstStream0/SIRS)|
|[PIR](https://dl.acm.org/doi/abs/10.1145/3581783.3612374)|**A Prior Instruction Representation Framework for Remote Sensing Image-text Retrieval**|ACMMM 2023 oral|Zhejiang University of Technology|[Github](https://github.com/Zjut-MultimediaPlus/PIR-pytorch)|
|[PE-RSITR](https://ieeexplore.ieee.org/abstract/document/10231134)|**Parameter-Efficient Transfer Learning for Remote Sensing Image–Text Retrieval**|TGRS 2023|Northwestern Polytechnical University|[Github](https://github.com/ZhanYang-nwpu/PE-RSITR)|
|[HVSA](https://ieeexplore.ieee.org/document/10533243)|**Hypersphere-Based Remote Sensing Cross-Modal Text–Image Retrieval via Curriculum Learning**|TGRS 2023|Aerospace Information Research Institute,  Chinese Academy of Sciences|[Github](https://github.com/ZhangWeihang99/HVSA)|
|[SWAN](https://dl.acm.org/doi/abs/10.1145/3591106.3592236)|**Reducing Semantic Confusion Scene-aware Aggregation Network for Remote Sensing Cross-modal Retrieval**|ICMR 2023 oral|Zhejiang University of Technology |[Github](https://github.com/jaychempan/SWAN)|
|[KAMCL](https://ieeexplore.ieee.org/document/10315162)|**Knowledge-Aided Momentum Contrastive Learning for Remote-Sensing Image Text Retrieval**|TGRS 2023 |Tianjin University|[Github](https://github.com/mcx-mcx/KAMCL)|
|[IEFT](https://ieeexplore.ieee.org/abstract/document/10138021)|**Interacting-Enhancing Feature Transformer for Cross-Modal Remote-Sensing Image and Text Retrieval**|TGRS 2023 |Xidian University|[Github](https://github.com/TangXu-Group/Cross-modal-remote-sensing-image-and-text-retrieval-models/tree/main/IEFT)|
|[-](https://ieeexplore.ieee.org/document/10282896)|**A Texture and Saliency Enhanced Image Learning Method For Cross-Modal Remote Sensing Image-Text Retrieval**|IGARSS 2023 |Xidian University|-|
|[Multilanguage Transformer ](https://ieeexplore.ieee.org/abstract/document/9925582)|**Multilanguage Transformer for Improved Text to Remote Sensing Image Retrieval**|JSTARS 2022|King Saud University|-|
|[MSIT](https://ieeexplore.ieee.org/abstract/document/9883252)|**Multi-Scale Interactive Transformer for Remote Sensing Cross-Modal Image-Text Retrieval**|IGARSS 2022|Xidian University|-|
|[GaLR](https://ieeexplore.ieee.org/document/9745546)|**Remote Sensing Cross-Modal Text-Image Retrieval Based on Global and Local Information**|TGRS 2022|Aerospace Information Research Institute,  Chinese Academy of Sciences|[Github](https://github.com/xiaoyuan1996/GaLR)|
|[-](https://www.tandfonline.com/doi/abs/10.1080/01431161.2023.2225705)|**Cross-modal retrieval of remote sensing images and text based on self-attention unsupervised deep common feature space**|IJRS 2022|National University of Defense Technology|-|
|[AMFMN](https://ieeexplore.ieee.org/document/9745546)|**Exploring a Fine-Grained Multiscale Method for Cross-Modal Remote Sensing Image Retrieval**|TGRS 2021|Aerospace Information Research Institute,  Chinese Academy of Sciences|[Github](https://github.com/xiaoyuan1996/GaLR)|
|[LW-MCR](https://ieeexplore.ieee.org/abstract/document/9594840/)|**A Lightweight Multi-Scale Crossmodal Text-Image Retrieval Method in Remote Sensing**|TGRS 2021|Aerospace Information Research Institute,  Chinese Academy of Sciences|[Github](https://github.com/xiaoyuan1996/retrievalSystem)|
|[VSE++](https://arxiv.org/abs/1707.05612)|**VSE++: Improving Visual-Semantic Embeddings with Hard Negatives**|BMVC 2018 spotlight |University of Toronto|[Github](https://github.com/fartashf/vsepp)|

## Remote Sensing <ins>Vision-Language</ins> Modal Model for More Tasks 
|Paper|Title|Publication|Affiliation|Code|Note
|:---:|---|:---:|:---:|:---:|:---:|
|[FIANet](https://ieeexplore.ieee.org/abstract/document/10816052)|**Exploring Fine-Grained Image-Text Alignment for Referring Remote Sensing Image Segmentation**|TGRS 2024|Southwest Jiaotong University|[Github](https://github.com/Shaosifan/FIANet)|Image Segmentation
|[FedRSClip](https://arxiv.org/abs/2501.02461)|**FedRSClip: Federated Learning for Remote Sensing Scene Classification Using Vision-Language Models**|Arxiv 2024|China Academy of Electronics and Information Technology|-|Scene Classification

## Remote Sensing <ins>Vision-Language</ins> Large & Foundation Models

|Abbreviation|Title|Publication|Paper|Code & Weights|
|:---:|---|:---:|:---:|:---:|
|**VHM**|**VHM: Versatile and Honest Vision Language Model for Remote Sensing Image Analysis**|Arxiv 2024|[VHM](https://arxiv.org/abs/2403.20213)|[link](https://github.com/opendatalab/VHM)|
|**TeoChat**|**TEOChat: A Large Vision-Language Assistant for Temporal Earth Observation Data**|Arxiv 2024|[TeoChat](https://arxiv.org/abs/2410.06234)|[link](https://github.com/ermongroup/TEOChat)|
|**RingMoGPT**|**RingMoGPT: A Unified Remote Sensing Foundation Model for Vision, Language, and grounded tasks**|TGRS 2024|[RingMoGPT](https://ieeexplore.ieee.org/abstract/document/10777289)|-|
|**EarthMarker**|**EarthMarker: A Visual Prompting Multi-modal Large Language Model for Remote Sensing**|TGRS 2024|[EarthMarker](https://ieeexplore.ieee.org/abstract/document/10817639)|[link](https://github.com/wivizhang/EarthMarker)|
|**GeoChat**|**GeoChat: Grounded Large Vision-Language Model for Remote Sensing**|CVPR 2024|[GeoChat](https://openaccess.thecvf.com/content/CVPR2024/html/Kuckreja_GeoChat_Grounded_Large_Vision-Language_Model_for_Remote_Sensing_CVPR_2024_paper.html)|[link](https://github.com/mbzuai-oryx/GeoChat)|
|**EarthGPT**|**EarthGPT: A Universal Multimodal Large Language Model for Multisensor Image Comprehension in Remote Sensing Domain**|TGRS 2024|[EarthGPT](https://ieeexplore.ieee.org/abstract/document/10547418)|[link](https://github.com/wivizhang/EarthGPT)|
|**RemoteCLIP**|**RemoteCLIP: A Vision Language Foundation Model for Remote Sensing**|TGRS 2024|[RemoteCLIP](https://arxiv.org/abs/2306.11029)|[link](https://github.com/ChenDelong1999/RemoteCLIP)|
|**RSGPT**|**RSGPT: A Remote Sensing Vision Language Model and Benchmark**|Arxiv 2023|[RSGPT](https://arxiv.org/abs/2307.15266)|[link](https://github.com/Lavender105/RSGPT)|
|**GeoRSCLIP**|**RS5M: A Large Scale Vision-Language Dataset for Remote Sensing Vision-Language Foundation Model**|Arxiv 2023|[GeoRSCLIP](https://arxiv.org/abs/2306.11300)|[link](https://github.com/om-ai-lab/RS5M?tab=readme-ov-file)|
|**GRAFT**|**Remote Sensing Vision-Language Foundation Models without Annotations via Ground Remote Alignment**|ICLR 2024|[GRAFT](https://openreview.net/pdf?id=w9tc699w3Z)|-|
|**CSP**|**CSP: Self-Supervised Contrastive Spatial Pre-Training for Geospatial-Visual Representations**|ICML 2023|[CSP](https://arxiv.org/abs/2305.01118)|[link](https://gengchenmai.github.io/csp-website/)|
|**GeoCLIP**|**GeoCLIP: Clip-Inspired Alignment between Locations and Images for Effective Worldwide Geo-localization**|NeurIPS 2023|[GeoCLIP](https://arxiv.org/abs/2309.16020)|[link](https://vicentevivan.github.io/GeoCLIP/)|
|**SatCLIP**|**SatCLIP: Global, General-Purpose Location Embeddings with Satellite Imagery**|Arxiv 2023|[SatCLIP](https://arxiv.org/abs/2311.17179)|[link](https://github.com/microsoft/satclip)|


&nbsp;

## 问题、反馈和对此存储库的贡献

我欢迎各种反馈，最好通过[GitHub Issues](https://github.com/BaolanChen/Awesome-Remote-Sensing-Cross-Modal-Retrieval/issues) 分享。
同样，如果您有任何疑问或只是想与他人交流想法，请随时发布这些内容。

## 致谢
感谢相关论文、相关项目

## 引用

如果您发现本项目对您的研究有用，请考虑引用它。


