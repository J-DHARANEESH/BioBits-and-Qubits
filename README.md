# Genomic Clustering using Classical and Quantum-Inspired Methods 🧬

This project applies classical and simulated quantum hybrid clustering methods on Human Microbiome Project (HMP) genomic data. The objective is to uncover meaningful biological patterns such as dominant body sites, gene count distributions, and organism groupings.

## 🚀 Highlights

* Feature engineering on HMP Genomic Data
* Classical KMeans and Quantum-Inspired clustering
* Evaluation using Silhouette Score & Davies-Bouldin Index
* Dimensionality reduction with PCA
* Biological interpretation of clusters
* Visual analytics: Elbow curve, cluster distribution, gene count spread

---

## 📂 Dataset

Dataset: Human Microbiome Project Genomic Metadata
Sample columns:

| HMP ID | Organism Name            | Domain   | Body Site | Gene Count |
| ------ | ------------------------ | -------- | --------- | ---------- |
| 1      | Abiotrophia defectiva    | Bacteria | Oral      | 1950       |
| 2      | Achromobacter piechaudii | Bacteria | Airways   | 5755       |

📝 

---

## 🛠️ Workflow

1. 📦 Load and preprocess dataset
2. 🧠 Encode categorical features
3. ⚖️ Normalize features using StandardScaler
4. 📊 Determine optimal clusters via Elbow Method
5. 📈 Perform Classical and Simulated Quantum Clustering
6. 🧪 Evaluate using Silhouette Score & DB Index
7. 🧬 Biological interpretation of clusters
8. 🎨 Visualizations with Seaborn and Matplotlib

---

## 📊 Results & Insights

### 🧠 Optimal Number of Clusters – Elbow Method

![Elbow](https://github.com/user-attachments/assets/99d2629d-ef15-4801-99e1-2d9da4423adc)


### 🔍 PCA Visualization of Clusters

Add two PCA scatter plots:

![Classical_kmeans_cluster](https://github.com/user-attachments/assets/8c68a60b-a575-4cbe-b68c-e70dd81e10af)

![Quantum_hybrid_clustering](https://github.com/user-attachments/assets/011be6a4-538c-4c12-8653-d2ad19c42e40)


These plots highlight separation among clusters in 2D.

### 📊 Cluster Characteristics

| Cluster | Dominant Site | Avg. Gene Count | Domain   |
| ------- | ------------- | --------------- | -------- |
| 0       | Oral          | 2100            | Bacteria |
| 1       | Airways       | 4300            | Bacteria |
| 2       | Gut           | 5000            | Bacteria |


---

## 📈 Evaluation Comparison

| Model                 | Silhouette Score (Higher Better) | Davies-Bouldin Index (Lower Better) |
| --------------------- | -------------------------------- | ----------------------------------- |
| Classical KMeans      | 0.4185                           | 1.0066                              |
| Quantum Hybrid KMeans | 0.9629                           | 0.0872                              |


---

## 📦 Requirements

Install dependencies:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

---

## 🤖 Author

👤 Built with 💡 by \Dharaneesh J
📫 Reach out: j.dharaneesh12@gmail.com

