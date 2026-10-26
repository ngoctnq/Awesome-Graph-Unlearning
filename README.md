# Awesome Graph Unlearning
[![Awesome](https://awesome.re/badge.svg)](https://github.com/ngoctnq/Awesome-Graph-Unlearning) 
[![License: CC-BY-4.0](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](https://github.com/ngoctnq/Awesome-Graph-Unlearning/blob/main/LICENSE)
[![PRs Welcome](https://img.shields.io/badge/PRs-Welcome-red)](https://github.com/ngoctnq/Awesome-Graph-Unlearning/compare)

This repository aims to provide comprehensive paper lists of works on machine unlearning for the graph domain, accompanying [**A Survey of Graph Unlearning**](https://www.sciencedirect.com/science/article/pii/S0925231226028687).
<br>
Missing paper recommendations are welcomed! Please contribute by creating a new **Issue** or **Pull Request**.

   
## Content

- [Surveys and Benchmarks](#surveys-and-benchmarks)
- [Retraining-based Methods](#retraining-based-methods)
    - [Partitioning and Sharding](#partitioning-and-sharding)
    - [Parameter-based Retraining](#parameter-based-retraining)
- [Model and Graph Update Methods](#model-and-graph-update-methods)
    - [Closed-form Updates](#closed-form-updates)
    - [Influence Functions and Second-order Updates](#influence-functions-and-second-order-updates)
    - [Model Editing and Local Adaptation](#model-editing-and-local-adaptation)
    - [Distillation-based Methods](#distillation-based-methods)
    - [Other Unlearning Objectives](#other-unlearning-objectives)

##  Papers

### Surveys and Benchmarks
- [[arXiv](https://arxiv.org/abs/2501.02728)]
    [[code](https://github.com/bwfan-bit/OpenGU)]
    _Fan et al._
    **OpenGU: A Comprehensive Benchmark for Graph Unlearning**
    (2025).

---

### Retraining-based Methods

#### Partitioning and Sharding
- [[CCS](https://dl.acm.org/doi/10.1145/3548606.3559352)]
    [[arxiv](https://arxiv.org/abs/2103.14991)]
    [[code](https://github.com/MinChen00/Graph-Unlearning)]
    _Chen et al.,_
    **Graph Unlearning**
    (2022).
- [[WWW](https://dl.acm.org/doi/10.1145/3485447.3511997)]
    [[arxiv](https://arxiv.org/abs/2201.06820)]
    [[code](https://github.com/chenchongthu/Recommendation-Unlearning)]
    _Chen et al.,_
    **Recommendation Unlearning**
    (2022).
- [[USENIX](https://www.usenix.org/conference/usenixsecurity23/presentation/wang-cheng-long)]
    [[arxiv](https://arxiv.org/abs/2304.03093)]
    [[code](https://github.com/Happy2Git/GUIDE)]
    _Wang et al.,_
    **Inductive Graph Unlearning**
    (2023).
- [[NeurIPS](https://proceedings.neurips.cc/paper_files/paper/2023/hash/29a0ea49a103a233b17c0705cdeccb66-Abstract-Conference.html)]
    [[code](https://github.com/ZhangYizhao/UltraRE)]
    _Zhang et al.,_
    **UltraRE: Enhancing RecEraser for Recommendation Unlearning via Error Decomposition**
    (2023).

#### Parameter-based Retraining
- [[arxiv](https://arxiv.org/abs/2302.06676)]
    _Xu et al.,_
    **Netflix and Forget: Efficient and Exact Machine Unlearning from Bi-linear Recommendations**
    (2023).

---

### Model and Graph Update Methods

#### Closed-form Updates
- [[preprint](https://congweilin.github.io/CongWeilin.io/files/GraphEditor.pdf)]
    _Cong and Mahdavi,_
    **GraphEditor: An Efficient Graph Representation Learning and Unlearning Approach**
    (2023).
- [[AISTATS](https://proceedings.mlr.press/v206/cong23a.html)]
    [[arxiv](https://arxiv.org/abs/2302.08990)]
    [[code](https://github.com/CongWeilin/Projector)]
    _Cong and Mahdavi,_
    **GraphEditor: An Efficient Graph Representation Learning and Unlearning Approach**
    (2023).

#### Influence Functions and Second-order Updates
- [[WWW](https://dl.acm.org/doi/10.1145/3543507.3583547)]
    [[arxiv](https://arxiv.org/abs/2211.03216)]
    [[code](https://github.com/thupchnsky/graph_unlearn)]
    _Pan et al.,_
    **Unlearning Graph Classifiers with Limited Data Resources**
    (2023).
- [[ICLR](https://openreview.net/forum?id=fhcu4FBLciL)]
    [[arxiv](https://arxiv.org/abs/2206.09140)]
    [[code](https://github.com/thupchnsky/sgc_unlearn)]
    _Chien et al.,_
    **Efficient Model Updates for Approximate Unlearning of Graph-Structured Data**
    (2023).
- [[WWW](https://dl.acm.org/doi/10.1145/3543507.3583521)]
    [[arxiv](https://arxiv.org/abs/2304.02835)]
    [[code](https://github.com/wujcan/GIF-torch)]
    _Wu et al.,_
    **GIF: A General Graph Unlearning Strategy via Influence Function**
    (2023).
- [[ESWA](https://www.sciencedirect.com/science/article/pii/S0957417423015270)]
    [[arxiv](https://arxiv.org/abs/2304.10199)]
    _Li et al.,_
    **Selective and Collaborative Influence Function for Efficient Recommendation Unlearning**
    (2023).
- [[KDD](https://dl.acm.org/doi/10.1145/3580305.3599271)]
    [[preprint](https://yue-ning.github.io/docs/kdd23-ceu.pdf)]
    [[code](https://github.com/kunwu522/certified_edge_unlearning)]
    _Wu et al.,_
    **Certified Edge Unlearning for Graph Neural Networks**
    (2023).
- [[KDD](https://dl.acm.org/doi/10.1145/3637528.3671744)]
    [[arxiv](https://arxiv.org/abs/2407.19398)]
    [[code](https://github.com/yushundong/IDEA)]
    _Dong et al.,_
    **IDEA: A Flexible Framework of Certified Unlearning for Graph Neural Networks**
    (2024).
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/33423)]
    [[arxiv](https://arxiv.org/abs/2409.16684)]
    [[code](https://github.com/AllminerLab/ETR)]
    _Yang et al.,_
    **Erase then Rectify: A Training-Free Parameter Editing Approach for Cost-Effective Graph Unlearning**
    (2025).
- [[ACM ToRS](https://dl.acm.org/doi/10.1145/3701763)]
    [[arxiv](https://arxiv.org/abs/2307.02147)]
    [[code](https://github.com/baiyimeng/IFRU)]
    _Zhang et al.,_
    **Recommendation Unlearning via Influence Function**
    (2024).
- [[ICLR](https://openreview.net/forum?id=pPyJyeLriR)]
    [[arxiv](https://arxiv.org/abs/2408.09212)]
    [[code](https://github.com/luyi256/ScaleGUN)]
    _Yi and Wei,_
    **Scalable and Certifiable Graph Unlearning: Overcoming the Approximation Error Barrier**
    (2025).

#### Model Editing and Local Adaptation
- [[ICLR](https://openreview.net/forum?id=X9yCkmT5Qrl)]
    [[arxiv](https://arxiv.org/abs/2302.13406)]
    [[code](https://github.com/mims-harvard/GNNDelete)]
    _Cheng et al.,_
    **GNNDelete: A General Strategy for Unlearning in Graph Neural Networks**
    (2023).
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/29273)]
    [[arxiv](https://arxiv.org/abs/2401.11760)]
    [[code](https://github.com/xkLi-Allen/MEGU)]
    _Li et al.,_
    **Towards Effective and General Graph Unlearning via Mutual Evolution**
    (2024).
- [[WWW](https://doi.org/10.1145/3589335.3651578)]
    [[arxiv](https://arxiv.org/abs/2402.10695)]
    [code](https://github.com/Sumsky21/Unlink-to-Unlearn)]
    _Tan et al.,_
    **Unlink to Unlearn: Simplifying Edge Unlearning in GNNs**
    (2024).
- [[IJCAI](https://ijcai.org/proceedings/2025/308)]
    [[arxiv](https://arxiv.org/abs/2505.12614)]
    [[code](https://github.com/Aliezzz/AGU)]
    _Ding et al.,_
    **Adaptive Graph Unlearning**
    (2025).
- [[arxiv](https://arxiv.org/abs/2501.11823)]
    _Li et al.,_
    **Toward Scalable Graph Unlearning: A Node Influence Maximization based Approach**
    (2025).
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/34041)]
    [[arxiv](https://arxiv.org/abs/2408.09705)]
    [[code](https://github.com/liiiyi/CCGU)]
    _Li et al.,_
    **Community-Centric Graph Unlearning**
    (2025).
- [[COLING](https://aclanthology.org/2025.coling-main.238/)]
    [[code](https://github.com/NKUShaw/KGUnlearningBySchema)]
    _Xiao et al.,_
    **Knowledge Graph Unlearning with Schema**
    (2025).

#### Distillation-based Methods
- [[ICICS](https://link.springer.com/chapter/10.1007/978-981-99-7356-9_29)]
    _Zheng et al.,_
    **Graph Unlearning Using Knowledge Distillation**
    (2023).
- [[TNNLS](https://ieeexplore.ieee.org/document/11197591)]
    [[arxiv](https://arxiv.org/abs/2309.16173)]
    [[code](https://github.com/MachineUnlearn/D2DGN)]
    _Sinha et al.,_
    **Distill to Delete: Unlearning in Graph Networks With Knowledge Distillation**
    (2025).
- [[WWW](https://dl.acm.org/doi/10.1145/3774904.3792383)]
    [[arxiv](https://arxiv.org/abs/2601.14694)]
    _Ding et al.,_
    **Re-understanding Graph Unlearning through Memorization**
    (2026).

#### Other Unlearning Objectives
- [[AAAI](https://ojs.aaai.org/index.php/AAAI/article/view/28782)]
    _You et al.,_
    **RRL: Recommendation Reverse Learning**
    (2024).
- [[ICML](https://proceedings.mlr.press/v267/kolipaka25a.html)]
    [[arxiv](https://arxiv.org/abs/2412.00789)]
    [[code](https://github.com/cognac-gnn-unlearning/corrective-unlearning-for-gnns)]
    _Kolipaka et al.,_
    **A Cognac Shot To Forget Bad Memories: Corrective Unlearning for Graph Neural Networks**
    (2025).
- [[WWW](https://dl.acm.org/doi/10.1145/3774904.3792397)]
    [[arxiv](https://arxiv.org/abs/2507.20566)]
    [[code](https://github.com/ljj-007/GraphDPO)]
    _Liu et al.,_
    **Unlearning of Knowledge Graph Embedding via Preference Optimization**
    (2026).

## Contribution
### Contributors 
<a href="https://github.com/ngoctnq/Awesome-Graph-Unlearning/graphs/contributors">
  <img src="https://contrib.rocks/image?repo=ngoctnq/Awesome-Graph-Unlearning" />
</a>

### Contributing (welcome!)
- Add a new paper or update an existing one by creating a new **Issue** or **Pull Request**.
- Use the same format as existing entries to describe the work.
- A very brief explanation why you think a paper should be added or updated (optional, but recommended).

## Star History

[![Star History Chart](https://api.star-history.com/svg?repos=ngoctnq/Awesome-Graph-Unlearning&type=Date)](https://star-history.com/#ngoctnq/Awesome-Graph-Unlearning&Date)

---
This work is licensed under a
[Creative Commons Attribution 4.0 International License][cc-by].

[![CC BY 4.0][cc-by-image]][cc-by]

[cc-by]: http://creativecommons.org/licenses/by/4.0/
[cc-by-image]: https://i.creativecommons.org/l/by/4.0/88x31.png