Awesome Robust Graph Learning Resources
====================================

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

* `3. Papers <#3-papers>`_

  * `3.1. Graph Adversarial Attack <#31-graph-adversarial-attack>`_
  * `3.2. Graph Adversarial Defense <#32-graph-adversarial-defense>`_

* `4. Key Conferences/Workshops/Journals <#4-key-conferencesworkshopsjournals>`_

  * `4.1. Conferences & Workshops <#41-conferences--workshops>`_
  * `4.2. Journals <#42-journals>`_
-----------

1. Tutorials & Benchmarks
---------------------------------

1.1. Benchmarks
^^^^^^^^^^^^^^^


=============  =================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Data Types     Paper Title                                                                                        Venue                         Year   Ref                           Materials
=============  =================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Graph          Graph Robustness Benchmark: Benchmarking the Adversarial Robustness of Graph Machine Learning      NeurIPS                       2021   [#Zhu2021GRB]_                `[PDF] <https://arxiv.org/pdf/2111.04314>`_, `[Code] <https://cogdl.ai/grb/home>`_

=============  =================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================


1.2. Tutorials
^^^^^^^^^^^^^^

=============================================================================== ============================================  =====  ==============================  ==========================================================================================================================================================================
Tutorial Title                                                                  Venue                                         Year   Ref                             Materials
=============================================================================== ============================================  =====  ==============================  ==========================================================================================================================================================================
Robust Graph Learning on the Web: Challenges, Methods, and Applications         WWW                                           2026   [#Ao2026RobustGraphTutorial]_   `[HTML] <https://qwer12191.github.io/Robust-Graph-Learning-on-Web/>`_

=============================================================================== ============================================  =====  ==============================  ==========================================================================================================================================================================



----

2. Toolbox & Datasets
---------------------


----


3. Papers
---------


3.1. Graph Adversarial Attack
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

=====================================================================================  =======  ====  ===========================  ====================================================================================================================================
Paper Title                                                                            Venue    Year  Ref                          Materials                                                                                                                           
=====================================================================================  =======  ====  ===========================  ====================================================================================================================================
Adversarial Attacks on Neural Networks for Graph Data                                  KDD      2018  [#Zugner2018Adversarial]_    `[PDF] <https://arxiv.org/pdf/1805.07984>`_, `[Code] <https://github.com/danielzuegner/nettack>`_                                   
Indirect Adversarial Attacks via Poisoning Neighbors for Graph Convolutional Networks  BigData  2019  [#Takahashi2019Indirect]_    `[PDF] <https://arxiv.org/pdf/2002.08012>`_, Code: N/A                                                                              
TDGIA: Effective Injection Attacks on Graph Neural Networks                            KDD      2021  [#Zou2021TDGIA]_             `[PDF] <https://keg.cs.tsinghua.edu.cn/jietang/publications/KDD21-Zou-et-al-TDGIA.pdf>`_, `[Code] <https://github.com/THUDM/tdgia>`_
Adversarial Attacks on Graph Neural Networks via Meta Learning                         ICLR     2019  [#Zugner2019Adversarial]_    `[PDF] <https://openreview.net/pdf?id=Bylnx209YX>`_, `[Code] <https://github.com/danielzuegner/gnn-meta-attack>`_                   
Backdoor Attacks to Graph Neural Networks                                              SACMAT   2021  [#Zhang2021Backdoor]_        `[PDF] <https://arxiv.org/pdf/2006.11165>`_, `[Code] <https://github.com/zaixizhang/graphbackdoor>`_                                
Unnoticeable Backdoor Attacks on Graph Neural Networks                                 WWW      2023  [#Dai2023Unnoticeable]_      `[PDF] <https://arxiv.org/pdf/2303.01263>`_, `[Code] <https://github.com/ventr1c/UGBA>`_                                            
SPEAR: A Structure-Preserving Manipulation Method for Graph Backdoor Attacks           WWW      2025  [#Ding2025SPEAR]_            `[PDF] <https://ponderly.github.io/pub/SPEAR_WWW2025.pdf>`_, `[Code] <https://github.com/yhDing/SPEAR>`_                            
=====================================================================================  =======  ====  ===========================  ====================================================================================================================================
.. note:: For PoisonProbe, I did not find a public official code repository during verification, so the code field is marked as ``N/A``.



3.2. Graph Adversarial Defense
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The following papers are filtered as **broadly model-level defense** works. The scope here is intentionally relaxed: besides strict model-level privacy defenses, we also include papers on privacy-preserving GNN training/inference, graph reconstruction defense, training-graph protection, and model/IP protection mechanisms that are closely related to defending trained GNN systems.

====================================================================================================   ============================  =====  =============================  ============================================================================================================================================================================================================================================================
Paper Title                                                                                            Venue                         Year   Ref                            Materials
====================================================================================================   ============================  =====  =============================  ============================================================================================================================================================================================================================================================
NetFense: Adversarial Defenses against Privacy Attacks on Neural Networks for Graph Data               IEEE TKDE                     2023   [#Hsieh2023NetFense]_          `[PDF] <https://www.computer.org/csdl/journal/tk/2023/01/09448513/1ugDQeDTD3O>`_, `[Code] <https://github.com/ICHproject/NetFense>`_
Locally Private Graph Neural Networks                                                                  ACM CCS                       2021   [#Sajadmanesh2021Locally]_     `[PDF] <https://arxiv.org/pdf/2006.05535>`_, `[Code] <https://github.com/sisaman/LPGNN>`_
Releasing Graph Neural Networks with Differential Privacy Guarantees                                   AISec Workshop                2021   [#Olatunji2021Releasing]_      `[PDF] <https://arxiv.org/pdf/2109.08907>`_
GAP: Differentially Private Graph Neural Networks with Aggregation Perturbation                        USENIX Security               2023   [#Sajadmanesh2023GAP]_         `[PDF] <https://www.usenix.org/system/files/sec23fall-prepub-196-sajadmanesh.pdf>`_, `[Code] <https://github.com/sisaman/GAP>`_
SecGNN: Privacy-Preserving Graph Neural Network Training and Inference as a Cloud Service              IEEE TSC                      2023   [#Wang2023SecGNN]_             `[Paper] <https://www.computer.org/csdl/journal/sc/2023/04/10035510/1Krc3O7eDkc>`_
MDP: Privacy-Preserving GNN Based on Matrix Decomposition and Differential Privacy                     IEEE JCC                      2023   [#Xu2023MDP]_                  `[Paper] <https://www.computer.org/csdl/proceedings-article/jcc/2023/285500a038/1Q3JXMAGcM0>`_
On Strengthening and Defending Graph Reconstruction Attack with Markov Chain Approximation             ICML                          2023   [#Zhou2023On]_                 `[PDF] <https://proceedings.mlr.press/v202/zhou23s/zhou23s.pdf>`_, `[Code] <https://github.com/AndrewZhou924/MC-GRA>`_
OblivGNN: Oblivious Inference on Transductive and Inductive Graph Neural Networks                      USENIX Security               2024   [#Xu2024OblivGNN]_             `[PDF] <https://www.usenix.org/system/files/usenixsecurity24-xu-zhibo.pdf>`_
GRID: Protecting Training Graph from Link Stealing Attacks on GNN Models                               IEEE S&P                      2025   [#Lou2025GRID]_                `[Paper] <https://www.computer.org/csdl/proceedings-article/sp/2025/223600a059/21B7R5azVuM>`_
Watermarking Graph Neural Networks based on Backdoor Attacks                                           IEEE EuroS&P                  2023   [#Xu2023Watermarking]_         `[Paper] <https://repository.ubn.ru.nl/handle/2066/295585>`_
Deep anomaly detection on attributed networks                                                          SDM                           2019   [#ding2019deep]_               `[Paper] <https://epubs.siam.org/doi/abs/10.1137/1.9781611975673.67>`_
Graph-level anomaly detection via hierarchical memory networks                                         ECML PKDD                     2023   [#niu2023graph]_               `[PDF] <https://arxiv.org/pdf/2307.00755>`_, `[Code] <https://github.com/Niuchx/HimNet>`_
Gad-nr: Graph anomaly detection via neighborhood reconstruction                                        WSDM                          2024   [#roy2024gad]_                 `[PDF] <https://dl.acm.org/doi/pdf/10.1145/3616855.3635767>`_, `[Code] <https://github.com/graph-com/GAD-NR>`_
Anomaly Detection on Attributed Networks via Contrastive Self-Supervised Learning                      IEEE TNNLS                    2021   [#liu2021anomaly]_             `[PDF] <https://arxiv.org/pdf/2103.00113>`_
One-class graph neural networks for anomaly detection in attributed networks                           Neurcomputing                 2021   [#wang2021one]_                `[PDF] <https://arxiv.org/pdf/2002.09594>`_, `[Code] <https://github.com/WangXuhongCN/OCGNN>`_
Adversarial Examples on Graph Data: Deep Insights into Attack and Defense                              IJCAI                         2019   [#ijcai2019p669]_              `[PDF] <https://arxiv.org/pdf/1903.01610>`_
All you need is low (rank) defending against adversarial attacks on graphs                             WSDM                          2020   [#entezari2020all]_            `[PDF] <https://dl.acm.org/doi/pdf/10.1145/3336191.3371789>`_
Graph structure learning for robust graph neural networks                                              KDD                           2020   [#jin2020graph]_               `[PDF] <https://dl.acm.org/doi/pdf/10.1145/3394486.3403049>`_, `[Code] <https://github.com/ChandlerBang/Pro-GNN>`_
Reliable Representations Make A Stronger Defender: Unsupervised Structure Refinement for Robust GNN    KDD                           2022   [#li2022reliable]_             `[PDF] <https://dl.acm.org/doi/pdf/10.1145/3534678.3539484>`_
Initializing Then Refining: A Simple Graph Attribute Imputation Network                                IJCAI                         2022   [#tu2022initializing]_         `[PDF] <https://changwangzhang.github.io/files/2022_ijcai_itr.pdf>`_
Dilution of Unreliable Information: Learning in Graph with Noisy Structures and Absent Attributes      ICDM                          2025   [#li2025dilution]_             `[PDF] <https://ponderly.github.io/pub/RENA_ICDM2025.pdf>`_
Learning Strong Graph Neural Networks with Weak Information                                            KDD                           2023   [#liu2023learning]_            `[PDF] <https://dl.acm.org/doi/pdf/10.1145/3580305.3599410>`_, `[Code] <https://github.com/yixinliu233/D2PT>`_
====================================================================================================   ============================  =====  =============================  ============================================================================================================================================================================================================================================================




----

4. Key Conferences/Workshops/Journals
-------------------------------------

4.1. Conferences & Workshops
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

`ACM International Conference on Knowledge Discovery and Data Mining (SIGKDD) <http://www.kdd.org/conferences>`_. 

`ACM International Conference on Management of Data (SIGMOD) <https://sigmod.org/>`_

`The Web Conference (WWW) <https://www2018.thewebconf.org/>`_

`IEEE International Conference on Data Mining (ICDM) <https://icdm2024.org//>`_

`SIAM International Conference on Data Mining (SDM) <https://www.siam.org/Conferences/CM/Main/sdm19>`_

`IEEE International Conference on Data Engineering (ICDE) <https://icde2018.org/>`_

`ACM InternationalConference on Information and Knowledge Management (CIKM) <http://www.cikmconference.org/>`_

`ACM International Conference on Web Search and Data Mining (WSDM) <http://www.wsdm-conference.org/2018/>`_

`The European Conference on Machine Learning and Principles and Practice of Knowledge Discovery in Databases (ECML-PKDD) <http://www.ecmlpkdd2018.org/>`_

`The Pacific-Asia Conference on Knowledge Discovery and Data Mining (PAKDD) <http://pakdd2019.medmeeting.org>`_

4.2. Journals
^^^^^^^^^^^^^

`ACM Transactions on Knowledge Discovery from Data (TKDD) <https://tkdd.acm.org/>`_

`IEEE Transactions on Knowledge and Data Engineering (TKDE) <https://www.computer.org/web/tkde>`_

`ACM SIGKDD Explorations Newsletter <http://www.kdd.org/explorations>`_

`Data Mining and Knowledge Discovery <https://link.springer.com/journal/10618>`_

`Knowledge and Information Systems (KAIS) <https://link.springer.com/journal/10115>`_

----

References
----------

.. [#Zhu2021GRB] Deyu Zhu, Qinkai Zheng, Yang Liu. 2021. Graph Robustness Benchmark: Benchmarking the Adversarial Robustness of Graph Machine Learning. In *Advances in Neural Information Processing Systems (NeurIPS)*.

.. [#Ao2026RobustGraphTutorial] Xiang Ao, Yang Liu, Guansong Pang, Yuanhao Ding, Hezhe Qiao, Dawei Cheng, and Qing He. 2026. Robust Graph Learning on the Web: Challenges, Methods, and Applications. In *Companion Proceedings of the ACM Web Conference (WWW)*.

.. [#Zugner2018Adversarial] Daniel Zügner, Amir Akbarnejad, and Stephan Günnemann. 2018. Adversarial Attacks on Neural Networks for Graph Data. In *Proceedings of the 24th ACM SIGKDD International Conference on Knowledge Discovery & Data Mining (KDD)*, 2847–2856. https://doi.org/10.1145/3219819.3220078.

.. [#Takahashi2019Indirect] Tsubasa Takahashi. 2019. Indirect Adversarial Attacks via Poisoning Neighbors for Graph Convolutional Networks. In *2019 IEEE International Conference on Big Data (Big Data)*, 1395–1400.

.. [#Zou2021TDGIA] Xu Zou, Qinkai Zheng, Yuxiao Dong, Xinyu Guan, Evgeny Kharlamov, Jialiang Lu, and Jie Tang. 2021. TDGIA: Effective Injection Attacks on Graph Neural Networks. In *Proceedings of the 27th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD)*, 2461–2471. https://doi.org/10.1145/3447548.3467314.

.. [#Zugner2019Adversarial] Daniel Zügner and Stephan Günnemann. 2019. Adversarial Attacks on Graph Neural Networks via Meta Learning. In *International Conference on Learning Representations (ICLR)*.

.. [#Zhang2021Backdoor] Zaixi Zhang, Jinyuan Jia, Binghui Wang, and Neil Zhenqiang Gong. 2021. Backdoor Attacks to Graph Neural Networks. In *Proceedings of the 26th ACM Symposium on Access Control Models and Technologies (SACMAT)*, 15–26. https://doi.org/10.1145/3450569.3463560.

.. [#Dai2023Unnoticeable] Enyan Dai, Minhua Lin, Xiang Zhang, and Suhang Wang. 2023. Unnoticeable Backdoor Attacks on Graph Neural Networks. In *Proceedings of the ACM Web Conference 2023 (WWW)*, 2263–2273. https://doi.org/10.1145/3543507.3583392.

.. [#Ding2025SPEAR] Yuanhao Ding, Yang Liu, Yugang Ji, Weigao Wen, Qing He, and Xiang Ao. 2025. SPEAR: A Structure-Preserving Manipulation Method for Graph Backdoor Attacks. In *Proceedings of the ACM Web Conference 2025 (WWW)*, 1237–1247. https://doi.org/10.1145/3696410.3714665.

.. [#Hsieh2023NetFense] Hsieh, I.-C. and Li, C.-T., 2023. NetFense: Adversarial Defenses against Privacy Attacks on Neural Networks for Graph Data. *IEEE Transactions on Knowledge and Data Engineering*\ , 35(1), pp.796-809.

.. [#Sajadmanesh2021Locally] Sajadmanesh, S. and Gatica-Perez, D., 2021. Locally Private Graph Neural Networks. In *Proceedings of the 2021 ACM SIGSAC Conference on Computer and Communications Security*, pp.2130-2145.

.. [#Olatunji2021Releasing] Olatunji, I.E., Nejdl, W. and Khosla, M., 2021. Releasing Graph Neural Networks with Differential Privacy Guarantees. In *Proceedings of the 14th ACM Workshop on Artificial Intelligence and Security*, pp.31-40.

.. [#Sajadmanesh2023GAP] Sajadmanesh, S., Shamsabadi, A.S., Bellet, A. and Gatica-Perez, D., 2023. GAP: Differentially Private Graph Neural Networks with Aggregation Perturbation. In *32nd USENIX Security Symposium (USENIX Security 23)*, pp.3223-3240.

.. [#Wang2023SecGNN] Wang, S., Zheng, Y. and Jia, X., 2023. SecGNN: Privacy-Preserving Graph Neural Network Training and Inference as a Cloud Service. *IEEE Transactions on Services Computing*\ , 16(4), pp.2923-2938.

.. [#Xu2023MDP] Xu, W., Shi, B., Zhang, J., Feng, Z., Pan, T. and Dong, B., 2023. MDP: Privacy-Preserving GNN Based on Matrix Decomposition and Differential Privacy. In *2023 IEEE 14th International Conference on Joint Cloud Computing (JCC)*, pp.38-45.

.. [#Zhou2023On] Zhou, Z., Zhou, C., Li, X., Yao, J., Yao, Q. and Han, B., 2023. On Strengthening and Defending Graph Reconstruction Attack with Markov Chain Approximation. In *Proceedings of the 40th International Conference on Machine Learning (ICML)*, pp.41803-41833.

.. [#Xu2024OblivGNN] Xu, Z., Lai, S., Liu, X., Abuadbba, A., Yuan, X. and Yi, X., 2024. OblivGNN: Oblivious Inference on Transductive and Inductive Graph Neural Network. In *33rd USENIX Security Symposium (USENIX Security 24)*, pp.2209-2226.

.. [#Lou2025GRID] Lou, J., Yuan, X., Zhang, R., Yuan, X., Gong, N.Z. and Tzeng, N.-F., 2025. GRID: Protecting Training Graph from Link Stealing Attacks on GNN Models. In *2025 IEEE Symposium on Security and Privacy (IEEE S\&P 2025)*, pp.2095-2113.

.. [#Xu2023Watermarking] Xu, J., Koffas, S., Ersoy, O. and Picek, S., 2023. Watermarking Graph Neural Networks based on Backdoor Attacks. In *2023 IEEE European Symposium on Security and Privacy (EuroS\&P 2023)*, pp.1179-1197.

.. [#ding2019deep] Kaize Ding, Jundong Li, Rohit Bhanushali, and Huan Liu. 2019. Deep anomaly detection on attributed networks. In *Proceedings of the 2019 SIAM International Conference on Data Mining (SDM)*, 594–602. https://doi.org/10.1137/1.9781611975673.67.

.. [#niu2023graph] Chaoxi Niu, Guansong Pang, and Ling Chen. 2023. Graph-level anomaly detection via hierarchical memory networks. In *Joint European Conference on Machine Learning and Knowledge Discovery in Databases (ECML PKDD)*, 201–218.

.. [#roy2024gad] Amit Roy, Juan Shu, Jia Li, Carl Yang, Olivier Elshocht, Jeroen Smeets, and Pan Li. 2024. Gad-nr: Graph anomaly detection via neighborhood reconstruction. In *Proceedings of the 17th ACM International Conference on Web Search and Data Mining (WSDM)*, 576–585.

.. [#liu2021anomaly] Yixin Liu, Zhao Li, Shirui Pan, Chen Gong, Chuan Zhou, and George Karypis. 2021. Anomaly detection on attributed networks via contrastive self-supervised learning. *IEEE Transactions on Neural Networks and Learning Systems*, 33(6), 2378–2392.

.. [#wang2021one] Xuhong Wang, Baihong Jin, Ying Du, Ping Cui, Yingshui Tan, and Yupu Yang. 2021. One-class graph neural networks for anomaly detection in attributed networks. *Neurocomputing*, 33, 12073–12085.

.. [#ijcai2019p669] Huijun Wu, Chen Wang, Yuriy Tyshetskiy, Andrew Docherty, Kai Lu, and Liming Zhu. 2019. Adversarial examples on graph data: Deep insights into attack and defense. In *Proceedings of the Twenty-Eighth International Joint Conference on Artificial Intelligence (IJCAI)*, 4816–4823. https://doi.org/10.24963/ijcai.2019/669.

.. [#entezari2020all] Negin Entezari, Saba A. Al-Sayouri, Amirali Darvishzadeh, and Evangelos E. Papalexakis. 2020. All you need is low (rank) defending against adversarial attacks on graphs. In *Proceedings of the 13th ACM International Conference on Web Search and Data Mining (WSDM)*, 169–177.

.. [#jin2020graph] Wei Jin, Yao Ma, Xiaorui Liu, Xianfeng Tang, Suhang Wang, and Jiliang Tang. 2020. Graph structure learning for robust graph neural networks. In *Proceedings of the 26th ACM SIGKDD International Conference on Knowledge Discovery and Data Mining (KDD)*, 66–74.

.. [#li2022reliable] Kuan Li, Yang Liu, Xiang Ao, Jianfeng Chi, Jinghua Feng, Hao Yang, and Qing He. 2022. Reliable Representations Make A Stronger Defender:Unsupervised Structure Refinement for RobustGNN. In *Proceedings of the 28th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD)*, 925–935.

.. [#tu2022initializing] Wenxuan Tu, Sihang Zhou, Xinwang Liu, Yue Liu, Zhiping Cai, En Zhu, Changwang Zhang, and Jieren Cheng. 2022. Initializing Then Refining: A Simple Graph Attribute Imputation Network. In *Proceedings of the International Joint Conference on Artificial Intelligence (IJCAI)*, 3494–3500.

.. [#li2025dilution] Xinxin Li, Yang Liu, Siyong Xu, Weigao Wen, Qing He, and Xiang Ao. 2025. Dilution of Unreliable Information: Learning in Graph with Noisy Structures and Absent Attributes. In *Proceedings of the IEEE International Conference on Data Mining (ICDM)*, 1360–1369.

.. [#liu2023learning] Yixin Liu, Kaize Ding, Jianling Wang, Vincent Lee, Huan Liu, and Shirui Pan. 2023. Learning Strong Graph Neural Networks with Weak Information. In *Proceedings of the 29th ACM SIGKDD Conference on Knowledge Discovery and Data Mining (KDD)*, 1559–1571.
