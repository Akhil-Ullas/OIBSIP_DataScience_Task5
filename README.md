# 📧 Email Spam Detector (Python + Machine Learning)

This project implements a **Spam Email Detector** using Python, Scikit-learn, and Plotly.  
The model is trained on the classic `spam.csv` dataset, where emails are classified into **Ham (not spam)** or **Spam**.  

### 🚀 Features
- Data preprocessing with **TF-IDF Vectorization**  
- Model training using **Naive Bayes Classifier**  
- Performance evaluation (Accuracy, Classification Report, Confusion Matrix)  
- **Interactive visualizations** with Plotly  
- A function to test **custom emails** for spam detection  

### 📊 Example
```python
sample_email = "Congratulations! You've won a $1000 gift card. Click here to claim."
print(check_email(sample_email))  # Output: Spam
🔧 Tech Stack

Python

Scikit-learn

Pandas

Plotly
