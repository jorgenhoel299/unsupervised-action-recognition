# Invariant Information Clustering (IIC) for Human Activity Recognition (HAR)

This repository hosts the code and resources for adapting **Invariant Information Clustering (IIC)** to the challenging domain of Human Activity Recognition (HAR) using image data. The project investigates the performance of unsupervised learning on a dataset of still images containing 15 human activities.

## 📄 Project Overview

Human activity recognition has traditionally relied on supervised learning, but unsupervised methods like **IIC** provide an alternative that avoids costly labeling. This project explores IIC’s potential for clustering human activities in still images, building on previous works that use mutual information to learn invariant representations.

Key features:
- **Dataset**: Still images representing 15 human activities (e.g., drinking, using a laptop) in various environments. 
- **Preprocessing**: Data augmentation and pair generation to improve diversity and cluster stability.
- **Model**: ResNet18-based architecture with overclustering techniques to handle noise and class overlap.
- **Experiments**: Comparison of unsupervised IIC results with supervised models, highlighting the challenges of unsupervised HAR.

## 📚 Repository Contents

- `notebooks/`: Jupyter notebooks with code for preprocessing, model training, and evaluation.
- `dataset/`: Images used for testing and evaluation.
- `Viabiltiy of Invariant Information Clustering of Human Actions.pdf`: Detailed report documenting methodology, experiments, and findings.

## Key Links

- [IIC Paper](https://openaccess.thecvf.com/content_ICCV_2019/papers/Ji_Invariant_Information_Clustering_for_Unsupervised_Image_Classification_and_Segmentation_ICCV_2019_paper.pdf) - The original paper introducing Invariant Information Clustering for images.
- [Dataset Source](https://www.kaggle.com/datasets/meetnagadia/human-action-recognition-har-dataset/) 
