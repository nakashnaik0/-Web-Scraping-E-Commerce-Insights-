🛒 Web Scraping & E-Commerce Purchase Prediction

This project demonstrates a complete pipeline for analyzing customer purchase behavior on an e-commerce platform inspired by Flipkart. Due to scraping restrictions and ethical compliance, a realistic dataset was **simulated using GenAI tools** to reflect real-world product listings.

The objective is to uncover key patterns influencing customer decisions and build a **Logistic Regression** model to predict the likelihood of purchase based on product features.

---

## 🔍 Project Overview

- **Domain**: E-commerce  
- **Technique**: Logistic Regression (Classification)  
- **Data**: AI-generated simulation of Flipkart-style product listings  
- **Goal**: Identify factors that influence customer purchases  

---

## 📂 Files Included

| File Name               | Description                                           |
|------------------------|-------------------------------------------------------|
| `web_scraping_ecom.ipynb` | Complete Python notebook: simulation → EDA → modeling |
| `visuals_output.pdf`      | High-quality visual charts and insights              |
| `README.md`               | Project documentation (you are here)                 |

---

## 🧰 Tools & Libraries Used

- **Python 3.x**
- `Pandas`, `NumPy` – data manipulation  
- `Seaborn`, `Matplotlib` – data visualization  
- `Scikit-learn` – machine learning (Logistic Regression)

---

## 📊 Simulated Dataset Features

| Column Name       | Description                                |
|-------------------|--------------------------------------------|
| Product_Name      | Product title                              |
| Category          | Type of product (e.g., Mobile, Laptop)     |
| Rating            | User rating (1.0 – 5.0)                    |
| Price             | Product price (INR)                        |
| Discount (%)      | Percentage discount offered                |
| Seller_Trust      | Categorical flag (High / Low trust seller) |
| Fast_Delivery     | Whether delivery is fast (Yes / No)        |
| Purchased         | **Target** variable (1 = Bought, 0 = Not)  |

> **Note:** This dataset was entirely AI-generated to simulate a realistic Flipkart product listing and purchase scenario.

---

## 🧠 Key Steps Performed

### ✅ 1. Data Generation  
- Used GenAI tools to simulate a dataset closely mirroring Flipkart electronics listings

### ✅ 2. Preprocessing  
- Cleaned inconsistent formats  
- Converted categorical variables using encoding techniques  
- Removed outliers and standardized features

### ✅ 3. Exploratory Data Analysis (EDA)  
- Analyzed relationships between ratings, discounts, price, and purchase decisions  
- Created correlation matrix and key visual charts

### ✅ 4. Modeling  
- Built a **Logistic Regression** model to predict the likelihood of purchase  
- Evaluated using accuracy, confusion matrix, and feature importance

### ✅ 5. Visualizations  
- Correlation heatmaps  
- Bar plots showing influence of discount, trust, and ratings on purchase  
- Distribution plots and purchase patterns
