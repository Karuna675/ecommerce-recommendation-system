# E-Commerce Product Recommendation System

## 📌 Problem Statement
In e-commerce platforms, recommending relevant products improves user experience and increases sales.
The goal of this project is to build a recommendation system that suggests products to customers based on their past purchase behavior.

---

## 📊 Dataset
- Online Retail Dataset (UCI / Kaggle)
- ~400,000 transaction records
- Features include InvoiceNo, StockCode, Description, Quantity, CustomerID, InvoiceDate, UnitPrice

---

## 🧹 Data Cleaning
- Removed transactions with missing CustomerID
- Excluded cancelled invoices
- Filtered out zero or negative quantities
- Converted CustomerID to integer format

---

## 🧠 Recommendation Approach
- Built a **user–item interaction matrix**
- Applied **user-based collaborative filtering**
- Used **cosine similarity** to identify similar customers
- Recommended products based on average purchase behavior of similar users

---

## 🎯 Output
- Generated top-N product recommendations for a given customer
- Enhanced interpretability by mapping product codes to product names

---

## 🛠️ Tech Stack
- Python
- Pandas, NumPy
- Scikit-learn
- Jupyter Notebook

---

## 🚀 Future Improvements
- Item-based collaborative filtering
- Matrix factorization (SVD)
- Streamlit web app for real-time recommendations
