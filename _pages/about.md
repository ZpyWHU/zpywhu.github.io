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

I am an incoming Ph.D. student at Shanghai Jiao Tong University, advised by [Prof. Xue Yang](https://yangxue.site/) and [Prof. Junchi Yan](https://scholar.google.com/citations?user=ga230VoAAAAJ&hl=en).

Previously, I was an undergraduate student at Wuhan University, where I worked with [Prof. Yansheng Li](https://jszy.whu.edu.cn/liyansheng/zh_CN/index.htm).

My research interests include Deep Learning and Computer Vision, with a focus on **<mark>(Unified) Multimodal Large Language Model</mark>** and **<mark>Object Detection</mark>**.

I am always open to academic collaboration—feel free to reach out to me at 📧 <a href="mailto:peiyuanzhangwhu@whu.edu.cn">peiyuanzhangwhu@whu.edu.cn</a>.

# 🔥 News
- *2025.02*: &nbsp;🎉🎉 One paper related to OBB (Point2RBox-v2) is accepted by **CVPR**！
- *2025.05*: &nbsp;🎉🎉 One paper related to OBB (PointOBB-v3) is accepted by **IJCV**！
- *2025.07*: &nbsp;🎉🎉 One paper related to OBB (PWOOD) is now available on arXiv
- *2025.09*: &nbsp;🎉🎉 One paper related to VLM (RISEBench) is accepted by **NeurIPS Datasets and Benchmarks Track oral _<mark>(Top 0.35%)</mark>_**！


# 📝 Publications 

## 🔶 Vision-Language Model

<div class="paper-card">
  <img src="images/risebench.png" alt="RISEBench">
  <div class="meta">
    <span class="tag">🧠 Vision-Language</span>
    <span class="tag">NeurIPS 2025 Oral</span>
  </div>
  <a href="https://arxiv.org/abs/2504.02826" class="title">
    Envisioning Beyond the Pixels: Benchmarking Reasoning-Informed Visual Editing
  </a>
  <p class="authors">Xiangyu Zhao*, Peiyuan Zhang*, Kexian Tang*, Xiaorong Zhu*, Hao Li, Wenhao Chai, Zicheng Zhang, Renqiu Xia, Guangtao Zhai, Junchi Yan, Hua Yang, Xue Yang, Haodong Duan</p>
  <p class="desc">
    Introduces <b>RISEBench</b> — the first benchmark for reasoning-informed visual editing, covering four reasoning types (Temporal, Causal, Spatial, Logical) with a three-dimensional evaluation framework.
  </p>
  <p class="links">
    [📄 Paper](https://arxiv.org/abs/2504.02826) | [💻 Code](https://github.com/PhoenixZ810/RISEBench)
  </p>
</div>


## 🔷 Object Detection

<div class="paper-card">
  <img src="images/point2rbox-v2.png" alt="Point2RBox-v2">
  <div class="meta">
    <span class="tag">📦 Object Detection</span>
    <span class="tag">CVPR 2025</span>
  </div>
  <a href="https://arxiv.org/pdf/2502.04268" class="title">
    Point2RBox-v2: Rethinking Point-supervised Oriented Object Detection with Spatial Layout Among Instances
  </a>
  <p class="authors">Yi Yu*, Botao Ren*, Peiyuan Zhang*, Mingxin Liu, Junwei Luo, Shaofeng Zhang, Feipeng Da, Junchi Yan, Xue Yang</p>
  <p class="desc">
    Proposes a rethinking of point-supervised OBB detection via spatial layout priors, introducing <b>Gaussian overlap</b>, <b>Voronoi watershed</b>, and <b>Consistency</b> losses for strong performance.
  </p>
  <p class="links">
    [📄 Paper](https://arxiv.org/pdf/2502.04268) | [💻 Code](https://github.com/VisionXLab/point2rbox-v2)
  </p>
</div>

<div class="paper-card">
  <img src="images/pointobb-v3.png" alt="PointOBB-v3">
  <div class="meta">
    <span class="tag">📦 Object Detection</span>
    <span class="tag">IJCV 2025</span>
  </div>
  <a href="https://arxiv.org/abs/2501.13898" class="title">
    PointOBB-v3: Expanding Performance Boundaries of Single Point-Supervised Oriented Object Detection
  </a>
  <p class="authors">Peiyuan Zhang*, Junwei Luo*, Xue Yang*, Yi Yu, Qingyun Li, Yue Zhou, Xiaosong Jia, Xudong Lu, Jingdong Chen, Xiang Li, Junchi Yan, Yansheng Li</p>
  <p class="desc">
    Extends <b>PointOBB</b> with a <b>Scale-Sensitive Feature Fusion (SSFF)</b> module and end-to-end optimization to boost scale perception and detection accuracy.
  </p>
  <p class="links">
    [📄 Paper](https://arxiv.org/abs/2501.13898) | [💻 Code](https://github.com/VisionXLab/PointOBB-v3)
  </p>
</div>

<div class="paper-card">
  <img src="images/pwood.png" alt="PWOOD">
  <div class="meta">
    <span class="tag">📦 Object Detection</span>
    <span class="tag">arXiv 2025</span>
  </div>
  <a href="https://arxiv.org/abs/2507.02751" class="title">
    Partial Weakly-Supervised Oriented Object Detection
  </a>
  <p class="authors">Mingxin Liu, Peiyuan Zhang, Yuan Liu, Wei Zhang, Yue Zhou, Ning Liao, Ziyang Gong, Junwei Luo, Zhirui Wang, Yi Yu, Xue Yang</p>
  <p class="desc">
    Presents <b>PWOOD</b>, a cost-efficient OBB framework leveraging partially weak and unlabeled data via orientation- and scale-aware learning to reduce annotation cost.
  </p>
  <p class="links">
    [📄 Paper](https://arxiv.org/abs/2507.02751) | [💻 Code](https://github.com/VisionXLab/PWOOD)
  </p>
</div>



# 🏅 Honors and Awards

- **2025.10**  Lei Jun Scholarship of CS, Wuhan University (Top 1%)

- **2025.09**  First-class Scholarship of CS, Wuhan University (Top 5%)

- **2025.08**  National College Students Computer System Capability Competition (XiaomiCup) **National First Prize**
  
- **2024.12**  National College Students Computer System Capability Competition (PolarDB)  **National Winning Prize**
  
- **……**


# 🎓 Educations
- *2022.09 - now*, Wuhan University, School of Computer Science. 

# 💬 Invited Talks
Not yet — but my GPU has heard plenty of my research talks. 

# 🧑‍💻 Internships
- *2023.12 - 2025.06*, WHU SkyEarth
- *2024.07 - now*, SJTU VisionXLab
