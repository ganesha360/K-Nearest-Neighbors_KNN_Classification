# Task 6: K-Nearest Neighbors (KNN) Classification

## 📘 Project Overview
This project demonstrates how to implement **K-Nearest Neighbors (KNN)** for classification using the **Iris dataset**.  
The objective is to classify iris flowers based on sepal and petal measurements by comparing distance-based neighbors.  
This task focuses on normalization, experimenting with different values of `K`, and evaluating model accuracy.

---

## 🧰 Tools & Libraries Used
- **Python**
- **Pandas** – for data handling  
- **NumPy** – for mathematical operations  
- **Matplotlib / Seaborn** – for visualization  
- **Scikit-learn** – for model training and evaluation  

---

## 🧩 Steps Performed

### 1️⃣ Import & Explore Data
- Loaded the Iris dataset using Pandas.  
- Checked for null values, data types, and dataset summary.

### 2️⃣ Data Preprocessing
- Dropped unnecessary columns (`Id` if present).  
- Encoded target variable (`Species`) using LabelEncoder.  
- Standardized features using `StandardScaler` for equal weightage.

### 3️⃣ Model Training (KNN)
- Trained **KNeighborsClassifier** from `sklearn`.  
- Tested `k` values from **1 to 20**.  
- Selected the best `k` based on **maximum accuracy**.

### 4️⃣ Model Evaluation
- Evaluated model using:
  - ✅ **Accuracy Score**
  - ✅ **Confusion Matrix**
  - ✅ **Classification Report (Precision, Recall, F1-score)**
- Compared performance across `k` values.

### 5️⃣ Visualization
- Plotted **Accuracy vs K** to find the best value.  
- Displayed **Decision Boundary** using the first two features to visualize class separation.

---

## 📊 Visualization Samples
| Visualization | Purpose |
|----------------|----------|
| `plt.plot(range(1,21), accuracy_scores)` | Compare accuracy for each K |
| `plt.contourf()` | Visualize decision boundaries between classes |
| `sns.heatmap(confusion_matrix)` | Display classification performance |

---

## ✅ Results
- Found the **optimal value of K** for best accuracy.  
- Achieved high classification accuracy on the Iris dataset.  
- Visualized clean class separation using the decision boundary.

---

## 💾 Files Included
- `Iris.csv` — original dataset  
- `KNN_Classification.ipynb` — full project code  
- `README.md` — project documentation  

---

## 📚 Learning Outcome
Through this task, I learned:
- How KNN works and how distance affects predictions.  
- How to tune hyperparameters (K value).  
- How to visualize and interpret classification boundaries.

---

## 🧑‍💻 Author
**Ganesh R**  
*(Junior AIML Engineer Trainee)*  
