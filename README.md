# Breast Cancer Classification (Supervised ML)       
The objective of this project is to evaluate the performance of supervised learning techniques in classificationto on a real-world dataset.
Classification models under supervised learning techniques are trained and tested using **Breast Cancer Dataset** available in the **sklearn** library.

## Breast Cancer Wisconsin (Diagnostic) Dataset (WDBC)

The Breast Cancer Wisconsin (Diagnostic) dataset, commonly referred to as the WDBC dataset, is a well-known dataset in the field of machine learning and data analysis. It is frequently used for binary classification tasks, where the primary goal is to classify breast cancer tumors into two categories: malignant (cancerous) and benign (non-cancerous).
Dataset Overview

>Instances: 569 breast mass lesions      
 Malignant (cancerous): 212 (label = 0)      
 Benign (non-cancerous): 357 (label = 1)

### Features
The dataset contains 30 features, computed from the cell nuclei of breast mass lesions. These features are derived from various physical properties, including:
>   Radius<br>
    Texture<br>
    Perimeter<br>
    Area<br>
    Smoothness<br>
    Compactness<br>
    Concave points<br>
    Concavity<br>
    Symmetry<br>
    Fractal dimension<br>

For each feature, the dataset provides three values:
>   Mean<br>
    Standard error<br>
    Worst (largest) value

This results in a total of 30 features (10 features measured in triplicate).
### Usage

The WDBC dataset is widely used for training machine learning algorithms to distinguish between malignant and benign tumors based on the provided features.

**Note:** use  `from sklearn.datasets import load_breast_cancer` to import the dataset.
