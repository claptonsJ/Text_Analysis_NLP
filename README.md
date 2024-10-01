**Introduction**

This project aims at solving a real world in the internet age we are today. The internet and social media platforms have become our daily communication tools in the modern world, enabling the exchange of ideas and opinions. However, the rise of toxic online behavior, such as harassment, hate speech, and abusive comments, has become a significant concern for individuals, and organizations. The impact of such behavior can range from emotional distress to widespread misinformation, creating a harmful online environment that enhances trolling.

The objective of this project is to build two machine learning models that can classify comments as either toxic or non-toxic based on the content of the text. Using a dataset of social media comments, we applied natural language processing (NLP) techniques, trained a logistic regression and Naive Bayes classification model to predict toxicity. 
The automatic detection and classification of toxic comments have become critical tasks. While many platforms rely on human moderators to manage inappropriate content, these manual methods are time-consuming, subjective, and difficult to scale. Machine learning offers a solution by automating the process of identifying toxic language with greater speed and accuracy, thereby supporting moderation efforts and improving online interactions.

**Process Workflow**
1. Importing necessary libraries.
2. Loading training and test datasets.
3. Data cleaning and Text preprocessing.
4. Machine Learning models training and evaluation.
5. Predicting toxic/non-toxic comments in test data.
6. Saving Prediction file in csv format

A key challenge in this project is the inherent imbalance in the dataset, where non-toxic comments significantly outnumber toxic ones. To address this, the Synthetic Minority Over-sampling Technique (SMOTE) was used to balance the classes, ensuring a more effective model training process. This approach, combined with feature selection, logistic regression, and Naive Bayes Classification forms the core methodology of this project.
