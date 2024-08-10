# Breast_cancer_data_analysis

## Project Overview
This project aims to analyze breast cancer data using machine learning techniques to build predictive models and visualize insights. The main objectives include data cleaning, feature selection, model building, and creating an interactive application for users.

### Data Description
The dataset used in this project contains breast cancer data, including various features related to the diagnosis and characteristics of the tumors.

## Setup Instructions

### Prerequisites
- Python 3.7 or higher
- Libraries:
   - `pandas` 1.5.3
   - `numpy` 1.23.5
   - `scikit-learn` 1.1.3
   - `tensorflow` 2.11.0
   - `streamlit` 1.16.0
   - `matplotlib` 3.6.2
   - `seaborn` 0.12.1

### Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/Bronia-John29/Breast_cancer_data_analysis.git
   ```
2. Navigate to the project directory:
   ```sh
   cd Breast_cancer_data_analysis
   ```
3. Install the required libraries:
   ```sh
   pip install -r requirements.txt
   ```

## Code Description

### Python Scripts

- **data_preparation.py**: Handles data cleaning and preprocessing.
- **feature_selection.py**: Selects important features for the model.
- **ann_model.py**: Builds and trains an artificial neural network model.
- **model_tuning.py**: Tunes model parameters for better performance.

### Streamlit App
- **app.py**: A Streamlit application to visualize data insights and interact with the predictive model.

## Usage
To run the Streamlit app and interact with the predictive model:

```sh
streamlit run app.py
```
