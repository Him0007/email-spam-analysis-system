# 📧 Email Spam Analysis System

This project is a simple email spam detection system built using **Python, Machine Learning, and Flask**.  
It checks whether a given email or message text is **Spam** or **Not Spam (Ham)** and also shows how confident the model is about its prediction.

The main purpose of this project is to understand how text classification works and how a machine learning model can be used in a real web application.

---

## 🔍 What This Project Does

- Takes email or message text as input
- Analyzes the content using machine learning
- Predicts whether the message is **Spam** or **Not Spam**
- Shows the spam confidence score
- Allows testing with random messages from the dataset

---

## 🛠 Tools and Technologies Used

- **Python** – core programming language  
- **Flask** – for building the web application  
- **Scikit-learn** – for machine learning model  
- **Pandas** – for handling the dataset  
- **HTML & CSS** – for the user interface  

---

## 📊 Dataset Information

- Uses the **SMS Spam Collection Dataset**
- Messages are already labeled as `spam` or `ham`
- If the dataset is not found locally, it is downloaded automatically

---

## ⚙️ How It Works (In Simple Terms)

1. The dataset is loaded and cleaned
2. The text is converted into numbers using **TF-IDF**
3. A **Naive Bayes** model is trained on the data
4. The user enters an email or message
5. The system predicts whether it is spam and shows the confidence

---

## ▶️ How to Run This Project

### Step 1: Clone the Repository
```bash
git clone https://github.com/him0007/email-spam-analysis-system.git
cd email-spam-analysis-system

---
