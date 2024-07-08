This project aims to predict loan eligibility based on applicant information using machine learning techniques. It utilizes a dataset containing various features such as gender, marital status, income, education, loan amount, and credit history.

1. Data Loading and Exploration:
   - Load the training dataset (`loan-train.csv`).
   - Explore the dataset using functions like `head()`, `shape`, `info()`, and `describe()`.
   - Visualize data distributions and relationships using histograms and box plots.

2. Data Preprocessing:
   - Handle missing values by filling them with mode or mean.
   - Transform categorical variables using label encoding.
   - Standardize numerical features using StandardScaler.

3. Model Training and Evaluation:
   - Split the dataset into training and testing sets.
   - Train a Decision Tree Classifier and a Gaussian Naive Bayes model.
   - Evaluate model performance using accuracy score.

4. Prediction on Test Data:
   - Load the test dataset (`loan-test.csv`).
   - Preprocess the test data similarly to the training data.
   - Use the trained Naive Bayes model to predict loan eligibility on the test data.

## Dependencies

- pandas
- numpy
- matplotlib
- scikit-learn

## Usage

1. Ensure the required libraries are installed.
2. Place the training and test datasets (`loan-train.csv` and `loan-test.csv`) in the project directory.
3. Run the provided Python code to train the models and make predictions.

## Results

The accuracy of the Decision Tree model and Naive Bayes model on the test data is printed in the output.

