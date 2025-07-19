# SMS Spam Detector using Naive Bayes

This project builds a machine learning model to classify SMS messages as **Spam** or **Ham** using the **SMS Spam Collection Dataset**. It applies a **Naive Bayes Classifier** with `CountVectorizer` to analyze text and detect spam.

---

## What’s Included

- Data cleaning and label encoding (Spam = 1, Ham = 0)
- Train/test split of the dataset
- Text vectorization using `CountVectorizer`
- Model training with `MultinomialNB`
- Evaluation with:
  - Accuracy score
  - Confusion matrix
  - Classification report (Precision, Recall, F1)
- Testing with custom input messages

---

## Key Results

- Achieved high accuracy on test data (based on the dataset)
- Successfully predicts spam messages with good confidence
- Custom input support to classify any new SMS as Spam or Ham

---

## Tech Stack

- Python  
- Pandas, Matplotlib  
- Scikit-learn (Naive Bayes, CountVectorizer, Metrics)

---

## Dataset

- **SMS Spam Collection** from UCI Machine Learning Repository
- Format: CSV  

---

## How It Works

1. Loads and processes SMS data
2. Vectorizes text into numerical features
3. Trains Naive Bayes model on message contents
4. Evaluates model performance
5. Allows real-time testing with your own messages

---

## 🧪 Example Usage

**python**
your_texts = ["you won a reward prize for free", "im good wbu?"]

**Output:** 
you won a reward prize for free = Spam  
im good wbu? = Ham 
