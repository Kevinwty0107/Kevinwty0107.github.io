---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

[1]. Taiyi Wang, Zhihao Wu, Jianehng Liu, et al. “DistRL: An Asynchronous Distributed Reinforcement Learning Framework for On-Device Control Agents.” NeurIPS 2024 Workshop on Fine-Tuning in Modern Machine Learning: Principles and Scalability.

[2]. Taiyi Wang, Jianheng Liu, Bryan Lee, Zhihao Wu, Yu Wu. “OCMDP: Observation-Constrained Markov Decision Process”, under review

[3]. Taiyi Wang, Wenxuan Li, Eiko Yoneki. “HiBO: Hierarchical Bayesian Optimization via Adaptive Search Space Partitioning”, under review

[4]. Taiyi Wang, Eiko Yoneki. “IA2: Leveraging Instance-Aware Index Advisor with Reinforcement Learning for Diverse Workloads”, the 4th Workshop on Machine Learning and Systems of EuroSys, 2024 (EuroMLSys’24)

[5]. Taiyi Wang, Eiko Yoneki. “Enhancing Generalization through Task Vector Fusion in Deep Reinforcement Learning for Database Optimization”, EuroSys, 2024 (Poster)

[6]. Taiyi Wang, George-Octavian Bărbulescu, Zak Singh and Eiko Yoneki. “Learned Graph Rewriting with Equality Saturation: A New Paradigm in Relational Query Rewrite and Beyond”, Under Review

[7]. Taiyi Wang, Guang Yang, Liang Liang, Thomas Heinis and Eiko Yoneki. “LITune: Tuning Learned Index Using Deep Reinforcement Learning”, Under Review

[8]. Ali Hadian, Behzad Ghaffari, Taiyi Wang and Thomas Heinis. “COAX: Correlation-Aware Indexing on Multidimensional Data with Soft Functional Dependencies", DBML workshop of the 39th IEEE International Conference on Data Engineering (ICDE), 2023

[9]. Hao Sun, Taiyi Wang. “Toward Causal-Aware RL: State-Wise Action-Refined Temporal Difference.” NeurIPS 2022 Workshop DeepRL, 2022

[10]. Hao Sun, Ziping Xu, Meng Fang, Zhenghao Peng, Taiyi Wang, Bolei Zhou. “Constrained MDPs can be Solved by Early-Termination with Recurrent Models.” NeurIPS 2022 Workshop FMDM, 2022

[11]. Hao Sun, Ziping Xu, Taiyi Wang, Meng Fang, Bolei Zhou. “Supervised Q-Learning can be a Strong Baseline for Continuous Control.” NeurIPS 2022 Workshop FMDM, 2022

[12]. Wang, Taiyi, Shi, Jiahao, "Solving Maximal Stable Set problem via Deep Reinforcement Learning." International Conference on Communication Technology, Computational Engineering and Artificial Intelligence (ICAART), 2020

[13]. Wang, Taiyi, Yajun Fang, and Berthold KP Horn. "Why do we need bilateral control?-in view of energy consumption." 2018 4th International Conference on Universal Village (UV). IEEE, 2018.

[14]. Wang, Taiyi, Fu, Zuntao. "Regional Studies on low-frequency variations in DTR." Graduation thesis, Department of Atmospheric and Oceanic Sciences, School of Physics, Peking University, 2019

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
