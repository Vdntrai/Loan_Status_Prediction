
# Loan Prediction System using SVM

This repository implements a machine learning system to predict loan approvals using a Support Vector Machine (SVM) classifier. The system leverages historical loan application data to build a model that can assess the risk of default for new loan requests.

### Key Features:

- **Data Exploration and Visualization:**
    - Analyzes the loan dataset using countplots to visualize the distribution of categorical features (e.g., loan status, income bracket).
- **Data Preprocessing:**
    - Handles missing values (e.g., imputation techniques).
    - Encodes categorical features (e.g., one-hot encoding).
    - Scales numerical features (e.g., standardization).
- **Train-Test Split:**
    - Splits the preprocessed data into training and testing sets to ensure unbiased model evaluation.
- **SVM Model Training:**
    - Trains an SVM classifier using optimal hyperparameters (potentially explored through grid search or other techniques).
- **Model Evaluation:**
    - Calculates performance metrics like accuracy, precision, recall, and F1-score to assess the model's effectiveness.
- **Loan Prediction:**
    - Provides a function or script to predict loan approvals for new loan applications based on the trained model.

### Dependencies:

- Python 3.x ([https://www.python.org/downloads/](https://www.python.org/downloads/))
- scikit-learn ([https://scikit-learn.org/](https://scikit-learn.org/))
- matplotlib ([https://matplotlib.org/](https://matplotlib.org/))
- pandas ([https://pandas.pydata.org/](https://pandas.pydata.org/))

### Installation:
1. Clone this repository: `git clone https://github.com/<your-username>/loan-prediction-svm.git`
2. Install required libraries: `pip install -r requirements.txt` (if provided)

### Usage:

1. Run the main script (e.g., `python main.py`) to perform data exploration, training, evaluation, and prediction.
2. Alternatively, explore individual scripts for specific functionalities (e.g., `data_exploration.py`, `model_training.py`, `prediction.py`). Customize these scripts according to your project structure.

### Data:

The system expects a CSV file containing historical loan application data with relevant features (e.g., applicant information, loan amount, credit history). Ensure the data is formatted correctly and includes column headers. You can replace the placeholder data with your actual dataset.

### Prediction System:

The prediction system allows you to input new loan application data (e.g., through a user interface or script) and receive a predicted loan approval status based on the trained model.
