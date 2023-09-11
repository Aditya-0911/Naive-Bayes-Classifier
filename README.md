# Naive Bayes Classifier

- [Naive Bayes Theorem](#naive-bayes-theorem)
- [How to Use](#how-to-use)
- [Code Explanation](#code-explanation)
- [Dependencies](#dependencies)
- [Note](#note)

## Naive Bayes Theorem

The Naive Bayes theorem is a probabilistic theorem used for classification and prediction tasks. It's based on Bayes' theorem, which calculates the probability of an event based on prior knowledge of conditions that might be related to that event. In the context of classification, the Naive Bayes classifier calculates the probability of a data point belonging to a particular class given its features.

The "naive" part of the theorem refers to the assumption that the features used in the classification are independent of each other, which simplifies the calculations. In practice, this assumption may not always hold true, but Naive Bayes classifiers often perform well even when it is violated.

## How to Use

1. **Input File**: Provide the filename of your CSV dataset when using the script. Ensure that the dataset is well-structured, with a header row containing column names.

2. **Target Variable**: Enter the name of the target variable (the variable you want to predict) when prompted.

3. **Select Features**: Choose the factors (features) you want to include in the analysis. Input the numbers corresponding to the columns you want to use, separated by commas or as a range (e.g., "0,1,3,5" or "0:5").

4. **Training and Testing Data**: The script automatically splits the dataset into training (80%) and testing (20%) sets.

5. **Accuracy Metrics**: The script computes accuracy metrics for both the training and testing datasets, providing insights into the classifier's performance.

## Code Explanation

The provided Python code implements the Naive Bayes classifier. Here's a brief explanation of key components:

- **Data Preprocessing**: The code loads the dataset, allows users to select features, and prepares the data for classification.

- **Naive Bayes Classifier**: The `devdas` function calculates class probabilities using Gaussian Naive Bayes and predicts class labels for data points.

- **Accuracy Calculation**: The script computes accuracy metrics for both the training and testing datasets, providing insights into the classifier's performance.

## Dependencies

- `numpy`: For numerical operations.
- `pandas`: For data manipulation and DataFrame handling.
- `math`: For mathematical functions.
- `scipy`: For scientific and statistical computations.

## Note

While this script provides a basic implementation of the Naive Bayes classifier, for more complex classification tasks and specialized features, consider using dedicated machine learning libraries such as scikit-learn.

Enjoy using the Naive Bayes Classifier!
