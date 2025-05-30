This repository contains the code and supplementary materials for the research paper:

"**Benchmarking and Stepwise Fine-tuning of Transfer Learning Models for Bean Disease Classification**"

**Authors:** [Thein Kyaw Lwin, Thandar Phyo, Carla Sales]
**Affiliation(s):** [Batangas State University]

## Overview

This research paper explores the application of transfer learning using various pre-trained Convolutional Neural Network (CNN) architectures for the task of classifying diseases in bean plant images. We conduct a comparative benchmark of several popular models to identify the most promising architecture for this specific task. Furthermore, we implement and analyze a stepwise fine-tuning strategy on the best-performing model to further optimize its performance and adaptability to the bean disease dataset.

The goal is to provide insights into effective transfer learning strategies for agricultural image classification, specifically demonstrating the potential of readily available pre-trained models and the benefits of structured fine-tuning.

## Repository Contents

*   `bean-disease-classification.ipynb`: The main Jupyter notebook containing all the Python code for data loading, preprocessing, model benchmarking, stepwise fine-tuning, evaluation, and visualization.
*   `outputs/`: This directory store generated plots (e.g., training history, confusion matrices and fine-tuned model) and performance summaries after running the notebook.

## Running the Code

This notebook is designed to be easily run on Kaggle, providing a convenient cloud-based environment with necessary libraries pre-installed and dataset access configured. **Kaggle also offers free access to GPUs, which are highly recommended for significantly faster training of deep learning models like the ones used in this project.**

The code in the notebook will automatically download and extract the dataset from the original source URL provided by the dataset creators.

[Kaggle Notebook](https://www.kaggle.com/code/theinkyawlwin/bean-disease-classification)

## Dataset

The dataset used in this research is the [Bean disease dataset (iBeans)](https://github.com/AI-Lab-Makerere/ibean).
