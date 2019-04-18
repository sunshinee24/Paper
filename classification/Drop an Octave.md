Abstract:
在自然图像处理中，信息是以不同频率传递的，高频率的编码细节信息而低频率的编码全局结构。  
相似的，feature maps可以被看成不同频率的
信息的混合。 在本文中，我们提出通过频率因式分解混合的特征图， 设计了一个Octave卷积操作存储和处理feature maps that vary spatially
“slower”  在低分辨率的时候，减少内存和计算成本。 不同于现有的多尺度方法，Octave卷积 被定义为一个single, generic, plug-andplay convolutional unit，
取代卷积操作但在网络结构中不需要做任何调整。It is also orthogonal and complementary to methods that suggest better topologies or reduce
channel-wise redundancy like group or depth-wise convolutions.
![特征图分解](https://github.com/sunshinee24/Paper/blob/master/classification/images/Octave1.png)

1. (b)->(c)是如何实现的？
在3.1节直接说低频的size变成了w/2,h/2,怎么降采样的？
2. (d)是如何实现的？
![octave卷积](https://github.com/sunshinee24/Paper/blob/master/classification/images/Octave2.png)



论文地址 [PDF](https://arxiv.org/pdf/1904.05049v1.pdf)  
论文代码 [Code](https://github.com/lxtGH/OctaveConv_pytorch)
