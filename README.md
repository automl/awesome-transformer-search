# Awesome Transformer Architecture Search: [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
  <img width="250" src="https://camo.githubusercontent.com/1131548cf666e1150ebd2a52f44776d539f06324/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f6d61737465722f6d656469612f6c6f676f2e737667" "Awesome!">
</p>

To keep track of the large number of recent papers that look at the intersection of Transformers and Neural Architecture Search (NAS), we have created this _awesome_ list of curated papers and resources, inspired by [awesome-autodl](https://github.com/D-X-Y/Awesome-AutoDL), [awesome-architecture-search](https://github.com/markdtw/awesome-architecture-search), and [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision). Papers are divided into the following categories:
1. [**General Transformer search**](#general-transformer-search)
2. [**Domain Specific, applied Transformer search (divided into NLP, Vision, ASR)**](#domain-specific-transformer-search)
3. [**Transformers Knowledge: Insights / Searchable parameters / Attention**](#transformers-knowledge-insights-searchable-parameters-attention)
4. [**Transformer Surveys**](#transformer-surveys)
5. [**Misc Resources**](#misc-resources)

This repository is maintained by the [AutoML Group Freiburg](https://www.automl.org/). Please feel free to [pull requests](https://github.com/automl/awesome-transformer-search/pulls) or [open an issue](https://github.com/automl/awesome-transformer-search/issues) to add papers.


## General Transformer Search

| Title                                                                                                   | Venue         | Group                  |
|:--------------------------------------------------------------------------------------------------------|:--------------|:-----------------------|
| [LiteTransformerSearch: Training-free On-device Search for Efficient Autoregressive Language Models](https://arxiv.org/pdf/2203.02094.pdf) | arxiv [March'22]|  MSR |
| [Training Free Transformer Architecture Search](https://arxiv.org/abs/2203.12217)                    | **CVPR'22** |  Tencent & Xiamen University |
| [Searching the Search Space of Vision Transformer](https://proceedings.neurips.cc/paper/2021/file/48e95c45c8217961bf6cd7696d80d238-Paper.pdf)                    | **NeurIPS'21** | MSRA, Stony Brook University              |
| [UniNet: Unified Architecture Search with Convolutions, Transformer and MLP](https://arxiv.org/pdf/2110.04035.pdf)                              | arxiv [Oct'21] | SenseTime              |
| [Analyzing and Mitigating Interference in Neural Architecture Search](https://arxiv.org/pdf/2108.12821.pdf)                              | arxiv [Aug'21] | Tsinghua, MSR         |
| [BossNAS: Exploring Hybrid CNN-transformers with Block-wisely Self-supervised Neural Architecture Search](https://arxiv.org/pdf/2103.12424.pdf) | **ICCV'21**       | Sun Yat-sen University |
| [Memory-Efficient Differentiable Transformer Architecture Search](https://aclanthology.org/2021.findings-acl.372.pdf)                              | **ACL-IJCNLP'21** | MSR, Peking University              |
| [Finding Fast Transformers: One-Shot Neural Architecture Search by Component Composition](https://arxiv.org/pdf/2008.06808.pdf)                 | arxiv [Aug'20] | Google Research        |
| [AutoTrans: Automating Transformer Design via Reinforced Architecture Search](https://arxiv.org/pdf/2009.02070.pdf)                             | arxiv [Sep'20] | Fudan University       |
| [NASABN: A Neural Architecture Search Framework for Attention-Based Networks](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9207600)                                                                                 | **IJCNN'20**       | Chinese Academy of Sciences           |
| [NAT: Neural Architecture Transformer for Accurate and Compact Architectures](https://arxiv.org/pdf/1910.14488.pdf)                             | **NeurIPS'19**    | Tencent AI             |
| [The Evolved Transformer](http://proceedings.mlr.press/v97/so19a/so19a.pdf)                                                                                 | **ICML'19**       | Google Brain           |


## Domain Specific Transformer Search
### Vision

| Title                                                                                                   | Venue         | Group                  |
|:--------------------------------------------------------------------------------------------------------|:--------------|:-----------------------|
| [𝛼NAS: Neural Architecture Search using Property Guided Synthesis](https://arxiv.org/abs/2205.03960)        | arxiv |  MIT, Google  |
| [NASViT: Neural Architecture Search for Efficient Vision Transformers with Gradient Conflict aware Supernet Training](https://openreview.net/pdf?id=Qaw16njk6L)        | **ICLR'22** |  Meta Reality Labs    |
| [AutoFormer: Searching Transformers for Visual Recognition](https://arxiv.org/pdf/2107.00651.pdf)                              | **ICCV'21** | MSR              |
| [GLiT: Neural Architecture Search for Global and Local Image Transformer](https://arxiv.org/pdf/2107.02960.pdf) | **ICCV'21**       | University of Sydney |
| [Searching for Efficient Multi-Stage Vision Transformers](https://neural-architecture-ppf.github.io/papers/00011.pdf)                             | ICCV'21 workshop | MIT       |
| [HR-NAS: Searching Efficient High-Resolution Neural Architectures with Lightweight Transformers](https://openaccess.thecvf.com/content/CVPR2021/papers/Ding_HR-NAS_Searching_Efficient_High-Resolution_Neural_Architectures_With_Lightweight_Transformers_CVPR_2021_paper.pdf)                             | **CVPR'21**    | Bytedance Inc.             |
| [ViTAS: Vision Transformer Architecture Search](https://arxiv.org/pdf/2106.13700.pdf)                 | arxiv [June'21] | SenseTime, Tsingua University        |


### Natural Language Processing

| Title                                                                                                   | Venue         | Group                  |
|:--------------------------------------------------------------------------------------------------------|:--------------|:-----------------------|
| [AutoBERT-Zero: Evolving the BERT backbone from scratch](https://arxiv.org/pdf/2107.07445.pdf) | **AAAI'22** | Huawei Noah’s Ark Lab       |
| [Primer: Searching for Efficient Transformers for Language Modeling](https://arxiv.org/pdf/2109.08668.pdf)  | **NeurIPS'21**    | Google           |
| [AutoTinyBERT: Automatic Hyper-parameter Optimization for Efficient Pre-trained Language Models](https://aclanthology.org/2021.acl-long.400.pdf)  | **ACL'21**    | Tsinghua, Huawei Naoh's Ark    |
| [NAS-BERT: Task-Agnostic and Adaptive-Size BERT Compression with Neural Architecture Search](https://arxiv.org/pdf/2105.14444.pdf) | **KDD'21**       | MSR, Tsinghua University |
| [HAT: Hardware-Aware Transformers for Efficient Natural Language Processing](https://arxiv.org/pdf/2005.14187.pdf)  | **ACL'20**    | MIT           |

### Automatic Speech Recognition

| Title                                                                                                   | Venue         | Group                  |
|:--------------------------------------------------------------------------------------------------------|:--------------|:-----------------------|
| [LightSpeech: Lightweight and Fast Text to Speech with Neural Architecture Search](https://arxiv.org/abs/2102.04040) | **ICASSP'21** | MSR       |
| [Efficient Gradient-Based Neural Architecture Search For End-to-End ASR](https://dl.acm.org/doi/abs/10.1145/3461615.3491109) | ICMI-MLMI'21 | NPU, Xi'an       |
| [Improved Conformer-based End-to-End Speech Recognition Using Neural Architecture Search](https://arxiv.org/pdf/2104.05390.pdf) | arxiv [April'21]  | Chinese Academy of Sciences |
| [Evolved Speech-Transformer: Applying Neural Architecture Search to End-to-End Automatic Speech Recognition](https://indico2.conference4me.psnc.pl/event/35/contributions/3122/attachments/301/324/Tue-1-8-5.pdf)  | **INTERSPEECH'20**    | VUNO Inc.           |


### Transformers Knowledge: Insights, Searchable parameters, Attention

| Title                                                                                                   | Venue         | Group                  |
|:--------------------------------------------------------------------------------------------------------|:--------------|:-----------------------|
| [Seperable Self Attention for Mobile Vision Transformers](https://arxiv.org/abs/2206.02680)  | arxiv'22 | Apple |
| [EfficientFormer: Vision Transformers at MobileNet Speed](https://arxiv.org/abs/2206.01191)  | arxiv'22 | Snap Inc |
| [Neighborhood Attention Transformer](https://arxiv.org/pdf/2204.07143.pdf)  | arxiv'22 | Meta AI |
| [Training Compute Optimal Large Language Models](https://arxiv.org/pdf/2203.15556.pdf)  | arxiv'22 | DeepMind |
| [Parameter-efficient Fine-tuning for Vision Transformers](https://arxiv.org/pdf/2203.16329.pdf)  | arxiv | MSR & UCSC |
| [CMT: Convolutional Neural Networks meet Vision Transformers](https://openaccess.thecvf.com/content/CVPR2022/html/Guo_CMT_Convolutional_Neural_Networks_Meet_Vision_Transformers_CVPR_2022_paper.html)  | **CVPR'22** | Huawei Noah’s Ark Lab |
| [Patch Slimming for Efficient Vision Transformers](https://openaccess.thecvf.com/content/CVPR2022/html/Tang_Patch_Slimming_for_Efficient_Vision_Transformers_CVPR_2022_paper.html)  | **CVPR'22** | Huawei Noah’s Ark Lab |
| [Lite Vision Transformer with Enhanced Self-Attention](https://arxiv.org/abs/2112.10809)  | **CVPR'22** | Johns Hopkins University, Adobe |
| [TubeDETR: Spatio-Temporal Video Grounding with Transformers](https://arxiv.org/pdf/2203.16434.pdf)  | **CVPR'22 (Oral)** | CNRS & Inria |
| [Beyond Fixation: Dynamic Window Visual Transformer](https://arxiv.org/abs/2203.12856)  | **CVPR'22** | UT Sydney & RMIT University |
| [BEiT: BERT Pre-Training of Image Transformers](https://openreview.net/forum?id=p-BhZSz59o4)  | **ICLR'22 (Oral)** | MSR |
| [How Do Vision Transformers Work?](https://openreview.net/forum?id=D78Go4hVcxO)  | **ICLR'22 (Spotlight)** | NAVER AI |
| [Scale Efficiently: Insights from Pretraining and FineTuning Transformers](https://openreview.net/pdf?id=f2OYVDyfIB)  | **ICLR'22** | Google Research |
| [Tuformer: Data-Driven Design of Expressive Transformer by Tucker Tensor Representation](https://openreview.net/pdf?id=V0A5g83gdQ_)  | **ICLR'22** | UoMaryland |
| [DictFormer: Tiny Transformer with Shared Dictionary](https://openreview.net/pdf?id=GWQWAeE9EpB)  | **ICLR'22** | Samsung Research |
| [QuadTree Attention for Vision Transformers](https://arxiv.org/pdf/2201.02767.pdf)  | **ICLR'22** | Alibaba AI Lab |
| [Expediting Vision Transformers via Token Reorganization](https://openreview.net/pdf?id=BjyvwnXXVn_)  | **ICLR'22 (Spotlight)** | UC San Diego & Tencent AI Lab |
| [UniFormer: Unified Transformer for Efficient Spatial-Temporal Representation Learning](https://openreview.net/forum?id=nBU_u6DLvoK)  | arxiv | - |
| [Patches are All You Need ?](https://openreview.net/pdf?id=TVHS5Y4dNvM)                              | arxiv'22 | - |
| [Hierarchical Transformers Are More Efficient Language Models](https://arxiv.org/pdf/2110.13711.pdf)       | arxiv'21 | Google Research, UoWarsaw |
| [Transformer in Transformer](https://papers.nips.cc/paper/2021/file/854d9fca60b4bd07f9bb215d59ef5561-Paper.pdf)    | **NeurIPS'21** | Huawei Noah's Ark |
| [Long-Short Transformer: Efficient Transformers for Language and Vision](https://papers.nips.cc/paper/2021/file/9425be43ba92c2b4454ca7bf602efad8-Paper.pdf)  | **NeurIPS'21** | NVIDIA |
| [Memory-efficient Transformers via Top-k Attention](https://aclanthology.org/2021.sustainlp-1.5.pdf)  | EMNLP Workshop '21 | Allen AI |
| [Swin Transformer: Hierarchical Vision Transformer using Shifted Windows](https://arxiv.org/pdf/2103.14030.pdf)                              | **ICCV'21 best paper** | MSR |
| [Rethinking Spatial Dimensions of Vision Transformers](https://arxiv.org/pdf/2103.16302.pdf)                              | **ICCV'21** | NAVER AI |
| [What makes for hierarchical vision transformers](https://arxiv.org/pdf/2107.02174.pdf)                                                                                 | arxiv [Sept'21]       | HUST           |
| [AutoAttend: Automated Attention Representation Search](http://proceedings.mlr.press/v139/guan21a/guan21a.pdf) | **ICML'21**       | Tsinghua University |
| [Rethinking Attention with Performers](https://openreview.net/pdf?id=Ua6zuk0WRH)                              | **ICLR'21 Oral** | Google              |
| [LambdaNetworks: Modeling long-range Interactions without Attention](https://openreview.net/forum?id=xTJEN-ggl1b)                 | **ICLR'21** | Google Research        |
| [HyperGrid Transformers](https://openreview.net/pdf?id=hiq1rHO8pNT)                             | **ICLR'21** | Google Research       |
| [LocalViT: Bringing Locality to Vision Transformers](https://arxiv.org/pdf/2104.05707.pdf)                             | arxiv [April'21]   | ETH Zurich            |
| [Compressive Transformers for Long Range Sequence Modelling](https://openreview.net/forum?id=SylKikSYDH)                                                                                 | **ICLR'20**       | DeepMind     |
| [Improving Transformer Models by Reordering their Sublayers](https://arxiv.org/pdf/1911.03864.pdf)                                                                                 | **ACL'20**       | FAIR, Allen AI           |
| [Analyzing Multi-Head Self-Attention: Specialized Heads Do the Heavy Lifting, the Rest Can Be Pruned](https://www.aclweb.org/anthology/P19-1580.pdf)                                                                                 | **ACL'19**       | Yandex           |

## Transformer Surveys
| Title                                                                                                   | Venue         | Group                  |
|:--------------------------------------------------------------------------------------------------------|:--------------|:-----------------------|
| [Transformers in Vision: A Survey](https://arxiv.org/pdf/2101.01169.pdf) | arxiv [Oct'21] | MBZ University of AI      |
[Neural Architecture Search for Transformers: A Survey](https://ieeexplore.ieee.org/document/9913476) | IEEE xplore [Sep'22] | Iowa State Uni |
| [A Survey of Visual Transformers](https://arxiv.org/pdf/2111.06091.pdf) | arxiv [Nov'21]  | CAS |
| [Efficient Transformers: A Survey](https://arxiv.org/pdf/2009.06732.pdf) | arxiv [Sept'21]  | Google Research |

### Misc resources
- [Awesome Visual Transformer](https://github.com/dk-liang/Awesome-Visual-Transformer)
- [Vision Transformer & Attention Awesome List](https://github.com/cmhungsteve/Awesome-Transformer-Attention)

