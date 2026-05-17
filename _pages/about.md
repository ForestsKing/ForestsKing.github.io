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

I'm a PhD student in the class of 2023 at the <a href='https://nirc.bupt.site/'>Network Intelligence Research Center (NIRC)</a> within the <a href='https://www.bupt.edu.cn/'>Beijing University of Posts and Telecommunications (BUPT)</a>, advised by Prof. <a href='https://scholar.google.com/citations?user=2W2h0SwAAAAJ'>Qi Qi</a> and Prof. <a href='https://jericwang.github.io/'>Jingyu Wang</a>. My primary research interests focus on time series analysis and genomic foundation model. I have published several relevant papers in top conferences with total <a href='https://scholar.google.com/citations?user=6KQpKtgAAAAJ'>google scholar citations 307 / 326</a>.

If you are interested in collaborating on research projects, offering internship opportunities, or exchange programs, I would be thrilled to connect with you. You can also find my CV here: <a href='files/CV_EN.pdf'>EN</a> / <a href='files/CV_ZH.pdf'>ZH</a>.

# 🔥 News

- *2025.09*: &nbsp;🎉🎉🎉 <a href='https://dl.acm.org/doi/full/10.1145/3759460'>MCAKE: Memory-Augmented Autoencoder with Contrastive Learning for Unsupervised Anomaly Detection</a> has been accepted by **TKDD 2025**.
- *2024.12*: &nbsp;🎉🎉🎉 <a href='https://ojs.aaai.org/index.php/AAAI/article/view/33384'>ChatTime: A Unified Multimodal Time Series Foundation Model Bridging Numerical and Textual Data</a> has been accepted by **AAAI 2025 \[oral\]**.
- *2024.09*: &nbsp;🎉🎉🎉 <a href='https://proceedings.neurips.cc/paper_files/paper/2024/hash/2783192ea2696ee2ceb8746f5eea6681-Abstract-Conference.html'>Rethinking the Power of Timestamps for Robust Time Series Forecasting: A Global-Local Fusion Perspective</a> has been accepted by **NeurIPS 2024**.
- *2023.09*: &nbsp;🎉🎉🎉 <a href='https://proceedings.neurips.cc/paper_files/paper/2023/hash/22f5d8e689d2a011cd8ead552ed59052-Abstract-Conference.html'>Drift doesn’t Matter: Dynamic Decomposition with Diffusion Reconstruction for Unstable Multivariate Time Series Anomaly Detection</a> has been accepted by **NeurIPS 2023**.

# 📖 Educations

- *2023.09 – Present*, PhD Student, Computer Science and Technology, Beijing University of Posts and Telecommunications.
- *2022.09 – 2023.06*, MS Student, Computer Science and Technology, Beijing University of Posts and Telecommunications.
- *2018.09 – 2022.06*, Undergrad Student, Automation, Beijing University of Posts and Telecommunications.

# 🛵 Experiences

- *2025.02 – 2025.05*, Research Intern, Noah's Ark Lab, Huawei Technologies.

# 🌱 Services

- Conferences
  - Reviewer, The Thirty-Second SIGKDD Conference on Knowledge Discovery and Data Mining (SIGKDD 2026, h5=124)
  - Reviewer, The Forty-Third International Conference on Machine Learning (ICML 2026, h5=272)
  - Reviewer, The Fourteenth International Conference on Learning Representations (ICLR 2026, h5=362)
  - Reviewer, The Fortieth AAAI Conference on Artificial Intelligence (AAAI 2026, h5=232)
  - Reviewer, The Thirty-Ninth Annual Conference on Neural Information Processing Systems (NeurIPS 2025, h5=371)
  - Reviewer, The Forty-Second International Conference on Machine Learning (ICML 2025, h5=272)
  - Reviewer, The Thirteenth International Conference on Learning Representations (ICLR 2025, h5=362)
  - Reviewer, The Thirty-Eighth Annual Conference on Neural Information Processing Systems (NeurIPS 2024, h5=371)
- Journals
  - Reviewer, IEEE Transactions on Knowledge and Data Engineering (TKDE, h5=126)
  - Reviewer, IEEE Transactions on Neural Networks and Learning Systems (TNNLS, h5=165)

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TKDD 2026</div><img src='images/publications/MCAKE.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**MCAKE: Memory-Augmented Autoencoder with Contrastive Learning for Unsupervised Anomaly Detection**

**Chengsen Wang**, Qi Qi, Jinming Wu, Haifeng Sun, Zirui Zhuang, Yuhan Jing, Lianyuan Li, Jingyu Wang

<a href='https://dl.acm.org/doi/full/10.1145/3759460'>**[Paper]**</a>  <a href='https://github.com/ForestsKing/MCAKE'>**[Code]**</a>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025 [oral]</div><img src='images/publications/ChatTime.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**ChatTime: A Unified Multimodal Time Series Foundation Model Bridging Numerical and Textual Data**

**Chengsen Wang**, Qi Qi, Jingyu Wang, Haifeng Sun, Zirui Zhuang, Jinming Wu, Lei Zhang, Jianxin Liao

<a href='https://ojs.aaai.org/index.php/AAAI/article/view/33384'>**[Paper]**</a>  <a href='https://github.com/ForestsKing/ChatTime'>**[Code]**</a>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/publications/GLAFF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Rethinking the Power of Timestamps for Robust Time Series Forecasting: A Global-Local Fusion Perspective**

**Chengsen Wang**, Qi Qi, Jingyu Wang, Haifeng Sun, Zirui Zhuang, Jinming Wu, Jianxin Liao

<a href='https://proceedings.neurips.cc/paper_files/paper/2024/hash/2783192ea2696ee2ceb8746f5eea6681-Abstract-Conference.html'>**[Paper]**</a>  <a href='https://github.com/ForestsKing/GLAFF'>**[Code]**</a>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2023</div><img src='images/publications/D3R.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

**Drift doesn’t Matter: Dynamic Decomposition with Diffusion Reconstruction for Unstable Multivariate Time Series Anomaly Detection**

**Chengsen Wang**, Zirui Zhuang, Qi Qi, Jingyu Wang, Xingyu Wang, Haifeng Sun, Jianxin Liao

<a href='https://proceedings.neurips.cc/paper_files/paper/2023/hash/22f5d8e689d2a011cd8ead552ed59052-Abstract-Conference.html'>**[Paper]**</a>  <a href='https://github.com/ForestsKing/D3R'>**[Code]**</a>

</div>
</div>

# 👀 Visitors

<script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=3mdJGbhpaHXvMScIWLLG2cWeQONvMTnaX-MRowCtuH8&cl=ffffff&w=400"></script>

<br>