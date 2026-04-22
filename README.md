# 🔐 Prompt Injection Detection (AI Security Project)

## 📌 Overview

This project detects malicious / jailbreak prompts in LLM inputs using a hybrid ML + Deep Learning approach.

## ⚙️ Tech Stack

* Python
* LightGBM
* PyTorch (BiLSTM + Attention)
* TF-IDF (Word + Character)
* Scikit-learn

## 🧠 Model Architecture

* TF-IDF (word + char features)
* Metadata features (length, special chars, jailbreak patterns)
* LightGBM classifier
* BiLSTM + Attention neural network
* Final prediction = Ensemble (50% LGBM + 50% DL)

## 📊 Results

* F1 Score: XX.XX
* Accuracy: XX.XX
* Precision: XX.XX

## 📁 Dataset

Kaggle Competition Dataset: Prompt Injection Detection

## 🚀 How to Run

```bash
pip install -r requirements.txt
python src/train.py
```

## 📸 Output

* Confusion Matrix
* Feature Importance
* Prediction Distribution

## 🔍 Key Highlights

* 5-Fold Stratified Cross Validation
* Custom Tokenizer
* Attention Mechanism
* Feature Engineering for jailbreak detection

## 📬 Author

Sejal Wadibhasme
