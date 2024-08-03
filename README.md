# classification-challenge
## Background
Let's say you work at an Internet Service Provider (ISP) and you've been tasked with improving the email filtering system for its customers. You've been provided with a dataset that contains information about emails, with two possible classifications: spam and not spam. The ISP wants you to take this dataset and develop a supervised machine learning (ML) model that will accurately detect spam emails so it can filter them out of its customers' inboxes.

You will be creating two classification models to fit the provided data, and evaluate which model is more accurate at detecting spam. The models you'll create will be a logistic regression model and a random forest model.

## Solution 

The dataset contains various features related to word and character frequencies in emails, as well as a target column (`spam`) indicating whether an email is spam (1) or not spam (0).

the below steps have beeen performedon the data:

1. **Preprocess the Data**: Clean and prepare the data for modeling.
2. **Split the Data**: Separate the dataset into training and testing sets.
3. **Train the Models**: Train a logistic regression model and a random forest model on the training set.
4. **Evaluate the Models**: Assess the performance of both models using the testing set.
5. **Compare the Models**: Determine which model performs better based on accuracy and other relevant metrics.

## Results 

RandomForestClassifier performed better with the 96% accuracy compare to logistic regression.

Looking at the data we predicted Logistic Regression will perform better as we have binary class type of data.
However results prove differently.
