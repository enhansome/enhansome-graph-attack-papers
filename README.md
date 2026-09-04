# Awesome Graph Attack and Defense Papers with stars

[![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 502,802 | 🐛 106 | 📅 2026-09-02
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

This repository aims to provide links to works about adversarial attacks and defenses on graph data or GNN (Graph Neural Networks).

<div align=center><img src="https://github.com/DSE-MSU/DeepRobust/blob/master/adversary_examples/graph_attack_example.png" width="500" /></div>

If you find this repo helpful, we would really appreciate it if you could cite our survey.

```
@article{10.1145/3447556.3447566,
author = {Jin, Wei and Li, Yaxing and Xu, Han and Wang, Yiqi and Ji, Shuiwang and Aggarwal, Charu and Tang, Jiliang},
title = {Adversarial Attacks and Defenses on Graphs},
year = {2021},
publisher = {Association for Computing Machinery},
journal = {SIGKDD Explor. Newsl.},
pages = {19–34},
numpages = {16}
}

```

### Contents

* [1. Survey Papers](#1-survey-papers)
* [2. Attack Papers](#2-attack-papers) (classified according to attack goal)
  * [2.1 Targeted Attack](#21-targeted-attack)
  * [2.2 Untargeted Attack](#22-untargeted-attack)
  * [2.3 Attacks on Combinatorial Problems](#23-attacks-on-combinatorial-problems)
* [3. Defense Papers](#3-defense-papers)
* [4. Certified Robustness Papers](#4-certified-robustness-papers)

## 0. Toolbox

Github Repository: **DeepRobust** (<https://github.com/DSE-MSU/DeepRobust> ⭐ 1,086 | 🐛 54 | 🌐 Python | 📅 2025-06-26)

Corresponding paper: **DeepRobust: A PyTorch Library for Adversarial Attacks and Defenses.** [\[paper\]](https://arxiv.org/abs/2005.06149)[\[documentation\]](https://deeprobust.readthedocs.io/en/latest/)

## 1. Survey Papers

1. **Adversarial Attacks and Defenses on Graphs: A Review and Empirical Study.**
   *Wei Jin, Yaxin Li, Han Xu, Yiqi Wang, Shuiwang Ji, Charu C Aggarwal, Jiliang Tang.*  SIGKDD Explorations 2020. [\[paper\]](https://arxiv.org/abs/2003.00653) [\[code\]](https://github.com/DSE-MSU/DeepRobust/) ⭐ 1,086 | 🐛 54 | 🌐 Python | 📅 2025-06-26
2. **A Survey of Adversarial Learning on Graphs.**
   *Liang Chen, Jintang Li, Jiaying Peng, Tao Xie, Zengxu Cao, Kun Xu, Xiangnan He, Zibin Zheng.* arxiv, 2020. [\[paper\]](https://arxiv.org/abs/2003.05730)
3. **Adversarial Attacks and Defenses in Images, Graphs and Text: A Review.**
   *Han Xu, Yao Ma, Haochen Liu, Debayan Deb, Hui Liu, Jiliang Tang, Anil K. Jain.* arxiv, 2019. [\[paper\]](https://arxiv.org/pdf/1909.08072.pdf)
4. **Adversarial Attack and Defense on Graph Data: A Survey.**
   *Lichao Sun, Ji Wang, Philip S. Yu, Bo Li.* arviv 2018. [\[paper\]](https://arxiv.org/pdf/1812.10528.pdf)

## 2. Attack Papers

### 2.1 Targeted Attack

1. **Adversarial Examples on Graph Data: Deep Insights into Attack and Defense.**
   *Huijun Wu, Chen Wang, Yuriy Tyshetskiy, Andrew Docherty, Kai Lu, Liming Zhu.* IJCAI 2019. [\[paper\]](https://arxiv.org/pdf/1903.01610.pdf) [\[code\]](https://github.com/DSE-MSU/DeepRobust) ⭐ 1,086 | 🐛 54 | 🌐 Python | 📅 2025-06-26
2. **Fast Gradient Attack on Network Embedding.**
   *Jinyin Chen, Yangyang Wu, Xuanheng Xu, Yixian Chen, Haibin Zheng, Qi Xuan.* arxiv 2018. [\[paper\]](https://arxiv.org/pdf/1809.02797.pdf) [\[code\]](https://github.com/DSE-MSU/DeepRobust) ⭐ 1,086 | 🐛 54 | 🌐 Python | 📅 2025-06-26
3. **Adversarial Attacks on Neural Networks for Graph Data.**
   *Daniel Zügner, Amir Akbarnejad, Stephan Günnemann.*  KDD 2018. [\[paper\]](https://arxiv.org/pdf/1805.07984.pdf) [\[code\]](https://github.com/danielzuegner/nettack) ⭐ 226 | 🐛 0 | 🌐 Python | 📅 2022-05-31
4. **Adversarial Attack on Graph Structured Data.**
   *Hanjun Dai, Hui Li, Tian Tian, Xin Huang, Lin Wang, Jun Zhu, Le Song.* ICML 2018. [\[paper\]](https://arxiv.org/pdf/1806.02371.pdf) [\[code\]](https://github.com/Hanjun-Dai/graph_adversarial_attack) ⭐ 130 | 🐛 9 | 🌐 Python | 📅 2022-07-16
5. **Adversarial Attacks on Node Embeddings via Graph Poisoning.**
   *Aleksandar Bojchevski, Stephan Günnemann.* ICML 2019. [\[paper\]](https://arxiv.org/pdf/1809.01093.pdf) [\[code\]](https://github.com/abojchevski/node_embedding_attack) ⭐ 59 | 🐛 2 | 🌐 Python | 📅 2019-12-23
6. **A Restricted Black-box Adversarial Framework Towards Attacking Graph Embedding Models.**
   *Heng Chang, Yu Rong, Tingyang Xu, Wenbing Huang, Honglei Zhang, Peng Cui, Wenwu Zhu, Junzhou Huang.* AAAI 2020. [\[paper\]](https://arxiv.org/pdf/1908.01297.pdf) [\[code\]](https://github.com/SwiftieH/GFAttack) ⭐ 35 | 🐛 0 | 🌐 Python | 📅 2021-05-26
7. **Robustness of Graph Neural Networks at Scale.** NeurIPS 2021. [\[paper\]](https://www.in.tum.de/daml/robustness-of-gnns-at-scale/) [\[code\]](https://github.com/sigeisler/robustness_of_gnns_at_scale) ⭐ 30 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2023-07-25
8. **Are Defenses for Graph Neural Networks Robust?** NeurIPS 2022. [\[paper\]](https://www.cs.cit.tum.de/daml/are-gnn-defenses-robust/) [\[code\]](http://github.com/LoadingByte/are-gnn-defenses-robust) ⭐ 29 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2022-11-17
9. **Learning to Deceive Knowledge Graph Augmented Models via Targeted Perturbation.** ICLR 2021. [\[paper\]](https://arxiv.org/abs/2010.12872)[\[code\]](https://github.com/INK-USC/deceive-KG-models) ⭐ 5 | 🐛 1 | 🌐 Python | 📅 2021-05-03
10. **Transferable Graph Backdoor Attack.**  RAID 2022. [\[paper\]](https://arxiv.org/abs/2207.00425)
11. **Adversarial Attacks on Deep Graph Matching.** NeurIPS 2020. [\[paper\]](https://papers.nips.cc/paper/2020/file/ef126722e64e98d1c33933783e52eafc-Paper.pdf)
12. **Adversarial Attack on Large Scale Graph.** arxiv 2020. [\[paper\]](https://arxiv.org/pdf/2009.03488.pdf)
13. **Efficient Evasion Attacks to Graph Neural Networks via Influence Function.** arxiv 2020. [\[paper\]](https://arxiv.org/abs/2009.00203)
14. **Graph Backdoor.**
    *Zhaohan Xi, Ren Pang, Shouling Ji, Ting Wang.* arxiv 2020. [\[paper\]](https://arxiv.org/abs/2006.11890)
15. **Attacking Black-box Recommendations via Copying Cross-domain User Profiles.**
    *Wenqi Fan, Tyler Derr, Xiangyu Zhao, Yao Ma, Hui Liu, Jianping Wang, Jiliang Tang, Qing Li.* arxiv 2020. [\[paper\]](https://arxiv.org/abs/2005.08147)
16. **Scalable Attack on Graph Data by Injecting Vicious Nodes.**
    *Jihong Wang, Minnan Luo, Fnu Suya, Jundong Li, Zijiang Yang, Qinghua Zheng.* arxiv 2020. [\[paper\]](https://arxiv.org/pdf/2004.14734.pdf)
17. **Adversarial Attacks to Scale-Free Networks: Testing the Robustness of Physical Criteria.**
    *Jason Gaitonde, Jon Kleinberg, Eva Tardos.* arxiv 2020. [\[paper\]](https://arxiv.org/pdf/2002.01249.pdf)
18. **MGA: Momentum Gradient Attack on Network.**
    *Jinyin Chen, Yixian Chen, Haibin Zheng, Shijing Shen, Shanqing Yu, Dan Zhang, Qi Xuan.* arxiv 2020. [\[paper\]](https://arxiv.org/pdf/2002.11320.pdf)
19. **Graph Universal Adversarial Attacks: A Few Bad Actors Ruin Graph Learning Models.**
    *Xiao Zang, Yi Xie, Jie Chen, Bo Yuan.* arxiv, 2020. [\[paper\]](https://arxiv.org/abs/2002.04784)
20. **Time-aware Gradient Attack on Dynamic Network Link Prediction.**
    *Jinyin Chen, Jian Zhang, Zhi Chen, Min Du, Feifei Li, Qi Xuan.* arxiv 2019. [\[paper\]](https://arxiv.org/pdf/1911.10561.pdf)
21. **Multiscale Evolutionary Perturbation Attack on Community Detection.**
    *Jinyin Chen, Yixian Chen, Lihong Chen, Minghao Zhao, and Qi Xuan.* arxiv 2019. [\[paper\]](https://arxiv.org/pdf/1910.09741.pdf)
22. **Data Poisoning Attack against Knowledge Graph Embedding.**
    *Hengtong Zhang, Tianhang Zheng, Jing Gao, Chenglin Miao, Lu Su, Yaliang Li, Kui Ren.* IJCAI 2019. [\[paper\]](https://arxiv.org/pdf/1904.12052.pdf)
23. **Attacking Graph-based Classification via Manipulating the Graph Structure.**
    *Binghui Wang, Neil Zhenqiang Gong.* CCS 2019. [\[paper\]](https://arxiv.org/pdf/1903.00553.pdf)

### 2.2 Untargeted Attack

1. **Adversarial Examples on Graph Data: Deep Insights into Attack and Defense.**
   *Huijun Wu, Chen Wang, Yuriy Tyshetskiy, Andrew Docherty, Kai Lu, Liming Zhu.* IJCAI 2019. [\[paper\]](https://arxiv.org/pdf/1903.01610.pdf) [\[code\]](https://github.com/DSE-MSU/DeepRobust) ⭐ 1,086 | 🐛 54 | 🌐 Python | 📅 2025-06-26
2. **Adversarial Attacks on Graph Neural Networks via Meta Learning.**
   *Daniel Zugner, Stephan Gunnemann.* ICLR 2019. [\[paper\]](https://openreview.net/pdf?id=Bylnx209YX) [\[code\]](https://github.com/danielzuegner/gnn-meta-attack) ⭐ 158 | 🐛 0 | 🌐 Python | 📅 2021-12-09
3. **Topology Attack and Defense for Graph Neural Networks: An Optimization Perspective.**
   *Kaidi Xu, Hongge Chen, Sijia Liu, Pin-Yu Chen, Tsui-Wei Weng, Mingyi Hong, Xue Lin.* IJCAI 2019. [\[paper\]](https://arxiv.org/pdf/1906.04214.pdf) [\[code\]](https://github.com/KaidiXu/GCN_ADV_Train) ⭐ 62 | 🐛 2 | 🌐 Python | 📅 2021-02-26
4. **Adversarial Attacks on Node Embeddings via Graph Poisoning.**
   *Aleksandar Bojchevski, Stephan Günnemann.* ICML 2019. [\[paper\]](https://arxiv.org/pdf/1809.01093.pdf) [\[code\]](https://github.com/abojchevski/node_embedding_attack) ⭐ 59 | 🐛 2 | 🌐 Python | 📅 2019-12-23
5. **Robustness of Graph Neural Networks at Scale.** NeurIPS 2021. [\[paper\]](https://www.in.tum.de/daml/robustness-of-gnns-at-scale/) [\[code\]](https://github.com/sigeisler/robustness_of_gnns_at_scale) ⭐ 30 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2023-07-25
6. **Are Defenses for Graph Neural Networks Robust?** NeurIPS 2022. [\[paper\]](https://www.cs.cit.tum.de/daml/are-gnn-defenses-robust/) [\[code\]](http://github.com/LoadingByte/are-gnn-defenses-robust) ⭐ 29 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2022-11-17
7. **Towards More Practical Adversarial Attacks on Graph Neural Networks.**
   *Jiaqi Ma, Shuangrui Ding, Qiaozhu Mei.*  NeurIPS 2020. [\[paper\]](https://arxiv.org/abs/2006.05057) [\[code\]](https://github.com/Mark12Ding/GNN-Practical-Attack) ⭐ 27 | 🐛 0 | 🌐 Python | 📅 2021-11-13
8. **Attacking Graph Neural Networks at Scale.**
   *Simon Geisler, Daniel Zügner, Aleksandar Bojchevski, Stephan Günnemann.* AAAI workshop 2021. [\[paper\]](https://www.dropbox.com/s/ddrwoswpz3wwx40/Robust_GNNs_at_Scale__AAAI_Workshop_2020_CameraReady.pdf?dl=0)
9. **Backdoor Attacks to Graph Neural Networks.**
   *Zaixi Zhang, Jinyuan Jia, Binghui Wang, Neil Zhenqiang Gong.* arxiv 2020. [paper](https://arxiv.org/abs/2006.11165)
10. **Adversarial Attack on Hierarchical Graph Pooling Neural Networks.**
    *Haoteng Tang, Guixiang Ma, Yurong Chen, Lei Guo, Wei Wang, Bo Zeng, Liang Zhan.* arxiv 2020. [\[paper\]](https://arxiv.org/abs/2005.11560)
11. **Non-target-specific Node Injection Attacks on Graph Neural Networks: A Hierarchical Reinforcement Learning Approach.**
    *Yiwei Sun, Suhang Wang, Xianfeng Tang, Tsung-Yu Hsieh, Vasant Honavar.* WWW 2020. [\[paper\]](https://arxiv.org/pdf/1909.06543.pdf)
12. **A Unified Framework for Data Poisoning Attack to Graph-based Semi-supervised Learning.**
    *Xuanqing Liu, Si Si, Xiaojin(Jerry) Zhu, Yang Li, Cho-Jui Hsieh.* NeurIPS 2019. [\[paper\]](https://arxiv.org/pdf/1910.14147.pdf)
13. **Attacking Graph Convolutional Networks via Rewiring.**
    *Yao Ma, Suhang Wang, Lingfei Wu, Jiliang Tang.*  arxiv 2019. [\[paper\]](https://arxiv.org/pdf/1906.03750.pdf)

### 2.3 Attacks on Combinatorial Problems

1. **Generalization of Neural Combinatorial Solvers Through the Lens of Adversarial Robustness.** arXiv 2021. [\[paper\]](https://arxiv.org/abs/2110.10942)

## 3. Defense Papers

1. **All You Need is Low (Rank): Defending Against Adversarial Attacks on Graphs.**
   *Negin Entezari, Saba Al-Sayouri, Amirali Darvishzadeh, and Evangelos E. Papalexakis.*  WSDM 2020. [\[paper\]](https://dl.acm.org/doi/pdf/10.1145/3336191.3371789?download=true) [\[code\]](https://github.com/DSE-MSU/DeepRobust/) ⭐ 1,086 | 🐛 54 | 🌐 Python | 📅 2025-06-26
2. **Adversarial Examples on Graph Data: Deep Insights into Attack and Defense.**
   *Huijun Wu, Chen Wang, Yuriy Tyshetskiy, Andrew Docherty, Kai Lu, Liming Zhu.*   IJCAI 2019. [\[paper\]](https://arxiv.org/pdf/1903.01610.pdf) [\[code\]](https://github.com/DSE-MSU/DeepRobust) ⭐ 1,086 | 🐛 54 | 🌐 Python | 📅 2025-06-26
3. **Graph Contrastive Learning with Augmentations.** NeurIPS 2020. [\[paper\]](https://arxiv.org/abs/2010.13902) [\[code\]](https://github.com/Shen-Lab/GraphCL) ⭐ 635 | 🐛 33 | 🌐 Python | 📅 2024-07-17
4. **Graph Structure Learning for Robust Graph Neural Networks.**
   *Wei Jin, Yao Ma, Xiaorui Liu, Xianfeng Tang, Suhang Wang, Jiliang Tang*. KDD 2020. [\[paper\]](https://arxiv.org/abs/2005.10203) [\[code\]](https://github.com/ChandlerBang/Pro-GNN) ⭐ 310 | 🐛 10 | 🌐 Python | 📅 2023-05-12
5. **Graph Information Bottleneck.** NeurIPS 2020. [\[paper\]](https://arxiv.org/abs/2010.12811) [\[code\]](https://github.com/snap-stanford/GIB) ⭐ 139 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2022-11-29
6. **Robust Detection of Adaptive Spammers by Nash Reinforcement Learning.** KDD 2020. [\[paper\]](https://arxiv.org/abs/2006.06069) [\[code\]](https://github.com/YingtongDou/Nash-Detect) ⭐ 120 | 🐛 0 | 🌐 Python | 📅 2020-11-17
7. **Empowering Graph Representation Learning with Test-Time Graph Transformation.** ICLR 2023 [\[paper\]](https://openreview.net/forum?id=Lnxl5pr018) [\[code\]](https://github.com/ChandlerBang/GTrans) ⭐ 67 | 🐛 0 | 🌐 Python | 📅 2023-06-23
8. **Topology Attack and Defense for Graph Neural Networks: An Optimization Perspective.**
   *Kaidi Xu, Hongge Chen, Sijia Liu, Pin-Yu Chen, Tsui-Wei Weng, Mingyi Hong, Xue Lin.*  IJCAI 2019. [\[paper\]](https://arxiv.org/pdf/1906.04214.pdf) [\[code\]](https://github.com/KaidiXu/GCN_ADV_Train) ⭐ 62 | 🐛 2 | 🌐 Python | 📅 2021-02-26
9. **Node Similarity Preserving Graph Convolutional Networks.** WSDM 2021. [\[paper\]](https://arxiv.org/abs/2011.09643) [\[code\]](https://github.com/ChandlerBang/SimP-GCN) ⭐ 60 | 🐛 1 | 🌐 Python | 📅 2021-03-11
10. **Elastic Graph Neural Networks.** ICML 2021. [\[paper\]](http://proceedings.mlr.press/v139/liu21k.html) [\[code\]](https://github.com/lxiaorui/ElasticGNN) ⭐ 42 | 🐛 0 | 🌐 Python | 📅 2021-07-25
11. **GARNET: Reduced-Rank Topology Learning for Robust and Scalable Graph Neural Networks.** LoG 2022 [\[paper\]](https://openreview.net/forum?id=kvwWjYQtmw) [\[code\]](https://github.com/cornell-zhang/GARNET) ⭐ 36 | 🐛 2 | 🌐 Python | 📅 2023-10-01
12. **Robustness of Graph Neural Networks at Scale.** NeurIPS 2021. [\[paper\]](https://www.in.tum.de/daml/robustness-of-gnns-at-scale/) [\[code\]](https://github.com/sigeisler/robustness_of_gnns_at_scale) ⭐ 30 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2023-07-25
13. **Variational Inference for Graph Convolutional Networks in the Absence of Graph Data and Adversarial Settings.** NeurIPS 2020. [\[paper\]](https://arxiv.org/abs/1906.01852) [\[code\]](https://github.com/ebonilla/VGCN) ⭐ 23 | 🐛 0 | 🌐 Python | 📅 2020-10-16
14. **Reliable Graph Neural Networks via Robust Aggregation.** NeurIPS 2020. [\[paper\]](https://arxiv.org/abs/2010.15651) [\[code\]](https://github.com/sigeisler/reliable_gnn_via_robust_aggregation) ⭐ 17 | 🐛 0 | 🌐 Python | 📅 2022-03-16
15. **Expressive 1-Lipschitz Neural Networks for Robust Multiple Graph Learning against Adversarial Attacks.** ICML 2021. [\[paper\]](http://proceedings.mlr.press/v139/zhao21e/zhao21e.pdf)
16. **Integrated Defense for Resilient Graph Matching.** ICML 2021. [\[paper\]](http://proceedings.mlr.press/v139/ren21c/ren21c.pdf)
17. **GNNGuard: Defending Graph Neural Networks against Adversarial Attacks.** NeurIPS 2020. [\[paper\]](https://arxiv.org/abs/2006.08149)
18. **Robust Graph Representation Learning via Neural Sparsification.** ICML 2020. [\[paper\]](https://proceedings.icml.cc/static/paper_files/icml/2020/2611-Paper.pdf)
19. **Robust Collective Classification against Structural Attacks.**
    *Kai Zhou, Yevgeniy Vorobeychik.* UAI 2020. [\[paper\]](http://www.auai.org/uai2020/proceedings/119_main_paper.pdf)
20. **EDoG: Adversarial Edge Detection For Graph Neural Networks.** [\[paper\]](https://www.osti.gov/servlets/purl/1631086)
21. **A Robust Hierarchical Graph Convolutional Network Model for Collaborative Filtering.**
    *Shaowen Peng, Tsunenori Mine.* arxiv 2020. [\[paper\]](https://arxiv.org/pdf/2004.14734.pdf)
22. **Tensor Graph Convolutional Networks for Multi-relational and Robust Learning.**
    *Vassilis N. Ioannidis, Antonio G. Marques, Georgios B. Giannakis.* arxiv 2020. [\[paper\]](https://arxiv.org/pdf/2003.07729.pdf)
23. **Topological Effects on Attacks Against Vertex Classification.**
    *Benjamin A. Miller, Mustafa Çamurcu, Alexander J. Gomez, Kevin Chan, Tina Eliassi-Rad.* arxiv 2020. [\[paper\]](https://arxiv.org/pdf/2003.05822.pdf)
24. **Towards an Efficient and General Framework of Robust Training for Graph Neural Networks.**
    *Kaidi Xu, Sijia Liu, Pin-Yu Chen, Mengshu Sun, Caiwen Ding, Bhavya Kailkhura, Xue Lin.* arxiv 2020. [\[paper\]](https://arxiv.org/pdf/2002.10947.pdf)
25. **How Robust Are Graph Neural Networks to Structural Noise?**
    *James Fox, Sivasankaran Rajamanickam.* arxiv 2020. [\[paper\]](https://arxiv.org/pdf/1912.10206.pdf)
26. **GraphDefense: Towards Robust Graph Convolutional Networks.**
    *Xiaoyun Wang, Xuanqing Liu, Cho-Jui Hsieh.*  arxiv 2019. [\[paper\]](https://arxiv.org/pdf/1911.04429v1.pdf)
27. **Graph Adversarial Training: Dynamically Regularizing Based on Graph Structure**
    *Fuli Feng, Xiangnan He, Jie Tang, Tat-Seng Chua.*  TKDE 2019. [\[paper\]](https://arxiv.org/pdf/1902.08226.pdf)
28. **Edge Dithering for Robust Adaptive Graph Convolutional Networks.**
    *Vassilis N. Ioannidis, Georgios B. Giannakis.*  arxiv 2019. [\[paper\]](https://arxiv.org/pdf/1910.09590.pdf)
29. **GraphSAC: Detecting anomalies in large-scale graphs.**
    *Vassilis N. Ioannidis, Dimitris Berberidis, Georgios B. Giannakis.* arxiv 2019. [\[paper\]](https://arxiv.org/pdf/1910.09589.pdf)
30. **Robust Graph Neural Network Against Poisoning Attacks via Transfer Learning.**
    *Xianfeng Tang, Yandong Li, Yiwei Sun, Huaxiu Yao, Prasenjit Mitra, Suhang Wang.*  WSDM 2020. [\[paper\]](https://arxiv.org/pdf/1908.07558.pdf)
31. **Robust Graph Convolutional Networks Against Adversarial Attacks.**
    *Dingyuan Zhu, Ziwei Zhang, Peng Cui, Wenwu Zhu.*  KDD 2019. [\[paper\]](http://pengcui.thumedialab.com/papers/RGCN.pdf)
32. **Power up! Robust Graph Convolutional Network against Evasion Attacks based on Graph Powering.**
    *Ming Jin, Heng Chang, Wenwu Zhu, Somayeh Sojoudi.*  arxiv 2019. [\[paper\]](https://arxiv.org/abs/1905.10029)
33. **Latent Adversarial Training of Graph Convolution Networks.**
    *Hongwei Jin, Xinhua Zhang.*  ICML 2019 workshop. [\[paper\]](https://graphreason.github.io/papers/35.pdf)
34. **Batch Virtual Adversarial Training for Graph Convolutional Networks.**
    *Zhijie Deng, Yinpeng Dong, Jun Zhu.*  ICML 2019 Workshop. [\[paper\]](https://arxiv.org/pdf/1902.09192.pdf)
35. **Graph Adversarial Training: Dynamically Regularizing Based on Graph Structure.**
    *Fuli Feng, Xiangnan He, Jie Tang, Tat-Seng Chua.*   arXiv, 2019. [\[paper\]](https://arxiv.org/pdf/1902.08226.pdf)

## 4. Certified Robustness Papers

1. **Certifiable Robustness and Robust Training for Graph Convolutional Networks.**
   *Daniel Zügner Stephan Günnemann.*  KDD 2019. [\[paper\]](https://arxiv.org/pdf/1906.12269.pdf) [\[code\]](https://github.com/danielzuegner/robust-gcn) ⭐ 42 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2020-12-07
2. **Efficient Robustness Certificates for Graph Neural Networks via Sparsity-Aware Randomized Smoothing.** ICML 2020. [\[paper\]](https://proceedings.icml.cc/static/paper_files/icml/2020/6890-Paper.pdf) [\[code\]](https://github.com/abojchevski/sparse_smoothing) ⭐ 37 | 🐛 1 | 🌐 Python | 📅 2023-06-27
3. **Certifiable Robustness to Graph Perturbations.**
   *Aleksandar Bojchevski, Stephan Günnemann.*  NeurIPS 2019. [\[paper\]](https://arxiv.org/pdf/1910.14356.pdf)[\[code\]](https://github.com/abojchevski/graph_cert) ⭐ 14 | 🐛 1 | 🌐 Jupyter Notebook | 📅 2020-05-08
4. **Certified Robustness of Graph Convolution Networks for Graph Classification under Topological Attacks.** NeurIPS 2020. [\[paper\]](https://arxiv.org/abs/2009.05872) [\[code\]](https://github.com/RobustGraph/RoboGraph) ⭐ 13 | 🐛 0 | 🌐 Python | 📅 2021-06-17
5. **Certifiable Robustness of Graph Convolutional Networks under Structure Perturbations.** KDD 2020. [\[paper\]](https://dl.acm.org/doi/abs/10.1145/3394486.3403217) [\[code\]](https://github.com/danielzuegner/robust-gcn-structure) ⭐ 11 | 🐛 0 | 🌐 Python | 📅 2020-12-01
6. **Adversarial Immunization for Improving Certifiable Robustness on Graphs.** Arxiv 2020. [\[paper\]](https://arxiv.org/abs/2007.09647)
7. **Certified Robustness of Graph Neural Networks against Adversarial Structural Perturbation.** Arxiv 2020. [\[paper\]](https://arxiv.org/abs/2008.10715)
8. **Certified Robustness of Community Detection against Adversarial Structural Perturbation via Randomized Smoothing.**
   *Jinyuan Jia, Binghui Wang, Xiaoyu Cao, Neil Zhenqiang Gong.* WWW 2020. [\[paper\]](https://arxiv.org/pdf/2002.03421.pdf)

### Relevant Workshops

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-09-04._
