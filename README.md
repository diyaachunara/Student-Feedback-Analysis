#📊 College Event Feedback Analysis – Data Science Internship Project

This project analyzes a complete student dataset containing demographics, geographic information, academic grades, and application-quality ratings.  
The goal is to perform **Exploratory Data Analysis (EDA)** and generate insights about student performance, diversity, and application strength.

---

## 📂 Dataset Overview

The dataset consists of the following columns:

### 👤 Personal & Demographic Information
- **id** — Unique student ID  
- **name** — Full name  
- **nationality** — Country of origin  
- **city** — Current city  
- **latitude** — City latitude  
- **longitude** — City longitude  
- **gender** — Male / Female  
- **ethnic.group** — Ethnic background (mostly missing values)  
- **age** — Student age  

### 📚 Academic Grades (0–4 GPA Scale)
- **english.grade**  
- **math.grade**  
- **sciences.grade**  
- **language.grade**

### 📝 Application Ratings (0–5 Scale)
- **portfolio.rating**  
- **coverletter.rating**  
- **refletter.rating**

---

## 🛠 Technologies Used
- Python  
- Pandas  
- NumPy  
- Seaborn  
- Matplotlib  
- Google Colab  

---

## 🔧 Project Workflow

### **1️⃣ Load the dataset**
```python
import pandas as pd

df = pd.read_csv("student-dataset.csv")
df.head()
