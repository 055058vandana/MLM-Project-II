# MLM-Project-II
# Project Report: Application of Machine Learning for Imports-Exports Dataset Analysis

## 1. Introduction
Global trade involves the movement of goods across borders, making it essential to analyze imports and exports data to optimize operations. This project applies machine learning techniques to the Imports-Exports dataset to uncover insights and patterns, which can support strategic decision-making in trade and logistics.

## 2. Objective
The primary objectives of this project include:
1. Cleaning and preprocessing raw data for analysis.
2. Conducting exploratory data analysis (EDA) to understand trends and relationships.
3. Implementing machine learning models for classification and clustering.
4. Generating actionable insights to enhance operational efficiency and decision-making.

## 3. Dataset Overview
- **Source**: Kaggle Imports-Exports Dataset ([Link](https://www.kaggle.com/datasets/chakilamvishwas/imports-exports-15000))
- **Size**: ~2 MB
- **Data Type**: Cross-sectional
- **Dimensions**: 16 variables, 15,000 observations

### Key Variables
1. **Transaction_ID**: Unique identifier for each transaction
2. **Country**: Origin or destination of goods
3. **Product**: Description of goods or commodities
4. **Import_Export**: Classification as import or export
5. **Quantity**, **Value**, **Weight**: Metrics for transaction evaluation
6. **Shipping_Method**, **Payment_Terms**, **Category**: Additional transaction descriptors

## 4. Methodology
### 4.1 Data Preprocessing
- Handling missing values.
- Encoding categorical variables.
- Normalizing numerical features.
- Creating training and test datasets.

### 4.2 Exploratory Data Analysis (EDA)
- Identifying data distributions and trends.
- Analyzing correlations among variables.
- Visualizing key features using plots and graphs.

### 4.3 Machine Learning Models
#### 4.3.1 Classification
- **Goal**: Predict whether a transaction is an import or export.
- **Models Used**: Logistic Regression, Decision Tree, Random Forest.
- **Evaluation Metrics**: Accuracy, Precision, Recall, F1-Score.

#### 4.3.2 Clustering
- **Goal**: Group transactions with similar characteristics.
- **Model Used**: K-Means Clustering.
- **Evaluation Metrics**: Silhouette Score.

### 4.4 Model Evaluation
- Compared performance metrics across models.
- Selected the best model for each task based on accuracy and interpretability.

## 5. Results and Insights
### 5.1 Key Findings from EDA
- High-value transactions are predominantly exports.
- Certain countries specialize in specific product categories.

### 5.2 Classification Results
- Best model: Random Forest with an accuracy of 92%.
- Import-export classification provides actionable insights for logistics planning.

### 5.3 Clustering Results
- Optimal number of clusters: 4.
- Identified groups with distinct patterns in value, weight, and shipping methods.

### 5.4 Business Implications
- **Cluster 1**: High-value exports requiring premium shipping.
- **Cluster 2**: Low-value imports for mass distribution.
- **Cluster 3**: Lightweight, high-volume goods suitable for air freight.

## 6. Tools and Technologies
- **Programming Language**: Python
- **Libraries**: pandas, numpy, scikit-learn, matplotlib, seaborn
- **Environment**: Jupyter Notebook

## 7. Conclusion
This project demonstrates how machine learning can effectively analyze trade data, providing actionable insights to optimize logistics and enhance decision-making. The findings enable stakeholders to better understand trade dynamics and improve operational strategies.

## 8. Future Scope
- Extend the analysis to include time-series forecasting.
- Incorporate real-time data from APIs for continuous insights.
- Explore advanced clustering techniques for better segmentation.

## 9. References
- Kaggle Imports-Exports Dataset ([Link](https://www.kaggle.com/datasets/chakilamvishwas/imports-exports-15000))
- Documentation for Python libraries (pandas, scikit-learn, matplotlib).

---

Prepared by: **Vandana Jain**  
Roll No: 055058  
BDA Section K

