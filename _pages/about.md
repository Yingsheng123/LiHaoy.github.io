---
permalink: /
title: ""
excerpt: ""
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

<span class='anchor' id='about-me'></span>

# 🧑🏻‍🎓 Biography
I received a B.S. degree in Automation from [Beijing Information Science and Technology University](https://www.bistu.edu.cn/), China, in 2023. I am currently working toward an M.S. degree in Control Engineering at the School of Astronautics, [Harbin Institute of Technology](https://www.hit.edu.cn/), Harbin , China.


I'm interested in Robotics, SLAM, 3dgs, 3D Vision, VLM and Embodied AI. Most of my research is about enabling mobile robots sensing intelligently.

 [//]: # (I was the recipient of the National Scholarship for Postgraduate at Northwestern Polytechnical University in 2024 and hold 5 Chinese invention patents.)
 
 [//]: # (My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).)


# 🔥 News
- *2025.03*: &nbsp;🎉🎉 The paper *DQO-MAP: Dual Quadrics Multi-Object mapping with Gaussian Splatting* has been submitted to the IROS 2025.
- *2024.12*: &nbsp;🎉🎉 The paper *MLINE-VINS: Robust Monocular Visual-Inertial SLAM With Flow Manhattan and Line Features* has been submitted to the IEEE Transactions on Instrumentation and Measurement.
- *2024.09*:  &nbsp;✏️ I have taken on the role of student editor for the journal IEEE Transactions on Industrial Informatics.
- *2024.09*:&nbsp;🎉🎉 I won the first class scholarship of the HIT.
- *2023.06*: &nbsp; 🎓 Graduated from Beijing Information Science and Technology University .

# 📝 Publications 
\* indicates equal contribution
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2025</div><img src='images/DQO-MAP/example.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DQO-MAP: Dual Quadrics Multi-Object mapping with Gaussian Splatting](https://arxiv.org/pdf/2503.02223)
[Video](https://www.bilibili.com/video/BV1qoVrzaEbJ/?spm_id_from=333.1387.homepage.video_card.click)

**Haoyuan Li**, Ziqin Ye, Yue Hao, Weiyang Lin, Chao Ye

Submitted to IROS 2025

 <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Accurate object perception is essential for robotic applications such as object navigation. In this paper, we propose DQO-MAP, a novel object-SLAM system that seamlessly integrates object pose estimation and reconstruction. We employ 3D Gaussian Splatting for high-fidelity object reconstruction and leverage quadrics for precise object pose estimation. Both of them management is handled on the CPU, while optimization is performed on the GPU, significantly improving system efficiency. By associating objects with unique IDs, our system enables rapid object extraction from the scene. 
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE Trans/Journal</div><img src='images/MLINE-VINS/traj.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MLINE-VINS: Robust Monocular Visual-Inertial SLAM With Flow Manhattan and Line Features]
[Video](https://www.bilibili.com/video/BV1joVrzYEQN/?spm_id_from=333.1387.homepage.video_card.click&vd_source=a3b6b3c9fa798376b8455ccc7b7946f8)(https://arxiv.org/pdf/2503.01571)

Chao Ye\*, **Haoyuan Li**\*, Weiyang Lin,  Xianqiang Yang

Submitted to IEEE Transactions on Instrumentation and Measurement

 <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- In this paper we introduce MLINE-VINS, a novel monocular visual-inertial odometry (VIO) system that leverages line features and Manhattan Word assumption. Specifically, for line matching process, we propose a novel geometric line optical flow algorithm that efficiently tracks line features with varying lengths, whitch is do not require detections and descriptors in every frame. To address the instability of Manhattan estimation from line features, we propose a tracking-by-detection module that consistently tracks and optimizes Manhattan framse in consecutive images. By aligning the Manhattan World with the VIO world frame, the tracking could restart using the latest pose from back-end, simplifying the coordinate transformations within the system. Furthermore, we implement a mechanism to validate Manhattan frames and a novel global structural constraints back-end optimization
</div>
</div>



<div class='paper-box'><div class='paper-box-image'><div><div class="badge">MCTE 2022</div><img src='images/design.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Design of motion pattern recognition system based on MPU6050 and pressure 
sensor](https://www.spiedigitallibrary.org/conference-proceedings-of-spie/12500/125001M/Design-of-motion-pattern-recognition-system-based-on-MPU6050-and/10.1117/12.2662807.short)

**Haoyuan Li**\*, Xufeng Hu,  Jingxu Huang, Yang Wang

 <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Aimed at the defects of low accuracy of motion pattern recognition and large volume of measuring equipment, a motion pattern recognition system based on MPU6050 and pressure sensor is designed, and the overall structure of the system is given.  
</div>
</div>


[//]: # (- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020**)
# 💻 Project
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2021-2022</div><img src='images/fig1-1.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Consensus control of unknown nonlinear discrete-time multi-agent systems with nonuniform time-delays. 

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- This project investigates the data-driven consensus control for a class of unknown heterogeneous nonlinear multi-agent systems with non-uniform communication delay by using model free adaptive control (MFAC) method. The designed controller is distributed and data-driven with only using the agent itself and its neighbors data information without any model information.
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2020-2021</div><img src='images/ROV.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">
Remotely operated underwater vehicle（ROV) production. 
<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Based on STM32, MAX1482, DMA to achieve full duplex communication between upper and lower computers; Design the hardware circuit of the machine (DC-DC circuit; Communication circuit; Control circuit) and draw four layers of PCB board;
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">2019-2020</div><img src='images/software.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Chinese short message compression project. 

<strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Using Chinese word segmentation and adaptive Huffman coding to compress Chinese short messages
</div>
</div>


# 🎖 Honors and Awards
- *2024.09* The First Class Scholarship of the HIT
- *2022.09* The Excellent good student of the BISTU(top 3%)
- *2022.09* Science and technology innovation scholarship of the 
BISTU
- *2022.09* Excellent scholarship of the BISTU
- *2022.05* The First prize of the CSPC
- *2022.05* The First prize of “Blue Bridge Cup”
- *2021.11* The National Second prize of the CUMCM
- *2021.09* The Excellent good student of the BISTU(top 3%)
- *2021.09* Science and technology innovation scholarship of the 
BISTU
- *2021.09* Excellent scholarship of the BISTU
- *2021.04* The Third prize in RoboCup
- *2021.04* The National Third prize of the NECCS
- *2020.12* The Second prize of Beijing Mathematical Competition


# 📖 Educations
- *2023.06 - 2026.06 (now)*, Harbin Institute of Technology, Control Engineering.
- *2019.09 - 2023.06*, B.S. Beijing Information Science and Technology University,  Automation.
