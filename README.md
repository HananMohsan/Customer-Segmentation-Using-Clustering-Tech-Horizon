#  Customer Segmentation Using Machine Learning

This project applies **unsupervised learning (K-Means clustering)** to segment mall customers based on their demographic and spending attributes.  
The goal is to uncover hidden patterns in customer behavior that businesses can leverage for **targeted marketing and customer retention strategies**.

---

##  Dataset
- **Source**: Mall Customers Dataset (200 entries)
- **Features**:
  - `CustomerID`
  - `Gender`
  - `Age`
  - `Annual Income (k$)`
  - `Spending Score (1–100)`

---

## Approach
1. **Data Preprocessing**
   - Checked for missing values (none found).
   - Focused on **Annual Income** and **Spending Score** for clustering.
   
2. **Clustering**
   - Applied **K-Means** algorithm.
   - Used the **Elbow Method** to identify optimal clusters (`k = 5`).
   
3. **Visualization**
   - Scatter plots used to represent clusters for interpretability.

---

##  Challenges
- **Feature selection dilemma** → including all variables reduced cluster clarity.  
- **Subjectivity in Elbow Method** → interpreting the optimal number of clusters.  
- **Interpretability** → required business context to label clusters.  
- **Dataset size** → small sample (200 records) limits generalization.

---

##  Outcomes
The model identified **5 distinct customer segments**:

1. **Low Income – Low Spending** → Price-sensitive customers.  
2. **High Income – Low Spending** → Wealthy but disengaged customers.  
3. **Average Income – Average Spending** → Moderate shoppers.  
4. **High Income – High Spending** → Premium, high-value customers.  
5. **Low Income – High Spending** → Aspirational shoppers (often younger).  

**Business Value**: Enables better **targeted marketing, product placement, and retention strategies**.

---

##  Results Visualization
Sample cluster visualization:

*(screenshot/plot from notebook can be added here)*

---

## 🛠 Technologies Used
- Python 🐍
- Pandas, NumPy
- Matplotlib, Seaborn
- Scikit-learn

---

##  How to Run
1. Clone this repository:
   ```bash
   git clone https://github.com/HananMohsan/Customer-Segmentation.git
   cd Customer-Segmentation
