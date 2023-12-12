# DDOS-detection
# Random Forest Classifier for Network Traffic Classification

## Overview

This project utilizes a Random Forest Classifier to predict network traffic normality based on various features extracted from packet data. The dataset is preprocessed and additional features are engineered for better model performance.

## Table of Contents

1. [Dataset](#dataset)
2. [Code Structure](#code-structure)
3. [Usage](#usage)
4. [Results](#results)
5. [Dependencies](#dependencies)
6. [License](#license)

## Dataset

The dataset used in this project is stored in a CSV file, 'Preprocessed_data.csv', and is located in the Google Drive directory '/content/drive/MyDrive/Colab Notebooks/'. The features include packet length, IP length, TCP length, packets per second, bytes per second, mean packet size, and interarrival time.

## Code Structure

The main Python script is provided in the Jupyter Notebook 'Untitled0.ipynb'. It consists of the following sections:

- **Mount Google Drive:** Mounts Google Drive to access the dataset file.
- **Read Data:** Reads the preprocessed dataset into a Pandas DataFrame.
- **Feature Engineering:** Adds additional features such as packets per second, bytes per second, mean packet size, and interarrival time.
- **Data Imputation:** Handles missing values using the mean imputation strategy.
- **Model Training:** Utilizes a Random Forest Classifier to train the model.
- **Model Evaluation:** Evaluates the model using accuracy, confusion matrix, and classification report.

## Usage

1. Open the Jupyter Notebook in Google Colab by clicking on the provided link.
2. Run each cell in the notebook sequentially.

## Results

The model is evaluated on a test set, and the results are printed in terms of accuracy, confusion matrix, and classification report.

## Dependencies

The following Python libraries are used in this project:

- `google.colab`
- `pandas`
- `sklearn`

Make sure to install these dependencies before running the code.

```bash
pip install google-colab pandas scikit-learn
