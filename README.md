# Awesome Transformer Architecture Search: [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

<p align="center">
  <img width="250" src="https://camo.githubusercontent.com/1131548cf666e1150ebd2a52f44776d539f06324/68747470733a2f2f63646e2e7261776769742e636f6d2f73696e647265736f726875732f617765736f6d652f6d61737465722f6d656469612f6c6f676f2e737667" "Awesome!">
</p>

To keep track of the large number of recent papers that look at the intersection of Transformers and Neural Architecture Search (NAS), we have created this _awesome_ list of curated papers and resources, inspired by [awesome-autodl](https://github.com/D-X-Y/Awesome-AutoDL), [awesome-architecture-search](https://github.com/markdtw/awesome-architecture-search), and [awesome-computer-vision](https://github.com/jbhuang0604/awesome-computer-vision). Papers are divided into the following categories:
1. [**General Transformer search**](#general-transformer-search)
2. [**Domain Specific, applied Transformer search (divided into NLP, Vision, ASR)**](#domain-specific-transformer-search)
3. [**Insights on Transformer components or searchable parameters**]()
4. **Transformer Surveys**

This repository is maintained by the [AutoML Group Freiburg](https://www.automl.org/). Please feel free to [pull requests](https://github.com/yashsmehta/awesome-transformer-search/pulls) or [open an issue](https://github.com/yashsmehta/awesome-transformer-search/issues) to add papers.

## General Transformer Search

| Title                                                                                                   | Venue         | Group                  |
|:--------------------------------------------------------------------------------------------------------|:--------------|:-----------------------|
| [UniNet: Unified Architecture Search with Convolutions, Transformer and MLP](https://openreview.net/forum?id=Esk2g83ELUt)                              | arxiv [Oct'21] | SenseTime              |
| [BossNAS: Exploring Hybrid CNN-transformers with Block-wisely Self-supervised Neural Architecture Search](https://arxiv.org/pdf/2103.12424.pdf) | **ICCV'21**       | Sun Yat-sen University |
| [Memory-Efficient Differentiable Transformer Architecture Search](https://aclanthology.org/2021.findings-acl.372.pdf)                              | **ACL-IJCNLP'21** | MSR, Peking University              |
| [Finding Fast Transformers: One-Shot Neural Architecture Search by Component Composition](https://arxiv.org/pdf/2008.06808.pdf)                 | arxiv [Aug'20] | Google Research        |
| [AutoTrans: Automating Transformer Design via Reinforced Architecture Search](https://arxiv.org/pdf/2009.02070.pdf)                             | arxiv [Sep'20] | Fudan University       |
| [NAT: Neural Architecture Transformer for Accurate and Compact Architectures](https://arxiv.org/pdf/1910.14488.pdf)                             | **NeurIPS'19**    | Tencent AI             |
| [The Evolved Transformer](http://proceedings.mlr.press/v97/so19a/so19a.pdf)                                                                                 | **ICML'19**       | Google Brain           |


## Domain Specific Transformer Search
### Vision

| Title                                                                                                   | Venue         | Group                  |
|:--------------------------------------------------------------------------------------------------------|:--------------|:-----------------------|
| [AutoFormer: Searching Transformers for Visual Recognition](https://arxiv.org/pdf/2107.00651.pdf)                              | **ICCV'21** | MSR              |
| [GLiT: Neural Architecture Search for Global and Local Image Transformer](https://arxiv.org/pdf/2107.02960.pdf) | **ICCV'21**       | University of Sydney |
| [Searching for Efficient Multi-Stage Vision Transformers](https://neural-architecture-ppf.github.io/papers/00011.pdf)                             | ICCV'21 workshop | MIT       |
| [HR-NAS: Searching Efficient High-Resolution Neural Architectures with Lightweight Transformers](https://openaccess.thecvf.com/content/CVPR2021/papers/Ding_HR-NAS_Searching_Efficient_High-Resolution_Neural_Architectures_With_Lightweight_Transformers_CVPR_2021_paper.pdf)                             | **CVPR'21**    | Bytedance Inc.             |
| [Vision Transformer Architecture Search](https://arxiv.org/pdf/2106.13700.pdf)                 | arxiv [June'21] | SenseTime, Tsingua University        |


### Natural Language Processing

| Title                                                                                                   | Venue         | Group                  |
|:--------------------------------------------------------------------------------------------------------|:--------------|:-----------------------|
| [NAS-BERT: Task-Agnostic and Adaptive-Size BERT Compression with Neural Architecture Search](https://arxiv.org/pdf/2105.14444.pdf) | **KDD'21**       | MSR, Tsinghua University |
| [AutoBERT-Zero: Evolving the BERT backbone from scratch](https://arxiv.org/pdf/2107.07445.pdf) | arxiv [July'21] | Huawei Noah’s Ark Lab       |
| [HAT: Hardware-Aware Transformers for Efficient Natural Language Processing](https://arxiv.org/pdf/2005.14187.pdf)  | **ACL'20**    | MIT           |


### Automatic Speech Recognition

| Title                                                                                                   | Venue         | Group                  |
|:--------------------------------------------------------------------------------------------------------|:--------------|:-----------------------|
| [Darts-Conformer: Towards Efficient Gradient-Based Neural Architecture Search For End-to-End ASR](https://arxiv.org/pdf/2104.02868.pdf) | arxiv [Aug'21] | NPU, Xi'an       |
| [Improved Conformer-based End-to-End Speech Recognition Using Neural Architecture Search](https://arxiv.org/pdf/2104.05390.pdf) | arxiv [April'21]  | Chinese Academy of Sciences |
| [Evolved Speech-Transformer: Applying Neural Architecture Search to End-to-End Automatic Speech Recognition](https://indico2.conference4me.psnc.pl/event/35/contributions/3122/attachments/301/324/Tue-1-8-5.pdf)  | **INTERSPEECH'20**    | VUNO Inc.           |
