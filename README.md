# KGE
Some papers on Knowledge Graph Embedding(KGE)

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
- Scikit-KGE [code](https://github.com/mnick/scikit-kge)

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

#### Temporal

| Year | Source        |	Methods                        |
|:----:|:-------------:|:-------------------------------:|
| 2014 | EMNLP         | **[CTPs](#CTPs)**               |
| 2016 | EMNLP         | **[t-TransE](#t-TransE)**       |
| 2016 | COLING        | **[TransE-TAE](#TransE-TAE)**   |
| 2017 | ICML          | **[Know-Evolve](#Know-Evolve)** |
| 2017 | AAAI          | **[MLNs](#MLNs)**               |
| 2018 | WWW           | **[TTransE](#TTransE)**         |
| 2018 | EMNLP         | **[TA-DistMult](#TA-DistMult)** |
| 2018 | EMNLP         | **[HyTE](#HyTE)**               |
| 2019 | ICLR          | **[DyRep](#DyRep)**             |
| 2019 | J. Web Semant | **[ConT](#ConT)**               |
| 2020 | ICLR          | **[TComplEx](#TComplEx)**       |
| 2020 | AAAI          | **[DE-SimplE](#DE-SimplE)**     |

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

## Papers

### Survey

- Yoshua Bengio, Aaron C. Courville, Pascal Vincent. "**Representation Learning: A Review and New Perspectives**". **IEEE Transactions on Pattern Analysis and Machine Intelligence 2013**. [paper](https://ieeexplore.ieee.org/document/6472238)

- Maximilian Nickel, Kevin Murphy, Volker Tresp, Evgeniy Gabrilovich. "**A Review of Relational Machine Learning for Knowledge Graphs**". **Proceedings of the IEEE 2016**. [paper](https://ieeexplore.ieee.org/document/7358050)

- Quan Wang, Zhendong Mao, Bin Wang, Li Guo. "**Knowledge Graph Embedding: A Survey of Approaches and Applications**". **IEEE Transactions on Knowledge and Data Engineering 2017**. [paper](https://ieeexplore.ieee.org/document/8047276)

- HongYun Cai, Vincent W. Zheng, Kevin Chen-Chuan Chang. "**A Comprehensive Survey of Graph Embedding: Problems, Techniques, and Applications**". **IEEE Transactions on Knowledge and Data Engineering 2018**. [paper](https://ieeexplore.ieee.org/document/8294302)

- Xiaojun Chen, Shengbin Jia, Yang Xiang. "**A review: Knowledge reasoning over knowledge graph**". **Expert Systems with Applications 2020**. [paper](https://www.sciencedirect.com/science/article/pii/S0957417419306669?via%3Dihub)

- Seyed Mehran Kazemi, Rishab Goel, Kshitij Jain, Ivan Kobyzev, Akshay Sethi, Peter Forsyth, Pascal Poupart. "**Relational 
Representation Learning for Dynamic (Knowledge) Graphs: A Survey**". **arxiv 2019-05**. [paper](https://arxiv.org/abs/1905.11485)

- Shaoxiong Ji, Shirui Pan, Erik Cambria, Pekka Marttinen, Philip S. Yu. "**A Survey on Knowledge Graphs: Representation, Acquisition and Applications**". **arxiv 2020-02**. [paper](https://arxiv.org/abs/2002.00388)

- Andrea Rossi, Donatella Firmani, Antonio Matinata, Paolo Merialdo, Denilson Barbosa. "**Knowledge Graph Embedding for Link Prediction: A Comparative Analysis**". **arxiv 2020-02**. [paper](https://arxiv.org/abs/2002.00819)

### Journal

#### 2017

- **(ComplEx)** Théo Trouillon, Christopher R. Dance, Éric Gaussier, Johannes Welbl, Sebastian Riedel, Guillaume Bouchard. "**Knowledge Graph Completion via Complex Tensor Factorization**". **Journal of Machine Learning Research 2017**. [paper](http://jmlr.org/papers/v18/16-563.html) [code](https://github.com/ttrouill/complex)

- **(LPMR)** Caiyan Dai, Ling Chen, Bin Li, Yun Li. "**Link prediction in multi-relational networks based on relational similarity**". **Information Sciences 2017**. [paper](https://www.sciencedirect.com/science/article/pii/S0020025517304139?via%3Dihub)

- Lidong Bing, Zhiming Zhang, Wai Lam, William W. Cohen. "**Towards a language-independent solution: Knowledge base completion by searching the Web and deriving language pattern**". **Knowledge-based Systems 2017**. [paper](https://www.sciencedirect.com/science/article/pii/S0950705116303859?via%3Dihub)

- **(TransPES)** Yu Wu, Tingting Mu, John Yannis Goulermas. "**Translating on pairwise entity space for knowledge graph embedding**". **Neurocomputing 2017**. [paper](https://www.sciencedirect.com/science/article/pii/S0925231217307968?via%3Dihub) [code](https://github.com/while519/TranPES)

- **(SSE)** Shu Guo, Quan Wang, Bin Wang, Lihong Wang, Li Guo. "**SSE: Semantically Smooth Embedding for Knowledge Graphs**". **IEEE Transactions on Knowledge and Data Engineering 2017**. [paper](https://ieeexplore.ieee.org/document/7779046)

- **(TRANSFER)** Xiaochi Wei, Heyan Huang, Liqiang Nie, Hanwang Zhang, Xianling Mao, Tat-Seng Chua. "**I Know What You Want to Express: Sentence Element Inference by Incorporating External Knowledge Base**". **IEEE Transactions on Knowledge and Data Engineering 2017**. [paper](https://ieeexplore.ieee.org/document/7723822) [code](https://datapublication.wixsite.com/transfer)

#### 2018

- **(PaSKoGE)** Yantao Jia, Yuanzhuo Wang, Xiaolong Jin, Xueqi Cheng. "**Path-specific knowledge graph embedding**". **Knowledge-based Systems 2018**. [paper](https://www.sciencedirect.com/science/article/pii/S0950705118301448?via%3Dihub)

- Lirong He, Bin Liu, Guangxi Li, Yongpan Sheng, Yafang Wang, Zenglin Xu. "**Knowledge Base Completion by Variational Bayesian Neural Tensor Decomposition**". **Cognitive Computation 2018**. [paper](https://link.springer.com/article/10.1007%2Fs12559-018-9565-x)

#### 2019

- **(TKGE)** Binling Nie, Shouqian Sun. "**Knowledge graph embedding via reasoning over entities, relations, and text**". **Future Generation Computer Systems 2019**. [paper](https://www.sciencedirect.com/science/article/pii/S0167739X17321593?via%3Dihub)

- Chengchun Shi, Wenbin Lu, Rui Song. "**Determining the Number of Latent Factors in Statistical Multi-Relational Learning**". **Journal of Machine Learning Research 2019**. [paper](http://jmlr.org/papers/v20/18-037.html)

- **(KEC)** Niannian Guan, Dandan Song, Lejian Liao. "**Knowledge graph embedding with concepts**". **Knowledge-based Systems 2019**. [paper](https://www.sciencedirect.com/science/article/pii/S0950705118304945?via%3Dihub)

- **(ProjFE)** Huajing Liu, Luyi Bai, Xiangnan Ma, Wenting Yu, Changming Xu. "**ProjFE: Prediction of fuzzy entity and relation for knowledge graph completion**". **Applied Soft Computing 2019**. [paper](https://www.sciencedirect.com/science/article/pii/S1568494619302959?via%3Dihub)

- **(RPE)** Xixun Lin, Yanchun Liang, Fausto Giunchiglia, Xiaoyue Feng, Renchu Guan. "**Relation path embedding in knowledge graphs**". **Neural Computing and Applications 2019**. [paper](https://link.springer.com/article/10.1007%2Fs00521-018-3384-6)

- Qiannan Zhu, Xiaofei Zhou, Peng Zhang, Yong Shi. "**A neural translating general hyperplane for knowledge graph embedding**". **Journal of Computational Science 2019**. [paper](https://www.sciencedirect.com/science/article/pii/S1877750318310172?via%3Dihub)

- Ankur Padia, Konstantinos Kalpakis, Francis Ferraro, Tim Finin. "**Knowledge Graph Fact Prediction via Knowledge-Enriched Tensor Factorization**". **Journal of Web Semantics 2019**. [paper](https://www.sciencedirect.com/science/article/pii/S1570826819300046?via%3Dihub) [code](https://github.com/Ebiquity/KGFP)

- <a name="ConT"></a> **(ConT)** Yunpu Ma, Volker Tresp, Erik A. Daxberger. "**Embedding models for episodic knowledge graphs**". **Journal of Web Semantics 2019**. [paper](https://www.sciencedirect.com/science/article/pii/S1570826818300702?via%3Dihub)

- **(AWML)** Chenchen Guo, Chunhong Zhang, Xiao Han, Yang Ji. "**AWML: adaptive weighted margin learning for knowledge
graph embedding**". **Journal of Intelligent Information Systems 2019**. [paper](https://link.springer.com/article/10.1007%2Fs10844-018-0535-2)

#### 2020

- Yuanfei Dai, Shiping Wang, Xing Chen, Chaoyang Xu, Wenzhong Guo. "**Generative adversarial networks based on Wasserstein distance for knowledge graph embeddings**". **Knowledge Based Systems 2020**. [paper](https://www.sciencedirect.com/science/article/abs/pii/S0950705119305143?via%3Dihub)

- Batselem Jagvaral, Wan-Kon Lee, Jae-Seung Roh, Min-Sung Kim, Young-Tack Park. "**Path-based reasoning approach for knowledge graph completion using CNN-BiLSTM with attention mechanism**". **Expert Systems with Applications 2020**. [paper](https://www.sciencedirect.com/science/article/abs/pii/S0957417419306785?via%3Dihub)

- Jia Zhu, Zetao Zheng, Min Yang, Gabriel Pui Cheong Fung, Yong Tang. "**A semi-supervised model for knowledge graph embedding**". **Data Mining and Knowledge Discovery 2020**. [paper](https://link.springer.com/article/10.1007%2Fs10618-019-00653-z)

### Conference

### 2011

- <a name="RESCAL"></a> **(RESCAL)** Nickel Maximilian, Tresp Volker, Kriegel Hans-Peter. "**A Three-Way Model for Collective Learning on Multi-Relational Data**". **ICML 2011**. [paper](https://icml.cc/2011/papers/438_icmlpaper.pdf) [code](https://github.com/mnick/scikit-kge)

- <a name="SE"></a> **(SE)** Antoine Bordes, Jason Weston, Ronan Collobert, Yoshua Bengio. "**Learning Structured Embeddings of Knowledge Bases**". **AAAI 2011**. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI11/paper/view/3659)

### 2012

- <a name="LFM"></a> **(LFM)** Rodolphe Jenatton, Nicolas L. Roux, Antoine Bordes, Guillaume R. Obozinski. "**A Latent Factor Model for Highly Multi-relational Data**". **NIPS 2012**. [paper](http://papers.nips.cc/paper/4744-a-latent-factor-model-for-highly-multi-relational-data)

### 2013

- <a name="NTN"></a> **(SLM/NTN)** Richard Socher, Danqi Chen, Christopher D. Manning, Andrew Y. Ng. "**Reasoning With Neural Tensor Networks for Knowledge Base Completion**". **NIPS 2013**. [paper](http://papers.nips.cc/paper/5028-reasoning-with-neural-tensor-networks-for-knowledge-base-completion) [reviews](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips26/reviews/504.html)

- <a name="TransE"></a> **(TransE)** Antoine Bordes, Nicolas Usunier, Alberto Garcia-Duran, Jason Weston, Oksana Yakhnenko. "**Translating Embeddings for Modeling Multi-relational Data**". **NIPS 2013**. [paper](http://papers.nips.cc/paper/5071-translating-embeddings-for-modeling-multi-relational-data) [reviews](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips26/reviews/1282.html)

### 2014

- <a name="TransH"></a> **(TransH)** Zhen Wang, Jianwen Zhang, Jianlin Feng, Zheng Chen. "**Knowledge Graph Embedding by Translating on Hyperplanes**". **AAAI 2014**. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI14/paper/view/8531)

- <a name="ER-MLP"></a> **(ER-MLP)** Xin Dong, Evgeniy Gabrilovich, Geremy Heitz, Wilko Horn, Ni Lao, Kevin Murphy, Thomas Strohmann, Shaohua Sun, Wei Zhang. "**Knowledge vault: a web-scale approach to probabilistic knowledge fusion**". **KDD 2014**. [paper](https://dl.acm.org/doi/10.1145/2623330.2623623)

- <a name="pTransE"></a> **(pTransE)** Zhen Wang, Jianwen Zhang, Jianlin Feng, Zheng Chen. "**Knowledge Graph and Text Jointly Embedding**". **EMNLP 2014**. [paper](https://www.aclweb.org/anthology/D14-1167/)

- <a name="CTPs"></a> **(CTPs)** Derry Tanti Wijaya, Ndapandula Nakashole, Tom M. Mitchell. "**CTPs: Contextual Temporal Profiles for Time Scoping Facts using State Change Detection**". **EMNLP 2014**. [paper](https://www.aclweb.org/anthology/D14-1207/)

### 2015

- <a name="DistMult"></a> **(DistMult)** Bishan Yang, Wen-tau Yih, Xiaodong He, Jianfeng Gao, Li Deng. "**Embedding Entities and Relations for Learning and Inference in Knowledge Bases**". **ICLR 2015**. [paper](https://arxiv.org/abs/1412.6575)

- <a name="TransR"></a> **(TransR/CTransR)** Yankai Lin, Zhiyuan Liu, Maosong Sun, Yang Liu, Xuan Zhu. "**Learning Entity and Relation Embeddings for Knowledge Graph Completion**". **AAAI 2015**. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI15/paper/view/9571) [code](https://github.com/thunlp/KB2E)

- <a name="r-TransE"></a> **(r-TransE)** Quan Wang, Bin Wang, Li Guo. "**Knowledge Base Completion Using Embeddings and Rules**". **IJCAI 2015**. [paper](http://ijcai.org/Abstract/15/264)

- <a name="SSE"></a> **(SSE)** Shu Guo, Quan Wang, Bin Wang, Lihong Wang, Li Guo. "**Semantically Smooth Knowledge Graph Embedding**". **ACL 2015**. [paper](https://www.aclweb.org/anthology/P15-1009/)

- <a name="TransD"></a> **(TransD)** Guoliang Ji, Shizhu He, Liheng Xu, Kang Liu, Jun Zhao. "**Knowledge Graph Embedding via Dynamic Mapping Matrix**". **ACL 2015**. [paper](https://www.aclweb.org/anthology/P15-1067/)

- <a name="AMDC"></a> **(AMDC)** Hiroshi Kajino, Akihiro Kishimoto, Adi Botea, Elizabeth M. Daly, Spyros Kotoulas. "**Active Learning for Multi-relational Data Construction**". **WWW 2015**. [paper](https://dl.acm.org/doi/10.1145/2736277.2741103)

- <a name="PTransE"></a> **(PTransE)** Yankai Lin, Zhiyuan Liu, Huanbo Luan, Maosong Sun, Siwei Rao, Song Liu. "**Modeling Relation Paths for Representation Learning of Knowledge Bases**". **EMNLP 2015**. [paper](https://www.aclweb.org/anthology/D15-1082/) [code](https://github.com/thunlp/KB2E)

- <a name="RTransE"></a> **(RTransE)** Alberto Garcia-Duran, Antoine Bordes, Nicolas Usunier. "**Composing Relationships with Translations**". **EMNLP 2015**. [paper](https://www.aclweb.org/anthology/D15-1034/)

- Yuanfei Luo, Quan Wang, Bin Wang, Li Guo. "**Context-Dependent Knowledge Graph Embedding**". **EMNLP 2015**. [paper](https://www.aclweb.org/anthology/D15-1191/)

- <a name="Jointly(desp)"></a> **(Jointly(desp))** Huaping Zhong, Jianwen Zhang, Zhen Wang, Hai Wan, Zheng Chen. "**Aligning Knowledge and Text Embeddings by Entity Descriptions**". **EMNLP 2015**. [paper](https://www.aclweb.org/anthology/D15-1031/)

- <a name="TransE-COMP"></a> **(TransE-COMP)** Kelvin Guu, John Miller, Percy Liang. "**Traversing Knowledge Graphs in Vector Space**". **EMNLP 2015**. [paper](https://www.aclweb.org/anthology/D15-1038/) [code](https://github.com/millerjohnp/traversing_knowledge_graphs)

- Zhuoyu Wei, Jun Zhao, Kang Liu, Zhenyu Qi, Zhengya Sun, Guanhua Tian. "**Large-scale Knowledge Base Completion: Inferring via Grounding Network Sampling over Selected Instances**". **CIKM 2015**. [paper](https://dl.acm.org/citation.cfm?doid=2806416.2806513)

- <a name="KG2E"></a> **(KG2E)** Shizhu He, Kang Liu, Guoliang Ji, Jun Zhao. "**Learning to Represent Knowledge Graphs with Gaussian Embedding**". **CIKM 2015**. [paper](https://dl.acm.org/citation.cfm?doid=2806416.2806502)

### 2016

- <a name="Gaifman"></a> **(Gaifman)** Mathias Niepert. "**Discriminative Gaifman Models**". **NeurIPS 2016**. [paper](http://papers.nips.cc/paper/6098-discriminative-gaifman-models) [reviews](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips29/reviews/1689.html)

- <a name="ComplEx"></a> **(ComplEx)** Théo Trouillon, Johannes Welbl, Sebastian Riedel, Éric Gaussier, Guillaume Bouchard. "**Complex Embeddings for Simple Link Prediction**". **ICML 2016**. [paper](http://proceedings.mlr.press/v48/trouillon16.html)  [code](https://github.com/ttrouill/complex)

- <a name="TransA"></a> **(TransA)** Yantao Jia, Yuanzhuo Wang, Hailun Lin, Xiaolong Jin, Xueqi Cheng. "**Locally Adaptive Translation for Knowledge Graph Embedding**". **AAAI 2016**. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/view/12018)

- <a name="HolE"></a> **(HolE)** Maximilian Nickel, Lorenzo Rosasco, Tomaso Poggio. "**Holographic Embeddings of Knowledge Graphs**". **AAAI 2016**. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/view/12484) [code](https://github.com/mnick/holographic-embeddings)

- <a name="TranSparse"></a> **(TranSparse)** Guoliang Ji, Kang Liu, Shizhu He, Jun Zhao. "**Knowledge Graph Completion with Adaptive Sparse Transfer Matrix**". **AAAI 2016**. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/view/11982)

- <a name="DKRL"></a> **(DKRL)** Ruobing Xie, Zhiyuan Liu, Jia Jia, Huanbo Luan, Maosong Sun. "**Representation Learning of Knowledge Graphs with Entity Descriptions**". **AAAI 2016**. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI16/paper/view/12216) [code](https://github.com/xrb92/DKRL)

- <a name="ManifoldE"></a> **(ManifoldE)** Han Xiao, Minlie Huang, Xiaoyan Zhu. "**From One Point to a Manifold: Knowledge Graph Embedding for Precise Link Prediction**". **IJCAI 2016**. [paper](http://www.ijcai.org/Abstract/16/190) [code](https://github.com/BookmanHan/Embedding)

- <a name="KR-EAR"></a> **(KR-EAR)** Yankai Lin, Zhiyuan Liu, Maosong Sun. "**Knowledge Representation Learning with Entities, Attributes and Relations**". **IJCAI 2016**. [paper](http://www.ijcai.org/Abstract/16/407) [code](https://github.com/thunlp/KR-EAR)

- <a name="TEKE"></a> **(TEKE)** Zhigang Wang, Juanzi Li. "**Text-Enhanced Representation Learning for Knowledge Graph**". **IJCAI 2016**. [paper](http://www.ijcai.org/Abstract/16/187)

- <a name="TKRL"></a> **(TKRL)** Ruobing Xie, Zhiyuan Liu, Maosong Sun. "**Representation Learning of Knowledge Graphs with Hierarchical Types**". **IJCAI 2016**. [paper](http://www.ijcai.org/Abstract/16/421) [code](https://github.com/thunlp/TKRL)

- <a name="ProPPR"></a> **(ProPPR)** William Yang Wang, William W. Cohen. "**Learning First-Order Logic Embeddings via Matrix Factorization**".  **IJCAI 2016**. [paper](http://www.ijcai.org/Abstract/16/304) [code](https://github.com/TeamCohen/ProPPR)

- Teng Long, Ryan Lowe, Jackie Chi Kit Cheung, Doina Precup. "**Leveraging Lexical Resources for Learning Entity Embeddings in Multi-Relational Data**". **ACL 2016**. [paper](https://www.aclweb.org/anthology/P16-2019/)

- <a name="TransG"></a> **(TransG)** Han Xiao, Minlie Huang, Xiaoyan Zhu. "**TransG: A Generative Model for Knowledge Graph Embedding**". **ACL 2016**. [paper](https://www.aclweb.org/anthology/P16-1219/) [code](https://github.com/BookmanHan/Embedding)

- <a name="HiRi"></a> **(HiRi)** Qiao Liu, Liuyi Jiang, Minghao Han, Yao Liu, Zhiguang Qin. "**Hierarchical Random Walk Inference in Knowledge Graphs**". **SIGIR 2016**. [paper](https://dl.acm.org/doi/10.1145/2911451.2911509)

- <a name="KALE"></a> **(KALE)** Shu Guo, Quan Wang, Lihong Wang, Bin Wang, Li Guo."**Jointly Embedding Knowledge Graphs and Logical Rules**". **EMNLP 2016**. [paper](https://www.aclweb.org/anthology/D16-1019/) [code](https://github.com/iieir-km/KALE)

- <a name="t-TransE"></a> **(t-TransE)** Tingsong Jiang, Tianyu Liu, Tao Ge, Lei Sha, Sujian Li, Baobao Chang, Zhifang Sui. "**Encoding Temporal Information for Time-Aware Link Prediction**". **EMNLP 2016**. [paper](https://www.aclweb.org/anthology/D16-1260/)

- <a name="GAKE"></a> **(GAKE)** Jun Feng, Minlie Huang, Yang Yang, Xiaoyan Zhu. "**GAKE: Graph Aware Knowledge Embedding**".  **COLING 2016**. [paper](https://www.aclweb.org/anthology/C16-1062/) [code](https://github.com/JuneFeng/GAKE)

- <a name="TransE-TAE"></a> **(TransE-TAE)** Tingsong Jiang, Tianyu Liu, Tao Ge, Lei Sha, Baobao Chang, Sujian Li, Zhifang Sui. "**Towards Time-Aware Knowledge Graph Completion**". **COLING 2016**. [paper](https://www.aclweb.org/anthology/C16-1161/)

- <a name="FTransE"></a> **(FTransE)** Jun Feng, Minlie Huang, Mingdong Wang, Mantong Zhou, Yu Hao, Xiaoyan Zhu. "**Knowledge Graph Embedding by Flexible Translation**". **KR 2016**. [paper](https://www.aaai.org/ocs/index.php/KR/KR16/paper/view/12887) [code](http://ml.knu.ac.kr/lppKE)

- <a name="lppTransE"></a> **(lppTransE)** Hee-Geun Yoon, Hyun-Je Song, Seong-Bae Park, Se-Young Park. "**A Translation-Based Knowledge Graph Embedding Preserving Logical Property of Relations**". **HLT-NAACL 2016**. [paper](https://www.aclweb.org/anthology/N16-1105)

- <a name="STransE"></a> **(STransE)** Dat Quoc Nguyen, Kairit Sirts, Lizhen Qu, Mark Johnson. "**STransE: A Novel Embedding Model of Entities and Relationships in Knowledge Bases**". **NAACL-HLT 2016**. [paper](https://www.aclweb.org/anthology/N16-1054/) [code](https://github.com/datquocnguyen/STransE)

### 2017

- <a name="Neural-LP"></a> **(Neural-LP)** Fan Yang, Zhilin Yang, William W. Cohen. "**Differentiable Learning of Logical Rules for Knowledge Base Reasoning**". **NIPS 2017**. [paper](http://papers.nips.cc/paper/6826-differentiable-learning-of-logical-rules-for-knowledge-base-reasoning) [reviews](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips30/reviews/1347.html) [code](https://github.com/fanyangxyz/Neural-LP)

- <a name="ANALOGY"></a> **(ANALOGY)** Hanxiao Liu, Yuexin Wu, Yiming Yang. "**Analogical Inference for Multi-relational Embeddings**". **ICML 2017**. [paper](http://proceedings.mlr.press/v70/liu17d.html) [code](https://github.com/quark0/ANALOGY)

- <a name="Know-Evolve"></a> **(Know-Evolve)** Rakshit Trivedi, Hanjun Dai, Yichen Wang, Le Song. "**Know-Evolve: Deep Temporal Reasoning for Dynamic Knowledge Graphs**". **ICML 2017**. [paper](http://proceedings.mlr.press/v70/trivedi17a.html)

- <a name="SSP"></a> **(SSP)** Han Xiao, Minlie Huang, Lian Meng, Xiaoyan Zhu. "**SSP: Semantic Space Projection for Knowledge Graph Embedding with Text Descriptions**". **AAAI 2017**. [paper](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14306) [code](https://github.com/BookmanHan/Embedding)

- <a name="ProjE"></a> **(ProjE)** Baoxu Shi, Tim Weninger. "**ProjE: Embedding Projection for Knowledge Graph Completion**". **AAAI 2017**. [paper](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14279) [code](https://github.com/bxshi/ProjE)

- <a name="puTransE"></a> **(puTransE)** Yi Tay, Luu Anh Tuan, Siu Cheung Hui. "**Non-Parametric Estimation of Multiple Embeddings for Link Prediction on Dynamic Knowledge Graphs**". **AAAI 2017**. [paper](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14524)

- <a name="MLNs"></a> **(MLNs)** Melisachew Wudage Chekol, Giuseppe Pirrò, Joerg Schoenfisch, Heiner Stuckenschmidt. "**Marrying Uncertainty and Time in Knowledge Graphs**". **AAAI 2017**. [paper](https://aaai.org/ocs/index.php/AAAI/AAAI17/paper/view/14730)

-  <a name="Jointly(A-LSTM)"></a> **(Jointly(A-LSTM))** Jiacheng Xu, Xipeng Qiu, Kan Chen, Xuanjing Huang. "**Knowledge Graph Representation with Jointly Structural and Textual Encoding**". **IJCAI 2017**. [paper](https://www.ijcai.org/proceedings/2017/183) [code](https://github.com/jiacheng-xu/Attn-KGE)

- <a name="IKRL"></a> **(IKRL)** Ruobing Xie, Zhiyuan Liu, Huanbo Luan, Maosong Sun. "**Image-embodied Knowledge Representation Learning**". **IJCAI 2017**. [paper](https://www.ijcai.org/proceedings/2017/438) [code](https://github.com/thunlp/IKRL)

- <a name="FRN"></a> **(FRN)** Alexandros Komninos, Suresh Manandhar. "**Feature-Rich Networks for Knowledge Base Completion**". **ACL 2017**. [paper](https://www.aclweb.org/anthology/P17-2051/)

- <a name="ITransf"></a> **(ITransF)** Qizhe Xie, Xuezhe Ma, Zihang Dai, Eduard Hovy. "**An Interpretable Knowledge Transfer Model for Knowledge Base Completion**". **ACL 2017**. [paper](https://www.aclweb.org/anthology/P17-1088/)

- Jay Pujara, Eriq Augustine, Lise Getoor. "**Sparsity and Noise:Where Knowledge Graph Embeddings Fall Short**". **EMNLP 2017**. [paper](https://www.aclweb.org/anthology/D17-1184/) [code](https://github.com/linqs/pujara-emnlp17)

- <a name="DeepPath"></a> **(DeepPath)** Wenhan Xiong, Thien Hoang, William Yang Wang. "**DeepPath: A Reinforcement Learning Method for Knowledge Graph Reasoning**". **EMNLP 2017**. [paper](https://www.aclweb.org/anthology/D17-1060/)

- <a name="ETE"></a> **(ETE)** Changsung Moon, Paul Jones, Nagiza F. Samatova. "**Learning Entity Type Embeddings for Knowledge Graph Completion**". **CIKM 2017**. [paper](https://dl.acm.org/doi/10.1145/3132847.3133095)

- Soumajit Pal, Jacopo Urbani. "**Enhancing Knowledge Graph Completion By Embedding Correlations**". **CIKM 2017**. [paper](https://dl.acm.org/doi/10.1145/3132847.3133143) [code](https://github.com/karmaresearch/statlearning)

- <a name="TCE"></a> **(TCE)** Jun Shi, Huan Gao, Guilin Qi, Zhangquan Zhou. "**Knowledge Graph Embedding with Triple Context**". **CIKM 2017**. [paper](https://dl.acm.org/doi/10.1145/3132847.3133119) [code](https://github.com/juneshi0315/TCE)

- <a name="TransE-RS"></a> **(TransE-RS)** Xiaofei Zhou, Qiannan Zhu, Ping Liu, Li Guo. "**Learning Knowledge Embeddings by Combining Limit-based Scoring Loss**". **CIKM 2017**. [paper](https://dl.acm.org/doi/10.1145/3132847.3132939)

- <a name="CombinE"></a> **(CombinE)** Zhen Tan, Xiang Zhao, Wei Wang. "**Representation Learning of Large-Scale Knowledge Graphs via Entity Feature Combinations**". **CIKM 2017**. [paper](https://dl.acm.org/doi/10.1145/3132847.3132961)

- <a name="RSTE"></a> **(RSTE)** Yi Tay, Anh Tuan Luu, Siu Cheung Hui, Falk Brauer. "**Random Semantic Tensor Ensemble for Scalable Knowledge Graph Link Prediction**". **WSDM 2017**. [paper](https://dl.acm.org/doi/10.1145/3018661.3018695)

### 2018

- <a name="SimplE"></a> **(SimplE)** Seyed Mehran Kazemi, David Poole. "**SimplE Embedding for Link Prediction in Knowledge Graphs**". **NeurIPS 2018**. [paper](http://papers.nips.cc/paper/7682-simple-embedding-for-link-prediction-in-knowledge-graphs) [reviews](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips31/reviews/2093.html) [code](https://github.com/Mehran-k/SimplE)

- <a name="GQE"></a> **(GQE)** William L. Hamilton, Payal Bajaj, Marinka Zitnik, Dan Jurafsky, Jure Leskovec. "**Embedding Logical Queries on Knowledge Graphs**". **NeurIPS 2018**. [paper](http://papers.nips.cc/paper/7473-embedding-logical-queries-on-knowledge-graphs) [reviews](http://media.nips.cc/nipsbooks/nipspapers/paper_files/nips31/reviews/1018.html) [code](https://github.com/williamleif/graphqembed)

- <a name="ComplEx-N3"></a> **(ComplEx-N3)** Timothée Lacroix, Nicolas Usunier, Guillaume Obozinski. "**Canonical Tensor Decomposition for Knowledge Base Completion**". **ICML 2018**. [paper](http://proceedings.mlr.press/v80/lacroix18a.html) [code](https://github.com/facebookresearch/kbc)

- <a name="MINERVA"></a> **(MINERVA)** Rajarshi Das, Shehzaad Dhuliawala, Manzil Zaheer, Luke Vilnis, Ishan Durugkar, Akshay Krishnamurthy, Alex Smola, Andrew McCallum. "**Go for a Walk and Arrive at the Answer: Reasoning Over Paths in Knowledge Bases using Reinforcement Learning**". **ICLR 2018** [paper](https://openreview.net/forum?id=Syg-YfWCW) [code](https://github.com/shehzaadzd/MINERVA)

- Yanjie Wang, Rainer Gemulla, Hui Li. "**On Multi-Relational Link Prediction with Bilinear Models**". **AAAI 2018**. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16900) [code](https://github.com/y-j-wang/b4l)

- <a name="ComplEx-L1"></a> **(ComplEx-L1)** Hitoshi Manabe, Katsuhiko Hayashi, Masashi Shimbo. "**Data-Dependent Learning of Symmetric/Antisymmetric Relations for Knowledge Base Completion**". **AAAI 2018**. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16211) [code](https://github.com/mana-ysh/symmetry-learning-kgc)

- <a name="ConvE"></a> **(ConvE)** Tim Dettmers, Pasquale Minervini, Pontus Stenetorp, Sebastian Riedel. "**Convolutional 2D Knowledge Graph Embeddings**". **AAAI 2018**. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/17366) [code](https://github.com/TimDettmers/ConvE)

- <a name="TorusE"></a> **(TorusE)** Takuma Ebisu, Ryutaro Ichise. "**TorusE: Knowledge Graph Embedding on a Lie Group**". **AAAI 2018**. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16227) [code](https://github.com/TakumaE/TorusE)

- <a name="RUGE"></a> **(RUGE)** Shu Guo, Quan Wang, Lihong Wang, Bin Wang, Li Guo. "**Knowledge Graph Embedding With Iterative Guidance From Soft Rules**". **AAAI 2018**. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16369) [code](https://github.com/iieir-km/RUGE)

- <a name="ConMask"></a> **(ConMask)** Baoxu Shi, Tim Weninger. "**Open-World Knowledge Graph Completion**". **AAAI 2018**. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16055) [code](https://github.com/bxshi/ConMask)

- <a name="IGAN"></a> **(IGAN)** Peifeng Wang, Shuangyin Li, Rong Pan. "**Incorporating GAN for Negative Sampling in Knowledge Representation Learning**". **AAAI 2018**. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16094)

- <a name="CKRL"></a> **(CKRL)** Ruobing Xie, Zhiyuan Liu, Fen Lin, Leyu Lin. "**Does William Shakespeare REALLY Write Hamlet? Knowledge Representation Learning With Confidence**". **AAAI 2018**. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16577) [code](https://github.com/thunlp/CKRL)

- <a name="TransE-T"></a> **(TransE-T)** Richong Zhang, Fanshuang Kong, Chenyue Wang, Yongyi Mao. "**Embedding of Hierarchically Typed Knowledge Bases**". **AAAI 2018**. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16539) [code](https://github.com/fskong/Embedding_of_Hierarchically_Typed_KB)

- <a name="JointNRE"></a> **(JointNRE)** Xu Han, Zhiyuan Liu, Maosong Sun. "**Neural Knowledge Acquisition via Mutual Attention Between Knowledge Graph and Text**". **AAAI 2018**. [paper](https://www.aaai.org/ocs/index.php/AAAI/AAAI18/paper/view/16691) [code](https://github.com/thunlp/JointNRE)

- <a name="TransAt"></a> **(TransAt)** Wei Qian, Cong Fu, Yu Zhu, Deng Cai, Xiaofei He. "**Translating Embeddings for Knowledge Graph Completion with Relation Attention Mechanism**". **IJCAI 2018**. [paper](https://www.ijcai.org/proceedings/2018/596) [code](https://github.com/ZJULearning/TransAt)

- Ryo Takahashi, Ran Tian, Kentaro Inui. "**Interpretable and Compositional Relation Learning by Joint Training with an Autoencoder**". **ACL 2018**. [paper](https://www.aclweb.org/anthology/P18-1200/) [code](https://github.com/tianran/glimvec)

- **(KG-Geometry)** Chandrahas, Aditya Sharma, Partha Talukdar. "**Towards Understanding the Geometry of Knowledge Graph Embeddings**". **ACL 2018**. [paper](https://www.aclweb.org/anthology/P18-1012/) [code](https://github.com/malllabiisc/kg-geometry)

- <a name="ComplEx-NNE"></a> **(ComplEx-NNE)** Boyang Ding, Quan Wang, Bin Wang, Li Guo. "**Improving Knowledge Graph Embedding Using Simple Constraints**". **ACL 2018**. [paper](https://www.aclweb.org/anthology/P18-1011/) [code](https://github.com/iieir-km/ComplEx-NNE_AER)

- <a name="TransN"></a> **(TransN)** Chun-Chih Wang, Pu-Jen Cheng. "**Translating Representations of Knowledge Graphs with Neighbors**". **SIGIR 2018**. [paper](https://dl.acm.org/doi/10.1145/3209978.3210085)

- **(Max-K Criterion)** Jiajie Mei, Richong Zhang, Yongyi Mao, Ting Deng. "**On Link Prediction in Knowledge Bases: Max-K Criterion and Prediction Protocols**". **SIGIR 2018**. [paper](https://dl.acm.org/doi/10.1145/3209978.3210029)

- <a name="TTransE"></a> **(TTransE)** Julien Leblay, Melisachew Wudage Chekol. "**Deriving Validity Time in Knowledge Graph**". **WWW 2018**. [paper](https://dl.acm.org/doi/10.1145/3184558.3191639)

- <a name="TransE-HRS"></a> **(TransE-HRS)** Zhao Zhang, Fuzhen Zhuang, Meng Qu, Fen Lin, Qing He. "**Knowledge Graph Embedding with Hierarchical Relation Structure**". **EMNLP 2018**. [paper](https://www.aclweb.org/anthology/D18-1358/)

- <a name="MultiHopKG"></a> **(MultiHopKG)** Xi Victoria Lin, Richard Socher, Caiming Xiong. "**Multi-Hop Knowledge Graph Reasoning with Reward Shaping**". **EMNLP 2018**. [paper](https://www.aclweb.org/anthology/D18-1362/) [code](https://github.com/salesforce/MultiHopKG)

- <a name="TA-DistMult"></a> **(TA-DistMult)** Alberto Garcia-Duran, Sebastijan Dumančić, Mathias Niepert. "**Learning Sequence Encoders for Temporal Knowledge Graph Completion**". **EMNLP 2018**. [paper](https://www.aclweb.org/anthology/D18-1516/) [dataset](https://github.com/nle-ml/mmkb)

- <a name="HyTE"></a> **(HyTE)** Shib Sankar Dasgupta, Swayambhu Nath Ray, Partha Talukdar. "**HyTE: Hyperplane-based Temporally aware Knowledge Graph Embedding**". **EMNLP 2018**. [paper](https://www.aclweb.org/anthology/D18-1225/) [code](https://github.com/malllabiisc/HyTE)

- <a name="TransC"></a> **(TransC)** Xin Lv, Lei Hou, Juanzi Li, Zhiyuan Liu. "**Differentiating Concepts and Instances for Knowledge Graph Embedding**". **EMNLP 2018**. [paper](https://www.aclweb.org/anthology/D18-1222/) [code](https://github.com/davidlvxin/TransC)

- <a name="MKBE"></a> **(MKBE)** Pouya Pezeshkpour, Liyan Chen, Sameer Singh. "**Embedding Multimodal Relational Data for Knowledge Base Completion**". **EMNLP 2018**. [paper](https://www.aclweb.org/anthology/D18-1359/) [code](https://github.com/pouyapez/mkbe)

- <a name="GMatching"></a> **(GMatching)** Wenhan Xiong, Mo Yu, Shiyu Chang, Xiaoxiao Guo, William Yang Wang. "**One-Shot Relational Learning for Knowledge Graphs**". **EMNLP 2018**. [paper](https://www.aclweb.org/anthology/D18-1223/) [code](https://github.com/xwhan/One-shot-Relational-Learning)

- Víctor Gutiérrez-Basulto, Steven Schockaert. "**From Knowledge Graph Embedding to Ontology Embedding? An Analysis of the Compatibility between Vector Space Representations and Rules**". **KR 2018**. [paper](https://aaai.org/ocs/index.php/KR/KR18/paper/view/18013)

- <a name="KBLRN"></a> **(KBLRN)** Alberto García-Durán, Mathias Niepert. "**KBlrn: End-to-End Learning of Knowledge Base Representations with Latent, Relational, and Numerical Features**". **UAI 2018**. [paper](http://auai.org/uai2018/proceedings/papers/149.pdf)

- Farahnaz Akrami, Lingbing Guo, Wei Hu, Chengkai Li. "**Re-evaluating Embedding-Based Knowledge Graph Completion Methods**". **CIKM 2018**. [paper](https://dl.acm.org/doi/10.1145/3269206.3269266)

- <a name="SENN"></a> **(SENN)** Saiping Guan, Xiaolong Jin, Yuanzhuo Wang, Xueqi Cheng. "**Shared Embedding Based Neural Networks for Knowledge Graph Completion**". **CIKM 2018**. [paper](https://dl.acm.org/doi/10.1145/3269206.3271704)

- <a name="MultiE"></a> **(MultiE)** Zhao Zhang, Fuzhen Zhuang, Zheng-Yu Niu, Deqing Wang, Qing He. "**MultiE: Multi-Task Embedding for Knowledge Base Completion**". **CIKM 2018**. [paper](https://dl.acm.org/doi/10.1145/3269206.3269295)

- <a name="CACL"></a> **(CACL)** Byungkook Oh, Seungmin Seo, Kyong-Ho. "**Knowledge Graph Completion by Context-Aware Convolutional Learning with Multi-Hop Neighborhoods**". **CIKM 2018**. [paper](https://dl.acm.org/doi/10.1145/3269206.3271769)

- <a name="R-GCN"></a> **(R-GCN)** Michael Schlichtkrull, Thomas N. Kipf, Peter Bloem, Rianne van den Berg, Ivan Titov, Max Welling. "**Modeling Relational Data with Graph Convolutional Networks**". **ESWC 2018**. [paper](https://link.springer.com/chapter/10.1007%2F978-3-319-93417-4_38) [code](https://github.com/tkipf/relational-gcn)

- <a name="ConvKB"></a> **(ConvKB)** Dai Quoc Nguyen, Tu Dinh Nguyen, Dat Quoc Nguyen, Dinh Phung. "**A Novel Embedding Model for Knowledge Base Completion Based on Convolutional Neural Network**". **NAACL-HLT 2018**. [paper](https://www.aclweb.org/anthology/N18-2053/) [code](https://github.com/daiquocnguyen/ConvKB)

- <a name="KBGAN"></a> **(KBGAN)** Liwei Cai, William Yang Wang. "**KBGAN: Adversarial Learning for Knowledge Graph Embeddings**". **NAACL-HLT 2018**. [paper](https://www.aclweb.org/anthology/N18-1133/) [code](https://github.com/cai-lw/KBGAN)

- <a name="ATE"></a> **(ATE)** Bo An, Bo Chen, Xianpei Han, Le Sun. "**Accurate Text-Enhanced Knowledge Graph Representation Learning**". **NAACL-HLT 2018**. [paper](https://www.aclweb.org/anthology/N18-1068/)

### 2019

- <a name="QuatE"></a> **(QuatE)** Shuai Zhangy, Yi Tay, Lina Yao, Qi Liu. "**Quaternion Knowledge Graph Embeddings**". **NeurIPS 2019**. [paper](http://papers.nips.cc/paper/8541-quaternion-knowledge-graph-embeddings) [code](https://github.com/cheungdaven/QuatE) 

- <a name="DRUM"></a> **(DRUM)** 	Ali Sadeghian, Mohammadreza Armandpour, Patrick Ding, Daisy Zhe Wang. "**DRUM: End-To-End Differentiable Rule Mining On Knowledge Graphs**". **NeurIPS 2019**. [paper](http://papers.nips.cc/paper/9669-drum-end-to-end-differentiable-rule-mining-on-knowledge-graphs) [code](https://github.com/alisadeghian/DRUM)

- <a name="MuRP"></a> **(MuRP)** Ivana Balaževic, Carl Allen, Timothy Hospedales. "**Multi-relational Poincaré Graph Embeddings**". **NeurIPS 2019**. [paper](http://papers.nips.cc/paper/8696-multi-relational-poincare-graph-embeddings) [code](https://github.com/ibalazevic/multirelational-poincare)

- <a name="RSN"></a> **(RSN)** Lingbing Guo, Zequn Sun, Wei Hu. "**Learning to Exploit Long-term Relational Dependencies in Knowledge Graphs**". **ICML 2019**. [paper](http://proceedings.mlr.press/v97/guo19c.html) [code](https://github.com/nju-websoft/RSN)

- <a name="RotatE"></a> **(RotatE)** Zhiqing Sun, Zhi-Hong Deng, Jian-Yun Nie, Jian Tang. "**RotatE: Knowledge Graph Embedding by Relational Rotation in Complex Space**". **ICLR 2019**. [paper](https://openreview.net/forum?id=HkgEQnRqYQ) [code](https://github.com/DeepGraphLearning/KnowledgeGraphEmbedding)

- <a name="DyRep"></a> **(DyRep)** Rakshit Trivedi, Mehrdad Farajtabar, Prasenjeet Biswal, Hongyuan Zha. "**DyRep: Learning Representations over Dynamic Graphs**". **ICLR 2019**. [paper](https://openreview.net/forum?id=HyePrhR5KX)

- <a name="TransGate"></a> **(TransGate)** Jun Yuan, Neng Gao, Ji Xiang. "**TransGate: Knowledge Graph Embedding with Shared Gate Structure**". **AAAI 2019**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4169)

- <a name="UKGE"></a> **(UKGE)** Xuelu Chen, Muhao Chen, Weijia Shi, Yizhou Sun, Carlo Zaniolo. "**Embedding Uncertain Knowledge Graphs**". **AAAI 2019**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4210) [code](https://github.com/stasl0217/UKGE)

- <a name="SimplE+"></a> **(SimplE+)** Bahare Fatemi, Siamak Ravanbakhsh, David Poole. "**Improved Knowledge Graph Embedding Using Background Taxonomic Information**". **AAAI 2019**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4231)

- <a name="LENA"></a> **(LENA)** Fanshuang Kong, Richong Zhang, Yongyi Mao, Ting Deng. "**LENA: Locality-Expanded Neural Embedding for Knowledge Base Completion**". **AAAI 2019**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4144) [code](https://github.com/fskong/LENA)

- <a name="LAN"></a> **(LAN)** PeiFeng Wang, Jialong Han, Chenliang Li, Rong Pan. "**Logic Attention Based Neighborhood Aggregation for Inductive Knowledge Graph Embedding**". **AAAI 2019**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4698) [code](https://github.com/wangpf3/LAN)

- <a name="SACN"></a> **(SACN)** Chao Shang, Yun Tang, Jing Huang, Jinbo Bi, Xiaodong He, Bowen Zhou. "**End-to-End Structure-Aware Convolutional Networks for Knowledge Base Completion**". **AAAI 2019**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4164) [code](https://github.com/JD-AI-Research-Silicon-Valley/SACN)

- <a name="OWE"></a> **(OWE)** Haseeb Shah, Johannes Villmow, Adrian Ulges, Ulrich Schwanecke, Faisal Shafait. "**An Open-World Extension to Knowledge Graph Completion Models**". **AAAI 2019**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4162) [code](https://github.com/haseebs/OWE)

- <a name="AnyBURL"></a> **(AnyBURL)** Christian Meilicke, Melisachew Wudage Chekol, Daniel Ruffinelli, Heiner Stuckenschmidt. "**Anytime Bottom-Up Rule Learning for Knowledge Graph Completion**". **IJCAI 2019**. [paper](https://www.ijcai.org/proceedings/2019/435) [code](http://web.informatik.uni-mannheim.de/AnyBURL/)

- Hengtong Zhang, Tianhang Zheng, Jing Gao, Chenglin Miao, Lu Su, Yaliang Li, Kui Ren. "**Data Poisoning Attack against Knowledge Graph Embedding**". **IJCAI 2019**. [paper](https://www.ijcai.org/proceedings/2019/674)

-  <a name="TransMS"></a> **(TransMS)** Shihui Yang, Jidong Tian, Honglun Zhang, Junchi Yan, Hao He, Yaohui Jin. "**TransMS: Knowledge Graph Embedding for Complex Relations by Multidirectional Semantics**". **IJCAI 2019**. [paper](https://www.ijcai.org/proceedings/2019/268)

-  <a name="WWV"></a> **(WWV)** Neil Veira, Brian Keng, Kanchana Padmanabhan, Andreas G. Veneris. "**Unsupervised Embedding Enhancements of Knowledge Graphs using Textual Associations**". **IJCAI 2019**. [paper](https://www.ijcai.org/proceedings/2019/725) [code](https://github.com/rubikloud/kg-text-embeddings)

- <a name="M-GNN"></a> **(M-GNN)** Zihan Wang, Zhaochun Ren, Chunyu He, Peng Zhang, Yue Hu. "**Robust Embedding with Multi-Level Structures for Link Prediction**". **IJCAI 2019**. [paper](https://www.ijcai.org/proceedings/2019/728)

- <a name="VR-GCN"></a> **(VR-GCN)** Rui Ye, Xin Li, Yujie Fang, Hongyu Zang, Mingzhong Wang. "**A Vectorized Relational Graph Convolutional Network for Multi-Relational Network Alignment**". **IJCAI 2019**. [paper](https://www.ijcai.org/Proceedings/2019/574)

- <a name="KBGAT"></a> **(KBGAT)** Deepak Nathani, Jatin Chauhan, Charu Sharma, Manohar Kaul. "**Learning Attention-based Embeddings for Relation Prediction in Knowledge Graphs**". **ACL 2019**. [paper](https://www.aclweb.org/anthology/P19-1466/) [code](https://github.com/deepakn97/relationPrediction)

- <a name="DihEdral"></a> **(DihEdral)** Canran Xu, Ruijiang Li. "**Relation Embedding with Dihedral Group in Knowledge Graph**". **ACL 2019**. [paper](https://www.aclweb.org/anthology/P19-1026/)

- **(JOIE)** Junheng Hao, Muhao Chen, Wenchao Yu, Yizhou Sun, Wei Wang. "**Universal Representation Learning of Knowledge Bases by Jointly Embedding Instances and Ontological Concepts**". **KDD 2019**. [paper](https://dl.acm.org/doi/10.1145/3292500.3330838) [code](https://github.com/JunhengH/joie-kdd19)

- <a name="NSCaching"></a> **(NSCaching)** Yongqi Zhang, Quanming Yao, Yingxia Shao, Lei Chen. "**NSCaching: Simple and Efficient Negative Sampling for Knowledge Graph Embedding**". **ICDE 2019**. [paper](https://ieeexplore.ieee.org/document/8731371) [code](https://github.com/yzhangee/NSCaching)

- <a name="MARINE"></a> **(MARINE)** Ming-Han Feng, Chin-Chi Hsu, Cheng-Te Li, Mi-Yen Yeh, Shou-De Lin. "**MARINE: Multi-relational Network Embeddings with Relational Proximity and Node Attributes**". **WWW 2019**. [paper](https://dl.acm.org/doi/10.1145/3308558.3313715)

- **(NaLP)** Saiping Guan, Xiaolong Jin, Yuanzhuo Wang, Xueqi Cheng. "**Link Prediction on N-ary Relational Data**". **WWW 2019**. [paper](https://dl.acm.org/doi/10.1145/3308558.3313414) [code](https://github.com/gsp2014/NaLP)

- <a name="ActiveLink"></a> **(ActiveLink)** Natalia Ostapuk, Jie Yang, Philippe Cudré-Mauroux. "**ActiveLink: Deep Active Learning for Link Prediction in Knowledge Graphs**". **WWW 2019**. [paper](https://dl.acm.org/doi/10.1145/3308558.3313620) [code](https://github.com/eXascaleInfolab/ActiveLink)

- <a name="IterE"></a> **(IterE)** Wen Zhang, Bibek Paudel, Liang Wang, Jiaoyan Chen, Hai Zhu, Wei Zhang, Abraham Bernstein, Huajun Chen. "**Iteratively Learning Embeddings and Rules for Knowledge Graph Reasoning**". **WWW 2019**. [paper](https://dl.acm.org/doi/10.1145/3308558.3313612) [code](https://github.com/wencolani/IterE)

- <a name="CaRe"></a> **(CaRe)** Swapnil Gupta, Sreyash Kenkre, Partha Talukdar. "**CaRe: Open Knowledge Graph Embeddings**". **EMNLP 2019**. [paper](https://www.aclweb.org/anthology/D19-1036/) [code](https://github.com/malllabiisc/CaRE)

- <a name="MetaR"></a> **(MetaR)** Mingyang Chen, Wen Zhang, Wei Zhang, Qiang Chen and Huajun Chen. "**Meta Relational Learning for Few-Shot Link Prediction in Knowledge Graphs**". **EMNLP 2019**. [paper](https://www.aclweb.org/anthology/D19-1431/) [code](https://github.com/AnselCmy/MetaR)

- <a name="OPTransE"></a> **(OPTransE)** Yao Zhu, Hongzhi Liu, Zhonghai Wu, Yang Song and Tao Zhang. "**Representation Learning with Ordered Relation Paths for Knowledge Graph Completion**". **EMNLP 2019**. [paper](https://www.aclweb.org/anthology/D19-1268/)

- <a name="TCVAE"></a> **(TCVAE)** Zihao Wang, Kwunping Lai, Piji Li, Lidong Bing and Wai Lam. "**Tackling Long-Tailed Relations and Uncommon Entities in Knowledge Graph Completion**". **EMNLP 2019**. [paper](https://www.aclweb.org/anthology/D19-1024/)

- <a name="TuckER"></a> **(TuckER)** Ivana Balazevic, Carl Allen, Timothy M. Hospedales. "**TuckER: Tensor Factorization for Knowledge Graph Completion**". **EMNLP 2019**. [paper](https://www.aclweb.org/anthology/D19-1522/) [code](https://github.com/ibalazevic/TuckER)

- <a name="JoBi ComplEx"></a> **(JoBi ComplEx)** Esma Balkir, Masha Naslidnyk, Dave Palfrey and Arpit Mittal. "**Using Pairwise Occurrence Information to Improve Knowledge Graph Completion on Large-Scale Datasets**". **EMNLP 2019**. [paper](https://www.aclweb.org/anthology/D19-1368/)

- <a name="Meta-KGR"></a> **(Meta-KGR)** Xin Lv, Yuxian Gu, Xu Han, Lei Hou, Juanzi Li, Zhiyuan Liu. "**Adapting Meta Knowledge Graph Information for Multi-Hop Reasoning over Few-Shot Relations**". **EMNLP 2019**. [paper](https://doi.org/10.18653/v1/D19-1334)

- <a name="CPL"></a> **(CPL)** Cong Fu, Tong Chen, Meng Qu, Woojeong Jin, Xiang Ren. "**Collaborative Policy Learning for Open Knowledge Graph Reasoning**". **EMNLP 2019**. [paper](https://doi.org/10.18653/v1/D19-1269)

- <a name="EM"></a> **(EM)** Robert Bamler, Farnood Salehi, Stephan Mandt. "**Augmenting and Tuning Knowledge Graph Embeddings**". **UAI 2019**. [paper](http://auai.org/uai2019/proceedings/papers/172.pdf) [code](https://github.com/mandt-lab/knowledge-graph-tuning)

- <a name="CrossE"></a> **(CrossE)** Wen Zhang, Bibek Paudel, Wei Zhang, Abraham Bernstein, Huajun Chen. "**Interaction Embeddings for Prediction and Explanation in Knowledge Graphs**". **WSDM 2019**. [paper](https://dl.acm.org/doi/10.1145/3289600.3291014) [code](https://github.com/wencolani/CrossE)

- Erik B. Myklebust, Ernesto Jiménez-Ruiz, Jiaoyan Chen, Raoul Wolf, Knut Erik Tollefsen. "**Knowledge Graph Embedding for Ecotoxicological Effect Prediction**". **ISWC 2019**. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-30796-7_30)

- Simon Gottschalk, Elena Demidova. "**HapPenIng: Happen, Predict, Infer - Event Series Completion in a Knowledge Graph**". **ISWC 2019**. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-30793-6_12)

- Ye Liu, Hui Li, Alberto García-Durán, Mathias Niepert, Daniel O?oro-Rubio, David S. Rosenblum. "**MMKG: Multi-modal Knowledge Graphs**". **ESWC 2019**. [paper](https://link.springer.com/chapter/10.1007%2F978-3-030-21348-0_30)

- <a name="CRIAGE"></a> **(CRIAGE)** Pouya Pezeshkpour, Yifan Tian, Sameer Singh. “**Investigating Robustness and Interpretability of Link Prediction via Adversarial Modifications**”. **NAACL-HLT 2019**. [paper](https://www.aclweb.org/anthology/N19-1337/) [code](https://github.com/pouyapez/criage)

- <a name="CapsE"></a> **(CapsE)** Dai Quoc Nguyen, Thanh Vu, Tu Dinh Nguyen, Dat Quoc Nguyen, Dinh Q. Phung. "**A Capsule Network-based Embedding Model for Knowledge Graph Completion and Search Personalization**". **NAACL-HLT 2019**. [paper](https://www.aclweb.org/anthology/N19-1226/) [code](https://github.com/daiquocnguyen/CapsE)

- <a name="ConvR"></a> **(ConvR)** Xiaotian Jiang, Quan Wang, Bin Wang. "**Adaptive Convolution for Multi-Relational Learning**". **NAACL-HLT 2019**. [paper](https://www.aclweb.org/anthology/N19-1103/)

- <a name="GRank"></a> **(GRank)** Takuma Ebisu, Ryutaro Ichise. "**Graph Pattern Entity Ranking Model for Knowledge Graph Completion**". **NAACL-HLT 2019**. [paper](https://www.aclweb.org/anthology/N19-1104/)

- **(FFD)** Zihao Fu, Yankai Lin, Zhiyuan Liu, Wai Lam. "**Fact Discovery from Knowledge Base via Facet Decomposition**". 
**NAACL-HLT 2019**. [paper](https://www.aclweb.org/anthology/N19-1297/)

- <a name="TransGCN"></a> **(TransGCN)** Ling Cai, Bo Yan, Gengchen Mai, Krzysztof Janowicz, Rui Zhu. "**TransGCN: Coupling Transformation Assumptions with Graph Convolutional Networks for Link Prediction**". **K-CAP 2019**. [paper](https://dl.acm.org/doi/10.1145/3360901.3364441)

- <a name="ATiSE"></a> **(ATiSE)** Chengjin Xu, Mojtaba Nayyeri, Fouad Alkhoury, Jens Lehmann, Hamed Shariat Yazdi. "**Temporal Knowledge Graph Embedding Model based on Additive Time Series Decomposition**". **arxiv 2019-11**. [paper](https://arxiv.org/abs/1911.07893)

- Ningyu Zhang, Shumin Deng, Zhanlin Sun, Jiaoyan Chen, Wei Zhang, Huajun Chen. "**Relation Adversarial Network for Low Resource Knowledge Graph Completion**". **arxiv 2019-11**. [paper](https://arxiv.org/abs/1911.03091)

- Komal K. Teru, Etienne Denis, William L. Hamilton. "**Inductive Relation Prediction by Subgraph Reasoning**". **arxiv 2019-11**. [paper](https://arxiv.org/abs/1911.06962)

- **(S2E)** Yongqi Zhang, Quanming Yao, Lei Chen. "**Neural Recurrent Structure Search for Knowledge Graph Embedding**". **arxiv 2019-11**. [paper](https://arxiv.org/abs/1911.07132)

- **(CDC)** Bo Peng, Renqiang Min, Xia Ning. "**CNN-based Dual-Chain Models for Knowledge Graph Learning**". **arxiv 2019-11**. [paper](https://arxiv.org/abs/1911.06910)

- **(GC-OTE)** Yun Tang, Jing Huang, Guangtao Wang, Xiaodong He, Bowen Zhou. "**Orthogonal Relation Transforms with Graph Context Modeling for Knowledge Graph Embedding**". **arxiv 2019-11**. [paper](https://arxiv.org/abs/1911.04910)

- **(DeCom)** Xiang Kong, Xianyang Chen, Eduard H. Hovy. "**Decompressing Knowledge Graph Representations for Link Prediction**". **arxiv 2019-11**. [paper](https://arxiv.org/abs/1911.04053) [code](https://github.com/shawnkx/Decom)

- Zhiqing Sun, Shikhar Vashishth, Soumya Sanyal, Partha P. Talukdar, Yiming Yang. "**A Re-evaluation of Knowledge Graph Completion Methods**". **arxiv 2019-11**. [paper](https://arxiv.org/abs/1911.03903) [code](https://github.com/svjan5/kgc-reevaluation)

- **(CoKE)** Quan Wang, Pingping Huang, Haifeng Wang, Songtai Dai, Wenbin Jiang, Jing Liu, Yajuan Lyu, Yong Zhu, Hua Wu. "**CoKE: Contextualized Knowledge Graph Embedding**". **arxiv 2019-11**. [paper](https://arxiv.org/abs/1911.02168) [code](https://github.com/paddlepaddle/models/tree/develop/PaddleKG/CoKE)

- **(KANE)** Wenqiang Liu, Hongyun Cai, Xu Cheng, Sifa Xie, Yipeng Yu, Hanyu Zhang. "**Learning High-order Structural and Attribute information by Knowledge Graph Attention Networks for Enhancing Knowledge Graph Embedding**". **arxiv 2019-10**. [paper](https://arxiv.org/abs/1910.03891)

- Tianxing Wu, Arijit Khan, Huan Gao, Cheng Li. "**Efficiently Embedding Dynamic Knowledge Graphs**". **arxiv 2019-10**. [paper](https://arxiv.org/abs/1910.06708)

- Chaitanya Malaviya, Chandra Bhagavatula, Antoine Bosselut, Yejin Choi. "**Commonsense Knowledge Base Completion with Structural and Semantic Context**". **arxiv 2019-10**. [paper](https://arxiv.org/abs/1910.02915)

- Gengchen Mai, Krzysztof Janowicz, Bo Yan, Rui Zhu, Ling Cai, Ni Lao. "**Contextual Graph Attention for Answering Logical Queries over Incomplete Knowledge Graphs**". **arxiv 2019-10**. [paper](https://arxiv.org/abs/1910.00084)

- Takuma Ebisu, Ryutaro Ichise. "**Combination of Unified Embedding Model and Observed Features for Knowledge Graph Completion**". **arxiv 2019-09**. [paper](https://arxiv.org/abs/1909.03821)

- Mojtaba Nayyeri, Chengjin Xu, Yadollah Yaghoobzadeh, Hamed Shariat Yazdi, Jens Lehmann. "**Toward Understanding The Effect Of Loss function On Then Performance Of Knowledge Graph Embedding**". **arxiv 2019-09**. [paper](https://arxiv.org/abs/1909.00519)

- **(TransW)** Lianbo Ma,Peng Sun, Zhiwei Lin, Hui Wang. ""**Composing Knowledge Graph Embeddings via Word Embeddings**". **aexiv 2019-09**. [paper](https://arxiv.org/abs/1909.03794)

- **(KG-BERT)** Liang Yao, Chengsheng Mao, Yuan Luo. "**KG-BERT: BERT for Knowledge Graph Completion**". **arxiv 2019-09**. [paper](https://arxiv.org/abs/1909.03193) [code](https://github.com/yao8839836/kg-bert)

- Carl Allen, Ivana Balazevic, Timothy M. Hospedales. "**On Understanding Knowledge Graph Representation**". **arxiv 2019-09**. [paper](https://arxiv.org/abs/1909.11611)

- **(LogicENN)** Mojtaba Nayyeri, Chengjin Xu, Jens Lehmann, Hamed Shariat Yazdi. "**LogicENN: A Neural Based Knowledge Graphs Embedding Model with Logical Rules**". **arxiv 2019-08**. [paper](https://arxiv.org/abs/1908.07141)

- **(HyperKG)** Prodromos Kolyvakis, Alexandros Kalousis, Dimitris Kiritsis. "**HyperKG: Hyperbolic Knowledge Graph Embeddings for Knowledge Base Completion**". **arxiv 2019-08**. [paper](https://arxiv.org/abs/1908.04895) [code](https://github.com/prokolyvakis/hyperkg)

- Hong Wang, Wenhan Xiong, Mo Yu, Xiaoxiao Guo, Shiyu Chang, William Yang Wang. "**Meta Reasoning over Knowledge Graphs**". **arxiv 2019-08**. [paper](https://arxiv.org/abs/1908.04877)

- **(R-MeN)** Dai Quoc Nguyen, Tu Dinh Nguyen, Dinh Phung. "**Relational Memory-based Knowledge Graph Embedding**". **arxiv 2019-07**. [paper](https://arxiv.org/abs/1907.06080)

-	**(TransEAML)** Mojtaba Nayyeri, Xiaotian Zhou, Sahar Vahdati, Hamed Shariat Yazdi, Jens Lehmann. "**Adaptive Margin Ranking Loss for Knowledge Graph Embeddings via a Correntropy Objective Function**". **arxiv 2019-07**. [paper](https://arxiv.org/abs/1907.05336)

- Alexander Imani Cowen-Rivers, Pasquale Minervini, Tim Rockt?schel, Matko Bosnjak, Sebastian Riedel, Jun Wang. "**Neural Variational Inference For Estimating Uncertainty in Knowledge Graph Embeddings**". **arxiv 2019-06**. 
[paper](https://arxiv.org/abs/1906.04985)

- Zhengxiao Du, Chang Zhou, Ming Ding, Hongxia Yang, Jie Tang. "**Cognitive Knowledge Graph Reasoning for One-shot Relational Learning**". **arxiv 2019-06**. [paper](https://arxiv.org/abs/1906.05489)

- **(MDE)** Afshin Sadeghi, Damien Graux, Jens Lehmann. "**MDE: Multi Distance Embeddings for Link Prediction in Knowledge Graphs**"". **arxiv 2019-05**. [paper](https://arxiv.org/abs/1905.10702)

- Jinkui Yao, Lianghua Xu. "**Knowledge Graph Embedding Bi-Vector Models for Symmetric Relation**". **arxiv 2019-05**. [paper](https://arxiv.org/abs/1905.09557)

- **(TransESM)** Mojtaba Nayyeri, Sahar Vahdati, Jens Lehmann, Hamed Shariat Yazdi. "**Soft Marginal TransE for Scholarly Knowledge Graph Completion**". **arxiv 2019-04**. [paper](https://arxiv.org/abs/1904.12211)

- **(AutoKGE)** Yongqi Zhang, Quanming Yao, Wenyuan Dai, Lei Chen. "**AutoKGE: Searching Scoring Functions for Knowledge Graph Embedding**". **arxiv 2019-04**. [paper](https://arxiv.org/abs/1904.11682) [code](https://github.com/yzhangee/AutoSF)

- <a name="RE-Net"></a> **(RE-Net)** Woojeong Jin, Changlin Zhang, Pedro A. Szekely, Xiang Ren. "**Recurrent Event Network for Reasoning over Temporal Knowledge Graphs**". **arxiv 2019-04**. [paper](https://arxiv.org/abs/1904.05530)

- Sara Morsy, George Karypis. "**Sparse Neural Attentive Knowledge-based Models for Grade Prediction**". **arxiv 2019-04**. [paper](https://arxiv.org/abs/1904.11858)

- **(QCE)** Yunpu Ma, Volker Tresp, Liming Zhao, Yuyi Wang. "**Variational Quantum Circuit Model for Knowledge Graphs Embedding**". **arxiv 2019-03**. [paper](https://arxiv.org/abs/1903.00556)

- Pengwei Wang, Dejing Dou, Fangzhao Wu, Nisansa de Silva, Lianwen Jin. "**Logic Rules Powered Knowledge Graph Embedding**". **arxiv 2019-03**. [paper](https://arxiv.org/abs/1903.03772)

- Yanjie Wang, Samuel Broscheit, Rainer Gemulla. "**A Relational Tucker Decomposition for Multi-Relational Link Prediction**". **arxiv 2019-02**. [paper](https://arxiv.org/abs/1902.00898)

### 2020

- <a name="CompGCN"></a> **(CompGCN)** Shikhar Vashishth, Soumya Sanyal, Vikram Nitin, Partha Talukdar. "**Composition-based Multi-Relational Graph Convolutional Networks**". **ICLR 2020**. [paper](https://openreview.net/pdf?id=BylA_C4tPr) [code](https://github.com/malllabiisc/CompGCN)

- <a name="Neural-LP-N"></a> **(Neural-LP-N)** Po-Wei Wang, Daria Stepanova, Csaba Domokos, J. Zico Kolter. "**Differentiable learning of numerical rules in knowledge graphs**". **ICLR 2020**. [paper](https://openreview.net/forum?id=rJleKgrKwS)

- <a name="Teach"></a> **(Teach)** Daniel Ruffinelli, Samuel Broscheit, Rainer Gemulla. "**You CAN Teach an Old Dog New Tricks! On Training Knowledge Graph Embeddings**". **ICLR 2020**. [paper](https://openreview.net/forum?id=BkxSmlBFvr) 

- Pedro Tabacof, Luca Costabello. "**Probability Calibration for Knowledge Graph Embedding Models**". **ICLR 2020**. [paper](https://openreview.net/forum?id=S1g8K1BFwS) 

- Bahare Fatemi, Perouz Taslakian, David Vazquez, David Poole. "**Knowledge Hypergraphs: Prediction Beyond Binary Relations**". **ICLR 2020**. [paper](https://openreview.net/forum?id=ryxIZR4tvS) 

- <a name="TComplEx"></a> **(TComplEx)** Timothée Lacroix, Guillaume Obozinski, Nicolas Usunier. "**Tensor Decompositions for Temporal Knowledge Base Completion**". **ICLR 2020**. [paper](https://openreview.net/forum?id=rke2P1BFwS) 

- <a name="Q2B"></a> **(Q2B)** Hongyu Ren, Weihua Hu, Jure Leskovec. "**Query2box: Reasoning over Knowledge Graphs in Vector Space Using Box Embeddings**". **ICLR 2020**. [paper](https://openreview.net/forum?id=BJgr4kSFDS)  

- <a name="ReifKB"></a> **(ReifKB)**  William W. Cohen, Haitian Sun, R. Alex Hofer, Matthew Siegler. "**Scalable Neural Methods for Reasoning With a Symbolic Knowledge Base**". **ICLR 2020**. [paper](https://openreview.net/forum?id=BJlguT4YPr)  

- <a name="DPMPN"></a> **(DPMPN)** Xiaoran Xu, Wei Feng, Yunsheng Jiang, Xiaohui Xie, Zhiqing Sun, Zhi-Hong Deng. "**Dynamically Pruned Message Passing Networks for Large-scale Knowledge Graph Reasoning**". **ICLR 2020**. [paper](https://openreview.net/forum?id=rkeuAhVKvB)

- <a name="InteractE"></a> **(InteractE)** Shikhar Vashishth, Soumya Sanyal, Vikram Nitin, Nilesh Agrawal, Partha Talukdar. "**InteractE: Improving Convolution-based Knowledge Graph Embeddings by Increasing Feature Interactions**". **AAAI 2020**. [paper](https://arxiv.org/abs/1911.00219) [code](https://github.com/malllabiisc/InteractE) [supp](https://shikhar-vashishth.github.io/assets/pdf/interacte_supp.pdf)

- <a name="HAKE"></a> **(HAKE)** Zhanqiu Zhang, Jianyu Cai, Yongdong Zhang, Jie Wang. "**Learning Hierarchy-Aware Knowledge Graph Embeddings for Link Prediction**". **AAAI 2020**. [paper](https://arxiv.org/abs/1911.09419) [code](https://github.com/MIRALab-USTC/KGE-HAKE)

- <a name="FSRL"></a> **(FSRL)** Chuxu Zhang, Huaxiu Yao, Chao Huang, Meng Jiang, Zhenhui Li, Nitesh V. Chawla. "**Few-Shot Knowledge Graph Completion**". **AAAI 2020**. [paper](https://arxiv.org/abs/1911.11298)

- <a name="RPJE"></a> **(RPJE)** Guanglin Niu, Yongfei Zhang, Bo Li, Peng Cui, Si Liu, Jingyang Li, Xiaowei Zhang. "**Rule-Guided Compositional Representation Learning on Knowledge Graphs**". **AAAI 2020**. [paper](https://arxiv.org/abs/1911.08935)

- **(R2D2)** Marcel Hildebrandt, Jorge Andres Quintero Serna, Yunpu Ma, Martin Ringsquandl, Mitchell Joblin, Volker Tresp. "**Reasoning on Knowledge Graphs with Debate Dynamics**". **AAAI 2020**. [paper](https://arxiv.org/abs/2001.00461)

-	Feihu Che, Dawei Zhang, Jianhua Tao, Mingyue Niu, Bocheng Zhao. "**ParamE: Regarding Neural Network Parameters as Relation Embeddings for Knowledge Graph Completion**". **AAAI 2020**

-	**(GNTPs)** Pasquale Minervini, Matko Bosnjak, Tim Rocktäschel, Sebastian Riedel, Edward Grefenstette. "**Differentiable Reasoning on Large Knowledge Bases and Natural Language**". **AAAI 2020**. [paper]( https://arxiv.org/abs/1912.10824)

-	Zhao Zhang, Fuzhen Zhuang, Hengshu Zhu, Zhiping Shi, Hui Xiong, Qing He. "**Relational Graph Neural Network with Hierarchical Attention for Knowledge Graph Completion**". **AAAI 2020**

-	Pengda Qin, Xin Wang, Wenhu Chen, Chunyun Zhang, Weiran Xu, William Yang Wang. "**Generative Adversarial Zero-Shot Relational Learning for Knowledge Graphs**". **AAAI 2020**. [paper]( https://arxiv.org/abs/2001.02332)

- George Stoica, Otilia Stretcu, Anthony Platanios, Tom Mitchell, Barnabas Poczos. "**Contextual Parameter Generation for Knowledge Graph Link Prediction**". **AAAI 2020**

- <a name="DE-SimplE"></a> **(DE-SimplE)** Rishab Goel, Seyed Mehran Kazemi, Marcus Brubaker, Pascal Poupart. "**Diachronic Embedding for Temporal Knowledge Graph Completion**". **AAAI 2020**. [paper](https://arxiv.org/abs/1907.03143) [code](https://github.com/BorealisAI/DE-SimplE)

-	Chaitanya Malaviya, Chandra Bhagavatula, Antoine Bosselut, Yejin Choi. "**Commonsense Knowledge Base Completion with Structural and Semantic Context**". **AAAI 2020**

- Mehdi Ali, Hajira Jabeen, Charles Tapley Hoyt, Jens Lehmann. "**The KEEN Universe: An Ecosystem for Knowledge Graph 
Embeddings with a Focus on Reproducibility and Transferability**". **arxiv 2020-01**. [paper](https://arxiv.org/abs/2001.10560)

- Caglar Demir, Axel-Cyrille Ngonga Ngomo. "**A Physical Embedding Model for Knowledge Graphs**". **arxiv 2020-01**.
[paper](https://arxiv.org/abs/2001.07418)

- Jiaoyan Chen, Xi Chen, Ian Horrocks, Ernesto Jiménez-Ruiz, Erik B. Myklebust. "**Correcting Knowledge Base Assertions**". 
**2020-01**. [paper](https://arxiv.org/abs/2001.06917)

- Yunpu Ma, Yuyi Wang, Volker Tresp. "**Quantum Machine Learning Algorithm for Knowledge Graphs**". 
**arxiv 2020-01**. [paper](https://arxiv.org/abs/2001.01077)

## Datasets

### Standard

| Dataset   | Entity  | Relation |  Training  |  Validation | Test   |
|:---------:|:-------:|:--------:|:----------:|:-----------:|:------:|
| WN11      | 38,696  | 11       |  112,581   | 2,609       | 10,544 |
| WN18      | 40,943  | 18       |  141,442   | 5,000       | 5,000  |
| WN18RR    | 40,943  | 11       |  86,835    | 3,034       | 3,134  |
| FB13      | 75,043  | 13       |  316,232   | 5,908       | 23,733 |
| FB15K     | 14,951  | 1,345    |  483,142   | 50,000      | 59,071 |
| FB166     | 9,658   | 166      | 100,289    | 10,457      | 12,327 |
| FB15k-237 | 14,541  | 237      |  272,115   | 17,535      | 20,466 |
| UMLS      | 135     | 46       |  5,216     | 652         | 661    |
| YAGO3-10  | 123,182 | 37       |  1,079,040 | 5,000       | 5,000  |
| NELL-995  | 75,492  | 200      |  123,370   | 15,000      | 15,838 |
| NELL-995  | 75,492  | 200      |  149,678   | 543         | 3992   |
| Kinship   | 104     | 25       |  8544      | 1068        | 1074   |

### Rule

### Text

### Temporal

| Dataset     | Entities | Relations | Time Steps | Time Span | Training | Validation | Test   |
|:-----------:|:--------:|:---------:|:----------:|:---------:|:--------:|:----------:|:------:|
| ICEWS14     | 6,869    | 230       | 365        | 2014      | 72,826   | 8,941      | 8,963  |
| ICEWS05-15  | 10,094   | 251       | 4,017      | 2005-2015 | 368,962  | 46,275     | 46,092 |
| YAGO11k     | 10,623   | 10        | 70         | -453-2844 | 16,408   | 2,050      | 2,051  |
| Wikidata12k | 12,554   | 24        | 81         | 1709-2018 | 32,497   | 4,062      | 4,062  |

## Performance

### Link Prediction

#### WN18

| Year | Source | Methods |  MR |  MRR |Hits@1| Hits@3 | Hits@10 |
|:----:|:------:|:-------:|:---:|:----:|:----:|:------:|:-------:|
| 2013 | NeurIPS | **[TransE](#TransE)<sup>[ComplEx](#ComplEx)</sup>**     |  -  | 0.454 | 0.089 | 0.823 | 0.934 |
| 2015 | ICLR    | **[DistMult](#DistMult)<sup>[ComplEx](#ComplEx)</sup>** | 902 | 0.822 | 0.728 | 0.914 | 0.936 |
| 2016 | ICML    | **[ComplEx](#ComplEx)**                                 |  -  | 0.941 | 0.936 | 0.945 | 0.947 |
| 2018 | AAAI    | **[ConvE](#ConvE)**                                     | 504 | 0.942 | 0.935 | 0.947 | 0.955 |
| 2018 | ESWC    | **R-GCN+**    |  -  | 81.9 | 69.7 |  92.9  |   96.4  |
| 2018 | NeurIPS | **SimplE**    |  -  | 94.2 | 93.9 |  94.4  |   94.7  |
| 2019 | ICLR    | **[RotatE](#RotatE)**                                   | 309 | 0.949 | 0.944 | 0.952 | 0.959 |
| 2019 | ACL     | **D4-STE**    |  -  | 94.6 | 94.2 |  94.8  |   95.2  |
| 2019 | ACL     | **D4-Gumbel** |  -  | 94.6 | 94.2 |  94.9  |   95.4  |
| 2019 | EMNLP   | **[TuckER](#TuckER)**                                   |   - | 0.953 | 0.949 | 0.955 | 0.958 |

#### WN18RR

| Year | Source | Methods |  MR |  MRR |Hits@1| Hits@3 | Hits@10 |
|:----:|:------:|:-------:|:---:|:----:|:----:|:------:|:-------:|
| 2013 | NeurIPS | **[TransE](#TransE)<sup>[ConvKB](#ConvKB)</sup>**    | 3384 | 0.226 |   -   |  -    | 0.501 |
| 2015 | ICLR    | **[DistMult](#DistMult)<sup>[ConvE](#ConvE)</sup>**  | 5110 | 0.43  | 0.39  | 0.44  | 0.49  |
| 2016 | ICML    | **[ComplEx](#ComplEx)<sup>[ConvE](#ConvE)</sup>**    | 5261 | 0.44  | 0.41  | 0.46  | 0.51  |
| 2018 | AAAI    | **[ConvE](#ConvE)**                                  | 5277 | 0.46  | 0.39  | 0.43  | 0.48  |
| 2019 | ICLR    | **[RotatE](#RotatE)**                                | 3340 | 0.476 | 0.428 | 0.492 | 0.571 |
| 2019 | ACL     | **D4-STE**    |   -  | 48.0 | 45.2 |  49.1  |   53.6  |
| 2019 | ACL     | **D4-Gumbel** |   -  | 48.6 | 44.2 |  50.5  |   55.7  |
| 2019 | EMNLP   | **[TuckER](#TuckER)**                                |   -  | 0.470 | 0.443 | 0.482 | 0.526 |
| 2020 | AAAI    | **[HAKE](#HAKE)**                                    |   -  | 0.497 | 0.452 | 0.516 | 0.582 |
| 2020 | AAAI    | **InteractE** | 5203 | 46.3 | 43.0 |  -     |   52.8  |

#### FB15K

| Year | Source | Methods |  MR |  MRR |Hits@1| Hits@3 | Hits@10 |
|:----:|:------:|:-------:|:---:|:----:|:----:|:------:|:-------:|
| 2013 | NeurIPS | **[TransE](#TransE)<sup>[ComplEx](#ComplEx)</sup>**      | -  | 0.380 | 0.231 | 0.472 | 0.641 |
| 2015 | ICLR    | **[DistMult](#DistMult)<sup>[ComplEx](#ComplEx)</sup>**  | 97 | 0.654 | 0.546 | 0.733 | 0.824 |
| 2016 | ICML    | **[ComplEx](#ComplEx)**                                  | -  | 0.692 | 0.599 | 0.759 | 0.840 |
| 2018 | AAAI    | **[ConvE](#ConvE)**                                      | 64 | 0.745 | 0.670 | 0.801 | 0.873 |
| 2018 | ESWC    | **R-GCN+**    |   -   | 69.6 | 60.1 |  76.0  |   84.2  |
| 2018 | NeurIPS | **SimplE**    |   -   | 72.7 | 66.0 |  77.3  |   83.8  |
| 2019 | ICLR    | **[RotatE](#RotatE)**                                    | 40 | 0.797 | 0.746 | 0.830 | 0.884 |
| 2019 | ACL     | **D4-STE**    |   -   | 73.3 | 64.1 |   80.3 |   87.7  |
| 2019 | ACL     | **D4-Gumbel** |   -   | 72.8 | 64.8 |   78.2 |   86.4  |
| 2019 | EMNLP   | **[TuckER](#TuckER)**                                    | -  | 0.795 | 0.741 | 0.833 | 0.892 |

#### FB15K-237

| Year | Source | Methods |  MR |  MRR |Hits@1| Hits@3 | Hits@10 |
|:----:|:------:|:-------:|:---:|:----:|:----:|:------:|:-------:|
| 2013 | NeurIPS | **[TransE](#TransE)<sup>[ConvKB](#ConvKB)</sup>**    | 357 | 0.294 |   -   |    -  | 0.465 |
| 2015 | ICLR    | **[DistMult](#DistMult)<sup>[ConvE](#ConvE)</sup>**  | 254 | 0.241 | 0.155 | 0.263 | 0.419 |
| 2016 | ICML    | **[ComplEx](#ComplEx)<sup>[ConvE](#ConvE)</sup>**    | 339 | 0.247 | 0.158 | 0.275 | 0.428 |
| 2018 | ESWC    | **R-GCN+**    |  -  | 24.9 | 15.1 |  26.4  |   41.7  |
| 2018 | AAAI    | **[ConvE](#ConvE)**                                  | 246 | 0.316 | 0.239 | 0.350 | 0.491 |
| 2019 | ICLR    | **[RotatE](#RotatE)**                                | 177 | 0.338 | 0.241 | 0.375 | 0.533 |
| 2019 | ACL     | **D4-STE**    |  -  | 32.0 | 23.0 |  35.3  |   50.2  |
| 2019 | ACL     | **D4-Gumbel** |  -  | 30.0 | 20.4 |  33.2  |   49.6  |
| 2019 | EMNLP   | **[TuckER](#TuckER)**                                |  -  | 0.358 | 0.266 | 0.394 | 0.544 |
| 2020 | AAAI    | **[HAKE](#HAKE)**                                    |  -  | 0.346 | 0.250 | 0.381 | 0.542 |
| 2020 | AAAI    | **InteractE** | 172 | 35.4 | 26.3 |  -     |   53.5  |

#### YAGO3-10

| Year | Source | Methods |  MR |  MRR |Hits@1| Hits@3 | Hits@10 |
|:----:|:------:|:-------:|:---:|:----:|:----:|:------:|:-------:|
| 2015 | ICLR    | **[DistMult](#DistMult)<sup>[ConvE](#ConvE)</sup>**   | 5926 | 0.34  | 0.24  | 0.38  | 0.54  |
| 2016 | ICML    | **[ComplEx](#ComplEx)<sup>[ConvE](#ConvE)</sup>**     | 6351 | 0.36  | 0.26  | 0.40  | 0.55  |
| 2018 | AAAI    | **[ConvE](#ConvE)**                                   | 2792 | 0.52  | 0.45  | 0.56  | 0.66  |
| 2018 | ACL     | **ComplEx-N3** | -    | 0.58  |  -     |  -     |  0.71  |
| 2019 | ACL     | **D4-STE**    |   -   | 0.472 |  0.381 |  0.523 |  0.643 |
| 2019 | ACL     | **D4-Gumbel** |   -   | 0.388 |  0.294 |  0.436 |  0.573 |
| 2019 | ICLR    | **[RotatE](#RotatE)**                                 | 1767 | 0.495 | 0.402 | 0.550 | 0.670 |
| 2020 | AAAI    | **[HAKE](#HAKE)**                                     |  -   | 0.545 | 0.462 | 0.596 | 0.694 |
| 2020 | AAAI    | **InteractE**  | 2375 | 0.541 |  0.462 |  -     |  0.687 |
| 2020 | ICLR    | **DPMPN**      | -    | 0.553 |  0.484 |  0.595 |  0.679 |


#### NELL-995

| Year | Source | Methods |  MR |  MRR |Hits@1| Hits@3 | Hits@10 |
|:----:|:------:|:-------:|:---:|:----:|:----:|:------:|:-------:|
| 2013 | NeurIPS | **TransE**    | -    | 0.219  |  -     |   -    |  0.352 |
| 2015 | ICLR    | **DistMult**  | -    | -      |  0.610 |  -     |  0.795 |
| 2015 | EMNLP   | **PTransE**   | -    | 0.304  |  -     |   -    |  0.437 |
| 2016 | ICML    | **ComplEx**   | -    | -      |  0.612 |  -     |  0.827 |
| 2018 | AAAI    | **ConvE**     | -    | -      |  0.672 |  -     |  0.864 |
| 2018 | AAAI    | **RUGE**      | -    | 0.318  |  -     |   -    |  0.433 |
| 2020 | AAAI    | **RPJE**      | -    | 0.361  |  -     |   -    |  0.501 |
| 2020 | ICLR    | **ReifKB**    | -    | -      |  0.641 |   -    |  0.824 |

#### GDELT

| Year | Source | Methods    |  MR |  MRR  | Hits@1 | Hits@3 | Hits@10 |
|:----:|:------:|:----------:|:---:|:-----:|:------:|:------:|:-------:|
| 2018 | EMNLP | **[TA-DistMult](#TA-DistMult)<sup>[DE-SinplE](#DE-SimplE)</sup>** | - | 0.206 | 0.124 | 0.219 | 0.365 |
| 2018 | EMNLP  | **[HyTE](#HyTE)<sup>[DE-SinplE](#DE-SimplE)</sup>** | - | 0.118 | 0.0 | 0.165 | 0.326 |
| 2020 | AAAI | **[DE-SimplE](#DE-SimplE)** | - | 0.230 | 0.141 | 0.248 | 0.403 |

#### ICEWS14

| Year | Source | Methods     |  MR |  MRR  | Hits@1 | Hits@3 | Hits@10 |
|:----:|:------:|:-----------:|:---:|:-----:|:------:|:------:|:-------:|
| 2018 | EMNLP  | **[TA-DistMult](#TA-DistMult)** | 276 | 0.477 | 0.363  | -      | 0.686   |
| 2018 | EMNLP  | **[HyTE](#HyTE)<sup>[DE-SinplE](#DE-SimplE)</sup>** | - | 0.297 | 0.108 | 0.416 | 0.655 |
| 2020 | AAAI   | **[DE-SimplE](#DE-SimplE)**    | -   | 0.526 | 0.418  | 0.592  | 0.725   |
| 2020 | ICLR   | **[TNTComplEx](#TNTComplEx)**  | -   | 0.56  | 0.46   | 0.61   | 0.74    |

#### ICEWS15-05

| Year | Source | Methods    |  MR |  MR R | Hits@1 | Hits@3 | Hits@10 |
|:----:|:------:|:----------:|:---:|:-----:|:------:|:------:|:-------:|
| 2018 | EMNLP  | **[TA-DistMult](#TA-DistMult)** | 98 | 0.474 | 0.346  | - | 0.728 |
| 2018 | EMNLP  | **[HyTE](#HyTE)<sup>[DE-SinplE](#DE-SimplE)</sup>** | - | 0.316 | 0.116 | 0.445 | 0.681 |
| 2020 | AAAI   | **[DE-SimplE](#DE-SimplE)**   | -   | 0.513 | 0.392  | 0.578  | 0.748   |
| 2020 | ICLR   | **[TNTComplEx](#TNTComplEx)** | -   | 0.60  | 0.50   | 0.65   | 0.78    |

#### YAGO15K

| Year | Source | Methods    |  MR |  MRR | Hits@1 | Hits@3 | Hits@10 |
|:----:|:------:|:----------:|:---:|:----:|:------:|:------:|:-------:|
| 2018 | EMNLP  | **[TA-DistMult](TA-DistMult)** | 551 | 0.291 | 0.216 | -    | 0.476 |
| 2020 | ICLR   | **[TNTComplEx](#TNTComplEx)**  | -   | 0.35  | 0.28  | 0.35 | 0.52  |

#### WikiDATA

| Year | Source | Methods     |  MR |  MRR  | Hits@1 | Hits@3 | Hits@10 |
|:----:|:------:|:-----------:|:---:|:-----:|:------:|:------:|:-------:|
| 2018 | EMNLP  | **[TA-DistMult](TA-DistMult)** | 198 | 0.700 | 0.652 | - | 0.785 |



