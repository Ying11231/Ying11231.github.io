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

I am currently a fourth-year undergraduate student at Nanjing University of Chinese Medicine.

I love KPOP...

> 📢📢📢 <font color=red>I am looking for a Ph.D. position (2024 Fall).</font> If you would like to discuss potential opportunities or learn more about my qualifications, please feel free to [contact me](mailto:lin.yuxiang.contact@gmail.com). 😊


# 🔥 News
- *2023.07*: One paper is accepted by ACM MM Grand Challenge 2023! 🎉
- *2023.07*: We win the second prize in MER-SEMI, Multimodal Emotion Recognition, ACM MM 2023 Grand Challenge! 🥈
- *2023.05*: I was awarded a Dahua outstanding scholarship (4000 CNY)! 🏆
- *2023.04*: One first-author paper is accepted by IEEE International Conference on Real-time Computing and Robotics 2023! 🎉
- *2023.02*: I join [SIAT, CAS](https://english.siat.ac.cn/) as a visiting student to doing research! 🔬
- *2022.05*: We win the second prize in China Undergraduate Mathematical Contest after one year's preparation (top 2%). Thanks all my teammates! 🥈


# 📝 Publications
## 📌 Pinned
<div class='paper-box-top'><div class='paper-box-top-image'><div><div class="badge">CVPR 2023 (Highlight)</div><img src='images/repmode.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-top-text' markdown="1">

[RepMode: Learning to Re-parameterize Diverse Experts for Subcellular Structure Prediction](https://openaccess.thecvf.com/content/CVPR2023/html/Zhou_RepMode_Learning_to_Re-Parameterize_Diverse_Experts_for_Subcellular_Structure_Prediction_CVPR_2023_paper.html)

**Donghao Zhou**, Chunbin Gu, Junde Xu, Furui Liu, Qiong Wang, Guangyong Chen, Pheng-Ann Heng

**<font color=red>CVPR 2023 (Highlight)</font>** \| [[Project]](https://correr-zhou.github.io/RepMode/) [[Paper]](https://arxiv.org/pdf/2212.10066.pdf) [[Code]](https://github.com/Correr-Zhou/RepMode) [[Poster]](resources/repmode_poster.pdf) [[Talk]](https://www.techbeat.net/talk-info?id=783)
- We model fluorescence staining as a 3D dense prediction task termed subcellular structure prediction (SSP).
- We propose Re-parameterizing Mixture-of-Diverse-Experts (RepMode), a network that dynamically organizes its parameters with task-aware priors.
<!-- -  to handle specified single-label prediction tasks of SSP. -->
- Experiments show that RepMode can attain SOTA overall performance on twelve prediction tasks and achieve effiecent task-incremental learning.

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/acktheunknown.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Acknowledging the Unknown for Multi-Label Learning with Single Positive Labels](https://link.springer.com/chapter/10.1007/978-3-031-20053-3_25)

**Donghao Zhou**, Pengfei Chen, Qiong Wang, Guangyong Chen, Pheng-Ann Heng

**<font color=red>ECCV 2022</font>** \| [[Paper]](https://arxiv.org/pdf/2203.16219.pdf) [[Code]](https://github.com/Correr-Zhou/SPML-AckTheUnknown) [[Poster]](resources/acktheunknown_poster.pdf) [[Slides]](resources/acktheunknown_10min_slides.pdf)
<!-- ![](https://img.shields.io/github/stars/Correr-Zhou/SPML-AckTheUnknown?style=social) -->
- This work focuses on single positive multi-label learning (SPML), an extreme of weakly supervised learning problem.
- We choose to treat all unannotated labels from a novel perspective, and hence propose our entropy-maximization loss (with a special gradient regime) and asymmetric pseudo-labeling (with asymmetric-tolerance strategies).
- Our method achieves SOTA results on all four SPML benchmarks and various analyses are provided to verify its effectiveness and rationality.

</div>
</div>

<!-- # 👨‍💻 Experience
- *2023.04 - now* &ensp; Research Intern, [Tencent YouTu Lab](https://open.youtu.qq.com/), Shenzhen, China
- *2022.07 - 2023.01* &ensp; Research Intern, [Zhejiang Lab](https://en.zhejianglab.com/), Hangzhou, China
- *2021.03 - 2021.08* &ensp; Research Assistant, [SIAT](https://english.siat.ac.cn/), Shenzhen, China
- *2019.08 - 2020.01* &ensp; Entrepreneurial Intern, [XbotPark](http://www.xbotpark.com/?lang=en), Dongguan, China
<div class='exp-box'> <div class='exp-box-image'><div><img src='images/logo_YouTu.png' alt="sym" width="100%"></div></div>
<div class='exp-box-text' markdown="1">

[Tencent YouTu Lab](https://open.youtu.qq.com/), Shenzhen, China

**Research Intern** @ FuXi Research Center

*2023.04 - now*

</div>
</div>

---

<div class='exp-box'><div class='exp-box-image'><div><img src='images/logo_ZJLab.png' alt="sym" width="100%"></div></div>
<div class='exp-box-text' markdown="1">

[Zhejiang Lab](https://en.zhejianglab.com/), Hangzhou, China

**Research Intern** @ Research Institute of Intelligent Computing

*2022.07 - 2023.01*

</div>
</div>

---

<div class='exp-box'><div class='exp-box-image'><div><img src='images/logo_SIAT_CAS.png' alt="sym" width="100%"></div></div>
<div class='exp-box-text' markdown="1">

[SIAT, CAS](https://english.siat.ac.cn/), Shenzhen, China

**Research Assistant** @ CV2R-Lab

*2021.03 - 2021.08*

</div>
</div>
   -->
# 🏅 Selected Awards
- *2020* &ensp; Second Prize of SZTU Freshman Scholarship (6000 CNY)
- *2022* &ensp; China Undergraduate Mathematical Contest in Modeling, National Second Prize (top 2%), 2022
- *2023* &ensp; Dahua Outstanding Scholarship (4000 CNY)
- *2023* &ensp; OpenMMLab MMSTAR I
