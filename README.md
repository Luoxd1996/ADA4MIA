# ADA4MIA: Active Domain Adaptation for Medical Image Analysis

* **ADA4MIA** is a benchmark repo dedicated to enhancing **Domain Adaptation** and **Active Learning** in medical image analysis. Our goal is to foster robust model development across varied medical datasets, facilitating straightforward evaluation and comparison of different methods.

* This repository collects various **state-of-the-art methods**, **open-source code**, and related **datasets** for the community. **If you are interested, you can push your implementations or ideas to this repo or contact me (hongqiuwang16@gmail.com) at any time**.

* This project was originally developed for our previous works. Now and future, we are still working on extending it to be more user-friendly and support more approaches to further boost and ease this topic research. **If you use this codebase in your research, please cite the following works**:
```
     @article{wang2024dual,
      title={Dual-reference source-free active domain adaptation for nasopharyngeal carcinoma tumor segmentation across multiple hospitals},
      author={Wang, Hongqiu and Chen, Jian and Zhang, Shichen and He, Yuan and Xu, Jinfeng and Wu, Mengwan and He, Jinlan and Liao, Wenjun and Luo, Xiangde},
      journal={IEEE Transactions on Medical Imaging},
      year={2024},
      publisher={IEEE}
    }
  
    @article{wang2024advancing,
      title={Advancing UWF-SLO Vessel Segmentation with Source-Free Active Domain Adaptation and a Novel Multi-Center Dataset},
      author={Wang, Hongqiu and Luo, Xiangde and Chen, Wu and Tang, Qingqing and Xin, Mei and Wang, Qiong and Zhu, Lei},
      journal={arXiv preprint arXiv:2406.13645},
      year={2024}
    }
```

**Outline**

- [ADA4MIA: Active Domain Adaptation for Medical Image Analysis]
  - [1. Datasets](#1-datasets)
  - [2. Source Free Active Domain Adaptation](#2-source-free-active-domain-adaptation)
  - [3. Traditional Domain Adaptation](#3-traditional-domain-adaptation)
  - [4. Active Learning](#4-active-learning)


## 1. Datasets

| Short name | Paper | Source | Code/Project Link  |
| --- | --- | --- | --- |
| STDR | [Dual-Reference Source-Free Active Domain Adaptation for Nasopharyngeal Carcinoma Tumor Segmentation across Multiple Hospitals](https://arxiv.org/abs/2308.08544) | TMI 2024 | [[dataset]](https://github.com/whq-xxh/SFADA-GTV-Seg) |

## 2. Source-Free-Active-Domain-Adaptation

| Short name | Paper | Source | Code/Project Link  |
| --- | --- | --- | --- |
| STDR | [Dual-Reference Source-Free Active Domain Adaptation for Nasopharyngeal Carcinoma Tumor Segmentation across Multiple Hospitals](https://arxiv.org/abs/2308.08544) | TMI 2024 | [[code]](https://github.com/whq-xxh/SFADA-GTV-Seg)  |
| CUP | [Advancing UWF-SLO Vessel Segmentation with Source-Free Active Domain Adaptation and a Novel Multi-Center Dataset](https://arxiv.org/abs/2406.13645) | MICCAI 2024 | [[code]](https://github.com/whq-xxh/SFADA-UWF-SLO)  |

## 3. Traditional Domain Adaptation
| Short name | Paper | Source | Code/Project Link  |
| --- | --- | --- | --- |
| AdaptSeg | [Learning to adapt structured output space for semantic segmentation](https://openaccess.thecvf.com/content_cvpr_2018/html/Tsai_Learning_to_Adapt_CVPR_2018_paper.html) | CVPR 2018 | [[code]](https://github.com/wasidennis/AdaptSegNet)  |
| AdvEnt | [Advent: Adversarial entropy minimization for domain adaptation in semantic segmentation](https://openaccess.thecvf.com/content_CVPR_2019/html/Vu_ADVENT_Adversarial_Entropy_Minimization_for_Domain_Adaptation_in_Semantic_Segmentation_CVPR_2019_paper.html) | CVPR 2019 | [[code]](https://github.com/valeoai/ADVENT) |
| UncertainDA | [Uncertainty reduction for model adaptation in semantic segmentation](https://openaccess.thecvf.com/content/CVPR2021/html/S_Uncertainty_Reduction_for_Model_Adaptation_in_Semantic_Segmentation_CVPR_2021_paper.html?ref=https://githubhelp.com) | CVPR 2021 | [[code]](https://github.com/idiap/model-uncertainty-for-adaptation)  |
| Tent | [Tent: Fully test-time adaptation by entropy minimization](https://arxiv.org/abs/2006.10726) | ICLR 2021 | [[code]](https://github.com/DequanWang/tent)  |

## 4. Active Learning
