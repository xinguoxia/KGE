# KGE
Some papers on Knowledge Graph Embedding(KGE)

Thanks for your attention and kind words! We will update KGE later.

Welcome to join our small WeChat group via email, to learn and talk about KGE.

## Contents

* [Libraries](#Libraries)
* [Methodologies](#methodologies)
* [Papers](#papers)
* [Datasets](#datasets)
* [Performance](#performance)

## Libraries

- LibKGE [code](https://github.com/uma-pi1/kge)
- OpenKE [code](https://github.com/thunlp/OpenKE)
- BioKEEN [code](https://github.com/SmartDataAnalytics/BioKEEN)
- Pykg2vec [code](https://github.com/Sujit-O/pykg2vec)
- GraphVite [code](https://github.com/DeepGraphLearning/graphvite)
- Scikit-KGE [code](https://github.com/mnick/scikit-kge)
- AmpliGraph [code](https://github.com/Accenture/AmpliGraph)

## Methodologies

### Traditions

#### Translation

| Year | Source        |	Methods                        |
|:----:|:-------------:|:-------------------------------:|
| 2013 | NeurIPS       | **[TransE](#TransE)**           |
| 2014 | AAAI          | **[TransH](#TransH)**           |
| 2015 | AAAI          | **[TransR](#TransR)**           |
| 2015 | ACL           | **[TransD](#TransD)**           |
| 2015 | EMNLP         | **[PTransE](#PTransE)**         |
| 2015 | EMNLP         | **[RTransE](#RTransE)**         |
| 2015 | CIKM          | **[KG2E](#KG2E)**               |
| 2016 | AAAI          | **[TransA](#TransA)**           |
| 2016 | AAAI          | **[TranSparse](#TranSparse)**   |
| 2016 | IJCAI         | **[ManifoldE](#ManifoldE)**     |
| 2016 | ACL           | **[TransG](#TransG)**           |
| 2016 | KR            | **[FTransE](#FTransE)**         |
| 2016 | NAACL-HLT     | **[lppTransE](#lppTransE)**     |
| 2016 | NAACL-HLT     | **[STransE](#STransE)**         |
| 2017 | AAAI          | **[puTransE](#puTransE)**       |
| 2017 | ACL           | **[ITransF](#ITransF)**         |
| 2017 | CIKM          | **[TransE-RS](#TransE-RS)**     |
| 2017 | CIKM          | **[CombinE](#CombinE)**         |
| 2018 | AAAI          | **[TorusE](#TorusE)**           |
| 2018 | AAAI          | **[TransAt](#TransAt)**         |
| 2018 | EMNLP         | **[TransC](#TransC)**           |
| 2019 | ICLR          | **[RotatE](#RotatE)**           |
| 2019 | AAAI          | **[TransGate](#TransGate)**     |
| 2019 | IJCAI         | **[TransMS](#TransMS)**         |
| 2019 | WSDM          | **[CrossE](#CrossE)**           |
| 2020 | AAAI          | **[HAKE](#HAKE)**               |

#### Multiplication

| Year | Source        |	Methods                        |
|:----:|:-------------:|:-------------------------------:|
| 2011 | ICML          | **[RESCAL](#RESCAL)**           |
| 2015 | ICLR          | **[DistMult](#DistMult)**       |
| 2016 | ICML          | **[ComplEx](#ComplEx)**         |
| 2016 | AAAI          | **[HolE](#HolE)**               |
| 2017 | ICML          | **[ANALOGY](#ANALOGY)**         |
| 2018 | NeurIPS       | **[SimplE](#SimplE)**           |
| 2019 | ACL           | **[DihEdral](#DihEdral)**       |
| 2019 | EMNLP         | **[TuckER](#TuckER)**           |

#### Neural Networks

| Year | Source        |	Methods                        |
|:----:|:-------------:|:-------------------------------:|
| 2013 | NeurIPS       | **[NTN](#NTN)**                 |
| 2014 | KDD           | **[ER-MLP](#ER-MLP)**           |
| 2017 | AAAI          | **[ProjE](#ProjE)**             |
| 2018 | AAAI          | **[ConvE](#ConvE)**             |
| 2018 | CIKM          | **[SENN](#SENN)**               |
| 2018 | ESWC          | **[R-GCN](#R-GCN)**             |
| 2018 | NAACL-HLT     | **[ConvKB](#ConvKB)**           |
| 2018 | NAACL-HLT     | **[KBGAN](#KBGAN)**             |
| 2019 | ICML          | **[RSN](#RSN)**                 |
| 2019 | AAAI          | **[SACN](#SACN)**               |
| 2019 | IJCAI         | **[VR-GCN](#VR-GCN)**           |
| 2019 | IJCAI         | **[M-GNN](#M-GNN)**             |
| 2019 | ACL           | **[KBGAT](#KBGAT)**             |
| 2019 | WWW           | **[ActiveLink](#ActiveLink)**   |
| 2019 | NAACL-HLT     | **[CapsE](#CapsE)**             |
| 2019 | NAACL-HLT     | **[ConvR](#ConvR)**             |
| 2019 | K-CAP         | **[TransGCN](#TransGCN)**       |
| 2020 | ICLR          | **[CompGCN](#CompGCN)**         |
| 2020 | ICLR          | **[DPMPN](#DPMPN)**             |
| 2020 | AAAI          | **[InteractE](#InteractE)**     |

### Informations

#### Path

| Year | Source        |	Methods                        |
|:----:|:-------------:|:-------------------------------:|
| 2015 | EMNLP         | **[PTransE](#PTransE)**         |
| 2015 | EMNLP         | **[RTransE](#RTransE)**         |
| 2015 | EMNLP         | **[TransE-COMP](#TransE-COMP)** |
| 2016 | COLING        | **[GAKE](#GAKE)**               |
| 2017 | EMNLP         | **[DeepPath](#DeepPath)**       |
| 2017 | CIKM          | **[TCE](#TCE)**                 |
| 2018 | ICLR          | **[MINERVA](#MINERVA)**         |
| 2018 | EMNLP         | **[MultiHopKG](#MultiHopKG)**   |
| 2019 | ICML          | **[RSN](#RSN)**                 |
| 2019 | EMNLP         | **[OPTransE](#OPTransE)**       |
| 2020 | AAAI          | **[RPJE](#RPJE)**               |

#### Textual

| Year | Source        |	Methods                                |
|:----:|:-------------:|:---------------------------------------:|
| 2014 | EMNLP         | **[pTransE](#pTransE)**                 |
| 2015 | EMNLP         | **[Jointly(desp)](#Jointly(desp))**     |
| 2016 | AAAI          | **[DKRL](#DKRL)**                       |
| 2016 | IJCAI         | **[TEKE](#TEKE)**                       |
| 2017 | AAAI          | **[SSP](#SSP)**                         |
| 2017 | IJCAI         | **[Jointly(A-LSTM)](#Jointly(A-LSTM))** |
| 2017 | ACL           | **[FRN](#FRN)**                         |
| 2018 | AAAI          | **[ConMask](#ConMask)**                 |
| 2018 | AAAI          | **[JointNRE](#JointNRE)**               |
| 2018 | NAACL-HLT     | **[ATE](#ATE)**                         |
| 2019 | AAAI          | **[OWE](#OWE)**                         |
| 2019 | IJCAI         | **[WWV](#WWV)**                         |
| 2019 | EMNLP         | **[CaRe](#CaRe)**                       |
| 2019 | EMNLP         | **[TCVAE](#TCVAE)**                     |
| 2019 | EMNLP         | **[CPL](#CPL)**                         |

#### Hierarchy

| Year | Source        |	Methods                        |
|:----:|:-------------:|:-------------------------------:|
| 2016 | IJCAI         | **[TKRL](#TKRL)**               |
| 2016 | SIGIR         | **[HiRi](#HiRi)**               |
| 2018 | AAAI          | **[TransE-T](#TransE-T)**       |
| 2018 | EMNLP         | **[TransE-HRS](#TransE-HRS)**   |
| 2020 | AAAI          | **[HAKE](#HAKE)**               |

#### Taxonomic

| Year | Source        |	Methods                        |
|:----:|:-------------:|:-------------------------------:|
| 2019 | AAAI          | **[SimplE+](#SimplE+)**         |

#### Neighborhood

| Year | Source        |	Methods                        |
|:----:|:-------------:|:-------------------------------:|
| 2016 | NeurIPS       | **[Gaifman](#Gaifman)**         |
| 2016 | COLING        | **[GAKE](#GAKE)**               |
| 2017 | CIKM          | **[TCE](#TCE)**                 |
| 2018 | UAI           | **[KBLRN](#KBLRN)**             |
| 2018 | CIKM          | **[SENN](#SENN)**               |
| 2018 | ESWC          | **[R-GCN](#R-GCN)**             |
| 2019 | AAAI          | **[LENA](#LENA)**               |
| 2019 | AAAI          | **[LAN](#LAN)**                 |
| 2019 | AAAI          | **[SACN](#SACN)**               |
| 2019 | WWW           | **[TransN](#TransN)**           |
| 2019 | EMNLP         | **[CaRe](#CaRe)**               |
| 2020 | AAAI          | **[FSRL](#FSRL)**               |

### Augmentations

#### Constraints

| Year | Source        |	Methods                        |
|:----:|:-------------:|:-------------------------------:|
| 2015 | ACL           | **[SSE](#SSE)**                 |
| 2018 | ACL           | **[ComplEx-NNE](#ComplEx-NNE)** |
| 2019 | AAAI          | **[SimplE+](#SimplE+)**         |

#### Regularizers

| Year | Source        |	Methods                        |
|:----:|:-------------:|:-------------------------------:|
| 2015 | ACL           | **[SSE](#SSE)**                 |
| 2018 | ICML          | **[ComplEx-N3](#ComplEx-N3)**   |
| 2018 | AAAI          | **[ComplEx-L1](#ComplEx-L1)**   |
| 2019 | UAI           | **[EM](#EM)**                   |
| 2020 | ICLR          | **[Teach](#Teach)**             

#### Soft Rules

| Year | Source        |	Methods                        |
|:----:|:-------------:|:-------------------------------:|
| 2015 | IJCAI         | **[r-TransE](#r-TransE)**       |
| 2016 | IJCAI         | **[ProPPR](#ProPPR)**           |
| 2016 | EMNLP         | **[KALE](#KALE)**               |
| 2017 | NeurIPS       | **[Neural-LP](#Neural-LP)**     |
| 2018 | NeurIPS       | **[GQE](#GQE)**                 |
| 2018 | AAAI          | **[RUGE](#RUGE)**               |
| 2019 | NeurIPS       | **[DRUM](#DRUM)**               |
| 2019 | AAAI          | **[UKGE](#UKGE)**               |
| 2019 | IJCAI         | **[AnyBURL](#AnyBURL)**         |
| 2019 | WWW           | **[IterE](#IterE)**             |
| 2020 | ICLR          | **[Neural-LP-N](#Neural-LP-N)** |
| 2020 | ICLR          | **[Q2B](#Q2B)**                 |
| 2020 | AAAI          | **[RPJE](#RPJE)**               |

#### Negative Sampling

| Year | Source        |	Methods                        |
|:----:|:-------------:|:-------------------------------:|
| 2014 | AAAI          | **[TransH](#TransH)**           |
| 2018 | AAAI          | **[IGAN](#IGAN)**               |
| 2018 | NAACL-HLT     | **[KBGAN](#KBGAN)**             |
| 2019 | ICLR          | **[RotatE](#RotatE)**           |
| 2019 | ICDE          | **[NSCaching](#NACaching)**     |

### Emergents

#### Few Shot

| Year | Source        |	Methods                        |
|:----:|:-------------:|:-------------------------------:|
| 2018 | EMNLP         | **[GMatching](#GMatching)**     |
| 2019 | EMNLP         | **[MetaR](#MetaR)**             |
| 2019 | EMNLP         | **[TCVAE](#TCVAE)**             |
| 2019 | EMNLP         | **[Meta-KGR](#Meta-KGR)**       |
| 2020 | AAAI          | **[FSRL](#FSRL)**               |

#### Hyper Planes

| Year | Source        |	Methods                        |
|:----:|:-------------:|:-------------------------------:|
| 2016 | ICML          | **[ComplEx](#ComplEx)**         |
| 2018 | AAAI          | **[TorusE](#TorusE)**           |
| 2019 | NeurIPS       | **[QuatE](#QuatE)**             |
| 2019 | NeurIPS       | **[MuRP](#MuRP)**               |
| 2019 | ICLR          | **[RotatE](#RotatE)**           |
| 2020 | AAAI          | **[HAKE](#HAKE)**               |

#### Graph Networks

| Year | Source        |	Methods                        |
|:----:|:-------------:|:-------------------------------:|
| 2018 | ESWC | **[R-GCN](#R-GCN)** |
| 2019 | AAAI | **[SACN](#SACN)** |
| 2019 | IJCAI | **[VR-GCN](#VR-GCN)** |
| 2019 | ICASSP | **[GRNN](#GRNN)** |
| 2019 | PRICAI | **[SAGCN](#SAGCN)** |
| 2019 | K-CAP | **[TransGCN](#TransGCN)** |
| 2020 | IEEE Access | **[GAATs](#GAATs)** |
| 2020 | ICLR | **[CompGCN](#SAGCN)** |
| 2020 | ICLR | **[DPMPN](#DPMPN)** |
| 2020 | AAAI | **[RGHAT](#RGHAT)** |
| 2020 | CoRR | **[TGCN](#TGCN)** |

#### Temporal

| Year | Source                   |	Methods                     |
|:----:|:------------------------:|:-------------------------------:|
| 2014 | EMNLP                    | **[CTPs](#CTPs)**               |
| 2016 | EMNLP                    | **[t-TransE](#t-TransE)**       |
| 2016 | COLING                   | **[TransE-TAE](#TransE-TAE)**   |
| 2017 | ICML                     | **[Know-Evolve](#Know-Evolve)** |
| 2017 | AAAI                     | **[MLNs](#MLNs)**               |
| 2018 | WWW                      | **[TTransE](#TTransE)**         |
| 2018 | EMNLP                    | **[TA-DistMult](#TA-DistMult)** |
| 2018 | EMNLP                    | **[HyTE](#HyTE)**               |
| 2019 | Journal of Web Semantics | **[ConT](#ConT)**               |
| 2019 | ICLR                     | **[DyRep](#DyRep)**             |
| 2019 | ICTAI                    | **[Hybrid-TE](#Hybrid-TE)**     |
| 2019 | WISE                     | **[CATE](#CATE)**               |
| 2020 | IEEE Access              | **[TDG2E](#TDG2E)**             |
| 2020 | ICLR                     | **[TComplEx](#TComplEx)**       |
| 2020 | AAAI                     | **[DE-SimplE](#DE-SimplE)**     |
| 2020 | IJCAI                    | **[DArtNet](#DArtNet)**         |
| 2020 | CoRR                     | **[TIMEPLEX](#TIMEPLEX)**       |

## Papers

### Survey

- Yoshua Bengio, Aaron C. Courville, Pascal Vincent. "**Representation Learning: A Review and New Perspectives**". **Transactions on Pattern Analysis and Machine Intelligence 2013**. [paper](https://ieeexplore.ieee.org/document/6472238)

- Maximilian Nickel, Kevin Murphy, Volker Tresp, Evgeniy Gabrilovich. "**A Review of Relational Machine Learning for Knowledge Graphs**". **Proceedings of the IEEE 2016**. [paper](https://ieeexplore.ieee.org/document/7358050)

- Quan Wang, Zhendong Mao, Bin Wang, Li Guo. "**Knowledge Graph Embedding: A Survey of Approaches and Applications**". **IEEE Transactions on Knowledge and Data Engineering 2017**. [paper](https://ieeexplore.ieee.org/document/8047276)

- HongYun Cai, Vincent W. Zheng, Kevin Chen-Chuan Chang. "**A Comprehensive Survey of Graph Embedding: Problems, Techniques, and Applications**". **IEEE Transactions on Knowledge and Data Engineering 2018**. [paper](https://ieeexplore.ieee.org/document/8294302)

- Xiaojun Chen, Shengbin Jia, Yang Xiang. "**A review: Knowledge reasoning over knowledge graph**". **Expert Systems with Applications 2020**. [paper](https://www.sciencedirect.com/science/article/pii/S0957417419306669?via%3Dihub)

- Seyed Mehran Kazemi, Rishab Goel, Kshitij Jain, Ivan Kobyzev, Akshay Sethi, Peter Forsyth, Pascal Poupart. "**Relational 
Representation Learning for Dynamic (Knowledge) Graphs: A Survey**". **arxiv 2019-05**. [paper](https://arxiv.org/abs/1905.11485)

- Shaoxiong Ji, Shirui Pan, Erik Cambria, Pekka Marttinen, Philip S. Yu. "**A Survey on Knowledge Graphs: Representation, Acquisition and Applications**". **arxiv 2020-02**. [paper](https://arxiv.org/abs/2002.00388)

- Andrea Rossi, Donatella Firmani, Antonio Matinata, Paolo Merialdo, Denilson Barbosa. "**Knowledge Graph Embedding for Link Prediction: A Comparative Analysis**". **arxiv 2020-02**. [paper](https://arxiv.org/abs/2002.00819)

### 2011

#### Conference

- <a name="RESCAL"></a> **(RESCAL)** Nickel Maximilian, Tresp Volker, Kriegel Hans-Peter. "**A Three-Way Model for Collective Learning on Multi-Relational Data**". **ICML 2011**. CCF A. Cite 1114. [paper](https://icml.cc/2011/papers/438_icmlpaper.pdf) [code](https://github.com/mnick/scikit-kge) :fire:

- <a name="SE"></a> **(SE)** Antoine Bordes, Jason Weston, Ronan Collobert, Yoshua Bengio. "**Learning Structured Embeddings of Knowledge Bases**". **AAAI 2011**. CCF A. Cite 743. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI11/paper/view/3659) :fire:

### 2012

#### Conference

- <a name="LFM"></a> **(LFM)** Rodolphe Jenatton, Nicolas L. Roux, Antoine Bordes, Guillaume R. Obozinski. "**A Latent Factor Model for Highly Multi-relational Data**". **NIPS 2012**. CCF A. Cite 371. [paper](http://papers.nips.cc/paper/4744-a-latent-factor-model-for-highly-multi-relational-data) :fire:

### 2013

#### Conference

- <a name="TransE"></a> **(TransE)** Antoine Bordes, Nicolas Usunier, Alberto Garcia-Duran, Jason Weston, Oksana Yakhnenko. "**Translating Embeddings for Modeling Multi-relational Data**". **NIPS 2013**. CCF A. Cite 2679. [paper](http://papers.nips.cc/paper/5071-translating-embeddings-for-modeling-multi-relational-data) [reviews](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips26/reviews/1282.html) :fire:

- <a name="NTN"></a> **(SLM/NTN)** Richard Socher, Danqi Chen, Christopher D. Manning, Andrew Y. Ng. "**Reasoning With Neural Tensor Networks for Knowledge Base Completion**". **NIPS 2013**. CCF A. Cite 1414. [paper](http://papers.nips.cc/paper/5028-reasoning-with-neural-tensor-networks-for-knowledge-base-completion) [reviews](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips26/reviews/504.html) :fire:

### 2014

#### Conference

- <a name="TransH"></a> **(TransH)** Zhen Wang, Jianwen Zhang, Jianlin Feng, Zheng Chen. "**Knowledge Graph Embedding by Translating on Hyperplanes**". **AAAI 2014**. CCF A. Cite 1333. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/view/8531) :fire:

- <a name="ER-MLP"></a> **(ER-MLP)** Xin Dong, Evgeniy Gabrilovich, Geremy Heitz, Wilko Horn, Ni Lao, Kevin Murphy, Thomas Strohmann, Shaohua Sun, Wei Zhang. "**Knowledge vault: a web-scale approach to probabilistic knowledge fusion**". **KDD 2014**. CCF A. Cite 1302. [paper](https://dl.acm.org/doi/10.1145/2623330.2623623) :fire:

- <a name="pTransE"></a> **(pTransE)** Zhen Wang, Jianwen Zhang, Jianlin Feng, Zheng Chen. "**Knowledge Graph and Text Jointly Embedding**". **EMNLP 2014**. CCF B. Cite 311. [paper](https://www.aclweb.org/anthology/D14-1167/) :fire:

- <a name="CTPs"></a> **(CTPs)** Derry Tanti Wijaya, Ndapandula Nakashole, Tom M. Mitchell. "**CTPs: Contextual Temporal Profiles for Time Scoping Facts using State Change Detection**". **EMNLP 2014**. CCF B. Cite 6. [paper](https://www.aclweb.org/anthology/D14-1207/)

### 2015

#### Conference

- <a name="DistMult"></a> **(DistMult)** Bishan Yang, Wen-tau Yih, Xiaodong He, Jianfeng Gao, Li Deng. "**Embedding Entities and Relations for Learning and Inference in Knowledge Bases**". **ICLR 2015**. CCF A. Cite 870. [paper](https://arxiv.org/abs/1412.6575) :fire:

- <a name="TransR"></a> **(TransR/CTransR)** Yankai Lin, Zhiyuan Liu, Maosong Sun, Yang Liu, Xuan Zhu. "**Learning Entity and Relation Embeddings for Knowledge Graph Completion**". **AAAI 2015**. CCF A. Cite 498?. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/view/9571) [code](https://github.com/thunlp/KB2E) :fire:

- <a name="TransD"></a> **(TransD)** Guoliang Ji, Shizhu He, Liheng Xu, Kang Liu, Jun Zhao. "**Knowledge Graph Embedding via Dynamic Mapping Matrix**". **ACL 2015**. CCF A. Cite 615. [paper](https://www.aclweb.org/anthology/P15-1067/) :fire:

- <a name="r-TransE"></a> **(r-TransE)** Quan Wang, Bin Wang, Li Guo. "**Knowledge Base Completion Using Embeddings and Rules**". **IJCAI 2015**. CCF A. Cite 138. [paper](http://ijcai.org/Abstract/15/264) :fire:

- <a name="SSE"></a> **(SSE)** Shu Guo, Quan Wang, Bin Wang, Lihong Wang, Li Guo. "**Semantically Smooth Knowledge Graph Embedding**". **ACL 2015**. CCF A. Cite 98. [paper](https://www.aclweb.org/anthology/P15-1009/) :fire:

- <a name="AMDC"></a> **(AMDC)** Hiroshi Kajino, Akihiro Kishimoto, Adi Botea, Elizabeth M. Daly, Spyros Kotoulas. "**Active Learning for Multi-relational Data Construction**". **WWW 2015**. CCF A. Cite 5. [paper](https://dl.acm.org/doi/10.1145/2736277.2741103)

- <a name="PTransE"></a> **(PTransE)** Yankai Lin, Zhiyuan Liu, Huanbo Luan, Maosong Sun, Siwei Rao, Song Liu. "**Modeling Relation Paths for Representation Learning of Knowledge Bases**". **EMNLP 2015**. CCF B. Cite 368. [paper](https://www.aclweb.org/anthology/D15-1082/) [code](https://github.com/thunlp/KB2E) :fire:

- <a name="TransE-COMP"></a> **(TransE-COMP)** Kelvin Guu, John Miller, Percy Liang. "**Traversing Knowledge Graphs in Vector Space**". **EMNLP 2015**. CCF B. Cite 242. [paper](https://www.aclweb.org/anthology/D15-1038/) [code](https://github.com/millerjohnp/traversing_knowledge_graphs) :fire:

- <a name="Jointly(desp)"></a> **(Jointly(desp))** Huaping Zhong, Jianwen Zhang, Zhen Wang, Hai Wan, Zheng Chen. "**Aligning Knowledge and Text Embeddings by Entity Descriptions**". **EMNLP 2015**. CCF B. Cite 109. [paper](https://www.aclweb.org/anthology/D15-1031/) :fire:

- <a name="RTransE"></a> **(RTransE)** Alberto Garcia-Duran, Antoine Bordes, Nicolas Usunier. "**Composing Relationships with Translations**". **EMNLP 2015**. CCF B. Cite 77. [paper](https://www.aclweb.org/anthology/D15-1034/)

- Yuanfei Luo, Quan Wang, Bin Wang, Li Guo. "**Context-Dependent Knowledge Graph Embedding**". **EMNLP 2015**. CCF B.Cite 39. [paper](https://www.aclweb.org/anthology/D15-1191/)

- <a name="KG2E"></a> **(KG2E)** Shizhu He, Kang Liu, Guoliang Ji, Jun Zhao. "**Learning to Represent Knowledge Graphs with Gaussian Embedding**". **CIKM 2015**. CCF B. Cite 189. [paper](https://dl.acm.org/citation.cfm?doid=2806416.2806502) :fire:

- Zhuoyu Wei, Jun Zhao, Kang Liu, Zhenyu Qi, Zhengya Sun, Guanhua Tian. "**Large-scale Knowledge Base Completion: Inferring via Grounding Network Sampling over Selected Instances**". **CIKM 2015**. CCF B. Cite 40. [paper](https://dl.acm.org/citation.cfm?doid=2806416.2806513)

### 2016

#### Journal

- Fei Tian, Bin Gao, Enhong Chen, Tie-Yan Liu. "**Learning Better Word Embedding by Asymmetric Low-Rank Projection of Knowledge Graph**". **Journal of Computer Science and Technology 2016**. **Sci 3**. **Impact 1.506**. Cite 9. [paper](https://link.springer.com/article/10.1007%2Fs11390-016-1651-5) 

- Pasquale Minervini, Claudia d'Amato, Nicola Fanizzi. "**Efficient energy-based embedding models for link prediction in knowledge graphs**". **Journal of Intelligent Information Systems 2016**. **Sci 4**. **Impact 1.813**. Cite 9. [paper](https://link.springer.com/article/10.1007%2Fs10844-016-0414-7)

#### Conference

- <a name="Gaifman"></a> **(Gaifman)** Mathias Niepert. "**Discriminative Gaifman Models**". **NeurIPS 2016**. CCF A. Cite 29. [paper](http://papers.nips.cc/paper/6098-discriminative-gaifman-models) [reviews](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips29/reviews/1689.html)

- <a name="ComplEx"></a> **(ComplEx)** Théo Trouillon, Johannes Welbl, Sebastian Riedel, Éric Gaussier, Guillaume Bouchard. "**Complex Embeddings for Simple Link Prediction**". **ICML 2016**. CCF A. Cite 739. [paper](http://proceedings.mlr.press/v48/trouillon16.html) [code](https://github.com/ttrouill/complex) :fire: :boom:

- <a name="HolE"></a> **(HolE)** Maximilian Nickel, Lorenzo Rosasco, Tomaso Poggio. "**Holographic Embeddings of Knowledge Graphs**". **AAAI 2016**. CCF A. Cite 577. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/view/12484) [code](https://github.com/mnick/holographic-embeddings) :fire: :boom:

- <a name="DKRL"></a> **(DKRL)** Ruobing Xie, Zhiyuan Liu, Jia Jia, Huanbo Luan, Maosong Sun. "**Representation Learning of Knowledge Graphs with Entity Descriptions**". **AAAI 2016**. CCF A. Cite 317. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/view/12216) [code](https://github.com/xrb92/DKRL) :fire: :boom:

- <a name="TranSparse"></a> **(TranSparse)** Guoliang Ji, Kang Liu, Shizhu He, Jun Zhao. "**Knowledge Graph Completion with Adaptive Sparse Transfer Matrix**". **AAAI 2016**. CCF A. Cite 228. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/view/11982) :fire:

- <a name="TransA"></a> **(TransA)** Yantao Jia, Yuanzhuo Wang, Hailun Lin, Xiaolong Jin, Xueqi Cheng. "**Locally Adaptive Translation for Knowledge Graph Embedding**". **AAAI 2016**. CCF A. Cite 80. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/view/12018) :fire:

- <a name="TKRL"></a> **(TKRL)** Ruobing Xie, Zhiyuan Liu, Maosong Sun. "**Representation Learning of Knowledge Graphs with Hierarchical Types**". **IJCAI 2016**. CCF A. Cite 140. [paper](http://www.ijcai.org/Abstract/16/421) [code](https://github.com/thunlp/TKRL) :fire:

- <a name="TEKE"></a> **(TEKE)** Zhigang Wang, Juanzi Li. "**Text-Enhanced Representation Learning for Knowledge Graph**". **IJCAI 2016**. CCF A. Cite 113. [paper](http://www.ijcai.org/Abstract/16/187) :fire:

- <a name="ManifoldE"></a> **(ManifoldE)** Han Xiao, Minlie Huang, Xiaoyan Zhu. "**From One Point to a Manifold: Knowledge Graph Embedding for Precise Link Prediction**". **IJCAI 2016**. CCF A. Cite 82. [paper](http://www.ijcai.org/Abstract/16/190) [code](https://github.com/BookmanHan/Embedding) :fire:

- <a name="KR-EAR"></a> **(KR-EAR)** Yankai Lin, Zhiyuan Liu, Maosong Sun. "**Knowledge Representation Learning with Entities, Attributes and Relations**". **IJCAI 2016**. CCF A. Cite 49. [paper](http://www.ijcai.org/Abstract/16/407) [code](https://github.com/thunlp/KR-EAR)

- <a name="ProPPR"></a> **(ProPPR)** William Yang Wang, William W. Cohen. "**Learning First-Order Logic Embeddings via Matrix Factorization**".  **IJCAI 2016**. CCF A. Cite 48. [paper](http://www.ijcai.org/Abstract/16/304) [code](https://github.com/TeamCohen/ProPPR)

- Jianfeng Wen, Jianxin Li, Yongyi Mao, Shini Chen, Richong Zhang. "**On the Representation and Embedding of Knowledge Bases beyond Binary Relations**". **IJCAI 2016**. CCF A. Cite 22. [paper](https://www.ijcai.org/Abstract/16/188)

- <a name="TransG"></a> **(TransG)** Han Xiao, Minlie Huang, Xiaoyan Zhu. "**TransG: A Generative Model for Knowledge Graph Embedding**". **ACL 2016**. CCF A. Cite 194. [paper](https://www.aclweb.org/anthology/P16-1219/) [code](https://github.com/BookmanHan/Embedding) :fire:

- Teng Long, Ryan Lowe, Jackie Chi Kit Cheung, Doina Precup. "**Leveraging Lexical Resources for Learning Entity Embeddings in Multi-Relational Data**". **ACL 2016**. CCF A. Cite 18. [paper](https://www.aclweb.org/anthology/P16-2019/)

- <a name="HiRi"></a> **(HiRi)** Qiao Liu, Liuyi Jiang, Minghao Han, Yao Liu, Zhiguang Qin. "**Hierarchical Random Walk Inference in Knowledge Graphs**". **SIGIR 2016**. CCF A. Cite 22. [paper](https://dl.acm.org/doi/10.1145/2911451.2911509)

- <a name="KALE"></a> **(KALE)** Shu Guo, Quan Wang, Lihong Wang, Bin Wang, Li Guo."**Jointly Embedding Knowledge Graphs and Logical Rules**". **EMNLP 2016**. CCF B. Cite 110. [paper](https://www.aclweb.org/anthology/D16-1019/) [code](https://github.com/iieir-km/KALE) :fire:

- <a name="t-TransE"></a> **(t-TransE)** Tingsong Jiang, Tianyu Liu, Tao Ge, Lei Sha, Sujian Li, Baobao Chang, Zhifang Sui. "**Encoding Temporal Information for Time-Aware Link Prediction**". **EMNLP 2016**. CCF B. Cite 35. [paper](https://www.aclweb.org/anthology/D16-1260/)

- <a name="FTransE"></a> **(FTransE)** Jun Feng, Minlie Huang, Mingdong Wang, Mantong Zhou, Yu Hao, Xiaoyan Zhu. "**Knowledge Graph Embedding by Flexible Translation**". **KR 2016**. CCF B. Cite 58. [paper](https://www.aaai.org/ocs/index.php/KR/KR16/paper/view/12887) [code](http://ml.knu.ac.kr/lppKE)

- <a name="GAKE"></a> **(GAKE)** Jun Feng, Minlie Huang, Yang Yang, Xiaoyan Zhu. "**GAKE: Graph Aware Knowledge Embedding**".  **COLING 2016**. CCF B. Cite 58. [paper](https://www.aclweb.org/anthology/C16-1062/) [code](https://github.com/JuneFeng/GAKE)

- <a name="TransE-TAE"></a> **(TransE-TAE)** Tingsong Jiang, Tianyu Liu, Tao Ge, Lei Sha, Baobao Chang, Sujian Li, Zhifang Sui. "**Towards Time-Aware Knowledge Graph Completion**". **COLING 2016**. CCF B. Cite 38. [paper](https://www.aclweb.org/anthology/C16-1161/)

- <a name="STransE"></a> **(STransE)** Dat Quoc Nguyen, Kairit Sirts, Lizhen Qu, Mark Johnson. "**STransE: A Novel Embedding Model of Entities and Relationships in Knowledge Bases**". **HLT-NAACL 2016**. CCF C. Cite 129. [paper](https://www.aclweb.org/anthology/N16-1054/) [code](https://github.com/datquocnguyen/STransE) :fire:

- <a name="lppTransE"></a> **(lppTransE)** Hee-Geun Yoon, Hyun-Je Song, Seong-Bae Park, Se-Young Park. "**A Translation-Based Knowledge Graph Embedding Preserving Logical Property of Relations**". **HLT-NAACL 2016**. CCF C. Cite 44. [paper](https://www.aclweb.org/anthology/N16-1105)

- Changwei Hu, Piyush Rai, Lawrence Carin. "**Topic-Based Embeddings for Learning from Large Knowledge Graphs**". **AISTATS 2016**. CCF C. Cite 9. [paper](http://proceedings.mlr.press/v51/hu16d.html)

- Yinchong Yang, Cristóbal Esteban, Volker Tresp. "**Embedding Mapping Approaches for Tensor Factorization and Knowledge Graph Modelling**". **ESWC 2016**. CCF C. Cite 3. [paper](https://link.springer.com/chapter/10.1007%2F978-3-319-34129-3_13)

### 2017

#### Journal

- **(LPMR)** Caiyan Dai, Ling Chen, Bin Li, Yun Li. "**Link prediction in multi-relational networks based on relational similarity**". **Information Sciences 2017**. **Sci 1**. **Impact 5.910**. Cite 26. [paper](https://www.sciencedirect.com/science/article/pii/S0020025517304139?via%3Dihub) :fire:

- Lidong Bing, Zhiming Zhang, Wai Lam, William W. Cohen. "**Towards a language-independent solution: Knowledge base completion by searching the Web and deriving language pattern**". **Knowledge-based Systems 2017**. **Sci 2**. **Impact 5.921**. Cite 4. [paper](https://www.sciencedirect.com/science/article/pii/S0950705116303859?via%3Dihub)

- **(SSE)** Shu Guo, Quan Wang, Bin Wang, Lihong Wang, Li Guo. "**SSE: Semantically Smooth Embedding for Knowledge Graphs**". **IEEE Transactions on Knowledge and Data Engineering 2017**. **Sci 2**. **Impact 4.935**. Cite 22. [paper](https://ieeexplore.ieee.org/document/7779046) :fire:

- **(TRANSFER)** Xiaochi Wei, Heyan Huang, Liqiang Nie, Hanwang Zhang, Xianling Mao, Tat-Seng Chua. "**I Know What You Want to Express: Sentence Element Inference by Incorporating External Knowledge Base**". **IEEE Transactions on Knowledge and Data Engineering 2017**. **Sci 2**. **Impact 4.935**. Cite 9. [paper](https://ieeexplore.ieee.org/document/7723822) [code](https://datapublication.wixsite.com/transfer)

- **(TransPES)** Yu Wu, Tingting Mu, John Yannis Goulermas. "**Translating on pairwise entity space for knowledge graph embedding**". **Neurocomputing 2017**. **Sci 2**. **Impact 4.438**. Cite 6. [paper](https://www.sciencedirect.com/science/article/pii/S0925231217307968?via%3Dihub) [code](https://github.com/while519/TranPES)

- Liang Chang, Manli Zhu, Tianlong Gu, Chenzhong Bin, Junyan Qian, Ji Zhang. "**Knowledge Graph Embedding by Dynamic Translation**". **IEEE Access 2017**. **Sci 2**. **Impact 3.745**. Cite 18. [paper](https://ieeexplore.ieee.org/document/8057770)

- **(ComplEx)** Théo Trouillon, Christopher R. Dance, Éric Gaussier, Johannes Welbl, Sebastian Riedel, Guillaume Bouchard. "**Knowledge Graph Completion via Complex Tensor Factorization**". **Journal of Machine Learning Research 2017**. **Sci 2**. **Impact 3.484**. Cite 107. [paper](http://jmlr.org/papers/v18/16-563.html) [code](https://github.com/ttrouill/complex) :fire:

- Nico Potyka, Matthias Thimm. "**Inconsistency-tolerant reasoning over linear probabilistic knowledge bases**". **International Journal of Approximate Reasoning 2017**. **Sci 3**. **Impact 2.678**. Cite 4. [paper](https://www.sciencedirect.com/science/article/abs/pii/S0888613X17303705?via%3Dihub)

#### Conference

- <a name="Neural-LP"></a> **(Neural-LP)** Fan Yang, Zhilin Yang, William W. Cohen. "**Differentiable Learning of Logical Rules for Knowledge Base Reasoning**". **NIPS 2017**. CCF A. Cite 150. [paper](http://papers.nips.cc/paper/6826-differentiable-learning-of-logical-rules-for-knowledge-base-reasoning) [reviews](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips30/reviews/1347.html) [code](https://github.com/fanyangxyz/Neural-LP) :fire:

- <a name="ANALOGY"></a> **(ANALOGY)** Hanxiao Liu, Yuexin Wu, Yiming Yang. "**Analogical Inference for Multi-relational Embeddings**". **ICML 2017**. CCF A. Cite 164. [paper](http://proceedings.mlr.press/v70/liu17d.html) [code](https://github.com/quark0/ANALOGY) :fire:

- <a name="Know-Evolve"></a> **(Know-Evolve)** Rakshit Trivedi, Hanjun Dai, Yichen Wang, Le Song. "**Know-Evolve: Deep Temporal Reasoning for Dynamic Knowledge Graphs**". **ICML 2017**. CCF A. Cite 124.[paper](http://proceedings.mlr.press/v70/trivedi17a.html) :fire:

- <a name="ProjE"></a> **(ProjE)** Baoxu Shi, Tim Weninger. "**ProjE: Embedding Projection for Knowledge Graph Completion**". **AAAI 2017**. CCF A. Cite 150. [paper](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14279) [code](https://github.com/bxshi/ProjE) :fire:

- <a name="SSP"></a> **(SSP)** Han Xiao, Minlie Huang, Lian Meng, Xiaoyan Zhu. "**SSP: Semantic Space Projection for Knowledge Graph Embedding with Text Descriptions**". **AAAI 2017**. CCF A. Cite 99. [paper](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14306) [code](https://github.com/BookmanHan/Embedding) :fire:

- <a name="MLNs"></a> **(MLNs)** Melisachew Wudage Chekol, Giuseppe Pirrò, Joerg Schoenfisch, Heiner Stuckenschmidt. "**Marrying Uncertainty and Time in Knowledge Graphs**". **AAAI 2017**. CCF A. Cite 34. [paper](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14730)

- <a name="puTransE"></a> **(puTransE)** Yi Tay, Luu Anh Tuan, Siu Cheung Hui. "**Non-Parametric Estimation of Multiple Embeddings for Link Prediction on Dynamic Knowledge Graphs**". **AAAI 2017**. CCF A. Cite 22. [paper](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14524)

-  <a name="Jointly(A-LSTM)"></a> **(Jointly(A-LSTM))** Jiacheng Xu, Xipeng Qiu, Kan Chen, Xuanjing Huang. "**Knowledge Graph Representation with Jointly Structural and Textual Encoding**". **IJCAI 2017**. CCF A. Cite 57. [paper](https://www.ijcai.org/proceedings/2017/183) [code](https://github.com/jiacheng-xu/Attn-KGE) :fire:

- <a name="IKRL"></a> **(IKRL)** Ruobing Xie, Zhiyuan Liu, Huanbo Luan, Maosong Sun. "**Image-embodied Knowledge Representation Learning**". **IJCAI 2017**. CCF A. Cite 46. [paper](https://www.ijcai.org/proceedings/2017/438) [code](https://github.com/thunlp/IKRL)

- <a name="ITransf"></a> **(ITransF)** Qizhe Xie, Xuezhe Ma, Zihang Dai, Eduard Hovy. "**An Interpretable Knowledge Transfer Model for Knowledge Base Completion**". **ACL 2017**. CCF A. Cite 45. [paper](https://www.aclweb.org/anthology/P17-1088/)

- <a name="FRN"></a> **(FRN)** Alexandros Komninos, Suresh Manandhar. "**Feature-Rich Networks for Knowledge Base Completion**". **ACL 2017**. CCF A. Cite 5. [paper](https://www.aclweb.org/anthology/P17-2051/)

- Wen Zhang. "**Knowledge Graph Embedding with Diversity of Structures**". **WWW 2017**. CCF A. Cite 11. [paper](https://dl.acm.org/doi/10.1145/3041021.3053380)

- Vibhor Kanojia, Hideyuki Maeda, Riku Togashi, Sumio Fujita. "**Enhancing Knowledge Graph Embedding with Probabilistic Negative Sampling**". **WWW 2017**. CCF A. Cite 5. [paper](https://dl.acm.org/doi/10.1145/3041021.3054238)

- <a name="DeepPath"></a> **(DeepPath)** Wenhan Xiong, Thien Hoang, William Yang Wang. "**DeepPath: A Reinforcement Learning Method for Knowledge Graph Reasoning**". **EMNLP 2017**. CCF B. Cite 180. [paper](https://www.aclweb.org/anthology/D17-1060/) :fire:

- Jay Pujara, Eriq Augustine, Lise Getoor. "**Sparsity and Noise: Where Knowledge Graph Embeddings Fall Short**". **EMNLP 2017**. CCF B. Cite 41. [paper](https://www.aclweb.org/anthology/D17-1184/) [code](https://github.com/linqs/pujara-emnlp17)

- <a name="ETE"></a> **(ETE)** Changsung Moon, Paul Jones, Nagiza F. Samatova. "**Learning Entity Type Embeddings for Knowledge Graph Completion**". **CIKM 2017**. CCF B. Cite 22. [paper](https://dl.acm.org/doi/10.1145/3132847.3133095)

- <a name="TransE-RS"></a> **(TransE-RS)** Xiaofei Zhou, Qiannan Zhu, Ping Liu, Li Guo. "**Learning Knowledge Embeddings by Combining Limit-based Scoring Loss**". **CIKM 2017**. CCF B. Cite 19. [paper](https://dl.acm.org/doi/10.1145/3132847.3132939)

- <a name="TCE"></a> **(TCE)** Jun Shi, Huan Gao, Guilin Qi, Zhangquan Zhou. "**Knowledge Graph Embedding with Triple Context**". **CIKM 2017**. CCF B. Cite 12. [paper](https://dl.acm.org/doi/10.1145/3132847.3133119) [code](https://github.com/juneshi0315/TCE)

- <a name="CombinE"></a> **(CombinE)** Zhen Tan, Xiang Zhao, Wei Wang. "**Representation Learning of Large-Scale Knowledge Graphs via Entity Feature Combinations**". **CIKM 2017**. CCF B. Cite 5. [paper](https://dl.acm.org/doi/10.1145/3132847.3132961)

- Soumajit Pal, Jacopo Urbani. "**Enhancing Knowledge Graph Completion By Embedding Correlations**". **CIKM 2017**. CCF B. Cite 2.  [paper](https://dl.acm.org/doi/10.1145/3132847.3133143) [code](https://github.com/karmaresearch/statlearning)

- Pasquale Minervini, Luca Costabello, Emir Muñoz, Vít Novácek, Pierre-Yves Vandenbussche. "**Regularizing Knowledge Graph Embeddings via Equivalence and Inversion Axioms**". **ECML/PKDD 2017**. CCF B. Cite 31. [paper](https://link.springer.com/chapter/10.1007%2F978-3-319-71249-9_40)

- Shiheng Ma, Jianhui Ding, Weijia Jia, Kun Wang, Minyi Guo. "**TransT: Type-Based Multiple Embedding Representations for Knowledge Graph Completion**". **ECML/PKDD 2017**. CCF B. Cite 24. [paper](https://link.springer.com/chapter/10.1007%2F978-3-319-71249-9_43)

- Zhijuan Du, Zehui Hao, Xiaofeng Meng, Qiuyue Wang. "**CirE: Circular Embeddings of Knowledge Graphs**". **DASFAA 2017**. CCF B. Cite 3. [paper](https://link.springer.com/chapter/10.1007%2F978-3-319-55753-3_10)

- <a name="RSTE"></a> **(RSTE)** Yi Tay, Anh Tuan Luu, Siu Cheung Hui, Falk Brauer. "**Random Semantic Tensor Ensemble for Scalable Knowledge Graph Link Prediction**". **WSDM 2017**. CCF B. Cite 13. [paper](https://dl.acm.org/doi/10.1145/3018661.3018695)

- Jianfeng Du, Kunxun Qi, Hai Wan, Bo Peng, Shengbin Lu, Yuming Shen. "**Enhancing Knowledge Graph Embedding from a Logical Perspective**". **JIST 2017**. Cite 7. [paper](https://link.springer.com/chapter/10.1007%2F978-3-319-70682-5_15)

- Tianxing Wu, Du Zhang, Lei Zhang, Guilin Qi. "**Cross-Lingual Taxonomy Alignment with Bilingual Knowledge Graph Embeddings**". **JIST 2017**. Cite 5. [paper](https://link.springer.com/chapter/10.1007%2F978-3-319-70682-5_16)

- Bhushan Kotnis, Vivi Nastase. "**Learning Knowledge Graph Embeddings with Type Regularizer**". **K-CAP 2017**. Cite 3. [paper](https://dl.acm.org/doi/10.1145/3148011.3154466)

### 2018

#### Journal

- **(PaSKoGE)** Yantao Jia, Yuanzhuo Wang, Xiaolong Jin, Xueqi Cheng. "**Path-specific knowledge graph embedding**". **Knowledge-based Systems 2018**. **Sci 2**. **Impact 5.921**. Cite 10. [paper](https://www.sciencedirect.com/science/article/pii/S0950705118301448?via%3Dihub)

- Lirong He, Bin Liu, Guangxi Li, Yongpan Sheng, Yafang Wang, Zenglin Xu. "**Knowledge Base Completion by Variational Bayesian Neural Tensor Decomposition**". **Cognitive Computation 2018**. **Sci 2**. **Impact 4.287**. Cite 16. [paper](https://link.springer.com/article/10.1007%2Fs12559-018-9565-x) :fire:

- Zhen Tan, Xiang Zhao, Yang Fang, Weidong Xiao. "**GTrans: Generic Knowledge Graph Embedding via Multi-State Entities and Dynamic Relation Spaces**". **IEEE Access 2018**. **Sci 2**. **Impact 3.745**. Cite 12. [paper](https://ieeexplore.ieee.org/document/8269287)

- Huan Gao, Jun Shi, Guilin Qi, Meng Wang. "**Triple Context-Based Knowledge Graph Embedding**". **IEEE Access 2018**. **Sci 2**. **Impact 3.745**. Cite 8. [paper](https://ieeexplore.ieee.org/document/8490812/)

- Hyun-Je Song, Seong-Bae Park. "**Enriching Translation-Based Knowledge Graph Embeddings Through Continual Learning**". **IEEE Access 2018**. **Sci 2**. **Impact 3.745**. Cite 2. [paper](https://ieeexplore.ieee.org/document/8486959)

- Xiao Han, Chunhong Zhang, Tingting Sun, Yang Ji, Zheng Hu. "**A Triple-Branch Neural Network for Knowledge Graph Embedding**". **IEEE Access 2018**. **Sci 2**. **Impact 3.745**. Cite 1. [paper](https://ieeexplore.ieee.org/document/8552355)

- Jizhao Zhu, Yantao Jia, Jun Xu, Jianzhong Qiao, Xueqi Cheng. "**Modeling the Correlations of Relations for Knowledge Graph Embedding**. **Journal of Computer Science and Technology 2018**. **Sci 3**. **Impact 1.506**. Cite 8. [paper](https://link.springer.com/article/10.1007/s11390-018-1821-8)

- Yantao Jia, Yuanzhuo Wang, Xiaolong Jin, Hailun Lin, Xueqi Cheng. "**Knowledge Graph Embedding: A Locally and Temporally Adaptive Translation-Based Approach**". **ACM Transactions on the Web 2018**. **Sci 4**. **Impact 1.157**. Cite 10. [paper](https://dl.acm.org/doi/10.1145/3132733)

#### Conference

- <a name="MINERVA"></a> **(MINERVA)** Rajarshi Das, Shehzaad Dhuliawala, Manzil Zaheer, Luke Vilnis, Ishan Durugkar, Akshay Krishnamurthy, Alex Smola, Andrew McCallum. "**Go for a Walk and Arrive at the Answer: Reasoning Over Paths in Knowledge Bases using Reinforcement Learning**". **ICLR 2018**. CCF A. Cite 164. [paper](https://openreview.net/forum?id=Syg-YfWCW) [code](https://github.com/shehzaadzd/MINERVA) :fire:

- <a name="SimplE"></a> **(SimplE)** Seyed Mehran Kazemi, David Poole. "**SimplE Embedding for Link Prediction in Knowledge Graphs**". **NeurIPS 2018**. CCF A. Cite 163. [paper](http://papers.nips.cc/paper/7682-simple-embedding-for-link-prediction-in-knowledge-graphs) [reviews](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips31/reviews/2093.html) [code](https://github.com/Mehran-k/SimplE) :fire:

- <a name="GQE"></a> **(GQE)** William L. Hamilton, Payal Bajaj, Marinka Zitnik, Dan Jurafsky, Jure Leskovec. "**Embedding Logical Queries on Knowledge Graphs**". **NeurIPS 2018**. CCF A. Cite 66. [paper](http://papers.nips.cc/paper/7473-embedding-logical-queries-on-knowledge-graphs) [reviews](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips31/reviews/1018.html) [code](https://github.com/williamleif/graphqembed) :fire:

- <a name="ComplEx-N3"></a> **(ComplEx-N3)** Timothée Lacroix, Nicolas Usunier, Guillaume Obozinski. "**Canonical Tensor Decomposition for Knowledge Base Completion**". **ICML 2018**. CCF A. Cite 113. [paper](http://proceedings.mlr.press/v80/lacroix18a.html) [code](https://github.com/facebookresearch/kbc) :fire:

- <a name="ConvE"></a> **(ConvE)** Tim Dettmers, Pasquale Minervini, Pontus Stenetorp, Sebastian Riedel. "**Convolutional 2D Knowledge Graph Embeddings**". **AAAI 2018**. CCF A. Cite 512. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/17366) [code](https://github.com/TimDettmers/ConvE) :fire:

- <a name="TorusE"></a> **(TorusE)** Takuma Ebisu, Ryutaro Ichise. "**TorusE: Knowledge Graph Embedding on a Lie Group**". **AAAI 2018**. CCF A. Cite 78. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16227) [code](https://github.com/TakumaE/TorusE) :fire:

- <a name="RUGE"></a> **(RUGE)** Shu Guo, Quan Wang, Lihong Wang, Bin Wang, Li Guo. "**Knowledge Graph Embedding With Iterative Guidance From Soft Rules**". **AAAI 2018**. CCF A. Cite 74. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16369) [code](https://github.com/iieir-km/RUGE) :fire:

- <a name="ConMask"></a> **(ConMask)** Baoxu Shi, Tim Weninger. "**Open-World Knowledge Graph Completion**". **AAAI 2018**. CCF A. Cite 73. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16055) [code](https://github.com/bxshi/ConMask) "fire"

- <a name="JointNRE"></a> **(JointNRE)** Xu Han, Zhiyuan Liu, Maosong Sun. "**Neural Knowledge Acquisition via Mutual Attention Between Knowledge Graph and Text**". **AAAI 2018**. CCF A. Cite 55. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16691) [code](https://github.com/thunlp/JointNRE) :fire:

- <a name="IGAN"></a> **(IGAN)** Peifeng Wang, Shuangyin Li, Rong Pan. "**Incorporating GAN for Negative Sampling in Knowledge Representation Learning**". **AAAI 2018**. CCF A. Cite 39. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16094)

- Yanjie Wang, Rainer Gemulla, Hui Li. "**On Multi-Relational Link Prediction with Bilinear Models**". **AAAI 2018**. CCF A. Cite 28. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16900) [code](https://github.com/y-j-wang/b4l)

- <a name="CKRL"></a> **(CKRL)** Ruobing Xie, Zhiyuan Liu, Fen Lin, Leyu Lin. "**Does William Shakespeare REALLY Write Hamlet? Knowledge Representation Learning With Confidence**". **AAAI 2018**. CCF A. Cite 19. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16577) [code](https://github.com/thunlp/CKRL)

- <a name="ComplEx-L1"></a> **(ComplEx-L1)** Hitoshi Manabe, Katsuhiko Hayashi, Masashi Shimbo. "**Data-Dependent Learning of Symmetric/Antisymmetric Relations for Knowledge Base Completion**". **AAAI 2018**. CCF A. Cite 7. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16211) [code](https://github.com/mana-ysh/symmetry-learning-kgc)

- <a name="TransE-T"></a> **(TransE-T)** Richong Zhang, Fanshuang Kong, Chenyue Wang, Yongyi Mao. "**Embedding of Hierarchically Typed Knowledge Bases**". **AAAI 2018**. CCF A. Cite 2. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16539) [code](https://github.com/fskong/Embedding_of_Hierarchically_Typed_KB)

- <a name="TransAt"></a> **(TransAt)** Wei Qian, Cong Fu, Yu Zhu, Deng Cai, Xiaofei He. "**Translating Embeddings for Knowledge Graph Completion with Relation Attention Mechanism**". **IJCAI 2018**. CCF A. Cite 19. [paper](https://www.ijcai.org/proceedings/2018/596) [code](https://github.com/ZJULearning/TransAt)

- <a name="ComplEx-NNE"></a> **(ComplEx-NNE)** Boyang Ding, Quan Wang, Bin Wang, Li Guo. "**Improving Knowledge Graph Embedding Using Simple Constraints**". **ACL 2018**. CCF A. Cite 48. [paper](https://www.aclweb.org/anthology/P18-1011/) [code](https://github.com/iieir-km/ComplEx-NNE_AER) :fire:

- Luke Vilnis, Xiang Li, Shikhar Murty, Andrew McCallum. "**Probabilistic Embedding of Knowledge Graphs with Box Lattice Measures**". **ACL 2018**. CCF A. Cite 40. [paper](https://www.aclweb.org/anthology/P18-1025/)

- **(KG-Geometry)** Chandrahas, Aditya Sharma, Partha Talukdar. "**Towards Understanding the Geometry of Knowledge Graph Embeddings**". **ACL 2018**. CCF A. Cite 22. [paper](https://www.aclweb.org/anthology/P18-1012/) [code](https://github.com/malllabiisc/kg-geometry)

- Ryo Takahashi, Ran Tian, Kentaro Inui. "**Interpretable and Compositional Relation Learning by Joint Training with an Autoencoder**". **ACL 2018**. CCF A. Cite 4. [paper](https://www.aclweb.org/anthology/P18-1200/) [code](https://github.com/tianran/glimvec)

- <a name="TransN"></a> **(TransN)** Chun-Chih Wang, Pu-Jen Cheng. "**Translating Representations of Knowledge Graphs with Neighbors**". **SIGIR 2018**. CCF A. Cite 3. [paper](https://dl.acm.org/doi/10.1145/3209978.3210085)

- **(Max-K Criterion)** Jiajie Mei, Richong Zhang, Yongyi Mao, Ting Deng. "**On Link Prediction in Knowledge Bases: Max-K Criterion and Prediction Protocols**". **SIGIR 2018**. CCF A. Cite 1. [paper](https://dl.acm.org/doi/10.1145/3209978.3210029)

- <a name="TTransE"></a> **(TTransE)** Julien Leblay, Melisachew Wudage Chekol. "**Deriving Validity Time in Knowledge Graph**". **WWW 2018**. CCF A. Cite 34. [paper](https://dl.acm.org/doi/10.1145/3184558.3191639)

- Kaja Zupanc, Jesse Davis. "**Estimating Rule Quality for Knowledge Base Completion with the Relationship between Coverage Assumption**". **WWW 2018**. CCF A. Cite 18. [paper](https://dl.acm.org/doi/10.1145/3178876.3186006)

- <a name="KBLRN"></a> **(KBLRN)** Alberto García-Durán, Mathias Niepert. "**KBlrn: End-to-End Learning of Knowledge Base Representations with Latent, Relational, and Numerical Features**". **UAI 2018**. CCF B. Cite 41. [paper](http://auai.org/uai2018/proceedings/papers/149.pdf) :fire:

- <a name="MultiHopKG"></a> **(MultiHopKG)** Xi Victoria Lin, Richard Socher, Caiming Xiong. "**Multi-Hop Knowledge Graph Reasoning with Reward Shaping**". **EMNLP 2018**. CCF B. Cite 69. [paper](https://www.aclweb.org/anthology/D18-1362/) [code](https://github.com/salesforce/MultiHopKG) :fire:

- <a name="HyTE"></a> **(HyTE)** Shib Sankar Dasgupta, Swayambhu Nath Ray, Partha Talukdar. "**HyTE: Hyperplane-based Temporally aware Knowledge Graph Embedding**". **EMNLP 2018**. CCF B. Cite 50. [paper](https://www.aclweb.org/anthology/D18-1225/) [code](https://github.com/malllabiisc/HyTE) :fire:

- <a name="GMatching"></a> **(GMatching)** Wenhan Xiong, Mo Yu, Shiyu Chang, Xiaoxiao Guo, William Yang Wang. "**One-Shot Relational Learning for Knowledge Graphs**". **EMNLP 2018**. CCF B. Cite 40. [paper](https://www.aclweb.org/anthology/D18-1223/) [code](https://github.com/xwhan/One-shot-Relational-Learning)

- <a name="TA-DistMult"></a> **(TA-DistMult)** Alberto Garcia-Duran, Sebastijan Dumančić, Mathias Niepert. "**Learning Sequence Encoders for Temporal Knowledge Graph Completion**". **EMNLP 2018**. CCF B. Cite 39. [paper](https://www.aclweb.org/anthology/D18-1516/) [dataset](https://github.com/nle-ml/mmkb)

- <a name="TransC"></a> **(TransC)** Xin Lv, Lei Hou, Juanzi Li, Zhiyuan Liu. "**Differentiating Concepts and Instances for Knowledge Graph Embedding**". **EMNLP 2018**. CCF B. Cite 30. [paper](https://www.aclweb.org/anthology/D18-1222/) [code](https://github.com/davidlvxin/TransC)

- <a name="MKBE"></a> **(MKBE)** Pouya Pezeshkpour, Liyan Chen, Sameer Singh. "**Embedding Multimodal Relational Data for Knowledge Base Completion**". **EMNLP 2018**. CCF B. Cite 28. [paper](https://www.aclweb.org/anthology/D18-1359/) [code](https://github.com/pouyapez/mkbe)

- <a name="TransE-HRS"></a> **(TransE-HRS)** Zhao Zhang, Fuzhen Zhuang, Meng Qu, Fen Lin, Qing He. "**Knowledge Graph Embedding with Hierarchical Relation Structure**". **EMNLP 2018**. CCF B. Cite 17. [paper](https://www.aclweb.org/anthology/D18-1358/)

- Víctor Gutiérrez-Basulto, Steven Schockaert. "**From Knowledge Graph Embedding to Ontology Embedding? An Analysis of the Compatibility between Vector Space Representations and Rules**". **KR 2018**. CCF B. Cite 24. [paper](https://aaai.org/ocs/index.php/KR/KR18/paper/view/18013)

- Farahnaz Akrami, Lingbing Guo, Wei Hu, Chengkai Li. "**Re-evaluating Embedding-Based Knowledge Graph Completion Methods**". **CIKM 2018**. CCF B. Cite 12. [paper](https://dl.acm.org/doi/10.1145/3269206.3269266)

- <a name="SENN"></a> **(SENN)** Saiping Guan, Xiaolong Jin, Yuanzhuo Wang, Xueqi Cheng. "**Shared Embedding Based Neural Networks for Knowledge Graph Completion**". **CIKM 2018**. CCF B. Cite 12. [paper](https://dl.acm.org/doi/10.1145/3269206.3271704)

- <a name="CACL"></a> **(CACL)** Byungkook Oh, Seungmin Seo, Kyong-Ho. "**Knowledge Graph Completion by Context-Aware Convolutional Learning with Multi-Hop Neighborhoods**". **CIKM 2018**. CCF B. Cite 10. [paper](https://dl.acm.org/doi/10.1145/3269206.3271769)

- <a name="MultiE"></a> **(MultiE)** Zhao Zhang, Fuzhen Zhuang, Zheng-Yu Niu, Deqing Wang, Qing He. "**MultiE: Multi-Task Embedding for Knowledge Base Completion**". **CIKM 2018**. CCF B. Cite 2. [paper](https://dl.acm.org/doi/10.1145/3269206.3269295)

- Benjamin J. Lengerich, Andrew L. Maas, Christopher Potts. "**Retrofitting Distributional Embeddings to Knowledge Graphs with Functional Relations**". **COLING 2018**. CCF B. Cite 19. [paper](https://www.aclweb.org/anthology/C18-1205/)

- Zichao Huang, Bo Li, Jian Yin. "**Knowledge Graph Embedding by Learning to Connect Entity with Relation**". **APWeb/WAIM  2018**. CCF C. Cite 1. [paper](https://link.springer.com/chapter/10.1007%2F978-3-319-96890-2_33)

- Maoyuan Zhang, Qi Wang, Wukui Xu, Wei Li, Shuyuan Sun. "**Discriminative Path-Based Knowledge Graph Embedding for Precise Link Prediction**". **ECIR 2018**. CCF C. Cite 11. [paper](https://link.springer.com/chapter/10.1007%2F978-3-319-76941-7_21)

- <a name="R-GCN"></a> **(R-GCN)** Michael Schlichtkrull, Thomas N. Kipf, Peter Bloem, Rianne van den Berg, Ivan Titov, Max Welling. "**Modeling Relational Data with Graph Convolutional Networks**". **ESWC 2018**. CCF C. Cite 855. [paper](https://link.springer.com/chapter/10.1007%2F978-3-319-93417-4_38) [code](https://github.com/tkipf/relational-gcn) :fire:

- Md. Mostafizur Rahman, Atsuhiro Takasu. "**Knowledge Graph Embedding via Entities' Type Mapping Matrix**". **ICONIP 2018:**. CCF C. Cite 6. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-04182-3_11)

- Shengyue Luo, Wei Fang. "**Potential Probability of Negative Triples in Knowledge Graph Embedding**". **ICONIP 2018**. CCF C. Cite 1. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-04182-3_5)
		
- Kien Do, Truyen Tran, Svetha Venkatesh. "**Knowledge Graph Embedding with Multiple Relation Projections**". **ICPR 2018**. CCF C. Cite 13. [paper](https://ieeexplore.ieee.org/document/8545027)

- Zhiqiang Geng, 
