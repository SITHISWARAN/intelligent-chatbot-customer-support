# 🤖 AI Chatbot for Customer Support

This project aims to revolutionize customer support by creating an AI-driven chatbot that can automatically classify customer queries into intents using Natural Language Processing (NLP). The chatbot helps businesses provide 24/7 assistance, reduce response times, and improve customer satisfaction.

---

## 🚀 Features

- Intent classification using advanced NLP models
- Preprocessing pipeline: cleaning, lemmatization, and vectorization (TF-IDF)
- Trained on real and synthetic customer support data
- Text-based chatbot interface (runs directly in Google Colab)
- Fully offline: no external deployment required

---

## 🛠️ Technologies Used

- Python
- Scikit-learn
- spaCy
- Joblib
- Pandas, NumPy
- Google Colab

---

## 🧠 Workflow

1. **Data Preparation**  
   Load a dataset of labeled customer queries (intent classification only).

2. **Preprocessing**  
   Clean text, remove stop words, and apply lemmatization.

3. **Vectorization**  
   TF-IDF vectorization is applied to convert text into numerical format.

4. **Model Training**  
   Logistic Regression and Random Forest used for classification. BERT optionally used for fine-tuning.

5. **Evaluation**  
   Accuracy, F1-score, and confusion matrix used to evaluate performance.

6. **Chatbot Interface**  
   Run a text-based chatbot directly in Colab and interact with the model.

---

## 📁 Files in This Repository

| File               | Description                                      |
|--------------------|--------------------------------------------------|
| `dataset.csv`      | Sample dataset with customer queries and intents |
| `source_code.py`   | Code to train the model and save artifacts     |
| `chatbot_colab_demo.py` | Full Colab chatbot script                    |
| `README.md`        | This file                                        |

---

## 📦 How to Run (Google Colab)

1. Upload `Dataset.csv`,file to Colab.
2. Run `Source code.py` to start chatting.


## 📬 License

This project is open for academic and non-commercial use only.
