# ✈️ Customer Segmentation using Unsupervised Machine Learning

## 📌 Project Overview
This project focuses on **customer segmentation** for EastWest Airlines using unsupervised machine learning techniques. The goal is to identify distinct customer groups based on their behavior and characteristics, enabling better business decision-making and targeted marketing strategies.

---

## 🎯 Objectives
- Perform data preprocessing and cleaning
- Explore customer behavior through EDA
- Apply multiple clustering algorithms
- Evaluate clustering performance
- Extract meaningful business insights

---

## 🧠 Techniques Used
- **K-Means Clustering**
- **Hierarchical Clustering (Agglomerative)**
- **DBSCAN**
- **Feature Scaling (StandardScaler)**
- **Dimensionality Reduction (if applied)**
- **Silhouette Score for evaluation**

---

## 📊 Dataset
- Dataset: *EastWest Airlines Customer Data*
- Contains customer-related features such as:
  - Balance
  - Qual_miles
  - Bonus miles
  - Flight miles
  - Membership details

---

## ⚙️ Workflow

1. Data Loading
2. Data Cleaning & Preprocessing  
3. Exploratory Data Analysis (EDA)  
4. Feature Scaling  
5. Clustering Model Implementation:
   - K-Means
   - Hierarchical Clustering
   - DBSCAN  
6. Model Evaluation  
7. Visualization & Interpretation  

---

## 📈 Results

- **K-Means provided the most interpretable clusters**
- Achieved a **Silhouette Score of ~0.36**, indicating moderate cluster separation
- DBSCAN struggled due to data density variations
- Hierarchical clustering provided useful visual insights through dendrograms

---

## 📊 Visualizations

### Elbow Method
![Elbow Method](images/elbow_method.png)

### K-Means Clustering
![KMeans](images/kmeans_clustering.png)

### Hierarchical Clustering
![Hierarchical](images/hierarchical_clustering.png)

### DBSCAN Clustering
![DBSCAN](images/dbscan_clustering.png)

### Feature Distribution
![Feature Distribution](images/customer_feature_distribution.png)

### Outlier Detection
![Boxplot](images/outlier_detection_boxplot.png)

---

## 💡 Key Insights

- Identified distinct customer segments based on travel and spending behavior
- High-value customers can be targeted for premium services
- Low-engagement customers may require retention strategies
- Clustering helps in designing personalized marketing campaigns

---

## 🗂️ Repository Structure
Customer-Segmentation-using-Unsupervised-Machine-Learning/                                          
│                                                                                                   
├── dataset/                                                                                        
│ └── EastWestAirlines.xlsx                                                                         
│                                                                                                   
├── images/                                                                                         
│ ├── elbow_method.png                                                                              
│ ├── kmeans_clustering.png                                                                         
│ ├── hierarchical_clustering.png                                                                   
│ ├── dbscan_clustering.png                                                                         
│ ├── customer_feature_distribution.png                                                             
│ └── outlier_detection_boxplot.png                                                                 
│                                                                                                   
├── notebooks/                                                                                      
│ └── eastwest_airlines_customer_segmentation.ipynb                                                 
│                                                                                                   
├── README.m                                                                                        
└── requirements.txt                                                                                


---

## 🚀 Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📌 Conclusion

This project demonstrates how unsupervised learning techniques can be used to uncover hidden patterns in customer data. Despite moderate cluster separation, the models provided actionable insights for business strategy.

---

## 🙌 Author
**Aquib Nooruddeen Shams**
