# Breast Cancer Data Analysis

## Project Overview

This project focuses on analyzing breast cancer data to develop predictive models using machine learning techniques. The primary goals are to perform data cleaning, feature selection, and model building, ultimately culminating in an interactive application that allows users to explore insights and predictions.

### Key Objectives:
- **Data Cleaning:** Ensured the dataset is free from inconsistencies and missing values.
- **Feature Selection:** Identified the most relevant features for model training.
- **Model Building:** Developed and trained machine learning models, specifically using artificial neural networks.
- **Interactive Visualization:** Created a user-friendly interface for data visualization and model interaction.

## Data Description

The dataset includes various attributes related to breast cancer diagnosis, such as tumor characteristics and patient information. This data is used to classify tumors as either benign or malignant.

## Setup Instructions

### Prerequisites

The following software installed:

- **Python 3.7 or higher**
- Required Python libraries:
  - `pandas` 1.5.3
  - `numpy` 1.23.5
  - `scikit-learn` 1.1.3
  - `tensorflow` 2.11.0
  - `streamlit` 1.16.0
  - `matplotlib` 3.6.2
  - `seaborn` 0.12.1

### Installation

1. **Clone the Repository:**
   ```sh
   git clone https://github.com/Bronia-John29/Breast_cancer_data_analysis.git
   ```

2. **Navigate to the Project Directory:**
   ```sh
   cd Breast_cancer_data_analysis
   ```

3. **Install the Required Libraries:**
   ```sh
   pip install -r requirements.txt
   ```

## Code Description

### Python Scripts

- **`data_preparation.py`:** Handled the data cleaning process, including dealing with missing values and outliers.
- **`feature_selection.py`:** Performed feature selection to identify the most important features for model training.
- **`ann_model.py`:** Built and trained an Artificial Neural Network (ANN) model for breast cancer prediction.
- **`model_tuning.py`:** Provided tools to fine-tune model parameters for optimal performance.

### Notebooks

- **`data_preprocessing.ipynb`:** Jupyter Notebook detailing the data cleaning and preprocessing steps.
- **`feature_selection.ipynb`:** Jupyter Notebook that walks through the feature selection process.
- **`model_building.ipynb`:** Jupyter Notebook demonstrating the process of building and training the ANN model.

### Streamlit App

- **`app.py`:** A Streamlit application that offers an interactive interface for users to visualize data insights and interact with the predictive model.

## Usage

To run the Streamlit application and explore the model's predictions:

```sh
streamlit run app.py
```

Once the command is executed, the web browser will open the application, allowing us to interact with the model and visualize the output.

## Project Structure

The project is organized as follows:

```
Breast_cancer_data_analysis/
│
├── data_preparation.py
├── feature_selection.py
├── ann_model.py
├── model_tuning.py
├── app.py
├── data_preprocessing.ipynb
├── feature_selection.ipynb
├── model_building.ipynb
├── breast_cancer_data.csv
├── breast_cancer_data_selected.csv
├── requirements.txt
└── README.md
```
