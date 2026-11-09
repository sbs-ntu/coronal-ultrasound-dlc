# Coronal Ultrasound DeepLabCut Model

A DeepLabCut model for tracking the tongue surface in coronal ultrasound images, developed at the [Speech Behavior and Science (SBS) Lab](https://github.com/sbs-ntu), Graduate Institute of Linguistics, National Taiwan University.

## Status

This repository is a placeholder. The trained model and the tracking pipeline will be released here after further validation. It currently contains this README only.

## Planned release

- **Model**: DeepLabCut weights (ResNet-50) for seven tongue-surface landmarks in coronal ultrasound images.
- **Pipeline**: full-recording tracking, median filtering of landmark trajectories, and contour interpolation (PCHIP with uniform arc-length resampling, Savitzky–Golay smoothing over time).
- **Documentation**: landmark definitions and usage instructions.

## Background

The model comes from a study of how many annotated frames and training epochs DeepLabCut needs to track the coronal tongue surface. The dataset comprises 6,080 annotated frames from two speakers of Taiwan Mandarin, and 15 models were trained on nested subsets of the training pool. In this dataset, test accuracy rose quickly up to 740 frames, and 3,900 frames came within 0.5 mAP of the best observed model. These benchmarks come from two speakers and one recording setup.

## Citation

Wang, C.-W., & Chiu, C. (2026). *How much is enough? Estimating annotation requirements for DeepLabCut tracking of coronal ultrasound tongue images* [Poster presentation]. Ultrafest XII, Université Paris Cité, Paris, France, 19–20 November 2026.

## Contact

Please open an issue in this repository.
