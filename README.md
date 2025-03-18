# Concept_Literature_Review
| Paper | Proceedings / Journal | Venue Year / Last Updated | Code | Alternative PDF Source | Notes |
| ----- | --------------------- | ------------------------- | ---- | ---------------------- | ----- |
| Human-level concept learning through probabilistic program induction| Science | 2015 | Null | [Paper](https://www.cs.cmu.edu/~rsalakhu/papers/LakeEtAl2015Science.pdf) | - 1. **one-shot** **learning** people can learn a new concept from just one or a handful of examples while machine learning require tons of examples to perform similarly; 2. **Generalization** **capability** people learn richer representations than machines do. <br> - challenges: how can learning succeed from sparse data yet produce rich representations? <br> - Bayesian Program Learning (BPL) represents concepts as probabilistic programs
| **$\beta$-VAE**: Learning Basic Visual Concepts With a Constrained Variational Framework | ICLR | 2017 | Null | [OpenReview](https://openreview.net/pdf?id=Sy2fzU9gl) | - Google DeepMind <br> -  unsupervised interprete latent representations from image data (no need of a prior) <br> - modification of VAE (pros: scalability and training stability) <br> - introduce adjustable hyperparameter $\beta$ [balance latent channel capacity & indepedentce constraints w/ reconstruction accuracy] <br> -$\beta$-VAE outperform regular VAE and InfoGAN(unsupervised) and DC-IGN(semi-supervised) on [celebA, faces, chairs] dataset <br> - Concepts = Disentangled representations <br> - new measure of disentanglement <br> - with a higher $\beta$, posterior distribution $q_\phi(z,x)$ is forced to be close to prior distribution $p(z)$, a isotropic Gaussian dis., hence have the isotropic nature, thus disentangle latents. <br> - $\beta$ tradeoffs betweem reconstruction idelity and the quality of disentanglement. | 
| **ConceptNet** ConceptNet 5.5: An Open Multilingual Graph of General Knowledge | AAAI | 2017 | [Code](https://github.com/yewsiang/ConceptBottleneck) | [Arxiv](https://arxiv.org/abs/1612.03975) | - Knowledge graph for word embeddings (language semantic vectors) |
| Concept Bottleneck Models | ICML | 2020 | [Code](https://github.com/yilundu/comet) | [Arxiv](https://arxiv.org/abs/2007.04612) | |
|  **comet** Unsupervised Learning of Compositional Energy Concepts | NeurIPS | 2021 | [Code](https://github.com/commonsense/conceptnet-numberbatch) | [Arxiv](https://arxiv.org/abs/2111.03042) | - consider concepts as energy functions |
| Concept Learning for Interpretable Multi-Agent Reinforcement Learning | CoRL | 2022 | Null | [Arxiv](https://arxiv.org/abs/2302.12232) | |
| Interactive Disentanglement: Learning Concepts by Interacting with their Prototype Representations | CVPR | 2022 | [Code](https://github.com/ml-research/xiconceptlearning) | [Arxiv](https://arxiv.org/abs/2112.02290) | - weak supervision <br> - prototype representation of concepts |
| **ZeroC**: A Neuro-Symbolic Model for Zero-shot Concept Recognition and Acquisition at Inference Time | NeurIPS | 2022 | [Code]() | [Arxiv](https://arxiv.org/abs/2206.15049) | - zero-shot <br> - introduce graph knowledge | 
| **Concept** **Embedding** **Models**: Beyond the Accuracy-Explainability Trade-Off | NeurIPS | 2022 | [Code](https://github.com/pietrobarbiero/pytorch_explain) | [Arxiv](https://arxiv.org/abs/2209.09056) | - Build upon Concept Bottleneck Models <br> - explain library |
| Multi-dimensional concept discovery (**MCD**): A unifying framework with completeness guarantees | TMLR | 2023 | [Code](https://github.com/jvielhaben/mcd-xai?tab=readme-ov-file#mcd-multi-dimensional-concept-discovery) | [Arxiv](https://arxiv.org/abs/2301.11911) | - a novel concept definition as low-dimensional feature sub- spaces <br> - sparse subspace clustering for concept discovery <br> - a novel definition of concept completeness applicable to many state-of-the-art architectures <br> - global and local concept relevance measures with corresponding completeness relations |
| Towards Robust Metrics for Concept Representation Evaluation | AAAI | 2023 | Null | [Arxiv](https://arxiv.org/abs/2301.10367) | | 
| Actional Atomic-Concept Learning for Demystifying Vision-Language Navigation | AAAI | 2023 | Null | [Arxiv](https://arxiv.org/abs/2302.06072) | |
| Label-Free Concept Bottleneck Models | ICLR | 2023 | [Code](https://github.com/Trustworthy-ML-Lab/Label-free-CBM) | [Arxiv](https://arxiv.org/abs/2304.06129) | - CBM family|
| Language in a Bottle: Language Model Guided Concept Bottlenecks for Interpretable Image Classification | CVPR | 2023 | [Code](https://github.com/yueyang1996/labo) | [Arxiv](https://arxiv.org/abs/2211.11158) | - CBM family |
| **Custom Diffusion** Multi-Concept Customization of Text-to-Image Diffusion | CVPR | 2023 | [Code](https://github.com/adobe-research/custom-diffusion) | [Project](https://www.cs.cmu.edu/~custom-diffusion/) | - Jun-Yan Zhu Lab | 
| **GCD** Dynamic Conceptional Contrastive Learning for Generalized Category Discovery | CVPR | 2023 | [Code](https://github.com/tpcd/dccl) | [Arxiv](https://arxiv.org/abs/2303.17393) | |
| **BotCL** Learning Bottleneck Concepts in Image Classification | CVPR | 2023 | [Code](https://github.com/wbw520/botcl) | [Arxiv](https://arxiv.org/abs/2304.10131) | - CBM family <br> - w/o explicit supervision |
| A Closer Look at the Intervention Procedure of Concept Bottleneck Models | ICML | 2023 | [Code](https://github.com/ssbin4/closer-intervention-cbm) | [Arxiv](https://arxiv.org/abs/2302.14260) | -select intervening concepts |
| **Cones**: Concept Neurons in Diffusion Models for Customized Generation | ICML | 2023 | 404 | [Arxiv](https://arxiv.org/abs/2303.05125) | |
| Interpretable Neural-Symbolic Concept Reasoning | ICML | 2023 | [Code](https://github.com/pietrobarbiero/pytorch_explain) | [Arxiv](https://arxiv.org/abs/2304.14068) | - explain library |
| **DISC** Discover and Cure: Concept-aware Mitigation of Spurious Correlation | ICML | 2023 | [Code](https://github.com/wuyxin/disc) | [Arxiv](https://arxiv.org/abs/2305.00650) | - adaptively discover and remove spurious correlations during model training|
| Text-To-Concept (and Back) via Cross-Model Alignment | ICML | 2023 | Null | [Arxiv](https://arxiv.org/abs/2305.06386) | |
| Probabilistic Concept Bottleneck Models | ICML | 2023 | [Code](https://github.com/ejkim47/prob-cbm) | [Arxiv](https://arxiv.org/abs/2306.01574) | - CBM family |
| Unsupervised Compositional Concepts Discovery with Text-to-Image Generative Models | ICCV | 2023 | [Code](https://github.com/nanlliu/Unsupervised-Compositional-Concepts-Discovery) |[Arxiv](https://arxiv.org/abs/2306.05357)| |
| Erasing Concepts from Diffusion Models | ICCV | 2023 | [Code](https://github.com/rohitgandikota/erasing) | [Project](https://erasing.baulab.info/)| - David Bau Lab |
| Ablating Concepts in Text-to-Image Diffusion Models | ICCV | 2023 | [Code](https://github.com/nupurkmr9/concept-ablation) | [Project](https://www.cs.cmu.edu/~concept-ablation/) | - Jun-Yan Zhu Lab |
| **ConceptLab**: Creative Generation using Diffusion Prior Constraints | | 2023 |[Code](https://github.com/kfirgoldberg/ConceptLab) | [Arxiv](https://arxiv.org/abs/2308.02669) | |
| **CPM** Causal Proxy Models for Concept-Based Model Explanations | | 2023 |[Code](https://github.com/frankaging/Causal-Proxy-Model) | [Arxiv](https://arxiv.org/abs/2209.14279) | - NLP |
| Explain Any Concept: Segment Anything Meets Concept-Based Explanation | | 2023 | Null | [Arxiv](https://arxiv.org/abs/2305.10289) | |
| **UCE**  Unified Concept Editing in Diffusion Models | WACV | 2024 | [Code](https://github.com/rohitgandikota/unified-concept-editing) | [Project](https://unified.baulab.info/) | - David Bau Lab
| **Concept Sliders**: LoRA Adaptors for Precise Control in Diffusion Models | ECCV | 2024 | [Code](https://github.com/rohitgandikota/sliders) | [Project](https://sliders.baulab.info/) | - David Bau Lab |