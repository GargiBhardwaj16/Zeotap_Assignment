
# 🛒 Customer Analytics and Insights

This repository contains an end-to-end data analysis project that leverages exploratory data analysis (EDA), lookalike modeling, and customer segmentation to derive actionable business insights from customer, product, and transaction data.

---

## 📁 Project Structure

- **`Customers.csv`**: Contains customer information, including regions and signup dates.
- **`Products.csv`**: Includes product details, such as categories and pricing.
- **`Transactions.csv`**: Tracks transaction history with purchase details.

### Key Features:
1. **Exploratory Data Analysis (EDA)**:
   - Uncovers customer behavior, product trends, and transaction patterns.
   - Provides innovative insights to improve business decision-making.
   - Visualizations for better understanding.

2. **Lookalike Model**:
   - Recommends 3 similar customers for a given user based on their profile and transaction history.
   - Uses cosine similarity for precise recommendations.
   - Outputs similarity scores.

3. **Customer Segmentation**:
   - Clusters customers using K-Means based on transactional and profile data.
   - Evaluates clusters with the Davies-Bouldin Index.
   - Provides visualizations to explain segmentation patterns.

---

## 🚀 Tasks and Deliverables

### Task 1: Exploratory Data Analysis
**Objective**: Analyze the dataset and derive meaningful business insights.
- Conducted detailed EDA with visualizations.
- Identified key patterns in customer transactions, product categories, and seasonal trends.

**Deliverable**:
- Jupyter Notebook/Python script with EDA code.
- PDF report summarizing actionable insights.

---

### Task 2: Lookalike Model
**Objective**: Build a model to recommend similar customers.
- Utilized customer profiles and transaction data for similarity computation.
- Generated top 3 lookalikes for the first 20 customers.

**Deliverable**:
- Python script with model development.
- `Lookalike.csv` containing recommendations for CustomerID C0001–C0020.

---

### Task 3: Customer Segmentation
**Objective**: Segment customers into distinct clusters.
- Implemented K-Means clustering on normalized customer profiles.
- Evaluated clusters with the Davies-Bouldin Index.
- Visualized clusters for business interpretation.

**Deliverable**:
- Python script with clustering code.
- `Customer_Clusters.csv` containing cluster assignments.
- Visualization plots of clusters.

---

## 📊 Business Insights
- **Top-performing products**: Products contributing 80% of revenue (Pareto analysis).
- **Customer lifetime value**: Identified high-value customers contributing significantly to total revenue.
- **Seasonality**: Detected seasonal transaction spikes in specific months.
- **Region analysis**: Highlighted regions driving maximum revenue.
- **Repeat purchases**: Found strong affinity for specific product-customer pairs.

---

## 🛠️ Tools & Technologies
- **Programming**: Python
- **Libraries**: Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn
- **Clustering Metrics**: Davies-Bouldin Index
- **Similarity Measurement**: Cosine Similarity

---

## 📂 Repository Files
- `eda_lookalike_clustering.py`: Main script containing all tasks.
- `Business_Insights.pdf`: Report summarizing EDA and insights.
- `Lookalike.csv`: Recommendations for similar customers.
- `Customer_Clusters.csv`: Clustering results with labels.

---


## 🔮 Future Improvements
- Implement additional clustering methods (DBSCAN, Hierarchical Clustering).
- Enhance lookalike model using advanced NLP techniques on customer reviews.
- Integrate demographic and geographic data for deeper analysis.

---

## 🤝 Contributing
Contributions are welcome! Feel free to submit a pull request or open an issue for discussion.

---

## 📄 License
This project is licensed under the MIT License. See `LICENSE` for more details.

---

### 🌟 Give a ⭐ if you like this project!
