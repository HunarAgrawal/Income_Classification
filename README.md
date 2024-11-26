# Logistic Regression on Adult Income Dataset

This project demonstrates how to use **Logistic Regression** for classification tasks with the **UCI Adult Income Dataset**. The goal is to predict whether an individual earns more than $50K per year based on attributes like age, education, marital status, and more.

---

## Features

### 1. **Data Loading & Preprocessing**
- **Dataset**: The project uses the UCI Adult Income Dataset, which contains demographic information about individuals.
- **Handle Missing Values**: Missing values are handled by filling with the most frequent value for each column.
- **Categorical Variable Encoding**: Categorical variables are encoded using `LabelEncoder` to transform them into numerical values suitable for machine learning models.
- **Feature Scaling**: Features are standardized using `StandardScaler` to ensure that all features have the same scale, improving model performance.

### 2. **Model Training**
- The dataset is split into training and testing subsets.
- A logistic regression model is trained to predict whether an individual earns more than $50K.
- The model is evaluated using accuracy and a classification report, which includes precision, recall, and F1-score for each class.

### 3. **Model Evaluation**
- The model's performance is evaluated on a separate test set using accuracy and classification metrics from the `sklearn.metrics` library.
- The trained model is evaluated on the test data using metrics such as accuracy, precision, recall, and F1-score.
- These metrics provide insight into the model's performance in correctly predicting the income class.

### 4. Predictions & Output
- The predictions on the test dataset are showing the actual vs. predicted income classes.

### 5. **Saving Predictions**
- The model's predictions on the test set are saved to a CSV file for future analysis.


Overall, this project shows how to implement a machine learning classification task, evaluate its performance, and save the results for future reference. It provides a hands-on understanding of preprocessing, model training, and evaluation in a real-world context.

---

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/HunarAgrawal/Income_Classification.git
   cd Income_Classification

2. Install the required Python libraries:
   ```bash
   pip install pandas scikit-learn

---

## Usage

1. Run the script to train the Logistic Regression model and evaluate it:
   ```bash
   python logistic_regression.py

2. After running the script, the performance metrics and the predictions will be printed in the terminal.
3. A CSV file (test_predictions.csv) will be created containing the actual and predicted income classes for the test set.

---

## File Descriptions

- logistic_regression.py: Main script containing all steps, including loading the dataset, preprocessing, model training, evaluation, and saving predictions.
- test_predictions.csv: CSV file containing the actual vs. predicted income classes for the test set.

---

## Dependencies

- Python 3.x or higher
- Libraries: pandas, scikit-learn

---

## Contributing

Contributions are welcome! If you have suggestions, improvements, or bug fixes, please fork the repository, make your changes, and submit a pull request.

---

## License

This project is licensed under the MIT License. See the LICENSE file for more details.

---

## Author

Hunar Agrawal

---

## Acknowledgments

Special thanks to the UCI Machine Learning Repository for providing the Adult Income dataset.
