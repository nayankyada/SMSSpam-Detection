# SMSSpam-Detection
As it is evident that usage of mobile phone has been increased there is a dramatic
increase in Spam SMS.So its very difficult for the mobile messaging company to manually
classify it in either spam sms or not.So here supervised machine learning algorithm will help us
by learning spam sms data to classify new sms as spam or not.
In this all machine learning algorithm works on numerical datasets and we have data in
text form so we need to convert this data into numerical form by applying some data
preprocessing technique.Data preprocessing task compose some natural language processing
tasks for data cleaning.After successfully cleaning data we need to convert this text data into
numerical vector.
## Steps:
1. Data Loading
2. Basic EDA for given datasets
3. Data Cleaning
4. Data preprocessing
5. Choose Machine Learning model based on requirements
6. Analys all ML model all output and performance metrics
Refer : SMSSpam.ipynb or SMSSpam.ipynb
## Conclusion:
After performing all above operations:
1. Given SMSSpam data set is imbalanced dataset because no of spam text datapoint are
large as compared to ham text datapoint.
2. All models perform best for spam text data point because data set contain various spam
text.
3. Its two class (ham,spam) classification problem so we can measure performance by
confusion metrics.
4. LogisticRegression gives 96% accuracy on test data
5. RandomForest gives 97% accuracy on test data
6. LSTM model of deep learning gives 98% accuracy on test data
