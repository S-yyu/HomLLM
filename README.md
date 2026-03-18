# HomLLM
HomLLM: Exploiting Semantic Homology Relationship for Fine-Grained Bird Image Classification via Large Language Models



## 📑 Abstract

How to recognize endangered bird species in complex outdoor environments has attracted considerable attention in the fields of computer vision and machine learning. However, fine-grained bird image classification (FBIC) is susceptible to problems such as arbitrary postures, interclass discriminability, and occlusions. We propose a novel semantic homology relationship representation learning for fine-grained bird classification with large language models, namely HomLLM, to address these challenges in FBIC effectively. Our proposed model aims to learn homology relationship representations adaptively by identifying invariant structural correspondences between visual features and semantic descriptions, using limited bird data and base class labels. Our approach yields two key findings: 1) invariant homology in key regions of birds that maintain structural consistency across different postures and 2) homological relationships that establish essential taxonomic markers among similar bird classes. Based on these insights, we propose two new modules of the model: the semantic homology generation (SHG) module and homology relationship mining (HRM) module. Specifically, in SHG, bird features are described at multiple granularities through a large language model (LLM) to establish semantic homology. In HRM, feature adaptation is performed separately for textual and visual information, and cross-modal homological interaction is performed hierarchically. In addition, we propose a hierarchical homology interaction scheme to integrate multilevel homological features while preserving structural consistency. Experiments on the commonly used bird datasets CUB-200-2011 and NABirds demonstrate that HomLLM exhibits better performance than state-of-the-art (SOTA) methods.


<img width="743" height="463" alt="image" src="https://github.com/user-attachments/assets/5671f69a-7075-4899-a3df-2cf527fc62e5" />

## 🌟 Key Contributions

1）A novel semantic homology relationship representation learning for fine-grained bird classification, which utilizes a LLM to establish invariant structural correspondences between visual features and semantic descriptions, directing the visual model to focus on homologically consistent features across different viewing conditions and improving classification accuracy.

2）Two homology relationship-based modules are designed: SHG module that generates visual descriptions aligned with biological homologies from coarse to fine; and the HRM module that optimizes textual representations and integrates them with visual features through homological correspondence. These modules work with the hierarchical homology interaction scheme to synthesize multilevel homological features.

3）Comprehensive experiments are conducted on two FBIC-related datasets, namely, CUB-200-2011 and NABirds. Our proposed HomLLM demonstrates superior results over existing state-of-the-art (SOTA) methods, validating the effectiveness of incorporating language prompts for accurate bird classification.

## 📊 Datasets

Comparative experiments were conducted on two widely used fine-grained classification datasets, NABirds and CUB-200-2011. All datasets followed the official training/test splits, and all images were uniformly resized to a resolution of 224×224.

## Citation
```bibtex

@ARTICLE{11219338,
  author={Liu, Hai and Song, Yu and Liu, Tingting and Zheng, Hao and Chen, Lin and Zhang, Zhaoli and Li, You-Fu},
  journal={IEEE Transactions on Neural Networks and Learning Systems}, 
  title={HomLLM: Exploiting Semantic Homology Relationship for Fine-Grained Bird Image Classification via Large Language Models}, 
  year={2026},
  volume={37},
  number={3},
  pages={1221-1235},
  keywords={Birds;Visualization;Semantics;Head;Convolutional neural networks;Beak;Accuracy;Large language models;Image classification;Feature extraction;Classification;homology relationship;image understanding;large language models (LLMs)},
  doi={10.1109/TNNLS.2025.3617339}}

H. Liu, Y. Song, T. Liu, H. Zheng, L. Chen, Z. Zhang, and Y.-F. Li, “HomLLM: Exploiting Semantic Homology Relationship for Fine-Grained Bird Image Classification via Large Language Models,” IEEE Transactions on Neural Networks and Learning Systems, vol. 37, no. 3, pp. 1221 - 1235, 2026.
