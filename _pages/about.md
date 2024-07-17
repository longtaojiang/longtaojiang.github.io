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

I am now a master student in the National Key Microsoft Key Laboratory of Multimedia Computing and Communication of [University of Science and Technology of China](https://www.ustc.edu.cn/), mainly engaged in the research of multimedia retrieval, image generation, multimodal large language models.

I graduated from School of [College of Information Science and Engineering](https://ise.hhu.edu.cn/), [Hohai University](http://www.hhu.edu.cn/) (河海大学信息科学与工程学院) with a bachelor’s degree. Now, I'm pursuing my master’s degree in the [School of Information Science and Technology](https://sist.ustc.edu.cn/), [University of Science and Technology of China](https://www.ustc.edu.cn/) (中国科学技术大学信息科学技术学院), advised by [Wengang Zhou](http://staff.ustc.edu.cn/~zhwg/) (周文罡) and [Houqiang Li](http://staff.ustc.edu.cn/~lihq/) (李厚强).

My research interests include computer vision, multimodal retrieval, image generation and editing, and multimodal prediction models.

# 📖 Educations
- *2023.09 - 2024.07 (now)*, [University of Science and Technology of China](https://www.ustc.edu.cn/), Heifei, (GPA: 3.92/4.0, rank: 5/112).
- *2019.09 - 2023.06*, [Hohai University](http://www.hhu.edu.cn/), Nanjing, (GPA: 4.96/5.0, rank: 1/125).

# 💻 Internships
<div class='paper-box'>
<div class='paper-box-image'>
<img src='images/alibaba.png' alt="sym" width="100%">
</div>
<div class='paper-box-text' markdown="1">
- *2023.01 - 2023.06*, [Alibaba, Quark Search Department](https://ali-home.alibaba.com/about-alibaba-businesses-1496656660737818624), Hangzhou.


# 📝 Publications 

## 📃 Papers

<!-- Paper -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/publications/acmmm24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**SEDS: Semantically Enhanced Dual-Stream Encoder for Sign Language Retrieval**](https://arxiv.org/abs/2303.12793)

**Longtao Jiang**, Min Wang, Zecheng Li, Yao Fang, Wengang Zhou, Houqiang Li

[**abstract**](https://arxiv.org/abs/2303.12793)
  Sign language retrieval, as an emerging visual-language task, has received widespread attention. Different from traditional video retrieval, it is more biased towards understanding the semantic information of human actions contained in video clips. Previous works typically only encode RGB videos to obtain high-level semantic features, resulting in local action details drowned in a large amount of visual information redundancy. Furthermore, existing RGB-based sign retrieval works suffer from the huge memory cost of dense visual data embedding in end-to-end training, and adopt offline RGB encoder instead, leading to suboptimal feature representation. To address these issues, we propose a novel sign language representation framework called Semantically Enhanced Dual-Stream Encoder (SEDS), which integrates Pose and RGB modalities to represent the local and global information of sign language videos. Specifically, the Pose encoder embeds the coordinates of keypoints corresponding to human joints, effectively capturing detailed action features. For better context-aware fusion of two video modalities, we propose a Cross Gloss Attention Fusion (CGAF) module to aggregate the adjacent clip features with similar semantic information from intra-modality and inter-modality. Moreover, a Pose-RGB Fine-grained Matching Objective is developed to enhance the aggregated fusion feature by contextual matching of fine-grained dual-stream features. Besides the offline RGB encoder, the whole framework only contains learnable lightweight networks, which can be trained end-to-end. Extensive experiments demonstrate that our framework significantly outperforms state-of-the-art methods on How2Sign, PHOENIX-2014T, and CSL-Daily datasets.

</div>
</div>

<!-- Paper -->
<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Robotics and Autonomous Systems</div><img src='images/publications/202309_A_study_of_robotic_search_strategy_for_multi-radiation_sources_in_unknown_environments.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**A study of robotic search strategy for multi-radiation sources in unknown environments**](https://doi.org/10.1016/j.robot.2023.104529)

Hua Bai, Wenrui Gao, **Haofei Ma**, Pengchao Ding, Gongcheng Wang, Wenda Xu, Weidong Wang, Zhijiang Du

[**Paper**](https://doi.org/10.1016/j.robot.2023.104529)
- A robot search strategy is proposed and evaluated for unknown radiation environments.
- Combine ADE optimization with the PSPF algorithm to improve estimation efficiency.
- An exploration scheme is proposed to balance exploration and exploitation.

</div>
</div> -->

<!-- - <code class="language-plaintext highlighter-rouge">IEEE Sensors Journal</code> [**Kalman Filter-based EM-optical Sensor Fusion for Bone Needle Position Tracking**](https://doi.org/10.1109/JSEN.2024.3364701)<br>
Zhiyu Xia, Han Wang, Yulong Men, **Haofei Ma**, Zexin Cao, Weidong Wang, Zhijiang Du, "Kalman Filter-based EM-optical Sensor Fusion for Bone Needle Position Tracking." IEEE Sensors Journal, 2024. (SCI-Q2) -->

## 📚 Patents

- <code class="language-plaintext highlighter-rouge">Invention Patent</code> [**An Intelligent Vehicle System Based on Electromagnetic Positioning**](https://xueshu.baidu.com/usercenter/paper/show?paperid=1a4w0r20cd1p08708x0k0r00e5163321&site=xueshu_se), **Longtao Jiang**, Zhiheng Zeng, Yipei Liu (CN202111388699.X)

- <code class="language-plaintext highlighter-rouge">Invention Patent</code> [**A vehicle positioning system based on electromagnetic waves**](https://xueshu.baidu.com/usercenter/paper/show?paperid=1s3y0v80hm7w0jc06p3t0r00sc563453&site=xueshu_se), Yipei Liu, **Longtao Jiang**, Zhiheng Zeng (CN202210222945.2)

- <code class="language-plaintext highlighter-rouge">Invention Patent</code> [**A machine vision based autonomous tracking intelligent vehicle**](https://xueshu.baidu.com/usercenter/paper/show?paperid=174a0ej0uy7x0xf0820b0ms01b755398&site=xueshu_se), Zhiheng Zeng, Yipei Liu, **Longtao Jiang**, Zhaowen Chen (CN202111286807.2)

# 🔍 Projects

<!-- Project -->

## Rock Core Box Handling Robot

<div class='paper-box'>
<div class='paper-box-image'>
<div class="badge">2022.08 - 2023.02</div>
<img src='images/projects/202208_Rock_Core_Box_Handling_Robot.jpg' alt="sym" width="100%">
</div>
<div class='paper-box-text' markdown="1">

Rock Core samples obtained from drilling before oil extraction are crucial data for assessing mining value, and they are stored in dedicated core boxes. During research and analysis, it's essential to arrange these rock core boxes neatly on-site in a designated order, one box at a time. However, these boxes are typically heavy, resulting in a high labor intensity that can impact transportation efficiency. The present invention aims to address the labor intensity associated with the current method of transporting core boxes, ultimately improving transportation efficiency.

</div><div markdown="1">

**Finished Works**:
1. Build a sensing system that utilizes infrared sensors to detect surrounding obstacles, as well as fractional laser sensors to detect the current stacking height and alignment.

2. Implement rock core box instance segmentation based on Mask RCNN, combined with a depth camera to determine its corner space coordinates for visual servo during the robot handling process.

3. Utilize a monocular camera and Aruco markers to achieve 2D pose adjustment of the robot in place by identifying the offset distance and angle of the Aruco marker.

</div>
</div>

<!-- Project -->

## Medical Pan-Tilt Control System Based on Binocular Vision

<div class='paper-box'>
<div class='paper-box-image'>
<div class="badge">2022.01 - 2022.06</div>
<img src='images/projects/202201_Medical_Multi-DoF_Pan-Tilt_Control_System_Based_on_Binocular_Vision.jpg' alt="sym" width="100%">
</div>
<div class='paper-box-text' markdown="1">

In traditional medical processes, traditional Chinese medicine practitioners often need to frequently change positions and adjust their angles to view the surgical area. Additionally, during rehabilitation treatment, the camera's range can be inadequate to cover the patient's moving area. Current recording methods commonly used suffer from limitations and lack automation. This article introduces a multi-degree-of-freedom pan-tilt system designed to track the positions of doctors and patients.

[**Project**](https://github.com/HaofeiMa/Multi-DOF_PTZ), [**Video**](https://www.youtube.com/watch?v=gDLijtdpC2w)

</div><div markdown="1">

**Finished Works**:
1. Design the mechanical structure and simulate the platform's motion, using internal toothed rotary bearings to minimize the structural size. Protective structures have been designed for all sensor components.

2. Design hardware control algorithms for pan-tilt using STM32 and A4988 drivers, and establish communication between STM32 and the host computer's ROS system for pan-tilt motion control within ROS.

3. Propose a target tracking method based on HOG and SIFT feature matching, capable of short-term single target tracking while maintaining robustness to changes in the target object's appearance.

4. Construct an experimental Pan-Tilt system and conduct experiments with all proposed algorithms, using 3D printed structural components, a Realsense camera, and stepper motors.

</div>
</div>

<!-- Project -->

# 📝 Academic Services
- ACM Multimedia (ACMMM) 2024, Reviewer
- Conference on Neural Information Processing Systems (NeurIPS) 2024, Reviewer

# 🏆 Honors and Awards

## 🏅 Honors
- *2023.12*, First Class Master's Scholarship from USTC
- *2023.09*, Outstanding Graduate of Hohai University (Top 1%)
- *2023.02*, Xiaomi Scholarship Special Prize (Top 1%)
- *2022.10*, First Prize of Yan Kai Scholarship (Top 1%)
- *2020.09*, National Scholarship for Undergraduate Student (Top 1%)
- *2020.12*, Excellent Student Model in Hohai University
- *2020.09*, The First Prize Scholarship in Hohai University

## 🎏 Competitions
- *2020.09*, Third Prize in the National College Student Intelligent Car Competition.
- *2022.12*, Blue Bridge Cup Software Design Competition National Third Prize.
- *2022.09*, National Second Prize in the National College Student Electronic Design Competition.

# 💼 Societies
- *2023.09 - 2024.07 (now)*, Leader of Multimodal Generation Group of Microsoft Multimedia Computing and Communication State Key Laboratory.
- *2020.09 - 2021.06*, Director of the Competition Service Department of the Internet of Things Institute.
- *2019.09 - 2020.06*, Member of the Software Technology Department of the Association for Science and Technology of the Internet of Things.

<!-- # 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->