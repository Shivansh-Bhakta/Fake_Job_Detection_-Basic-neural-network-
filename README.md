# Fake Job Detection System (scikit-learn)

##  Overview
This project is a **Fake Job Detection System** built using **scikit-learn** and **Logistic Regression**.  
It classifies job postings as **Fake or Real** based on handcrafted behavioral and content-related features commonly observed in fraudulent job listings.

---

##  Problem Statement
Fake job postings often show suspicious patterns such as:
- Requests for processing or registration fees  
- Urgent or manipulative language  
- Missing or unclear company information  
- Absence of an official website  

The objective is to **automatically detect fraudulent job postings** using machine learning.

---

##  Approach
- Binary classification problem  
- Supervised learning  
- Strong emphasis on **manual feature engineering**  

Instead of relying only on raw text, this project uses **structured indicators** that represent real-world scam behavior.

---

## Features Used
Each job posting is represented using the following features:

- Internship / Job type  
- Internship duration  
- Interview conducted (Yes/No)  
- Processing fees required  
- Salary mentioned (Yes/No)  
- Stipend / Salary amount  
- Official website exists (Yes/No)  
- Grammar quality score  
- Company information clarity  
- Urgency-related words  
- Experience required  
- Job description length  

---

##  Model
- **Algorithm:** Logistic Regression  
- **Library:** scikit-learn  
- **Output Labels:**  
  - `1` → Real Job  
  - `0` → Fake Job  

Logistic Regression was selected for its **simplicity, interpretability, and effectiveness** in structured binary classification tasks.

---

##  Evaluation
- Data split into training and testing sets  
- Achieved approximately **84% accuracy**  
- Model behavior analyzed to understand correct and incorrect predictions  

> Accuracy may vary depending on dataset size and feature quality.

---

##  Tech Stack
- Python  
- scikit-learn  

---

##  Usage
1. Prepare job posting data using the same feature format  
2. Train the Logistic Regression model using scikit-learn  
3. Use the trained model to predict whether a job posting is Fake or Real  

---

##  Notes
- Feature order must remain **consistent** during training and prediction  
- This project focuses on **classical machine learning**, not deep learning  
- Designed for learning, experimentation, and concept demonstration  

---

##  Future Improvements
- Add TF-IDF–based text features  
- Integrate an LLM for semantic analysis  
- Increase dataset size and diversity  
- Deploy as a web application  

---


