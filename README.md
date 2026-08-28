# Awesome source free test time adaptation with stars

## Awesome Source-free Test-time Adaptation   [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome) ⭐ 500,632 | 🐛 105 | 📅 2026-08-21 [![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/StrapDown.js/graphs/commit-activity) ⭐ 118 | 🐛 3 | 🌐 CSS | 📅 2022-03-21

This is a curated list of research papers in `Test-time Adaptation` (**TTA**), which also goes by other names, such as `Test-time Training` (**TTT**), `Source-free Domain Adaptation` (**SFDA**) and `Unsupervised Model Adaptation` (**UMA**).

The repository is actively maintained. Pull requests or direct messages are welcome.

### Table of Contents

* [Methods](#methods)
  * [Self-supervision](#self-supervision)
  * [Information Entropy](#information-entropy)
  * [Batch Normalization](#batch-normalization)
  * [Pseudo Labeling](#pseudo-labeling)
  * [Class Prototype](#class-prototype)
  * [Feature Alignment](#feature-alignment)
  * [Generative Modeling](#generative-modeling)
  * [Nearest Neighbors](#nearest-neighbors)
  * [Augmentation Invariance](#augmentation-invariance)
  * [Meta-learning](#meta-learning)
  * [Time-varying](#time-varying)
  * [Others](#others)
* [Benchmark](#benchmark)
* [Applications](#applications)

### Methods

#### Self-supervision

* [Contrastive Test-Time Adaptation](https://openaccess.thecvf.com/content/CVPR2022/papers/Chen_Contrastive_Test-Time_Adaptation_CVPR_2022_paper.pdf) CVPR'22 [\[Code\]](https://github.com/DianCh/AdaContrast) ⭐ 106 | 🐛 4 | 🌐 Python | 📅 2022-04-29
* [TTT++: When Does Self-Supervised Test-Time Training Fail or Thrive?](https://openreview.net/pdf?id=86NHK__yFDl) NeurIPS'21 [\[Code\]](https://github.com/vita-epfl/ttt-plus-plus) ⭐ 75 | 🐛 5 | 🌐 Python | 📅 2022-02-14
* [On the Robustness of Open-World Test-Time Training: Self-Training with Dynamic Prototype Expansion](https://arxiv.org/abs/2308.09942) ICCV'23  [\[Code\]](https://github.com/Yushu-Li/OWTTT) ⭐ 46 | 🐛 0 | 🌐 Python | 📅 2024-12-18
* [Improved Test-Time Adaptation for Domain Generalization](https://arxiv.org/abs/2304.04494) CVPR'23 [\[Code\]](https://github.com/liangchen527/ITTA) ⭐ 34 | 🐛 1 | 🌐 Python | 📅 2025-01-18
* [Test-Time Training with Self-Supervision for Generalization under Distribution Shifts](http://proceedings.mlr.press/v119/sun20b.html) ICML'20 [\[Project\]](https://yueatsprograms.github.io/ttt/home.html)
* [Model Adaptation: Historical Contrastive Learning for Unsupervised Domain Adaptation without Source Data](https://openreview.net/pdf?id=0zXJRJecC_) NeurIPS'21
* [Divide and Contrast: Source-free Domain Adaptation via Adaptive Contrastive Learning](https://openreview.net/forum?id=NjImFaBEHl) NeurIPS'22
* [Test-Time Training with Masked Autoencoders](https://openreview.net/forum?id=SHMi1b7sjXk) NeurIPS'22 [\[Project\]](https://yossigandelsman.github.io/ttt_mae/index.html)
* [PromptStyler: Prompt-driven Style Generation for Source-free Domain Generalization](https://arxiv.org/abs/2307.15199) ICCV'23
* [MATE: Masked Autoencoders are Online 3D Test-Time Learners](https://arxiv.org/abs/2211.11432) ICCV'23

#### Information Entropy

* [Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation](http://proceedings.mlr.press/v119/liang20a.html) ICML'20 [\[Code\]](https://github.com/tim-learn/SHOT) ⭐ 497 | 🐛 4 | 🌐 Python | 📅 2024-02-22
* [Tent: Fully Test-Time Adaptation by Entropy Minimization](https://openreview.net/forum?id=uXl3bZLkr3c) ICLR'21 [\[Code\]](https://github.com/DequanWang/tent) ⚠️ Archived
* [Towards Stable Test-time Adaptation in Dynamic Wild World](https://openreview.net/forum?id=g2YraF75Tj) ICLR'23 [\[Code\]](https://github.com/mr-eggplant/SAR) ⭐ 212 | 🐛 1 | 🌐 Python | 📅 2023-09-08
* [Efficient Test-Time Model Adaptation without Forgetting](https://arxiv.org/abs/2204.02610) ICML'22 [\[Code\]](https://github.com/mr-eggplant/EATA) ⭐ 143 | 🐛 1 | 🌐 Python | 📅 2023-05-19
* [Uncertainty Reduction for Model Adaptation in Semantic Segmentation](https://openaccess.thecvf.com/content/CVPR2021/html/S_Uncertainty_Reduction_for_Model_Adaptation_in_Semantic_Segmentation_CVPR_2021_paper.html) CVPR'21 [\[Code\]](https://github.com/idiap/model-uncertainty-for-adaptation) ⭐ 52 | 🐛 1 | 🌐 Python | 📅 2022-09-12
* [Confidence Score for Source-Free Unsupervised Domain Adaptation](https://arxiv.org/abs/2206.06640) ICML'22 [\[Code\]](https://github.com/Jhyun17/CoWA-JMDS) ⭐ 26 | 🐛 0 | 🌐 Python | 📅 2023-02-03
* [Bayesian Adaptation for Covariate Shift](https://openreview.net/forum?id=15HPeY8MGQ) NeurIPS'21

#### Batch Normalization

* [Tent: Fully Test-Time Adaptation by Entropy Minimization](https://openreview.net/forum?id=uXl3bZLkr3c) ICLR'21 [\[Code\]](https://github.com/DequanWang/tent) ⚠️ Archived
* [Towards Stable Test-time Adaptation in Dynamic Wild World](https://openreview.net/forum?id=g2YraF75Tj) ICLR'23 [\[Code\]](https://github.com/mr-eggplant/SAR) ⭐ 212 | 🐛 1 | 🌐 Python | 📅 2023-09-08
* [Improving robustness against common corruptions by covariate shift adaptation](https://proceedings.neurips.cc/paper/2020/file/85690f81aadc1749175c187784afc9ee-Paper.pdf) NeurIPS'20 [\[Code\]](https://github.com/bethgelab/robustness) ⭐ 139 | 🐛 2 | 🌐 Python | 📅 2023-07-05
* [Limitations of Post-Hoc Feature Alignment for Robustness
  ](https://openaccess.thecvf.com/content/CVPR2021/html/Burns_Limitations_of_Post-Hoc_Feature_Alignment_for_Robustness_CVPR_2021_paper.html) CVPR'21 [\[Code\]](https://github.com/collin-burns/feature-alignment) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2021-03-11
* [TTN: A Domain-Shift Aware Batch Normalization in Test-Time Adaptation](https://openreview.net/forum?id=EQfeudmWLQ) ICLR'23
* [Delta: Degradation-Free Fully Test-Time Adaptation](https://openreview.net/forum?id=eGm22rqG93) ICLR'23
* [Test-time Adaptation in the Dynamic World with Compound Domain Knowledge Management](https://arxiv.org/abs/2212.08356) RA-L'23

#### Pseudo Labeling

* [Do We Really Need to Access the Source Data? Source Hypothesis Transfer for Unsupervised Domain Adaptation](http://proceedings.mlr.press/v119/liang20a.html) ICML'20 [\[Code\]](https://github.com/tim-learn/SHOT) ⭐ 497 | 🐛 4 | 🌐 Python | 📅 2024-02-22
* [Continual Test-Time Domain Adaptation](https://arxiv.org/abs/2203.13591) CVPR'22 [\[Code\]](https://github.com/qinenergy/cotta) ⭐ 326 | 🐛 3 | 🌐 Python | 📅 2024-06-17
* [Adapting ImageNet-scale models to complex distribution shifts with self-learning](https://arxiv.org/abs/2104.12928) TMLR'22 [\[Code\]](https://github.com/bethgelab/robustness) ⭐ 139 | 🐛 2 | 🌐 Python | 📅 2023-07-05
* [Contrastive Test-Time Adaptation](https://openaccess.thecvf.com/content/CVPR2022/papers/Chen_Contrastive_Test-Time_Adaptation_CVPR_2022_paper.pdf) CVPR'22 [\[Code\]](https://github.com/DianCh/AdaContrast) ⭐ 106 | 🐛 4 | 🌐 Python | 📅 2022-04-29
* [Uncertainty Reduction for Model Adaptation in Semantic Segmentation](https://openaccess.thecvf.com/content/CVPR2021/html/S_Uncertainty_Reduction_for_Model_Adaptation_in_Semantic_Segmentation_CVPR_2021_paper.html) CVPR'21 [\[Code\]](https://github.com/idiap/model-uncertainty-for-adaptation) ⭐ 52 | 🐛 1 | 🌐 Python | 📅 2022-09-12
* [Test-Time Adaptation via Conjugate Pseudo-labels](https://openreview.net/forum?id=2yvUYc-YNUH) NeurIPS'22 [\[Code\]](https://github.com/locuslab/tta_conjugate) ⭐ 42 | 🐛 1 | 🌐 Python | 📅 2023-05-25
* [TeSLA: Test-Time Self-Learning With Automatic Adversarial Augmentation](https://arxiv.org/abs/2303.09870) CVPR'23 [\[Code\]](https://github.com/devavratTomar/TeSLA) ⭐ 24 | 🐛 3 | 🌐 Python | 📅 2023-04-01
* [Generative Pseudo-label Refinement for Unsupervised Domain Adaptation](https://www.computer.org/csdl/proceedings-article/wacv/2020/09093579/1jPbrqho82k) WACV'20
* [A Free Lunch for Unsupervised Domain Adaptive Object Detection without Source Data](https://ojs.aaai.org/index.php/AAAI/article/view/17029) AAAI'21
* [Towards Understanding GD with Hard and Conjugate Pseudo-labels for Test-Time Adaptation](https://openreview.net/forum?id=FJXf1FXN8C) ICLR'23

#### Class Prototype

* [Test-Time Classifier Adjustment Module for Model-Agnostic Domain Generalization](https://proceedings.neurips.cc/paper/2021/hash/1415fe9fea0fa1e45dddcff5682239a0-Abstract.html) NeurIPS'21 [\[Code\]](https://github.com/matsuolab/T3A) ⭐ 108 | 🐛 5 | 🌐 Python | 📅 2021-12-02
* [Attracting and Dispersing: A Simple Approach for Source-free Domain Adaptation](https://openreview.net/forum?id=ZlCpRiZN7n) NeurIPS'22 [\[Code\]](https://github.com/Albert0147/AaD_SFDA) ⭐ 74 | 🐛 4 | 🌐 Python | 📅 2024-12-11
* [Revisiting Realistic Test-Time Training: Sequential Inference and Adaptation by Anchored Clustering](https://openreview.net/forum?id=W-_4hgRkwb) NeurIPS'22 [\[Code\]](https://github.com/Gorilla-Lab-SCUT/TTAC) ⭐ 49 | 🐛 0 | 🌐 Python | 📅 2023-10-06
* [On the Robustness of Open-World Test-Time Training: Self-Training with Dynamic Prototype Expansion](https://arxiv.org/abs/2308.09942) ICCV'23  [\[Code\]](https://github.com/Yushu-Li/OWTTT) ⭐ 46 | 🐛 0 | 🌐 Python | 📅 2024-12-18
* [Model Adaptation: Unsupervised Domain Adaptation Without Source Data](https://openaccess.thecvf.com/content_CVPR_2020/html/Li_Model_Adaptation_Unsupervised_Domain_Adaptation_Without_Source_Data_CVPR_2020_paper.html) CVPR'20

#### Feature Alignment

* [TTT++: When Does Self-Supervised Test-Time Training Fail or Thrive?](https://proceedings.neurips.cc/paper/2021/hash/b618c3210e934362ac261db280128c22-Abstract.html) NeurIPS'21 [\[Code\]](https://github.com/vita-epfl/ttt-plus-plus) ⭐ 75 | 🐛 5 | 🌐 Python | 📅 2022-02-14
* [Feature Alignment and Uniformity for Test Time Adaptation
  ](https://openaccess.thecvf.com/content/CVPR2023/html/Wang_Feature_Alignment_and_Uniformity_for_Test_Time_Adaptation_CVPR_2023_paper.html) CVPR'23 [\[Code\]](https://github.com/SakurajimaMaiii/TSD) ⭐ 49 | 🐛 2 | 🌐 Python | 📅 2025-11-23
* [ActMAD: Activation Matching to Align Distributions for Test-Time-Training](https://arxiv.org/abs/2211.12870) CVPR'23 [\[Code\]](https://github.com/jmiemirza/actmad) ⭐ 21 | 🐛 2 | 🌐 Python | 📅 2023-06-27
* [Source-Free Adaptation to Measurement Shift via Bottom-Up Feature Restoration](https://openreview.net/forum?id=1JDiK_TbV4S) ICLR'22 [\[Code\]](https://github.com/cianeastwood/bufr) ⭐ 16 | 🐛 0 | 🌐 Python | 📅 2022-08-30
* [SoFA: Source-data-free Feature Alignment for Unsupervised Domain Adaptation](https://openaccess.thecvf.com/content/WACV2021/papers/Yeh_SoFA_Source-Data-Free_Feature_Alignment_for_Unsupervised_Domain_Adaptation_WACV_2021_paper.pdf) WACV'21
* [Adaptive Adversarial Network for Source-Free Domain Adaptation](https://openaccess.thecvf.com/content/ICCV2021/html/Xia_Adaptive_Adversarial_Network_for_Source-Free_Domain_Adaptation_ICCV_2021_paper.html) ICCV'21
* [Invariance Through Latent Alignment](https://openreview.net/forum?id=vXGcHthY6v) RSS'22 [\[Project\]](https://invariance-through-latent-alignment.github.io/)
* [Source-Free Domain Adaptation via Distribution Estimation](https://openaccess.thecvf.com/content/CVPR2022/papers/Ding_Source-Free_Domain_Adaptation_via_Distribution_Estimation_CVPR_2022_paper.pdf) CVPR'22
* [Robustness to corruption in pre-trained Bayesian neural networks](https://openreview.net/forum?id=kUI41mY8bHl) ICLR'23

#### Generative Modeling

* [Back to the Source: Diffusion-Driven Test-Time Adaptation](https://arxiv.org/abs/2207.03442) CVPR'23 [\[Code\]](https://github.com/shiyegao/DDA) ⭐ 87 | 🐛 0 | 🌐 Python | 📅 2023-11-27
* [Model Adaptation: Unsupervised Domain Adaptation without Source Data](https://openaccess.thecvf.com/content_CVPR_2020/html/Li_Model_Adaptation_Unsupervised_Domain_Adaptation_Without_Source_Data_CVPR_2020_paper.html) CVPR'20
* [Domain Impression: A Source Data Free Domain Adaptation Method](https://openaccess.thecvf.com/content/WACV2021/papers/Kurmi_Domain_Impression_A_Source_Data_Free_Domain_Adaptation_Method_WACV_2021_paper.pdf) WACV'21

#### Nearest Neighbors

* [Generalized Source-free Domain Adaptation](https://openaccess.thecvf.com/content/ICCV2021/papers/Yang_Generalized_Source-Free_Domain_Adaptation_ICCV_2021_paper.pdf) ICCV'21 [\[Code\]](https://github.com/Albert0147/G-SFDA) ⭐ 110 | 🐛 1 | 🌐 Python | 📅 2022-03-29
* [Exploiting the Intrinsic Neighborhood Structure for Source-free Domain Adaptation](https://proceedings.neurips.cc/paper/2021/hash/f5deaeeae1538fb6c45901d524ee2f98-Abstract.html) NeurIPS'21 [\[Code\]](https://github.com/Albert0147/NRC_SFDA) ⭐ 81 | 🐛 1 | 🌐 Python | 📅 2022-12-11
* [Test-Time Adaptation via Self-Training with Nearest Neighbor Information](https://openreview.net/forum?id=EzLtB4M1SbM) ICLR'23 [\[Code\]](https://github.com/mingukjang/TAST) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2023-07-11

#### Augmentation Invariance

* [MEMO: Test Time Robustness via Adaptation and Augmentation](https://openreview.net/forum?id=vn74m_tWu8O) NeurIPS'22 [\[Code\]](https://github.com/zhangmarvin/memo) ⭐ 74 | 🐛 4 | 🌐 Python | 📅 2023-06-27
* [Test time Adaptation through Perturbation Robustness](https://openreview.net/forum?id=GbBeI5z86uD) NeurIPS-WS'21
* [Balancing Discriminability and Transferability for Source-Free Domain Adaptation](https://arxiv.org/abs/2206.08009?context=cs.LG) ICML'22 [\[Project\]](https://sites.google.com/view/mixup-sfda)

#### Meta-learning

* [Meta-DMoE: Adapting to Domain Shift by Meta-Distillation from Mixture-of-Experts](https://openreview.net/forum?id=_ekGcr07Dsp) NeurIPS'22 [\[Code\]](https://github.com/n3il666/Meta-DMoE) ⭐ 44 | 🐛 0 | 🌐 Python | 📅 2023-03-17
* [Learning to Generalize across Domains on Single Test Samples](https://openreview.net/forum?id=CIaQKbTBwtU) ICLR'22 [\[Code\]](https://github.com/zzzx1224/SingleSampleGeneralization-ICLR2022) ⭐ 23 | 🐛 1 | 🌐 Python | 📅 2022-02-08
* [Test-Time Fast Adaptation for Dynamic Scene Deblurring via Meta-Auxiliary Learning](https://openaccess.thecvf.com/content/CVPR2021/html/Chi_Test-Time_Fast_Adaptation_for_Dynamic_Scene_Deblurring_via_Meta-Auxiliary_Learning_CVPR_2021_paper.html) CVPR'21
* [Adaptive Risk Minimization: Learning to Adapt to Domain Shift](https://proceedings.neurips.cc/paper/2021/hash/c705112d1ec18b97acac7e2d63973424-Abstract.html) NeurIPS'21 [\[Code\]](https://sites.google.com/view/adaptive-risk-minimization)

#### Time-varying

* [Continual Test-Time Domain Adaptation](https://arxiv.org/abs/2203.13591) CVPR'22 [\[Code\]](https://github.com/qinenergy/cotta) ⭐ 326 | 🐛 3 | 🌐 Python | 📅 2024-06-17
* [Robust Mean Teacher for Continual and Gradual Test-Time Adaptation](https://arxiv.org/abs/2211.13081) CVPR'23 [\[Code\]](https://github.com/mariodoebler/test-time-adaptation) ⭐ 287 | 🐛 0 | 🌐 Python | 📅 2025-05-29
* [Robust Test-Time Adaptation in Dynamic Scenarios](https://arxiv.org/abs/2303.13899) CVPR'23 [\[Code\]](https://github.com/BIT-DA/RoTTA) ⭐ 71 | 🐛 0 | 🌐 Python | 📅 2023-07-11
* [NOTE: Robust Continual Test-time Adaptation Against Temporal Correlation](https://openreview.net/forum?id=E9HNxrCFZPV) NeurIPS'22 [\[Code\]](https://github.com/TaesikGong/NOTE) ⭐ 50 | 🐛 0 | 🌐 Python | 📅 2023-12-21
* [A Probabilistic Framework for Lifelong Test-Time Adaptation](https://arxiv.org/abs/2212.09713) CVPR'23 [\[Code\]](https://github.com/dhanajitb/petal) ⭐ 13 | 🐛 1 | 🌐 Python | 📅 2023-09-08
* [Extrapolative Continuous-time Bayesian Neural Network for Fast Training-free Test-time Adaptation](https://openreview.net/forum?id=wiHzQWwg3l) NeurIPS'22 [\[Code\]](https://github.com/guxm2021/ECBNN) ⭐ 10 | 🐛 0 | 🌐 Python | 📅 2022-12-02
* [Decorate the Newcomers: Visual Domain Prompt for Continual Test Time Adaptation](https://arxiv.org/pdf/2212.04145.pdf) AAAI'23
* [EcoTTA: Memory-Efficient Continual Test-time Adaptation via Self-distilled Regularization](https://arxiv.org/abs/2303.01904) CVPR'23 [\[Project\]](https://sites.google.com/view/junha/ecotta)

#### Others

* [Parameter-free Online Test-time Adaptation](https://arxiv.org/abs/2201.05718) CVPR'22 [\[Code\]](https://github.com/fiveai/LAME) ⭐ 77 | 🐛 3 | 🌐 Python | 📅 2022-06-21
* [Collaborative Sampling in Generative Adversarial Networks](https://arxiv.org/pdf/1902.00813.pdf) AAAI'20 [\[Code\]](https://github.com/vita-epfl/collaborative-gan-sampling) ⭐ 24 | 🐛 0 | 🌐 Python | 📅 2020-06-25
* [Adaptive Methods for Real-World Domain Generalization](https://openaccess.thecvf.com/content/CVPR2021/papers/Dubey_Adaptive_Methods_for_Real-World_Domain_Generalization_CVPR_2021_paper.pdf) CVPR'21 [\[Code\]](https://github.com/abhimanyudubey/PrototypicalDomainGeneralization) ⭐ 8 | 🐛 0 | 🌐 Python | 📅 2021-06-16
* [Domain Adaptation in the Absence of Source Domain Data](https://www.kdd.org/kdd2016/papers/files/adp0290-chidlovskiiA.pdf) KDD'16
* [Semantic Photo Manipulation with a Generative Image Prior](https://arxiv.org/pdf/2005.07727.pdf) SIGGRAPH'19
* [Universal Source-Free Domain Adaptation](https://openaccess.thecvf.com/content_CVPR_2020/papers/Kundu_Universal_Source-Free_Domain_Adaptation_CVPR_2020_paper.pdf) CVPR'20 [\[Project\]](https://sites.google.com/view/usfda-cvpr2020)
* [Evaluating the Adversarial Robustness of Adaptive Test-time Defenses](https://proceedings.mlr.press/v162/croce22a/croce22a.pdf) ICML'22
* [MECTA: Memory-Economic Continual Test-Time Model Adaptation](https://openreview.net/forum?id=N92hjSf5NNh) ICLR'23
* [Neuro-Modulated Hebbian Learning for Fully Test-Time Adaptation](https://arxiv.org/abs/2303.00914) CVPR'23

### Benchmark

* [On Pitfalls of Test-Time Adaptation](https://arxiv.org/pdf/2306.03536.pdf) ICML'2023 [\[Code\]](https://github.com/LINs-lab/ttab) ⭐ 128 | 🐛 1 | 🌐 Python | 📅 2024-04-06

### Applications

* [Towards Robust and Adaptive Motion Forecasting: A Causal Representation Perspective](https://arxiv.org/abs/2111.14820) CVPR'22 [\[Code\]](https://github.com/vita-epfl/causalmotion) ⭐ 75 | 🐛 0 | 🌐 Python | 📅 2022-07-20
* [Source-Free Object Detection by Learning to Overlook Domain Style](https://openaccess.thecvf.com/content/CVPR2022/html/Li_Source-Free_Object_Detection_by_Learning_To_Overlook_Domain_Style_CVPR_2022_paper.html) CVPR'22 [\[Code\]](https://github.com/Flashkong/Source-Free-Object-Detection-by-Learning-to-Overlook-Domain-Style) ⭐ 54 | 🐛 8 | 🌐 Python | 📅 2023-05-12
* [Source-Free Domain Adaptation for Image Segmentation](https://arxiv.org/pdf/2108.03152.pdf) MICCAI'20 [\[Code\]](https://github.com/mathilde-b/SFDA) ⭐ 46 | 🐛 2 | 🌐 Python | 📅 2023-04-27
* [Test-Time Personalization with a Transformer for Human Pose Estimation](https://proceedings.neurips.cc/paper/2021/file/1517c8664be296f0d87d9e5fc54fdd60-Paper.pdf) NeurIPS'21 [\[Code\]](https://github.com/harry11162/TTP) ⭐ 45 | 🐛 0 | 🌐 Cuda | 📅 2021-10-23
* [Source-free Video Domain Adaptation by Learning Temporal Consistency for Action Recognition](https://arxiv.org/abs/2203.04559) ECCV'22 [\[Code\]](https://github.com/xuyu0010/ATCoN) ⭐ 24 | 🐛 1 | 🌐 Python | 📅 2023-03-09
* [SfM-TTR: Using Structure from Motion for Test-Time Refinement of Single-View Depth Networks](https://arxiv.org/abs/2211.13551) CVPR'23 [\[Code\]](https://github.com/serizba/SfM-TTR) ⭐ 23 | 🐛 3 | 🌐 Python | 📅 2022-11-18
* [Test-Time Training Can Close the Natural Distribution Shift Performance Gap in Deep Learning Based Compressed Sensing](https://proceedings.mlr.press/v162/darestani22a/darestani22a.pdf) ICML'22 [\[Code\]](https://github.com/MLI-lab/ttt_for_deep_learning_cs) ⭐ 17 | 🐛 0 | 🌐 Jupyter Notebook | 📅 2022-04-27
* [The Dual Form of Neural Networks Revisited: Connecting Test Time Predictions to Training Patterns via Spotlights of Attention
  ](https://proceedings.mlr.press/v162/irie22a/irie22a.pdf) ICML'22 [\[Code\]](https://github.com/robertcsordas/linear_layer_as_attention) ⭐ 16 | 🐛 2 | 🌐 Python | 📅 2025-06-11
* [Ev-TTA: Test-Time Adaptation for Event-Based Object Recognition](https://arxiv.org/abs/2203.12247) CVPR'22 [\[Code\]](https://github.com/82magnolia/ev_tta) ⭐ 9 | 🐛 0 | 🌐 Python | 📅 2024-02-26
* [Consistent Video Depth Estimation](https://arxiv.org/pdf/2004.15021.pdf) SIGGRAPH'2020 [\[Project\]](https://roxanneluo.github.io/Consistent-Video-Depth-Estimation/)
* [Self-Supervised Policy Adaptation during Deployment](https://openreview.net/forum?id=o_V-MjyyGV_) ICLR'21 [\[Project\]](https://nicklashansen.github.io/PAD/)
* [Fully Test-Time Adaptation for Image Segmentation](https://link.springer.com/chapter/10.1007/978-3-030-87199-4_24) MICCAI'21
* [Adapting Off-the-Shelf Source Segmenter for Target Medical Image Segmentation](https://arxiv.org/pdf/2106.12497.pdf) MICCAI'21
* [Source-Free Domain Adaptation for Semantic Segmentation](https://openaccess.thecvf.com/content/CVPR2021/html/Liu_Source-Free_Domain_Adaptation_for_Semantic_Segmentation_CVPR_2021_paper.html) CVPR'21
* [Generalize Then Adapt: Source-Free Domain Adaptive Semantic Segmentation
  ](https://openaccess.thecvf.com/content/ICCV2021/html/Kundu_Generalize_Then_Adapt_Source-Free_Domain_Adaptive_Semantic_Segmentation_ICCV_2021_paper.html) ICCV'21 [\[Project\]](https://sites.google.com/view/sfdaseg)
* [SS-SFDA: Self-Supervised Source-Free Domain Adaptation for Road Segmentation in Hazardous Environments](https://openaccess.thecvf.com/content/WACV2021/papers/Yeh_SoFA_Source-Data-Free_Feature_Alignment_for_Unsupervised_Domain_Adaptation_WACV_2021_paper.pdf) ICCV'21 [\[Project\]](https://gamma.umd.edu/researchdirections/autonomousdriving/weathersafe/)
* [MM-TTA: Multi-Modal Test-Time Adaptation for 3D Semantic Segmentation](https://arxiv.org/abs/2204.12667) CVPR'22 [\[Project\]](https://www.nec-labs.com/~mas/MM-TTA/)
* [On the Road to Online Adaptation for Semantic Image Segmentation](https://openaccess.thecvf.com/content/CVPR2022/papers/Volpi_On_the_Road_to_Online_Adaptation_for_Semantic_Image_Segmentation_CVPR_2022_paper.pdf) CVPR'22
* [AuxAdapt: Stable and Efficient Test-Time Adaptation for Temporally Consistent Video Semantic Segmentation](https://openaccess.thecvf.com/content/WACV2022/papers/Zhang_AuxAdapt_Stable_and_Efficient_Test-Time_Adaptation_for_Temporally_Consistent_Video_WACV_2022_paper.pdf) WACV'22
* [Test-Time Prompt Tuning for Zero-Shot Generalization in Vision-Language Models](https://openreview.net/forum?id=e8PVEkSa4Fq) NeurIPS'22 [\[Project\]](https://azshue.github.io/TPT/)
* [TTA-COPE: Test-Time Adaptation for Category-Level Object Pose Estimation](https://arxiv.org/abs/2303.16730) CVPR'23 [\[Project\]](https://sites.google.com/view/taeyeop-lee/ttacope)
* [Video Test-Time Adaptation for Action Recognition](https://arxiv.org/abs/2211.15393) CVPR'23 [\[Project\]](https://wlin-at.github.io/vitta)

***

> _Enhansomed by [enhansome](https://github.com/enhansome) on 2026-08-28._
