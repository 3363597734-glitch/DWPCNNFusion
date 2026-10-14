# DWPCNNFusion
## Deep pulse-coupled neural networks incorporating Weber’s law for efficient infrared and visible image fusion

We are pleased to announce that this work has been accepted by **Infrared Physics & Technology (JCR Q2)**.

**Paper:** [Read the published article](https://doi.org/10.1016/j.infrared.2026.106417)

## Highlights

- We propose **DWPCNNFusion**, a brain-inspired, end-to-end trainable framework for infrared and visible image fusion that combines infrared target saliency with visible texture details.
- We introduce **Weber’s law into deep pulse-coupled neural networks**, using learnable coupling weights and brightness-dependent linking strength to improve feature extraction and alleviate detail loss in low-light environments.
- We use **linear threshold decay, temporal adaptive batch normalization, and rate encoding** to support stable training and integrate pulse-based temporal representations with conventional deep learning layers.
- We design **Pulse Convolutional Dense Blocks (PCDB)** to extract high-level semantic features. Experiments on **TNO and MSRS**, compared with **15 representative methods**, demonstrate a favorable balance between fusion quality and computational efficiency.

## Overall Architecture

![Overall Architecture](https://github.com/user-attachments/assets/806a2d7e-2073-4dc4-89e4-33d69367c2fe)

## Abstract

Infrared and visible image fusion aims to combine complementary information from two modalities into a single image with salient targets and rich texture details. Many deep learning methods improve fusion performance by increasing network complexity, which also increases computational demands. We propose DWPCNNFusion, a brain-inspired fusion framework built around a Deep Pulse-Coupled Neural Network incorporating Weber’s law (DWPCNN). Learnable coupling weights adapt to input features, while Weber’s-law-based linking strength models nonlinear brightness perception to alleviate detail loss under low illumination. Linear threshold decay and temporal adaptive batch normalization support the training of pulse-based dynamics, and rate encoding integrates temporal information into representations compatible with conventional deep learning layers. Pulse Convolutional Dense Blocks further enhance high-level feature extraction. Qualitative and quantitative comparisons with 15 representative methods on the TNO and MSRS datasets demonstrate effective detail preservation and a favorable tradeoff between fusion performance and computational efficiency.

## Datasets

The paper evaluates DWPCNNFusion on:

- **MSRS:** paired infrared and visible images.
- **TNO:** infrared and visible image pairs used to evaluate fusion performance across different scenes.

## Installation

Code and dependency instructions will be added to this repository.

## Quick Start

Training and inference commands will be provided with the code release.

## Citation

If you find this work useful, please cite:

```bibtex
@article{zhao2026dwpcnnfusion,
  title = {DWPCNNFusion: Deep pulse-coupled neural networks incorporating Weber's law for efficient infrared and visible image fusion},
  author = {Zhao, Jia and Jia, Sirui and Di, Jing and Lian, Jing and Ma, Yide and Xin, Yuelan and Dang, Jisheng and Liu, Jizhao},
  journal = {Infrared Physics \& Technology},
  volume = {154},
  pages = {106417},
  year = {2026},
  doi = {10.1016/j.infrared.2026.106417}
}
```

