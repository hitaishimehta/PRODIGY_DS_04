# 📊 PRODIGY_DS_04 – Sentiment Analysis on Amazon Reviews

## 📌 Internship Task

This project is part of my **Data Science Internship at Prodigy InfoTech**.
Task-04 focuses on analyzing and visualizing sentiment patterns in social media or review data.

---

## 🎯 Objective

To analyze customer reviews and understand public sentiment (Positive, Neutral, Negative) across different product categories.

---

## 📂 Dataset

* Custom Amazon Product Reviews dataset
* Contains 300+ reviews
* Columns:

  * `reviewText` – Customer review
  * `overall` – Rating (1–5)
  * `productCategory` – Category (Electronics, Fashion, Grocery)

---

## ⚙️ Workflow

### 1. Data Preprocessing

* Converted text to lowercase
* Removed special characters and noise

### 2. Sentiment Classification

* Ratings mapped to sentiment:

  * 4–5 → Positive
  * 3 → Neutral
  * 1–2 → Negative

### 3. Visualization

* Bar chart for sentiment distribution
* Category-wise sentiment analysis
* Word Cloud for frequent terms

---

## 📊 Results & Insights

* Most reviews are **positive**, showing customer satisfaction
* Negative reviews highlight issues like product quality and delivery
* Different product categories show varying sentiment patterns

---

## 🛠️ Tools & Technologies

* Python
* Pandas
* Matplotlib
* WordCloud
* Jupyter Notebook
