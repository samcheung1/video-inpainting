# Video Inpainting  
视频修复任务是一项旨在用合理的内容填补视频帧中缺失区域的任务。视频修复在各种场景下都有着许多应用，例如将损坏的视频进行修复、将不想要的对象进行删除和视频重定目标等。 

目前的基于深度学习的视频修复工作可以分为三类：  
1.利用3D卷积来进行视频修复  
2.利用光流场来进行视频修复  
3.利用上下文match匹配来进行视频修复  

## 利用3D卷积来进行视频修复  
以下方法通过利用3D卷积来实现视频修复。  
1.[Video inpainting by jointly learning temporal structure and spatial details.](https://arxiv.org/abs/1806.08482) Wang, C., Huang, H., Han, X., & Wang, J. In AAAI 2019
