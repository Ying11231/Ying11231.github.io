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

I am currently a fourth-year undergraduate student at [Shenzhen Technology University](https://english.sztu.edu.cn/) <img src='images/logo_SZTU.png' style='width: 1.1em;'>, and previously as a visiting student doing my research at [Shenzhen Institute of Advanced Technology (SIAT)](https://english.siat.ac.cn/) <img src='images/logo_SIAT.webp' style='width: 1.1em;'>, [Chinese Academy of Sciences (CAS)](https://english.cas.cn/).

My research interest mainly includes machine learning and computer vision. Recently, I focus on Emotion Recognition using multimodal features and its applications for various fields, aiming to understand human feelings.

> 📢📢📢 <font color=red>I am looking for a Ph.D. position (2024 Fall).</font> If you would like to discuss potential opportunities or learn more about my qualifications, please feel free to [contact me](mailto:lin.yuxiang.contact@gmail.com). 😊


# 🔥 News
- *2023.07*: One paper is accepted by ACM MM Grand Challenge 2023! 🎉
- *2023.07*: We win the second prize in MER-SEMI, Multimodal Emotion Recognition, ACM MM 2023 Grand Challenge! 🎉
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

## 🔎 Other

- [DPPMask: Masked Image Modeling with Determinantal Point Processes](https://arxiv.org/abs/2303.12736)

  Junde Xu, Zikai Lin, **Donghao Zhou**, Yaodong Yang, Xiangyun Liao, Bian Wu, Guangyong Chen, Pheng-Ann Heng

  arXiv Preprint 2023 (Under Review) \| [[Paper]](https://arxiv.org/pdf/2303.12736.pdf)

- [IFAST: Weakly Supervised Interpretable Face Anti-spoofing from Single-shot Binocular NIR Images](https://correr-zhou.github.io/)

  Jiancheng Huang\*, **Donghao Zhou\***, Shifeng Huang (\* indicates equal contribution)

  IEEE Transactions on Information Forensics and Security (TIFS) 2022 (Major Revision)
<!-- - [Deep Learning in Cell Image Analysis](https://downloads.spj.sciencemag.org/icomputing/2022/9861263.pdf), Junde Xu, **Donghao Zhou (Co-first Author)**, Danruo Deng, Jingpeng Li, Cheng Chen, Xiangyun Liao, Guangyong Chen, Pheng-Ann Heng, Intelligent Computing, 2022 -->


# 👨‍💻 Experience
<!-- - *2023.04 - now* &ensp; Research Intern, [Tencent YouTu Lab](https://open.youtu.qq.com/), Shenzhen, China
- *2022.07 - 2023.01* &ensp; Research Intern, [Zhejiang Lab](https://en.zhejianglab.com/), Hangzhou, China
- *2021.03 - 2021.08* &ensp; Research Assistant, [SIAT](https://english.siat.ac.cn/), Shenzhen, China
- *2019.08 - 2020.01* &ensp; Entrepreneurial Intern, [XbotPark](http://www.xbotpark.com/?lang=en), Dongguan, China -->
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

# 🏅 Selected Awards
- *2021 - 2023* &ensp; UCAS Postgraduate Fellowship (Full Tuition Waiver & 8,000 CNY p.a.)
- *2021.06* &ensp; Outstanding Graduate (Top 2.5%)
- *2021.06* &ensp; Excellent Graduation Thesis & Graduation Thesis Innovation Prize
- *2021.04* &ensp; Top 10 Student Innovation Figure (Bonus: 10,000 CNY)
- *2020.09* &ensp; China National Scholarship (Top 0.3%)
- *2018 - 2020* &ensp; First-Class Excellent Student Scholarships (Three Times)
- *2019.05* &ensp; [Asia-Pacific Robot Contest (ROBOCON)](https://en.wikipedia.org/wiki/ABU_Robocon), China Regional Competition, Second Prize (Leading a team of 30+ undergradutes)
- *2018.09* &ensp; Guangdong University Electronic Design Competition, Second Prize

# 💬 Invited Talks
- *2023.06* &ensp; Subcellular Structure Prediction: Revealing Fluorescent Images with Deep Learning, Topic Talk, held by [TechBeat](https://www.techbeat.net/) \| [[News]](https://mp.weixin.qq.com/s/uxUsJiS1m0VwnEeBb3A6cg) [[Video]](https://www.techbeat.net/talk-info?id=783)
- *2023.03* &ensp; Subcellular Structure Prediction from Multiple Partially Labeled Datasets, Internal Youth Forum, held by [Zhejiang Lab](https://en.zhejianglab.com/) \| [[Poster]](images\talk_zjlab_repmode.png)
- *2022.12* &ensp; Single Positive Multi-Label Learning, Youth Ph.D. Talk, held by [ITIC](https://www.itic-sci.com/) and [AI TIME](http://www.aitime.cn/) \| [[News]](https://mp.weixin.qq.com/s/l0gM0sUOR5H0DSP81_GKCQ)
- *2022.12* &ensp; Learning a Multi-Label Classifier from a Single-Label Dataset, Internal Youth Forum, held by [Zhejiang Lab](https://en.zhejianglab.com/) \| [[Poster]](images\talk_zjlab_acktheunknown.png)
<!-- - *2022.08* &ensp; Accepted Paper Sharing, ECCV 2022 China Pre-conference, held by [CSIG](http://en.csig.org.cn/) and [BAAI](https://www.baai.ac.cn/english.html) -->
