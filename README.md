# MACHINE-MODEL-IMPLEMENTION
COMPANY: CODTECH IT SOLUTIONS

NAME: JAKKAM SRAVAN

INTERN_ID:CT08UDR

DOMAIN:PYTHON

DURATION: 4 WEEKS

MENTOR:NEELA SANTHOSH KUMAR

Machine learning model implementation involves several key steps: data collection, preprocessing, feature extraction, model selection, training, evaluation, and deployment. In this project, we implemented a spam detection model using Scikit-Learn.

First, we loaded the SMS Spam Collection dataset, which contains labeled messages as "spam" or "ham" (non-spam). We then preprocessed the data by converting labels into binary values (0 for ham, 1 for spam) and splitting it into training and testing sets. Next, we applied feature extraction using the TF-IDF (Term Frequency-Inverse Document Frequency) vectorizer to convert text messages into numerical representations.

For model selection, we chose the Naïve Bayes classifier, which is well-suited for text classification tasks. The model was trained using the processed training data and then tested on unseen messages. To evaluate performance, we calculated accuracy, precision, recall, and F1-score, and visualized the confusion matrix.

The results showed that the model effectively distinguishes spam from non-spam messages. This approach can be extended to other text classification tasks, such as sentiment analysis and fake news detection.

OUTPUT:
<img width="1680" alt="Image" src="https://github.com/user-attachments/assets/3069ffca-683b-455b-9fc6-2901723a1f40" />
