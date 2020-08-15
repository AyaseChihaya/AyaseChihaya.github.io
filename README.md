![image](https://github.com/AyaseChihaya/AyaseChihaya.github.io/blob/master/illustration.jpg)

# Abstract
The task of room layout estimation is to locate the wall-floor, wall-ceiling, and wall-wall boundaries. Most recent methods solve this problem based on edge/keypoint detection or semantic segmentation. However, these approaches have shown limited attention on the geometry of the dominant planes and the intersection between them, which has significant impact on room layout. In this work, we propose to incorporate geometric reasoning to deep learning for layout estimation. Our approach learns to infer the depth maps of the dominant planes in the scene by predicting the pixel-level surface parameters, and the layout can be generated by the intersection of the depth maps. Moreover, we present a new dataset with pixel-level depth annotation of dominant planes. It is larger than the existing datasets and contains both cuboid and non-cuboid rooms. Experimental results show that our approach produces considerable performance gains on both 2D and 3D datasets.
