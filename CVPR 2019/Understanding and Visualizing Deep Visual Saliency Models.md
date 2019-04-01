Understanding and Visualizing Deep Visual Saliency Models [PDF](https://arxiv.org/pdf/1903.02501.pdf)


这篇文章希望回答“what have these models learned, how and where theyfail, and how they can be improved”，通过“nalyzing the representationslearned by individual neurons located at the intermediatelayers of deep saliency models”。
最后证明了以下的观点：  
1） some visual regions(e.g. head, text, symbol, vehicle) are already encoded within various layers of the network pre-trained for object recognition  
   一些视觉区域在浅层就已经被编码了  
2）using modern datasets,  we find that fine-tuningpre-trained models for saliency prediction makes them favor some categories (e.g. head) over some others (e.g. text)  
3）although deep models of saliency outperform classicalmodels on natural images, the converse is true for syntheticstimuli (e.g. pop-out search arrays), an evidence of signif-icant  difference  between  human  and  data-driven  saliencymodels  
4) we confirm that, after-fine tuning, the changein inner-representations is mostly due to the task and not thedomain shift in the datasets  

验证salience mask的作用![image](https://github.com/sunshinee24/Paper/blob/master/CVPR%202019/images/Salience.png)
1）mask是有作用的，第二列的高亮就是mask的地方  
2）在没有mask的时候，依然编码了显著性的region，思考：浅层网络编码纹理等特征是否是个错误的设定？  

fine-tune 中的target改变![image](https://github.com/sunshinee24/Paper/blob/master/CVPR%202019/images/salient.png)
