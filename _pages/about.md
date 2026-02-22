---
permalink: /
title: "Zhixin Cheng"
excerpt: "Ph.D. loading..."
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}


<p style="font-size: 18px; line-height: 1.7;">
  I am currently a fourth-year Ph.D. student (2022 – now) in the Department of Automation,
  University of Science and Technology of China (USTC), advised by
  <a href="http://staff.ustc.edu.cn/~tzzhang/" target="_blank" style="text-decoration: none; color: inherit;">
    Prof. Tianzhu Zhang
  </a>
  and 
  <a href="https://faculty.ustc.edu.cn/yinbaoqun/en/index.htm" target="_blank" style="text-decoration: none; color: inherit;">
    Prof. Baoqun Yin</a>.
  I spent my M.Eng. studies at the Advanced Technology Research Institute, USTC.
  Huazhong University of Science and Technology conferred upon me a B.Eng. degree in 2020 from the School of Electrical and Electronic Engineering.
  My research interests include
  computer vision, multimodal learning and 3D vision.
</p>


<h2 id="news" style="font-size: 32px; font-weight: 700;">🔥 News</h2>


<div style="font-size: 18px; line-height: 1.7;">
  <p><strong>2025.11:</strong> 🎉🎉 “Rethinking 2D-3D Registration: A Novel Network for High-Value Zone Selection and Representation Consistency Alignment” and “GeoGuide: Hierarchical Geometric Guidance for Open-Vocabulary 3D Semantic Segmentation” was accepted by CVPR 2026.</p>

  <p><strong>2025.11:</strong> 🎉🎉 “Adversarial Attacks Already Tell the Answer: Directional Bias-Guided Test-time Defense for Vision-Language Models” and “RayI2P: Learning Rays for Image-to-Point Cloud Registration” was accepted by ICLR 2026.</p>
  
  <p><strong>2025.11:</strong> 🎉🎉 “Adaptive Agent Selection and Interaction Network for Image-to-point cloud Registration” was accepted by AAAI 2026, and I attend the conference in Singapore🦁.</p>

  <p><strong>2025.10:</strong> 🎉🎉 “EF-3DGS: Event-Aided Free-Trajectory 3D Gaussian Splatting” (Spotlight) and “BeyondMix: Leveraging Structural Priors and Long-Range Dependencies for Domain-Invariant LiDAR Segmentation” were accepted by NeurIPS 2025.</p>

  <p><strong>2025.06:</strong> 🎉🎉 “CA-I2P: Channel-Adaptive Registration Network with Global Optimal Selection” was accepted by ICCV 2025, and I attended the conference in Hawaii🥥.</p>

  <p><strong>2025.02:</strong> 🎉🎉 “Implicit Correspondence Learning for Image-to-Point Cloud Registration” was accepted by CVPR 2025 as a Highlight.</p>

  <p><strong>2024.12:</strong> 🎉🎉 “Bridge 2D-3D: Uncertainty-aware Hierarchical Registration Network with Domain Alignment” and “DiffCorr: Conditional Diffusion Model with Reliable PseudoLabel Guidance for Unsupervised Point Cloud Shape Correspondence” was accepted by AAAI 2025.</p>

  <p><strong>2024.03:</strong> 🏀🏀 Won the championship in the USTC “复兴杯” Basketball Tournament 2024.</p>

  <p><strong>2023.06:</strong> 🎤🎤 Participated in the graduation gala.</p>
</div>

<div style="display: flex; gap: 12px; margin-top: 10px;">

  <img src="images/iccv1.jpg" alt="ICCV 2025 in Hawaii 1"
       style="flex: 1; width: 0; border-radius: 12px; object-fit: cover; aspect-ratio: 4 / 3;">

  <img src="images/b.jpg" 
       style="flex: 1; width: 0; border-radius: 12px; object-fit: cover; aspect-ratio: 4 / 3;">
       
  <img src="images/c.jpg" 
       style="flex: 1; width: 0; border-radius: 12px; object-fit: cover; aspect-ratio: 4 / 3;">

</div>

<div style="display: flex; gap: 12px; margin-top: 10px;">
  <img src="images/basketball.png" alt="basketball"
       style="flex: 1; width: 0; border-radius: 12px; object-fit: cover; aspect-ratio: 4 / 3;">

  <!-- 第三个图：点击打开 B 站视频 -->
  <a href="https://www.bilibili.com/video/BV1CV411T7Hz/?spm_id_from=333.1387.upload.video_card.click&vd_source=5ea11a9f3fc3d418bc770d294e810466"
     target="_blank"
     style="flex: 1; display: block; width: 0; border-radius: 12px; overflow: hidden; aspect-ratio: 4/3;">
    <img src="images/sing.png" alt="点击打开 B 站视频"
         style="width: 100%; height: 100%; object-fit: cover;">
  </a>


  <img src="images/a.png" style="flex: 1; width: 0; border-radius: 12px; object-fit: cover; aspect-ratio: 4 / 3;">

</div>

<h2 id="publications" style="font-size: 32px;">📝 Publications</h2>

<table>
<tr>
<td width="35%">
<img src="/images/fig2.png" width="100%">
</td>
<td width="65%">

<h3>
  <a target="_blank" style="text-decoration: none; color: #1a73e8; font-size: 28px; font-weight: 600;">
    Rethinking 2D-3D Registration: A Novel Network for High-Value Zone Selection and Representation Consistency Alignment
  </a>
</h3>
<p><span style="color:#00B0F0;">Zhixin Cheng</span>, Bohao Liao, Jiacheng Deng, Xiaotian Yin, Xinjun Li, Yujia Chen, Baoqun Yin, Tianzhu Zhang*</p>
<p>
  This paper rethinks image-to-point cloud registration by addressing two key challenges: many correspondences arise from non-overlapping or low-quality regions, and the same scene areas appear differently across modalities since images capture texture while point clouds represent geometry. The method therefore emphasizes selecting informative, matchable regions first, and then enforcing more consistent cross-modal region representations, reducing ambiguity and mismatches. 
</p>

<h3>
  <span style="font-size: 16px; color: #FFA3B0;">Presented at Computer Vision and Pattern Recognition 2026🌸</span>
</h3>

</td>
</tr>
</table>

---

<table>
<tr>
<td width="35%">
<img src="/images/AAAI26.png" width="100%">
</td>
<td width="65%">

<h3>
  <a href="https://arxiv.org/pdf/2511.05965" target="_blank" style="text-decoration: none; color: #1a73e8; font-size: 28px; font-weight: 600;">
    Adaptive Agent Selection and Interaction Network for Image-to-Point Cloud Registration
  </a>
</h3>
<p><span style="color:#00B0F0;">Zhixin Cheng</span>, Xiaotian Yin, Jiacheng Deng, Bohao Liao, Yujia Chen, Xu Zhou, Wenfei Yang*, Baoqun Yin</p>
<p>
  This paper targets the challenges of image-to-point-cloud registration under noise, where false correspondences are common and cross-modal information is difficult to filter effectively. It proposes a framework composed of Iterative Agent Selection and Reliable Agent Interaction: phase maps enhance structural perception, and reinforcement learning selects more reliable agents to guide cross-modal interaction, thereby reducing mismatches and improving robustness.
</p>

<h3>
  <span style="font-size: 16px; color: #FFA3B0;">Presented at Association for the Advancement of Artificial Intelligence 2026🌸</span>
</h3>

</td>
</tr>
</table>

---

<table>
   <tr>
<td width="35%">
  <div style="display: flex; flex-direction: column; gap: 10px; align-items: center;">
    <img src="/images/ICCV25_poster_CAI2P.png" style="width: 95%; display: block; margin: 0 auto;">
    <img src="/images/iccv.png" style="width: 95%; display: block; margin: 0 auto;">
  </div>
</td>
    <td width="65%">



<h3>
  <a href="https://openaccess.thecvf.com/content/ICCV2025/html/Cheng_CA-I2P_Channel-Adaptive_Registration_Network_with_Global_Optimal_Selection_ICCV_2025_paper.html"
     target="_blank"
     style="text-decoration: none; color: #1a73e8; font-size: 28px; font-weight: 600;">
    CA-I2P: Channel-Adaptive Registration Network with Global Optimal Selection
  </a>
</h3>



<p><span style="color:#00B0F0;">Zhixin Cheng</span>, Jiacheng Deng, Xinjun Li, Xiaotian Yin, Bohao Liao, Baoqun Yin, Wenfei Yang*, Tianzhu Zhang</p>

<p>
  This paper addresses detection-free image-to-point cloud registration, where cross-modal channel mismatches and redundant top-k correspondences reduce matching quality. CA-I2P uses a Channel Adaptive Adjustment module to align channels across modalities and a Global Optimal Selection module to produce globally consistent matches for robust registration. We attend the conference and discussed our ideas with Google AI scientist Martin Sundermeyer.
</p>

<h3>
  <span style="font-size: 16px; color: #FFA3B0;">Presented at International Conference on Computer Vision 2025🌸</span>
</h3>

</td>
</tr>
</table>

---

<table>
<tr>
<td width="35%">
<img src="/images/aaai25_poster_B2-3Dnet.png" width="100%">
</td>
<td width="65%">
  

<h3>
  <a href="https://ojs.aaai.org/index.php/AAAI/article/view/32251"
   target="_blank"
   style="text-decoration: none; color: #1a73e8; font-size: 28px; font-weight: 600;">
  Bridge 2D-3D: Uncertainty-aware Hierarchical Registration Network with Domain Alignment
  </a>
</h3>


<p><span style="color:#00B0F0;">Zhixin Cheng</span>, Jiacheng Deng, Xinjun Li, Baoqun Yin, Tianzhu Zhang*</p>

<p>
  This paper proposes B2-3Dnet for detection-free image-to-point cloud registration, aiming to reduce distraction from noisy image patches and narrow the cross-modal domain gap. It introduces an uncertainty-aware hierarchical matching module that estimates patch reliability and performs multi-scale coarse-to-fine interactions, and an adversarial modal alignment module that aligns image and point-cloud features using a gradient reversal strategy and a domain classifier.
</p>

<h3>
  <span style="font-size: 16px; color: #FFA3B0;">Presented at Association for the Advancement of Artificial Intelligence 2025🌸</span>
</h3>

</td>
</tr>
</table>

---
<h3>
  <a target="_blank" style="text-decoration: none; color: inherit;">
    GeoGuide: Hierarchical Geometric Guidance for Open-Vocabulary 3D Semantic Segmentation
  </a>
</h3>
<p>Xujing Tao, Chuxin Wang, Yubo Ai, <span style="color:#00B0F0;">Zhixin Cheng</span>, Zhuoyuan Li, Liangsheng Liu, Yujia Chen, Xinjun Li, Qiao Li, Wenfei Yang*, Tianzhu Zhang </p>

<h3>
  <a target="_blank" style="text-decoration: none; color: inherit;">
    RayI2P: Learning Rays for Image-to-Point Cloud Registration
  </a>
</h3>
<p>Xinjun Li, Wenfei Yang*, <span style="color:#00B0F0;">Zhixin Cheng</span>, Jiacheng Deng, Fei Wang, Chen Qian, Tianzhu Zhang</p>

<h3>
  <a target="_blank" style="text-decoration: none; color: inherit;">
    Adversarial Attacks Already Tell the Answer: Directional Bias-Guided Test-time Defense for Vision-Language Models
  </a>
</h3>
<p>Liangsheng Liu, Si Chen, Jiamin Wu, Weiwei Feng, <span style="color:#00B0F0;">Zhixin Cheng</span>, Xiaotian Yin, Wenfei Yang*, Tianzhu Zhang</p>

<h3>
  <a href="https://arxiv.org/pdf/2410.15392" target="_blank" style="text-decoration: none; color: inherit;">
    EF-3DGS: Event-Aided Free-Trajectory 3D Gaussian Splatting (Spotlight)
  </a>
</h3>
<p>Bohao Liao, Wei Zhai*, Zengyu Wan, <span style="color:#00B0F0;">Zhixin Cheng</span>, Wenfei Yang, Yang Cao, Tianzhu Zhang, Zhengjun Zha</p>

<h3>
  <a href="https://neurips.cc/virtual/2025/loc/san-diego/poster/115060" target="_blank" style="text-decoration: none; color: inherit;">
    BeyondMix: Leveraging Structural Priors and Long-Range Dependencies for Domain-Invariant LiDAR Segmentation
  </a>
</h3>
<p>Yujia Chen, Rui Sun, Wangkai Li, Huayu Mai, Si Chen, Zhuoyuan Li, <span style="color:#00B0F0;">Zhixin Cheng</span>, Tianzhu Zhang*</p>

<h3>
  <a href="https://cvpr.thecvf.com/virtual/2025/poster/32978" target="_blank" style="text-decoration: none; color: inherit;">
    Implicit Correspondence Learning for Image-to-Point Cloud Registration (Highlight)
  </a>
</h3>
<p>Xinjun Li, Wenfei Yang*, Jiacheng Deng, <span style="color:#00B0F0;">Zhixin Cheng</span>, Xu Zhou, Tianzhu Zhang</p>

<h3>
  <a href="https://ojs.aaai.org/index.php/AAAI/article/view/32273" target="_blank" style="text-decoration: none; color: inherit;">
    DiffCorr: Conditional Diffusion Model with Reliable PseudoLabel Guidance for Unsupervised Point Cloud Shape Correspondence
  </a>
</h3>
<p>Jiacheng Deng, Jiahao Lu, <span style="color:#00B0F0;">Zhixin Cheng</span>, Wenfei Yang*</p>


<h2 id="honors-and-awards" class="section-title">🏅 Honors and Awards</h2>


First‑Class Scholarship, USTC Graduate School

Deep Space Exploration Scholarship

Excellent Minister, Graduate Student Union, Advanced Technology Research Institute, USTC

USTC “复兴杯” Basketball Champion (2024) and Runner‑up (2023)

Outstanding Graduate, Huazhong University of Science and Technology

Level 10 Certification in Erhu Performance🎶


<h2 id="education" class="section-title">📖 Education</h2>


2022.09 – present: Ph.D. in Automation, USTC, Hefei, China

2020.09 – 2022.08: M.Eng., Advanced Technology Research Institute, USTC, Hefei, China

2016.09 – 2020.06: B.Eng., School of Electrical and Electronic Engineering, Huazhong University of Science and Technology, Wuhan, China

2013.09 – 2016.06: Senior High School, Hefei No.8 High School, Hefei, China

2010.09 – 2013.06: Junior High School, Hefei No.50 Middle School, Hefei, China


<h2 id="internships" class="section-title">💻 Internships</h2>

2025.06 – 2025.10: Research Intern, COG1, Spark Large Model Research Institute, iFLYTEK, Hefei, China

2021.09 – 2022.08: Research Intern, Brain‑Inspired Intelligence Platform, Hefei Comprehensive National Science Center, Hefei, China

2020.09 – 2021.03: AI Algorithm Intern, Jiyuan–Huawei Ascend Joint Laboratory,
NARI Jiyuan Electric Grid Technology Co., Ltd., Hefei, China


2018.07 – 2018.09: Visiting Student, The University of Manchester, Manchester, UK🎡

<h2 id="skills" class="section-title">🛠 Skills</h2>


Programming: Python, PyTorch, CUDA

Research: Deep learning, Multimodal fusion, 3D vision task

Service: Reviewer for ICML, CVPR, ICCV, AAAI, NIPS, ICLR, ACM MM, TCSVT, TMM

Language: CET‑6, good English writing and communication


<h2 id="contact" class="section-title">📬 Contact</h2>


Email: chengzhixin@mail.ustc.edu.cn

