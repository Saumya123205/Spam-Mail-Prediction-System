# Spam-Mail-Prediction-System
🔍 Objective:
 To create a system that accurately classifies emails as either Spam or Ham (Not Spam), improving email safety and user productivity.

📁 Dataset Overview:
Dataset: mail_data.csv containing 5,572 email records.
Columns: Message (email content), Category (label as ham or spam).

⚙️ Project Workflow:
🧹 Data Preprocessing:
✅ Checked for and confirmed no missing values.
✅ Encoded categorical labels using LabelEncoder (Spam = 1, Ham = 0).
✅ Split the data into 80% training and 20% testing sets.

🧠 Feature Extraction:
🧮 Utilized TF-IDF Vectorizer to convert email text into numerical vectors.
🧹 Applied transformations such as stopword removal and lowercase conversion.

🧪 Model Development:
⚙️ Implemented a Logistic Regression model from scikit-learn.
📈 Trained the model on TF-IDF-transformed text data.

📊 Model Evaluation:
🎯 Training Accuracy: 96.76%
🎯 Testing Accuracy: 96.68%
✅ The model shows strong generalization with minimal overfitting.

🚀 Deployment-Ready Prediction System:
📥 Built a real-time prediction function to classify any new email as Spam or Ham.

📌 Key Takeaways:
💡 TF-IDF is highly effective in representing text for machine learning tasks.
💡 Logistic Regression, despite its simplicity, performs excellently for binary classification problems when paired with strong feature engineering.
💡 The model is lightweight and can be deployed in real-time applications.

🧰 Tools & Technologies Used:
🐍 Python
📦 Pandas, NumPy
🔧 Scikit-learn (LogisticRegression, TfidfVectorizer, LabelEncoder)
🧪 Jupyter Notebook
