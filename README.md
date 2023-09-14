
# Email Spam Detection Using Logistic Regression 📧🚫



## Background 🌐


In today's digital age, we are inundated with a deluge of emails. To combat the flood of unwanted messages, email services employ spam detection algorithms. One effective method for identifying spam emails is Logistic Regression. This technique leverages various attributes of emails to construct a model capable of classifying them as spam or not.

## Purpose 🎯

The primary aim of this project is to harness the power of email attributes, such as sender and recipient information, to create a Generalized Linear Model. We then apply the logit function to this model, converting its output into probabilities. These probabilities, derived from email characteristics, serve as indicators of the likelihood that an email is spam.

## Methods 🛠️

- We begin with a dataset containing 21 attributes.
- Categorical data is converted into numerical data through one-hot encoding.
- The dataset is split into training and testing sets with an 80/20 ratio.
- Using Python's `statsmodels` library, we construct a Generalized Linear Model linked to the logit function.
- The model is trained on the training dataset.

## Results 📊

- The model produces probabilities that signify whether an email is spam or not.
- A threshold of 0.50 (50%) is used to classify emails.
- The model exhibits an accuracy ranging from 90% to 95%, dependent on random data splits.
- Additional metrics like precision, sensitivity, specificity, and others are computed to evaluate the model's performance.

## Conclusion 🎉

Our logistic regression model, built on diverse email attributes, demonstrates reliability. With its impressive accuracy and robust performance metrics, we confidently assert its effectiveness in distinguishing spam emails from legitimate ones.

For more details, please visit [this website](https://balnarendrasapa.github.io/spam_classification/docs/intro). 🌐

