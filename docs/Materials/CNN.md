# Probability vs Likelihood
Intuition : https://jjangjjong.tistory.com/41 <br>
In python : https://yamalab.tistory.com/91?category=709317

# Overview
Different Types of Convolutions : https://towardsdatascience.com/a-comprehensive-introduction-to-different-types-of-convolutions-in-deep-learning-669281e58215<br>
Types of Convolution Kernels : https://towardsdatascience.com/types-of-convolution-kernels-simplified-f040cb307c37<br>
https://www.youtube.com/watch?v=3exMAKtSGBQ

# Deep CNN Networks
conventionally Classification/Localization Problem<br>
LeNet -> AlexNet -> ZFNet -> Inception/VGGNet -> OverFeat -> ResNet

# Object Detection Problem
Region Proposal -> R-CNN -> Fast R-CNN / SPPNet -> Faster R-CNN -> Mask R-CNN(Detectron V1/V2...)<br>

#### Object recognition for dummies (useful link to learn)
https://lilianweng.github.io/lil-log/2017/10/29/object-recognition-for-dummies-part-1.html

## R-CNN
https://github.com/FairyOnIce/ObjectDetectionRCNN (Tensorflow)

## Region Proposal
[Selective Search](http://www.huppelen.nl/publications/selectiveSearchDraft.pdf) : Region Proposal 중 R-CNN에서 사용한 방식 <br>
[Edge Boxes](https://pdollar.github.io/files/papers/ZitnickDollarECCV14edgeBoxes.pdf) : Region Proposal 중 Selective search 다음으로 성능이 좋았던 방식

# Image Segmentation Problem
Region Proposal -> FCN -> U-Net/Dilated Convolution(Atrous Convolution)/Transposed Convolution(Deconvolution) -> SegNet