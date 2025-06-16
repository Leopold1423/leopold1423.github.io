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

I am currently a PhD student in the Intelligent and Distributed Computing ([IDC](https://idc.hust.edu.cn/index.htm)) Laboratory of Huazhong University of Science and Technology (HUST), 
under the supervision of Prof. [Yuhua Li](https://idc.hust.edu.cn/yhli/index.html) and Prof. [Ruixuan Li](https://idc.hust.edu.cn/rxli/index.htm). Before joining HUST, I got my bachelor’s degree in Beijing University of Posts and Telecommunications (BUPT).

My research interest includes Model Compression and Acceleration, and their applications in Recommender Systems, Distributed Training, and Large Language Models. Recently, I have been working on Parameter-Efficient Fine-Tuning and Inference Acceleration for LLMs.

# 🔥 News
- *2025.05*: &nbsp;🎉🎉 One paper was accepted by KDD 2025 ADS Track.
- *2025.05*: &nbsp;🎉🎉 Two papers were accepted by ICML 2025.
- *2024.07*: &nbsp;🎉🎉 One paper was accepted by MM 2024.
- *2024.05*: &nbsp;🎉🎉 One paper was accepted by ICML 2024. 

# 📝 Publications 
<!-- - Xing Tang , Chaohua Yang, Yuwen Fu, Dongyang Ao, **Shiwei Li**<sup>†</sup>, Fuyuan Lyu, Dugang Liu, and Xiuqiang He<sup>†</sup>. <u>Retrieval Augmented Cross-Domain Life Long Behavior Modeling for Enhancing Click-through Rate Prediction</u>. The 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining (**KDD**), August 3-7, 2025. (**CCF-A**) [[paper]](https://arxiv.org/abs) -->
- Xing Tang , Chaohua Yang, Yuwen Fu, Dongyang Ao, **Shiwei Li**, Fuyuan Lyu, Dugang Liu, and Xiuqiang He. <u>Retrieval Augmented Cross-Domain Life Long Behavior Modeling for Enhancing Click-through Rate Prediction</u>. The 31st ACM SIGKDD Conference on Knowledge Discovery and Data Mining (**KDD**), August 3-7, 2025. (**CCF-A**) [[paper]](https://arxiv.org/abs)
- **Shiwei Li**<sup>\*</sup>, Xiandi Luo<sup>\*</sup>, Haozhao Wang<sup>†</sup>, Xing Tang<sup>†</sup>, Hao Chen, Weihong Luo, Yuhua Li, Xiuqiang He, Ruixuan Li<sup>†</sup>. <u>Beyond Zero Initialization: Investigating the Impact of Non-Zero Initialization on LoRA Fine-Tuning Dynamics.</u> The 42nd International Conference on Machine Learning (**ICML**), Vancouver, Canada, July 13-19, 2025. (**CCF-A**) [[paper]](https://arxiv.org/abs/2505.23194) [[code]](https://github.com/Leopold1423/non_zero_lora-icml25)
- **Shiwei Li**<sup>\*</sup>, Xiandi Luo<sup>\*</sup>, Haozhao Wang, Xing Tang, Shijie Xu, Weihong Luo, Yuhua Li, Xiuqiang He, Ruixuan Li<sup>†</sup>. <u>The Panaceas for Improving Low-Rank Decomposition in Communication-Efficient Federated Learning.</u> The 42nd International Conference on Machine Learning (**ICML**), Vancouver, Canada, July 13-19, 2025. (**CCF-A**) [[paper]](https://arxiv.org/abs/2505.23176) [[code]](https://github.com/Leopold1423/fedmud-icml25)

- **Shiwei Li**, Yingyi Cheng, Haozhao Wang<sup>†</sup>, Xing Tang, Shijie Xu, Weihong Luo, Yuhua Li, Dugang Liu, Xiuqiang He, Ruixuan Li. <u>Masked Random Noise for Communication-Efficient Federated Learning.</u> The 32nd ACM International Conference on Multimedia (**ACM MM**), Melbourne, Australia, October 28 - November 1, 2024. (**CCF-A**) [[paper]](https://arxiv.org/abs/2408.03220) [[code]](https://github.com/Leopold1423/fedmrn-mm24)
- **Shiwei Li**, Wenchao Xu, Haozhao Wang<sup>†</sup>, Xing Tang<sup>†</sup>, Yining Qi, Shijie Xu, Weihong Luo, Yuhua Li, Xiuqiang He, Ruixuan Li<sup>†</sup>. <u>FedBAT: Communication-Efficient Federated Learning via Learnable Binarization.</u> The 41st International Conference on Machine Learning (**ICML**), Vienna, Austria, July 21-27, 2024. (**CCF-A**) [[paper]](https://arxiv.org/abs/2408.03215) [[code]](https://github.com/Leopold1423/fedbat-icml24)

- **Shiwei Li**<sup>\*</sup>, Huifeng Guo<sup>\*</sup>, Xing Tang, Ruiming Tang, Lu Hou, Ruixuan Li<sup>†</sup>, Rui Zhang<sup>†</sup>. <u>Embedding Compression in Recommender Systems: A Survey.</u> **ACM Computing Surveys**, 2024, 56(5): 1-21. (**Q1, IF=23.8**) [[paper]](https://arxiv.org/abs/2408.02304) 
- **Shiwei Li**, Huifeng Guo, Lu Hou, Wei Zhang, Xing Tang, Ruiming Tang, Rui Zhang<sup>†</sup>, Ruixuan Li<sup>†</sup>. <u>Adaptive Low-Precision Training for Embeddings in Click-Through Rate Prediction.</u> The 37th AAAI Conference on Artificial Intelligence (**AAAI**), Washington, DC, USA, February 7-14, 2023. (**CCF-A**) [[paper]](https://arxiv.org/abs/2212.05735) [[code]](https://github.com/Leopold1423/alpt-aaai23)

# 😊 Preprint 
- **Shiwei Li**, Zhuoqi Hu, Xing Tang, Haozhao Wang, Shijie Xu, Weihong Luo, Yuhua Li, Xiuqiang He, Ruixuan Li<sup>†</sup>. <u>Mixed-Precision Embeddings for Large-Scale Recommendation Models.</u> [[paper]](https://arxiv.org/abs/2409.20305) [[code]](https://github.com/Leopold1423/mpe)

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2021.09 - 2026.06 (expected)*, Ph.D. in Huazhong University of Science and Technology (HUST).
- *2017.09 - 2021.06*, B.S. in Beijing University of Posts and Telecommunications (BUPT). 

# 💻 Internships
- *2023.06 - 2025.06*, [Tencent Financial Technology (FiT)], Shenzhen, China, under the supervision of [Xing Tang](https://xingt-tang.github.io/) and [Xiuqiang He](https://he-xiuqiang.github.io/).
- *2021.10 - 2022.09*, [Huawei Noah's Ark Lab], Shenzhen, China, under the supervision of [Huifeng Guo](https://scholar.google.com/citations?user=jlBcPn8AAAAJ&hl=zh-CN), [Lu Hou](https://houlu369.github.io/), [Ruiming Tang](https://scholar.google.com/citations?user=fUtHww0AAAAJ&hl=zh-CN) and [Rui Zhang](https://www.ruizhang.info/).
  
# 👨‍💻 Service
- Area Chair: KDD 2025
- Reviewer: KDD 2025, NeurIPS 2025, MM 2025, IJCAI 2025, ECAI 2025
