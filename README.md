# ATASGG-SFDA

Official repository for the MICCAI 2026 paper:

> **Anatomy-Texture Aware Safe Gradient Guidance for Source-Free Domain Adaptive Echocardiography Video Segmentation**  
> **Jinrong Lv**, Xun Gong, Ning Cheng, Zhaohuan Li, and Weili Jiang  
> *Medical Image Computing and Computer Assisted Intervention (MICCAI), 2026*

## Repository Status

> **Code release in progress.**  
> The implementation is currently being cleaned, organized, and documented. The source code and detailed reproduction instructions will be released in this repository soon.

No runnable implementation is available in the repository yet. Please **watch** or **star** the repository to receive future updates.

## Overview

ATASGG-SFDA is a source-free domain adaptation framework for echocardiography video segmentation. It is designed to improve adaptation stability under cross-vendor and cross-population domain shifts without requiring access to source-domain data.

The framework contains two main components:

- **Anatomy-Texture Decomposition Strategy (ATDS):** combines a frozen source-model anchor with a momentum-updated texture adapter to construct anatomy- and texture-aware pseudo-supervision.
- **Safe Gradient Guidance Mechanism (SGGM):** dynamically controls the entropy-minimization signal according to its gradient compatibility with anatomy-texture supervision.


## Paper

The paper link and final proceedings information will be added after they become publicly available.

## Datasets

The experiments use the following publicly available echocardiography datasets:

- CAMUS
- EchoNet-Dynamic
- EchoNet-Pediatric

The datasets are not redistributed in this repository. Users should obtain them from their official providers and comply with the corresponding terms of use.

## Installation

Installation instructions will be provided with the code release.

## Training and Evaluation

Training, adaptation, inference, and evaluation commands will be provided with the code release.

## Citation

The following entry is preliminary and will be updated after the official MICCAI 2026 proceedings metadata becomes available:

```bibtex
@inproceedings{lv2026atasgg,
  title     = {Anatomy-Texture Aware Safe Gradient Guidance for Source-Free Domain Adaptive Echocardiography Video Segmentation},
  author    = {Lv, Jinrong and Gong, Xun and Cheng, Ning and Li, Zhaohuan and Jiang, Weili},
  booktitle = {Medical Image Computing and Computer Assisted Intervention -- MICCAI 2026},
  year      = {2026}
}
```

## License

License information will be added together with the public code release. Any third-party code, models, or datasets remain subject to their respective licenses and terms of use.

## Contact

For questions about this work, please contact:

**Jinrong Lv**  
School of Computing and Artificial Intelligence, Southwest Jiaotong University  
Email: lvjinrong@my.swjtu.edu.cn
