# sms_spam_detection
📩 SMS Spam Detection System – Project Description  The SMS Spam Detection System is a machine learning-based project designed to automatically classify text messages as spam or ham (not spam). The goal of this project is to build an intelligent model that can detect unwanted and potentially harmful messages by analyzing their textual content.
🔹 Project Workflow:

Data Preprocessing
The raw SMS data is first cleaned and prepared for analysis. This step includes:

Converting text to lowercase

Removing punctuation and special characters

Eliminating stopwords

Tokenization

Stemming 

Data preprocessing ensures that the text is in a structured and meaningful format for model training.

Text Vectorization
Since machine learning models cannot process raw text directly, the cleaned text is transformed into numerical format using vectorization techniques such as:

Bag of Words (BoW)

TF-IDF (Term Frequency–Inverse Document Frequency)

This step converts textual data into feature vectors that represent the importance of words in each message.

Model Training & Prediction
A machine learning algorithm (such as Naive Bayes, Logistic Regression, or Support Vector Machine) is trained on the vectorized dataset.
Once trained, the model predicts whether a new incoming SMS message is:

Spam 🚫

Ham ✅

Output Generation
The system provides a clear classification result for each message, helping users filter spam automatically.

🎯 Key Features:

Automated spam detection

Efficient text preprocessing pipeline

Accurate prediction using trained ML model

Real-time message classification capability

🚀 Objective:

The main objective of this project is to enhance communication security by reducing spam messages using Natural Language Processing (NLP) and Machine Learning techniques.

I use multiple model but Multinomial Naive Bayes gives good accuracy and precision as 1(I consider precision as important) i also try to improve the model performance but it was not work the main top 5 model that  predict output correcect as compared to another are (KNeighborsClassifier,Naive bayyes,ExtraTree Classifier,random fores,Support vector machine)
