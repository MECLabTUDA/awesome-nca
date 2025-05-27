# Awesome NCA

A curated list of anything related to Neural Cellular Automata (NCA) research, frameworks and applications.

NCA are a new type of neural architecture, marrying cellular automata and neural networks to create memory-efficient, robust models.
Mostly, NCAs are applied in image segmentation, classification and generation.
However, there are also works that use NCAs for reinforcement learning or generation of three-dimensional structures.
This list is a curated collection of research papers and code repositories, presenting ideas and applications for NCA.

Scope: Other types of self-organizing systems, traditional cellular automata, other deep learning techiques are not covered, unless they utilize a cellular automaton with a learned rule in their computation.
Review papers are not listed here, unless they are reviews of Neural Cellular Automata in particular (no reviews of, e.g., self-organizing systems in general that mention NCA).

You are welcome to [contribute](#contributing) if you've found other NCA papers, code repositories or resources that you like to share.

[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

--------------------

## Table of contents

- [Research](#research)
  - [Open Access](#open-access)
  - [Restricted Access](#restricted-access)
- [Code](#code)
- [Videos and Visuals](#videos-and-visuals)
- [Study Material and Tutorials](#tutorials)
- [Contributing](#contributing)
- [License](#license)

## Research

Papers presenting theoretical and methodological contributions to NCA research, ordered by publication year.

### Open Access

#### On 2D/3D Image Grids

Works that study NCAs applied to 2D or 3D lattices.

* [Growing Neural Cellular Automata](https://distill.pub/2020/growing-ca/), Mordvintsev et al. 2020
* [Self-classifying MNIST Digits](https://distill.pub/2020/selforg/mnist/), Randazzo et al. 2020
* [Image Generation With Neural Cellular Automata](https://arxiv.org/abs/2010.04949), Chen & Wang 2020
* [Predicting Geographic Information with Neural Cellular Automata](https://arxiv.org/pdf/2009.09347), Chen et al. 2020
* [Self-organizing Textures](https://distill.pub/selforg/2021/textures/), Niklasson et al. 2021
* [Growing 3D Artefacts and Functional Machines with Neural Cellular Automata](https://arxiv.org/abs/2103.08737), Sudhakaran et al. 2021
* [Adversarial Reprogramming of Neural Cellular Automata](https://distill.pub/selforg/2021/adversarial/), Randazzo et al. 2021
* [Generative Adversarial Neural Cellular Automata](https://arxiv.org/abs/2108.04328), Otte et al. 2021
* [Physical Neural Cellular Automata for 2D Shape Classification](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9981214), Walker et al. 2022
* [Goal-Guided Neural Cellular Automata: Learning to Control Self-organizing Systems](https://arxiv.org/pdf/2205.06806), Sudhakaran et al. 2022
* [Variational Neural Cellular Automata](https://arxiv.org/pdf/2201.12360), Palm et al. 2022
* [Empowered Neural Cellular Automata](https://arxiv.org/pdf/2205.06771), Grasso & Bongard 2022
* [Attention-based Neural Cellular Automata](https://proceedings.neurips.cc/paper_files/paper/2022/file/361e5112d2eca09513bbd266e4b2d2be-Paper-Conference.pdf), Tasfaldet et al. 2022
* [HyperNCA: Growing Developmental Networks with NCA](https://arxiv.org/pdf/2204.11674), Najarro et al. 2022
* [Med-NCA, Robust and Lightweight Segmentation with Neural Cellular Automata](https://arxiv.org/abs/2302.03473), Kalkhof et al. 2023
* [M3D-NCA: Robust 3D Segmentation with Built-in Quality Control](https://arxiv.org/pdf/2309.02954), Kalkhof & Mukhopadhyay 2023
* [Growing Steerable Neural Cellular Automata](https://arxiv.org/abs/2302.10197), Randazzo et al. 2023
* [NCA-Morph: Medical Image Registration with Neural Cellular Automata](https://arxiv.org/pdf/2410.22265), Ranem et al. 2024
* [Unsupervised Training of Neural Cellular Automata on Edge Devices](https://arxiv.org/pdf/2407.18114), Kalkhof et al. 2024
* [Localized Data Representation with NCA-Based Autoencoders](https://link.springer.com/chapter/10.1007/978-3-031-78186-5_25), Ihm et al. 2024
* [Evolving Hierarchical Neural Cellular Automata](https://dl.acm.org/doi/pdf/10.1145/3638529.3654150), Bielawski et al. 2024
* [Skin lesion segmentation via Neural Cellular Automata](https://www.sciencedirect.com/science/article/pii/S1746809424006050), Yue et al. 2024
* [An Organism Starts with a Single Pix-Cell: A Neural Cellular Diffusion for High-Resolution Image Synthesis](https://arxiv.org/pdf/2407.03018), Elbatel et al. 2024
* [Deep learning with photonic neural cellular automata](https://www.nature.com/articles/s41377-024-01651-7), Li et al. 2024
* [eNCApsulate: Neural Cellular Automata for Precision Diagnosis on Capsule Endoscopes](https://arxiv.org/pdf/2504.21562), Krumb & Mukhopadhyay 2025
* [NCAdapt: Dynamic Adaptation with Domain-Specific Neural Cellular Automata for Continual Hippocampus Segmentation](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10943578), Ranem & Mukhopadhyay 2025
* [Unraveling Neural Cellular Automata for Lightweight Image Compression](https://openreview.net/pdf?id=gIrVoQEDQv), Falcao et al. 2025
* [MED-NCA: Bio-inspired medical image segmentation](https://www.sciencedirect.com/science/article/pii/S1361841525001483), Kalkhof et al. 2025
* [Differentiable Logic Cellular Automata](https://google-research.github.io/self-organising-systems/difflogic-ca/), Miotti et al. 2025
* [Parameter-efficient diffusion with neural cellular automata](https://www.nature.com/articles/s44335-025-00026-4), Kalkhof et al. 2025

#### Graph NCA

Works that study Graph Neural Cellular Automata.

* [Learning Graph Cellular Automata](https://arxiv.org/abs/2110.14237), Grattarola et al. 2021
* [Training Topology With Graph Neural Cellular Automata](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10187381), Dwyer et al. 2023
* [Physics-Informed Graph Neural Cellular Automata: an Application to Compartmental Modelling](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10650578), Navarin et al. 2024
* [E(n)-equivariant Graph Neural Cellular Automata](https://arxiv.org/pdf/2301.10497), Gala et al. 2025

### Restricted Access

None so far

### Overview

Tabular overview of research papers on NCA since 2020, ordered by publication year.

| Paper URL                                              | Year | Downstream Task     | Dataset(s)                    | Code | Model              |
| ------------------------------------------------------ | ---- | ------------------- | ----------------------------- | ---- | ------------------ |
| [Paper](https://distill.pub/2020/growing-ca/)          | 2020 | Grow from seed      | Emojis                        | [tensorflow](https://colab.research.google.com/github/google-research/self-organising-systems/blob/master/notebooks/growing_ca.ipynb), [torch](https://github.com/chenmingxiang110/Growing-Neural-Cellular-Automata/tree/master) | NCA |
| [Paper](https://distill.pub/2020/selforg/mnist/)       | 2020 | Classification      | MNIST Digits                  | [tensorflow](https://colab.research.google.com/github/google-research/self-organising-systems/blob/master/notebooks/mnist_ca.ipynb) | NCA                |
| [Paper](https://arxiv.org/abs/2010.04949)              | 2020 | Generation          | Emojis, MNIST, CelebA         | [torch](https://github.com/chenmingxiang110/VAE-NCA) | NCA + VAE          |
| [Paper](https://arxiv.org/pdf/2009.09347)              | 2020 | Traffic Prediction  | Maps+Traffic overlay (custom) | [torch](https://github.com/chenmingxiang110/NCA_Prediction) | Multi-layer NCA    |
| [Paper](https://distill.pub/selforg/2021/textures/)    | 2021 | Texture Generation  | [Dataset](https://arxiv.org/pdf/1311.3618) | [torch](https://colab.research.google.com/github/google-research/self-organising-systems/blob/master/notebooks/texture_nca_pytorch.ipynb), [tensorflow](https://colab.research.google.com/github/google-research/self-organising-systems/blob/master/notebooks/texture_nca_tf2.ipynb) | NCA        |
| [Paper](https://arxiv.org/abs/2103.08737)              | 2021 | 3D Structure Gen.   | Minecraft Structures          | [torch](https://github.com/real-itu/3d-artefacts-nca) | Multi-layer 3D NCA |
| [Paper](https://distill.pub/selforg/2021/adversarial/) | 2021 | Classification, Reprogramming | MNIST               | [tensorflow](https://colab.research.google.com/github/google-research/self-organising-systems/blob/master/adversarial_reprogramming_ca/adversarial_mnist_ca.ipynb) | NCA                |
| [Paper](https://arxiv.org/abs/2108.04328)              | 2021 | Generation          | Emojis                        | N/A  | NCA + GAN          |
| [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9981214&tag=1) | 2022  | Shape self-classification on µC H/W | Digits (custom, but simple)   | N/A               | NCA  |
| [Paper](https://arxiv.org/pdf/2205.06806)              | 2022 | Control of self-organization | Emojis               | [torch](https://github.com/shyamsn97/controllable-ncas) | NCA  |
| [Paper](https://arxiv.org/pdf/2201.12360)              | 2022 | Gen. Modelling      | Emojis, CelebA                | [torch](https://github.com/rasmusbergpalm/vnca) | NCA + VAE |
| [Paper](https://arxiv.org/pdf/2205.06771)              | 2022 | Grow from seed      | Custom shapes                 | [numpy](https://github.com/caitlingrasso/empowered-nca) | NCA trained with information-theoretic fitness function and age-fitness pareto optimization |
| [Paper](https://proceedings.neurips.cc/paper_files/paper/2022/file/361e5112d2eca09513bbd266e4b2d2be-Paper-Conference.pdf) | 2022 | Classification | Tiny ImageNet, MNIST, FashionMNIST, CelebA | [torch](https://proceedings.neurips.cc/paper_files/paper/2022/hash/361e5112d2eca09513bbd266e4b2d2be-Abstract-Conference.html)  | ViT + NCA (ViTCA) |
| [Paper](https://arxiv.org/pdf/2204.11674)              | 2022 | Generating policy networks for reinforcement learning | | [torch](https://github.com/enajx/hyperNCA) | 3D NCA |
| [Paper](https://arxiv.org/abs/2302.03473)              | 2023 | MRI Segmentation on Raspberry Pi | Decathlon (Hippocampus & Prostate), ISBI 2013 challenge | [torch](https://github.com/MECLabTUDA/Med-NCA)  | Multi-scale NCA |
| [Paper](https://arxiv.org/pdf/2309.02954)              | 2023 | MRI Segmentation on Raspberry Pi | Decathlon (Hippocampus & Prostate) | [torch](https://github.com/MECLabTUDA/M3D-NCA) | 3D NCA with patchification |
| [Paper](https://arxiv.org/pdf/2302.10197)              | 2023 | Grow from seed(s)   | Emojis                        | [torch](https://github.com/google-research/self-organising-systems/blob/master/isotropic_nca/blogpost_isonca_single_seed_pytorch.ipynb) | Steerable NCA |
| [Paper](https://arxiv.org/pdf/2410.22265)              | 2024 | MRI Registration (Prostate, Hippocampus, other) | OASIS-1, PROMISE12, Dryad | [torch](https://github.com/MECLabTUDA/NCA-Morph) | 3D NCA with patchification |
| [Paper](https://arxiv.org/pdf/2407.18114)              | 2024 | X-ray segmentation on smartphone | Padchest, ChestX-ray8, MIMIC-III | [torch](https://arxiv.org/pdf/github.com/MECLabTUDA/M3D-NCA) | Med-NCA, trained with variance-weighted loss |
| [Paper](https://link.springer.com/chapter/10.1007/978-3-031-78186-5_25) | 2024 | Classification | CIFAR-10-C | N/A | NCA + VAE |
| [Paper](https://www.nature.com/articles/s41377-024-01651-7) | 2024 | Classification | FashionMNIST | N/A | NCA on photonics hardware |
| [Paper](https://dl.acm.org/doi/pdf/10.1145/3638529.3654150) | 2024 | Shape generation | Custom shapes | [numpy+numba](https://github.com/ngaylinn/mocs-final) | HNCA (Hierarchical NCA) |
| [Paper](https://www.sciencedirect.com/science/article/pii/S1746809424006050) | 2024 | Skin lesion segmentation | ISIC2017 | N/A | UNet-style network with NCA bottleneck |
| [Paper](https://arxiv.org/pdf/2407.03018)              | 2024 | Generation          | Optical Coherence Tomography  | [torch]( https://github.com/xmed-lab/GeCA) | Diffusion + NCA |
| [Paper](https://arxiv.org/pdf/2504.21562)              | 2025 | Segmentation, Depth Est., edge AI | Capsule Endoscopic | [torch](https://github.com/MECLabTUDA/eNCApsulate) | NCA |
| [Paper](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=10943578) | 2025       | Continual Hippocampus MRI Segmentation | HarP, Dryad, DecathHip | [torch](https://github.com/MECLabTUDA/NCAdapt) | NCA with adaptible layers and multiple heads |
| [Paper](https://openreview.net/pdf?id=gIrVoQEDQv)      | 2025 | Image Compression   | COCO 2017                     | N/A | Grid-based, "GNCA" |
| [Paper](https://google-research.github.io/self-organising-systems/difflogic-ca/) | 2025 | Grow from seed using learned logic gates | Emojis, Icons | [jax](https://colab.research.google.com/github/google-research/self-organising-systems/blob/master/notebooks/diffLogic_CA.ipynb) | Differential Logic Gates + NCA |
| [Paper](https://www.nature.com/articles/s44335-025-00026-4) | 2025 | Image Generation | CelebA, Pathology | [torch](https://github.com/MECLabTUDA/M3D-NCA/tree/parameter_efficient_diffusion) | FourierDiff-NCA, Fourier-based diffusion |

## Code

NCA code repositories, including accompanying repositories for publications listed above.

* [Growing-Neural-Cellular-Automata (Pytorch)](https://github.com/chenmingxiang110/Growing-Neural-Cellular-Automata/tree/master): Pytorch implementation of "Growing Neural Cellular Automata", including interactive pygame demo.
* [M3D NCA](https://github.com/MECLabTUDA/M3D-NCA): Implementation of Med-NCA, M3D-NCA and related works.
* [VAE-NCA](https://github.com/chenmingxiang110/VAE-NCA): Reproduction of [paper](https://arxiv.org/abs/2010.04949) "Image Generation With Neural Cellular Automata" (2020)
* [Predicting Geographic Information with Neural Cellular Automata](https://github.com/chenmingxiang110/NCA_Prediction): Reproduction of [paper](https://arxiv.org/pdf/2009.09347).
* [NCALab](https://github.com/MECLabTUDA/NCAlab): Framework for training and evaluation of NCA models, including various examples for classification, segmentation, etc.
* [Growing 3D Artefacts and Functional Machines with Neural Cellular Automata](https://github.com/real-itu/3d-artefacts-nca): Using NCA for generating Minecraft structures
* [Learning Graph Cellular Automata](https://github.com/danielegrattarola/GNCA): Code for [paper](https://arxiv.org/abs/2110.14237)

## Tutorials

Tutorials and study material related to NCA.

- [Video: Growing NCA in Pytorch](https://www.youtube.com/watch?v=21ACbWoF2Oo)
- [Video: Growing NCA](https://www.youtube.com/watch?v=9Kec_7WFyp0) - 15 Minute paper review by Yannic Kilcher
- [Video: What are Neural Cellular Automata?](https://www.youtube.com/watch?v=3H79ZcBuw4M)
- [Youtube-Channel: Programmable Artificial Life](https://www.youtube.com/@zzznah/videos) - Several videos on NCA
- [Two-minute Papers feature of Growing NCA](https://www.youtube.com/watch?v=bXzauli1TyU)
- [NCA do active inference](https://aman-bhargava.com/ai/neuro/neuromorphic/2024/03/25/nca-do-active-inference.html)
- [Graph Neural Cellular Automata](https://danielegrattarola.github.io/posts/2021-11-08/graph-neural-cellular-automata.html) - Blog article


## Videos and Visuals

Cool demo videos and visuals of NCAs in action.

- [Video: Minecraft Morphogenesis](https://www.youtube.com/watch?v=-EzztzKoPeo)
- [Interactive: Random NCA](https://nailbar.io/proj/curves/test10.html) - Clicking anywhere on the image randomizes the rule.

## Contributing

Contribution guidelines can be found in [CONTRIBUTING.md](https://github.com/MECLabTUDA/awesome-nca/blob/main/CONTRIBUTING.md)

## License

This list is under the [Creative Commons Attribution-ShareAlike 4.0](https://creativecommons.org/licenses/by-sa/4.0) License.
The list of authors can be found in the [AUTHORS](https://github.com/MECLabTUDA/awesome-nca/blob/main/AUTHORS.md) file.
