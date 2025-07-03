# Task-7-Support-Vector-Machines-SVM-.
Hey! So for this task, I worked with **SVM (Support Vector Machines)** using the **Breast Cancer Dataset** from sklearn.

1.  Loaded the Dataset:
   Used the built-in `load_breast_cancer()` dataset from `sklearn.datasets`. It's binary classification – perfect for SVM.

2.  Explored the Data:
   Printed shape, target names, and checked for missing values. Everything looked clean.

3. Preprocessed the Data:
   Standardized features using `StandardScaler` – super important for SVMs to work properly!

4. Split into Train/Test:
   Used `train_test_split()` to separate data for training and testing (80-20 split).

5. Trained SVM with Linear Kernel:
   First tried `SVC(kernel='linear')`. Checked accuracy and confusion matrix.

6. Trained SVM with RBF Kernel:
   Then used `kernel='rbf'`, tried default hyperparams first. Later tuned them.

7.  Visualized Decision Boundaries:
   Picked just 2 features (`mean radius`, `mean texture`) for plotting decision boundaries using contour plots.

8.  Tuned Hyperparameters (C & gamma):  
   Used `GridSearchCV` to try different values for `C` and `gamma` (for RBF kernel).

9.  Evaluated Model:
   Did cross-validation using `cross_val_score` and checked scores for both kernels.

10. Learned Concepts:
    Got hands-on with margin maximization, kernel trick, and hyperparameter tuning using cross-validation.

