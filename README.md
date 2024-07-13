# Machine Learning Projects: Datasets and Analysis

This repository contains Jupyter Notebooks showcasing hands-on experience with machine learning using popular datasets and the scikit-learn framework. The notebooks cover basic analysis, visualization, regression, and classification tasks on three commonly used datasets: Boston Housing, Iris, and Breast Cancer.

## Datasets

### 1. Boston Housing Dataset
- **Description**: This dataset contains information collected by the U.S Census Service concerning housing in the area of Boston, Massachusetts.
- **Analysis**: Exploratory data analysis (EDA) including statistical summaries and visualizations to understand relationships between various features and house prices.
- **Datset**: https://www.cs.toronto.edu/~delve/data/boston/bostonDetail.html

### 2. Iris Dataset
- **Description**: A classic dataset for classification, it consists of measurements of various iris flowers.
- **Analysis**: EDA to explore the distribution of iris species and their characteristics. Classification models are built to predict the species based on petal and sepal measurements.
- **Datset**: https://archive.ics.uci.edu/dataset/53/iris

### 3. Breast Cancer Dataset
- **Description**: This dataset contains features computed from a digitized image of a fine needle aspirate (FNA) of a breast mass. The goal is to classify whether the mass is benign or malignant.
- **Analysis**: EDA to understand the distribution of features and their relationship with cancer type. Classification models are trained to predict the malignancy of breast masses.
- **Datset**: https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data

## Notebooks

- **Boston_Housing_Analysis.ipynb:** Explore the Boston Housing dataset, perform EDA, and build a regression model to predict house prices.
- **Iris_Classification.ipynb:** Analyze the Iris dataset, visualize data, train a classification model to distinguish between the three iris species.
- **Breast_Cancer_Classification.ipynb:** Investigate the Breast Cancer dataset, apply EDA, and create a classification model to classify breast masses.
- **wine_quality_dataset.ipynb:** Experiment with PyTorch, use the Wine Quality dataset to build a regression model for predicting wine quality.
- **torch_vision_on_FashionMNIST.ipynb:** Employ PyTorch for computer vision, train a CNN model on the Fashion-MNIST dataset to classify clothing types.

## Dependencies

- Python 3
- Jupyter Notebooks
- NumPy
- Pandas
- Matplotlib
- Scikit-learn

## Usage

1. Clone the repository:

    ```bash
    git clone https://github.com/nadunnr/Dataset_Exploration_ML-Models.git
    ```
    
2. Go to the directory:

    ```bash
    cd Dataset_Exploration_ML-Models
    ```
    
3. Install the dependencies:

    ```bash
    pip install -r requirements.txt
    ```

4. Open and run the Jupyter Notebooks to explore the datasets and execute machine learning tasks.

    ```bash
    jupyter notebook
    ```
