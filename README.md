# Archon: A Unified Multimodal Model for Holistic Digital Human Generation

### [Project Page](https://zju3dv.github.io/archon/) | [Paper](https://arxiv.org/abs/2605.30311) | [Video](https://www.youtube.com/watch?v=9h2_L9E2KjE)

<div align="center">

[![Paper](https://img.shields.io/badge/Paper-CVPR%202026-blue)](https://arxiv.org/abs/2605.30311)
[![Video](https://img.shields.io/badge/Video-YouTube-red)](https://www.youtube.com/watch?v=9h2_L9E2KjE)
[![Project Page](https://img.shields.io/badge/Project%20Page-Live-brightgreen)](https://zju3dv.github.io/archon/)
[![Models](https://img.shields.io/badge/Models-To%20be%20released-lightgrey)](#re-implementation-plan)

</div>

> [Archon: A Unified Multimodal Model for Holistic Digital Human Generation](https://arxiv.org/pdf/2605.30311)  
>
> Chong Bao, Shichen Liu, Lijun Yu, David Futschik, Stylianos Moschoglou, Shefali Srivastava, Ziqian Bai, Feitong Tan, Guofeng Zhang, Zhaopeng Cui, Sean Fanello, Yinda Zhang  
>
> CVPR 2026

Archon is a unified multimodal model for holistic digital human generation. It reasons over description, script, speech, animation, semantic video, image, and video, enabling cross-modal generation and editing across a human-centric multimodal space.

> **Release status:** this repository is currently a placeholder for the public Archon release. The original research system was implemented in a non-public internal codebase, so this repository will host the open-source reimplementation and release artifacts as they become available. Please treat the release plan below as the current public roadmap rather than runnable instructions.

## News

- **2026-05-28:** README initialized for the public Archon repository. Code, model weights, dataset preprocessing, and runnable examples are marked as coming soon until they are released in this repository.
- **2026:** Archon appears in the CVPR 2026 Open Access proceedings.

## Re-implementation Plan

The public re-implementation will use open-sourced models as backbones and public datasets for training, preprocessing, and evaluation whenever possible. The goal is to provide a reproducible open stack while keeping the release path practical and incremental.

- [ ] Release open-source model and inference assets, including checkpoints, configuration files, and runnable examples.
- [ ] Release training and data-processing scripts for the public-data pipeline once the core paths are validated.
- [ ] Release evaluation and reproduction documentation, followed by full training recipes where they are reproducible and supportable.

Weclome to discuss if you are also interested in details and reproduction.

## Citation

If you find Archon useful for your research, please cite:

```bibtex
@inproceedings{bao2026archon,
  title={Archon: A Unified Multimodal Model for Holistic Digital Human Generation},
  author={Bao, Chong and Liu, Shichen and Yu, Lijun and Futschik, David and Moschoglou, Stylianos and Srivastava, Shefali and Bai, Ziqian and Tan, Feitong and Zhang, Guofeng and Cui, Zhaopeng and Fanello, Sean and Zhang, Yinda},
  booktitle={The IEEE/CVF Computer Vision and Pattern Recognition Conference (CVPR)},
  year={2026}
}
```

## Acknowledgement

We thank the authors and maintainers of the datasets, toolkits, and foundation models that make open research on digital humans possible. Detailed acknowledgements for the public implementation will be added together with the code release.
