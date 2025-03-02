# Classification Model for Bank Marketing Dataset

## Overview
This project builds a **classification model** using the **Bank Marketing dataset**, which predicts whether a client will subscribe to a term deposit. The model is based on a **Random Forest Classifier**, and feature importance is analyzed using **SHAP** (if available).

## Features & Workflow
- **Loads and preprocesses data** from `bank-additional-full.csv`
- **Encodes categorical features** using One-Hot Encoding
- **Scales numerical features** for better model performance
- **Trains a Random Forest model** for classification
- **Evaluates model performance** using accuracy scores
- **Analyzes global feature importance** with a bar plot
- **Provides local interpretability** using SHAP (if available)

## Installation
### Prerequisites
Ensure you have **Python 3.7+** installed. Then, install dependencies:

```bash
pip install pandas numpy scikit-learn matplotlib shap
```

## Usage
### Running the Model
Clone the repository and navigate to the project directory:

```bash
git clone https://github.com/PendyalaPradeepReddy/Pwc-Digital-Intelligence.git
```

Run the script:

```bash
python classification_model.py
```

### Expected Output
- Training and testing **accuracy scores**
- **Feature importance plot** (Top 10 features)
- **SHAP explanations** for observations #4 and #20 (if SHAP is installed)

## Handling SHAP Issues
If `shap` is missing, the script will automatically skip SHAP analysis without breaking.

## Dataset Information
- Source: https://www.kaggle.com/datasets/henriqueyamahata/bank-marketing
- The dataset contains **41,188 records** with **20 input features** + target variable (`y`).
- The `duration` feature is **excluded** as per dataset documentation.

## Contributing
Feel free to submit issues or pull requests to improve the model.

## License
This project is open-source under the **MIT License**.

