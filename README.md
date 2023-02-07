# [CenterFace Description](https://gitee.com/mindspore/models/blob/r1.6/official/cv/centerface/README.md#contents)

CenterFace is a practical anchor-free face detection and alignment method for edge devices, we support training and evaluation on Ascend910.

Face detection and alignment in unconstrained environment is always deployed on edge devices which have limited memory storage and low computing power. CenterFace proposes a one-stage method to simultaneously predict facial box and landmark location with real-time speed and high accuracy.

[Paper](https://gitee.com/link?target=https%3A%2F%2Farxiv.org%2Fftp%2Farxiv%2Fpapers%2F1911%2F1911.03599.pdf): CenterFace: Joint Face Detection and Alignment Using Face as Point. Xu, Yuanyuan(Huaqiao University) and Yan, Wan(StarClouds) and Sun, Haixin(Xiamen University) and Yang, Genke(Shanghai Jiaotong University) and Luo, Jiliang(Huaqiao University)

# [Model Architecture](https://gitee.com/mindspore/models/blob/r1.6/official/cv/centerface/README.md#contents)

CenterFace uses mobilenet_v2 as pretrained backbone, add 4 layer fpn, with four head. Four loss is presented, total loss is their weighted mean.

[RepoLink](https://gitee.com/mindspore/models/tree/r1.6/official/cv/centerface)