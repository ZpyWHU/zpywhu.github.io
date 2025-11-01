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
## 🔶Vision-Language Model

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025 Oral</div><img src='images/risebench.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Envisioning Beyond the Pixels: Benchmarking Reasoning-Informed Visual Editing](https://arxiv.org/abs/2504.02826)

**Xiangyu Zhao^**, **Peiyuan Zhang^**, **Kexian Tang^**, **Xiaorong Zhu^**, Hao Li, Wenhao Chai, Zicheng Zhang, Renqiu Xia, Guangtao Zhai, Junchi Yan, Hua Yang, Xue Yang, Haodong Duan

[**Project**](https://github.com/PhoenixZ810/RISEBench) <strong><span class='show_paper_citations' data='rQbW67AAAAAJ:d1gkVwhDpl0C'></span></strong>

<details>
<summary><b>Summary</b></summary>
This paper proposes RISEBench, the first benchmark for reasoning-informed visual editing, covering four core reasoning tasks—Temporal, Causal, Spatial, and Logical—and introducing a comprehensive evaluation framework with three key dimensions: Instruction Reasoning, Appearance Consistency, and Visual Plausibility.
</details>

</div>
</div>

## 🔷Object Detection

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/point2rbox-v2.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Point2RBox-v2: Rethinking Point-supervised Oriented Object Detection with Spatial Layout Among Instances](https://arxiv.org/pdf/2502.04268)

**Yi Yu^**, **Botao Ren^**, **Peiyuan Zhang^**, Mingxin Liu, Junwei Luo, Shaofeng Zhang, Feipeng Da, Junchi Yan, Xue Yang

[**Project**](https://github.com/VisionXLab/point2rbox-v2) <strong><span class='show_paper_citations' data='rQbW67AAAAAJ:u-x6o8ySG0sC'></span></strong>

<details>
<summary><b>Summary</b></summary>
This work rethinks point-supervised oriented object detection with the layout among instances. At the core are three principles: 1) Gaussian overlap loss. 2) Voronoi watershed loss. 3) Consistency loss. These principles lead to strong performance.
</details>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCV 2025</div><img src='images/pointobb-v3.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Pointobb-v3: Expanding Performance Boundaries of Single Point-Supervised Oriented Object Detection](https://arxiv.org/abs/2501.13898)

**Peiyuan Zhang^**, **Junwei Luo^**, **Xue Yang^**, Yi Yu, Qingyun Li, Yue Zhou, Xiaosong Jia, Xudong Lu, Jingdong Chen, Xiang Li, Junchi Yan, Yansheng Li

[**Project**](https://github.com/VisionXLab/PointOBB-v3) <strong><span class='show_paper_citations' data='rQbW67AAAAAJ:u5HHmVD_uO8C'></span></strong>

<details>
<summary><b>Summary</b></summary>
This work presents an extended conference version of PointOBB, which incorporates a novel Scale-Sensitive Feature Fusion (SSFF) module to improve the model's capability of perceiving object scales, and further proposes an end-to-end optimized framework. 
</details>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arxiv 2025</div><img src='images/pwood.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Partial Weakly-Supervised Oriented Object Detection](https://arxiv.org/abs/2507.02751)

**Mingxin Liu**, Peiyuan Zhang, Yuan Liu, Wei Zhang, Yue Zhou, Ning Liao, Ziyang Gong, Junwei Luo, Zhirui Wang, Yi Yu, Xue Yang

[**Project**](https://github.com/VisionXLab/PWOOD) <strong><span class='show_paper_citations' data='rQbW67AAAAAJ:d1gkVwhDpl0C'></span></strong>

<details>
<summary><b>Summary</b></summary>
This paper proposes PWOOD, a cost-effective framework for oriented object detection that uses partially weak and unlabeled data through orientation- and scale-aware learning, achieving competitive performance with much lower annotation cost.
</details>

</div>
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
