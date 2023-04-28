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

I am currently a second-year M.Sc. student at [University of Chinese Academy of Sciences (UCAS)](https://english.ucas.ac.cn/) <img src='images/logo_UCAS.png' style='width: 1.1em;'> ([learn more about UCAS](https://en.wikipedia.org/wiki/University_of_the_Chinese_Academy_of_Sciences)), and doing my research at [Shenzhen Institute of Advanced Technology (SIAT)](https://english.siat.ac.cn/), [Chinese Academy of Sciences (CAS)](https://english.cas.cn/).

My research interest mainly includes machine learning and computer vision. Recently, I focus on Data-Efficient AI (learning with limited and imperfect data) and its applications for various fields, aiming to promote the efficiency and flexibility of AI algorithms in real world.

> 📢📢📢 <font color=red>I am looking for a Ph.D. position (2024 Fall).</font> If you would like to discuss potential opportunities or learn more about my qualifications, please feel free to [contact me](mailto:dh.zhou@siat.ac.cn). 😊


# 🔥 News
- *2023.04*: I join [Tencent YouTu Lab](https://open.youtu.qq.com/) as a research intern! 🔬
- *2023.03*: Our paper is selected as a CVPR Highlight (Top 2.5% of 9155 submissions)! 🎉
- *2023.02*: One first-author paper is accepted by CVPR 2023! 🎉
- *2022.07*: I join [Zhejiang Lab](https://en.zhejianglab.com/) as a research intern! 🔬
- *2022.07*: One first-author paper is accepted by ECCV 2022! 🎉
- *2021.07*: I get my bachelor’s degree as an outstanding graduate! 👨‍🎓
- *2021.03*: I join [CV2R-Lab @ SIAT](https://english.siat.ac.cn/) as a research assistant and will spend my last undergraduate time here! 🔬
- *2020.10*: I acquire a qualification of postgraduate recommendation, and decide to pursue my master’s degree in UCAS! 👨‍🎓
- *2020.09*: I am awarded a china national scholarship! 🏆
- *2019.05*: We win the second prize of [CN-ROBOCON](https://en.wikipedia.org/wiki/ABU_Robocon) after one-year's preparation. Thanks all my teammates! 🥈


# 📝 Selected Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023 (Highlight)</div><img src='images/repmode.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RepMode: Learning to Re-parameterize Diverse Experts for Subcellular Structure Prediction](https://arxiv.org/pdf/2212.10066.pdf)

**Donghao Zhou**, Chunbin Gu, Junde Xu, Furui Liu, Qiong Wang, Guangyong Chen, Pheng-Ann Heng

**<font color=red>CVPR 2023 (Highlight)</font>** | [[Project]](https://correr-zhou.github.io/RepMode/) [[Paper]](https://arxiv.org/pdf/2212.10066.pdf) [[Code]](https://github.com/Correr-Zhou/RepMode)
- We model fluorescence staining as a 3D dense prediction task termed subcellular structure prediction (SSP).
- We propose Re-parameterizing Mixture-of-Diverse-Experts (RepMode), a network that dynamically organizes its parameters with task-aware priors to handle specified single-label prediction tasks of SSP.
- Experiments show that RepMode can attain SOTA overall performance on twelve prediction tasks and achieve effiecent task-incremental learning.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2022</div><img src='images/acktheunknown.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Acknowledging the Unknown for Multi-Label Learning with Single Positive Labels](https://arxiv.org/pdf/2203.16219.pdf)

**Donghao Zhou**, Pengfei Chen, Qiong Wang, Guangyong Chen, Pheng-Ann Heng

**<font color=red>ECCV 2022</font>** | [[Paper]](https://arxiv.org/pdf/2203.16219.pdf) [[Code]](https://github.com/Correr-Zhou/SPML-AckTheUnknown) [[Poster]](resources/acktheunknown_poster.pdf) [[Slides]](resources/acktheunknown_10min_slides.pdf)
<!-- ![](https://img.shields.io/github/stars/Correr-Zhou/SPML-AckTheUnknown?style=social) -->
- This work focuses on single positive multi-label learning (SPML), an extreme of weakly supervised learning problem.
- We choose to treat all unannotated labels from a novel perspective, and hence propose our entropy-maximization loss (with a special gradient regime) and asymmetric pseudo-labeling (with asymmetric-tolerance strategies).
- Our method achieves SOTA results on all four SPML benchmarks and various analyses are provided to verify its effectiveness and rationality.

</div>
</div>

# 👨‍💻 Research Experience
- *2023.04 - now* &ensp; Research Intern, [Tencent YouTu Lab](https://open.youtu.qq.com/), Shenzhen, China
- *2022.07 - 2023.01* &ensp; Research Intern, [Zhejiang Lab](https://en.zhejianglab.com/), Hangzhou, China
- *2021.03 - 2021.08* &ensp; Research Assistant, [SIAT](https://english.siat.ac.cn/), Shenzhen, China
- *2019.08 - 2020.01* &ensp; Entrepreneurial Intern, [XbotPark](http://www.xbotpark.com/?lang=en), Dongguan, China

# 🏅 Honors and Awards
- *2021 - 2024* &ensp; University of Chinese Academy of Sciences Scholarship (¥10,000 per annum)
- *2021.06* &ensp; Outstanding Graduate (Top 2.5%)
- *2021.06* &ensp; Excellent Graduation Thesis & Graduation Thesis Innovation Prize
- *2021.04* &ensp; Top 10 Campus Innovation People (Bonus: ¥10,000)
- *2020.09* &ensp; China National Scholarship (Top 0.3%)
- *2018 - 2020* &ensp; First-Class Excellence Scholarship (Three times)
- *2019.05* &ensp; [Asia-Pacific Robot Contest (ROBOCON)](https://en.wikipedia.org/wiki/ABU_Robocon), China Regional Competition, Second Prize (As the captain of a team of 30+ undergradutes)
- *2018.09* &ensp; Guangdong University Electronic Design Competition, Second Prize

# 💬 Invited Talks
- *2023.03* &ensp; Subcellular Structure Prediction, Internal Youth Forum, held by [Zhejiang Lab](https://en.zhejianglab.com/)
- *2022.12* &ensp; Single Positive Multi-Label Learning, Youth Ph.D. Talk, held by [ITIC](https://www.itic-sci.com/) and [AI TIME](http://www.aitime.cn/)
- *2022.12* &ensp; Learning a Multi-Label Classifier from a Single-Label Dataset, Internal Youth Forum, held by [Zhejiang Lab](https://en.zhejianglab.com/)
- *2022.08* &ensp; Accepted Paper Sharing, ECCV 2022 China Pre-conference, held by [CSIG](http://en.csig.org.cn/) and [BAAI](https://www.baai.ac.cn/english.html)