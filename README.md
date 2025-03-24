# Spam SMS Detection

## 📌 Overview
This project builds an SMS classification model that identifies spam messages using Naïve Bayes and other machine learning techniques.

## 🚀 Features
- Uses **TF-IDF vectorization** for text processing.
- **Handles imbalanced data** using **SMOTE**.
- Implements **Naïve Bayes, Hybrid Models, and Classification Threshold Tuning**.
- Evaluates robustness with **adversarial obfuscation**.

## 🛠️ Setup & Installation
To run this project locally:

1. Clone the repository:
git clone https://github.com/RiddhikaTripathi/Spam-SMS-Detection.git cd Spam-SMS-Detection

2. Install dependencies:
pip install -r requirements.txt


3. Run the notebook:
- Open `Spam_SMS_Detection.ipynb` in Jupyter Notebook or Google Colab.

## 📊 Model Performance
| Model Variation | Accuracy | Precision | Recall | F1-Score |
|---------------|---------|----------|--------|---------|
| Baseline Naïve Bayes | 0.97 | 1.00 | 0.81 | 0.90 |
| Naïve Bayes (Alpha) | 0.98 | 0.98 | 0.85 | 0.91 |
| Naïve Bayes + SMOTE | 0.96 | 0.84 | 0.91 | 0.87 |
| SMOTE + Classification Threshold | 0.98 | 0.84 | 0.91 | 0.87 |
| **Hybrid Model (Best)** | **0.98** | **1.00** | **0.85** | **0.92** |

## 📄 License
This project is licensed under the MIT License.

