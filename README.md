Project Title: Customer Segmentation & Lifetime Value Prediction

Objective:
The project aimed to analyze customer behavior to segment users based on their purchasing patterns and to predict customer lifetime value (CLTV). This helps businesses make informed decisions about where to focus marketing efforts and how to retain valuable customers.

1. Data Understanding & Preprocessing:
   The dataset contained customer purchase records. Initial steps involved cleaning the data by removing null values and duplicates. New features such as recency (days since last purchase), frequency (total number of purchases), and monetary value (total amount spent) were created. Outliers were handled to maintain model accuracy.

2. RFM Analysis:
   RFM stands for Recency, Frequency, and Monetary value. Customers were scored based on these metrics. The RFM scores were used to categorize customers into types such as loyal, at-risk, champions, or churn-prone. This segmentation helps companies focus on retaining valuable customers and re-engaging inactive ones.

3. K-Means Clustering:
   To automate customer segmentation, K-Means clustering was applied to the standardized RFM data. The elbow method and silhouette scores were used to find the optimal number of clusters. Each resulting group represented a unique type of customer with shared behavior traits, enabling more precise targeting.

4. Customer Lifetime Value Prediction:
   Supervised learning models were trained to predict CLTV based on RFM metrics and other variables like average order value and customer age. Models used included linear regression, ridge and lasso regression, and random forest regression. These models helped estimate how much value a customer would bring in the future.

5. Tools and Libraries Used:
   The project used Python with libraries including Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn, and Yellowbrick for clustering diagnostics and model evaluation.

Outcome:
The project delivered actionable customer segments and predicted future customer value. These insights are useful for targeted promotions, customer retention strategies, and long-term profitability. It also demonstrated the practical application of both unsupervised and supervised machine learning techniques in business analytics.
