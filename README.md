# 💡 Patient Clustering on Heart Disease Data



---

## 📂 Project Overview

- Load and preprocess a medical dataset (e.g., heart disease data).
- Clean the data by handling missing values and converting categorical data.
- Apply **K-Means clustering**.
- Determine the optimal number of clusters using the **Elbow Method**.
- Visualize clusters and interpret the results.

---

## 📊 Dataset

The dataset used is based on health/heart-related patient information. It contains features such as:

- Age
- Sex
- Chest pain type
- Blood pressure
- Cholesterol levels
- Fasting blood sugar
- Maximum heart rate achieved
- Exercise-induced angina
- and more..

> Note: Actual column names were inferred and cleaned due to missing headers in the raw CSV.

---

## ⚙️ Technologies Used

- Python 🐍
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Scikit-learn

---

## 📌 Key Steps

1. **Data Cleaning**  
   - Replaced `"?"` with NaNs and dropped rows with missing data.
   - Converted all string-based numeric values to floats or integers.

2. **Feature Scaling**  
   - Standardized the features using `StandardScaler` to normalize the input for K-Means.

3. **Choosing K**  
   - Used the **Elbow Method** to find the optimal number of clusters by plotting inertia vs. number of clusters.

4. **Model Training**  
   - Applied `KMeans` clustering from scikit-learn.
   - Cluster labels were added to the dataset for further analysis.

5. **Visualization**  
   - Scatter plots and countplots were created to analyze how data is grouped into clusters.

---

## 📈 Results & Interpretation

- **Optimal Clusters Chosen**: `k = 3` (example; based on Elbow curve).
- Patients were grouped into 3 distinct clusters based on health attributes.
- Clusters can potentially represent different **risk groups** or **types of heart conditions** — valuable for exploratory analysis or further classification.

---






