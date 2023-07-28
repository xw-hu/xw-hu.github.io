---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}


### 2023
<ul>
     <li> <p style="margin-left: 0px; line-height: 150%; margin-top: 10px; margin-bottom: 10px;"><font face="Arial" size="3"><meta charset="utf-8">
            Instance Shadow Detection with A Single-Stage Detector <br> 
         <i> Tianyu Wang, <b>Xiaowei Hu</b>*, Pheng-Ann Heng, and Chi-Wing Fu. </i><br> 
	       IEEE Transactions on Pattern Analysis and Machine Intelligence (<b>IEEE TPAMI</b>), vol. 45, no. 3, pp. 3259-3273, 2023. <br>
	       [<a href="https://ieeexplore.ieee.org/document/9804810">paper</a>]
	       [<a href="https://arxiv.org/abs/2207.04614">arXiv</a>]
	       [<a href="https://github.com/stevewongv/SSIS">code</a>] 
	       [<a href="https://drive.google.com/drive/folders/1MKxyq3R6AUeyLai9i9XWzG2C_n5f0ppP">SOBA dataset</a>]
          </font>
	 </p> </li>
</ul>		
<ul>   
    <li> <p style="margin-left: 0px; line-height: 150%; margin-top: 10px; margin-bottom: 10px;"><font face="Arial" size="3"><meta charset="utf-8">
            SILT: Shadow-Aware Iterative Label Tuning for Learning to Detect Shadows from Noisy Labels <br> 
         <i>   Han Yang^, Tianyu Wang^, <b>Xiaowei Hu*</b>, and Chi-Wing Fu. (^ joint first authors) </i><br> 
	       IEEE International Conference on Computer Vision (<b>ICCV</b>), 2023. <br>
	  </font>
	 </p> </li>	
</ul>		
<ul> 
     <li> <p style="margin-left: 0px; line-height: 150%; margin-top: 10px; margin-bottom: 10px;"><font face="Arial" size="3"><meta charset="utf-8">
            Learning Weather-General and Weather-Specific Features for Image Restoration Under Multiple Adverse Weather Conditions <br> 
         <i>   Yurui Zhu, Tianyu Wang, Xueyang Fu*, Xuanyu Yang, Xin Guo, Jifeng Dai, Yu Qiao, and <b>Xiaowei Hu</b>* </i><br> 
	       IEEE Conference on Computer Vision and Pattern Recognition (<b>CVPR</b>), pp. 21747-21758, 2023. <br>
	       [<a href="https://openaccess.thecvf.com/content/CVPR2023/html/Zhu_Learning_Weather-General_and_Weather-Specific_Features_for_Image_Restoration_Under_Multiple_CVPR_2023_paper.html">paper</a>]
	       [<a href="https://github.com/zhuyr97/WGWS-Net">code</a>]
	     </font>
	 </p> </li>
</ul>		
<ul> 	
     <li> <p style="margin-left: 0px; line-height: 150%; margin-top: 10px; margin-bottom: 10px;"><font face="Arial" size="3"><meta charset="utf-8">
            Video Dehazing via a Multi-Range Temporal Alignment Network with Physical Prior <br> 
         <i>   Jiaqi Xu, <b>Xiaowei Hu</b>*, Lei Zhu*, Qi Dou, Jifeng Dai, Yu Qiao, and Pheng-Ann Heng </i><br> 
	       IEEE Conference on Computer Vision and Pattern Recognition (<b>CVPR</b>), pp. 18053-18062, 2023. <br>
	       [<a href="https://openaccess.thecvf.com/content/CVPR2023/html/Xu_Video_Dehazing_via_a_Multi-Range_Temporal_Alignment_Network_With_Physical_CVPR_2023_paper.html">paper</a>] 
	       [<a href="https://arxiv.org/abs/2303.09757">arXiv</a>] 
	       [<a href="https://github.com/jiaqixuac/MAP-Net">code</a>]
	       [<a href="https://github.com/jiaqixuac/MAP-Net/blob/main/docs/dataset_prepare.md">HazeWorld dataset</a>]
	  </font>
	 </p> </li>
</ul>		
<ul> 	
     <li> <p style="margin-left: 0px; line-height: 150%; margin-top: 10px; margin-bottom: 10px;"><font face="Arial" size="3"><meta charset="utf-8">
               Matching Is Not Enough: A Two-Stage Framework for Category-Agnostic Pose Estimation <br> 
         <i>   Min Shi, Zihao Huang, Xianzheng Ma, <b>Xiaowei Hu</b>, and Zhiguo Cao </i><br> 
	       IEEE Conference on Computer Vision and Pattern Recognition (<b>CVPR</b>), pp. 7308-7317, 2023. (<span style="color:rgb(224, 145, 92)"><b>Highlight</b></span>)  <br>
	       [<a href="https://openaccess.thecvf.com/content/CVPR2023/html/Shi_Matching_Is_Not_Enough_A_Two-Stage_Framework_for_Category-Agnostic_Pose_CVPR_2023_paper.html">paper</a>]
	       [<a href="https://github.com/flyinglynx/CapeFormer">code</a>]
	     </font>
	 </p> </li>
</ul>		
<ul> 	
     <li> <p style="margin-left: 0px; line-height: 150%; margin-top: 10px; margin-bottom: 10px;"><font face="Arial" size="3"><meta charset="utf-8">
               InternImage: Exploring Large-Scale Vision Foundation Models with Deformable Convolutions <br> 
         <i>   Wenhai Wang, Jifeng Dai, Zhe Chen, Zhenhang Huang, Zhiqi Li, Xizhou Zhu, <b>Xiaowei Hu</b>, Tong Lu, Lewei Lu, Hongsheng Li, Xiaogang Wang, and Yu Qiao </i><br> 
	       IEEE Conference on Computer Vision and Pattern Recognition (<b>CVPR</b>), pp. 14408-14419, 2023. (<span style="color:rgb(224, 145, 92)"><b>Highlight</b></span>) <br>
	       [<a href="https://openaccess.thecvf.com/content/CVPR2023/html/Wang_InternImage_Exploring_Large-Scale_Vision_Foundation_Models_With_Deformable_Convolutions_CVPR_2023_paper.html">paper</a>] 
	       [<a href="https://arxiv.org/abs/2211.05778">arXiv</a>] 
	       [<a href="https://github.com/OpenGVLab/InternImage">code</a>]
	  </font>
	 </p> </li>
</ul>		
<ul> 
     <li> <p style="margin-left: 0px; line-height: 150%; margin-top: 10px; margin-bottom: 10px;"><font face="Arial" size="3"><meta charset="utf-8">
            Deep Texture-Aware Features for Camouflaged Object Detection <br> 
         <i>   Jingjing Ren^, <b>Xiaowei Hu</b>^, Lei Zhu, Xuemiao Xu, Yangyang Xu, Weiming Wang, Zijun Deng, and Pheng-Ann Heng. (^ joint first authors)  </i><br> 
	        IEEE Transactions on Circuits and Systems for Video Technology (<b>IEEE TCSVT</b>), vol. 33, no. 3, pp. 1157-1167, 2023. <br>
	        [<a href="https://ieeexplore.ieee.org/document/9606888">paper</a>]
	  </font>
	 </p> </li>  
</ul>		
<ul>    
      <li> <p style="margin-left: 0px; line-height: 150%; margin-top: 10px; margin-bottom: 10px;"><font face="Arial" size="3"><meta charset="utf-8">
            Representative Feature Alignment for Adaptive Object Detection <br> 
         <i>   Shan Xu, Huaidong Zhang, Xuemiao Xu*, <b>Xiaowei Hu</b>*, Yangyang Xu, Liangui Dai, Kup-Sze Choi, and Pheng-Ann Heng. </i><br> 
	        IEEE Transactions on Circuits and Systems for Video Technology (<b>IEEE TCSVT</b>), vol. 33, no. 2, pp. 689-700, 2023. <br>
	     [<a href="https://ieeexplore.ieee.org/document/9868052">paper</a>]
	  </font>
	 </p> </li>    
</ul>		
<ul> 	
    <li> <p style="margin-left: 0px; line-height: 150%; margin-top: 10px; margin-bottom: 10px;"><font face="Arial" size="3"><meta charset="utf-8">
            Dynamic Message Propagation Network for RGB-D and Video Salient Object Detection <br> 
         <i>   Baian Chen, Zhilei Chen, <b>Xiaowei Hu</b>, Jun Xu, Haoran Xie, Jing Qin, and Mingqiang, Wei.  </i><br> 
	        ACM Transactions on Multimedia Computing Communications and Applications (<b>ACM TOMM</b>), accepted, 2023. <br>
	  </font>
	 </p> </li>  
</ul>		
