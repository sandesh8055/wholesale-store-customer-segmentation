# Wholesale Store Customer Segmentation using Agglomerative Clustering

## 📌 Project Overview
This project applies **Hierarchical (Agglomerative) Clustering** to segment wholesale store customers based on their annual spending behavior across different product categories. The goal is to identify meaningful customer groups for better business insights.

---

## 📂 Datasets Used

### 1️⃣ Diabetes Dataset (for Dendrogram Demonstration)
Used initially to demonstrate hierarchical clustering and dendrogram visualization.

**Features include:**
- Pregnancies
- Glucose
- Blood Pressure
- Skin Thickness
- Insulin
- BMI
- Age
- Outcome

---

### 2️⃣ Wholesale Customers Dataset
Main dataset used for customer segmentation.

**Features include:**
- Channel
- Region
- Fresh
- Milk
- Grocery
- Frozen
- Detergents_Paper
- Delicassen

---

## ⚙️ Technologies Used
- Python
- NumPy
- Pandas
- Scikit-learn
- SciPy
- Matplotlib
- Jupyter Notebook / Google Colab

---

## 🔍 Methodology
1. Loaded and explored datasets using Pandas
2. Performed exploratory data analysis
3. Built **dendrograms** using hierarchical clustering (Ward linkage)
4. Determined optimal number of clusters visually
5. Applied **Agglomerative Clustering**
6. Assigned cluster labels to customers
7. Interpreted customer segments

---

## 📊 Visualization
- Dendrograms used to visualize hierarchical cluster formation
- Helps identify optimal number of clusters
- Clear segmentation based on spending patterns

---

## 🚀 Results
- Customers successfully grouped into meaningful clusters
- Identified different purchasing behaviors across customer groups
- Demonstrated practical application of hierarchical clustering

---

## 📁 Project Structure
wholesale-store-customer-segmentation/

│
├── data/
│ ├── diabetes.csv
│ └── wholesale_customers_data.csv
│
├── notebooks/
│ └── Wholesale_store_cluster_Agglomerative_Clustering.ipynb
│
├── README.md

---

## 🧠 Key Learning Outcomes
- Understanding hierarchical clustering concepts
- Interpreting dendrograms
- Customer segmentation techniques
- Difference between K-Means and Agglomerative clustering

---

## 🔮 Future Improvements
- Feature scaling before clustering
- Compare results with K-Means clustering
- Add business interpretation for each cluster
- Use PCA for dimensionality reduction

---

## 👤 Author
**Sandesh Duduskar**  
Machine Learning Enthusiast | Aspiring Data Scientist
