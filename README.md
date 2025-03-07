# Spam Email Classifier: A Machine Learning Approach using TF-IDF and Logistic Regression also Random Forest for comparison
This project classifies emails as spam or not spam using Machine Learning techniques.
We use **TF-IDF** for feature extraction and **Logistic Regression and Random Forest** for classification.
## Dataset
The dataset used for training the model is from [Kaggle - Spam Email Dataset](https://www.kaggle.com/datasets/venky73/spam-mails-dataset).

# Clone the repository
git clone https://github.com/sewasewT7/Spam_Email_Classifier.git
cd spam_email_classifier

# Install required Python libraries
pip install -r requirements.txt

## How to Use
1. Open `Email Spam.ipynb` in Google Colab or Jupyter Notebook.
2. Run all cells to train the model.
3. To classify new emails, modify `test_email = "Your email text here"` and run the prediction function.

## Results
- Accuracy: **99%**
- Precision: **97%**
- Recall: **99%**
- F1-score: **98%**

## Future Improvements
- Implement **feature selection** to reduce dataset size and training time.
- Deploy as a simple web app using Flask.
