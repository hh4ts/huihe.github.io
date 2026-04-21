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

Greetings! I am currently a Postdoc at the Institute of Data Science, [National University of Singapore](https://www.nus.edu.sg/), working with [Prof. See-Kiong Ng](https://scholar.google.com/citations?user=_wsommYAAAAJ). Before that, I received my PhD degree at [Fuzhou University](https://ccds.fzu.edu.cn/), supervised by [Prof. Wenzhong Guo](https://ccds.fzu.edu.cn/info/1202/4993.htm) and [Prof. Shiping Wang](https://ccds.fzu.edu.cn/info/1202/8958.htm). From Oct 2021 to Oct 2022, I am a visiting student in the School of Data Science, Chinese University of Hong Kong (Shenzhen), China, supervised by [Prof. Jicong Fan](https://jicongfan.github.io/). From Jan 2023 to June 2023, I am a visiting student in the Cooperative AI Lab, King's College London, UK, supervised by [Prof. Yali Du](https://yalidu.github.io/). My research interests include anomaly detection, deep clustering, graph neural networks, and generative models <a href='https://scholar.google.com/citations?user=g9TVoA0AAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fjinyucai95%2Fjinyucai95.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>. My studies have led to over 20 scientific publications on top-tier conferences and journals, including IEEE TPAMI/TMM, ICML, NeurIPS, ICLR, CVPR, AAAI, IJCAI, ACM MM, PR, etc. 

# 🔥 News
- *2026.01*: &nbsp;🎉🎉 One paper has been accepted by ICLR'26! Congrats to Yunhe.
- *2026.01*: &nbsp;🎉🎉 One paper has been accepted by WWW'26 (CCF-A)! Congrats to Wei Guan.
- *2025.12*: &nbsp;🎉🎉 One paper regarding the exploration of MoE in graph anomaly detection has been accepted by TPAMI (CCF-A)! Many thanks to Yunhe and all the collaborators.
- *2025.11*: &nbsp;🎉🎉 One paper has been accepted by AAAI'26 (CCF-A)! Congrats to Zhihao Wu.
- *2025.09*: &nbsp;🎉🎉 Two papers have been accepted by NeurIPS'25 (CCF-A)! One of them has been selected as a **Spotlight** paper. Congratulations to Zhihao Wu, Yuan Xie, and all the collaborators.
- *2025.08*: &nbsp;🎉🎉 One paper has been accepted by Pattern Recognition (SCI Q1, CCF-B)! Many thanks to my collaborators.
- *2025.05*: &nbsp;🎉🎉 Two papers have been accepted by ICML'25 (CCF-A)! One of them has been selected as a **Spotlight** paper (**top 2.6%** of all submissions). Many thanks to Yunhe and all the collaborators.
- *2025.01*: &nbsp;🎉🎉 I am honored to receive the **Best Research Staff Award** from the Institute of Data Science (IDS), NUS.
- *2024.12*: &nbsp;🎉🎉 One paper has been accepted by AAAI'25 (CCF-A) as an **Oral** paper! Congrats to Yunhe.
- *2024.07*: &nbsp;🎉🎉 One paper regarding federated graph anomaly detection has been accepted by ACM MM'24 (CCF-A)! Many thanks to Yunhe and all the collaborators.
- *2024.04*: &nbsp;🎉🎉 Three papers have been accepted by IJCAI'24 (CCF-A)! Many thanks to my collaborators.
- *2024.02*: &nbsp;🎉🎉 One paper has been accepted by TMM (SCI Q1)! Many thanks to my collaborators.
- *2024.01*: &nbsp;🎉🎉 One paper has been accepted by ICLR'24 (Spotlight)! Congrats to Yunhe and all the collaborators.

# 💼 Work Experience
- *2023.08 - Now*, Postdoc, Institute of Data Science, National University of Singapore, Singapore.

# 🎓 Educations
- *2018.09 - 2023.06*, Ph.D., College of Computer and Data Science, Fuzhou University, China.
- *2023.01 - 2023.06*, Visiting Ph.D. Student, Cooperative AI Lab, King's College London, UK.
- *2021.10 - 2022.10*, Visiting Ph.D. Student, School of Data Science, Chinese University of HongKong (Shenzhen), China.
- *2014.09 - 2018.06*, B.E., College of Mathematics and Computer Science, Fuzhou University, China.

# 📝 Academic Service
- **Reviewers**
  - IEEE Transactions on Pattern Analysis and Machine Intelligence (IEEE TPAMI)
  - IEEE Transactions on Image Processing (IEEE TIP)
  - IEEE Transactions on Knowledge and Data Engineering (IEEE TKDE)
  - IEEE Transactions on Services Computing (IEEE TSC)
  - IEEE Transactions on Neural Networks and Learning Systems (IEEE TNNLS)
  - IEEE Transactions on Multimedia (IEEE TMM)
  - IEEE Transactions on Circuits and Systems for Video Technology (IEEE TCSVT)
  - Pattern Recognition (PR)
  - Engineering Applications of Artificial Intelligence (EAAI)
- **PC Members**
  - NeurIPS 2023/2024/2025
  - ICML 2024/2025/2026
  - ICLR 2024/2025/2026
  - CVPR 2023/2024/2025/2026
  - ICCV 2023/2025
  - ECCV 2024/2026
  - KDD 2024/2025/2026
  - IJCAI 2024/2025/2026
  - AAAI 2025/2026
  - ACM MM 2024/2025

# 📖 Selected Publications 
<p style="font-size:0.9em; color:#666; margin-top:-10px; margin-bottom:5px;">
<sup>†</sup> indicates co-first author; * indicates corresponding author. <a href="https://scholar.google.com/citations?user=g9TVoA0AAAAJ" target="_blank">Full List</a>
</p>

{% include_relative publication/AnomalyDetection.md %}

{% include_relative publication/DeepClustering.md %}

{% include_relative publication/others.md %}

# 📎 Links
- [FZUThesis](https://github.com/chenzl23/FZUThesis): Latex Template for FZU Thesis.
- [CCF Recommendation List](https://ccf.atom.im/)
- [CCF Recommendation Conference Deadlines](https://ccfddl.github.io/)
- [Fabulous](https://github.com/Creator-SN/Fabulous): an integrated management system for papers and literature, developed by Aleversn.
- [Matrix Calculus](https://www.matrixcalculus.org/?tdsourcetag=s_pctim_aiomsg)
- [Latex Table Convert](https://tableconvert.com/)
- [Latex Table Generator](https://www.tablesgenerator.com/)
- [Excel2latex](https://ctan.org/pkg/excel2latex?lang=en): a package for transforming excel tables into latex codes.

<script type='text/javascript' id='clustrmaps' src='//cdn.clustrmaps.com/map_v2.js?cl=ffffff&w=250&t=tt&d=rlVnmh50IOmOPOW6tIm2OnOeG7JG5s5-zdf0AOD1z7M&co=2d78ad&ct=ffffff&cmo=3acc3a&cmn=ff5353'></script>
