
<img src="https://raw.githubusercontent.com/AyaseChihaya/AyaseChihaya.github.io/master/illustration.jpg" width="635">

# Abstract
<p align="justify">
The task of room layout estimation is to locate the wall-floor, wall-ceiling, and wall-wall boundaries. Most recent methods solve this problem based on edge/keypoint detection or semantic segmentation. However, these approaches have shown limited attention on the geometry of the dominant planes and the intersection between them, which has significant impact on room layout. In this work, we propose to incorporate geometric reasoning to deep learning for layout estimation. Our approach learns to infer the depth maps of the dominant planes in the scene by predicting the pixel-level surface parameters, and the layout can be generated by the intersection of the depth maps. Moreover, we present a new dataset with pixel-level depth annotation of dominant planes. It is larger than the existing datasets and contains both cuboid and non-cuboid rooms. Experimental results show that our approach produces considerable performance gains on both 2D and 3D datasets.
</p>

# Paper
Weidong Zhang, Wei Zhang, Yinda Zhang. GeoLayout: Geometry Driven Room Layout Estimation Based on Depth Maps of Planes (ECCV'20)
[[Paper]](https://raw.githubusercontent.com/AyaseChihaya/AyaseChihaya.github.io/master/2606.pdf)


# Matterport3D-Layout dataset
Please visit our [dataset website](https://vsislab.github.io/Matterport3D-Layout/) to download the dataset. 

# Results
Qualitative results on the Matterport3D-Layout dataset. The first two rows are cuboid rooms and the following two rows are non-cuboid rooms. Failure cases are shown in the last two rows.

<img src="https://raw.githubusercontent.com/AyaseChihaya/AyaseChihaya.github.io/master/res3d.jpg" width="625" >

Qualitative results on the LSUN validation set.

<img src="https://raw.githubusercontent.com/AyaseChihaya/AyaseChihaya.github.io/master/res2d.jpg" width="625" >


# Contact
Email | <info@vsislab.com>, <chluzhre@gmail.com>, <yindaz@gmail.com>
