# SVM
# Task 7: Support Vector Machines (SVM)

###  Objective:
To use **Support Vector Machines** for both **linear** and **non-linear classification**, and to visualize decision boundaries using 2D data.

---

###  Tools Used:
- **Python**
- **Scikit-learn**
- **NumPy**
- **Matplotlib**

---

###  Steps Followed:

#### 1. **Dataset Preparation**
- The dataset `breast-cancer.csv` was uploaded to Google Colab.
- Target variable (`diagnosis`) was label encoded:  
  `0 = Benign`, `1 = Malignant`.
- Two features were selected for visualization (2D representation).

#### 2. **Data Preprocessing**
- Data split into training and testing sets (80-20 ratio).
- Features standardized using `StandardScaler`.

#### 3. **Model Training**
- **Linear SVM** trained with kernel = `'linear'`.
- **Non-linear SVM** trained with kernel = `'rbf'` (Radial Basis Function).

#### 4. **Evaluation**
- Accuracy, confusion matrix, and classification report printed for both kernels.
- RBF kernel generally performed better for non-linear separation.

#### 5. **Visualization**
- Decision boundaries were plotted for both **Linear** and **RBF** SVMs using contour plots.

#### 6. **Hyperparameter Tuning**
- `GridSearchCV` used to tune parameters `C` and `gamma`.
- Best parameters and cross-validation accuracy were displayed.

#### 7. **Cross-Validation**
- 5-fold cross-validation performed to ensure model generalization.

---

### Results:
- Both Linear and RBF SVMs classified data with high accuracy.
- RBF kernel captured complex boundaries better.
- The best hyperparameters were obtained via grid search.

---

### Visuals:
- Decision boundaries showing how linear and non-linear kernels classify data differently.

---

### Outcome:
Successfully implemented, visualized, and optimized SVM models for binary classification using Scikit-learn.
