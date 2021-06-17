# Graph Networks

| Year | Source |	Methods |
|:----:|:----:|:----:|
| 2018 | ESWC | **[R-GCN](#R-GCN)** |
| 2019 | AAAI | **[SACN](#SACN)** |
| 2019 | ACL | **[KBGAT](#KBGAT)** |
| 2019 | IJCAI | **[VR-GCN](#VR-GCN)** |
| 2019 | K-CAP | **[TransGCN](#TransGCN)** |
| 2020 | ICLR | **[CompGCN](#CompGCN)** |
| 2020 | ICLR | **[DPMPN](#DPMPN)** |
| 2020 | AAAI | **[RGHAT](#RGHAT)** |
| 2020 | CIKM | **[GAEAT](#GAEAT)** |
| 2020 | ICMLC | **[RA-GCN](#RA-GCN)** |
| 2020 | CoRR | **[AR-KGAT](#AR-KGAT)** |
| 2020 | IEEE Access | **[LSA-GAT](#LSA-GAT)** |

# Papers

## 2018

- <a name="R-GCN"></a> **(R-GCN)** Michael Schlichtkrull, Thomas N. Kipf, Peter Bloem, Rianne van den Berg, Ivan Titov, Max Welling. "**Modeling Relational Data with Graph Convolutional Networks**". **ESWC 2018**. [paper](https://link.springer.com/chapter/10.1007%2F978-3-319-93417-4_38) [code](https://github.com/tkipf/relational-gcn) :fire:

## 2019

- <a name="SACN"></a> **(SACN)** Chao Shang, Yun Tang, Jing Huang, Jinbo Bi, Xiaodong He, Bowen Zhou. "**End-to-End Structure-Aware Convolutional Networks for Knowledge Base Completion**". **AAAI 2019**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/4164) [code](https://github.com/JD-AI-Research-Silicon-Valley/SACN) :fire:

- <a name="KBGAT"></a> **(KBGAT)** Deepak Nathani, Jatin Chauhan, Charu Sharma, Manohar Kaul. "**Learning Attention-based Embeddings for Relation Prediction in Knowledge Graphs**". **ACL 2019**. [paper](https://www.aclweb.org/anthology/P19-1466/) [code](https://github.com/deepakn97/relationPrediction) :fire: :boom:

- <a name="VR-GCN"></a> **(VR-GCN)** Rui Ye, Xin Li, Yujie Fang, Hongyu Zang, Mingzhong Wang. "**A Vectorized Relational Graph Convolutional Network for Multi-Relational Network Alignment**". **IJCAI 2019**.  [paper](https://www.ijcai.org/Proceedings/2019/574) 

- <a name="TransGCN"></a> **(TransGCN)**	Ling Cai, Bo Yan, Gengchen Mai, Krzysztof Janowicz, Rui Zhu. "**TransGCN: Coupling Transformation Assumptions with Graph Convolutional Networks for Link Prediction**". **K-CAP 2019**. [paper](https://dl.acm.org/doi/10.1145/3360901.3364441)

## 2020

- <a name="CompGCN"></a> **(CompGCN)** Shikhar Vashishth, Soumya Sanyal, Vikram Nitin, Partha Talukdar. "**Composition-based Multi-Relational Graph Convolutional Networks**". **ICLR 2020**. [paper](https://openreview.net/forum?id=BylA_C4tPr) [code](https://github.com/malllabiisc/CompGCN) :fire:

- <a name="DPMPN"></a> **(DPMPN)** Xiaoran Xu, Wei Feng, Yunsheng Jiang, Xiaohui Xie, Zhiqing Sun, Zhi-Hong Deng. "**Dynamically Pruned Message Passing Networks for Large-scale Knowledge Graph Reasoning**". **ICLR 2020**. [paper](https://openreview.net/forum?id=rkeuAhVKvB) [code](https://github.com/netpaladinx/DPMPN)

- <a name="RGHAT"></a> **(RGHAT)** Zhao Zhang, Fuzhen Zhuang, Hengshu Zhu, Zhiping Shi, Hui Xiong, Qing He. "**Relational Graph Neural Network with Hierarchical Attention for Knowledge Graph Completion**". **AAAI 2020**. [paper](https://aaai.org/ojs/index.php/AAAI/article/view/6508)

- <a name="GAEAT"></a> **(GAEAT)** Yanfei Han, Quan Fang, Jun Hu, Shengsheng Qian, Changsheng Xu. "**GAEAT: Graph Auto-Encoder Attention Networks for Knowledge Graph Completion**". **CIKM 2020**. [paper](https://dl.acm.org/doi/10.1145/3340531.3412148)

- <a name="RA-GCN"></a> **(RA-GCN)** Anqi Tian, Chunhong Zhang, Miao Rang, Xueying Yang, Zhiqiang Zhan. "**RA-GCN: Relational Aggregation Graph Convolutional Network for Knowledge Graph Completion**". **ICMLC 2020**. [paper](https://dl.acm.org/doi/10.1145/3383972.3384067)

- <a name="AR-KGAT"></a> **(AR-KGAT)** Zhenghao Zhang, Jianbin Huang, Qinglin Tan. "**Association Rules Enhanced Knowledge Graph Attention Network**". **CoRR 2011**. [paper](https://arxiv.org/abs/2011.08431)

- <a name="LSA-GAT"></a> **(LSA-GAT)** Kexi Ji, Bei Hui, Guangchun Luo. "**Graph Attention Networks With Local Structure Awareness for Knowledge Graph Completion**". **IEEE Access 2020**. [paper](https://ieeexplore.ieee.org/document/9292922)

# Performance

## FB15k-237

| Year | Source | Methods | MR | MRR | Hits@1 | Hits@3 | Hits@10 |
|:----:|:------:|:-------:|:--:|:---:|:------:|:------:|:-------:|
| 2018 | ESWC | **[R-GCN](#R-GCN)** | 0.158 | 0.248 | 0.153 | 0.258 | 0.414 |
| 2019 | AAAI | **[SACN](#SACN)** | - | 0.35 | 0.26 | 0.39 | 0.54 |
| 2019 | IJCAI | **[VR-GCN](#VR-GCN)** | - | 0.248 | 0.159 | 0.272 | 0.432 |
| 2019 | K-CAP | **[TransGCN](#TransGCN)** | - | 0.356 | 0.252 | 0.388 | 0.555 |
| 2020 | ICLR | **[CompGCN](#CompGCN)** | 197 | 0.355 | 0.264 | 0.390 | 0.535 |
| 2020 | ICLR | **[DPMPN](#DPMPN)** | - | 0.369 | 0.286 | 0.403 | 0.530 |
| 2020 | AAAI | **[RGHAT](#RGHAT)** | 196 | 0.522 | 0.462 | 0.546 | 0.631 |
| 2020 | CIKM | **[GAEAT](#GAEAT)** | 305 | 0.316 | - | - | 0.481 |
| 2020 | ICMLC | **[RA-GCN](#RA-GCN)** | - | 0.249 | - | - | 0.417 |
| 2020 | CoRR | **[AR-KGAT](#AR-KGAT)** | - | 0.442 | 0.361 | 0.483 | 0.581 |
| 2020 | IEEE Access | **[LSA-GAT](#LSA-GAT)** | 273 | 0.47 | 0.41 | 0.50 | 0.60 |

## WN18RR

| Year | Source | Methods | MR | MRR | Hits@1 | Hits@3 | Hits@10 |
|:----:|:------:|:-------:|:--:|:---:|:------:|:------:|:-------:|
| 2019 | AAAI | **[SACN](#SACN)** | - | 0.47 | 0.43 | 0.48 | 0.54 |
| 2019 | K-CAP | **[TransGCN](#TransGCN)** | - | 0.485 | 0.438 | 0.510 | 0.578 |
| 2020 | ICLR | **[CompGCN](#CompGCN)** | 3533 | 0.479 | 0.443 | 0.494 | 0.546 |
| 2020 | ICLR | **[DPMPN](#DPMPN)** | - | 0.482 | 0.444 | 0.497 | 0.558 |
| 2020 | AAAI | **[RGHAT](#RGHAT)** | 1896 | 0.483 | 0.425 | 0.499 | 0.588 |
| 2020 | CIKM | **[GAEAT](#GAEAT)** | 3391 | 0.358 | - | - | 0.534 |
| 2020 | CoRR | **[AR-KGAT](#AR-KGAT)** | - | 0.518 | 0.465 | 0.540 | 0.626 |
| 2020 | IEEE Access | **[LSA-GAT](#LSA-GAT)** | 1947 | 0.44 | 0.35 | 0.49 | 0.58 |
