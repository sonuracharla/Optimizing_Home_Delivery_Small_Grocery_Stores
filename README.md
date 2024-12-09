
# Optimizing Home Delivery in Small Grocery Stores  
**A Data-Driven Strategy for Customer Segmentation and Marketing**

## ✨ Overview
This project investigates how small grocery stores can leverage data analytics to optimize customer engagement, retention, and marketing strategies. Using RFM analysis, K-Means clustering, and machine learning models for churn prediction, this study provides actionable insights for improving customer retention and targeted marketing.

---

## 🛠 Objectives
1. **RFM Analysis**: Quantify customer engagement using Recency, Frequency, and Monetary metrics.
2. **Customer Segmentation**: Segment customers into actionable groups (e.g., loyal, at-risk) using K-Means clustering.
3. **Churn Prediction**: Predict disengaged customers using machine learning models like Logistic Regression, Random Forest, and Gradient Boosting.
4. **Insights and Recommendations**: Develop targeted marketing strategies for each customer segment.

---

## 📊 Methods and Techniques
- **RFM Analysis**: Customers are analyzed based on:
  - **Recency**: Days since the last purchase.
  - **Frequency**: Total number of transactions.
  - **Monetary**: Total spending value.
- **K-Means Clustering**:
  - Used to segment customers into 4 clusters (Loyal, At-Risk, Moderate, Occasional).
  - Optimal clusters determined using the Elbow Method.
  - Silhouette Score: **0.601**.
- **Churn Prediction**:
  - Models used: Logistic Regression, Random Forest, Gradient Boosting.
  - Achieved **100% accuracy** with Recency as the most critical feature (based on feature importance).

---

## 🧰 Technologies
- **Languages**: Python  
- **Libraries**: 
  - Data Manipulation: `pandas`, `numpy`
  - Visualization: `matplotlib`, `seaborn`
  - Machine Learning: `scikit-learn`
- **Tools**: Jupyter Notebook

---


---

## 📈 Key Results
1. **RFM Analysis**:
   - Segmented customers based on their engagement and spending patterns.
   - Identified clusters:
     - **Loyal Customers**: High frequency and monetary value, low recency.
     - **At-Risk Customers**: High recency, low frequency and monetary value.
2. **Clustering**:
   - Four customer groups identified using K-Means clustering, validated with a silhouette score of **0.601**.
3. **Churn Prediction**:
   - Models achieved **100% accuracy** in predicting churn.
   - Recency was the most important feature, contributing over **85%** of the model's predictive power.

---

## 🌟 Insights and Recommendations
- **Loyal Customers (Cluster 0)**:
  - Offer loyalty rewards and exclusive deals to retain these customers.
- **At-Risk Customers (Cluster 3)**:
  - Focus on re-engagement campaigns like personalized discounts or reminder emails.
- **Occasional Buyers (Cluster 2)**:
  - Upsell with time-sensitive offers to encourage more frequent purchases.

---

## 🔮 Future Work
1. **Real-Time Analytics**: Implement a real-time pipeline for dynamic customer segmentation.
2. **Incorporate Additional Data**: Add demographic and behavioral data for deeper insights.
3. **Scalability Testing**: Apply methods to larger datasets or multi-store environments.

---




