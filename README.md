# Papers-of-Labels
Recording several papers about the labels appeared in the top-tier conferences, like NIPS, ICCV, CVPR, etc.

## My Own Ideas
Prototype features   
Semantic Featrues 

## Learning with Noisy Labels
### Diffusion Based Method

1. Label-Retrieval-Augmented Diffusion Models for Learning from Noisy Labels | **NeurIPS2023** | [paper](https://proceedings.neurips.cc/paper_files/paper/2023/file/d191ba4c8923ed8fd8935b7c98658b5f-Paper-Conference.pdf)

### Label Noise Methods

1. Regretful Decisions under Label Noise | **ICLR2025** | [paper](https://openreview.net/pdf?id=7B9FCDoUzB)
2. For Better or For Worse? Learning Minimum Variance Features With Label Augmentation | **ICLR2025** | [paper](https://openreview.net/pdf?id=LCL8SMGxDY)
3. SELC: Self-Ensemble Label Correction Improves Learning with Noisy Labels | **IJCAI2022** | [paper](https://www.ijcai.org/proceedings/2022/0455.pdf) | [**code**](https://github.com/MacLLL/SELC) | **Note**: this paper utilize the Ensemble Prediction (given labels + model's prediction) to improve the model's performance. 

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
2. Keep It on a Leash: Controllable Pseudo-label Generation Towards Realistic Long-Tailed Semi-Supervised Learning | **NIPS2025** | **[code](https://github.com/yaxinhou/CPG)**
3. Rethinking Classifier Re-Training in Long-Tailed Recognition: Label Over-Smooth Can Balance | **ICLR2025** | [paper](https://openreview.net/pdf?id=OeKp3AdiVO)

## Noisy Partial Label Learning (NPLL)
Terminology words:
candidate label set (CLS)
1. Noise Separation guided Candidate Label Reconstruction for Noisy Partial Label Learning | **ICLR 2025** | [paper](https://openreview.net/pdf?id=TOahfjA3sP) | **[code](https://github.com/pruirui/PLRC)** 

Keys: 1) partion samples into three parts: highly reliable normal samples, highly reliable noisy samples, and uncertain samples. 2) reconstruct the CLS for each instance -- reducing its size and containing ground-truth label. 

**Note**: This paper inspires me a lot, please read it carefully. 

2. Bridging weakly-supervised learning and VLM distialltion: Noisy Partial Label learning for effecient Downstream adaptation | **TCSVT** | [paper](https://arxiv.org/pdf/2506.03229) | **[code]()** 

**There are another several papers about this field, so we could read and try to utilize them in the Multi-rater learning**

## Partial Label Learning
1. Confidence-Aware With Prototype Alignment for Partial Multi-label Learning | **ICLR2025** | [paper](https://openreview.net/forum?id=Hp78SvTU2N) | **[code]()**
2. Reduction-based Pseudo-label Generation for
Instance-dependent Partial Label Learning | **NIPS2025** | [paper](https://openreview.net/pdf?id=0THi1tG1HY) | **[code]()**
3. Rethinking Self-Distillation: Label Averaging and Enhanced Soft Label Refinement with Partial Labels | **ICLR2025** | [paper](https://openreview.net/forum?id=EJfLvrzh2Q) | **[code](https://github.com/Hyeonsu-Jeong/SelfPLL/tree/master)**
4. Partial Information Decomposition via Normalizing Flows in Latent Gaussian Distributions | **NIPS2025** | [paper](https://openreview.net/forum?id=X13jOIhnog) | **[code]()**
5. Realistic Evaluation of Deep Partial-Label Learning Algorithms | **ICLR2025 Spotlight** | [paper](https://openreview.net/pdf?id=FtX6oAW7Dd) 

## Label Enhancement
1. Selective Label Enhancement Learning for Test-Time Adaptation | **ICLR2025** | [paper](https://openreview.net/pdf?id=3Z2flzXzBY) | **[code](https://github.com/palm-ml/PASLE)**

## Multi-Rater Learning

## Active Learning and Coreset Selection
1. Uncertainty Herding: One Active Learning Method for All Label Budgets | **ICLR2025** | [paper](https://openreview.net/pdf?id=UgPoHhYQ2U)
2. ELFS: Label-Free Coreset Selection with Proxy Training Dynamics | **ICLR2025** | [paper](https://openreview.net/pdf?id=yklJpvB7Dq)
3. Coreset Selection via Reducible Loss in Continual Learning | **ICLR2025** | [paper](https://openreview.net/pdf?id=mAztx8QO3B)

## Label Refinement and RLHF
1. Sail into the Headwind: Alignment via Robust Rewards and Dynamic Labels against Reward Hacking | **ICLR2025** | [paper](https://openreview.net/pdf?id=I8af9JdQTy)
2. Iterative Label Refinement Matters More than Preference Optimization under Weak Supervision | **ICLR2025 Spotlight** | [paper](https://openreview.net/pdf?id=q5EZ7gKcnW)

## Prototype Learning
1. Learn hybrid prototypes for multivariate time series anomaly detection | **ICLR2025** | [paper](https://openreview.net/pdf?id=8TBGdH3t6a)
2. What Do You See in Common? Learning Hierarchical Prototypes over Tree-of-Life to Discover Evolutionary Traits | **ICLR2025** | [paper](https://openreview.net/pdf?id=4sDicVEy6M)
3. Learning Clustering-based Prototypes for Compositional Zero-Shot Learning | **ICLR2025** | [paper](https://openreview.net/pdf?id=eE2PXlNydB)
4. High-dimension Prototype is a Better Incremental Object Detection Learner | **ICLR2025** | [paper](https://openreview.net/pdf?id=6T8czSBWce)

## Others maybe useful
1. SoftCVI: Contrastive variational inference with self-generated soft labels | **ICLR2025 Spotlight** | [paper](https://openreview.net/pdf?id=PiZtlzMWUj)
2. Can We Ignore Labels in Out of Distribution Detection? | **ICLR2025** | [paper](https://openreview.net/pdf?id=falBlwUsIH)
3. Dynamic Loss-Based Sample Reweighting for Improved Large Language Model Pretraining | **ICLR2025** | [paper](https://openreview.net/pdf?id=gU4ZgQNsOC)
4. Understanding Warmup-Stable-Decay Learning Rates: A River Valley Loss Landscape View | **ICLR2025** | [paper](https://openreview.net/pdf?id=m51BgoqvbP)
5. SIMPLE YET EFFECTIVE INCOMPLETE MULTI-VIEWCLUSTERING: SIMILARITY-LEVEL IMPUTATION ANDINTRA-VIEW HYBRID-GROUP PROTOTYPE CONSTRUC-TION | **ICLR2025** | [paper](https://openreview.net/pdf?id=KijslFbfOL) | **[code]**
6. DROP-UPCYCLING: TRAINING SPARSE MIXTURE OFEXPERTS WITH PARTIAL RE-INITIALIZATION | **ICLR2025** | [paper](https://openreview.net/pdf?id=gx1wHnf5Vp) | **[code]**


## Others
1. Forming Auxiliary High-confident Instance-level Loss to Promote Learning from Label Proportions | **CVPR2025** | [paper](https://openaccess.thecvf.com/content/CVPR2025/papers/Ma_Forming_Auxiliary_High-confident_Instance-level_Loss_to_Promote_Learning_from_Label_CVPR_2025_paper.pdf) 
**keypoint**: using bags of instances