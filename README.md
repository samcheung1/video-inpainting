# Video Inpainting  
视频修复任务是一项旨在用合理的内容填补视频帧中缺失区域的任务。视频修复在各种场景下都有着许多应用，例如将损坏的视频进行修复、将不想要的对象进行删除和视频重定目标等。 

目前的基于深度学习的视频修复工作可以分为三类：  
**1. 利用3D卷积来进行视频修复**   
**2. 利用光流场来进行视频修复**    
**3. 利用上下文patch匹配来进行视频修复** 

## 利用3D卷积来进行视频修复  
以下方法通过利用3D卷积来实现视频修复:  

1. [Video inpainting by jointly learning temporal structure and spatial details.](https://arxiv.org/abs/1806.08482) Wang,C., Huang,H., Han, X., & Wang, J.  `In AAAI 2019`  
2. [Deep Blind Video Decaptioning by Temporal Aggregation and Recurrence.](https://openaccess.thecvf.com/content_CVPR_2019/papers/Kim_Deep_Blind_Video_Decaptioning_by_Temporal_Aggregation_and_Recurrence_CVPR_2019_paper.pdf) Kim, D., Woo, S., Lee, J.Y., & Kweon, I. S. `In CVPR 2019`   
3. [Free-form Video Inpainting with 3D Gated Convolution and Temporal PatchGAN](https://arxiv.org/pdf/1904.10247.pdf) Ya-Liang Chang, Zhe Yu Liu, Kuan-Ying Lee, Winston Hsu. `In ICCV 2019` [[code]](https://github.com/amjltc295/Free-Form-Video-Inpainting)
4. [Learnable Gated Temporal Shift Module for Deep Video Inpainting](https://arxiv.org/pdf/1907.01131.pdf) Ya-Liang Chang, Zhe Yu Liu, Kuan-Ying Lee, Winston Hsu. `In BMVC 2019` [[code]](https://github.com/amjltc295/Free-Form-Video-Inpainting)
5. [Proposal-based Video Completion](https://www.cs.utexas.edu/~grauman/papers/eccv2020-hu.pdf) Hu et al. `In ECCV2020`  
 
## 利用光流场来进行视频修复
以下方法通过利用光流场来实现视频修复：

1. [Deep Flow-Guided Video Inpainting](https://arxiv.org/pdf/1905.02884.pdf) Xu, R., Li, X., Zhou, B., & Loy, C. C. `In CVPR 2019` [[code]](https://github.com/nbei/Deep-Flow-Guided-Video-Inpainting)
2. [Frame-Recurrent Video Inpainting by Robust Optical Flow Inference](https://arxiv.org/pdf/1905.02882.pdf) Yifan Ding, Chuan Wang, Haibin Huang, Jiaming Liu, Jue Wang, Liqiang Wang. `In Arxiv 2019`  
3. [VORNet: Spatio-temporally Consistent Video Inpainting for Object Removal](https://arxiv.org/pdf/1904.06726.pdf) Ya-Liang Chang, Zhe Yu Liu, Winston Hsu.` In CVPRW 2019` 
4. [An Internal Learning Approach to Video Inpainting](https://arxiv.org/pdf/1909.07957.pdf) Haotian Zhang, Long Mai, Ning Xu, Zhaowen Wang, John Collomosse, Hailin Jin. `In ICCV 2019`   
5. [Flow-edge Guided Video Completion](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123570698.pdf) Gao et al. `In ECCV2020` [[code]](https://github.com/vt-vl-lab/FGVC)  

## 利用上下文patch匹配来进行视频修复  
以下方法通过利用上下文patch匹配来进行视频修复  
1. [Deep Video Inpainting.](https://arxiv.org/pdf/1905.01639.pdf) Kim, D., Woo, S., Lee, J. Y., & Kweon, I. S. `In CVPR 2019` [[code]](https://github.com/mcahny/Deep-Video-Inpainting)  
2. [Align-and-Attend Network for Globally and Locally Coherent Video Inpainting.](https://arxiv.org/pdf/1905.13066.pdf) Woo, S., Kim, D., Park, K., Lee, J. Y., & Kweon, I. S. `In Arxiv 2019`  
3. [Onion-Peel Networks for Deep Video Completion](https://arxiv.org/pdf/1908.08718.pdf) Seoung Wug Oh, Sungho Lee, Joon-Young Lee, Seon Joo Kim. `In ICCV 2019` [[code]](https://github.com/seoungwugoh/opn-demo)  
4. [Copy-and-Paste Networks for Deep Video Inpainting](https://arxiv.org/pdf/1908.11587.pdf) Sunho Lee, Seoung Wug Oh, DaeYeun Won, Seon Joo Kim. `In ICCV 2019` [[code]](https://github.com/shleecs/Copy-and-Paste-Networks-for-Deep-Video-Inpainting)  
5. [Short-Term and Long-Term Context Aggregation Network for Video Inpainting](https://www.ecva.net/papers/eccv_2020/papers_ECCV/papers/123490698.pdf) Li et al. `In ECCV2020`  
6. [DVI: Depth Guided Video Inpainting for Autonomous Driving](https://arxiv.org/pdf/2007.08854.pdf) Liao et al. `In ECCV2020`   
7. [Learning Joint Spatial-Temporal Transformations for Video Inpainting](https://arxiv.org/pdf/2007.10247.pdf) Zeng et al. `In ECCV2020`   
8. 
