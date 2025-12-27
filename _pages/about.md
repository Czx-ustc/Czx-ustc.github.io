---
permalink: /
title: "Zhixin Cheng"
excerpt: "Ph.D. student at USTC"
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


I am currently a third‑year Ph.D. student (2022 – now) in the Department of Automation, University of Science and Technology of China (USTC), advised by Prof. Tianzhu Zhang and Prof. Baoqun Yin. I spent my M.Eng. studies at the Advanced Technology Research Institute, University of Science and Technology of China (USTC), and received my B.Eng. degree from Huazhong University of Science and Technology in 2020. My research interests include computer vision, multimodal learning, and image-to–point cloud registration.

🔥 News

2025.11:  🎉🎉 “Adaptive Agent Selection and Interaction Network for Image-to-point cloud Registration” was accepted by AAAI 2026.

2025.09:  🎉🎉 “CA-I2P: Channel-Adaptive Registration Network with Global Optimal Selection” was accepted by ICCV 2025.

2025.07:  🎉🎉 “EF-3DGS: Event-Aided Free-Trajectory 3D Gaussian Splatting” and "BeyondMix: Leveraging Structural Priors and Long-Range Dependencies for Domain-Invariant LiDAR Segmentation" was accepted by NIPS 2025.

2025.02:  🎉🎉 “Implicit Correspondence Learning for Image‑to‑Point Cloud Registration” was accepted by CVPR 2025 as a Highlight!

2024.12:  🎉🎉 “Bridge 2D-3D: Uncertainty-aware Hierarchical Registration Network with Domain Alignment” and "DiffCorr: Conditional Diffusion Model with Reliable PseudoLabel Guidance for Unsupervised Point Cloud Shape Correspondence" was accepted by AAAI 2025.

2024.03:  🏀 Won the championship in the USTC “复兴杯” Basketball Tournament 2024.

📝 Publications

<table>
<tr>
<td width="35%">
<img src="/images/AAAI26-Poster-CZX.png" width="100%">
</td>
<td width="65%">

**Adaptive Agent Selection and Interaction Network for Image-to-Point Cloud Registration**  
Zhixin Cheng, Xiaotian Yin, Jiacheng Deng, Yujia Chen, Bohao Liao, Wenfei Yang, Baoqun Yin  

This paper targets the challenges of image-to-point-cloud registration under noise, where false correspondences are common and cross-modal information is difficult to filter effectively. It proposes a framework composed of Iterative Agent Selection (IAS) and Reliable Agent Interaction (RAI): phase maps enhance structural perception, and reinforcement learning selects more reliable “agents” to guide cross-modal interaction, thereby reducing mismatches and improving robustness.


</td>
</tr>
</table>

---

<table>
<tr>
<td width="35%">
<img src="/images/ICCV25_poster_CAI2P.png" width="100%">
</td>
<td width="65%">

**CA-I2P: Channel-Adaptive Registration Network with Global Optimal Selection**  
Zhixin Cheng, Jiacheng Deng, Xinjun Li, Xiaotian Yin, Bohao Liao, Baoqun Yin, Wenfei Yang, Tianzhu Zhang  

This paper addresses detection-free image-to-point cloud registration, where cross-modal channel mismatches and redundant top-k correspondences reduce matching quality. CA-I2P use a Channel Adaptive Adjustment module to align channels across modalities and a Global Optimal Selection module to produce globally consistent matches for robust registration.


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

**Bridge 2D-3D: Uncertainty-aware Hierarchical Registration Network with Domain Alignment**  
Zhixin Cheng, Jiacheng Deng, Xinjun Li, Baoqun Yin, Tianzhu Zhang  

This paper proposes B2-3Dnet for detection-free image-to-point cloud registration, aiming to reduce distraction from noisy image patches and narrow the cross-modal domain gap. It introduces an uncertainty-aware hierarchical matching module that estimates patch reliability and performs multi-scale coarse-to-fine interactions, and an adversarial modal alignment module that aligns image and point-cloud features using a gradient reversal strategy and a domain classifier.

</td>
</tr>
</table>

---


EF-3DGS: Event-Aided Free-Trajectory 3D Gaussian Splatting || Bohao Liao, Wei Zhai, Zengyu Wan, Zhixin Cheng, Wenfei Yang, Yang Cao, Tianzhu Zhang, ZhengJun Zha

BeyondMix:Leveraging Structural Priors and Long-Range Dependencies for Domain-Invariant LiDAR Segmentation || Yujia Chen, Rui Sun, Wangkai Li, Huayu Mai, Si Chen, Zhuoyuan Li, Zhixin Cheng, Tianzhu Zhang

Implicit Correspondence Learning for Image‑to‑Point Cloud Registration || Xinjun Li, Wenfei Yang, Jiacheng Deng, Zhixin Cheng, Xu Zhou, Tianzhu Zhang

DiffCorr: Conditional Diffusion Model with Reliable PseudoLabel Guidance for Unsupervised Point Cloud Shape Correspondence || Jiacheng Deng, Jiahao Lu, Zhixin Cheng, Wenfei Yang

🎖 Honors and Awards

First‑Class Scholarship, USTC Graduate School

Excellent Minister, Graduate Student Union, Advanced Technology Research Institute, USTC

USTC “复兴杯” Basketball Champion (2024) and Runner‑up (2023)

Outstanding Graduate, Huazhong University of Science and Technology

Level 10 Certification in Erhu Performance

📖 Education

2022.09 – present: Ph.D. in Automation, USTC, Hefei, China

2020.09 – 2022.08: M.Eng., Advanced Technology Research Institute, USTC, Hefei, China

2016.09 – 2020.06: B.Eng., School of Electrical and Electronic Engineering, Huazhong University of Science and Technology, Wuhan, China

💻 Internships

2021.09 – 2022.08: Research Intern, Brain‑Inspired Intelligence Platform, Hefei Comprehensive National Science Center, Hefei, China

2020.09 – 2021.03: AI Algorithm Intern, Nari‑Jiyuan Electric Grid Technology Co., Ltd., Hefei, China

🛠 Skills

Programming: Python, PyTorch, CUDA

Research: Deep learning, Multimodal fusion, 2D‑3D registration

Service: Reviewer for ICML, CVPR, ICCV, AAAI, ACM MM, TCSVT

Language: CET‑6, good English writing and communication

📬 Contact

Email: chengzhixin@mail.ustc.edu.cn

Phone: +86 189 5606 3563

