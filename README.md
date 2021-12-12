# **HDA-Net: Horizontal Deformable Attention Network for Stereo Matching**

Official implementation of paper "HDA-Net: Horizontal Deformable Attention Network for Stereo Matching" (ACM MM2021 Oral)

------

Paper:

[[ACM MM2021]](https://dl.acm.org/doi/abs/10.1145/3474085.3475273)

Author:

Qi Zhang, Xuesong Zhang, Baoping Li, Yuhong Chen, Anlong Ming

Beijing University of Posts and Telecommunications,

## Introduction

Stereo matching is a fundamental and challenging task which has various applications in autonomous driving, dense reconstruction and other depth related tasks. Contextual information with discriminative features is crucial for accurate stereo matching in the ill-posed regions (textureless, occlusion, etc.). In this paper, we propose an efficient horizontal attention module to adaptively capture the global correspondence clues. Compared with the popular non-local attention, our horizontal attention is more effective for stereo matching with better performance and lower consumption of computation and memory. We further introduce a deformable module to refine the contextual information in the disparity discontinuous areas such as the boundary of objects. Learning-based method is adopted to construct the cost volume by concatenating the features of two branches. In order to offer explicit similarity measure to guide learning-based volume for obtaining more reasonable unimodal matching cost distribution we additionally combine the learning-based volume with the improved zero-centered group-wise correlation volume. Finally, we regularize the 4D joint cost volume by a 3D CNN module and generate the final output by disparity regression. The experimental results show that our proposed HDA-Net achieves the state-of-the-art performance on the Scene Flow dataset and obtains competitive performance on the KITTI datasets compared with the relevant networks.

## Citation

If you find our work helpful to your research, please cite our paper:

```
@inbook{10.1145/3474085.3475273,
author = {Zhang, Qi and Zhang, Xuesong and Li, Baoping and Chen, Yuzhong and Ming, Anlong},
title = {HDA-Net: Horizontal Deformable Attention Network for Stereo Matching},
year = {2021},
isbn = {9781450386517},
publisher = {Association for Computing Machinery},
address = {New York, NY, USA},
url = {https://doi.org/10.1145/3474085.3475273},
booktitle = {Proceedings of the 29th ACM International Conference on Multimedia},
pages = {32–40},
numpages = {9}
}
```

## Environmental Setup
