#  Iris Flower Classification using K-Nearest Neighbors (KNN)

##  Overview
This project demonstrates the use of the **K-Nearest Neighbors (KNN)** algorithm to classify species of iris flowers based on petal and sepal measurements. The task includes feature normalization, model training, hyperparameter tuning, evaluation, and visualization using **Scikit-learn**, **Matplotlib**, and **Pandas**.

---

##  Objectives
- Normalize features for distance-based learning
- Train a **KNN classifier** using different values of K
- Evaluate the model using accuracy and confusion matrix
- Visualize model performance across varying K values
- Plot decision boundaries using 2D features and PCA

---

##  Tools & Libraries
- Python (Jupyter Notebook)
- Pandas
- Scikit-learn
- Matplotlib

---

##  File Structure
├── iris.csv # Iris dataset (if used locally)

├── KNN_Iris_Classifier.ipynb # Jupyter notebook with full implementation

└── README.md # Project documentation


---

##  Dataset Description
**Iris Dataset**  
Each record represents a flower sample with the following features:
- `SepalLengthCm`, `SepalWidthCm`, `PetalLengthCm`, `PetalWidthCm`  
- Target: `Species` — Iris-setosa, Iris-versicolor, Iris-virginica

---

##  Evaluation Metrics
- **Accuracy Score**
- **Confusion Matrix**
- **K vs Accuracy Plot**

---

##  Visualizations
- Line graph of **Accuracy vs K**
- **Confusion Matrix**
- **Decision Boundary** using:
  - 2 selected features: `SepalLengthCm` & `SepalWidthCm`
  - **PCA** to reduce all 4 features to 2D

---

##  What You'll Learn
- How KNN uses distance to classify data (instance-based learning)
- Why **feature scaling** is essential for KNN
- How to choose the optimal value of **K**
- How to interpret results using **visual tools**
- Basics of **PCA** for dimensionality reduction

---

##  How to Run
1. Clone or download this repository
2. Ensure `pandas`, `matplotlib`, and `scikit-learn` are installed
3. Open `KNN_Iris_Classifier.ipynb` in Jupyter Notebook
4. Run all cells in order to train and visualize the model

---

