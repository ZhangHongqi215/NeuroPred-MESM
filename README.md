# NeuroScale
## Introduction

NeuroScale integrates advanced machine learning techniques with biological insights to address the challenges of neuropeptide prediction, which is critical for understanding various physiological and behavioral functions. This tool stands out due to its capability to handle diverse and complex data, providing robust predictions with high accuracy.

## Features

- **High Performance**: Utilizes state-of-the-art algorithms for high accuracy and performance.
- **Multi-Level Feature Extraction**: Incorporates GoogLeNet architectures for rich feature extraction.
- **User-Friendly**: Provides an easy-to-use Python interface for both training and predictions.
- **Extensive Documentation**: Detailed documentation to help users get started quickly.

## Installation

```bash
# Clone the repository
git clone https://github.com/ZhangHongqi215/NeuroScale.git

# Navigate to the project directory
cd NeuroScale

# Install the required dependencies
pip install -r requirements.txt




## Usage

The main code for the NeuroScale model is contained in the `NeuroScale.ipynb` notebook. Here is a step-by-step guide to using the notebook:

### Step 1: Load the Data

Load the dataset containing protein sequences and their labels (NPs or not). The dataset should be formatted as described in the notebook.

### Step 2: Feature Extraction

Run the cells responsible for extracting features from the protein sequences using ESM2. The notebook includes detailed comments explaining each step.


### Step 3: Model Training

Train the multi-channel neural network model using the extracted features. The notebook demonstrates how to train the model and evaluate its performance.


### Step 4: Model Evaluation

Evaluate the performance of the model using various metrics such as accuracy, precision, recall, F1 score, and MCC. The notebook provides code for generating ROC and PRC curves as well.


### Step 5: Model Interpretability

Use t-SNE and SHAP to visualize and interpret the model's predictions. The notebook includes examples of how to apply these techniques.
