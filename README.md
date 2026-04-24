🧬 Cancer Patient Analysis and Prediction

A Machine Learning project that analyzes patient medical data to accurately predict whether a tumor is benign or malignant, enabling early diagnosis and supporting healthcare decision-making.

📌 Overview

Early detection of cancer significantly improves treatment outcomes, but manual diagnosis can be time-consuming and prone to errors. This project leverages machine learning techniques to automate cancer prediction using diagnostic features.

Problem Statement: Build a predictive model to classify tumors based on medical attributes.
Objective: Develop a reliable classification system for early cancer detection.
Approach: Data preprocessing, exploratory data analysis (EDA), feature selection, and model building using supervised learning algorithms.

🎯 Target
Type: Binary Classification

Classes:
Benign (Non-cancerous)

Malignant (Cancerous)

📊 Dataset
Source: Breast Cancer Dataset

Features Include:

Radius
Texture
Perimeter
Area
Smoothness

Size: ~500+ records with multiple numerical features

🛠️ Tech Stack

Programming Language: Python

Libraries:

Pandas
NumPy
Scikit-learn
Matplotlib
Seaborn

Tools:

Google Colab
Jupyter Notebook

⚙️ Project Workflow

Data Collection & Loading
Data Preprocessing

Handling missing values
Feature scaling

Exploratory Data Analysis (EDA)
Model Building

K-Nearest Neighbors (KNN Classifier)
Model Evaluation

Prediction & Results Visualization

🚀 Getting Started
▶️ Run in Google Colab

Open the project directly:
👉 https://colab.research.google.com/drive/1acUZrfQnyTaIAv5Ul8tvk5W2ay2OrO8t?usp=sharing

▶️ Run Locally

git clone https://github.com/Sathiyap123/cancer-patient-analysis-and-prediction.git

cd cancer-patient-analysis-and-prediction

pip install -r requirements.txt

python cancer_prediction.py

📈 Results & Evaluation

Algorithm Used:
K-Nearest Neighbors (KNN)

Performance Metrics:

Accuracy
Precision
Recall
F1-Score

Result:

Achieved high accuracy (~98–99%)
Model effectively distinguishes between benign and malignant cases

Visualizations:

Confusion Matrix
Feature Correlation Heatmap
Distribution Plots

📁 Project Structure

├── data/              
├── notebooks/         
├── models/            
├── src/               
├── cancer_prediction.py
└── README.md

🌟 Key Highlights

End-to-end ML pipeline implementation
High accuracy classification model
Clean data preprocessing and visualization
Practical healthcare application

📄 License

This project is licensed under the MIT License.

🙌 Acknowledgements
Open-source dataset providers
Scikit-learn documentation
Machine Learning community

🔮 Future Work

Apply advanced models like Random Forest and SVM
Improve accuracy with hyperparameter tuning
Use larger real-world datasets
Deploy as a web application

✅ Conclusion

This project uses machine learning to predict cancer effectively.
The KNN model achieved high accuracy, showing its usefulness for early detection and healthcare support.
