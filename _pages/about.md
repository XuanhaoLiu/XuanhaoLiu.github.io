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

I am a Ph.D student in the Department of Computer Science and Engineering at Shanghai Jiao Tong University.

I graduated from Sun Yat-Sen University with a bachelor’s degree.

My research interests include EEG analysis and Brain-Computer Interfaces.

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- *2025.04*: &nbsp;🎉🎉 Our paper _mixEEG_ has been accepted by CogSci 2025 for Oral presentation.
- *2024.10*: &nbsp;🎉🎉 Our paper _SEED-VII_ has been accepted by IEEE TAFFC.
- *2024.09*: &nbsp;🎉🎉 Our paper _EEG2Video_ has been accepted by NeurIPS 2024.
- *2024.08*: &nbsp;🎉🎉 Our paper _MoGE_ has been accepted by IEEE BIBM 2024.

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/seed-dv.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[EEG2Video: Towards Decoding Dynamic Visual Perception from EEG Signals](https://openreview.net/forum?id=RfsfRn9OFd)

**Xuan-Hao Liu**, Yan-Kai Liu, Yansen Wang, Kan Ren, Hanwen Shi, Zilong Wang, Dongsheng Li, Bao-Liang Lu, Wei-Long Zheng

[**Project**](https://bcmi.sjtu.edu.cn/home/eeg2video) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- We develop a large dataset recording signals from 20 subjects while they were watching 1400 dynamic video clips of 40 concepts.
- We annotate each video clips to investigate the potential for decoding some specific meta information (e.g., color, dynamic, human or not) from EEG.
- We propose a novel framework EEG2Video for video reconstruction from EEG signals.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CogSci 2025 Oral</div><img src='images/mixeeg.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[mixEEG: Enhancing EEG Federated Learning for Cross-subject EEG Classification with Tailored mixup]()

**Xuan-Hao Liu**, Bao-Liang Lu, Wei-Long Zheng

[**Project**](https://github.com/XuanhaoLiu/mixEEG) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- For the first time, we investigate the cross-subject EEG classification in the FL setting, including the DG FL and DA FL settings.
- We propose a simple yet effective framework termed **mixEEG**. Specifically, we tailor the vanilla mixup considering the unique properties of the EEG modality.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TAFFC</div><img src='images/seed7.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[SEED-VII: A Multimodal Dataset of Six Basic Emotions with Continuous Labels for Emotion Recognition](https://ieeexplore.ieee.org/abstract/document/10731546)

Wei-Bang Jiang, **Xuan-Hao Liu**, Wei-Long Zheng, Bao-Liang Lu

[**Project**](https://bcmi.sjtu.edu.cn/home/seed/seed-vii.html) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- To systematically explore human emotions, we develop a multimodal dataset consisting of six basic (happiness, sadness, fear, disgust, surprise, and anger) emotions and the neutral emotion, named SEED-VII. 
</div>
</div>

- [EEG2Video: Towards Decoding Dynamic Visual Perception from EEG Signals](https://openreview.net/forum?id=RfsfRn9OFd), **Xuan-Hao Liu**, Yan-Kai Liu, Yansen Wang, Kan Ren, Hanwen Shi, Zilong Wang, Dongsheng Li, Bao-Liang Lu, Wei-Long Zheng, **NeurIPS 2024**
- [SEED-VII: A Multimodal Dataset of Six Basic Emotions with Continuous Labels for Emotion Recognition](https://ieeexplore.ieee.org/abstract/document/10731546), Wei-Bang Jiang, **Xuan-Hao Liu**, Wei-Long Zheng, Bao-Liang Lu, **IEEE TAFFC 2024**
- [Multimodal adaptive emotion transformer with flexible modality inputs on a novel dataset with continuous labels](https://dl.acm.org/doi/abs/10.1145/3581783.3613797), Wei-Bang Jiang, **Xuan-Hao Liu**, Wei-Long Zheng, Bao-Liang Lu, **ACM MM 2023**

# 🎖 Honors and Awards
- *2022.10* Shanghai Jiao Tong University Graduate First Prize Scholarship.
- *2023.10* Shanghai Jiao Tong University Graduate First Prize Scholarship.

# 📖 Educations
- *2024.06 - present*, Ph.D student, Computer Science and Technology, Shanghai Jiao Tong University.
- *2022.09 - 2024.06*, M.S student, Computer Science and Technology, Shanghai Jiao Tong University.
- *2018.09 - 2022.06*, Theoretical and Applied Mechanics, Sun Yat-Sen University.
- *2015.09 - 2018.06*, The High School Attached to Hunan Normal University.

<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

# 💻 Internships
- *2023.11 - 2024.05*, Microsoft Research Asia, Shanghai, China.
