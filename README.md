This Python code implements a spam message classification model using three different machine learning algorithms: Multinomial Naive Bayes (MNB), Complement Naive Bayes (CNB), and Linear Support Vector Classifier (SVC). It first loads and preprocesses the dataset of labeled spam and ham messages using TF-IDF Vectorization to convert the text into numerical format.

The dataset is split into training and testing sets (80%/20%). Each model is trained on the training data and then evaluated using accuracy scores and detailed classification metrics (precision, recall, F1-score). The LinearSVC model provides the best performance, achieving 99% accuracy.

The code also allows for testing the model by predicting the label for a custom message, for example, "hi how are you?", and it classifies it as either ham (non-spam) or spam.



