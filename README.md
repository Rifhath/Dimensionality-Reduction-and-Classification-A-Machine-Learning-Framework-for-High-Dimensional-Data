**Dimensionality Reduction and Classification: A Machine Learning Framework for High-Dimensional Data**

**Overview**

This project explores the use of dimensionality reduction techniques like Principal Component Analysis (PCA) and advanced classification algorithms such as Support Vector Machines (SVM) and Random Forests to classify high-dimensional datasets. The pipeline integrates preprocessing, feature extraction, and hyperparameter optimization to ensure accurate predictions and efficient computations.

**Key Features**

**Dimensionality Reduction:** Applied PCA to reduce feature space while preserving variance, enabling efficient computation and interpretability.

**Classification Algorithms:**
Kernelized SVM for non-linear decision boundaries.
Random Forest for ensemble learning and feature importance analysis.
**Performance Metrics:** Evaluated models using AUC-ROC, Precision-Recall, and F1 scores to account for class imbalance and predictive accuracy.
**Data Visualization:** Scatter plots, scree graphs, and classification boundaries to interpret PCA and model outputs.

**Technologies Used**

**Programming Language:** Python

**Libraries:**

**Data Analysis:** Pandas, NumPy
**Machine Learning:** Scikit-learn
**Visualization:** Matplotlib, Seaborn
**Model Pipelines:** Scikit-learn Pipelines

**Results**

**Best Classifier:** Kernelized SVM achieved the highest AUC-ROC (0.93) and Precision-Recall scores after PCA.
***PCA Impact:** 95% variance captured with 60 components, significantly reducing computational cost while retaining accuracy.

**Pipeline**

**Data Preprocessing:**
StandardScaler for normalization.
**Feature Extraction:**
PCA to extract key dimensions.
**Model Training:**
Hyperparameter-optimized SVM and Random Forest classifiers.
**Evaluation:**
Metrics like AUC-ROC, AUC-PR, F1-score, and MCC to assess model performance.

**Future Enhancements**

Incorporate neural networks for non-linear dimensionality reduction.
Experiment with other advanced classifiers like XGBoost.
Extend PCA analysis to non-linear variants like Kernel PCA.

**Contact**

**Author:** Rifhath Aslam Jageer Hussain
**Email:** rifhathaslam.jr.162@gmail.com
**LinkedIn:** [Rifhath Aslam](https://www.linkedin.com/in/rifhath-aslam-j-791a6a21b/)
