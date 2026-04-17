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


----


1. Tutorials & Benchmarks
---------------------------------

1.1. Benchmarks
^^^^^^^^^^^^^^^


=============  =================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Data Types     Paper Title                                                                                        Venue                         Year   Ref                           Materials
=============  =================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================
Graph          GADBench: Revisiting and Benchmarking Supervised Graph Anomaly Detection                           NeurIPS                       2023   [#Aggarwal2013Outlier]_          `[PDF] <https://arxiv.org/abs/2306.12251>`_, `[Code] <https://github.com/squareRoot3/GADBench>`_

=============  =================================================================================================  ============================  =====  ============================  ==========================================================================================================================================================================


1.2. Tutorials
^^^^^^^^^^^^^^

===================================================== ============================================  =====  ============================  ==========================================================================================================================================================================
Tutorial Title                                        Venue                                         Year   Ref                           Materials
===================================================== ============================================  =====  ============================  ==========================================================================================================================================================================
Trustworthy Anomaly Detection                         SDM                                           2024   [#Aggarwal2013Outlier]_       `[HTML] <https://yuan.shuhan.org/talks/SDM24/>`_

===================================================== ============================================  =====  ============================  ==========================================================================================================================================================================



----

2. Toolbox & Datasets
---------------------


----


3. Papers
---------


3.1. Graph Adversarial Attack
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

==============================================================================================================  ============================  =====  ============================  =====================================================================================================================================================================================
Paper Title                                                                                                     Venue                         Year   Ref                           Materials
==============================================================================================================  ============================  =====  ============================  =====================================================================================================================================================================================
AD-LLM: Benchmarking Large Language Models for Anomaly Detection                                                ACL 2025 Findings             2024   [#Abe2006Outlier]_             `[PDF] <https://arxiv.org/abs/2412.11142>`_, `[Code] <https://github.com/USC-FORTIS/AD-LLM>`_
==============================================================================================================  ============================  =====  ============================  =====================================================================================================================================================================================






3.2. Graph Adversarial Defense
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

The following papers are filtered as **broadly model-level defense** works. The scope here is intentionally relaxed: besides strict model-level privacy defenses, we also include papers on privacy-preserving GNN training/inference, graph reconstruction defense, training-graph protection, and model/IP protection mechanisms that are closely related to defending trained GNN systems.

=================================================================================================  ============================  =====  =============================  ============================================================================================================================================================================================================================================================
Paper Title                                                                                        Venue                         Year   Ref                            Materials
=================================================================================================  ============================  =====  =============================  ============================================================================================================================================================================================================================================================
NetFense: Adversarial Defenses against Privacy Attacks on Neural Networks for Graph Data           IEEE TKDE                     2023   [#Hsieh2023NetFense]_          `[PDF] <https://www.computer.org/csdl/journal/tk/2023/01/09448513/1ugDQeDTD3O>`_, `[Code] <https://github.com/ICHproject/NetFense>`_
Locally Private Graph Neural Networks                                                              ACM CCS                       2021   [#Sajadmanesh2021Locally]_     `[PDF] <https://arxiv.org/pdf/2006.05535>`_, `[Code] <https://github.com/sisaman/LPGNN>`_
Releasing Graph Neural Networks with Differential Privacy Guarantees                               AISec Workshop                2021   [#Olatunji2021Releasing]_      `[PDF] <https://arxiv.org/pdf/2109.08907>`_
GAP: Differentially Private Graph Neural Networks with Aggregation Perturbation                    USENIX Security               2023   [#Sajadmanesh2023GAP]_         `[PDF] <https://www.usenix.org/system/files/sec23fall-prepub-196-sajadmanesh.pdf>`_, `[Code] <https://github.com/sisaman/GAP>`_
SecGNN: Privacy-Preserving Graph Neural Network Training and Inference as a Cloud Service         IEEE TSC                      2023   [#Wang2023SecGNN]_             `[Paper] <https://www.computer.org/csdl/journal/sc/2023/04/10035510/1Krc3O7eDkc>`_
MDP: Privacy-Preserving GNN Based on Matrix Decomposition and Differential Privacy                 IEEE JCC                      2023   [#Xu2023MDP]_                  `[Paper] <https://www.computer.org/csdl/proceedings-article/jcc/2023/285500a038/1Q3JXMAGcM0>`_
On Strengthening and Defending Graph Reconstruction Attack with Markov Chain Approximation         ICML                          2023   [#Zhou2023On]_                 `[PDF] <https://proceedings.mlr.press/v202/zhou23s/zhou23s.pdf>`_, `[Code] <https://github.com/AndrewZhou924/MC-GRA>`_
OblivGNN: Oblivious Inference on Transductive and Inductive Graph Neural Networks                  USENIX Security               2024   [#Xu2024OblivGNN]_             `[PDF] <https://www.usenix.org/system/files/usenixsecurity24-xu-zhibo.pdf>`_
GRID: Protecting Training Graph from Link Stealing Attacks on GNN Models                           IEEE S&P                      2025   [#Lou2025GRID]_                `[Paper] <https://www.computer.org/csdl/proceedings-article/sp/2025/223600a059/21B7R5azVuM>`_
Watermarking Graph Neural Networks based on Backdoor Attacks                                       IEEE EuroS&P                  2023   [#Xu2023Watermarking]_         `[Paper] <https://repository.ubn.ru.nl/handle/2066/295585>`_
=================================================================================================  ============================  =====  =============================  ============================================================================================================================================================================================================================================================



3.3. Others
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

=================================================================================================  ============================  =====  =============================  ==============================================================================================================================================================================================
Paper Title                                                                                        Venue                         Year   Ref                            Materials
=================================================================================================  ============================  =====  =============================  ==============================================================================================================================================================================================
XGBOD: improving supervised outlier detection with unsupervised representation learning            IJCNN                         2018   [#Abe2006Outlier]_              `[PDF] <https://arxiv.org/abs/1912.00290>`_

=================================================================================================  ============================  =====  =============================  ==============================================================================================================================================================================================






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

.. [#Abe2006Outlier] Abe, N., Zadrozny, B. and Langford, J., 2006, August. Outlier detection by active learning. In *Proceedings of the 12th ACM SIGKDD international conference on Knowledge discovery and data mining*, pp. 504-509, ACM.

.. [#Aggarwal2013Outlier] Aggarwal, C.C., 2013. Outlier ensembles: position paper. *ACM SIGKDD Explorations Newsletter*\ , 14(2), pp.49-58.

.. [#Ahmed2016A] Ahmed, M., Mahmood, A.N. and Islam, M.R., 2016. A survey of anomaly detection techniques in financial domain. *Future Generation Computer Systems*\ , 55, pp.278-288.
