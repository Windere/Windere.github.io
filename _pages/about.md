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

# About me
I am a PH.D candidate at the [College of Computer Science and Technology](http://www.en.cs.zju.edu.cn/), [CCNT Lab](http://ccnt.zju.edu.cn/), Zhejiang University, supervised by Prof. Huajin Tang.
My research interest includes spiking neural network, sparse representation, and efficient neuromorphic computing. Additionally, I am interested in bio-based and bio-inspired reinforcement learning. Please contact me at zi_ming_wang@zju.edu.cn or zi_ming_wang@outlook.com if you are interested in my research.
<!-- I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
- 2024.07: &nbsp;🎉🎉 One paper is accepted by European Conference on Computer Vision (ECCV 2024).
- 2024.06: &nbsp;🎉🎉 Built this personal page, thanks to the [page template](https://github.com/RayeRen/acad-homepage.github.io) from Ren Yi.
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📝 Publications 

<!-- <div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICML 2023</div><img src='images/arch_v8.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1"> -->

- **Ziming Wang**, Ziling Wang, Huaning Li, Lang Qin, Runhao Jiang, De Ma, Huajin Tang. [EAS-SNN: End-to-End Adaptive Sampling and Representation for Event-based Detection with Recurrent
 Spiking Neural Networks](https://arxiv.org/abs/2403.12574), ECCV, 2024.

 - **Ziming Wang**, Runhao Jiang, Shuang Lian, Rui Yan, Huajin Tang. [Adaptive Smoothing Gradient Learning for Spiking Neural Networks](https://proceedings.mlr.press/v202/wang23j/wang23j.pdf), International Conference on Machine Learning (ICML), 2023

- **Ziming Wang**, Yuhao Zhang, Shuang Lian, Xiaoxin Cui, Rui Yan, Huajin Tang. [Toward High-accuracy and Low-latency Spiking Neural Networks with Dual Phase Optimization](https://ieeexplore.ieee.org/abstract/document/10361844/), IEEE Transactions on Neural Networks and Learning Systems (TNNLS), 2023.


- Lang Qin$^\*$, **Ziming Wang$^\*$** , Rui Yan, and Huajin Tang. [Attention-Based Deep Spiking Neural Networks for Temporal Credit Assignment Problems](https://scholar.google.com/scholar_url?url=https://ieeexplore.ieee.org/abstract/document/10038509/&hl=zh-CN&sa=T&oi=gsb&ct=res&cd=0&d=9839646359860287259&ei=4CtxZvjMDNiu6rQPotCy2AQ&scisig=AFWwaeZnGUw-evcTI5ecj7iP5uBg), IEEE Transactions on Neural Networks and Learning Systems (TNNLS), 2023. (* denotes co-first author)

- Shuang Lian, Jiangrong Shen, Qianhui Liu, **Ziming Wang**, Rui Yan, Huajin Tang. [Learnable Surrogate Gradient for Direct Training Spiking Neural Networks](https://www.ijcai.org/proceedings/2023/0335.pdf),  International Joint Conference on Artificial Intelligence (IJCAI), 2023.

- Mengwen, Yuan, Chengjun Zhang, **Ziming Wang**, Huixiang Liu, Gang Pan, Huajin Tang. [Trainable Spiking-YOLO for low-latency and high-performance object detection](https://www.sciencedirect.com/science/article/abs/pii/S0893608023007530). Neural Networks, 2024.




<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
=======
Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. Suspendisse condimentum, libero vel tempus mattis, risus risus vulputate libero, elementum fermentum mi neque vel nisl. Maecenas facilisis maximus dignissim. Curabitur mattis vulputate dui, tincidunt varius libero luctus eu. Mauris mauris nulla, scelerisque eget massa id, tincidunt congue felis. Sed convallis tempor ipsum rhoncus viverra. Pellentesque nulla orci, accumsan volutpat fringilla vitae, maximus sit amet tortor. Aliquam ultricies odio ut volutpat scelerisque. Donec nisl nisl, porttitor vitae pharetra quis, fringilla sed mi. Fusce pretium dolor ut aliquam consequat. Cras volutpat, tellus accumsan mattis molestie, nisl lacus tempus massa, nec malesuada tortor leo vel quam. Aliquam vel ex consectetur, vehicula leo nec, efficitur eros. Donec convallis non urna quis feugiat.

My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).


# 🔥 News
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 

# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2016</div><img src='images/500x300.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Deep Residual Learning for Image Recognition](https://openaccess.thecvf.com/content_cvpr_2016/papers/He_Deep_Residual_Learning_CVPR_2016_paper.pdf)

**Kaiming He**, Xiangyu Zhang, Shaoqing Ren, Jian Sun

[**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
>>>>>>> 2cc1577eeaf2f74dede6d016a70722dbd409ea2f
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
</div>
</div>

<<<<<<< HEAD
- [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

# 🎖 Honors and Awards
- [ICML 2022 Outstanding Reviewer](https://icml.cc/Conferences/2022/Reviewers) 
- Graduate of Merit/Triple A Performance, Zhejiang University
- Outstanding Graduate Student of CCNT, Zhejiang University
- [Second place in the Intel Neuromorphic Deep Noise Suppression Challenge](https://github.com/IntelLabs/IntelNeuromorphicDNSChallenge) 
-  First Prize in the Ninth Chinese Mathematics Competitions (Sichuan Province)
- Silver Award in the Eleventh ACM International Collegiate Programming Contest (Sichuan Province)

# 💬 Academic Service
 Reviewer for: 
- Neural Networks, NN
- International Conference on Machine Learning, ICML
- International Conference on Learning Representations, ICLR
- IEEE Transactions on Cognitive and Developmental Systems, TCDS
- IEEE Transactions on Neural Networks and Learning Systems, TNNLS
- Association for the Advancement of Artificial Intelligence, AAAI
- IEEE Transactions on Emerging Topics in Computational Intelligence, TETCI

<!-- ICLR, ICML, AAAI, TNNLS, Neural Networks, TCDS, TETCI -->

# 📖 Educations
- *2020.06 - 2024.6 (now)*, PhD Candidate, College of Computer Science, Zhejiang University, Hangzhou.
- *2016.09 - 2020.06*, Undergraduate, the Everest Class of Computer Science, Sichuan Univeristy, Chengdu.


<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/) -->

# 💻 Internships
- *2022.07 – 2024.06* Liangzhu Laboratory, Hangzhou, PRC. Research Intern（Brain-inspired Perception）
- *2020.06 – 2020.09* Zhejiang Laboratory, Hangzhou, PRC. Research Intern（Neuromorphic Algorithm）
