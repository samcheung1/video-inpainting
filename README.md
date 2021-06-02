# Video Inpainting  
视频修复任务是一项旨在用合理的内容填补视频帧中缺失区域的任务。视频修复在各种场景下都有着许多应用，例如将损坏的视频进行修复、将不想要的对象进行删除和视频重定目标等。 

目前的基于深度学习的视频修复工作可以分为三类：  
1.利用3D卷积来进行视频修复  
2.利用光流场来进行视频修复  
3.利用上下文match匹配来进行视频修复  

## 利用3D卷积来进行视频修复  
以下方法通过利用3D卷积来实现视频修复。  

1. [Video inpainting by jointly learning temporal structure and spatial details.](https://arxiv.org/abs/1806.08482) Wang,C.,Huang,H.,Han,X.,& Wang,J.  `In AAAI 2019`  
2. [Deep Blind Video Decaptioning by Temporal Aggregation and Recurrence.](https://openaccess.thecvf.com/content_CVPR_2019/papers/Kim_Deep_Blind_Video_Decaptioning_by_Temporal_Aggregation_and_Recurrence_CVPR_2019_paper.pdf) Kim,D.,Woo,S.,Lee,J.Y.,& Kweon,I. S. `In CVPR 2019`   
3. [Free-form Video Inpainting with 3D Gated Convolution and Temporal PatchGAN](https://arxiv.org/pdf/1904.10247.pdf) Ya-Liang Chang,Zhe Yu Liu,Kuan-Ying Lee,Winston Hsu. `In ICCV 2019` [[code]](https://github.com/amjltc295/Free-Form-Video-Inpainting)
