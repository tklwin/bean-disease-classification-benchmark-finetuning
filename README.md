This repository contains the code and supplementary materials for the research paper:

"**Improving Bean Disease Classification with Stepwise Fine-tuning of CNN-based Transfer Learning Models**"

**Authors:** [Thein Kyaw Lwin, Thandar Phyo, Carla Sales]
**Affiliation(s):** [Batangas State University]

## Overview

This research paper explores the application of transfer learning using various pre-trained Convolutional Neural Network (CNN) architectures for the task of classifying diseases in bean plant images. We conduct a comparative benchmark of 5 CNN models to identify the most promising architecture for this specific task. Furthermore, we implement and analyze a stepwise fine-tuning strategy on the best-performing model to further optimize its performance and adaptability to the bean disease dataset.

The goal is to provide insights into effective transfer learning strategies for agricultural image classification, specifically demonstrating the potential of readily available pre-trained models and the benefits of structured fine-tuning.

## Repository Contents

*   `revised-bean-disease-classification-finetuning.ipynb`: The main Jupyter notebook containing all the Python code for data loading, preprocessing, model benchmarking, stepwise fine-tuning, evaluation, and visualization.

## Running the Code

This notebook is designed to be easily run on Kaggle, providing a convenient cloud-based environment with necessary libraries pre-installed and dataset access configured. **Kaggle also offers free access to GPUs, which are highly recommended for significantly faster training of deep learning models like the ones used in this project.**

[![kaggle](https://kaggle.com/static/images/open-in-kaggle.svg)](https://www.kaggle.com/code/theinkyawlwin/revised-bean-disease-classification-finetuning)
[![colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tklwin/bean-disease-classification-finetuning/blob/main/revised-bean-disease-classification-finetuning.ipynb)
[![code](https://badges.aleen42.com/src/github.svg)](https://github.com/tklwin/bean-disease-classification-finetuning)

## Dataset

We used [integrated version](https://github.com/tklwin/bean-disease-classification-finetuning/tree/main/new_bean_dataset) of following datasets:
- iBean dataset: https://github.com/AI-Lab-Makerere/ibean/
- Bangladesh Bean Leaf Dataset: https://data.mendeley.com/datasets/ykvcrjffzd/1
