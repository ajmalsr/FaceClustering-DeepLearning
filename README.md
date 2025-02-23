# 🚀 FaceClustering-DeepLearning

**🔍 Advanced Face Clustering using Deep Learning & Unsupervised Learning**

---

## 📌 Overview  
This repository contains various implementations of **Face Clustering**, leveraging **Deep Learning & Unsupervised Machine Learning** techniques. Different methods like **Eigenfaces, DBSCAN, K-Means, and HDBSCAN** are explored across multiple datasets.  

📝 **Notebooks include:**  
✅ **Face encoding extraction**  
✅ **Clustering using DBSCAN, K-Means, and HDBSCAN**  
✅ **Eigenfaces for dimensionality reduction**  
✅ **GPU-accelerated clustering**  

---

## 📚 Repository Structure
```
📦 FaceClustering-DeepLearning
 ┣ 📄 face_clustering_simple.ipynb  # Custom dataset clustering with DBSCAN
 ┣ 📄 face_Clustering1 (1).ipynb    # Eigenfaces + DBSCAN/K-Means on Pins dataset
 ┣ 📄 face_encoding.ipynb           # Extracting & saving face encodings to CSV
 ┣ 📄 face_cluster2.ipynb           # Preprocessing + DBSCAN/K-Means clustering
 ┣ 📄 face_cluster3.ipynb           # HDBSCAN + GPU acceleration for clustering
 ┣ 📄 README.md                     # Repository documentation
 ┗ 📄 requirements.txt               # Dependencies for running notebooks
```

---

## 🛠️ Setup & Installation  
### **1️⃣ Clone the Repository**  
```sh
git clone https://github.com/yourusername/FaceClustering-DeepLearning.git
cd FaceClustering-DeepLearning
```

### **2️⃣ Install Dependencies**  
```sh
pip install -r requirements.txt
```

### **3️⃣ Run Jupyter Notebooks**  
```sh
jupyter notebook
```

---

## 📊 Notebooks Description  
### **1️⃣ face_clustering_simple.ipynb**  
- Implements a **basic face clustering model** using a small **custom dataset**.  
- Extracts **face encodings** and clusters using **DBSCAN**.  

### **2️⃣ face_Clustering1 (1).ipynb**  
- Uses the **Pins Face Recognition Dataset**.  
- Applies **Eigenfaces for dimensionality reduction**.  
- Tests multiple clustering methods (**K-Means, DBSCAN**).  

### **3️⃣ face_encoding.ipynb**  
- Extracts **face encodings** using **two different methods**.  
- Saves results in a **CSV file**.  

### **4️⃣ face_cluster2.ipynb**  
- Experiments with **different preprocessing methods**.  
- Uses **DBSCAN & K-Means for clustering**.  

### **5️⃣ face_cluster3.ipynb**  
- Implements **HDBSCAN for clustering**.  
- Uses **GPU-accelerated HDBSCAN** for speed optimization.  

---

## 🔬 Techniques Used  
✔ **Face Encoding Extraction**  
✔ **Eigenfaces for Dimensionality Reduction**  
✔ **Unsupervised Learning (K-Means, DBSCAN, HDBSCAN)**  
✔ **GPU Acceleration for HDBSCAN**  

---

## 📌 Future Work  
🔹 Improve clustering accuracy with advanced **deep learning embeddings**.  
🔹 Test on larger datasets with **self-supervised learning**.  
🔹 Optimize HDBSCAN further for real-time applications.  

---

## 👨‍💻 Contributions  
- If you'd like to **contribute**, feel free to fork the repository and submit a PR!  
- Any **suggestions or improvements** are welcome.  

---

## 📝 License  
This project is licensed under the **MIT License**.  

