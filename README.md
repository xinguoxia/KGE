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
- PyKEEN [code](https://github.com/pykeen/pykeen)
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

#### [Few Shot](https://github.com/xinguoxia/KGE/blob/master/Emergents/FewShot.md)

| Year | Source |	Methods |
|:----:|:------:|:-------:|
| 2018 | EMNLP | **[GMatching](#GMatching)** |
| 2019 | EMNLP | **[MetaR](#MetaR)** |
| 2019 | EMNLP | **[TCVAE](#TCVAE)** |
| 2019 | EMNLP | **[Meta-KGR](#Meta-KGR)** |
| 2020 | NeurIPS | **[GEN](#GEN)** |
| 2020 | AAAI | **[FSRL](#FSRL)** |
| 2020 | AAAI | **[ZSGAN](#ZSGAN)** |
| 2020 | EMNLP | **[FAAN](#FAAN)** |
| 2020 | EMNLP | **[FIRE](#FIRE)** |

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

- **(ComplEx)** Théo Trouillon, Christopher R. Dance, Éric Gaussier, Johannes Welbl, Sebastian Riedel, Guillaume Bouchard. "**Knowledge Graph Completion via Complex Tensor Factorization**". **Journal of Machine Learning Research 2017**. **Sci 2**. **Impact 3.484**. Cite 107. [paper](http://jmlr.org/papers/v18/16-563.html) [code](https://github.com/ttrouill/complex) :fire:

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

### 2018

#### Journal

- **(PaSKoGE)** Yantao Jia, Yuanzhuo Wang, Xiaolong Jin, Xueqi Cheng. "**Path-specific knowledge graph embedding**". **Knowledge-based Systems 2018**. **Sci 2**. **Impact 5.921**. Cite 10. [paper](https://www.sciencedirect.com/science/article/pii/S0950705118301448?via%3Dihub)

- Lirong He, Bin Liu, Guangxi Li, Yongpan Sheng, Yafang Wang, Zenglin Xu. "**Knowledge Base Completion by Variational Bayesian Neural Tensor Decomposition**". **Cognitive Computation 2018**. **Sci 2**. **Impact 4.287**. Cite 16. [paper](https://link.springer.com/article/10.1007%2Fs12559-018-9565-x) :fire:

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

- <a name="R-GCN"></a> **(R-GCN)** Michael Schlichtkrull, Thomas N. Kipf, Peter Bloem, Rianne van den Berg, Ivan Titov, Max Welling. "**Modeling Relational Data with Graph Convolutional Networks**". **ESWC 2018**. CCF C. Cite 855. [paper](https://link.springer.com/chapter/10.1007%2F978-3-319-93417-4_38) [code](https://github.com/tkipf/relational-gcn) :fire:

- Itsumi Saito, Kyosuke Nishida, Hisako Asano, Junji Tomita. "**Commonsense Knowledge Base Completion and Generation**". **CoNLL 2018**. CCF C. Cite 17. [paper](https://www.aclweb.org/anthology/K18-1014/)

- <a name="ConvKB"></a> **(ConvKB)** Dai Quoc Nguyen, Tu Dinh Nguyen, Dat Quoc Nguyen, Dinh Phung. "**A Novel Embedding Model for Knowledge Base Completion Based on Convolutional Neural Network**". **NAACL-HLT 2018**. CCF C. Cite 168. [paper](https://www.aclweb.org/anthology/N18-2053/) [code](https://github.com/daiquocnguyen/ConvKB) :fire:
 
- <a name="KBGAN"></a> **(KBGAN)** Liwei Cai, William Yang Wang. "**KBGAN: Adversarial Learning for Knowledge Graph Embeddings**". **NAACL-HLT 2018**. CCF C. Cite 116. [paper](https://www.aclweb.org/anthology/N18-1133/) [code](https://github.com/cai-lw/KBGAN) :fire:

- <a name="ATE"></a> **(ATE)** Bo An, Bo Chen, Xianpei Han, Le Sun. "**Accurate Text-Enhanced Knowledge Graph Representation Learning**". **NAACL-HLT 2018**. CCF C. Cite 26. [paper](https://www.aclweb.org/anthology/N18-1068/)

### 2019

#### Journal

- **(TKGE)** Binling Nie, Shouqian Sun. "**Knowledge graph embedding via reasoning over entities, relations, and text**". **Future Generation Computer Systems 2019**. **Sci 1**. **Impact 6.125**. Cite 12. [paper](https://www.sciencedirect.com/science/article/pii/S0167739X17321593?via%3Dihub) :fire:

- **(KEC)** Niannian Guan, Dandan Song, Lejian Liao. "**Knowledge graph embedding with concepts**". **Knowledge-based Systems 2019**. **Sci 2**. **Impact 5.921**. Cite 24. [paper](https://www.sciencedirect.com/science/article/pii/S0950705118304945?via%3Dihub) :fire: :boom:

- **(ProjFE)** Huajing Liu, Luyi Bai, Xiangnan Ma, Wenting Yu, Changming Xu. "**ProjFE: Prediction of fuzzy entity and relation for knowledge graph completion**". **Applied Soft Computing 2019**. **Sci 2**. **Impact 5.472**. Cite 4. [paper](https://www.sciencedirect.com/science/article/pii/S1568494619302959?via%3Dihub)

- Xing Tang, Ling Chen, Jun Cui, Baogang Wei. "**Knowledge representation learning with entity descriptions, hierarchical types, and textual relations**". **Information Processing and Management 2019**. **Sci 2**. **Impact 4.787**. Cite 8. [paper](https://www.sciencedirect.com/science/article/abs/pii/S0306457318303698?via%3Dihub)

- **(RPE)** Xixun Lin, Yanchun Liang, Fausto Giunchiglia, Xiaoyue Feng, Renchu Guan. "**Relation path embedding in knowledge graphs**". **Neural Computing and Applications 2019**. **Sci 2**. **Impact 4.774**. Cite 10. [paper](https://link.springer.com/article/10.1007%2Fs00521-018-3384-6)

- Chengchun Shi, Wenbin Lu, Rui Song. "**Determining the Number of Latent Factors in Statistical Multi-Relational Learning**". **Journal of Machine Learning Research 2019**. **Sci 2**. **Impact 3.484**. Cite 3. [paper](http://jmlr.org/papers/v20/18-037.html)

- **(ConvKB)** Dai Quoc Nguyen, Dat Quoc Nguyen, Tu Dinh Nguyen, Dinh Phung. "**A convolutional neural network-based model for knowledge base completion and its application to search personalization**". **Semantic Web 2019**. **Sci 3**. **Impact 3.182**. Cite 7. [paper](https://content.iospress.com/articles/semantic-web/sw318)

#### Conference

##### ICLR

- <a name="DyRep"></a> **(DyRep)** Rakshit Trivedi, Mehrdad Farajtabar, Prasenjeet Biswal, Hongyuan Zha. "**DyRep: Learning Representations over Dynamic Graphs**". **ICLR 2019**. [paper](https://openreview.net/forum?id=HyePrhR5KX) :fire: :boom:

- <a name="RotatE"></a> **(RotatE)** Zhiqing Sun, Zhi-Hong Deng, Jian-Yun Nie, Jian Tang. "**RotatE: Knowledge Graph Embedding by Relational Rotation in Complex Space**". **ICLR 2019**. [paper](https://openreview.net/forum?id=HkgEQnRqYQ) [code](https://github.com/DeepGraphLearning/KnowledgeGraphEmbedding) :fire: :boom:

##### AAAI

- <a name="LAN"></a> **(LAN)** PeiFeng Wang, Jialong Han, Chenliang Li, Rong Pan. "**Logic Attention Based Neighborhood Aggregation for Inductive Knowledge Graph Embedding**". **AAAI 2019**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4698) [code](https://github.com/wangpf3/LAN)

- <a name="LENA"></a> **(LENA)** Fanshuang Kong, Richong Zhang, Yongyi Mao, Ting Deng. "**LENA: Locality-Expanded Neural Embedding for Knowledge Base Completion**". **AAAI 2019**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4144) [code](https://github.com/fskong/LENA)

- <a name="OWE"></a> **(OWE)** Haseeb Shah, Johannes Villmow, Adrian Ulges, Ulrich Schwanecke, Faisal Shafait. "**An Open-World Extension to Knowledge Graph Completion Models**". **AAAI 2019**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4162) [code](https://github.com/haseebs/OWE)

- <a name="SACN"></a> **(SACN)** Chao Shang, Yun Tang, Jing Huang, Jinbo Bi, Xiaodong He, Bowen Zhou. "**End-to-End Structure-Aware Convolutional Networks for Knowledge Base Completion**". **AAAI 2019**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4164) [code](https://github.com/JD-AI-Research-Silicon-Valley/SACN) :fire:

- <a name="SimplE+"></a> **(SimplE+)** Bahare Fatemi, Siamak Ravanbakhsh, David Poole. "**Improved Knowledge Graph Embedding Using Background Taxonomic Information**". **AAAI 2019**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4231)

- <a name="TransGate"></a> **(TransGate)** Jun Yuan, Neng Gao, Ji Xiang. "**TransGate: Knowledge Graph Embedding with Shared Gate Structure**". **AAAI 2019**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4169)

- <a name="UKGE"></a> **(UKGE)** Xuelu Chen, Muhao Chen, Weijia Shi, Yizhou Sun, Carlo Zaniolo. "**Embedding Uncertain Knowledge Graphs**". **AAAI 2019**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4210) [code](https://github.com/stasl0217/UKGE)

##### NeurIPS

- <a name="DRUM"></a> **(DRUM)** Ali Sadeghian, Mohammadreza Armandpour, Patrick Ding, Daisy Zhe Wang. "**DRUM: End-To-End Differentiable Rule Mining On Knowledge Graphs**". **NeurIPS 2019**. [paper](http://papers.nips.cc/paper/9669-drum-end-to-end-differentiable-rule-mining-on-knowledge-graphs) [code](https://github.com/alisadeghian/DRUM)

- <a name="MuRP"></a> **(MuRP)** Ivana Balaževic, Carl Allen, Timothy Hospedales. "**Multi-relational Poincaré Graph Embeddings**". **NeurIPS 2019**. [paper](http://papers.nips.cc/paper/8696-multi-relational-poincare-graph-embeddings) [code](https://github.com/ibalazevic/multirelational-poincare) :fire:

- <a name="QuatE"></a> **(QuatE)** Shuai Zhangy, Yi Tay, Lina Yao, Qi Liu. "**Quaternion Knowledge Graph Embeddings**". **NeurIPS 2019**. [paper](http://papers.nips.cc/paper/8541-quaternion-knowledge-graph-embeddings) [code](https://github.com/cheungdaven/QuatE) :fire:

##### ACL

- <a name="DihEdral"></a> **(DihEdral)** Canran Xu, Ruijiang Li. "**Relation Embedding with Dihedral Group in Knowledge Graph**". **ACL 2019**. [paper](https://www.aclweb.org/anthology/P19-1026/)

- <a name="KBGAT"></a> **(KBGAT)** Deepak Nathani, Jatin Chauhan, Charu Sharma, Manohar Kaul. "**Learning Attention-based Embeddings for Relation Prediction in Knowledge Graphs**". **ACL 2019**. [paper](https://www.aclweb.org/anthology/P19-1466/) [code](https://github.com/deepakn97/relationPrediction) :fire: :boom:

##### ICML

- <a name="RSN"></a> **(RSN)** Lingbing Guo, Zequn Sun, Wei Hu. "**Learning to Exploit Long-term Relational Dependencies in Knowledge Graphs**". **ICML 2019**. [paper](http://proceedings.mlr.press/v97/guo19c.html) [code](https://github.com/nju-websoft/RSN) :fire:

##### IJCAI

- <a name="AnyBURL"></a> **(AnyBURL)** Christian Meilicke, Melisachew Wudage Chekol, Daniel Ruffinelli, Heiner Stuckenschmidt. "**Anytime Bottom-Up Rule Learning for Knowledge Graph Completion**". **IJCAI 2019**. [paper](https://www.ijcai.org/proceedings/2019/435) [code](http://web.informatik.uni-mannheim.de/AnyBURL/)

- <a name="Attack"></a> **(Attack)** Hengtong Zhang, Tianhang Zheng, Jing Gao, Chenglin Miao, Lu Su, Yaliang Li, Kui Ren. "**Data Poisoning Attack against Knowledge Graph Embedding**". **IJCAI 2019**. CCF A. Cite 6. [paper](https://www.ijcai.org/proceedings/2019/674)

- <a name="M-GNN"></a> **(M-GNN)** Zihan Wang, Zhaochun Ren, Chunyu He, Peng Zhang, Yue Hu. "**Robust Embedding with Multi-Level Structures for Link Prediction**". **IJCAI 2019**. [paper](https://www.ijcai.org/proceedings/2019/728)

-  <a name="TransMS"></a> **(TransMS)** Shihui Yang, Jidong Tian, Honglun Zhang, Junchi Yan, Hao He, Yaohui Jin. "**TransMS: Knowledge Graph Embedding for Complex Relations by Multidirectional Semantics**". **IJCAI 2019**. [paper](https://www.ijcai.org/proceedings/2019/268)

- <a name="VR-GCN"></a> **(VR-GCN)** Rui Ye, Xin Li, Yujie Fang, Hongyu Zang, Mingzhong Wang. "**A Vectorized Relational Graph Convolutional Network for Multi-Relational Network Alignment**". **IJCAI 2019**.  [paper](https://www.ijcai.org/Proceedings/2019/574) 

-  <a name="WWV"></a> **(WWV)** Neil Veira, Brian Keng, Kanchana Padmanabhan, Andreas G. Veneris. "**Unsupervised Embedding Enhancements of Knowledge Graphs using Textual Associations**". **IJCAI 2019**. [paper](https://www.ijcai.org/proceedings/2019/725) [code](https://github.com/rubikloud/kg-text-embeddings)


- **(JOIE)** Junheng Hao, Muhao Chen, Wenchao Yu, Yizhou Sun, Wei Wang. "**Universal Representation Learning of Knowledge Bases by Jointly Embedding Instances and Ontological Concepts**". **KDD 2019**. CCF A. Cite 25. [paper](https://dl.acm.org/doi/10.1145/3292500.3330838) [code](https://github.com/JunhengH/joie-kdd19)

- <a name="NSCaching"></a> **(NSCaching)** Yongqi Zhang, Quanming Yao, Yingxia Shao, Lei Chen. "**NSCaching: Simple and Efficient Negative Sampling for Knowledge Graph Embedding**". **ICDE 2019**. CCF A. Cite 22. [paper](https://ieeexplore.ieee.org/document/8731371) [code](https://github.com/yzhangee/NSCaching) 

- <a name="IterE"></a> **(IterE)** Wen Zhang, Bibek Paudel, Liang Wang, Jiaoyan Chen, Hai Zhu, Wei Zhang, Abraham Bernstein, Huajun Chen. "**Iteratively Learning Embeddings and Rules for Knowledge Graph Reasoning**". **WWW 2019**. CCF A. Cite 30. [paper](https://dl.acm.org/doi/10.1145/3308558.3313612) [code](https://github.com/wencolani/IterE) :fire:

- **(NaLP)** Saiping Guan, Xiaolong Jin, Yuanzhuo Wang, Xueqi Cheng. "**Link Prediction on N-ary Relational Data**". **WWW 2019**. CCF A. Cite 10. [paper](https://dl.acm.org/doi/10.1145/3308558.3313414) [code](https://github.com/gsp2014/NaLP)

- <a name="ActiveLink"></a> **(ActiveLink)** Natalia Ostapuk, Jie Yang, Philippe Cudré-Mauroux. "**ActiveLink: Deep Active Learning for Link Prediction in Knowledge Graphs**". **WWW 2019**. CCF A. Cite 9. [paper](https://dl.acm.org/doi/10.1145/3308558.3313620) [code](https://github.com/eXascaleInfolab/ActiveLink)

- <a name="MARINE"></a> **(MARINE)** Ming-Han Feng, Chin-Chi Hsu, Cheng-Te Li, Mi-Yen Yeh, Shou-De Lin. "**MARINE: Multi-relational Network Embeddings with Relational Proximity and Node Attributes**". **WWW 2019**. CCF A. Cite 7.  [paper](https://dl.acm.org/doi/10.1145/3308558.3313715)

- <a name="TuckER"></a> **(TuckER)** Ivana Balazevic, Carl Allen, Timothy M. Hospedales. "**TuckER: Tensor Factorization for Knowledge Graph Completion**". **EMNLP/IJCNLP 2019**. CCF B. Cite 92. [paper](https://www.aclweb.org/anthology/D19-1522/) [code](https://github.com/ibalazevic/TuckER) :fire: :boom:

- <a name="MetaR"></a> **(MetaR)** Mingyang Chen, Wen Zhang, Wei Zhang, Qiang Chen and Huajun Chen. "**Meta Relational Learning for Few-Shot Link Prediction in Knowledge Graphs**". **EMNLP/IJCNLP 2019**. CCF B. Cite 18.  [paper](https://www.aclweb.org/anthology/D19-1431/) [code](https://github.com/AnselCmy/MetaR)

- <a name="Meta-KGR"></a> **(Meta-KGR)** Xin Lv, Yuxian Gu, Xu Han, Lei Hou, Juanzi Li, Zhiyuan Liu. "**Adapting Meta Knowledge Graph Information for Multi-Hop Reasoning over Few-Shot Relations**". **EMNLP/IJCNLP 2019**. CCF B. Cite 9.  [paper](https://doi.org/10.18653/v1/D19-1334)

- <a name="CPL"></a> **(CPL)** Cong Fu, Tong Chen, Meng Qu, Woojeong Jin, Xiang Ren. "**Collaborative Policy Learning for Open Knowledge Graph Reasoning**". **EMNLP/IJCNLP 2019**. CCF B. Cite 7. [paper](https://doi.org/10.18653/v1/D19-1269)

- <a name="CaRe"></a> **(CaRe)** Swapnil Gupta, Sreyash Kenkre, Partha Talukdar. "**CaRe: Open Knowledge Graph Embeddings**". **EMNLP/IJCNLP 2019**. CCF B. Cite 3. [paper](https://www.aclweb.org/anthology/D19-1036/) [code](https://github.com/malllabiisc/CaRE)

- Heng Wang, Shuangyin Li, Rong Pan, Mingzhi Mao. "**Incorporating Graph Attention Mechanism into Knowledge Graph Reasoning Based on Deep Reinforcement Learning**". **EMNLP/IJCNLP 2019**. CCF B. Cite 3. [paper](https://www.aclweb.org/anthology/D19-1264/) 

- <a name="TCVAE"></a> **(TCVAE)** Zihao Wang, Kwunping Lai, Piji Li, Lidong Bing and Wai Lam. "**Tackling Long-Tailed Relations and Uncommon Entities in Knowledge Graph Completion**". **EMNLP/IJCNLP 2019**. CCF B. Cite 2.  [paper](https://www.aclweb.org/anthology/D19-1024/)

- <a name="OPTransE"></a> **(OPTransE)** Yao Zhu, Hongzhi Liu, Zhonghai Wu, Yang Song and Tao Zhang. "**Representation Learning with Ordered Relation Paths for Knowledge Graph Completion**". **EMNLP/IJCNLP 2019**. CCF B. Cite 2. [paper](https://www.aclweb.org/anthology/D19-1268/)

- <a name="JoBi ComplEx"></a> **(JoBi ComplEx)** Esma Balkir, Masha Naslidnyk, Dave Palfrey and Arpit Mittal. "**Using Pairwise Occurrence Information to Improve Knowledge Graph Completion on Large-Scale Datasets**". **EMNLP/IJCNLP 2019**. CCF B. Cite 0. [paper](https://www.aclweb.org/anthology/D19-1368/)

- Ondrej Kuzelka, Jesse Davis. "**Markov Logic Networks for Knowledge Base Completion: A Theoretical Analysis Under the MCAR Assumption**". **UAI 2019**. CCF B. Cite 4. [paper](http://auai.org/uai2019/proceedings/papers/427.pdf)

- <a name="EM"></a> **(EM)** Robert Bamler, Farnood Salehi, Stephan Mandt. "**Augmenting and Tuning Knowledge Graph Embeddings**". **UAI 2019**. CCF B. Cite 2. [paper](http://auai.org/uai2019/proceedings/papers/172.pdf) [code](https://github.com/mandt-lab/knowledge-graph-tuning)

- Agustinus Kristiadi, Mohammad Asif Khan, Denis Lukovnikov, Jens Lehmann, Asja Fischer. "**Incorporating Literals into Knowledge Graph Embeddings**. **ISWC 2019**. CCF B. Cite 17. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-30793-6_20)

- Zequn Sun, JiaCheng Huang, Wei Hu, Muhao Chen, Lingbing Guo, Yuzhong Qu. "**TransEdge: Translating Relation-Contextualized Embeddings for Knowledge Graphs**". **ISWC 2019**. CCF B. Cite 11. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-30793-6_35)

- Erik B. Myklebust, Ernesto Jiménez-Ruiz, Jiaoyan Chen, Raoul Wolf, Knut Erik Tollefsen. "**Knowledge Graph Embedding for Ecotoxicological Effect Prediction**". **ISWC 2019**. CCF B. Cite 8. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-30796-7_30)

- Mehdi Ali, Hajira Jabeen, Charles Tapley Hoyt, Jens Lehmann. "**The KEEN Universe - An Ecosystem for Knowledge Graph Embeddings with a Focus on Reproducibility and Transferability**". **ISWC 2019**. CCF B. Cite 6. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-30796-7_1)

- Changjian Wang, Minghui Yan, Chuanrun Yi, Ying Sha. "**Capturing Semantic and Syntactic Information for Link Prediction in Knowledge Graphs**". **ISWC 2019**. CCF B. Cite 1. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-30793-6_38)

- Simon Gottschalk, Elena Demidova. "**HapPenIng: Happen, Predict, Infer - Event Series Completion in a Knowledge Graph**". **ISWC 2019**. CCF B. Cite 0. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-30793-6_12)

- Vassilis N. Ioannidis, Antonio G. Marques, Georgios B. Giannakis. "**A Recurrent Graph Neural Network for Multi-relational Data**". **ICASSP 2019**. CCF B. Cite 11. [paper](https://ieeexplore.ieee.org/document/8682836)

- <a name="CapsE"></a> **(CapsE)** Dai Quoc Nguyen, Thanh Vu, Tu Dinh Nguyen, Dat Quoc Nguyen, Dinh Q. Phung. "**A Capsule Network-based Embedding Model for Knowledge Graph Completion and Search Personalization**". **NAACL-HLT 2019**. CCF C. Cite 43. [paper](https://www.aclweb.org/anthology/N19-1226/) [code](https://github.com/daiquocnguyen/CapsE) :fire:

- Xiaotian Jiang, Quan Wang, Bin Wang. "**Adaptive Convolution for Multi-Relational Learning**". **NAACL-HLT 2019**. CCF C. Cite 15. [paper](https://www.aclweb.org/anthology/N19-1103/)

- <a name="ConvR"></a> **(ConvR)** Xiaotian Jiang, Quan Wang, Bin Wang. "**Adaptive Convolution for Multi-Relational Learning**". **NAACL-HLT 2019**. CCF C. Cite 15. [paper](https://www.aclweb.org/anthology/N19-1103/)

- <a name="GRank"></a> **(GRank)** Takuma Ebisu, Ryutaro Ichise. "**Graph Pattern Entity Ranking Model for Knowledge Graph Completion**". **NAACL-HLT 2019**. CCF C. Cite 7. [paper](https://www.aclweb.org/anthology/N19-1104/)

- <a name="CRIAGE"></a> **(CRIAGE)** Pouya Pezeshkpour, Yifan Tian, Sameer Singh. “**Investigating Robustness and Interpretability of Link Prediction via Adversarial Modifications**”. **NAACL-HLT 2019**. CCF C. Cite 7. [paper](https://www.aclweb.org/anthology/N19-1337/) [code](https://github.com/pouyapez/criage)

- Dingcheng Li, Siamak Zamani, Jingyuan Zhang, Ping Li. "**Integration of Knowledge Graph Embedding Into Topic Modeling with Hierarchical Dirichlet Process**". **NAACL-HLT 2019**. CCF C. Cite 4. [paper](https://www.aclweb.org/anthology/N19-1099/)

- **(FFD)** Zihao Fu, Yankai Lin, Zhiyuan Liu, Wai Lam. "**Fact Discovery from Knowledge Base via Facet Decomposition**". 
**NAACL-HLT 2019**. CCF C. Cite 0. [paper](https://www.aclweb.org/anthology/N19-1297/)

- Ye Liu, Hui Li, Alberto García-Durán, Mathias Niepert, Daniel O?oro-Rubio, David S. Rosenblum. "**MMKG: Multi-modal Knowledge Graphs**". **ESWC 2019**. CCF C. Cite 11. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-21348-0_30)

- Sébastien Ferré. "**Link Prediction in Knowledge Graphs with Concepts of Nearest Neighbours**". **ESWC 2019**. CCF C. Cite 2. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-21348-0_6)

- <a name="CrossE"></a> **(CrossE)** Wen Zhang, Bibek Paudel, Wei Zhang, Abraham Bernstein, Huajun Chen. "**Interaction Embeddings for Prediction and Explanation in Knowledge Graphs**". **WSDM 2019**. CCF C. Cite 37. [paper](https://dl.acm.org/doi/10.1145/3289600.3291014) [code](https://github.com/wencolani/CrossE) :fire:

### 2020

#### Journal

##### Knowledge Based Systems

- <a name="ADRL"></a> **(ADRL)** Qi Wang, Yongsheng Hao, Jie Cao. "**ADRL: An attention-based deep reinforcement learning framework for knowledge graph reasoning**". **Knowl. Based Syst. 2020**. **Impact 5.921**. [paper](https://doi.org/10.1016/j.knosys.2020.105910)

- <a name="ConnectE"></a> **(ConnectE)** Yu Zhao, Anxiang Zhang, Huali Feng, Qing Li, Patrick Gallinari, Fuji Ren. "**Knowledge graph entity typing via learning connecting embeddings**". **Knowl. Based Syst. 2020**. **Impact 5.921**. [paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705120301921?via%3Dihub)

- <a name="GRL"></a> **(GRL)** Qi Wang, Yuede Ji, Yongsheng Hao, Jie Cao. "**GRL: Knowledge graph completion with GAN-based reinforcement learning**". **Knowl. Based Syst. 2020**. **Impact 5.921**. [paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705120305505?via%3Dihub)

- <a name="TransE&RW"></a> **(TransE&RW)** Chen Li, Xutan Peng, Shanghang Zhang, Hao Peng, Philip S. Yu, Min He, Linfen g Du, Lihong Wang. "**Modeling relation paths for knowledge base completion via joint adversarial training"**. **Knowl. Based Syst. 2020**. **Impact 5.921**. [paper](https://doi.org/10.1016/j.knosys.2020.105865)

- <a name="WDE"></a> **(WDE)** Yuanfei Dai, Shiping Wang, Xing Chen, Chaoyang Xu, Wenzhong Guo. "**Generative adversarial networks based on Wasserstein distance for knowledge graph embeddings**". **Knowl. Based Syst. 2020**. **Impact 5.921**. [paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705119305143?via%3Dihub)

##### Information Sciences

- <a name="FGEM"></a> **(FGEM)** Richong Zhang, Yongyi Mao, Weihua Zhao. "**Knowledge graphs completion via probabilistic reasoning**". **Inf. Sci. 2020**. **Impact 5.910**. [paper](https://www.sciencedirect.com/science/article/abs/pii/S0020025520300918?via%3Dihub)

- <a name="MAKR"></a> **(MAKR)** Yongming Han, GuoFei Chen, Zhongkun Li, Zhiqiang Geng, Fang Li, Bo Ma. "**An asymmetric knowledge representation learning in manifold space**". **Inf. Sci. 2020**. **Impact 5.910**. [paper](https://doi.org/10.1016/j.ins.2020.04.036)

##### Expert Systems with Applications

- Batselem Jagvaral, Wan-Kon Lee, Jae-Seung Roh, Min-Sung Kim, Young-Tack Park. "**Path-based reasoning approach for knowledge graph completion using CNN-BiLSTM with attention mechanism**". **Expert Syst. Appl. 2020**. **Impact 5.452**. [paper](https://www.sciencedirect.com/science/article/abs/pii/S0957417419306785?via%3Dihub)

- <a name="SDT"></a> **(SDT)** Xiaojun Chen, Shengbin Jia, Ling Ding, Hong Shen, Yang Xiang. "**SDT: An integrated model for open-world knowledge graph reasoning**". **Expert Syst. Appl. 2020**. **Impact 5.452**. [paper](https://www.sciencedirect.com/science/article/abs/pii/S0957417420306904?via%3Dihub)

##### IEEE Transactions on Knowledge and Data Engineering

- <a name="KGLG"></a> **(KGLG)** Takuma Ebisu, Ryutaro Ichise. "**Generalized Translation-Based Embedding of Knowledge Graph**". **IEEE Trans. Knowl. Data Eng. 2020**. **Impact 4.935**. [paper](https://doi.org/10.1109/TKDE.2019.2893920)

##### Neural Computing and Applications

- Kai Lei, Jin Zhang, Yuexiang Xie, Desi Wen, Daoyuan Chen, Min Yang, Ying Shen. "**Path-based reasoning with constrained type attention for knowledge graph completion**". **Neural Comput. Appl. 2020**. **Impact 4.774**. [paper](https://link.springer.com/article/10.1007%2Fs00521-019-04181-1)

- <a name="NKSGAN"></a> **(NKSGAN)** Hai Liu, Kairong Hu, Fu Lee Wang, Tianyong Hao. "**Aggregating neighborhood information for negative sampling for knowledge graph embedding**". **Neural Comput. Appl. 2020**. **Impact 4.774**. [paper](https://link.springer.com/article/10.1007%2Fs00521-020-04940-5)

##### Neurocomputing 

- <a name="ALSTM"></a> **(ALSTM)** Qi Wang , Yongsheng Hao. "**ALSTM: An attention-based long short-term memory framework for knowledge base reasoning**". **Neurocomputing 2020**. **Impact 4.438**. [paper](https://doi.org/10.1016/j.neucom.2020.02.065)

#### Conference

##### ICLR

- <a name="CompGCN"></a> **(CompGCN)** Shikhar Vashishth, Soumya Sanyal, Vikram Nitin, Partha Talukdar. "**Composition-based Multi-Relational Graph Convolutional Networks**". **ICLR 2020**. [paper](https://openreview.net/forum?id=BylA_C4tPr) [code](https://github.com/malllabiisc/CompGCN) :fire:

- <a name="DPMPN"></a> **(DPMPN)** Xiaoran Xu, Wei Feng, Yunsheng Jiang, Xiaohui Xie, Zhiqing Sun, Zhi-Hong Deng. "**Dynamically Pruned Message Passing Networks for Large-scale Knowledge Graph Reasoning**". **ICLR 2020**. [paper](https://openreview.net/forum?id=rkeuAhVKvB) [code](https://github.com/netpaladinx/DPMPN)

- <a name="DrKIT"></a> **(DrKIT)** Bhuwan Dhingra, Manzil Zaheer, Vidhisha Balachandran, Graham Neubig, Ruslan Salakhutdinov, William W. Cohen. "**Differentiable Reasoning over a Virtual Knowledge Base**". **ICLR 2020**. [paper](https://openreview.net/forum?id=SJxstlHFPH) :fire:

- <a name="Neural-LP-N"></a> **(Neural-LP-N)** Po-Wei Wang, Daria Stepanova, Csaba Domokos, J. Zico Kolter. "**Differentiable learning of numerical rules in knowledge graphs**". **ICLR 2020**. [paper](https://openreview.net/forum?id=rJleKgrKwS)

- Pedro Tabacof, Luca Costabello. "**Probability Calibration for Knowledge Graph Embedding Models**". **ICLR 2020**. [paper](https://openreview.net/forum?id=S1g8K1BFwS)

- <a name="Q2B"></a> **(Q2B)** Hongyu Ren, Weihua Hu, Jure Leskovec. "**Query2box: Reasoning over Knowledge Graphs in Vector Space Using Box Embeddings**". **ICLR 2020**. [paper](https://openreview.net/forum?id=BJgr4kSFDS) :fire:

- <a name="ReifKB"></a> **(ReifKB)**  William W. Cohen, Haitian Sun, R. Alex Hofer, Matthew Siegler. "**Scalable Neural Methods for Reasoning With a Symbolic Knowledge Base**". **ICLR 2020**. [paper](https://openreview.net/forum?id=BJlguT4YPr)

- <a name="TComplEx"></a> **(TComplEx)** Timothée Lacroix, Guillaume Obozinski, Nicolas Usunier. "**Tensor Decompositions for Temporal Knowledge Base Completion**". **ICLR 2020**. [paper](https://openreview.net/forum?id=rke2P1BFwS) 

- <a name="Teach"></a> **(Teach)** Daniel Ruffinelli, Samuel Broscheit, Rainer Gemulla. "**You CAN Teach an Old Dog New Tricks! On Training Knowledge Graph Embeddings**". **ICLR 2020**. [paper](https://openreview.net/forum?id=BkxSmlBFvr) :fire:

##### AAAI

- <a name="CoPER"></a> **(CoPER)** George Stoica, Otilia Stretcu, Anthony Platanios, Tom Mitchell, Barnabas Poczos. "**Contextual Parameter Generation for Knowledge Graph Link Prediction**". **AAAI 2020**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/5693)

- <a name="DE-SimplE"></a> **(DE-SimplE)** Rishab Goel, Seyed Mehran Kazemi, Marcus Brubaker, Pascal Poupart. "**Diachronic Embedding for Temporal Knowledge Graph Completion**". **AAAI 2020**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/5815) [code](https://github.com/BorealisAI/DE-SimplE) :fire:

- <a name="FSRL"></a> **(FSRL)** Chuxu Zhang, Huaxiu Yao, Chao Huang, Meng Jiang, Zhenhui Li, Nitesh V. Chawla. "**Few-Shot Knowledge Graph Completion**". **AAAI 2020**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/5698) [code](https://github.com/chuxuzhang/AAAI2020_FSRL)

- <a name="GNTPs"></a> **(GNTPs)** Pasquale Minervini, Matko Bosnjak, Tim Rocktäschel, Sebastian Riedel, Edward Grefenstette. "**Differentiable Reasoning on Large Knowledge Bases and Natural Language**". **AAAI 2020**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/5962) :fire:

- <a name="HAKE"></a> **(HAKE)** Zhanqiu Zhang, Jianyu Cai, Yongdong Zhang, Jie Wang. "**Learning Hierarchy-Aware Knowledge Graph Embeddings for Link Prediction**". **AAAI 2020**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/5701) [code](https://github.com/MIRALab-USTC/KGE-HAKE) :fire:

- <a name="InteractE"></a> **(InteractE)** Shikhar Vashishth, Soumya Sanyal, Vikram Nitin, Nilesh Agrawal, Partha Talukdar. "**InteractE: Improving Convolution-based Knowledge Graph Embeddings by Increasing Feature Interactions**". **AAAI 2020**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/5694) [code](https://github.com/malllabiisc/InteractE) [supp](https://shikhar-vashishth.github.io/assets/pdf/interacte_supp.pdf) :fire:

- <a name="ParamE"></a> **(ParamE)** Feihu Che, Dawei Zhang, Jianhua Tao, Mingyue Niu, Bocheng Zhao. "**ParamE: Regarding Neural Network Parameters as Relation Embeddings for Knowledge Graph Completion**". **AAAI 2020**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/5665)

- <a name="R2D2"></a> **(R2D2)** Marcel Hildebrandt, Jorge Andres Quintero Serna, Yunpu Ma, Martin Ringsquandl, Mitchell Joblin, Volker Tresp. "**Reasoning on Knowledge Graphs with Debate Dynamics**". **AAAI 2020**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/6600)

- <a name="RGHAT"></a> **(RGHAT)** Zhao Zhang, Fuzhen Zhuang, Hengshu Zhu, Zhiping Shi, Hui Xiong, Qing He. "**Relational Graph Neural Network with Hierarchical Attention for Knowledge Graph Completion**". **AAAI 2020**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/6508)

- <a name="Robust"></a> **(Robust)** Peru Bhardwaj. "**Towards Adversarially Robust Knowledge Graph Embeddings**. **AAAI 2020**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/7128)

- <a name="RPJE"></a> **(RPJE)** Guanglin Niu, Yongfei Zhang, Bo Li, Peng Cui, Si Liu, Jingyang Li, Xiaowei Zhang. "**Rule-Guided Compositional Representation Learning on Knowledge Graphs**". **AAAI 2020**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/5687)

- Chaitanya Malaviya, Chandra Bhagavatula, Antoine Bosselut, Yejin Choi. "**Commonsense Knowledge Base Completion with Structural and Semantic Context**". **AAAI 2020**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/5684) :fire:

- <a name="ZSGAN"></a> **(ZSGAN)** Pengda Qin, Xin Wang, Wenhu Chen, Chunyun Zhang, Weiran Xu, William Yang Wang. "**Generative Adversarial Zero-Shot Relational Learning for Knowledge Graphs**". **AAAI 2020**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/6392) [code](https://github.com/Panda0406/Zero-shot-knowledge-graph-relational-learning)

##### NeurIPS

- <a name="BETAE"></a> **(BETAE)** Hongyu Ren, Jure Leskovec. "**Beta Embeddings for Multi-Hop Logical Reasoning in Knowledge Graphs**". **NeurIPS 2020**. [paper](https://proceedings.neurips.cc/paper/2020/hash/e43739bba7cdb577e9e3e4e42447f5a5-Abstract.html)

- <a name="GEN"></a> **(GEN)** Jinheon Baek, Dong Bok Lee, Sung Ju Hwang. "**Learning to Extrapolate Knowledge: Transductive Few-shot Out-of-Graph Link Prediction**". **NeurIPS 2020**. [paper](https://neurips.cc/virtual/2020/public/poster_0663a4ddceacb40b095eda264a85f15c.html) [code](https://github.com/JinheonBaek/GEN)

- <a name="Interstellar"></a> **(Interstellar)** Yongqi Zhang, Quanming Yao, Lei Chen. "**Interstellar: Searching Recurrent Architecture for Knowledge Graph Embedding**". **NeurIPS 2020**. [paper](https://proceedings.neurips.cc/paper/2020/hash/722caafb4825ef5d8670710fa29087cf-Abstract.html)

##### ACL

- <a name="Compression"></a> **(Compression)** Mrinmaya Sachan. "**Knowledge Graph Embedding Compression**". **ACL 2020**. [paper](https://www.aclweb.org/anthology/2020.acl-main.238/)

- <a name="ConnectE"></a> **(ConnectE)** Yu Zhao, anxiang zhang, Ruobing Xie, Kang Liu and Xiaojie WANG. "**Connecting Embeddings for Knowledge Graph Entity Typing**". **ACL 2020**. [paper](https://www.aclweb.org/anthology/2020.acl-main.572/)

- Ines Chami, Adva Wolf, Da-Cheng Juan, Frederic Sala, Sujith Ravi and Christopher Ré. "**Low-Dimensional Hyperbolic Knowledge Graph Embeddings**". **ACL 2020**. [paper](https://www.aclweb.org/anthology/2020.acl-main.617/)

- <a name="OLP"></a> **(OLP)** Samuel Broscheit, Kiril Gashteovski, Yanjie Wang, Rainer Gemulla. "**Can We Predict New Facts with Open Knowledge Graph Embeddings? A Benchmark for Open Link Prediction**". **ACL 2020**. [paper](https://www.aclweb.org/anthology/2020.acl-main.209/)

- <a name="OTE"></a> **(OTE)** Yun Tang, Jing Huang, Guangtao Wang, Xiaodong He, Bowen Zhou. "**Orthogonal Relation Transforms with Graph Context Modeling for Knowledge Graph Embedding**". **ACL 2020**. [paper](https://www.aclweb.org/anthology/2020.acl-main.241/)

- <a name="Re-evaluation"></a> **(Re-evaluation)** Zhiqing Sun, Shikhar Vashishth, Soumya Sanyal, Partha Talukdar and Yiming Yang. "**A Re-evaluation of Knowledge Graph Completion Methods**". **ACL 2020**. [paper](https://www.aclweb.org/anthology/2020.acl-main.489/) :fire:

- <a name="ReInceptionE"></a> **(ReInceptionE)** Zhiwen Xie, Guangyou Zhou, Jin Liu and Jimmy Xiangji Huang. "**ReInceptionE: Relation-Aware Inception Network with Joint Local-Global Structural Information for Knowledge Graph Embedding**". **ACL 2020**. [paper](https://www.aclweb.org/anthology/2020.acl-main.526/)

- <a name="SEEK"></a> **(SEEK)** Wentao Xu, Shun Zheng, Liang He, Bin Shao, Jian Yin and Tie-Yan Liu. "**SEEK: Segmented Embedding of Knowledge Graphs**". **ACL 2020**. [paper](https://www.aclweb.org/anthology/2020.acl-main.358/)

##### ICML

- <a name="LowFER"></a> **(LowFER)** Saadullah Amin, Stalin Varanasi, Katherine Ann Dunfield, Günter Neumann. "**LowFER: Low-rank Bilinear Pooling for Link Prediction**". **ICML 2020**. [paper](http://proceedings.mlr.press/v119/amin20a)

##### IJCAI

- <a name="DArtNet"></a> **(DArtNet)** Sankalp Garg, Navodita Sharma, Woojeong Jin, Xiang Ren. "**Temporal Attribute Prediction via Joint Modeling of Multi-Relational Structure Evolution**". **IJCAI 2020**. [paper](https://www.ijcai.org/Proceedings/2020/386) [code](https://github.com/INK-USC/DArtNet)

- <a name="HypE"></a> **(HypE)** Bahare Fatemi, Perouz Taslakian, David Vázquez, David Poole. "**Knowledge Hypergraphs: Prediction Beyond Binary Relations**". **IJCAI 2020**. [paper](https://www.ijcai.org/Proceedings/2020/303)

- <a name="TransRHS"></a> **(TransRHS)** Fuxiang Zhang, Xin Wang, Zhao Li, Jianxin Li. "**TransRHS: A Representation Learning Method for Knowledge Graphs with Relation Hierarchical Structure**". **IJCAI 2020**. [paper](https://doi.org/10.24963/ijcai.2020/413)

##### EMNLP

- <a name="Calibration"></a> **(Calibration)** JTara Safavi, Danai Koutra, Edgar Meij. "**Evaluating the Calibration of Knowledge Graph Embeddings for Trustworthy Link Prediction**". **EMNLP 2020**. [paper](https://www.aclweb.org/anthology/2020.emnlp-main.667/)

- <a name="DacKGR"></a> **(DacKGR)** Xin Lv, Xu Han, Lei Hou, Juanzi Li, Zhiyuan Liu, Wei Zhang, Yichi Zhang, Hao Kong, Suhui Wu. "**Dynamic Anticipation and Completion for Multi-Hop Reasoning over Sparse Knowledge Graph**". **EMNLP 2020**. [paper](https://www.aclweb.org/anthology/2020.emnlp-main.667/)

- <a name="DebiasE"></a> **(DebiasE)** Joseph Fisher, Arpit Mittal, Dave Palfrey, Christos Christodoulopoulos. "**Debiasing knowledge graph embeddings**". **EMNLP 2020**. [paper](https://www.aclweb.org/anthology/2020.emnlp-main.595/)

- <a name="DyERNIE"></a> **(DyERNIE)** Zhen Han, Peng Chen, Yunpu Ma, Volker Tresp. "**DyERNIE: Dynamic Evolution of Riemannian Manifold Embeddings for Temporal Knowledge Graph Completion**". **EMNLP 2020**. [paper](https://www.aclweb.org/anthology/2020.emnlp-main.593/)

- <a name="FAAN"></a> **(FAAN)** Jiawei Sheng, Shu Guo, Zhenyu Chen, Juwei Yue, Lihong Wang, Tingwen Liu, Hongbo Xu. "**Adaptive Attentional Network for Few-Shot Knowledge Graph Completion**". **EMNLP 2020**. [paper](https://www.aclweb.org/anthology/2020.emnlp-main.131/) [code](https://github.com/JiaweiSheng/FAAN)

- <a name="HyperKA"></a> **(HyperKA)** Zequn Sun, Muhao Chen, Wei Hu, Chengming Wang, Jian Dai, Wei Zhang. "**Knowledge Association with Hyperbolic Knowledge Graph Embeddings**". **EMNLP 2020**. [paper](https://www.aclweb.org/anthology/2020.emnlp-main.460/)

- <a name="RE-Net"></a> **(RE-Net)** Woojeong Jin, Meng Qu, Xisen Jin, Xiang Ren. "**Recurrent Event Network: Autoregressive Structure Inferenceover Temporal Knowledge Graphs**". **EMNLP 2020**. [paper](https://www.aclweb.org/anthology/2020.emnlp-main.541/)

- <a name="TeMP"></a> **(TeMP)** Jiapeng Wu, Meng Cao, Jackie Chi Kit Cheung, William L. Hamilton. "**TeMP: Temporal Message Passing for Temporal Knowledge Graph Completion**". **EMNLP 2020**. [paper](https://www.aclweb.org/anthology/2020.emnlp-main.462/)

- <a name="TIMEPLEX"></a> **(TIMEPLEX)** Prachi Jain, Sushant Rathi, Mausam, Soumen Chakrabarti. "**Temporal Knowledge Base Completion: New Algorithms and Evaluation Protocols**". **EMNLP 2020**. [paper](https://www.aclweb.org/anthology/2020.emnlp-main.305/)

- <a name="AutoETER"></a> **(AutoETER)** Guanglin Niu, Bo Li, Yongfei Zhang, Shiliang Pu, Jingyang Li. "**AutoETER: Automated Entity Type Representation with Relation-Aware Attention for Knowledge Graph Embedding**". **EMNLP (Findings) 2020**. [paper](https://www.aclweb.org/anthology/2020.findings-emnlp.105/)

- <a name="B-CP"></a> **(B-CP)** Katsuhiko Hayashi, Koki Kishimoto, Masashi Shimbo. "**A Greedy Bit-flip Training Algorithm for Binarized Knowledge Graph Embeddings**". **EMNLP (Findings) 2020**. [paper](https://www.aclweb.org/anthology/2020.findings-emnlp.10/)

- <a name="FIRE"></a> **(FIRE)** Chuxu Zhang, Lu Yu, Mandana Saebi, Meng Jiang, Nitesh V. Chawla. "**Few-Shot Multi-Hop Relation Reasoning over Knowledge Bases**". **EMNLP (Findings) 2020**. [paper](https://www.aclweb.org/anthology/2020.findings-emnlp.51/)

##### ECAI

- <a name="BTDE"></a> **(BTDE)** Tao Luo, Yifan Wei, Mei Yu, Xuewei Li, Mankun Zhao, Tianyi Xu, Jian Yu, Jie Gao, Ruiguo Yu. "**BTDE: Block Term Decomposition Embedding for Link Prediction in Knowledge Graph**". **ECAI 2020**. [paper](http://ebooks.iospress.nl/publication/54966)

- <a name="HALF"></a> **(HALF)** Meng Wang, Tongtong Wu, Guilin Qi. "**A Hash Learning Framework for Search-Oriented Knowledge Graph Embedding**". **ECAI 2020**. [paper](http://ebooks.iospress.nl/publication/54979)

- <a name="MDE"></a> **(MDE)** Afshin Sadeghi, Damien Graux, Hamed Shariat Yazdi, Jens Lehmann. "**MDE: Multiple Distance Embeddings for Link Prediction in Knowledge Graphs**". **ECAI 2020**. [paper](http://ebooks.iospress.nl/publication/55043)

- <a name="MEI"></a> **(MEI)** Hung Nghiep Tran, Atsuhiro Takasu. "**Multi-Partition Embedding Interaction with Block Term Format for Knowledge Graph Completion**". **ECAI 2020**. [paper](http://ebooks.iospress.nl/publication/54979)

##### COLING

- <a name="AcrE"></a> **(AcrE)** Feiliang Ren, Juchen Li, Huihui Zhang, Shilei Liu, Bochao Li, Ruicheng Ming, Yujia Bai. "**Knowledge Graph Embedding with Atrous Convolution and Residual Learning**". **COLING 2020**. [paper](https://www.aclweb.org/anthology/2020.coling-main.134/)

- <a name="AprilE"></a> **(AprilE)** Yuzhang Liu, Peng Wang, Yingtai Li, Yizhan Shao, Zhongkai Xu. "**AprilE: Attention with Pseudo Residual Connection for Knowledge Graph Embedding**". **COLING 2020**. [paper](https://www.aclweb.org/anthology/2020.coling-main.44/)

- <a name="GeomE"></a> **(GeomE)** Chengjin Xu, Mojtaba Nayyeri, Yung-Yu Chen, Jens Lehmann. "**Knowledge Graph Embeddings in Geometric Algebras**". **COLING 2020**. [paper](https://www.aclweb.org/anthology/2020.coling-main.46/)

- <a name="RatE"></a> **(RatE)** Hao Huang, Guodong Long, Tao Shen, Jing Jiang, Chengqi Zhang. "**RatE: Relation-Adaptive Translating Embedding for Knowledge Graph Completion**". **COLING 2020**. [paper](https://www.aclweb.org/anthology/2020.coling-main.48/)

- <a name="TeRo"></a> **(TeRo)** Chengjin Xu, Mojtaba Nayyeri, Fouad Alkhoury, Hamed Shariat Yazdi, Jens Lehmann. "**TeRo: A Time-aware Knowledge Graph Embedding via Temporal Rotation**". **COLING 2020**. [paper](https://www.aclweb.org/anthology/2020.coling-main.139/)

##### UAI

- Aisha Mohamed, Shameem Puthiya Parambath, Zoi Kaoudi, Ashraf Aboulnaga. "**Popularity Agnostic Evaluation of Knowledge Graph Embeddings**". **UAI 2020**. [paper](http://proceedings.mlr.press/v124/mohamed20a.html)

##### AAMAS

- <a name="TransL"></a> **(TransL)** Zeyuan Cui, Shijun Liu, Li Pan, Qiang He. "**Translating Embedding with Local Connection for Knowledge Graph Completion**". **AAMAS 2020**. [paper](https://dl.acm.org/doi/abs/10.5555/3398761.3398995)

##### SIGMOD

- <a name="Re-evaluation"></a> **(Re-evaluation)** Farahnaz Akrami, Mohammed Samiul Saeef, Qingheng Zhang, Wei Hu, Chengkai Li. "**Realistic Re-evaluation of Knowledge Graph Completion Methods: An Experimental Study**". **SIGMOD 2020**. [paper](https://dl.acm.org/doi/10.1145/3318464.3380599)

##### ICDE

- <a name="AutoSF"></a> **(AutoSF)** Yongqi Zhang, Quanming Yao, Wenyuan Dai, Lei Chen. "**AutoSF: Searching Scoring Functions for Knowledge Graph Embedding**". **ICDE 2020**. [paper](https://doi.org/10.1109/ICDE48307.2020.00044)

##### SIGIR

- <a name="DGL-KE"></a> **(DGL-KE)**	Da Zheng, Xiang Song, Chao Ma, Zeyuan Tan, Zihao Ye, Jin Dong, Hao Xiong, Zheng Zhang, George Karypis. "**DGL-KE: Training Knowledge Graph Embeddings at Scale**". **SIGIR 2020**. [paper](https://dl.acm.org/doi/10.1145/3397271.3401172)

##### CIKM

- <a name="ELP"></a> **(ELP)**	Russa Biswas. "**Embedding based Link Prediction for Knowledge Graph Completion**". **CIKM 2020**. [paper](https://dl.acm.org/doi/10.1145/3340531.3418512)

- <a name="NagE"></a> **(NagE)** Tong Yang, Long Sha, Pengyu Hong. "**NagE: Non-Abelian Group Embedding for Knowledge Graphs**". **CIKM 2020**. [paper](https://dl.acm.org/doi/10.1145/3340531.3411875)

- <a name="NASE"></a> **(NASE)** Xiaoyu Kou, Bingfeng Luo, Huang Hu, Yan Zhang. "**NASE: Learning Knowledge Graph Embedding for Link Prediction via Neural Architecture Search**". **CIKM 2020**. [paper](https://dl.acm.org/doi/10.1145/3340531.3412104)

- <a name="SLRE"></a> **(SLRE)** Shu Guo, Lin Li, Zhen Hui, Lingshuai Meng, Bingnan Ma, Wei Liu, Lihong Wang, Haibin Zhai, Hong Zhang. "**Knowledge Graph Embedding Preserving Soft Logical Regularity**". **CIKM 2020**. [paper](https://dl.acm.org/doi/10.1145/3340531.3412055)

- Iti Bansal, Sudhanshu Tiwari, Carlos R. Rivero. "**The Impact of Negative Triple Generation Strategies and Anomalies on Knowledge Graph Completion**". **CIKM 2020**. [paper](https://dl.acm.org/doi/10.1145/3340531.3412023)

- Hao Tian, Reza Zafarani. "**Exploiting Common Neighbor Graph for Link Prediction**". **CIKM 2020**. [paper](https://dl.acm.org/doi/10.1145/3340531.3412023)

- Chang Gao, Chengjie Sun, Lili Shan, Lei Lin, Mingjiang Wang. "**Rotate3D: Representing Relations as Rotations in Three-Dimensional Space for Knowledge Graph Embedding**". **CIKM 2020**. [paper](https://dl.acm.org/doi/10.1145/3340531.3411889)

- Yanfei Han, Quan Fang, Jun Hu, Shengsheng Qian, Changsheng Xu. "**GAEAT: Graph Auto-Encoder Attention Networks for Knowledge Graph Completion**". **CIKM 2020**. [paper](https://dl.acm.org/doi/10.1145/3340531.3412148)

- Julien Leblay, Melisachew Wudage Chekol, Xin Liu. "**Towards Temporal Knowledge Graph Embeddings with Arbitrary Time Precision**". **CIKM 2020**. [paper](https://dl.acm.org/doi/10.1145/3340531.3412028)

- Garima Gaur, Arnab Bhattacharya, Srikanta Bedathur. "**How and Why is An Answer (Still) Correct? Maintaining Provenance in Dynamic Knowledge Graphs**". **CIKM 2020**. [paper](https://dl.acm.org/doi/10.1145/3340531.3411958)

##### ISWC

- <a name="ATiSE"></a> **(ATiSE)** Chenjin Xu, Mojtaba Nayyeri, Fouad Alkhoury, Hamed Shariat Yazdi, Jens Lehmann. "**Temporal Knowledge Graph Completion Based on Time Series Gaussian Embedding**". **ISWC 2020**. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-62419-4_37)

- <a name="EKGR"></a> **(EKGR)** Rajarshi Bhowmik, Gerard de Melo. "**Temporal Knowledge Graph Completion Based on Time Series Gaussian Embedding**". **ISWC 2020**. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-62419-4_3)

- <a name="BCRL"></a> **(BCRL)** Gang Wu, Wenfang Wu, Leilei Li, Guodong Zhao, Donghong Han, Baiyou Qiao. "**BCRL: Long Text Friendly Knowledge Graph Representation Learning**". **ISWC 2020**. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-62419-4_36)

- Mojtaba Nayyeri, Chengjin Xu, Sahar Vahdati, Nadezhda Vassilyeva, Emanuel Sallinger, Hamed Shariat Yazdi, Jens Lehmann. "**Fantastic Knowledge Graph Embeddings and How to Find the Right Space for Them**". **ISWC 2020**. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-62419-4_25)

##### ESWC

- <a name="HyperKG"></a> **(HyperKG)** Prodromos Kolyvakis, Alexandros Kalousis, Dimitris Kiritsis. "**Hyperbolic Knowledge Graph Embeddings for Knowledge Base Completion**". **ESWC 2020**. [paper](https://doi.org/10.1007/978-3-030-49461-2_12)

- <a name="YAGO4"></a> **(YAGO4)** Thomas Pellissier Tanon, Gerhard Weikum, Fabian M. Suchanek. "**YAGO 4: A Reason-able Knowledge Base**. **ESWC 2020**. [paper](https://doi.org/10.1007/978-3-030-49461-2_34)

##### WWW

- Jiaoyan Chen, Xi Chen, Ian Horrocks, Ernesto Jiménez-Ruiz, Erik B. Myklebust. "**Correcting Knowledge Base Assertions**". **WWW 2020**. [paper](https://dl.acm.org/doi/10.1145/3366423.3380226)

- <a name="GETD"></a> **(GETD)** Yu Liu, Quanming Yao, Yong Li. "**Generalizing Tensor Decomposition for N-ary Relational Knowledge Bases**. **WWW 2020**. [paper](https://dl.acm.org/doi/10.1145/3366423.3380188)

- <a name="HINGE"></a> **(HINGE)** Paolo Rosso, Dingqi Yang, Philippe Cudré-Mauroux. "**Beyond Triplets: Hyper-Relational Knowledge Graph Embedding for Link Prediction**". **WWW 2020**. [paper](https://doi.org/10.1145/3366423.3380257)

- Unmesh Joshi, Jacopo Urbani. "**Searching for Embeddings in a Haystack: Link Prediction on Knowledge Graphs with Subgraph Pruning**". **WWW 2020**. [paper](https://doi.org/10.1145/3366423.3380043)

- Liang Qu, Huaisheng Zhu, Qiqi Duan, Yuhui Shi. "**Continuous-Time Link Prediction via Temporal Dependent Graph Neural Network**". **WWW 2020**. [paper](https://dl.acm.org/doi/10.1145/3366423.3380073)

#### Arxiv

- Da Xu, Chuanwei Ruan, Jason Cho, Evren Körpeoglu, Sushant Kumar, Kannan Achan. "**Knowledge-aware Complementary Product Representation Learning**". **WSDM 2020**. [paper](https://doi.org/10.1145/3336191.3371854)

## Datasets

### Standard

### Rule

### Text

### Temporal

## Performance

### Link Prediction

#### ICEWS14

| Year | Source | Methods     |  MR |  MRR  | Hits@1 | Hits@3 | Hits@10 |
|:----:|:------:|:-----------:|:---:|:-----:|:------:|:------:|:-------:|
| 2018 | EMNLP  | **[TA-DistMult](#TA-DistMult)** | 276 | 0.477 | 0.363  | -      | 0.686   |
| 2018 | EMNLP  | **[HyTE](#HyTE)<sup>[DE-SinplE](#DE-SimplE)</sup>** | - | 0.297 | 0.108 | 0.416 | 0.655 |
| 2020 | AAAI   | **[DE-TransE](#DE-SimplE)** | - | 0.326 | 0.124 | 0.467 | 0.686 |
| 2020 | AAAI   | **[DE-DistMult](#DE-SimplE)** | - | 0.501 | 0.392 | 0.569 | 0.708 |
| 2020 | AAAI   | **[DE-SimplE](#DE-SimplE)** | - | 0.526 | 0.418 | 0.592 | 0.725 |
| 2020 | ICLR   | **[TNTComplEx](#TNTComplEx)**  | -   | 0.56  | 0.46   | 0.61   | 0.74    |


