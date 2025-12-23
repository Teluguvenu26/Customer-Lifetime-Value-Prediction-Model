# Customer Lifetime Value (LTV) Prediction

## 📌 Project Overview
This project predicts the **Customer Lifetime Value (LTV)** based on purchase behavior.  
The goal is to help businesses segment customers into **Low, Medium, and High value groups** for targeted marketing.

## ⚙️ Tools & Libraries
- Python (Pandas, NumPy, Scikit-learn, XGBoost)
- Google Colab
- Matplotlib & Seaborn for visualizations
- Excel (for quick checks and CSV outputs)

## 🛠️ Steps Followed
1. **Data Preparation**  
   - Created sample transactions dataset (`transactions.csv`)  
   - Merged customer IDs with order history  

2. **Feature Engineering**  
   - Frequency (number of orders)  
   - Recency (days since last purchase)  
   - Average Order Value (AOV)  
   - Total Spend (used as target LTV)  

3. **Model Training**  
   - Used **XGBoost Regressor**  
   - Evaluated with **MAE** and **RMSE**  

4. **Customer Segmentation**  
   - Divided customers into 3 segments: Low, Medium, High value  

5. **Visualizations**  
   - Distribution of predicted LTV  
   - Boxplot of LTV by segment  
   - Feature importance chart  

6. **Final Output**  
   - Exported predictions to `customer_ltv_predictions.csv`  

## 📊 Results
- The model successfully predicts LTV values.  
- Customers are segmented into actionable groups for marketing.  
- Visualizations show clear differences between segments.  

## 📂 Deliverables
- `customer_ltv_prediction.ipynb` → Notebook with full code & outputs for readability
- `customer_ltv_prediction.py` → Notebook with full code & outputs for reusability
- `customer_ltv_predictions.csv` → Final predictions for each customer
- `README.md` → Project documentation 

## 🚀 How to Run
1. Open the notebook in **Google Colab**.  
2. Run all cells to generate predictions.  
3. Download the CSV file (`customer_ltv_predictions.csv`).  
4. Use the CSV for further analysis or marketing strategy.
