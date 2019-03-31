Chinese explanation: [链接](https://mp.weixin.qq.com/s/SsXqcL5evYUw3KoxIq60kQ)

注意理解几个概念：
1) Unit of length
2) Natural Representation
3) Aligned Representation ![image](https://github.com/sunshinee24/Paper/blob/master/segmentation/images/TensorMask_Aligned_representation.jpg)

左图为自然表征，其中 (V, U) 子张量表示以该像素为中心的窗口。右图为对齐表征，(V hat, U hat) 子张量表示该像素在各窗口的值。
在表征的时候，移动了(V,U)这个窗口，从左到右，以颜色区分

4) Coordinate Transformation
5) Upscaling Transformation
6) Bipyramid
