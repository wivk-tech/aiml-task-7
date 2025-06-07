# Support Vector Machines (SVM)

## ✅ Objective
Use SVMs for binary classification using both linear and non-linear (RBF) kernels. Perform visualization, tuning, and evaluation.


## 📊 Dataset
**Breast Cancer Dataset** from Kaggle  


## 📌 Tools Used
- Python
- Google Colab
- Scikit-learn
- NumPy, Pandas
- Matplotlib, Seaborn


## 🛠 Steps Performed

1. **Data Preprocessing**
   - Handled missing values and encoded labels
   - Scaled features using `StandardScaler`

2. **Model Training**
   - SVM with **linear kernel**
   - SVM with **RBF kernel**

3. **Evaluation**
   - Accuracy, confusion matrix, classification report

4. **Hyperparameter Tuning**
   - Used `GridSearchCV` to tune `C` and `gamma`

5. **Cross-Validation**
   - Applied 5-fold CV to assess model stability

6. **Visualization**
   - Plotted decision boundaries using two features in 2D space


## 📈 Results

| Model         | Accuracy |
|---------------|----------|
| SVM Linear    | ~97%     |
| SVM RBF       | ~98%     |
| RBF + Tuning  | ~99%     |


## Submission
Submitted as part of the AI & ML Internship - Task 7.

---

### Author
**Vishwajeet Kumar**  
BS in Data Science and Applications @ IIT Madras  
BTech CSE @ LNJPIT Chapra, BEU Patna
