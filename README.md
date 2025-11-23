# Cloud Classification Benchmark: Efficiency vs Accuracy with Self-Distillation

This repository contains the notebook used for a comparative study of efficient CNN architectures for cloud-type classification. The study benchmarks several models under identical training conditions and evaluates how self-distillation influences their performance.

## Contents
- **`comparative_study.ipynb`** — End-to-end notebook for training, evaluation, efficiency measurement, and self-distillation experiments.

## Dataset
The experiments use the following publicly available cloud image dataset:

**Clouds Photos Dataset (Kaggle)**  
https://www.kaggle.com/datasets/jockeroika/clouds-photos

This dataset includes seven cloud categories:
- High Cumuliform  
- Cumulus  
- Cirriform  
- Stratocumulus  
- Clear Sky  
- Stratiform  
- Cumulonimbus  

## Summary
The notebook:
- Benchmarks several efficient CNNs (e.g., MobileNet, EfficientNet, ResNet, ConvNeXt).  
- Includes a TinyCNN model as a minimal lightweight baseline.  
- Applies **self-distillation** to analyze how each architecture responds to distilled supervision.  
- Compares baseline vs distilled models using accuracy, parameter count, FLOPs, and CPU/GPU latency.

## Citation

If you use this repository or build upon this study, please cite:

```sh
@software{Rahman_Nijhum_Cloud_Classification_Benchmark_2025,
author = {Rahman Nijhum, Ifran and Hoque Mithila, Iffat and Ayala Cabrera, David and Dev, Soumyabrata},
month = jan,
title = {{Cloud Classification Benchmark: Efficiency vs Accuracy with Self-Distillation}},
url = {https://github.com/ifran-rahman/cloud-classification-benchmark},
version = {1.0},
year = {2025}
}
```
