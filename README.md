# AI-Powered Revenue Forecasting & Customer Segmentation

This repository contains the final project and data science workflow developed for the **GCI World 2026 Final Assignment**. The project builds an end-to-end machine learning pipeline to predict customer monthly revenue, segment customers based on value, and drive targeted retention and marketing strategies in the telecommunications industry.

---

## 🚀 Project Overview
In the highly competitive telecommunications market, acquiring new customers costs significantly more than retaining existing ones[cite: 1]. This project addresses critical business challenges by transforming historical customer usage and demographic data into actionable insights:
- **Revenue Prediction:** Accurately forecasting a customer's average monthly revenue (`avgrev`) using machine learning.
- **Customer Segmentation:** Grouping customers into distinct tiers (Platinum, Gold, Silver, Bronze) to optimize marketing spend and VIP support[cite: 1].
- **Churn Risk Identification:** Detecting early warning signs of customer decline before churn occurs[cite: 1].

---

## 📊 Dataset
- **Size:** 100,000+ customer records[cite: 1].
- **Structure:** Merged from two primary datasets (`Client.csv` and `Record.csv`) on `Customer_ID`[cite: 1].
- **Features:** Includes usage metrics (minutes of use, calls, roaming), account details, and service data.

---

## 🛠️ Tech Stack & Libraries
- **Programming Language:** Python 3.x
- **Environment:** Google Colab / Jupyter Notebook
- **Libraries Used:**
  - **Data Manipulation:** `pandas`, `numpy`
  - **Data Visualization:** `matplotlib`, `seaborn`
  - **Machine Learning & Evaluation:** `scikit-learn`, `xgboost` (utilizing `HistGradientBoostingRegressor`)[cite: 1]

---

## 📈 Key Workflow & Methodology
1. **Data Preprocessing & Cleaning:** Merged client and record datasets, handled missing values, and dropped leaky columns to prevent data leakage.
2. **Model Training:** Trained a robust `HistGradientBoostingRegressor` model on 80% of the dataset[cite: 1].
3. **Model Evaluation & Validation:** Achieved an **$R^2$ Score of 0.8275** on the test set with minimal overfitting gap (0.0446), proving high stability and reliability[cite: 1].
4. **Customer Tiering:** Segmented the customer base into:
   - **Platinum (Top 5%):** High-value clients generating 20% of total revenue[cite: 1].
   - **Gold (Next 15%):** Strong contributors requiring loyalty programs and upgrades[cite: 1].
   - **Silver (Next 30%):** Mid-tier users targeted with family plans and bundles[cite: 1].
   - **Bronze (Bottom 50%):** Maintained through automated low-cost channels[cite: 1].

---

## 💡 Business Impact & ROI
- **Revenue Lift:** Projected +15% increase in monthly revenue[cite: 1].
- **Retention Improvement:** +5% reduction in churn rate through early detection[cite: 1].
- **Marketing Optimization:** -20% reduction in marketing spend by shifting from mass campaigns to targeted outreach[cite: 1].
- **Overall ROI:** Estimated **3x return on investment** within the first year[cite: 1].

---

## ⚙️ How to Run the Code
1. Clone the repository:
   ```bash
   git clone [https://github.com/kyaw-koko/GCI-bag.git](https://github.com/kyaw-koko/GCI-bag.git)
