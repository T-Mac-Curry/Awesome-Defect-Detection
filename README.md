# Awesome Defect Detection

If you have any problems, suggestions or improvements, please submit the issue or PR.

## Contents
* [Misc](#misc)
* [Datasets](#datasets)
* [Papers](#papers)
* [Leaderboard](#leaderboard)

## Misc



### Challenge
- 异常检测（anomaly/ outlier detection）领域还有那些值得研究的问题？[[Link](https://mp.weixin.qq.com/s/9LARhkDabD5kLwqFf8GBdA)]



### Code


### Technical blog
- [Chinese Blog] 基于深度学习的缺陷检测算法汇总 [[Link](https://mp.weixin.qq.com/s/0yIetPltdvFkCe4kwpGa2w)]
- [Chinese Blog] 表面缺陷检测数据集汇总及其相关项目推荐 [[Link](https://mp.weixin.qq.com/s?__biz=MzI5MDUyMDIxNA==&mid=2247498632&idx=2&sn=a39387b9c15794393eb6e2c9561616cf&chksm=ec1c1671db6b9f676670c815e540bc5fadc2d94ac05404d0dcfbca82f5f93bc09331fb61c95d&scene=21#wechat_redirect)]
### Tricks
- [Chinese Blog] 深度学习训练tricks总结（均有实验支撑） [[Link](https://mp.weixin.qq.com/s?__biz=Mzg4ODA3OTcyNA==&mid=2247502051&idx=3&sn=761cc7b908f14bc64fc028db0e97274e&chksm=cf821ce0f8f595f60706a860e87b4169432fa91101875797cff772916cca47fb2002e00e292d&mpshare=1&scene=1&srcid=10224rDFCVIXmpVIB9Rz0WvV&sharer_sharetime=1603361600193&sharer_shareid=fd8c7684b39b2eac07b5e0c63bf1346a&key=98afdbf20ac9b6e8132e0838603e4323a86efc4bc50f877a881004c36b75d0448370a9483569cdeedc40a3eae7be56431cca20d5f3c11ae1833bc54cbf769e6bfa0e57737d6261032c9f9159ae0b0a1f4730d92103221e34cca6ee87cfbf713dbee1c22ac7e43bf10c7465375c7acba82ee2ac2f694c92d434916ac83fab97f6&ascene=1&uin=Mjg1Mzg0ODMzMA%3D%3D&devicetype=Windows+10+x64&version=6300002f&lang=zh_CN&exportkey=AaoFLlmx7O6NSdJ2EYllnKA%3D&pass_ticket=Cz67wUTL3RpVi0NHLVPCJOM8DtIHGFNJZqgE5Tk%2FDHEDHwgbRWtMAfGco6cfR%2BOZ&wx_header=0)]
- [Chinese Blog] 深度学习调参tricks总结 [[Link](https://mp.weixin.qq.com/s?__biz=MzI5MDUyMDIxNA==&mid=2247510986&idx=1&sn=bce091af523416fe54d9d1b24fba94d3&chksm=ec1c4633db6bcf25721b1def549c324092180b17e5a0e509369af7f1d9793798633c3593f5fb&mpshare=1&scene=1&srcid=1022TwUZyqXynikueAXZS4om&sharer_sharetime=1603361629913&sharer_shareid=fd8c7684b39b2eac07b5e0c63bf1346a&key=98afdbf20ac9b6e87aae628597c8cd0f5253b5ab624b1569558cc44b37e2c3b23172411592aa8902e533dbfd149751629c64688e305971bcfbb4d2ef540e83f639de23c2faa34a0d9a7695bcfcb5d2865734c7db87f260d7f29b4d46bf3b87d2838c8c2c52828b9c1d879f3ce40c5ac66966c010928f5a3c8ee6794369171806&ascene=1&uin=Mjg1Mzg0ODMzMA%3D%3D&devicetype=Windows+10+x64&version=6300002f&lang=zh_CN&exportkey=AZbS3PAhj53%2Bh67o0ifJEv4%3D&pass_ticket=Cz67wUTL3RpVi0NHLVPCJOM8DtIHGFNJZqgE5Tk%2FDHEDHwgbRWtMAfGco6cfR%2BOZ&wx_header=0)]

- [Chinese Blog] 谷歌自动数据增强算法RandAugment，极大简化搜索空间，平衡成本与性能 [[Link](https://mp.weixin.qq.com/s?__biz=MzI5MDUyMDIxNA==&mid=2247510988&idx=1&sn=59df689486d7ae45700651d027d858cc&chksm=ec1c4635db6bcf2379f1723941537a303598644aaf54e11b7eb32f6cf4ce8b790d0585c24091&mpshare=1&scene=1&srcid=1017bmbKXmHu3V8KE5cmm0nF&sharer_sharetime=1602947045781&sharer_shareid=fd8c7684b39b2eac07b5e0c63bf1346a&key=b0e41fc55fd7ea00ce73783ebaba5e0a4be9e02dc406d950dc14b9886b502ec802e039e30b9913dd6e23243f0c5bc6e789e7caab9c8997a5d35303de4d2975ecdbfd72e48291b556e97c5209d3b1e0316a006b77ab73c75a877c3bfd7c45cdfaadbf70308e121c969d70d19eab5ea6f88f3af31fb04a44b31585b11a9e27952f&ascene=1&uin=Mjg1Mzg0ODMzMA%3D%3D&devicetype=Windows+10+x64&version=6300002f&lang=zh_CN&exportkey=AWJGUUCV7ePJFpA89qhSBs8%3D&pass_ticket=Cz67wUTL3RpVi0NHLVPCJOM8DtIHGFNJZqgE5Tk%2FDHEDHwgbRWtMAfGco6cfR%2BOZ&wx_header=0)][[paper](https://arxiv.org/abs/1909.13719)][[code](https://github.com/tensorflow/tpu/blob/master/models/official/efficientnet/autoaugment.py)]
## Datasets

Please refer to [this page](src/Datasets.md).

## Papers

Considering the increasing number of papers in this field, we roughly summarize some articles and put them into the following categories (they are still listed in this document):


### arXiv papers
Note that all unpublished arXiv papers are not included in [the leaderboard of performance](#performance).

- Segmentation-Based Deep-Learning Approach for Surface-Defect (SCI)[[paper](https://arxiv.org/abs/1903.08536v3)][[code](https://arxiv.org/abs/1903.08536v3)]
- Same Same But DifferNet: Semi-Supervised Defect Detection with Normalizing Flows [[paper](https://arxiv.org/abs/2008.12577)]
- Deep Learning for Anomaly Detection: A Survey [[paper](https://arxiv.org/abs/1901.03407v1)][[code](https://github.com/fastforwardlabs/deepad?utm_source=catalyzex.com)]







<details>
<summary>Earlier ArXiv Papers</summary>

</details>


### 2020

- Inspection of Imprint Defects in Stamped Metal Surfaces using Deep Learning and Tracking (IEEE-TIE)[[paper](https://ieeexplore.ieee.org/document/9062515)]
- <a name="D-ConvNet"></a> **[RPAN]** Deep Learning-based Solar-Cell Manufacturing Defect Detection with Complementary Attention Network (Network-TII)[[paper](https://ieeexplore.ieee.org/document/9136904)]
- <a name="D-ConvNet"></a> **[PGA-Net]** PGA-Net: Pyramid Feature Fusion and Global Context Attention Network for Automated Surface Defect Detection (IEEE-TII)[[paper](https://ieeexplore.ieee.org/document/8930292)]
- Deep-Learning-Based Small Surface Defect Detection via an Exaggerated Local Variation-Based Generative Adversarial Network (IEEE-TII)[[paper](https://ieeexplore.ieee.org/document/8859390)]
- <a name="D-ConvNet"></a> **[ESP]** Surface Defect Detection via Entity Sparsity Pursuit With Intrinsic Priors (IEEE-TII)[[paper](https://ieeexplore.ieee.org/document/8717723)]
- <a name="D-ConvNet"></a> **[NDT]** Multiview Learning for Subsurface Defect Detection in Composite Products: A Challenge on Thermographic Data Analysis (IEEE-TII)[[paper](https://ieeexplore.ieee.org/document/8949715)]
- <a name="D-ConvNet"></a> **[ERSCD]** A Surface Defect Detection Framework for Glass Bottle Bottom Using Visual Attention Model and Wavelet Transform (IEEE-TII)[[paper](https://ieeexplore.ieee.org/document/8795569)]
- <a name="D-ConvNet"></a> **[WGANs]** A learning-based approach for surface defect detection using small image datasets [[paper](https://www.sciencedirect.com/science/article/pii/S0925231220303386?via%3Dihub)]
- <a name="D-ConvNet"></a> **[Faster VG-RCNN]** Detecting textile micro-defects: A novel and efficient method based on visual gain mechanism [[paper](https://www.sciencedirect.com/science/article/pii/S0020025520306216?via%3Dihub)]
- An Efficient Convolutional Neural Network Model Based on Object-Level Attention Mechanism for Casting Defect Detection on Radiography Images (IEEE-TIE)[[paper](https://ieeexplore.ieee.org/document/8948332)]
- <a name="D-ConvNet"></a> **[GAN]** Multistage GAN for Fabric Defect Detection (IEEE-TIP)[[paper](https://ieeexplore.ieee.org/document/8937049)]
- A simulation-based few samples learning method for surface defect segmentation [[paper](https://www.sciencedirect.com/science/article/pii/S0925231220310791?via%3Dihub)]


- A Generic Semi-Supervised Deep Learning-Based Approach for Automated Surface Inspection (IEEE-Access)[[paper](https://ieeexplore.ieee.org/document/9121251)]
- A novel algorithm for defect extraction and classification of mobile phone screen based on machine vision (Inf Fusion)[[paper](https://www.sciencedirect.com/science/article/pii/S0360835220302643)]
- A Steel Surface Defect Recognition Algorithm Based on Improved Deep Learning Network Model Using Feature Visualization and Quality Evaluation (IEEE-Access)[[paper](https://ieeexplore.ieee.org/document/9031427)]
- Automated defect inspection system for metal surfaces based on deep learning and data augmentation (Inf Fusion)[[paper](https://www.sciencedirect.com/science/article/pii/S027861252030042X)]
- <a name="D-ConvNet"></a> **[CADN]** CADN: A weakly supervised learning-based category-aware object detection network for surface defect detection (Inf Fusion)[[paper](https://www.sciencedirect.com/science/article/pii/S0031320320303745)]
- <a name="D-ConvNet"></a> **[PDDNet]** Defect Detection of Pantograph Slide Based on Deep Learning and Image Processing Technology (IEEE-TITS)[[paper](https://ieeexplore.ieee.org/document/8667891)]
- Detection of PCB Surface Defects With Improved Faster-RCNN and Feature Pyramid Network (IEEE Access)[[paper](https://ieeexplore.ieee.org/document/9113299)]
- Detection of PV Solar Panel Surface Defects using Transfer Learning of the Deep Convolutional Neural Networks (ASET)[[paper](https://ieeexplore.ieee.org/document/9118382)]
- Electronic Product Surface Defect Detection Based on a MSSD Network (IEEE-ITNEC)[[paper](https://ieeexplore.ieee.org/document/9084756)]
- Research on Defect Detection Method for Steel Metal Surface based on Deep Learning (IEEE-ITOEC)[[paper](https://ieeexplore.ieee.org/document/9141669)]
- Surface damage detection for steel wire ropes using deep learning and computer vision techniques [[paper](https://www.sciencedirect.com/science/article/pii/S026322412030381X)]


### 2019

- <a name="D-ConvNet"></a> **[ESP]** Surface Defect Detection via Entity Sparsity Pursuit With Intrinsic Priors (IEEE-TII)[[paper](https://ieeexplore.ieee.org/document/8717723/authors#authors)]
- <a name="D-ConvNet"></a> **[CODEBRIM]** Meta-learning Convolutional Neural Architectures for Multi-target Concrete Defect Classiﬁcation with the COncrete DEfect BRidge IMage Dataset(CVPR-2019)[[paper](https://openaccess.thecvf.com/content_CVPR_2019/papers/Mundt_Meta-Learning_Convolutional_Neural_Architectures_for_Multi-Target_Concrete_Defect_Classification_With_CVPR_2019_paper.pdf)]
- <a name="D-ConvNet"></a> **[SDD-CNN]** applsci-SDD-CNN Small Data-Driven Convolution Neural Networks for Subtle Roller Defect Inspection(Applied Sciences) [[paper](https://www.mdpi.com/2076-3417/9/7/1364)]
- An End-to-End Steel Surface Defect Detection Approach via Fusing Multiple Hierarchical Features (IEEE-TIM)[[paper](https://repository.lboro.ac.uk/articles/journal_contribution/An_end-to-end_steel_surface_defect_detection_approach_via_fusing_multiple_hierarchical_features/12249215)]
- A New Self-Reference Image Decomposition Algorithm for Strip Steel Surface Defect Detection(IEEE-TIM) [[paper](https://ieeexplore.ieee.org/abstract/document/8897030)]
- Automatic fabric defect detection with a wide-and-compact network [[paper](https://www.sciencedirect.com/science/article/pii/S0925231218313109?via%3Dihub)]
- AnomalyNet: An Anomaly Detection Network for Video Surveillance (IEEE-TIFS)[[paper](https://ieeexplore.ieee.org/document/8649753)]
- Anomaly Detection in Images (CVPR-2019)[[paper](https://arxiv.org/abs/1905.13147)]


### 2018

- <a name="SANet"></a> **[CTFM]** A Coarse-to-Fine Model for Rail Surface Defect Detection (IEEE-TIM)[[paper](https://ieeexplore.ieee.org/abstract/document/8424494)]
- <a name="SANet"></a> **[MIL]** Real-world Anomaly Detection in Surveillance Videos (CVPR-2018)[[paper](https://openaccess.thecvf.com/content_cvpr_2018/papers/Sultani_Real-World_Anomaly_Detection_CVPR_2018_paper.pdf)][[code](https://github.com/root-master/pose-anomaly-detection?utm_source=catalyzex.com)]


### 2017



## Leaderboard
The section is being continually updated. Note that some values have superscript, which indicates their source. 


