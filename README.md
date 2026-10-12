# Federated Learning Paper Hub

This repository is a curated hub for **Federated Learning (FL)** research, aiming to collect
classic and recent papers with links.

---

## Contents

- [01. Foundational Works](#01-foundational-works)
- [02. Federated Optimization and Generalization](#02-federated-optimization-and-generalization)
- [03. Personalized Federated Learning](#03-personalized-federated-learning)
- [04. Prototype and Representation Learning](#04-prototype-and-representation-learning)
- [05. Federated Knowledge Distillation](#05-federated-knowledge-distillation)
- [06. Federated Prompt Learning](#06-federated-prompt-learning)
- [07. Federated Foundation Models and LLMs](#07-federated-foundation-models-and-llms)
- [08. Federated Graph and Multi-view Learning](#08-federated-graph-and-multi-view-learning)
- [09. Privacy-Preserving Federated Learning](#09-privacy-preserving-federated-learning)
- [10. Top Journal Papers](#10-top-journal-papers)
- [11. Surveys and Tutorials](#11-surveys-and-tutorials)

## 01. Foundational Works (2 papers)

- **[Communication-Efficient Learning of Deep Networks from Decentralized Data](https://proceedings.mlr.press/v54/mcmahan17a/mcmahan17a.pdf)** — AISTATS 2017 · *FedAvg*
- **[Towards Federated Learning at Scale: System Design](https://proceedings.mlsys.org/paper_files/paper/2019/hash/7b770da633baf74895be22a8807f1a8f-Abstract.html)** — MLSys 2019

## 02. Federated Optimization and Generalization (12 papers)

- **[Federated Optimization in Heterogeneous Networks](https://proceedings.mlsys.org/paper_files/paper/2020/hash/1f5fe83998a09396ebe6477d9475ba0c-Abstract.html)** — MLSys 2020 · *FedProx*
- **[SCAFFOLD: Stochastic Controlled Averaging for Federated Learning](https://proceedings.mlr.press/v119/karimireddy20a.html)** — ICML 2020
- **[Tackling the Objective Inconsistency Problem in Heterogeneous Federated Optimization](https://papers.neurips.cc/paper/2020/hash/564127c03caab942e503ee6f810f54fd-Abstract.html)** — NeurIPS 2020 · *FedNova*
- **[Adaptive Federated Optimization](https://openreview.net/forum?id=LkFG3lB13U5)** — ICLR 2021 · *FedOpt*
- **[Federated Learning Based on Dynamic Regularization](https://openreview.net/forum?id=B7v4QMR6Z9w)** — ICLR 2021 · *FedDyn*
- **[Balancing Similarity and Complementarity for Federated Learning](https://proceedings.mlr.press/v235/yan24a.html)** — ICML 2024 · *FedSaC*
- **[Beyond the Federation: Topology-aware Federated Learning for Generalization to Unseen Clients](https://proceedings.mlr.press/v235/ma24e.html)** — ICML 2024
- **[FedUV: Uniformity and Variance for Heterogeneous Federated Learning](https://openaccess.thecvf.com/content/CVPR2024/html/Son_FedUV_Uniformity_and_Variance_for_Heterogeneous_Federated_Learning_CVPR_2024_paper.html)** — CVPR 2024
- **[FedGPS: Statistical Rectification Against Data Heterogeneity in Federated Learning](https://papers.neurips.cc/paper_files/paper/2025/hash/87ee1bbac4635e7c948f3eea83c1f262-Abstract-Conference.html)** — NeurIPS 2025
- **[Widening the Network Mitigates the Impact of Data Heterogeneity on FedAvg](https://proceedings.mlr.press/v267/jian25a.html)** — ICML 2025
- **[One Arrow, Two Hawks: Sharpness-aware Minimization for Federated Learning via Global Model Trajectory](https://proceedings.mlr.press/v267/li25bd.html)** — ICML 2025 · *FedGMT*
- **[Momentum-Driven Adaptivity: Towards Tuning-Free Asynchronous Federated Learning](https://proceedings.mlr.press/v267/yan25f.html)** — ICML 2025

## 03. Personalized Federated Learning (17 papers)

- **[Personalized Federated Learning with Moreau Envelopes](https://papers.neurips.cc/paper_files/paper/2020/hash/f4f1f13c8289ac1b1ee0ff176b56fc60-Abstract.html)** — NeurIPS 2020 · *pFedMe*
- **[Personalized Federated Learning with Theoretical Guarantees: A Model-Agnostic Meta-Learning Approach](https://proceedings.neurips.cc/paper/2020/hash/24389bfe4fe2eba8bf9aa9203a44cdad-Abstract.html)** — NeurIPS 2020 · *Per-FedAvg*
- **[Ditto: Fair and Robust Federated Learning Through Personalization](https://proceedings.mlr.press/v139/li21h.html)** — ICML 2021
- **[Exploiting Shared Representations for Personalized Federated Learning](https://proceedings.mlr.press/v139/collins21a.html)** — ICML 2021 · *FedRep*
- **[FedBABU: Toward Enhanced Representation for Federated Image Classification](https://openreview.net/forum?id=HuaYQfggn5u)** — ICLR 2022
- **[FedALA: Adaptive Local Aggregation for Personalized Federated Learning](https://ojs.aaai.org/index.php/AAAI/article/view/26330)** — AAAI 2023
- **[Personalized Federated Learning with Feature Alignment and Classifier Collaboration](https://openreview.net/forum?id=SXZr8aDKia)** — ICLR 2023 · *FedPAC*
- **[Bold but Cautious: Unlocking the Potential of Personalized Federated Learning through Cautiously Aggressive Collaboration](https://openaccess.thecvf.com/content/ICCV2023/html/Wu_Bold_but_Cautious_Unlocking_the_Potential_of_Personalized_Federated_Learning_ICCV_2023_paper.html)** — ICCV 2023 · *FedCAC*
- **[Personalized Federated Learning with Inferred Collaboration Graphs](https://proceedings.mlr.press/v202/ye23b.html)** — ICML 2023 · *pFedGraph*
- **[FedAS: Bridging Inconsistency in Personalized Federated Learning](https://openaccess.thecvf.com/content/CVPR2024/html/Yang_FedAS_Bridging_Inconsistency_in_Personalized_Federated_Learning_CVPR_2024_paper.html)** — CVPR 2024
- **[Personalized Federated Learning via Feature Distribution Adaptation](https://proceedings.neurips.cc/paper_files/paper/2024/hash/8ce6c5450ccddbe6adee4b3749893587-Abstract-Conference.html)** — NeurIPS 2024 · *pFedFDA*
- **[FedCALM: Conflict-aware Layer-wise Mitigation for Selective Aggregation in Deeper Personalized Federated Learning](https://openaccess.thecvf.com/content/CVPR2025/html/Zheng_FedCALM_Conflict-aware_Layer-wise_Mitigation_for_Selective_Aggregation_in_Deeper_Personalized_CVPR_2025_paper.html)** — CVPR 2025
- **[Federated Oriented Learning: A Practical One-Shot Personalized Federated Learning Framework](https://proceedings.mlr.press/v267/huang25ae.html)** — ICML 2025
- **[Personalized Bayesian Federated Learning with Wasserstein Barycenter Aggregation](https://proceedings.neurips.cc/paper_files/paper/2025/hash/6d0c18c6edc02be434c883bdd9fbe3b5-Abstract-Conference.html)** — NeurIPS 2025
- **[Few-for-Many Personalized Federated Learning](https://openaccess.thecvf.com/content/CVPR2026/html/Guo_Few-for-Many_Personalized_Federated_Learning_CVPR_2026_paper.html)** — CVPR 2026 · *FedFew*
- **[FedMerge: Federated Model Merging for Personalization](https://ojs.aaai.org/index.php/AAAI/article/view/39113)** — AAAI 2026
- **[PPFL: A Parameter Behavior-Driven Plug-in Personalization Engine for Federated Learning](https://ojs.aaai.org/index.php/AAAI/article/view/39073)** — AAAI 2026

## 04. Prototype and Representation Learning (8 papers)

- **[FedProto: Federated Prototype Learning across Heterogeneous Clients](https://ojs.aaai.org/index.php/AAAI/article/view/20819)** — AAAI 2022
- **[Model-Contrastive Federated Learning](https://openaccess.thecvf.com/content/CVPR2021/html/Li_Model-Contrastive_Federated_Learning_CVPR_2021_paper.html)** — CVPR 2021 · *MOON*
- **[FedBN: Federated Learning on Non-IID Features via Local Batch Normalization](https://openreview.net/pdf?id=6YEQUn0QICG)** — ICLR 2021
- **[Federated Learning with Matched Averaging](https://iclr.cc/virtual_2020/poster_BkluqlSFDS.html)** — ICLR 2020 · *FedMA*
- **[Tackling Data Heterogeneity in Federated Learning with Class Prototypes](https://ojs.aaai.org/index.php/AAAI/article/view/25891)** — AAAI 2023 · *FedNH*
- **[FedSA: A Unified Representation Learning via Semantic Anchors for Prototype-based Federated Learning](https://ojs.aaai.org/index.php/AAAI/article/view/34464)** — AAAI 2025
- **[Intra-Class Unbiased Prototype Aggregation and Classifier Collaboration for Personalized Federated Learning](https://ojs.aaai.org/index.php/AAAI/article/view/40113)** — AAAI 2026 · *FedIC*
- **[FedPKDA: Personalized Federated Learning with Privacy-Preserving Knowledge Dynamic Alignment](https://ojs.aaai.org/index.php/AAAI/article/view/40037)** — AAAI 2026

## 05. Federated Knowledge Distillation (2 papers)

- **[Ensemble Distillation for Robust Model Fusion in Federated Learning](https://proceedings.neurips.cc/paper/2020/hash/18df51b97ccd68128e994804f3eccc87-Abstract.html)** — NeurIPS 2020 · *FedDF*
- **[Data-Free Knowledge Distillation for Heterogeneous Federated Learning](https://proceedings.mlr.press/v139/zhu21b.html)** — ICML 2021 · *FedGen*

## 06. Federated Prompt Learning (6 papers)

- **[Federated Adaptive Prompt Tuning for Multi-Domain Collaborative Learning](https://ojs.aaai.org/index.php/AAAI/article/view/29434)** — AAAI 2024 · *FedAPT*
- **[Federated Text-driven Prompt Generation for Vision-Language Models](https://proceedings.iclr.cc/paper_files/paper/2024/hash/37e90dcf2909b5068858b34b5239f187-Abstract-Conference.html)** — ICLR 2024 · *FedTPG*
- **[Global and Local Prompts Cooperation via Optimal Transport for Federated Learning](https://openaccess.thecvf.com/content/CVPR2024/html/Li_Global_and_Local_Prompts_Cooperation_via_Optimal_Transport_for_Federated_CVPR_2024_paper.html)** — CVPR 2024 · *FedOTP*
- **[Unlocking the Potential of Prompt-Tuning in Bridging Generalized and Personalized Federated Learning](https://openaccess.thecvf.com/content/CVPR2024/html/Deng_Unlocking_the_Potential_of_Prompt-Tuning_in_Bridging_Generalized_and_Personalized_CVPR_2024_paper.html)** — CVPR 2024 · *SGPT*
- **[FedPHA: Federated Prompt Learning for Heterogeneous Client Adaptation](https://proceedings.mlr.press/v267/fang25e.html)** — ICML 2025
- **[FedMGP: Personalized Federated Learning with Multi-Group Text-Visual Prompts](https://proceedings.neurips.cc/paper_files/paper/2025/hash/4a4d5fca4bbb93ead4548854f1f28c0f-Abstract-Conference.html)** — NeurIPS 2025

## 07. Federated Foundation Models and LLMs (4 papers)

- **[On-Device Collaborative Language Modeling via a Mixture of Generalists and Specialists](https://proceedings.mlr.press/v267/fan25h.html)** — ICML 2025
- **[FedP²EFT: Federated Learning to Personalize PEFT for Multilingual LLMs](https://ojs.aaai.org/index.php/AAAI/article/view/39443)** — AAAI 2026
- **[FedALT: Federated Fine-Tuning Through Adaptive Local Training with Rest-of-World LoRA](https://ojs.aaai.org/index.php/AAAI/article/view/39054)** — AAAI 2026
- **[Bi-level Personalization for Federated Foundation Models: A Task-vector Aggregation Approach](https://ojs.aaai.org/index.php/AAAI/article/view/39991)** — AAAI 2026

## 08. Federated Graph and Multi-view Learning (3 papers)

- **[Less is More: Federated Graph Learning with Alleviating Topology Heterogeneity from A Causal Perspective](https://proceedings.mlr.press/v267/fu25a.html)** — ICML 2025
- **[FedIGL: Federated Invariant Graph Learning for Non-IID Graphs](https://doi.org/10.52202/085713-3931)** — NeurIPS 2025
- **[An Effective and Secure Federated Multi-View Clustering Method with Information-Theoretic Perspective](https://proceedings.mlr.press/v267/chen25az.html)** — ICML 2025

## 09. Privacy-Preserving Federated Learning (1 papers)

- **[Practical Secure Aggregation for Privacy-Preserving Machine Learning](https://acmccs.github.io/papers/p1175-bonawitzA.pdf)** — ACM CCS 2017

## 10. Top Journal Papers (7 papers)

- **[Federated Learning for Generalization, Robustness, Fairness: A Survey and Benchmark](https://doi.org/10.1109/TPAMI.2024.3418862)** — IEEE TPAMI 2024
- **[Addressing Skewed Heterogeneity via Federated Prototype Rectification With Personalization](https://doi.org/10.1109/TNNLS.2024.3438281)** — IEEE TNNLS 2024 · *Online 2024*
- **[MAP: Model Aggregation and Personalization in Federated Learning With Incomplete Classes](https://doi.org/10.1109/TKDE.2024.3390041)** — IEEE TKDE 2024
- **[Robust Asymmetric Heterogeneous Federated Learning With Corrupted Clients](https://doi.org/10.1109/TPAMI.2025.3527137)** — IEEE TPAMI 2025
- **[Toward the Flatter Landscape and Better Generalization in Federated Learning Under Client-Level Differential Privacy](https://doi.org/10.1109/TPAMI.2025.3597922)** — IEEE TPAMI 2025
- **[FedPnP: Personalized graph-structured federated learning](https://doi.org/10.1016/j.patcog.2025.111455)** — Pattern Recognition 2025
- **[Intermediate features matter in prototype-guided personalized federated learning](https://doi.org/10.1016/j.inffus.2025.103381)** — Information Fusion 2025
