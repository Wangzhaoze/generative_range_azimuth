# Synthetic FMCW Radar Range–Azimuth Maps Augmentation with Generative Diffusion Model

Project page and resources for the RadarConf 2026 paper by Zhaoze Wang, Changxu Zhang, Tai Fei, Christopher Grimm, Yi Jin, Claas Tebruegge, Ernst Warsitz, and Markus Gardill.

- Project page: https://wangzhaoze.github.io/generative_range_azimuth/
- IEEE Xplore: https://ieeexplore.ieee.org/abstract/document/11675434
- arXiv: https://arxiv.org/abs/2601.06228

## Highlights

- Conditional diffusion framework for synthesizing realistic FMCW radar range–azimuth maps.
- Geometry-Aware Conditioning (GAC) models range attenuation, antenna gain, and occlusion effects.
- Target-Consistency Regularization (TCR) emphasizes target energy while preserving diverse radar background statistics.
- +3.6 dB PSNR over the baseline and +4.15 percentage points overall mAP in downstream radar object detection with hybrid real/synthetic training data.
