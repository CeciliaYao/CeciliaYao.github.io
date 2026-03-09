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

# About Me
Welcome! I'm Yuanqi Yao (姚元淇, CC Yao), a researcher at [INSAIT](https://insait.ai/), under the supervision of [Prof. Luc Van Gool](https://insait.ai/prof-luc-van-gool/) and [Dr. Danda Paudel](https://insait.ai/dr-danda-paudel/). My research focuses on **<font color="#ff79c6">Embodied AI, particularly Vision-Language-Action(VLA) foundation models.</font>** Welcome to discuss and collaborate!

Prior to this, I completed a long-term internship at the [Shanghai AI Laboratory](https://www.shlab.org.cn/), where I was supervised by [Dr. Dong Wang](https://scholar.google.es/citations?user=dasL9V4AAAAJ&hl=zh-CN) and [Prof. Xuelong Li](https://scholar.google.com/citations?user=ahUibskAAAAJ&hl=zh-CN).  I also earned both my Bachelor's and Master's degrees in Computer Science at [Harbin Institute of Technology (HIT)](http://en.hit.edu.cn/), where I was advised by [Prof. Junjun Jiang](https://scholar.google.com/citations?hl=zh-CN&user=WNH2_rgAAAAJ&view_op=list_works&sortby=pubdate).

# News
- *2026.03*: One paper is accepted by CVPR 2026!
- *2025.06*: One paper is accepted by IROS 2025!
- *2025.04*: Our paper **SpatialVLA** is accepted by [<ins>RSS 2025 Highlight</ins>](https://arxiv.org/abs/2501.15830) ([<ins>Project Page</ins>](https://spatialvla.github.io/))!
- *2025.03*: One paper is accepted by CVPR 2025!
- *2024.09*: One paper is accepted by NeurIPS 2024!
- *2024.07*: We placed 2<sup>nd</sup> in ECCV 2024 AIM Depth Upsampling Challenge!
- *2024.07*: One paper is accepted by ECCV 2024!

<span class='anchor' id='-internships'></span>

# Internships
- *2023.11 - 2025.07*, Embodied AI Intern, [**Shanghai AI Laboratory**](https://www.shlab.org.cn/)
- *2023.08 - 2023.11*, Computer Vision Intern,  [**Baidu VIS**](https://vis.baidu.com/#/)
- *2023.06 - 2023.08*, Computer Vision Research Intern, [**Lenovo Research**](https://research.lenovo.com/webapp/view_English/home.html)
- *2022.06 - 2022.10*, Autonomous Driving Perception Intern,  [**NIO**](https://www.nio.com/)

<span class='anchor' id='-honors-and-awards'></span>

# Honors and Awards
- **2<sup>nd</sup>** place at Multi-Agent Embodied Intelligence Challenge, Control Track (**NeurIPS 2025** Workshop)
- **2<sup>nd</sup>** place at ECCV 2024 AIM, Depth Upsampling Challenge (**ECCV 2024** Workshop)
- **1<sup>st</sup>** place at ICCV 2023 The ROAD++ Challenge, Agent Detection Track (**ICCV 2023** Workshop)
- **2<sup>nd</sup>** place at ICCV 2023 The ROAD++ Challenge, Road event detection Track (**ICCV 2023** Workshop)
- **3<sup>rd</sup>** place at ICRA 2023 The RoboDepth Challenge (**ICRA 2023** Workshop)
- **1<sup>st</sup>** Scholarship for Postgraduate Students. 2023-2024.
- The People's Scholarship in China. 2018-2020.
- **National Second Prize** (**Top 1%**), National University IoT Design Competition, **Huawei Cup**. 2019.

<span class='anchor' id='-publications'></span>

# Publications
<div class='paper-box' style="margin-top: -50px;"><div class='paper-box-image'><div><div class="badge">CVPR 2026</div><img src='images/hume.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">

  - **FM-Steer: Enhance Generalist Policies with Value-Guided Cascaded Denosing**
  
      Haoming Song\*, Delin Qu\*, **<ins><font color="#bd93f9">Yuanqi Yao</font></ins>**, Qizhi Chen, Jiarui Li, Qi Lv, Yiwen Tang, Li Kang, Heng Zhou, Xianqiang Gao, Yuhang Tang, Xiaofan Li, Modi Shi, Guanghui Ren, Maoqing Yao, Bin Zhao, Dong Wang, Xuelong Li.
    
      **<font color="#ff79c6">CVPR 2026</font>** \| [paper](https://arxiv.org/abs/2505.21432) \| [project page](https://hume-vla.github.io/)
  </div>
  </div>
  <div class='paper-box' style="margin-top: -50px;"><div class='paper-box-image'><div><div class="badge">IROS 2025</div><img src='images/fuse.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">

  - **FUSE: Label-Free Image-Event Joint Monocular Depth Estimation via Frequency-Decoupled Alignment and Degradation-Robust Fusion**
  
      Pihai Sun, Junjun Jiang, **<ins><font color="#bd93f9">Yuanqi Yao</font></ins>**, Youyu Chen, Wenbo Zhao, Kui Jiang, Xianming Liu.
    
      **<font color="#ff79c6">IROS 2025</font>** \| [paper](https://arxiv.org/abs/2503.19739) \| [project page](https://arxiv.org/abs/2503.19739)
  </div>
  </div>
  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">RSS 2025</div><img src='images/spatialvla.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
  
  - **SpatialVLA: Exploring Spatial Representations for Visual-Language-Action Models**
  
      Delin Qu\*, Haoming Song\*, Qizhi Chen\*, **<ins><font color="#bd93f9">Yuanqi Yao</font></ins>**, Xinyi Ye, Jiayuan Gu, Bin Zhao, Dong Wang, Xuelong Li.
    
      **<font color="#ff79c6">RSS 2025</font>** \| [paper](https://arxiv.org/abs/2501.15830) \| [project page](https://spatialvla.github.io/)
  </div>
  </div>
  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/ppl.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
  
  - **Think Small, Act Big: Primitive Prompt Learning for Lifelong Robot Manipulation**
    
    **<ins><font color="#bd93f9">Yuanqi Yao</font></ins>**, Siao Liu, Haoming Song, Yan Ding, Bin Zhao, Zhigang Wang, Dong Wang, Xuelong Li.
    
    **<font color="#ff79c6">CVPR 2025</font>** \| [paper](https://arxiv.org/abs/2504.00420) \| [project page](https://arxiv.org/abs/2504.00420)
  </div>
  </div>
  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/scat_eccv.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
    
  - **Improving Domain Generalization in Self-Supervised Monocular Depth Estimation via Stabilized Adversarial Training**
    
    **<ins><font color="#bd93f9">Yuanqi Yao</font></ins>**, Gang Wu, Kui Jiang, Siao Liu, Jian Kuai, Xianming Liu, Junjun Jiang. 
    
    **<font color="#ff79c6">ECCV 2024</font>** \| [paper](https://arxiv.org/abs/2411.02149) \| [project page](https://arxiv.org/abs/2411.02149)
  </div>
  </div>
  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">Under Review</div><img src='images/nips2024.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
    
  - **Enhance Image-Based Rendering with Unsupervised Source-View Geometric Constrain**
  
    Youyu Chen, Junjun Jiang, **<ins><font color="#bd93f9">Yuanqi Yao</font></ins>**, Kui Jiang, Wenbo Zhao, Xianming Liu.
    
    Under Review, 2024
  </div>
  </div>
  <div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/mllmguard.png' alt="sym" width="100%"></div></div>
  <div class='paper-box-text' markdown="1">
    
  - **MLLMGuard: A Multi-dimensional Safety Evaluation Suite for Multimodal Large Language Models**
  
    Tianle Gu, Zeyang Zhou, Kexin Huang, Dandan Liang, Yixu Wang, Haiquan Zhao, **<ins><font color="#bd93f9">Yuanqi Yao</font></ins>**, Xingge Qiao, Keqing Wang, Yujiu Yang, Yan Teng, Yu Qiao, Yingchun Wang.
    
    **<font color="#ff79c6">NeurIPS 2024</font>** \| [paper](https://arxiv.org/abs/2406.07594) \| [project page](https://github.com/AI45Lab/MLLMGuard)
  </div>
  </div>

<span class='anchor' id='-meow-and-woof'></span>

# Meow & Woof
<div align="center" style="display: flex; justify-content: center; gap: 10px; margin-top: -30px;">
  <figure style="text-align: center; width: 270px;">
    <img src="https://p.sda1.dev/24/9bca91f30ac7ce09c7ec1fe9bae96807/Toby.jpg" alt="My dog Toby" style="width: 100%; height: auto; aspect-ratio: 2/3;"/>
    <figcaption>
      <strong>Toby</strong><br/>
      <em>2011 – 2024</em><br/>
      A lively, loving boy who stayed with me through every stage of life.
    </figcaption>
  </figure>
  <figure style="text-align: center; width: 270px;">
    <img src="images/Hz.jpg" alt="My cat Hz" style="width: 100%; height: auto; aspect-ratio: 2/3;"/>
    <figcaption>
      <strong>Hz</strong><br/>
      <em>2023 - </em><br/>
      A clingy girl with stunning blue eyes who loves to lick me.
    </figcaption>
  </figure>
  <figure style="text-align: center; width: 270px;">
    <img src="images/HuHu.jpg" alt="My cat HuHu" style="width: 100%; height: auto; aspect-ratio: 2/3;"/>
    <figcaption>
      <strong>HuHu</strong><br/>
      <em>2023 - </em><br/>
      A smart and talkative girl with big round eyes and a curious spirit.
    </figcaption>
  </figure>
</div>








