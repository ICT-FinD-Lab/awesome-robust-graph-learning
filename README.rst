Awesome Robust Graph Learning Resources
=======================================

Robust graph learning is to develop learning algorithms that maintain predictive accuracy and stability in the presence of structural noise, adversarial perturbations, and out-of-distribution (OOD) shifts.

**This repository collects**:


#. Academic Papers
#. Online Courses and Videos
#. Graph Datasets
#. Open-source and Commercial Libraries/Toolkits
#. Key Conferences & Journals


**More items will be added to the repository**.
Please feel free to suggest other key resources by opening an issue report,
submitting a pull request, or dropping me an email @ (liuyang173@mails.ucas.edu.cn).
Enjoy reading!


----

Table of Contents
-----------------

* `1. Tutorials & Benchmarks <#1-tutorials--benchmarks>`_

  * `1.1. Benchmarks <#11-benchmarks>`_
  * `1.2. Tutorials <#12-tutorials>`_

* `2. Toolbox & Datasets <#2-toolbox--datasets>`_

  * `2.1. Toolboxes & Libraries <#21-toolboxes--libraries>`_
  * `2.2. Datasets <#22-datasets>`_

* `3. Papers <#3-papers>`_

  * `3.1. Graph Adversarial Attack <#31-graph-adversarial-attack>`_
  * `3.2. Graph Adversarial Defense & Robust GNNs <#32-graph-adversarial-defense--robust-gnns>`_
  * `3.3. Graph Structure Learning & Learning under Noisy/Weak Information <#33-graph-structure-learning--learning-under-noisyweak-information>`_
  * `3.4. Graph Anomaly Detection <#34-graph-anomaly-detection>`_
  * `3.5. Graph Out-of-Distribution Generalization <#35-graph-out-of-distribution-generalization>`_
  * `3.6. Privacy & IP Protection for GNNs <#36-privacy--ip-protection-for-gnns>`_

* `4. Key Conferences/Workshops/Journals <#4-key-conferencesworkshopsjournals>`_

  * `4.1. Conferences & Workshops <#41-conferences--workshops>`_
  * `4.2. Journals <#42-journals>`_

-----------

1. Tutorials & Benchmarks
-------------------------

1.1. Benchmarks
^^^^^^^^^^^^^^^

======================  =============================================================================================  =======  ====  =====================  ============================================================================================================================
Scope                   Paper Title                                                                                    Venue    Year  Ref                    Materials
======================  =============================================================================================  =======  ====  =====================  ============================================================================================================================
Adversarial Robustness  Graph Robustness Benchmark: Benchmarking the Adversarial Robustness of Graph Machine Learning  NeurIPS  2021  [#Zheng2021GRB]_       `[PDF] <https://arxiv.org/pdf/2111.04314>`_, `[Code] <https://github.com/THUDM/grb>`_, `[Home] <https://cogdl.ai/grb/home>`_
OOD Generalization      GOOD: A Graph Out-of-Distribution Benchmark                                                    NeurIPS  2022  [#Gui2022GOOD]_        `[PDF] <https://arxiv.org/pdf/2206.08452>`_, `[Code] <https://github.com/divelab/GOOD>`_
Anomaly Detection       GADBench: Revisiting and Benchmarking Supervised Graph Anomaly Detection                       NeurIPS  2023  [#Tang2023GADBench]_   `[PDF] <https://arxiv.org/pdf/2306.12251>`_, `[Code] <https://github.com/squareRoot3/GADBench>`_
Anomaly Detection       BOND: Benchmarking Unsupervised Outlier Node Detection on Static Attributed Graphs             NeurIPS  2022  [#Liu2022BOND]_        `[PDF] <https://arxiv.org/pdf/2206.10071>`_, `[Code] <https://github.com/pygod-team/pygod>`_
Structure Learning      OpenGSL: A Comprehensive Benchmark for Graph Structure Learning                                NeurIPS  2023  [#Zhou2023OpenGSL]_    `[PDF] <https://arxiv.org/pdf/2306.10280>`_, `[Code] <https://github.com/OpenGSL/OpenGSL>`_
Large-scale Graph ML    Open Graph Benchmark: Datasets for Machine Learning on Graphs                                  NeurIPS  2020  [#Hu2020OGB]_          `[PDF] <https://arxiv.org/pdf/2005.00687>`_, `[Code] <https://github.com/snap-stanford/ogb>`_
Adaptive-attack Audit   Are Defenses for Graph Neural Networks Robust?                                                 NeurIPS  2022  [#Mujkanovic2022Are]_  `[PDF] <https://arxiv.org/pdf/2301.13694>`_, `[Code] <https://github.com/LoadingByte/are-gnn-defenses-robust>`_
======================  =============================================================================================  =======  ====  =====================  ============================================================================================================================

.. note:: ``GRB``, ``GOOD``, ``GADBench``, ``BOND`` and ``OpenGSL`` are NeurIPS *Datasets and Benchmarks Track* papers; *Are Defenses for GNNs Robust?* is an adaptive-attack re-evaluation showing many published defenses give little gain over an undefended baseline.

1.2. Tutorials
^^^^^^^^^^^^^^

=======================================================================  =====  ====  ===============================  ===========================================================================================================
Tutorial Title                                                           Venue  Year  Ref                              Materials
=======================================================================  =====  ====  ===============================  ===========================================================================================================
Robust Graph Learning in Finance                                         ICAIF  2025  [#Ao2025RobustFinanceTutorial]_  `[HTML] <https://qwer12191.github.io/robust-graph-learning/>`_, `[ICAIF] <https://icaif25.org/tutorials/>`_
Robust Graph Learning on the Web: Challenges, Methods, and Applications  WWW    2026  [#Ao2026RobustGraphTutorial]_    `[HTML] <https://qwer12191.github.io/Robust-Graph-Learning-on-Web/>`_
=======================================================================  =====  ====  ===============================  ===========================================================================================================

----

2. Toolbox & Datasets
---------------------

2.1. Toolboxes & Libraries
^^^^^^^^^^^^^^^^^^^^^^^^^^

=================  ========================================================================================================================  ==============================================================================================
Toolbox            Description                                                                                                               Materials
=================  ========================================================================================================================  ==============================================================================================
DeepRobust         PyTorch library of adversarial attacks and defenses (image + graph); de-facto standard for graph adversarial robustness.  `[Code] <https://github.com/DSE-MSU/DeepRobust>`_, `[PDF] <https://arxiv.org/pdf/2005.06149>`_
GRB                Modular, reproducible framework for benchmarking the adversarial robustness of graph ML.                                  `[Code] <https://github.com/THUDM/grb>`_, `[Home] <https://cogdl.ai/grb/home>`_
GreatX             Toolbox for graph reliability and adversarial robustness (formerly GraphWar), built on PyG.                               `[Code] <https://github.com/EdisonLeeeee/GreatX>`_
GUARD              Graph universal adversarial defense; training-free defensive patch for GCNs (CIKM 2023).                                  `[Code] <https://github.com/EdisonLeeeee/GUARD>`_, `[PDF] <https://arxiv.org/pdf/2204.09803>`_
PyGOD              Comprehensive Python library for graph outlier / anomaly detection (JMLR 2024).                                           `[Code] <https://github.com/pygod-team/pygod>`_, `[PDF] <https://arxiv.org/pdf/2204.12095>`_
PyTorch Geometric  Widely used GNN library; foundation many robust-graph toolboxes build on.                                                 `[Code] <https://github.com/pyg-team/pytorch_geometric>`_
DGL                Framework-agnostic, high-performance package for deep learning on graphs.                                                 `[Code] <https://github.com/dmlc/dgl>`_
CogDL              Comprehensive graph deep-learning toolkit; also hosts GRB (WWW 2023).                                                     `[Code] <https://github.com/THUDM/CogDL>`_
DIG                Turnkey research library: graph generation, self-supervised learning, explainability, and OOD.                            `[Code] <https://github.com/divelab/DIG>`_
GraphGym           Platform for GNN design-space exploration and reproducible experiments (now integrated into PyG).                         `[Code] <https://github.com/snap-stanford/GraphGym>`_
=================  ========================================================================================================================  ==============================================================================================

2.2. Datasets
^^^^^^^^^^^^^

=======================  ===========================================  ===================================================================  ======================================================================================================================================================
Category                 Datasets                                     Typical Use                                                          Materials
=======================  ===========================================  ===================================================================  ======================================================================================================================================================
Citation networks        Cora, CiteSeer, PubMed                       Standard node-classification benchmark for attacks/defenses and GSL  `[Planetoid] <https://github.com/kimiyoung/planetoid>`_, `[PyG] <https://pytorch-geometric.readthedocs.io>`_
Co-purchase / Co-author  Amazon Computers/Photo, Coauthor CS/Physics  Robustness to data splits; semi-supervised node classification       `[Repo] <https://github.com/shchur/gnn-benchmark>`_
Political blogs          Polblogs                                     Featureless graph for structure attacks (Nettack / Metattack)        `[Data] <https://github.com/DSE-MSU/DeepRobust>`_
Large-scale              ogbn-arxiv, ogbn-products                    Scalable robustness and OOD evaluation                               `[OGB] <https://ogb.stanford.edu>`_
Inductive                Reddit, Flickr                               Inductive node classification and scalability                        `[GraphSAGE] <https://snap.stanford.edu/graphsage/>`_, `[GraphSAINT] <https://github.com/GraphSAINT/GraphSAINT>`_
Fraud / Anomaly          YelpChi, Amazon (fraud)                      Multi-relation fraud / graph anomaly detection                       `[CARE-GNN] <https://github.com/YingtongDou/CARE-GNN>`_
Financial anomaly        T-Finance, T-Social, Elliptic                Large-scale anomaly / anti-money-laundering detection                `[BWGNN] <https://github.com/squareRoot3/Rethinking-Anomaly-Detection>`_, `[Elliptic] <https://www.kaggle.com/datasets/ellipticco/elliptic-data-set>`_
OOD splits               GOOD-Cora, GOOD-CBAS                         Covariate / concept shift evaluation                                 `[GOOD] <https://github.com/divelab/GOOD>`_
Molecular OOD            DrugOOD                                      Molecular property OOD (scaffold / size / assay splits)              `[DrugOOD] <https://github.com/tencent-ailab/DrugOOD>`_
=======================  ===========================================  ===================================================================  ======================================================================================================================================================

----

3. Papers
---------

3.1. Graph Adversarial Attack
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

=======================  ============================================================================================  ===============  ====  =========================  ====================================================================================================================================
Category                 Paper Title                                                                                   Venue            Year  Ref                        Materials
=======================  ============================================================================================  ===============  ====  =========================  ====================================================================================================================================
Evasion Attack           Adversarial Attack on Graph Structured Data                                                   ICML             2018  [#Dai2018Adversarial]_     `[PDF] <https://arxiv.org/pdf/1806.02371>`_, `[Code] <https://github.com/Hanjun-Dai/graph_adversarial_attack>`_
Evasion Attack           Adversarial Attacks on Neural Networks for Graph Data                                         KDD              2018  [#Zugner2018Adversarial]_  `[PDF] <https://arxiv.org/pdf/1805.07984>`_, `[Code] <https://github.com/danielzuegner/nettack>`_
Evasion / Poisoning      Topology Attack and Defense for Graph Neural Networks: An Optimization Perspective            IJCAI            2019  [#Xu2019Topology]_         `[PDF] <https://arxiv.org/pdf/1906.04214>`_, `[Code] <https://github.com/KaidiXu/GCN_ADV_Train>`_
Evasion Attack           Indirect Adversarial Attacks via Poisoning Neighbors for Graph Convolutional Networks         BigData          2019  [#Takahashi2019Indirect]_  `[PDF] <https://arxiv.org/pdf/2002.08012>`_, Code: N/A
Evasion (Black-box)      A Restricted Black-box Adversarial Framework Towards Attacking Graph Embedding Models         AAAI             2020  [#Chang2020Restricted]_    `[PDF] <https://arxiv.org/pdf/1908.01297>`_, `[Code] <https://github.com/SwiftieH/GFAttack>`_
Evasion (Universal)      Graph Universal Adversarial Attacks: A Few Bad Actors Ruin Graph Learning Models              IJCAI            2021  [#Zang2021Graph]_          `[PDF] <https://arxiv.org/pdf/2002.04784>`_, `[Code] <https://github.com/chisam0217/Graph-Universal-Attack>`_
Poisoning Attack         Adversarial Attacks on Graph Neural Networks via Meta Learning                                ICLR             2019  [#Zugner2019Adversarial]_  `[PDF] <https://openreview.net/pdf?id=Bylnx209YX>`_, `[Code] <https://github.com/danielzuegner/gnn-meta-attack>`_
Injection Attack         Adversarial Attacks on Graph Neural Networks via Node Injections: A Hierarchical RL Approach  WWW              2020  [#Sun2020NIPA]_            `[Paper] <https://dl.acm.org/doi/10.1145/3366423.3380149>`_, Code: N/A
Injection Attack         TDGIA: Effective Injection Attacks on Graph Neural Networks                                   KDD              2021  [#Zou2021TDGIA]_           `[PDF] <https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD21-Zou-et-al-TDGIA.pdf>`_, `[Code] <https://github.com/THUDM/tdgia>`_
Injection Attack         Single Node Injection Attack against Graph Neural Networks                                    CIKM             2021  [#Tao2021Single]_          `[PDF] <https://arxiv.org/pdf/2108.13049>`_, `[Code] <https://github.com/TaoShuchang/G-NIA>`_
Injection Attack         Understanding and Improving Graph Injection Attack by Promoting Unnoticeability               ICLR             2022  [#Chen2022Understanding]_  `[PDF] <https://arxiv.org/pdf/2202.08057>`_, `[Code] <https://github.com/LFhase/GIA-HAO>`_
Injection (Query-based)  Cluster Attack: Query-based Adversarial Attacks on Graphs with Graph-Dependent Priors         IJCAI            2022  [#Wang2022Cluster]_        `[PDF] <https://arxiv.org/pdf/2109.13069>`_, `[Code] <https://github.com/thuwzy/Cluster-Attack>`_
Backdoor Attack          Graph Backdoor                                                                                USENIX Security  2021  [#Xi2021Graph]_            `[PDF] <https://arxiv.org/pdf/2006.11890>`_, `[Code] <https://github.com/zhaohan-xi/GraphBackdoor>`_
Backdoor Attack          Backdoor Attacks to Graph Neural Networks                                                     SACMAT           2021  [#Zhang2021Backdoor]_      `[PDF] <https://arxiv.org/pdf/2006.11165>`_, `[Code] <https://github.com/zaixizhang/graphbackdoor>`_
Backdoor Attack          Unnoticeable Backdoor Attacks on Graph Neural Networks                                        WWW              2023  [#Dai2023Unnoticeable]_    `[PDF] <https://arxiv.org/pdf/2303.01263>`_, `[Code] <https://github.com/ventr1c/UGBA>`_
Backdoor Attack          SPEAR: A Structure-Preserving Manipulation Method for Graph Backdoor Attacks                  WWW              2025  [#Ding2025SPEAR]_          `[PDF] <https://ponderly.github.io/pub/SPEAR_WWW2025.pdf>`_, `[Code] <https://github.com/yhDing/SPEAR>`_
=======================  ============================================================================================  ===============  ====  =========================  ====================================================================================================================================

3.2. Graph Adversarial Defense & Robust GNNs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Model- and structure-level defenses against adversarial perturbations: robust aggregation, robust spectral filtering, preprocessing/purification, adversarial training, and certified robustness.

=============================  ===============================================================================================================  =======  ====  =============================  =========================================================================================================================
Category                       Paper Title                                                                                                      Venue    Year  Ref                            Materials
=============================  ===============================================================================================================  =======  ====  =============================  =========================================================================================================================
Preprocessing                  Adversarial Examples for Graph Data: Deep Insights into Attack and Defense                                       IJCAI    2019  [#ijcai2019p669]_              `[PDF] <https://arxiv.org/pdf/1903.01610>`_
Robust Architecture            Robust Graph Convolutional Networks Against Adversarial Attacks                                                  KDD      2019  [#Zhu2019Robust]_              `[Paper] <https://dl.acm.org/doi/10.1145/3292500.3330851>`_, `[Code] <https://github.com/ZW-ZHANG/RobustGCN>`_
Certified Defense              Certifiable Robustness and Robust Training for Graph Convolutional Networks                                      KDD      2019  [#Zugner2019Certifiable]_      `[PDF] <https://arxiv.org/pdf/1906.12269>`_, `[Code] <https://github.com/danielzuegner/robust-gcn>`_
Certified Defense              Certifiable Robustness to Graph Perturbations                                                                    NeurIPS  2019  [#Bojchevski2019Certifiable]_  `[PDF] <https://arxiv.org/pdf/1910.14356>`_, `[Code] <https://github.com/abojchevski/graph_cert>`_
Preprocessing (Low-rank)       All You Need Is Low (Rank): Defending Against Adversarial Attacks on Graphs                                      WSDM     2020  [#entezari2020all]_            `[PDF] <https://dl.acm.org/doi/pdf/10.1145/3336191.3371789>`_
Certified Defense              Efficient Robustness Certificates for Discrete Data: Sparsity-Aware Randomized Smoothing                         ICML     2020  [#Bojchevski2020Efficient]_    `[PDF] <https://arxiv.org/pdf/2008.12952>`_, `[Code] <https://github.com/abojchevski/sparse_smoothing>`_
Structure Learning             Graph Structure Learning for Robust Graph Neural Networks                                                        KDD      2020  [#jin2020graph]_               `[PDF] <https://dl.acm.org/doi/pdf/10.1145/3394486.3403049>`_, `[Code] <https://github.com/ChandlerBang/Pro-GNN>`_
Robust Aggregation             GNNGuard: Defending Graph Neural Networks against Adversarial Attacks                                            NeurIPS  2020  [#Zhang2020GNNGuard]_          `[PDF] <https://arxiv.org/pdf/2006.08149>`_, `[Code] <https://github.com/mims-harvard/GNNGuard>`_
Robust Aggregation             Reliable Graph Neural Networks via Robust Aggregation                                                            NeurIPS  2020  [#Geisler2020Reliable]_        `[PDF] <https://arxiv.org/pdf/2010.15651>`_, `[Code] <https://github.com/sigeisler/reliable_gnn_via_robust_aggregation>`_
Robust Aggregation             Node Similarity Preserving Graph Convolutional Networks                                                          WSDM     2021  [#Jin2021Node]_                `[PDF] <https://arxiv.org/pdf/2011.09643>`_, `[Code] <https://github.com/ChandlerBang/SimP-GCN>`_
Robust Message Passing         Elastic Graph Neural Networks                                                                                    ICML     2021  [#Liu2021Elastic]_             `[PDF] <https://arxiv.org/pdf/2107.06996>`_, `[Code] <https://github.com/lxiaorui/ElasticGNN>`_
Robust Aggregation (Scalable)  Robustness of Graph Neural Networks at Scale                                                                     NeurIPS  2021  [#Geisler2021Robustness]_      `[PDF] <https://arxiv.org/pdf/2110.14038>`_, `[Code] <https://github.com/sigeisler/robustness_of_gnns_at_scale>`_
Structure Refinement           Reliable Representations Make A Stronger Defender: Unsupervised Structure Refinement for Robust GNN              KDD      2022  [#li2022reliable]_             `[PDF] <https://dl.acm.org/doi/pdf/10.1145/3534678.3539484>`_
Robust Spectral Filter         EvenNet: Ignoring Odd-Hop Neighbors Improves Robustness of Graph Neural Networks                                 NeurIPS  2022  [#Lei2022EvenNet]_             `[PDF] <https://arxiv.org/pdf/2205.13892>`_, `[Code] <https://github.com/Leirunlin/EvenNet>`_
Robust Spectral Filter         Robust Mid-Pass Filtering Graph Convolutional Networks                                                           WWW      2023  [#Huang2023Robust]_            `[PDF] <https://arxiv.org/pdf/2302.08048>`_
Adversarial Defense            A Simple and Yet Fairly Effective Defense for Graph Neural Networks                                              AAAI     2024  [#Ennadir2024Simple]_          `[PDF] <https://arxiv.org/pdf/2402.13987>`_, `[Code] <https://github.com/Sennadir/NoisyGNN>`_
Diffusion Purification         Robust Graph Learning Against Adversarial Evasion Attacks via Prior-Free Diffusion-Based Structure Purification  WWW      2025  [#Luo2025Robust]_              `[PDF] <https://arxiv.org/pdf/2502.05000>`_
=============================  ===============================================================================================================  =======  ====  =============================  =========================================================================================================================

3.3. Graph Structure Learning & Learning under Noisy/Weak Information
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Methods that learn, refine, or denoise the graph structure, and that learn under noisy labels, missing attributes, or otherwise weak/incomplete information.

===============================  =================================================================================================  =======  ====  ==========================  ==============================================================================================================
Category                         Paper Title                                                                                        Venue    Year  Ref                         Materials
===============================  =================================================================================================  =======  ====  ==========================  ==============================================================================================================
Structure Learning               Learning Discrete Structures for Graph Neural Networks                                             ICML     2019  [#Franceschi2019Learning]_  `[PDF] <https://arxiv.org/pdf/1903.11960>`_, `[Code] <https://github.com/lucfra/LDS-GNN>`_
Structure Learning               Iterative Deep Graph Learning for Graph Neural Networks: Better and Robust Node Embeddings         NeurIPS  2020  [#Chen2020Iterative]_       `[PDF] <https://arxiv.org/pdf/2006.13009>`_, `[Code] <https://github.com/hugochan/IDGL>`_
Label-Noise Robustness           NRGNN: Learning a Label Noise-Resistant GNN on Sparsely and Noisily Labeled Graphs                 KDD      2021  [#Dai2021NRGNN]_            `[PDF] <https://arxiv.org/pdf/2106.04714>`_, `[Code] <https://github.com/EnyanDai/NRGNN>`_
Unsupervised GSL                 Towards Unsupervised Deep Graph Structure Learning                                                 WWW      2022  [#Liu2022Towards]_          `[PDF] <https://arxiv.org/pdf/2201.06367>`_, `[Code] <https://github.com/TrustAGI-Lab/SUBLIME>`_
Structure Learning (MI)          Compact Graph Structure Learning via Mutual Information Compression                                WWW      2022  [#Liu2022Compact]_          `[PDF] <https://arxiv.org/pdf/2201.05540>`_, `[Code] <https://github.com/liun-online/CoGSL>`_
Attribute Imputation             Initializing Then Refining: A Simple Graph Attribute Imputation Network                            IJCAI    2022  [#tu2022initializing]_      `[PDF] <https://changwangzhang.github.io/files/2022_ijcai_itr.pdf>`_
Label-Noise Robustness           Robust Training of Graph Neural Networks via Noise Governance                                      WSDM     2023  [#Qian2023Robust]_          `[PDF] <https://arxiv.org/pdf/2211.06614>`_, `[Code] <https://github.com/GhostQ99/RobustTrainingGNN>`_
Weak Information                 Learning Strong Graph Neural Networks with Weak Information                                        KDD      2023  [#liu2023learning]_         `[PDF] <https://dl.acm.org/doi/pdf/10.1145/3580305.3599410>`_, `[Code] <https://github.com/yixinliu233/D2PT>`_
Robust Structure Refinement      Self-Guided Robust Graph Structure Refinement                                                      WWW      2024  [#In2024SelfGuided]_        `[PDF] <https://arxiv.org/pdf/2402.11837>`_, `[Code] <https://github.com/yeonjun-in/torch-SG-GSR>`_
Noisy Structure + Missing Attr.  Dilution of Unreliable Information: Learning in Graph with Noisy Structures and Absent Attributes  ICDM     2025  [#li2025dilution]_          `[PDF] <https://ponderly.github.io/pub/RENA_ICDM2025.pdf>`_
===============================  =================================================================================================  =======  ====  ==========================  ==============================================================================================================

3.4. Graph Anomaly Detection
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

============================  =========================================================================================  ====================  ====  =======================  ====================================================================================================================
Category                      Paper Title                                                                                Venue                 Year  Ref                      Materials
============================  =========================================================================================  ====================  ====  =======================  ====================================================================================================================
Reconstruction                Deep Anomaly Detection on Attributed Networks                                              SDM                   2019  [#ding2019deep]_         `[Paper] <https://epubs.siam.org/doi/abs/10.1137/1.9781611975673.67>`_
Fraud Detection               Enhancing Graph Neural Network-based Fraud Detectors against Camouflaged Fraudsters        CIKM                  2020  [#Dou2020Enhancing]_     `[PDF] <https://arxiv.org/pdf/2008.08692>`_, `[Code] <https://github.com/YingtongDou/CARE-GNN>`_
Contrastive (Unsupervised)    Anomaly Detection on Attributed Networks via Contrastive Self-Supervised Learning          IEEE TNNLS            2022  [#liu2021anomaly]_       `[PDF] <https://arxiv.org/pdf/2103.00113>`_
One-class                     One-class Graph Neural Networks for Anomaly Detection in Attributed Networks               Neural Comput. Appl.  2021  [#wang2021one]_          `[PDF] <https://arxiv.org/pdf/2002.09594>`_, `[Code] <https://github.com/WangXuhongCN/OCGNN>`_
Fraud (Imbalance)             Pick and Choose: A GNN-based Imbalanced Learning Approach for Fraud Detection              WWW                   2021  [#Liu2021Pick]_          `[PDF] <https://ponderly.github.io/pub/PCGNN_WWW2021.pdf>`_, `[Code] <https://github.com/PonderLY/PC-GNN>`_
Contrastive (Multi-scale)     ANEMONE: Graph Anomaly Detection with Multi-Scale Contrastive Learning                     CIKM                  2021  [#Jin2021ANEMONE]_       `[Paper] <https://dl.acm.org/doi/10.1145/3459637.3482057>`_, `[Code] <https://github.com/TrustAGI-Lab/ANEMONE>`_
Generative + Contrastive      Generative and Contrastive Self-Supervised Learning for Graph Anomaly Detection            IEEE TKDE             2021  [#Zheng2021Generative]_  `[PDF] <https://arxiv.org/pdf/2108.09896>`_, `[Code] <https://github.com/KimMeen/SL-GAD>`_
Spectral (Supervised)         Rethinking Graph Neural Networks for Anomaly Detection                                     ICML                  2022  [#Tang2022Rethinking]_   `[PDF] <https://arxiv.org/pdf/2205.15508>`_, `[Code] <https://github.com/squareRoot3/Rethinking-Anomaly-Detection>`_
Heterophily-aware             Addressing Heterophily in Graph Anomaly Detection: A Perspective of Graph Spectrum         WWW                   2023  [#Gao2023Addressing]_    `[PDF] <https://blacksingular.github.io/papers/www23-GHRN.pdf>`_, `[Code] <https://github.com/blacksingular/GHRN>`_
Graph-level                   Graph-level Anomaly Detection via Hierarchical Memory Networks                             ECML PKDD             2023  [#niu2023graph]_         `[PDF] <https://arxiv.org/pdf/2307.00755>`_, `[Code] <https://github.com/Niuchx/HimNet>`_
One-class Homophily           Truncated Affinity Maximization: One-class Homophily Modeling for Graph Anomaly Detection  NeurIPS               2023  [#Qiao2023Truncated]_    `[PDF] <https://arxiv.org/pdf/2306.00006>`_, `[Code] <https://github.com/mala-lab/TAM-master>`_
Reconstruction                GAD-NR: Graph Anomaly Detection via Neighborhood Reconstruction                            WSDM                  2024  [#roy2024gad]_           `[PDF] <https://dl.acm.org/doi/pdf/10.1145/3616855.3635767>`_, `[Code] <https://github.com/graph-com/GAD-NR>`_
Semi-supervised (Generative)  Generative Semi-supervised Graph Anomaly Detection                                         NeurIPS               2024  [#Qiao2024Generative]_   `[PDF] <https://arxiv.org/pdf/2402.11887>`_, `[Code] <https://github.com/mala-lab/GGAD>`_
============================  =========================================================================================  ====================  ====  =======================  ====================================================================================================================

3.5. Graph Out-of-Distribution Generalization
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Methods for generalizing GNNs under distribution shift: invariant / causal learning, size shift, environment-based augmentation, test-time adaptation, and surveys.

===========================  ============================================================================================  ==========  ====  ============================  ====================================================================================================================
Category                     Paper Title                                                                                   Venue       Year  Ref                           Materials
===========================  ============================================================================================  ==========  ====  ============================  ====================================================================================================================
Survey                       Out-Of-Distribution Generalization on Graphs: A Survey                                        arXiv       2022  [#Li2022OOD]_                 `[PDF] <https://arxiv.org/pdf/2202.07987>`_
Size Shift                   From Local Structures to Size Generalization in Graph Neural Networks                         ICML        2021  [#Yehudai2021From]_           `[PDF] <https://arxiv.org/pdf/2010.08853>`_
Shift-Robust Training        Shift-Robust GNNs: Overcoming the Limitations of Localized Graph Training Data                NeurIPS     2021  [#Zhu2021Shift]_              `[PDF] <https://arxiv.org/pdf/2108.01099>`_, `[Code] <https://github.com/GentleZhu/Shift-Robust-GNNs>`_
Invariant Learning           Handling Distribution Shifts on Graphs: An Invariance Perspective                             ICLR        2022  [#Wu2022Handling]_            `[PDF] <https://arxiv.org/pdf/2202.02466>`_, `[Code] <https://github.com/qitianwu/GraphOOD-EERM>`_
Invariant Learning           Discovering Invariant Rationales for Graph Neural Networks                                    ICLR        2022  [#Wu2022Discovering]_         `[PDF] <https://arxiv.org/pdf/2201.12872>`_, `[Code] <https://github.com/Wuyxin/DIR-GNN>`_
Invariant / Causal Learning  Learning Causally Invariant Representations for Out-of-Distribution Generalization on Graphs  NeurIPS     2022  [#Chen2022Learning]_          `[PDF] <https://arxiv.org/pdf/2202.05441>`_, `[Code] <https://github.com/LFhase/CIGA>`_
Augmentation (Rationale)     Graph Rationalization with Environment-based Augmentations                                    KDD         2022  [#Liu2022Graph]_              `[PDF] <https://arxiv.org/pdf/2206.02886>`_, `[Code] <https://github.com/liugangcode/GREA>`_
Environment Inference        Learning Substructure Invariance for Out-of-Distribution Molecular Representations            NeurIPS     2022  [#Yang2022Learning]_          `[OpenReview] <https://openreview.net/forum?id=2nWUNTnFijm>`_, `[Code] <https://github.com/yangnianzu0515/MoleOOD>`_
Size Shift                   SizeShiftReg: A Regularization Method for Improving Size-Generalization in GNNs               NeurIPS     2022  [#Buffelli2022SizeShiftReg]_  `[PDF] <https://arxiv.org/pdf/2207.07888>`_, `[Code] <https://github.com/DavideBuffelli/SizeShiftReg>`_
Test-Time Adaptation         Empowering Graph Representation Learning with Test-Time Graph Transformation                  ICLR        2023  [#Jin2023Empowering]_         `[PDF] <https://arxiv.org/pdf/2210.03561>`_, `[Code] <https://github.com/ChandlerBang/GTrans>`_
Causal Stable Learning       Generalizing Graph Neural Networks on Out-of-Distribution Graphs                              IEEE TPAMI  2024  [#Fan2023Generalizing]_       `[PDF] <https://arxiv.org/pdf/2111.10657>`_
Causal Independence          Joint Learning of Label and Environment Causal Independence for Graph OOD Generalization      NeurIPS     2023  [#Gui2023Joint]_              `[PDF] <https://arxiv.org/pdf/2306.01103>`_, `[Code] <https://github.com/divelab/LECI>`_
Invariant Learning (Theory)  Does Invariant Graph Learning via Environment Augmentation Learn Invariance?                  NeurIPS     2023  [#Chen2023Does]_              `[PDF] <https://arxiv.org/pdf/2310.19035>`_, `[Code] <https://github.com/LFhase/GALA>`_
Causal Intervention          Graph Out-of-Distribution Generalization via Causal Intervention                              WWW         2024  [#Wu2024Graph]_               `[PDF] <https://arxiv.org/pdf/2402.11494>`_, `[Code] <https://github.com/fannie1208/CaNet>`_
===========================  ============================================================================================  ==========  ====  ============================  ====================================================================================================================

3.6. Privacy & IP Protection for GNNs
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Broadly **model-level** protection of trained GNN systems: privacy-preserving training/inference, graph reconstruction / link-stealing defense, training-graph protection, and model/IP (watermarking) protection.

==========================================================================================  ===============  ====  ==========================  ====================================================================================================================================
Paper Title                                                                                 Venue            Year  Ref                         Materials
==========================================================================================  ===============  ====  ==========================  ====================================================================================================================================
Locally Private Graph Neural Networks                                                       ACM CCS          2021  [#Sajadmanesh2021Locally]_  `[PDF] <https://arxiv.org/pdf/2006.05535>`_, `[Code] <https://github.com/sisaman/LPGNN>`_
NetFense: Adversarial Defenses Against Privacy Attacks on Neural Networks for Graph Data    IEEE TKDE        2023  [#Hsieh2023NetFense]_       `[PDF] <https://www.computer.org/csdl/journal/tk/2023/01/09448513/1ugDQeDTD3O>`_, `[Code] <https://github.com/ICHproject/NetFense>`_
Releasing Graph Neural Networks with Differential Privacy Guarantees                        TMLR             2023  [#Olatunji2023Releasing]_   `[PDF] <https://arxiv.org/pdf/2109.08907>`_
GAP: Differentially Private Graph Neural Networks with Aggregation Perturbation             USENIX Security  2023  [#Sajadmanesh2023GAP]_      `[PDF] <https://www.usenix.org/system/files/sec23fall-prepub-196-sajadmanesh.pdf>`_, `[Code] <https://github.com/sisaman/GAP>`_
SecGNN: Privacy-Preserving Graph Neural Network Training and Inference as a Cloud Service   IEEE TSC         2023  [#Wang2023SecGNN]_          `[Paper] <https://www.computer.org/csdl/journal/sc/2023/04/10035510/1Krc3O7eDkc>`_
MDP: Privacy-Preserving GNN Based on Matrix Decomposition and Differential Privacy          IEEE JCC         2023  [#Xu2023MDP]_               `[Paper] <https://www.computer.org/csdl/proceedings-article/jcc/2023/285500a038/1Q3JXMAGcM0>`_
On Strengthening and Defending Graph Reconstruction Attack with Markov Chain Approximation  ICML             2023  [#Zhou2023On]_              `[PDF] <https://proceedings.mlr.press/v202/zhou23s/zhou23s.pdf>`_, `[Code] <https://github.com/AndrewZhou924/MC-GRA>`_
Watermarking Graph Neural Networks based on Backdoor Attacks                                IEEE EuroS&P     2023  [#Xu2023Watermarking]_      `[Paper] <https://repository.ubn.ru.nl/handle/2066/295585>`_
OblivGNN: Oblivious Inference on Transductive and Inductive Graph Neural Network            USENIX Security  2024  [#Xu2024OblivGNN]_          `[PDF] <https://www.usenix.org/system/files/usenixsecurity24-xu-zhibo.pdf>`_
GRID: Protecting Training Graph from Link Stealing Attacks on GNN Models                    IEEE S&P         2025  [#Lou2025GRID]_             `[Paper] <https://www.computer.org/csdl/proceedings-article/sp/2025/223600a059/21B7R5azVuM>`_
==========================================================================================  ===============  ====  ==========================  ====================================================================================================================================

----

4. Key Conferences/Workshops/Journals
-------------------------------------

4.1. Conferences & Workshops
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

`ACM International Conference on Knowledge Discovery and Data Mining (SIGKDD) <http://www.kdd.org/conferences>`_.

`ACM International Conference on Management of Data (SIGMOD) <https://sigmod.org/>`_

`The Web Conference (WWW) <https://www2018.thewebconf.org/>`_

`Conference on Neural Information Processing Systems (NeurIPS) <https://neurips.cc/>`_

`International Conference on Machine Learning (ICML) <https://icml.cc/>`_

`International Conference on Learning Representations (ICLR) <https://iclr.cc/>`_

`IEEE International Conference on Data Mining (ICDM) <https://icdm2024.org//>`_

`SIAM International Conference on Data Mining (SDM) <https://www.siam.org/Conferences/CM/Main/sdm19>`_

`IEEE International Conference on Data Engineering (ICDE) <https://icde2018.org/>`_

`ACM InternationalConference on Information and Knowledge Management (CIKM) <http://www.cikmconference.org/>`_

`ACM International Conference on Web Search and Data Mining (WSDM) <http://www.wsdm-conference.org/2018/>`_

`The European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML-PKDD) <http://www.ecmlpkdd2018.org/>`_

`The Pacific-Asia Conference on Knowledge Discovery and Data Mining (PAKDD) <http://pakdd2019.medmeeting.org>`_

`USENIX Security Symposium <https://www.usenix.org/conferences/byname/108>`_

`IEEE Symposium on Security and Privacy (S&P) <https://www.ieee-security.org/TC/SP-Index.html>`_

4.2. Journals
^^^^^^^^^^^^^

`ACM Transactions on Knowledge Discovery from Data (TKDD) <https://tkdd.acm.org/>`_

`IEEE Transactions on Knowledge and Data Engineering (TKDE) <https://www.computer.org/web/tkde>`_

`IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI) <https://www.computer.org/web/tpami>`_

`IEEE Transactions on Neural Networks and Learning Systems (TNNLS) <https://cis.ieee.org/publications/t-neural-networks-and-learning-systems>`_

`Transactions on Machine Learning Research (TMLR) <https://jmlr.org/tmlr/>`_

`ACM SIGKDD Explorations Newsletter <http://www.kdd.org/explorations>`_

`Data Mining and Knowledge Discovery <https://link.springer.com/journal/10618>`_

`Knowledge and Information Systems (KAIS) <https://link.springer.com/journal/10115>`_

----

References
----------

.. [#Zheng2021GRB] Qinkai Zheng, Xu Zou, Yuxiao Dong, Yukuo Cen, Da Yin, Jiarong Xu, Yang Yang, and Jie Tang. 2021. Graph Robustness Benchmark: Benchmarking the Adversarial Robustness of Graph Machine Learning. In *Advances in Neural Information Processing Systems (NeurIPS), Datasets and Benchmarks Track*.
.. [#Gui2022GOOD] Shurui Gui, Xiner Li, Limei Wang, and Shuiwang Ji. 2022. GOOD: A Graph Out-of-Distribution Benchmark. In *Advances in Neural Information Processing Systems (NeurIPS), Datasets and Benchmarks Track*.
.. [#Tang2023GADBench] Jianheng Tang, Fengrui Hua, Ziqi Gao, Peilin Zhao, and Jia Li. 2023. GADBench: Revisiting and Benchmarking Supervised Graph Anomaly Detection. In *Advances in Neural Information Processing Systems (NeurIPS), Datasets and Benchmarks Track*.
.. [#Liu2022BOND] Kay Liu, Yingtong Dou, Yue Zhao, Xueying Ding, Xiyang Hu, Ruitong Zhang, Kaize Ding, Canyu Chen, Hao Peng, Kai Shu, Lichao Sun, Jundong Li, George H. Chen, Zhihao Jia, and Philip S. Yu. 2022. BOND: Benchmarking Unsupervised Outlier Node Detection on Static Attributed Graphs. In *Advances in Neural Information Processing Systems (NeurIPS), Datasets and Benchmarks Track*.
.. [#Zhou2023OpenGSL] Zhiyao Zhou, Sheng Zhou, Bochao Mao, Xuanyi Zhou, Jiawei Chen, Qiaoyu Tan, Daochen Zha, Yan Feng, Chun Chen, and Can Wang. 2023. OpenGSL: A Comprehensive Benchmark for Graph Structure Learning. In *Advances in Neural Information Processing Systems (NeurIPS), Datasets and Benchmarks Track*.
.. [#Hu2020OGB] Weihua Hu, Matthias Fey, Marinka Zitnik, Yuxiao Dong, Hongyu Ren, Bowen Liu, Michele Catasta, and Jure Leskovec. 2020. Open Graph Benchmark: Datasets for Machine Learning on Graphs. In *Advances in Neural Information Processing Systems (NeurIPS)*.
.. [#Mujkanovic2022Are] Felix Mujkanovic, Simon Geisler, Stephan Gunnemann, and Aleksandar Bojchevski. 2022. Are Defenses for Graph Neural Networks Robust? In *Advances in Neural Information Processing Systems (NeurIPS)*.
.. [#Ao2025RobustFinanceTutorial] Xiang Ao, Yang Liu, Guansong Pang, Yuanhao Ding, Hezhe Qiao, Dawei Cheng, and Qing He. 2025. Robust Graph Learning in Finance. In *Proceedings of the 6th ACM International Conference on AI in Finance (ICAIF)*.
.. [#Ao2026RobustGraphTutorial] Xiang Ao, Yang Liu, Guansong Pang, Yuanhao Ding, Hezhe Qiao, Dawei Cheng, and Qing He. 2026. Robust Graph Learning on the Web: Challenges, Methods, and Applications. In *Companion Proceedings of the ACM Web Conference (WWW)*.
.. [#Dai2018Adversarial] Hanjun Dai, Hui Li, Tian Tian, Xin Huang, Lin Wang, Jun Zhu, and Le Song. 2018. Adversarial Attack on Graph Structured Data. In *Proceedings of the 35th International Conference on Machine Learning (ICML)*, 1115-1124.
.. [#Zugner2018Adversarial] Daniel Zugner, Amir Akbarnejad, and Stephan Gunnemann. 2018. Adversarial Attacks on Neural Networks for Graph Data. In *Proceedings of the 24th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (KDD)*, 2847-2856. https://doi.org/10.1145/3219819.3220078.
.. [#Xu2019Topology] Kaidi Xu, Hongge Chen, Sijia Liu, Pin-Yu Chen, Tsui-Wei Weng, Mingyi Hong, and Xue Lin. 2019. Topology Attack and Defense for Graph Neural Networks: An Optimization Perspective. In *Proceedings of the 28th International Joint Conference on Artificial Intelligence (IJCAI)*, 3961-3967.
.. [#Takahashi2019Indirect] Tsubasa Takahashi. 2019. Indirect Adversarial Attacks via Poisoning Neighbors for Graph Convolutional Networks. In *2019 IEEE International Conference on Big Data (Big Data)*, 1395-1400.
.. [#Chang2020Restricted] Heng Chang, Yu Rong, Tingyang Xu, Wenbing Huang, Honglei Zhang, Peng Cui, Wenwu Zhu, and Junzhou Huang. 2020. A Restricted Black-box Adversarial Framework Towards Attacking Graph Embedding Models. In *Proceedings of the AAAI Conference on Artificial Intelligence (AAAI)*, 3389-3396.
.. [#Zang2021Graph] Xiao Zang, Yi Xie, Jie Chen, and Bo Yuan. 2021. Graph Universal Adversarial Attacks: A Few Bad Actors Ruin Graph Learning Models. In *Proceedings of the 30th International Joint Conference on Artificial Intelligence (IJCAI)*, 3328-3334.
.. [#Zugner2019Adversarial] Daniel Zugner and Stephan Gunnemann. 2019. Adversarial Attacks on Graph Neural Networks via Meta Learning. In *International Conference on Learning Representations (ICLR)*.
.. [#Sun2020NIPA] Yiwei Sun, Suhang Wang, Xianfeng Tang, Tsung-Yu Hsieh, and Vasant Honavar. 2020. Adversarial Attacks on Graph Neural Networks via Node Injections: A Hierarchical Reinforcement Learning Approach. In *Proceedings of The Web Conference 2020 (WWW)*, 673-683. https://doi.org/10.1145/3366423.3380149.
.. [#Zou2021TDGIA] Xu Zou, Qinkai Zheng, Yuxiao Dong, Xinyu Guan, Evgeny Kharlamov, Jialiang Lu, and Jie Tang. 2021. TDGIA: Effective Injection Attacks on Graph Neural Networks. In *Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD)*, 2461-2471. https://doi.org/10.1145/3447548.3467314.
.. [#Tao2021Single] Shuchang Tao, Qi Cao, Huawei Shen, Junjie Huang, Yunfan Wu, and Xueqi Cheng. 2021. Single Node Injection Attack against Graph Neural Networks. In *Proceedings of the 30th ACM International Conference on Information and Knowledge Management (CIKM)*, 1794-1803.
.. [#Chen2022Understanding] Yongqiang Chen, Han Yang, Yonggang Zhang, Kaili Ma, Tongliang Liu, Bo Han, and James Cheng. 2022. Understanding and Improving Graph Injection Attack by Promoting Unnoticeability. In *International Conference on Learning Representations (ICLR)*.
.. [#Wang2022Cluster] Zhengyi Wang, Zhongkai Hao, Ziqiao Wang, Hang Su, and Jun Zhu. 2022. Cluster Attack: Query-based Adversarial Attacks on Graphs with Graph-Dependent Priors. In *Proceedings of the 31st International Joint Conference on Artificial Intelligence (IJCAI)*, 768-775.
.. [#Xi2021Graph] Zhaohan Xi, Ren Pang, Shouling Ji, and Ting Wang. 2021. Graph Backdoor. In *30th USENIX Security Symposium (USENIX Security 21)*, 1523-1540.
.. [#Zhang2021Backdoor] Zaixi Zhang, Jinyuan Jia, Binghui Wang, and Neil Zhenqiang Gong. 2021. Backdoor Attacks to Graph Neural Networks. In *Proceedings of the 26th ACM Symposium on Access Control Models and Technologies (SACMAT)*, 15-26. https://doi.org/10.1145/3450569.3463560.
.. [#Dai2023Unnoticeable] Enyan Dai, Minhua Lin, Xiang Zhang, and Suhang Wang. 2023. Unnoticeable Backdoor Attacks on Graph Neural Networks. In *Proceedings of the ACM Web Conference 2023 (WWW)*, 2263-2273. https://doi.org/10.1145/3543507.3583392.
.. [#Ding2025SPEAR] Yuanhao Ding, Yang Liu, Yugang Ji, Weigao Wen, Qing He, and Xiang Ao. 2025. SPEAR: A Structure-Preserving Manipulation Method for Graph Backdoor Attacks. In *Proceedings of the ACM Web Conference 2025 (WWW)*, 1237-1247. https://doi.org/10.1145/3696410.3714665.
.. [#ijcai2019p669] Huijun Wu, Chen Wang, Yuriy Tyshetskiy, Andrew Docherty, Kai Lu, and Liming Zhu. 2019. Adversarial Examples for Graph Data: Deep Insights into Attack and Defense. In *Proceedings of the Twenty-Eighth International Joint Conference on Artificial Intelligence (IJCAI)*, 4816-4823. https://doi.org/10.24963/ijcai.2019/669.
.. [#Zhu2019Robust] Dingyuan Zhu, Ziwei Zhang, Peng Cui, and Wenwu Zhu. 2019. Robust Graph Convolutional Networks Against Adversarial Attacks. In *Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (KDD)*, 1399-1407.
.. [#Zugner2019Certifiable] Daniel Zugner and Stephan Gunnemann. 2019. Certifiable Robustness and Robust Training for Graph Convolutional Networks. In *Proceedings of the 25th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (KDD)*, 246-256.
.. [#Bojchevski2019Certifiable] Aleksandar Bojchevski and Stephan Gunnemann. 2019. Certifiable Robustness to Graph Perturbations. In *Advances in Neural Information Processing Systems (NeurIPS)*.
.. [#entezari2020all] Negin Entezari, Saba A. Al-Sayouri, Amirali Darvishzadeh, and Evangelos E. Papalexakis. 2020. All You Need Is Low (Rank): Defending Against Adversarial Attacks on Graphs. In *Proceedings of the 13th ACM International Conference on Web Search and Data Mining (WSDM)*, 169-177.
.. [#Bojchevski2020Efficient] Aleksandar Bojchevski, Johannes Klicpera, and Stephan Gunnemann. 2020. Efficient Robustness Certificates for Discrete Data: Sparsity-Aware Randomized Smoothing for Graphs, Images and More. In *Proceedings of the 37th International Conference on Machine Learning (ICML)*, 1003-1013.
.. [#jin2020graph] Wei Jin, Yao Ma, Xiaorui Liu, Xianfeng Tang, Suhang Wang, and Jiliang Tang. 2020. Graph Structure Learning for Robust Graph Neural Networks. In *Proceedings of the 26th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD)*, 66-74.
.. [#Zhang2020GNNGuard] Xiang Zhang and Marinka Zitnik. 2020. GNNGuard: Defending Graph Neural Networks against Adversarial Attacks. In *Advances in Neural Information Processing Systems (NeurIPS)*.
.. [#Geisler2020Reliable] Simon Geisler, Daniel Zugner, and Stephan Gunnemann. 2020. Reliable Graph Neural Networks via Robust Aggregation. In *Advances in Neural Information Processing Systems (NeurIPS)*.
.. [#Jin2021Node] Wei Jin, Tyler Derr, Yiqi Wang, Yao Ma, Zitao Liu, and Jiliang Tang. 2021. Node Similarity Preserving Graph Convolutional Networks. In *Proceedings of the 14th ACM International Conference on Web Search and Data Mining (WSDM)*, 148-156.
.. [#Liu2021Elastic] Xiaorui Liu, Wei Jin, Yao Ma, Yaxin Li, Hua Liu, Yiqi Wang, Ming Yan, and Jiliang Tang. 2021. Elastic Graph Neural Networks. In *Proceedings of the 38th International Conference on Machine Learning (ICML)*, 6837-6849.
.. [#Geisler2021Robustness] Simon Geisler, Tobias Schmidt, Hakan Sirin, Daniel Zugner, Aleksandar Bojchevski, and Stephan Gunnemann. 2021. Robustness of Graph Neural Networks at Scale. In *Advances in Neural Information Processing Systems (NeurIPS)*.
.. [#li2022reliable] Kuan Li, Yang Liu, Xiang Ao, Jianfeng Chi, Jinghua Feng, Hao Yang, and Qing He. 2022. Reliable Representations Make A Stronger Defender: Unsupervised Structure Refinement for Robust GNN. In *Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD)*, 925-935.
.. [#Lei2022EvenNet] Runlin Lei, Zhen Wang, Yaliang Li, Bolin Ding, and Zhewei Wei. 2022. EvenNet: Ignoring Odd-Hop Neighbors Improves Robustness of Graph Neural Networks. In *Advances in Neural Information Processing Systems (NeurIPS)*.
.. [#Huang2023Robust] Jincheng Huang, Lun Du, Xu Chen, Qiang Fu, Shi Han, and Dongmei Zhang. 2023. Robust Mid-Pass Filtering Graph Convolutional Networks. In *Proceedings of the ACM Web Conference 2023 (WWW)*, 328-338.
.. [#Ennadir2024Simple] Sofiane Ennadir, Yassine Abbahaddou, Johannes F. Lutzeyer, Michalis Vazirgiannis, and Henrik Bostrom. 2024. A Simple and Yet Fairly Effective Defense for Graph Neural Networks. In *Proceedings of the AAAI Conference on Artificial Intelligence (AAAI)*, 21063-21071.
.. [#Luo2025Robust] Jiayi Luo, Qingyun Sun, Haonan Yuan, Xingcheng Fu, and Jianxin Li. 2025. Robust Graph Learning Against Adversarial Evasion Attacks via Prior-Free Diffusion-Based Structure Purification. In *Proceedings of the ACM Web Conference 2025 (WWW)*.
.. [#Franceschi2019Learning] Luca Franceschi, Mathias Niepert, Massimiliano Pontil, and Xiao He. 2019. Learning Discrete Structures for Graph Neural Networks. In *Proceedings of the 36th International Conference on Machine Learning (ICML)*, 1972-1982.
.. [#Chen2020Iterative] Yu Chen, Lingfei Wu, and Mohammed J. Zaki. 2020. Iterative Deep Graph Learning for Graph Neural Networks: Better and Robust Node Embeddings. In *Advances in Neural Information Processing Systems (NeurIPS)*.
.. [#Dai2021NRGNN] Enyan Dai, Charu Aggarwal, and Suhang Wang. 2021. NRGNN: Learning a Label Noise Resistant Graph Neural Network on Sparsely and Noisily Labeled Graphs. In *Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery & Data Mining (KDD)*, 227-236.
.. [#Liu2022Towards] Yixin Liu, Yu Zheng, Daokun Zhang, Hongxu Chen, Hao Peng, and Shirui Pan. 2022. Towards Unsupervised Deep Graph Structure Learning. In *Proceedings of the ACM Web Conference 2022 (WWW)*, 1392-1403.
.. [#Liu2022Compact] Nian Liu, Xiao Wang, Lingfei Wu, Yu Chen, Xiaojie Guo, and Chuan Shi. 2022. Compact Graph Structure Learning via Mutual Information Compression. In *Proceedings of the ACM Web Conference 2022 (WWW)*, 1601-1610.
.. [#tu2022initializing] Wenxuan Tu, Sihang Zhou, Xinwang Liu, Yue Liu, Zhiping Cai, En Zhu, Changwang Zhang, and Jieren Cheng. 2022. Initializing Then Refining: A Simple Graph Attribute Imputation Network. In *Proceedings of the International Joint Conference on Artificial Intelligence (IJCAI)*, 3494-3500.
.. [#Qian2023Robust] Siyi Qian, Haochao Ying, Renjun Hu, Jingbo Zhou, Jintai Chen, Danny Z. Chen, and Jian Wu. 2023. Robust Training of Graph Neural Networks via Noise Governance. In *Proceedings of the 16th ACM International Conference on Web Search and Data Mining (WSDM)*, 607-615.
.. [#liu2023learning] Yixin Liu, Kaize Ding, Jianling Wang, Vincent Lee, Huan Liu, and Shirui Pan. 2023. Learning Strong Graph Neural Networks with Weak Information. In *Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD)*, 1559-1571.
.. [#In2024SelfGuided] Yeonjun In, Kanghoon Yoon, Kibum Kim, Kijung Shin, and Chanyoung Park. 2024. Self-Guided Robust Graph Structure Refinement. In *Proceedings of the ACM Web Conference 2024 (WWW)*, 697-708.
.. [#li2025dilution] Xinxin Li, Yang Liu, Siyong Xu, Weigao Wen, Qing He, and Xiang Ao. 2025. Dilution of Unreliable Information: Learning in Graph with Noisy Structures and Absent Attributes. In *Proceedings of the IEEE International Conference on Data Mining (ICDM)*, 1360-1369.
.. [#ding2019deep] Kaize Ding, Jundong Li, Rohit Bhanushali, and Huan Liu. 2019. Deep Anomaly Detection on Attributed Networks. In *Proceedings of the 2019 SIAM International Conference on Data Mining (SDM)*, 594-602. https://doi.org/10.1137/1.9781611975673.67.
.. [#Dou2020Enhancing] Yingtong Dou, Zhiwei Liu, Li Sun, Yutong Deng, Hao Peng, and Philip S. Yu. 2020. Enhancing Graph Neural Network-based Fraud Detectors against Camouflaged Fraudsters. In *Proceedings of the 29th ACM International Conference on Information and Knowledge Management (CIKM)*, 315-324.
.. [#liu2021anomaly] Yixin Liu, Zhao Li, Shirui Pan, Chen Gong, Chuan Zhou, and George Karypis. 2022. Anomaly Detection on Attributed Networks via Contrastive Self-Supervised Learning. *IEEE Transactions on Neural Networks and Learning Systems (TNNLS)*, 33(6), 2378-2392.
.. [#wang2021one] Xuhong Wang, Baihong Jin, Ying Du, Ping Cui, Yingshui Tan, and Yupu Yang. 2021. One-class Graph Neural Networks for Anomaly Detection in Attributed Networks. *Neural Computing and Applications*, 33(18), 12073-12085.
.. [#Liu2021Pick] Yang Liu, Xiang Ao, Zidi Qin, Jianfeng Chi, Jinghua Feng, Hao Yang, and Qing He. 2021. Pick and Choose: A GNN-based Imbalanced Learning Approach for Fraud Detection. In *Proceedings of the Web Conference 2021 (WWW)*, 3168-3177.
.. [#Jin2021ANEMONE] Ming Jin, Yixin Liu, Yu Zheng, Lianhua Chi, Yuan-Fang Li, and Shirui Pan. 2021. ANEMONE: Graph Anomaly Detection with Multi-Scale Contrastive Learning. In *Proceedings of the 30th ACM International Conference on Information and Knowledge Management (CIKM)*, 3122-3126.
.. [#Zheng2021Generative] Yu Zheng, Ming Jin, Yixin Liu, Lianhua Chi, Khoa T. Phan, and Yi-Ping Phoebe Chen. 2021. Generative and Contrastive Self-Supervised Learning for Graph Anomaly Detection. *IEEE Transactions on Knowledge and Data Engineering (TKDE)*.
.. [#Tang2022Rethinking] Jianheng Tang, Jiajin Li, Ziqi Gao, and Jia Li. 2022. Rethinking Graph Neural Networks for Anomaly Detection. In *Proceedings of the 39th International Conference on Machine Learning (ICML)*, 21076-21089.
.. [#Gao2023Addressing] Yuan Gao, Xiang Wang, Xiangnan He, Zhenguang Liu, Huamin Feng, and Yongdong Zhang. 2023. Addressing Heterophily in Graph Anomaly Detection: A Perspective of Graph Spectrum. In *Proceedings of the ACM Web Conference 2023 (WWW)*, 1528-1538.
.. [#niu2023graph] Chaoxi Niu, Guansong Pang, and Ling Chen. 2023. Graph-level Anomaly Detection via Hierarchical Memory Networks. In *Joint European Conference on Machine Learning and Knowledge Discovery in Databases (ECML PKDD)*, 201-218.
.. [#Qiao2023Truncated] Hezhe Qiao and Guansong Pang. 2023. Truncated Affinity Maximization: One-class Homophily Modeling for Graph Anomaly Detection. In *Advances in Neural Information Processing Systems (NeurIPS)*.
.. [#roy2024gad] Amit Roy, Juan Shu, Jia Li, Carl Yang, Olivier Elshocht, Jeroen Smeets, and Pan Li. 2024. GAD-NR: Graph Anomaly Detection via Neighborhood Reconstruction. In *Proceedings of the 17th ACM International Conference on Web Search and Data Mining (WSDM)*, 576-585.
.. [#Qiao2024Generative] Hezhe Qiao, Qingsong Wen, Xiaoli Li, Ee-Peng Lim, and Guansong Pang. 2024. Generative Semi-supervised Graph Anomaly Detection. In *Advances in Neural Information Processing Systems (NeurIPS)*.
.. [#Li2022OOD] Haoyang Li, Xin Wang, Ziwei Zhang, and Wenwu Zhu. 2022. Out-Of-Distribution Generalization on Graphs: A Survey. *arXiv preprint arXiv:2202.07987*.
.. [#Yehudai2021From] Gilad Yehudai, Ethan Fetaya, Eli Meirom, Gal Chechik, and Haggai Maron. 2021. From Local Structures to Size Generalization in Graph Neural Networks. In *Proceedings of the 38th International Conference on Machine Learning (ICML)*, 11975-11986.
.. [#Zhu2021Shift] Qi Zhu, Natalia Ponomareva, Jiawei Han, and Bryan Perozzi. 2021. Shift-Robust GNNs: Overcoming the Limitations of Localized Graph Training Data. In *Advances in Neural Information Processing Systems (NeurIPS)*.
.. [#Wu2022Handling] Qitian Wu, Hengrui Zhang, Junchi Yan, and David Wipf. 2022. Handling Distribution Shifts on Graphs: An Invariance Perspective. In *International Conference on Learning Representations (ICLR)*.
.. [#Wu2022Discovering] Ying-Xin Wu, Xiang Wang, An Zhang, Xiangnan He, and Tat-Seng Chua. 2022. Discovering Invariant Rationales for Graph Neural Networks. In *International Conference on Learning Representations (ICLR)*.
.. [#Chen2022Learning] Yongqiang Chen, Yonggang Zhang, Yatao Bian, Han Yang, Kaili Ma, Binghui Xie, Tongliang Liu, Bo Han, and James Cheng. 2022. Learning Causally Invariant Representations for Out-of-Distribution Generalization on Graphs. In *Advances in Neural Information Processing Systems (NeurIPS)*.
.. [#Liu2022Graph] Gang Liu, Tong Zhao, Jiaxin Xu, Tengfei Luo, and Meng Jiang. 2022. Graph Rationalization with Environment-based Augmentations. In *Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery & Data Mining (KDD)*, 1069-1078.
.. [#Yang2022Learning] Nianzu Yang, Kaipeng Zeng, Qitian Wu, Xiaosong Jia, and Junchi Yan. 2022. Learning Substructure Invariance for Out-of-Distribution Molecular Representations. In *Advances in Neural Information Processing Systems (NeurIPS)*.
.. [#Buffelli2022SizeShiftReg] Davide Buffelli, Pietro Lio, and Fabio Vandin. 2022. SizeShiftReg: A Regularization Method for Improving Size-Generalization in Graph Neural Networks. In *Advances in Neural Information Processing Systems (NeurIPS)*.
.. [#Jin2023Empowering] Wei Jin, Tong Zhao, Jiayuan Ding, Yozen Liu, Jiliang Tang, and Neil Shah. 2023. Empowering Graph Representation Learning with Test-Time Graph Transformation. In *International Conference on Learning Representations (ICLR)*.
.. [#Fan2023Generalizing] Shaohua Fan, Xiao Wang, Chuan Shi, Peng Cui, and Bai Wang. 2024. Generalizing Graph Neural Networks on Out-of-Distribution Graphs. *IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)*, 46(1), 322-337.
.. [#Gui2023Joint] Shurui Gui, Meng Liu, Xiner Li, Youzhi Luo, and Shuiwang Ji. 2023. Joint Learning of Label and Environment Causal Independence for Graph Out-of-Distribution Generalization. In *Advances in Neural Information Processing Systems (NeurIPS)*.
.. [#Chen2023Does] Yongqiang Chen, Yatao Bian, Kaiwen Zhou, Binghui Xie, Bo Han, and James Cheng. 2023. Does Invariant Graph Learning via Environment Augmentation Learn Invariance? In *Advances in Neural Information Processing Systems (NeurIPS)*.
.. [#Wu2024Graph] Qitian Wu, Fan Nie, Chenxiao Yang, Tianyi Bao, and Junchi Yan. 2024. Graph Out-of-Distribution Generalization via Causal Intervention. In *Proceedings of the ACM Web Conference 2024 (WWW)*, 850-860.
.. [#Sajadmanesh2021Locally] Sina Sajadmanesh and Daniel Gatica-Perez. 2021. Locally Private Graph Neural Networks. In *Proceedings of the 2021 ACM SIGSAC Conference on Computer and Communications Security (CCS)*, 2130-2145.
.. [#Hsieh2023NetFense] I-Chung Hsieh and Cheng-Te Li. 2023. NetFense: Adversarial Defenses Against Privacy Attacks on Neural Networks for Graph Data. *IEEE Transactions on Knowledge and Data Engineering (TKDE)*, 35(1), 796-809.
.. [#Olatunji2023Releasing] Iyiola E. Olatunji, Thorben Funke, and Megha Khosla. 2023. Releasing Graph Neural Networks with Differential Privacy Guarantees. *Transactions on Machine Learning Research (TMLR)*.
.. [#Sajadmanesh2023GAP] Sina Sajadmanesh, Ali Shahin Shamsabadi, Aurelien Bellet, and Daniel Gatica-Perez. 2023. GAP: Differentially Private Graph Neural Networks with Aggregation Perturbation. In *32nd USENIX Security Symposium (USENIX Security 23)*, 3223-3240.
.. [#Wang2023SecGNN] Songlei Wang, Yifeng Zheng, and Xiaohua Jia. 2023. SecGNN: Privacy-Preserving Graph Neural Network Training and Inference as a Cloud Service. *IEEE Transactions on Services Computing (TSC)*, 16(4), 2923-2938.
.. [#Xu2023MDP] Wanghan Xu, Bin Shi, Jiqiang Zhang, Zhiyuan Feng, Tianze Pan, and Bo Dong. 2023. MDP: Privacy-Preserving GNN Based on Matrix Decomposition and Differential Privacy. In *2023 IEEE 14th International Conference on Joint Cloud Computing (JCC)*, 38-45.
.. [#Zhou2023On] Zhanke Zhou, Chenyu Zhou, Xuan Li, Jiangchao Yao, Quanming Yao, and Bo Han. 2023. On Strengthening and Defending Graph Reconstruction Attack with Markov Chain Approximation. In *Proceedings of the 40th International Conference on Machine Learning (ICML)*, 42843-42877.
.. [#Xu2023Watermarking] Jing Xu, Stjepan Koffas, Oguzhan Ersoy, and Stjepan Picek. 2023. Watermarking Graph Neural Networks based on Backdoor Attacks. In *2023 IEEE 8th European Symposium on Security and Privacy (EuroS&P)*, 1179-1197.
.. [#Xu2024OblivGNN] Zhibo Xu, Shangqi Lai, Xiaoning Liu, Alsharif Abuadbba, Xingliang Yuan, and Xun Yi. 2024. OblivGNN: Oblivious Inference on Transductive and Inductive Graph Neural Network. In *33rd USENIX Security Symposium (USENIX Security 24)*, 2209-2226.
.. [#Lou2025GRID] Jiacheng Lou, Xiaoyu Zhang, Rui Zhang, Xingliang Yuan, Neil Zhenqiang Gong, and Nian-Feng Tzeng. 2025. GRID: Protecting Training Graph from Link Stealing Attacks on GNN Models. In *2025 IEEE Symposium on Security and Privacy (S&P)*, 2095-2113.
