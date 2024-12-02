# Semi-Supervised Learning: Co-Training and Label Propagation

## Project Overview

This project investigates semi-supervised learning techniques to enhance model performance by leveraging both labeled and unlabeled data. The primary focus is on two approaches:

- **Co-Training**: A collaborative method combining a Convolutional Neural Network (CNN) and a Random Forest to iteratively improve predictions.
- **Label Propagation**: A graph-based algorithm that spreads labels from labeled to unlabeled data points using k-nearest neighbors (KNN).

The experiments explore the impact of varying the amount of labeled and unlabeled data, model complexity, and the interplay between supervised and semi-supervised learning methods.

## Key Features
- Implementation of co-training with CNN and Random Forest models.
- Label propagation using KNN for semi-supervised learning.
- Analysis of performance variations with different dataset splits.
- Comparison between supervised and semi-supervised approaches.

## Applications
This project demonstrates how semi-supervised learning can be applied to real-world problems with limited labeled data, such as:
- Image classification tasks.
- Large-scale text or feedback analysis.
- Domains requiring cost-effective data labeling solutions.
