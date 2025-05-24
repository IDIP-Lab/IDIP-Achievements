# IDIP Achievements
<!-- [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/Tianfang-Zhang/awesome-infrared-small-targets) -->

This webpage serves as a comprehensive compilation platform for all research outcomes and associated links from the IDIP Laboratory. We will progressively compile existing academic achievements while continuously updating the platform with the latest research developments.

We will continue to focus on this field and update relevant information.

Keywords: Infrared small targets detection, infrared small targets segmentation, IDIP.


## [Table of Contents](#table-of-contents)
- [IDIP Achievements](#idip-achievements)
  - [Table of Contents](#table-of-contents)
  - [Infrared Small Target Detection](#infrared-small-target-detection)
    - [Optimization-Based Methods](#optimization-based-methods)
      - [Tensor: Single-Frame](#tensor-single-frame)
    - [Deep Learning-Based Method](#deep-learning-based-method)
      - [Single-Frame](#single-frame)
    - [Deep Unfolding-Based Methods](#deep-unfolding-based-methods)
  - [Infrared Ship Detection](#infrared-ship-detection)
  - [Datasets](#datasets)
    - [Infrared Ship Dataset](#infrared-ship-dataset)
    - [Visible Generic Dataset](#visible-generic-dataset)
  - [Recommended Benchmarks](#recommended-benchmarks)
  - [Webpage](#webpage)
- [Acknowledgement](#acknowledgement)


<!-- ## SOTA Methods with Code

| Title  | Venue | Date  | Code |  Topic  |
|:------|:------:|:------:|:------:|:------:| -->
## [Infrared Small Target Detection](#table-of-contents)
### [Optimization-Based Methods](#table-of-contents)
#### [Tensor: Single-Frame](#table-of-contents)
- **PSTNN**, Infrared small target detection based on partial sum of the tensor nuclear norm.
  - Zhang L, Peng Z. **Remote Sensing, 2019**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://www.mdpi.com/2072-4292/11/4/382) [![](https://img.shields.io/badge/Code-Matlab-orange)](https://github.com/Lanneeee/Infrared-Small-Target-Detection-based-on-PSTNN)
- **NARIRM**, Nonlocal affinity-based robust interference-resistant model for infrared small target detection.
  - J.Deng, X.Cui, K.Li, J.Hu, C.Long, Y.Yin. **GRSL, 2025**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/10980125) [![](https://img.shields.io/badge/Code-python-orange)](https://github.com/djk1997-jk/NARIRM)

### [Deep Learning-Based Method](#table-of-contents)
#### [Single-Frame](#table-of-contents)
- **AGPCNet**, Attention-Guided Pyramid Context Networks for Infrared Small Target Detection.
  - T.Zhang, L.Li, S.Cao, T.Pu, Z.Peng. **TAES, 2023**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://arxiv.org/abs/2111.03580) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/Tianfang-Zhang/AGPCNet)

- **DATransNet**: dynamic attention transformer network for infrared small target detection.
  - C.Hu, Y.Huang, K.Li, L.Zhang, C.Long, Y.Zhu, T.Pu, and Z.Peng. **GRSL, 2025**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/10947728) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/greekinRoma/DATransNet)

### [Deep Unfolding-Based Methods](#table-of-contents)

- **RPCANet**: Deep Unfolding RPCA Based Infrared Small Target Detection.
  - F. Wu, T. Zhang, L. Li, Y. Huang, and Z. Peng. **WACV, 2024**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://openaccess.thecvf.com/content/WACV2024/html/Wu_RPCANet_Deep_Unfolding_RPCA_Based_Infrared_Small_Target_Detection_WACV_2024_paper.html) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/fengyiwu98/RPCANet)
  
## [Infrared Ship Detection](#table-of-contents)
- **SMPISD-MTPNet**: Scene Semantic Prior-Assisted Infrared Ship Detection Using Multitask Perception Networks.
  - C. Hu, X. Dong, Y. Huang, L. Wang, L. Xu and T. Peng. **TGRS, 2024**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/10802996) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/greekinRoma/SMPISD-MTPNet)

## [Datasets](#table-of-contents)
### [Infrared Ship Dataset](#table-of-contents)
- **IRSDSS**: SMPISD-MTPNet: Scene Semantic Prior-Assisted Infrared Ship Detection Using Multitask Perception Networks.
  - C. Hu, X. Dong, Y. Huang, L. Wang, L. Xu and T. Peng. **TGRS, 2024**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/10802996) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/greekinRoma/SMPISD-MTPNet) [![](https://img.shields.io/badge/Link-Dataset-green)](https://pan.baidu.com/s/1FwSVOrNgu1XJO6EvucWNGA?pwd=hchc)
- **EISDD**: SMPISD-MTPNet: Scene Semantic Prior-Assisted Infrared Ship Detection Using Multitask Perception Networks.
  - C. Hu, X. Dong, Y. Huang, L. Wang, L. Xu and T. Peng. **TGRS, 2024**.
  - [![](https://img.shields.io/badge/Link-Paper-blue)](https://ieeexplore.ieee.org/abstract/document/10802996) [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/greekinRoma/SMPISD-MTPNet) [![](https://img.shields.io/badge/Link-Dataset-green)](https://pan.baidu.com/s/1FwSVOrNgu1XJO6EvucWNGA?pwd=hchc)
### [Visible Generic Dataset](#table-of-contents)
- **TeaBudSort_Dataset**: A dataset for Tea Bud Detection.
  - [![](https://img.shields.io/badge/Code-PyTorch-orange)](https://github.com/IDIP-Lab/TeaBudSort#) [![](https://img.shields.io/badge/Link-Dataset-green)](https://huggingface.co/datasets/IDIP-Lab/TeaBudSort_Dataset/tree/main)


## [Recommended Benchmarks](#table-of-contents)
| Title  |  Date  | Link |
|:------|:------:|:------:|
|ISTD Python|2021|https://github.com/Tianfang-Zhang/ISTD-python|

## Webpage
- Github [![](https://img.shields.io/badge/Link-Website-yellow)](https://github.com/IDIP-Lab)
- Hugging Face [![](https://img.shields.io/badge/Link-Website-yellow)](https://huggingface.co/IDIP-Lab)
- Official Laboratory Website [![](https://img.shields.io/badge/Link-Website-yellow)](https://idiplab.uestc.cn/)

# Acknowledgement
This repository was founded by [IDIP-Lab](https://github.com/IDIP-Lab), and is currently updated by [YanHuanghhhh](https://github.com/YanHuanghhhh). If you have any issue, please contact us.


-----
Note:

- ![](https://img.shields.io/badge/Code-PyTorch-orange) represents offical code.
- ![](https://img.shields.io/badge/Code-PyTorch-green) represents reproduced code.
