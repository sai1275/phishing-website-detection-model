# Phishing Website Detection using Machine Learning Techniques

This repository contains code and details regarding the detection of phishing websites using various machine-learning models and techniques. The project aims to classify URLs as legitimate or phishing based on extracted features using several supervised learning algorithms.

## Dataset

The dataset used in this project consists of extracted features from URLs, including aspects like URL length, depth, presence of specific elements (IP, '@' symbol, redirections, etc.), and more. It contains 10,000 instances with 16 features and a target column.

### Files

- `Phishing Website Detection_Feature Extraction.ipynb`: Notebook illustrating the process of feature extraction from URLs and storing the data in a CSV file.
- `5.urldata.csv`: Resulted CSV file containing the extracted features uploaded for analysis.

## Overview

1. **Loading Data**: Loading the pre-processed dataset and basic exploration to understand its structure and features.
2. **Visualizing the Data**: Data distribution through histograms and correlation heatmap to analyze feature relationships.
3. **Data Preprocessing & EDA**: Cleaning, handling missing values, and dropping irrelevant columns like 'Domain'.
4. **Splitting the Data**: Separating features and target column (Label) and splitting the dataset into training and testing sets (80-20 split).
5. **Machine Learning Models & Training**: Implementation and training of various supervised learning models for classification:
    - Decision Tree
    - Random Forest
    - Multilayer Perceptrons (Deep Learning)
    - XGBoost
    - Autoencoder Neural Network
    - Support Vector Machines

## Model Performance

The performance of each model was evaluated using accuracy metrics on both the training and testing datasets.

### Results

| Model                    | Train Accuracy | Test Accuracy |
|--------------------------|----------------|---------------|
| Decision Tree            | 0.810          | 0.826         |
| Random Forest            | 0.814          | 0.834         |
| Multilayer Perceptrons   | 0.858          | 0.863         |
| XGBoost                  | 0.866          | 0.864         |
| Autoencoder              | 0.819          | 0.818         |
| Support Vector Machines  | 0.798          | 0.818         |

## Instructions

1. Clone the repository: `git clone https://github.com/yourusername/phishing-website-detection.git`
2. Explore the Jupyter Notebooks to understand the process of feature extraction and machine learning models' implementation.
3. Feel free to experiment with different models, hyperparameters, or feature engineering techniques.

## Dependencies

- Python 3.x
- Libraries: pandas, numpy, seaborn, matplotlib, scikit-learn, xgboost, keras, tensorflow

## Acknowledgments

- Credits to [Dataset Source](https://datasourcewebsite.com) for providing the dataset used in this project.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Make sure to replace placeholders like image URLs, dataset sources, your username, and add more specific details about the dataset or models if necessary. Adjust formatting, add installation instructions if required, and include any additional sections relevant to your project.
