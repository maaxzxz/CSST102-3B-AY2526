# 🧠 Student Lifestyle and Stress Level Prediction

## 📄 Project Overview
This project aims to analyze and predict **student stress levels** based on various **lifestyle factors** such as sleep duration, study habits, physical activity, and diet patterns. Using a **Logistic Regression model**, the experiment evaluates how well these factors can classify students into different stress categories (Low, Moderate, High). The model’s performance is assessed using metrics such as **accuracy, precision, recall, F1-score**, and **5-Fold Cross-Validation**, along with a **confusion matrix** and **learning curve** visualization.

---

## 📊 Dataset Description
The dataset used is **`student_lifestyle_dataset.csv`**, which contains several numerical and categorical features related to student habits and stress indicators.  
Key columns include:
- **Sleep Hours** – Average hours of sleep per day  
- **Study Hours** – Time spent studying daily  
- **Physical Activity** – Frequency or duration of exercise  
- **Social Interaction** – Time spent with peers or family  
- **Diet Quality** – Nutritional balance or meal regularity  
- **Stress_Level** – Target variable (Low, Moderate, High)

Before training, the dataset is split into **80% training** and **20% testing** sets to evaluate model generalization.

---

## 🧪 Experiment Summary
1. **Model Used:** Logistic Regression  
2. **Evaluation Techniques:**  
   - Confusion Matrix  
   - Accuracy, Precision, Recall, and F1-Score  
   - 5-Fold Cross-Validation  
   - Learning Curve Visualization  
3. **Findings:**  
   - The model achieved consistent accuracy across all folds, showing reliable generalization.  
   - The confusion matrix indicated stronger prediction accuracy for moderate stress levels.  
   - The learning curve showed good convergence between training and validation accuracy, suggesting minimal overfitting.  

---

## ⚙️ How to Run the Code

### **1. Upload Files**
Upload your `student_lifestyle_dataset.csv` and `.ipynb` file (e.g., `MP2.ipynb`) to **Google Colab**.

### **2. Import Required Libraries**
Make sure you have the following Python packages installed:
```bash
pip install numpy pandas scikit-learn matplotlib
```

### **3. Run the Notebook**
1. Open the notebook in Google Colab.  
2. Run all cells in order — starting from data loading, preprocessing, model training, evaluation, and visualization.  
3. The output will include:
   - Confusion Matrix with class labels  
   - Cross-validation results (Fold 1–5)  
   - Accuracy, Precision, Recall, and F1-score  
   - Learning Curve plot  

### **4. (Optional) Model Comparison**
For additional exploration, you can compare Logistic Regression with other classifiers such as:
```python
from sklearn.tree import DecisionTreeClassifier
from sklearn.neighbors import KNeighborsClassifier
from sklearn.svm import SVC
```
and evaluate which performs better using the same dataset.

---

## 🧩 Conclusion
The experiment demonstrates that **Logistic Regression** can effectively model the relationship between student lifestyle factors and stress levels, achieving consistent and interpretable results. Future improvements may involve testing non-linear models or optimizing hyperparameters for enhanced predictive accuracy.
