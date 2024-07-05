# Email Spam Detection

## Project Description

This project uses machine learning techniques to classify emails as spam or not spam. It includes data preprocessing, feature scaling, and model training using Logistic Regression. The dataset used is balanced with the Synthetic Minority Over-sampling Technique (SMOTE) to address class imbalance. Performance metrics such as accuracy, confusion matrix, and classification report are provided to evaluate the model.

### Key Components

1. **Data Collection and Preprocessing**:
   - Load and inspect the dataset.
   - Visualize the count of spam and non-spam emails.

2. **Feature Selection and Scaling**:
   - Select relevant features for model training.
   - Standardize features using `StandardScaler`.

3. **Handling Class Imbalance**:
   - Apply SMOTE to balance the dataset.

4. **Model Training**:
   - Train a Logistic Regression model with balanced class weights.

5. **Model Evaluation**:
   - Evaluate the model using accuracy, confusion matrix, and classification report.

### Dependencies

- `pandas`
- `numpy`
- `matplotlib`
- `scikit-learn`
- `imblearn`

### Usage

For a better understanding of this code, download the code file along with the dataset file and run it in your Jupyter Notebook.

### Contributor

- [Jaweria](https://github.com/jaweria15)

Feel free to contribute or raise issues for further improvements.
