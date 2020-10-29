# cv

## 传统图像处理

SIFT

SURF

## 分类

评价指标：Precision, Recall, AUC, ROC曲线，P-R曲线，FPR，TPR

VGG

ResNet

SENet

DenseNet

Inception系列

Xception

轻量级网络 (MobileNet, ShuffleNet)

### 比赛：

[Bengali.AI Handwritten Grapheme Classification](https://www.kaggle.com/c/bengaliai-cv19/overview)，[第一名](https://www.kaggle.com/c/bengaliai-cv19/discussion/135984)

[Humpback Whale Identification](https://www.kaggle.com/c/humpback-whale-identification/overview)，第一名的[方案](https://www.kaggle.com/c/humpback-whale-identification/discussion/82366)和[代码](https://github.com/earhian/Humpback-Whale-Identification-1st-)，
第2名的[代码](https://github.com/SeuTao/Humpback-Whale-Identification-Challenge-2019_2nd_palce_solution)，
第3名的[方案](https://www.kaggle.com/c/humpback-whale-identification/discussion/82484)和[代码](https://github.com/pudae/kaggle-humpback)，
第4名的[方案](https://www.kaggle.com/c/humpback-whale-identification/discussion/82356)

## GAN

[GAN](https://arxiv.org/abs/1406.2661)

[cGAN](https://arxiv.org/abs/1411.1784)

[DCGAN](https://arxiv.org/abs/1511.06434)

[wGAN](https://arxiv.org/abs/1701.07875)

[CycleGAN](https://arxiv.org/abs/1703.10593)

[StyleGAN](https://arxiv.org/abs/1812.04948)

[pixel-2-pixel](https://arxiv.org/abs/1611.07004)

## 图像超分辨率 （超分）

[SRCNN](https://arxiv.org/abs/1501.00092)

[SRGAN](https://arxiv.org/abs/1609.04802)

[EDSR](https://arxiv.org/abs/1707.02921)

[ESRGAN](https://arxiv.org/abs/1809.00219)

## 检测

评价指标：AP，mAP，IoU，mIoU

[YOLO系列](https://zhuanlan.zhihu.com/p/136382095A)

R-CNN：R-CNN, [Fast-RCNN](http://openaccess.thecvf.com/content_iccv_2015/html/Girshick_Fast_R-CNN_ICCV_2015_paper.html), [Faster R-CNN](http://papers.nips.cc/paper/5638-faster-r-cnn-towards-real-time-object-detection-with-region-proposal-networks), [Mask R-CNN](http://openaccess.thecvf.com/content_iccv_2017/html/He_Mask_R-CNN_ICCV_2017_paper.html), [Cascade R-CNN](http://openaccess.thecvf.com/content_cvpr_2018/html/Cai_Cascade_R-CNN_Delving_CVPR_2018_paper.html)

工具包：[mmdetection](https://mmdetection.readthedocs.io/en/latest/)

anchor-free方法：[Densebox](https://arxiv.org/abs/1509.04874), [CenterNet](http://openaccess.thecvf.com/content_ICCV_2019/html/Duan_CenterNet_Keypoint_Triplets_for_Object_Detection_ICCV_2019_paper.html)，[CornerNet](http://openaccess.thecvf.com/content_ECCV_2018/html/Hei_Law_CornerNet_Detecting_Objects_ECCV_2018_paper.html)，[FCOS](http://openaccess.thecvf.com/content_ICCV_2019/html/Tian_FCOS_Fully_Convolutional_One-Stage_Object_Detection_ICCV_2019_paper.html)，[YOLO系列](https://zhuanlan.zhihu.com/p/136382095)

[RetinaNet和Focal Loss](http://openaccess.thecvf.com/content_iccv_2017/html/Lin_Focal_Loss_for_ICCV_2017_paper.html)

### 数据集/榜单

MS COCO，PASCAL VOC

## 分割

评价指标：Dice

[FCN](https://www.cv-foundation.org/openaccess/content_cvpr_2015/html/Long_Fully_Convolutional_Networks_2015_CVPR_paper.html)

[DeepLab v3+](https://openaccess.thecvf.com/content_ECCV_2018/html/Liang-Chieh_Chen_Encoder-Decoder_with_Atrous_ECCV_2018_paper.html)

[U-Net](https://link.springer.com/chapter/10.1007/978-3-319-24574-4_28)

[Global Convolutional Network](https://openaccess.thecvf.com/content_cvpr_2017/html/Peng_Large_Kernel_Matters_CVPR_2017_paper.html)

[ENet](https://arxiv.org/abs/1606.02147)

[CAM](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Zhou_Learning_Deep_Features_CVPR_2016_paper.pdf)（虽然不是分割的，但是在弱监督分割里面很常用）

[HRNet](http://openaccess.thecvf.com/content_CVPR_2019/html/Sun_Deep_High-Resolution_Representation_Learning_for_Human_Pose_Estimation_CVPR_2019_paper.html)，也可以做分类、检测和人体姿态估计

### 数据集/榜单

PASCAL VOC

[Cityscape](https://www.cityscapes-dataset.com/)（可以一直提交，[第2名](https://arxiv.org/abs/2005.10821)，[第3名](https://arxiv.org/abs/2005.10266),[第4名](https://arxiv.org/abs/1909.11065)，[第5名](https://arxiv.org/abs/1911.10194)）

[KITTI](http://www.cvlibs.net/datasets/kitti/eval_semseg.php?benchmark=semantics2015)

[TGS salt identification](https://www.kaggle.com/c/tgs-salt-identification-challenge/overview)，[第1名](https://www.kaggle.com/c/tgs-salt-identification-challenge/discussion/69291)，[第4名](https://github.com/SeuTao/TGS-Salt-Identification-Challenge-2018-_4th_place_solution)，[第11名](https://www.kaggle.com/c/tgs-salt-identification-challenge/discussion/69093)

[2019 年县域农业大脑AI挑战赛](https://tianchi.aliyun.com/competition/entrance/231717/introduction)（天池平台需要报名参赛才能下载数据），
[第1名](https://tianchi.aliyun.com/forum/postDetail?spm=5176.12586969.1002.6.25ea4054p7VT3O&postId=78945)，
[第2名](https://tianchi.aliyun.com/forum/postDetail?spm=5176.12586969.1002.3.25ea4054sdzwGN&postId=79094)

## 图像检索

数据集/榜单

[Google Landmark Retrieval](https://www.kaggle.com/c/landmark-recognition-2020)（2020年的比赛，kernel-only，只需要提交一个做特征提取的模型、无需后处理），
第1名的[方案](https://www.kaggle.com/c/landmark-recognition-2020/discussion/187821)、[代码](https://github.com/psinger/kaggle-landmark-recognition-2020-1st-place)和[paper](https://arxiv.org/abs/2010.01650)，
第2名的[方案](https://www.kaggle.com/c/landmark-recognition-2020/discussion/188299)和[代码](https://www.kaggle.com/c/landmark-recognition-2020/discussion/188299)，
第3名的[代码](https://github.com/haqishen/Google-Landmark-Recognition-2020-3rd-Place-Solution)



## 图像质量评估

评价指标：SROCC，PLCC

[RANK4IQA](https://arxiv.org/abs/1712.05444)

## 关键点检测

[HourGlass](https://link.springer.com/chapter/10.1007/978-3-319-46484-8_29)，也可以用来做人体姿态估计（和关键点检测是同一类任务）

## 图像配准

Voxelmorph，[论文](https://ieeexplore.ieee.org/abstract/document/8633930/)，[代码](https://github.com/voxelmorph/voxelmorph)

