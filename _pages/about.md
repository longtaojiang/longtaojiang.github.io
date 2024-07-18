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
<!-- <div class='paper-box'>
<div class='paper-box-image'>
<img src='images/alibaba.png' alt="sym" width="100%">
</div>
<div class='paper-box-text' markdown="1"> -->
- *2023.01 - 2023.06*, [Alibaba, Quark Search Department](https://ali-home.alibaba.com/about-alibaba-businesses-1496656660737818624), Hangzhou.

# 📃 Papers

<!-- Paper -->
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/publications/acmmm24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**SEDS: Semantically Enhanced Dual-Stream Encoder for Sign Language Retrieval**](https://arxiv.org/abs/2303.12793)

**Longtao Jiang**, Min Wang, Zecheng Li, Yao Fang, Wengang Zhou, Houqiang Li

[**abstract**](https://arxiv.org/abs/2303.12793)
  - Sign language video retrieval, as an emerging visual-language task, is more biased towards understanding the semantic information of human actions contained in video clips.
  - We propose a novel representation framework called Semantically Enhanced Dual-Stream Encoder (SEDS), which integrates Pose and RGB modalities to represent local and global information of sign language videos.

</div>
</div>

<!-- Paper -->

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">computer measurement and control</div><img src='images/publications/littlecar_paper.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Design and Research of Intelligent Drug Delivery Robot System Based on ARM and Machine Vision**](https://www.nstl.gov.cn/paper_detail.html?id=c96622f8c2e6a3f659511a01787e825a)

**Longtao Jiang**, Yipei Liu, Zhuo Zhang

[**abstract**](https://www.nstl.gov.cn/paper_detail.html?id=c96622f8c2e6a3f659511a01787e825a)
 A medical intelligent drug delivery robot system based on embedded system is designed. The staff can give the house number room that the robot should distribute at the initial pharmacy location. After the automatic detection of drug cargo loading, the robot will complete a series of distribution tasks, including drug delivery ward house number identification, path planning, parking and unloading. The system takes STM32 high-performance ARM chip as the control core, carries k210 embedded platform with KPU neural network arithmetic unit for house number recognition, and carries out machine vision tracking through openmv open source hardware. It can accurately complete its own drug distribution task in complex medical environment. Through the experimental test of the system, the robot runs efficiently and stably, and has certain popularization value. 

</div>
</div> -->

<!-- - <code class="language-plaintext highlighter-rouge">IEEE Sensors Journal</code> [**Kalman Filter-based EM-optical Sensor Fusion for Bone Needle Position Tracking**](https://doi.org/10.1109/JSEN.2024.3364701)<br>
Zhiyu Xia, Han Wang, Yulong Men, **Haofei Ma**, Zexin Cao, Weidong Wang, Zhijiang Du, "Kalman Filter-based EM-optical Sensor Fusion for Bone Needle Position Tracking." IEEE Sensors Journal, 2024. (SCI-Q2) -->

# 🔍 Projects

## Pre-Training of Web Page Understanding Based on Document Multimodal Large Language Model

<div class='paper-box'>
<div class='paper-box-image'>
<div class="badge">2023.01 - 2023.06</div>
<img src='images/projects/kuake.png' alt="sym" width="100%">
</div>
<div class='paper-box-text' markdown="1">

In recent years, a series of document pre training models represented by Microsoft LayoutLM have also achieved significant results in document understanding tasks.The Quark Vertical Innovation Team is responsible for solving the problem of document multimodal understanding in library type documents and web-based documents. The task of understanding web-based documents includes layout classification, page experience, semantic segmentation, node extraction, etc; The task of understanding library type documents includes layout classification, layout experience, domain categories, title extraction, etc. The two are very similar in terms of multimodal model structure and downstream analysis and understanding tasks. Quark explored modal document pre training techniques suitable for web-based data based on its own search engine's massive web page data, and achieved significant improvements in downstream tasks of analyzing and understanding multiple web pages.

</div>
</div>

<!-- Project -->

## Intelligent Delivery Robot Based on Machine Vision

<div class='paper-box'>
<div class='paper-box-image'>
<div class="badge">2022.08 - 2022.12</div>
<img src='images/projects/littlecar.png' alt="sym" width="100%">
</div>
<div class='paper-box-text' markdown="1">

In view of the current shortage of human resources under the COVID-19 epidemic, the high risk of medical personnel, and the demand for the automation of the medical distribution service system. A medical intelligent delivery robot system based on embedded technology has been designed. The staff can provide the door number room that the robot should deliver at the initial pharmacy location. After automatic detection of drug cargo loading, the robot will complete a series of delivery tasks including identifying the door number of the delivery ward, path planning, parking and unloading. The system uses the STM32 high-performance ARM chip as the control core and is equipped with the K210 embedded platform with KPU neural network operator for house number recognition. It uses OPENMV4Plus open-source hardware for machine vision tracking and can accurately complete its own delivery tasks in complex industrial environments.

</div>
</div>

# 📚 Patents

- <code class="language-plaintext highlighter-rouge">Invention Patent</code> [**An Intelligent Vehicle System Based on Electromagnetic Positioning**](https://xueshu.baidu.com/usercenter/paper/show?paperid=1a4w0r20cd1p08708x0k0r00e5163321&site=xueshu_se), **Longtao Jiang**, Zhiheng Zeng, Yipei Liu (CN202111388699.X)

- <code class="language-plaintext highlighter-rouge">Invention Patent</code> [**A vehicle positioning system based on electromagnetic waves**](https://xueshu.baidu.com/usercenter/paper/show?paperid=1s3y0v80hm7w0jc06p3t0r00sc563453&site=xueshu_se), Yipei Liu, **Longtao Jiang**, Zhiheng Zeng (CN202210222945.2)

- <code class="language-plaintext highlighter-rouge">Invention Patent</code> [**A machine vision based autonomous tracking intelligent vehicle**](https://xueshu.baidu.com/usercenter/paper/show?paperid=174a0ej0uy7x0xf0820b0ms01b755398&site=xueshu_se), Zhiheng Zeng, Yipei Liu, **Longtao Jiang**, Zhaowen Chen (CN202111286807.2)
- 

# 📝 Academic Services
- ACM Multimedia (ACMMM) 2024, Reviewer
- Conference on Neural Information Processing Systems (NeurIPS) 2024, Reviewer

# 🏅 Honors
- *2023.12*, First Class Master's Scholarship from USTC
- *2023.09*, Outstanding Graduate of Hohai University (Top 1%)
- *2023.02*, Xiaomi Scholarship Special Prize (Top 1%)
- *2022.10*, First Prize of Yan Kai Scholarship (Top 1%)
- *2020.09*, National Scholarship for Undergraduate Student (Top 1%)
- *2020.12*, Excellent Student Model in Hohai University
- *2020.09*, The First Prize Scholarship in Hohai University

# 🏆 Competitions
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