#  Customer Insight & Segmentation Studio

A Machine Learning web application built with **Streamlit** that helps businesses analyze customer data, perform customer segmentation using **K-Means Clustering**, visualize clusters, and predict the cluster of new customers.

---

##  Features

-  Upload any CSV dataset
-  Preview uploaded dataset
-  Summary statistics
-  Missing value analysis
-  Correlation matrix
-  Distribution charts
-  Feature selection for clustering
-  Automatic preprocessing
  - Missing value handling
  - Label Encoding
  - Feature Scaling
-  Automatic Optimal K selection using Elbow Method
-  Customer Segmentation using K-Means Clustering
-  Interactive Cluster Visualization
-  Cluster Insights
-  Customer Profile Generation
-  Predict the cluster for a new customer

---

##  Technologies Used

- Python
- Streamlit
- Pandas
- Matplotlib
- Scikit-learn
- KMeans Clustering
- Kneed

---

##  Project Structure

```
Customer-Insight-Studio/
│
├── app.py
├── requirements.txt
├── Mall_Customers.csv
├── README.md
```

---

##  Installation

### 1. Clone the repository

```bash
git clone https://github.com/yourusername/Customer-Insight-Studio.git
```

### 2. Navigate to the project

```bash
cd Customer-Insight-Studio
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the application

```bash
streamlit run app.py
```

---

##  Dataset

This project is demonstrated using the **Mall Customers Dataset**.

Dataset Features:

- CustomerID
- Gender
- Age
- Annual Income (k$)
- Spending Score (1-100)

---

##  Workflow

1. Upload CSV dataset
2. Explore dataset statistics
3. Select clustering features
4. Find the optimal number of clusters using the Elbow Method
5. Perform K-Means clustering
6. Visualize customer segments
7. Analyze cluster insights
8. Predict the cluster for a new customer

---

##  Future Improvements

- Download clustered dataset as CSV
- 3D cluster visualization
- PCA dimensionality reduction
- Support for multiple clustering algorithms
- Save trained model
- Better cluster interpretation
- Interactive dashboards using Plotly

---

##  Requirements

```
pandas
streamlit
scikit-learn
matplotlib
kneed
```

---

##  Author

**Namita Bone**

GitHub: https://github.com/yourusername

LinkedIn: https://linkedin.com/in/yourprofile

---

##  License

This project is licensed under the MIT License.

---

##  If you like this project

If you found this project useful, consider giving it a star on GitHub!
