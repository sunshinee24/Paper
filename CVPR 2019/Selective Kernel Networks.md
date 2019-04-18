论文地址[PDF](https://arxiv.org/pdf/1903.06586.pdf)
代码地址[code](https://github.com/implus/SKNet)

摘要：
在标准的卷积神经网络中，每一层的神经元是享有同样大的感受野大。  
在这篇文章中，我们提出的动态选择机制可以根据输入的尺度信息自适应的选择感受野大的大小。  
选择核（selective kernel），有多个分支荣很而成，分别包含了多个尺寸的卷积核。  
每个分支还有Attention，依靠这些Attention在融合之后产生有效的感受野  
![selective kernel](https://github.com/sunshinee24/Paper/blob/master/CVPR%202019/images/SelecitveKernel.png)
