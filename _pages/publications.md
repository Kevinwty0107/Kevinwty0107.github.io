---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% if site.author.googlescholar %}
  <div class="wordwrap">You can also find my articles on <a href="{{site.author.googlescholar}}">my Google Scholar profile</a>.</div>
{% endif %}

### Machine Learning for Database and Storage, Indexing

[1]. Taiyi Wang, Liang Liang, Guang Yang, Thomas Heinis and Eiko Yoneki. “A New Paradigm in Tuning Learned Indexes: A Reinforcement Learning-Enhanced Approach”, the International Conference on Management of Data (SIGMOD 2025)

[2]. Taiyi Wang, Zakir Singh, Eiko Yoneki. "AutoIndexer: A Reinforcement Learning-Enhanced Index Advisor Towards Scaling Workloads", under review

[3]. Taiyi Wang, Eiko Yoneki. “IA2: Leveraging Instance-Aware Index Advisor with Reinforcement Learning for Diverse Workloads”, the 4th Workshop on Machine Learning and Systems of EuroSys, 2024 (EuroMLSys’24)

[4]. Taiyi Wang, Eiko Yoneki. “Enhancing Generalization through Task Vector Fusion in Deep Reinforcement Learning for Database Optimization”, EuroSys, 2024 (Poster)

[5]. George-Octavian Bărbulescu, Taiyi Wang, Zak Singh and Eiko Yoneki. “Learned Graph Rewriting with Equality Saturation: A New Paradigm in Relational Query Rewrite and Beyond”, under review

[6]. Ali Hadian, Behzad Ghaffari, Taiyi Wang and Thomas Heinis. “COAX: Correlation-Aware Indexing on Multidimensional Data with Soft Functional Dependencies", DBML workshop of the 39th IEEE International Conference on Data Engineering (DBML@ICDE), 2023

### Reinforcement Learning, RL X LLM

[1]. Taiyi Wang, Zhihao Wu, Jianehng Liu, et al. “DistRL: An Asynchronous Distributed Reinforcement Learning Framework for On-Device Control Agents”, the Thirteenth International Conference on Learning Representations (ICLR 2025).

[2]. Taiyi Wang, Jianheng Liu, Bryan Lee, Zhihao Wu, Yu Wu. “OCMDP: Observation-Constrained Markov Decision Process”, under review

[3]. Hao Sun, Taiyi Wang. “Toward Causal-Aware RL: State-Wise Action-Refined Temporal Difference.” NeurIPS 2022 Workshop DeepRL, 2022

[4]. Hao Sun, Ziping Xu, Meng Fang, Zhenghao Peng, Taiyi Wang, Bolei Zhou. “Constrained MDPs can be Solved by Early-Termination with Recurrent Models.” NeurIPS 2022 Workshop FMDM, 2022

[5]. Hao Sun, Ziping Xu, Taiyi Wang, Meng Fang, Bolei Zhou. “Supervised Q-Learning can be a Strong Baseline for Continuous Control.” NeurIPS 2022 Workshop FMDM, 2022

[6]. Taiyi Wang, Jiahao Shi. "Solving Maximal Stable Set problem via Deep Reinforcement Learning." International Conference on Communication Technology, Computational Engineering and Artificial Intelligence (ICAART), 2020

### MLSys, LLM training, and serving

[1]. Youhe Jiang(\*), Fangcheng Fu(\*), Taiyi Wang(\*), Eiko Yoneki. "LiveServe: Efficient LLM Serving via Workload-aware Scheduling and Workload-adaptive Switching", under review

[2]. Youhe Jiang, Fangcheng Fu, Xiaozhe Yao, Taiyi Wang, Bin CUI, Ana Klimovic, Eiko Yoneki. "ThunderServe: High-performance and Cost-efficient LLM Serving in Cloud Environments", under review

### Others

[1]. Wenxun Li(\*), Taiyi Wang(\*) Eiko Yoneki. “HiBO: Hierarchical Bayesian Optimization via Adaptive Search Space Partitioning”, under review

[2]. Wang, Taiyi, Yajun Fang, and Berthold KP Horn. "Why do we need bilateral control?-in view of energy consumption." 2018 4th International Conference on Universal Village (UV). IEEE, 2018.

[3]. Wang, Taiyi, Fu, Zuntao. "Regional Studies on low-frequency variations in DTR." Graduation thesis, Department of Atmospheric and Oceanic Sciences, School of Physics, Peking University, 2019



{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
