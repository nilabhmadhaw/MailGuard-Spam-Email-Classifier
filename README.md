# MailGuard 🛡️  
### Spam Email Classifier using Machine Learning

MailGuard is a machine learning–based spam email classification system that detects whether an email is **Spam** or **Ham (Not Spam)**.  
The project uses **TF-IDF vectorization** for text feature extraction and **Logistic Regression** for classification.

---

## 🚀 Features
- Text preprocessing and cleaning
- TF-IDF based feature extraction
- Spam vs Ham classification
- Logistic Regression model
- Model evaluation using accuracy
- Custom email prediction support

---

## 🧠 Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- Jupyter Notebook

---

## 📂 Dataset
The dataset contains labeled email messages with two categories:
- `spam`
- `ham`

Each record includes:
- **Category** → spam / ham  
- **Message** → email text

---

## ⚙️ Workflow
1. Load and clean the dataset
2. Encode labels (`spam → 0`, `ham → 1`)
3. Split data into training and testing sets
4. Convert text into numerical features using **TF-IDF**
5. Train a **Logistic Regression** model
6. Evaluate model performance
7. Test with custom email input

---

## 📊 Model Evaluation
The model is evaluated using:
- Training Accuracy
- Testing Accuracy

(Additional metrics like Precision, Recall, and F1-score can be added.)

---
## 📈 Results

The model successfully classifies spam and non-spam emails

Performs well on unseen email data

Suitable as a beginner-to-intermediate NLP project

## 🔮 Future Improvements

Add confusion matrix and classification report

Compare with Naive Bayes classifier

Hyperparameter tuning

Save and load model using joblib

Deploy using Streamlit or Flask

## 👨‍💻 Author

Nilabh Madhaw Mishra
B.Tech CSE (AI & ML)
Aspiring AI/ML Engineer
