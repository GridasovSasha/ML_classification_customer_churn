# ML | Predicting сustomer сhurn using Logistic Regression

<p align="center">
  <img src="images_to_report\image.png" width="400">
</p>

In this project, I implemented predicting customer churn for a telecommunications company using logistic regression.

Link to the data used in the project from the kaggle website: https://www.kaggle.com/datasets/blastchar/telco-customer-churn

Remark: comments in the code will be written in Russian

## IDA, feature transformation and ML model development
[main](main.ipynb) - The main code of the program is presented in this notebook. I conducted exploratory data analysis, encoding categorical features using DictVectorizer from the sklearn library. I used a ready-made implementation of the logistic regression model from the sklearn library - LogisticRegression.

## Result
The trained model was tested on a dedicated test data set and showed 82% accuracy.
