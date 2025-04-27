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

# 😀 Profile
I am now a master student of Information and Communication Engineering at the [University of Science and Technology of China](https://www.ustc.edu.cn/), 
pursuing my master’s degree in the [School of Information Science and Technology](https://sist.ustc.edu.cn/), [University of Science and Technology of China](https://www.ustc.edu.cn/).
<!-- , supervised by [Xiaojun Chang](http://staff.ustc.edu.cn/~zhwg/). -->
Before this, I graduated from School of [College of Information Science and Engineering](https://ise.hhu.edu.cn/), [Hohai University](http://www.hhu.edu.cn/) with a bachelor’s degree.

My research interests include visual content generation, multimedia understand and alignment.

# 📖 Educations
- *2023.09 - Now*, [University of Science and Technology of China](https://www.ustc.edu.cn/), Heifei, (GPA: 3.92/4.0, rank: 5/112).
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
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/publications/cvpr2025.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**SmartEraser: Remove Anything from Images using Masked-Region Guidance**](https://arxiv.org/abs/2501.08279)

**Longtao Jiang**, Zhendong Wang, Jianming Bao, Wengang Zhou, Dong Chen, Houqiang Li

[**abstract**](https://arxiv.org/abs/2501.08279)
  - In this work, we introduce SmartEraser, built with a new ``{removing}" paradigm called Masked-Region Guidance. 
  - The paradigm guides the model to accurately identify the object to be removed, preventing its regeneration in the output. 
  - Since the user mask often extends beyond the object itself, it aids in preserving the surrounding context in the final result.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ACM MM 2024</div><img src='images/publications/acmmm24.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**SEDS: Semantically Enhanced Dual-Stream Encoder for Sign Language Retrieval**](https://arxiv.org/abs/2407.16394)

**Longtao Jiang**, Min Wang, Zecheng Li, Yao Fang, Wengang Zhou, Houqiang Li

[**abstract**](https://arxiv.org/abs/2407.16394)
  - propose a novel representation framework called Semantically Enhanced Dual-Stream Encoder (SEDS), which aggregates Pose and RGB modalities to represent local and global information of sign language videos.
  - The aggregated clip-level video features are then fed into the CLIP vision encoder for interaction, and matched with the word-level text features embedded using the CLIP text encoder.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TMM 2025</div><img src='images/publications/tmm2025.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[**Structure-guided Diffusion Transformer for Low-Light Image Enhancement**](https://arxiv.org/abs/2504.15054)

Xiangchen Yin, Zhenda Yu, **Longtao Jiang**, Xin Gao, Xiao Sun, Zhi Liu, Xun Yang

[**abstract**](https://arxiv.org/abs/2504.15054)
  - we firstly introduce DiT into the low-light enhancement task and design a novel Structure-guided Diffusion Transformer based Low-light image enhancement (SDTL) framework.
  - Extensive qualitative and quantitative experiments demonstrate that our method achieves SOTA performance on several popular datasets, validating the effectiveness of SDTL.

</div>
</div>

# 🔍 Projects

## Pre-Training of Web Page Understanding Based on Document Multimodal Large Language Model

<div class='paper-box'>
<div class='paper-box-image'>
<div class="badge">2023.01 - 2023.06</div>
<img src='images/projects/kuake.png' alt="sym" width="100%">
</div>
<div class='paper-box-text' markdown="1">

In recent years, a series of document pre training models represented by Microsoft LayoutLM have also achieved significant results in document understanding tasks.The Quark Vertical Innovation Team is responsible for solving the problem of document multimodal understanding in library type documents and web-based documents. The task of understanding web-based documents includes layout classification, page experience, semantic segmentation, node extraction, etc; The task of understanding library type documents includes layout classification, layout experience, domain categories, title extraction, etc. The two are very similar in terms of multimodal model structure and downstream analysis and understanding tasks.

</div>
</div>

# 📝 Academic Services
- Conference on Computer Vision and Pattern Recognition (CVPR) 2025, Reviewer
- ACM International Conference on Multimedia (ACM MM) 2024, Reviewer
- Conference on Neural Information Processing Systems (NeurIPS) 2024, Reviewer

# 🏅 Honors
- *2024.12*, HuaWei Scholarship from USTC
- *2023.12*, First Class Master's Scholarship from USTC
- *2023.09*, Outstanding Graduate of Hohai University (Top 1%)
- *2023.02*, Xiaomi Scholarship Special Prize (Top 1%)
- *2022.10*, First Prize of Yan Kai Scholarship (Top 1%)
- *2020.09*, National Scholarship for Undergraduate Student (Top 1%)
- *2020.12*, Excellent Student Model in Hohai University
- *2020.09*, The First Prize Scholarship in Hohai University

# 🏆 Competitions
- *2022.12*, National Second Prize in the National College Student Electronic Design Competition.
- *2022.09*, Blue Bridge Cup Software Design Competition National Third Prize.
- *2021.09*, Third Prize in the National College Student Intelligent Car Competition.