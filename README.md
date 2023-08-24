# Advertisement Sale Prediction from Existing Customer

This Jupyter Notebook demonstrates the use of a Logistic Regression model for predicting whether a new customer will make a purchase based on their age and salary.

## Dataset

The dataset 'adsale.csv' is used for training and testing the model. The dataset includes customer information and whether they made a purchase (1 for Buy, 0 for Not Buy).

## Usage

1. Upload your dataset: Make sure the 'adsale.csv' file is uploaded to the same directory as the notebook.

2. Open the Jupyter Notebook in Google Colab.

3. Run the notebook: Execute the cells step by step to load the dataset, preprocess the data, train the Logistic Regression model, and make predictions.

4. Input new customer's information: The notebook prompts you to input a new customer's age and salary. The trained model then predicts whether the customer will make a purchase.

5. Evaluate the model: The notebook evaluates the model's performance by calculating accuracy and generating a confusion matrix for the test set.

## About the Project

This project demonstrates the following steps:

1. Loading and parsing the dataset using `pandas`.

2. Splitting the dataset into the feature matrix `X` and target vector `Y`.

3. Preprocessing the data by standardizing the features.

4. Creating a Logistic Regression model and training it on the standardized training data.

5. Predicting whether a new customer will make a purchase based on age and salary.

6. Evaluating the model's accuracy and generating a confusion matrix.

## Advantages

- **Predictive Insight**: The model provides valuable insights into whether a new customer is likely to make a purchase, allowing businesses to tailor their marketing strategies effectively.

- **Efficiency**: By utilizing existing customer data, the model can quickly assess potential buyers without extensive manual analysis.

- **Resource Optimization**: Targeted marketing efforts based on predictions can lead to resource optimization by focusing on customers more likely to convert.

- **Improved Customer Engagement**: Enhanced understanding of customer behavior helps in delivering personalized experiences and improving engagement.

## Input

The input consists of a new customer's age and salary for making predictions.

## Output

The output includes whether a new customer will make a purchase (Customer will Buy or Customer won't Buy) and the accuracy of the trained model.
