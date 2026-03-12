# IT Applications Assignment
## Market Segmentation in the Global Video Game Industry using Unsupervised Machine Learning

Student: Boda Pooja  
Section: B  
Roll Number: IPM06091  
Instructor: Dr. Karan Verma

---

# Project Overview

This project analyzes global video game sales data using unsupervised machine learning techniques. The objective is to identify hidden market segments based on regional sales patterns using PCA and K-Means clustering.

---

# Dataset

The dataset contains global video game sales data including:

• Game Name  
• Platform  
• Genre  
• Publisher  
• North America Sales  
• Europe Sales  
• Japan Sales  
• Global Sales  

---

# Exploratory Data Analysis

### Genre Distribution

![Genre Distribution](images/genre_distribution.png)

**Insight:** Action and Sports genres dominate the gaming market.

---

### Global Sales by Genre

![Genre Sales](images/genre_sales.png)

**Insight:** Certain genres generate significantly higher global revenue.

---

### Platform Market Share

![Platform Sales](images/platform_sales.png)

**Insight:** Some platforms dominate global gaming sales.

---

### Regional Sales Comparison

![Regional Sales](images/regional_sales.png)

**Insight:** North America and Europe show strong sales correlation.

---

# Correlation Analysis

![Correlation Heatmap](images/correlation_heatmap.png)

**Insight:** Regional sales variables are highly correlated.

---

# PCA Visualization

![PCA Plot](images/pca_plot.png)

**Insight:** PCA reduces dimensionality while preserving major sales patterns.

---

# Elbow Method

![Elbow Method](images/elbow_method.png)

**Insight:** The optimal number of clusters is identified using inertia values.

---

# K-Means Clustering

![Cluster Plot](images/cluster_plot.png)

**Insight:** Clustering reveals different market segments based on sales patterns.

---

# Cluster Comparison

![Cluster Comparison](images/cluster_comparison.png)

**Insight:** Different clusters represent varying levels of game popularity.

---

# Publisher Market Analysis

![Top Publishers](images/top_publishers.png)

**Insight:** A few publishers dominate the video game industry.

---

# Tools Used

• Python  
• Pandas  
• Scikit-learn  
• Matplotlib  
• Seaborn  
• Google Colab  
• GitHub

---

# Conclusion

This project demonstrates how unsupervised machine learning can identify hidden patterns in global video game sales data. PCA and K-Means clustering reveal meaningful market segments that can support strategic decision-making in the gaming industry.
