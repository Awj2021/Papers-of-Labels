# Papers-of-Labels
Recording several papers about the labels appeared in the top-tier conferences, like NIPS, ICCV, CVPR, etc.

## Learning with Noisy Labels
### Diffusion Based Method

1. Label-Retrieval-Augmented Diffusion Models for Learning from Noisy Labels | **NeurIPS2023** | [paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/d191ba4c8923ed8fd8935b7c98658b5f-Paper-Conference.pdf)

## Corrupted Labels Detection
1. Detecting Corrupted Labels without Training a Model to Predict | **ICML2022** | [paper](https://proceedings.mlr.press/v162/zhu22a/zhu22a.pdf)
2. LEMoN: Label Error Detection using MultiModal Neighbors
3. Understanding and Mitigating the Bias in Sample Selection for Learning with Noisy Labels | [paper](https://arxiv.org/pdf/2401.13360)

## Label-Noise and Long-tailed Data
1. Boosting Class Representation via Semantically Related Instances for Robust Long-Tailed Learning with Noisy Labels | **ICCV2025** | [paper](https://openaccess.thecvf.com/content/ICCV2025/papers/Li_Boosting_Class_Representation_via_Semantically_Related_Instances_for_Robust_Long-Tailed_ICCV_2025_paper.pdf) | [code](https://github.com/yhli-ml/IBC)
2. Unlocker: Disentangle the Deadlock of Learning from Label-noisy and Long-tailed Data | [paper](https://openreview.net/pdf?id=jTCiQpV0Lx)
3. When Noisy Labels Meet Long Tail Dilemmas: A Representation Calibration Method | **ICCV2023** | [paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Zhang_When_Noisy_Labels_Meet_Long_Tail_Dilemmas_A_Representation_Calibration_ICCV_2023_paper.pdf)
4. Label-Noise Learning with Intrinsically Long-Tailed Data | **ICCV2023** | [paper](https://openaccess.thecvf.com/content/ICCV2023/papers/Lu_Label-Noise_Learning_with_Intrinsically_Long-Tailed_Data_ICCV_2023_paper.pdf)

## Long-tailed Learning
1. Retrieval Augmented Classification for Long-Tail Visual Recognition | **CVPR2022** | [paper](https://openaccess.thecvf.com/content/CVPR2022/papers/Long_Retrieval_Augmented_Classification_for_Long-Tail_Visual_Recognition_CVPR_2022_paper.pdf)
2. Keep It on a Leash: Controllable Pseudo-label Generation Towards Realistic Long-Tailed Semi-Supervised Learning | **NIPS2025** | [paper]() | **[code](https://github.com/yaxinhou/CPG)**

## Noisy Partial Label Learning (NPLL)
Terminology words:
candidate label set (CLS)
1. Noise Separation guided Candidate Label Reconstruction for Noisy Partial Label Learning | **ICLR 2025** | [paper](https://openreview.net/pdf?id=TOahfjA3sP) | **[code](https://github.com/pruirui/PLRC)** 

Keys: 1) partion samples into three parts: highly reliable normal samples, highly reliable noisy samples, and uncertain samples. 2) reconstruct the CLS for each instance -- reducing its size and containing ground-truth label. 

**Note**: This paper inspires me a lot, please read it carefully. 

## Partial Label Learning 
1. Confidence-Aware With Prototype Alignment for Partial Multi-label Learning | **ICLR2025** | [paper](https://openreview.net/forum?id=Hp78SvTU2N) | **[code]()**
2. Reduction-based Pseudo-label Generation for
Instance-dependent Partial Label Learning | **NIPS2025** | [paper](https://openreview.net/pdf?id=0THi1tG1HY) | **[code]()**
3. Rethinking Self-Distillation: Label Averaging and Enhanced Soft Label Refinement with Partial Labels | **ICLR2025** | [paper](https://openreview.net/forum?id=EJfLvrzh2Q) | **[code]()**
4. Partial Information Decomposition via Normalizing Flows in Latent Gaussian Distributions | **NIPS2025** | [paper](https://openreview.net/forum?id=X13jOIhnog) | **[code]()** 

## Label Enhancement
1. Selective Label Enhancement Learning for Test-Time Adaptation | **ICLR2025** | [paper](https://openreview.net/pdf?id=3Z2flzXzBY) | **[code](https://github.com/palm-ml/PASLE)**

## Multi-Rater Learning

## Others maybe useful
1. SIMPLE YET EFFECTIVE INCOMPLETE MULTI-VIEWCLUSTERING: SIMILARITY-LEVEL IMPUTATION ANDINTRA-VIEW HYBRID-GROUP PROTOTYPE CONSTRUC-TION | **ICLR2025** | [paper](https://openreview.net/pdf?id=KijslFbfOL) | **[code]**
2. DROP-UPCYCLING: TRAINING SPARSE MIXTURE OFEXPERTS WITH PARTIAL RE-INITIALIZATION | **ICLR2025** | [paper](https://openreview.net/pdf?id=gx1wHnf5Vp) | **[code]**