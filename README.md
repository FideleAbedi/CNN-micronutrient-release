# CNN-micronutrient-release
A Convolutional Neural Network (CNN) based tool for predicting micronutrient release patterns. This project utilizes image processing techniques on fluorescence microscopic images to model and analyze the release behavior of bioactive compounds in yeast cells.

# Project Title: Image-Based Release Pattern Prediction with Pre-trained CNN

## Overview

### Introduction
This project uses a pre-trained Convolutional Neural Network (CNN) for predicting release patterns of bioactive compounds in yeast cells, based on fluorescence microscopic images. The approach involves transfer learning, data augmentation, and visualization techniques like t-SNE.

### Results
The model's effectiveness in predicting release patterns was validated through. Visualization of the neuron outputs at various layers was performed using t-SNE, providing insights into the model's functioning.

## Usage

### Setup
- **Development Environment**: Developed in a Python environment.
- **Dependencies**: Requires Python libraries such as numpy, pandas, seaborn, matplotlib, TensorFlow, and Keras. Use of Keras Tuner for hyperparameter tuning.
- **Data**: Image data of yeast cells loaded from specified directories.

### Running the Project
To reproduce the results:

**Step 1**: Clone the repository and navigate to the project directory.
```bash
git clone https://github.com/your-repo.git
cd your-project-directory
### Step 2: Set up the Python environment and install the required dependencies.
```bash
pip install numpy pandas seaborn matplotlib tensorflow keras keras-tuner
### Step 3: Run the provided Python script to train the model.
```python
# Python code to load data, train, and visualize the model
# (Refer to the provided Python script for detailed steps)
