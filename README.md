# 🌋 Uncovering Hidden Patterns in Geyser Eruptions Using K-Means Clustering

This project applies **unsupervised machine learning** to analyze the famous **Old Faithful Geyser dataset**. Using **K-Means clustering**, it uncovers natural patterns in eruption duration and waiting time.

## 📌 Project Overview

The Old Faithful geyser shows seemingly unpredictable eruption behavior. This project aims to:
- Discover hidden patterns in eruption duration and waiting time
- Segment eruption behavior using K-Means clustering
- Visualize and interpret clustering results

## 📂 Dataset

- Dataset: Old Faithful Geyser Dataset (`faithful.csv`)
- Features:
  - `eruptions` — eruption duration (minutes)
  - `waiting` — waiting time to the next eruption (minutes)

## 🛠️ Technologies Used

Python, Pandas, NumPy, Matplotlib, Seaborn, Scikit-learn

## ⚙️ Methodology

1. Loaded and cleaned the dataset by removing unnecessary columns, duplicates, and checking for missing values  
2. Standardized features using `StandardScaler`  
3. Visualized eruption duration vs waiting time  
4. Used the **Elbow Method** to determine the optimal number of clusters  
5. Applied **K-Means clustering (k = 2)**  
6. Analyzed cluster centroids and average behavior  

## 📊 Results & Insights

- The data naturally forms **two distinct clusters**
- Cluster 0: Short eruptions with shorter waiting times  
- Cluster 1: Long eruptions with longer waiting times  
- The clear separation validates the effectiveness of K-Means clustering

## 📈 Visualizations

- Scatter plot of raw data  
- Elbow curve for cluster selection  
- Clustered data visualization with centroids  

## ▶️ How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/your-repo-name.git
2. Navigate to the project directory:
   cd your-repo-name
3. Install dependencies
   pip install pandas numpy matplotlib seaborn scikit-learn
4. Run the notebook

## 🚀 Future Improvements

Try other clustering algorithms (DBSCAN, Hierarchical Clustering)

Evaluate results using silhouette score

Add interactive or advanced visualizations

## 📬 Contact

LinkedIn: www.linkedin.com/in/palagiri-reshma

GitHub: 
