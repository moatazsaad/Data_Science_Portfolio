# Targeted Aid Marketing Campaign Project

## Summary  
One of the primary challenges for marketers is gaining insight into customer preferences and requirements. By understanding the customer base, marketers can design targeted campaigns tailored to specific needs. Leveraging customer data and AI/ML techniques, this project focuses on market segmentation to identify distinct customer groups. Using 2.5 years of customer data, the objective is to segment the customer base into at least three groups for targeted advertising.

## Steps & Methodology  

### 1. Data Exploration and Preprocessing  
- Loaded sales data and performed Exploratory Data Analysis (EDA).  
- Handled missing values and adjusted data types.  
- Visualized categorical features and sales distribution over time.  
- Created dummy variables and encoded categorical features.  

### 2. K-Means Clustering  
- Applied K-Means clustering to segment customers based on purchasing behavior.  
- Used the **elbow method** to determine the optimal number of clusters.  
- Analyzed cluster characteristics, including sales trends and product preferences.  
- Visualized clusters using histograms.  

### 3. Dimensionality Reduction with PCA  
- Used **Principal Component Analysis (PCA)** to reduce dataset dimensionality.  
- Created a 3D scatter plot to visualize customer clusters.  

### 4. Autoencoder for Dimensionality Reduction  
- Built and trained an **autoencoder neural network** for feature reduction.  
- Used the encoder to transform data into a lower-dimensional space.  
- Applied K-Means clustering on the reduced data.  
- Analyzed and visualized cluster characteristics.  

### 5. Conclusion  
- Identified distinct customer segments based on purchasing behavior.  
- Compared **traditional clustering (K-Means)** with **deep learning-based clustering (Autoencoder + K-Means)**.  
- Provided insights for targeted marketing, such as personalized promotions and product recommendations.  
