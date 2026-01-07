# sms_spam_detection
The SMS Spam Detection project uses machine learning to classify SMS messages as "ham" (legitimate) or "spam" (unwanted). It includes data cleaning, exploratory analysis, text preprocessing, and model evaluation. The project addresses class imbalance, and future work involves model optimization, real-time processing, and deployment  Resources
### Introduction

The SMS Spam Detection project is designed to classify SMS messages as either "ham" (legitimate) or "spam" (unwanted or malicious). By leveraging machine learning and natural language processing (NLP), this system aims to filter out spam messages, improving user experience and security.

### Objectives

The main objectives include data cleaning, exploratory data analysis (EDA), text preprocessing, model building, evaluation, and deployment. The goal is to develop an effective machine learning model to classify SMS messages as spam or ham.

### Dataset

The dataset consists of 5,572 SMS entries, with a target label indicating whether the message is spam (1) or ham (0). After cleaning, the dataset is reduced to 5,169 entries. The data is imbalanced, with ham messages comprising 87.37% and spam messages 12.63%.

### Data Cleaning

Data cleaning involves removing unnecessary columns, renaming them for clarity, handling missing values, and eliminating duplicates. The target labels are encoded using LabelEncoder, converting "ham" messages to 0 and "spam" messages to 1.

### Exploratory Data Analysis (EDA)

EDA reveals important characteristics of the dataset, such as the average message length, word count, and sentence count. It shows that spam messages are generally longer and more complex compared to ham messages. A visual representation of class distribution is created, showcasing the imbalance.

### Text Preprocessing

Text preprocessing involves tokenization, removal of stopwords, and converting text into a format suitable for machine learning models. Features like message length, word count, and sentence count are also extracted for analysis.

### Model Building and Evaluation

Machine learning models, including Naive Bayes, Logistic Regression, and Random Forest, are trained on the preprocessed data. Evaluation metrics such as accuracy, precision, recall, and F1-score are used to assess the model’s performance, with cross-validation techniques for better generalization.

### Future Work

Future work will focus on optimizing the model, handling real-time message processing, and deploying the solution through a web interface or API. Advanced techniques and handling class imbalance will also be explored for improved accuracy.
