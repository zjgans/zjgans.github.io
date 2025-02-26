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

I am currently a PhD student in Computer Science at [Sun Yat-sen University](https://www.sysu.edu.cn/), advised by Prof. [Xiaodan Liang](https://scholar.google.com/citations?hl=zh-CN&user=voxznZAAAAAJ) (粱小丹) at [the Human Cyber Physical Intelligence Integration Lab (HCP-I2 Lab)](https://www.sysu-hcp.net/). I received my BS from [Sun Yat-sen University](https://www.sysu.edu.cn/), advised by Prof.[Qingling Cai](https://scholar.google.com/citations?hl=zh-CN&user=-KcEiOAAAAAJ&view_op=list_works&sortby=pubdate). I am also lucky to have opportunities to collaborate with [Calvin Yu-Chian Chen](https://www.ece.pku.edu.cn/info/1053/2659.htm) (Professor at Peking University).

My primary research interests lie in the areas of image generation and diffusion models, with a particular focus on instruction-based image editing. My work aims to enhance the capabilities of deep learning models to generate high-fidelity and controllable image content. By contributing to advancements in these fields, I hope to make a significant impact on applications such as photography, human-Computer interaction, advertising，and the gaming industries.

<!-- # 🔥 News
- *2024.01*: &nbsp;🎉🎉 One paper is accepted by the Computers in Biology and Medicine. 
- *2023.12*: &nbsp;🎉🎉 One paper is accepted by the Association for the Advancement of Artificial Intelligence(AAAI). 
- *2023.12*: &nbsp;🎉🎉 One paper is accepted by the Knowledge-Based Systems. 
- *2023.11*: &nbsp;🎉🎉 One paper is accepted by the Neurocomputing. 
- *2022.11*: &nbsp;🎉🎉 One paper is accepted by the Mathematics.  -->

# 🔥 News
- *2025.01*: &nbsp;🎉🎉 One paper was accepted by IEEE Transactions on Instrumentation & Measurement.
- *2024.11*: &nbsp;🎉🎉 Obtain the National Scholarship from the Sun Yat-sen University.
- *2024.04*: &nbsp;🎉🎉 Release (✨ 800+ Star), [ConsistentID](https://ssugarwh.github.io/consistentid.github.io/), one high-fidelity and fast customized portrait generation model.
- *2024.01*: &nbsp;🎉🎉 One paper was accepted by Computers in Biology and Medicine.
- *2023.12*: &nbsp;🎉🎉 Two papers were accepted by AAAI and Knowledge-Based Systems respectively.
- *2023.11*: &nbsp;🎉🎉 One paper was accepted by Neurocomputing.
- *2022.10*: &nbsp;🎉🎉 Obtain the Master's Scholarship for first class from the Sun Yat-sen University.
- *2021.11*: &nbsp;🎉🎉 Obtain the National Scholarship from the Nanchang University.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv</div><img src='images/publications/2024_Arxiv_ConsistentID.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[ConsistentID:Portrait Generation with Multimodal Fine-Grained Identity Preserving](https://arxiv.org/abs/2404.16771) \\
Jiehui Huang, Xiao Dong, Wenhui Song, Hanhui Li, **Jun Zhou**, Yuhao Cheng, Shutao Liao, Long Chen, Yiqiang Yan, Shengcai Liao, Xiaodan Liang*

[**Project**](https://github.com/JackAILab/ConsistentID), [**HuggingFace Demo**](https://huggingface.co/spaces/JackAILab/ConsistentID)  <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

- We introduce ConsistentID to improve fine-grained customized facial generation by incorporating detailed descriptions of facial regions and local facial features. 
- We devise an ID-preservation network optimized by facial attention localization strategy, enabling more accurate ID preservation and more vivid facial generation. 
- We introduce the inaugural fine-grained facial generation dataset, FGID, addressing limitations in existing datasets for capturing diverse identity-preserving facial details. 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Knowledge-Based System</div><img src='images/publications/2024KBS_TMBL.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[TMBL: Transformer-based multimodal binding learning model for multimodal sentiment analysis](https://doi.org/10.1016/j.knosys.2023.111346) \\
Jiehui Huang, **Jun Zhou**, Zhenchao Tang, Jiaying Lin, and Calvin Yu-Chian Chen*

[**Project**](https://github.com/JackAILab/TMBL) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

- Considering that existing multi-modal fusion systems rarely consider fine-grained word-level interactions, we redesigned the Transformer structure, effectively improving the ACC index by 6%. 
- In order to solve the problem of modal heterogeneity caused by multi-modal feature fusion, inspired by CLIP, a cross-model binding mechanism was designed for each modality to more effectively fuse modal features. 
- Aiming at the modal aliasing problem caused by the difficulty in distinguishing modal features, CLS and PositionEmbedding information are designed to effectively distinguish modal space and semantic relationships.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Neurocomputing</div><img src='images/publications/2024Neurocomputing_DTP.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Progressive network based on detail scaling and texture extraction: A more general framework for image deraining](https://www.sciencedirect.com/science/article/abs/pii/S092523122301189X) \\
Jiehui Huang, Zhenchao Tang, Xuedong He, **Jun Zhou**, Defeng Zhou, and Calvin Yu-Chian Chen*

[**Project**](https://github.com/JackAILab/DTPNet/tree/main) <strong><span class='show_paper_citations' data='4FA6C0AAAAAJ:qjMakFHDy7sC'></span></strong>

- In order to enhance the coupling and portability of the module, the existing rain removal module was redesigned and a multi-scale coupling method was established. A simple and effective strategy achieved a model increase of 5%.
- In order to improve the transferability and generalization of the model, a detail scaling module is designed to extract generalized features from degraded images and restore finer details to avoid distortion.
- The attention layer and feed-forward layer in the Transformer block are enhanced to extract universal features more efficiently, enhancing the model's ability to capture comprehensive and transferable features.
- The progressive learning strategy assists in learning more multi-scale features and achieves SOTA performance on data sets such as SPA-Data, RainDrop, RID, and Rain100.
</div>
</div>

# 🎖 Honors and Awards
- *2024.11*  National Scholarship of Sun Yat-sen University
- *2023.10*  President’s Scholarship of Sun Yat-sen University

# 💻 Internships
- *2024.0 - 2025.02*, with [Tencent Hunyuan](https://github.com/Tencent/HunyuanDiT) Team, Shenzhen.
- *2023.11 - 2024.05*, [Lenovo, Research Institute](https://research.lenovo.com/webapp/view/researchField.html), Shenzhen.
