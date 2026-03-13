# CreditGuard-Fraud-Detection-System

CreditGuard is a machine learning powered fraud detection system designed to identify fraudulent credit card transactions using advanced data analysis and classification algorithms.

The system performs data exploration, preprocessing, model training, and fraud prediction through an interactive Streamlit dashboard, allowing users to analyze transaction behavior and test models in real time.

🚀 Features
📊 Exploratory Data Analysis (EDA)

CreditGuard provides interactive tools to understand the dataset:

Transaction distribution

Fraud vs legitimate transaction comparison

Missing value analysis

Duplicate detection

Statistical summaries

Visualization of transaction patterns

📈 Data Visualization

The system generates multiple analytical plots including:

Transaction class distribution

Time vs Amount scatter plots

Box plots for transaction amount

Histogram distribution for transaction features

Multivariate fraud pattern visualization

Libraries used:

Matplotlib

Seaborn

⚙️ Data Preprocessing

The project performs multiple preprocessing steps:

Train-test split (80/20)

Feature scaling using StandardScaler

Skewness correction using PowerTransformer

Duplicate removal

Class distribution analysis

🧠 Machine Learning Models

CreditGuard evaluates multiple classification algorithms:

Model	Purpose
Logistic Regression	Baseline fraud detection model
Naive Bayes	Probabilistic classification
Decision Tree	Rule-based classification

Each model is evaluated using:

Accuracy

Precision

Recall

F1-score

ROC-AUC Score

Confusion Matrix

📉 Model Performance Comparison

The system automatically compares models and visualizes:

Accuracy comparison charts

ROC curves

AUC scores

This helps determine the most effective fraud detection model.

🔎 Manual Transaction Verification

Users can manually enter transaction features to verify whether a transaction is:

✔ Legitimate
❌ Fraudulent

This simulates a real-world fraud detection interface.

🖥 Interactive Dashboard

The project uses Streamlit to create an interactive interface.

Sidebar sections include:

Dataset exploration

Fraud analysis

Model building

Algorithm comparison

Manual fraud verification

🧱 Tech Stack

Programming Language

Python

Machine Learning

Scikit-learn

Data Analysis

Pandas

NumPy

Visualization

Matplotlib

Seaborn

Web Interface

Streamlit

📂 Dataset

The system uses the Credit Card Fraud Detection Dataset, which contains:

284,807 transactions

31 features

Highly imbalanced dataset

Target variable:

Class
0 → Legitimate transaction
1 → Fraudulent transaction

Features V1–V28 are PCA-transformed for privacy.

⚙️ Installation

Clone the repository:

git clone https://github.com/yourusername/CreditGuard-Fraud-Detection-System.git
cd CreditGuard-Fraud-Detection-System

Install dependencies:

pip install -r requirements.txt

Required libraries:

pandas
numpy
matplotlib
seaborn
scikit-learn
streamlit
▶️ Running the Application

Run the Streamlit dashboard:

streamlit run app.py

Then open the browser:

http://localhost:8501
📊 Evaluation Metrics

Models are evaluated using:

Accuracy

Precision

Recall

F1 Score

ROC Curve

AUC Score

Confusion Matrix

These metrics help measure fraud detection effectiveness.

🔮 Future Improvements

Possible enhancements include:

Handling extreme class imbalance with SMOTE

Using Random Forest and XGBoost

Implementing Deep Learning fraud detection

Real-time transaction monitoring

API-based fraud detection service

Explainable AI (SHAP / LIME)

📜 License

MIT License

👨‍💻 Author

Kaushal Dholakiya

AI Developer | Cybersecurity Enthusiast | Machine Learning Engineer
