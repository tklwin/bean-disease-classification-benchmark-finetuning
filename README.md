# bean-disease-classification-benchmark-finetuning
Benchmarking and Stepwise Fine-tuning using Transfer Learning for Bean Disease Classification with Pre-trained Convolutional Neural Networks
# Benchmarking and Stepwise Fine-tuning of Transfer Learning Models for Bean Disease Classification

[![DOI](https://zenodo.org/badge/DOI/YOUR_PAPER_DOI.svg)](https://doi.org/YOUR_PAPER_DOI) <!-- Optional: If you get a DOI for your paper/code -->

This repository contains the code and supplementary materials for the research paper:

"**Benchmarking and Stepwise Fine-tuning of Transfer Learning Models for Bean Disease Classification**"

**Authors:** [Your Name(s)]
**Affiliation(s):** [Your Affiliation(s)]
**[Optional: Link to the published paper or pre-print (e.g., on arXiv)]**

## Project Overview

This project explores the application of transfer learning using various pre-trained Convolutional Neural Network (CNN) architectures for the task of classifying diseases in bean plant images. We conduct a comparative benchmark of several popular models to identify the most promising architecture for this specific task. Furthermore, we implement and analyze a stepwise fine-tuning strategy on the best-performing model to further optimize its performance and adaptability to the bean disease dataset.

The goal is to provide insights into effective transfer learning strategies for agricultural image classification, specifically demonstrating the potential of readily available pre-trained models and the benefits of structured fine-tuning.

## Repository Contents

*   `bean-disease-classification.ipynb`: The main Jupyter notebook containing all the Python code for data loading, preprocessing, model benchmarking, stepwise fine-tuning, evaluation, and visualization.
*   `requirements.txt`: A list of all necessary Python libraries and their versions required to run the notebook.
*   `LICENSE`: Details the open-source license under which this code is made available.
*   `outputs/` (Optional): This directory can store generated plots (e.g., training history, confusion matrices) and performance summaries after running the notebook.

## Dataset

The dataset used in this research is the **Bean disease dataset (iBeans)**.

This dataset consists of images of healthy bean leaves and leaves affected by two common diseases: Angular Leaf Spot and Bean Rust.

The code in the notebook will automatically download and extract the dataset from the original source URL provided by the dataset creators using `tf.keras.utils.get_file`.

**Citation for the iBeans Dataset:**

If you use this dataset or code based on its use, please cite the original creators:
