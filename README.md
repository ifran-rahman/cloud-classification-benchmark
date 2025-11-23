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

