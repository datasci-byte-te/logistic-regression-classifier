Logistic Regression Classifier – Breast Cancer Detection

This project builds a binary classification model using Logistic Regression to predict whether a breast tumor is malignant (M) or benign (B) based on features extracted from digitized images of fine needle aspirates (FNA) of breast masses.

Dataset

Source: UCI Machine Learning Repository  
  [Breast Cancer Wisconsin (Diagnostic) Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
- Features: 30 numerical features describing cell nuclei
- Target: Diagnosis (`M` = Malignant, `B` = Benign)
- Class distribution: 357 benign, 212 malignant


## ⚙️ Tools & Libraries Used

- `Python`
- `pandas`
- `numpy`
- `scikit-learn`
- `matplotlib`
- `seaborn`


 Steps Performed

#1. Load and Explore Dataset
- Dropped the `ID` column.
- Encoded the target label (`M` = 1, `B` = 0).

#2. Preprocessing
- Split the dataset into training and testing sets (80/20).
- Standardized the features using `StandardScaler`.

#3. Model Building
- Trained a **Logistic Regression** model using Scikit-learn.

#4. Evaluation
- Evaluated the model using:
  -  Confusion Matrix
  -  Classification Report (Precision, Recall, F1-Score)
  -  ROC-AUC Score and ROC Curve

#5. Threshold Tuning
- Tested classification at a threshold of `0.3` (default is `0.5`).

#6. Sigmoid Function
- Plotted the sigmoid function to explain logistic regression's output transformation.



 Performance Summary (Default Threshold 0.5)

- Accuracy: ~95%
- ROC-AU: ~0.99
- High precision and recallfor both classes


## 📈 Visualization Highlights

- Heatmap of Confusion Matrix
- ROC Curve
- Sigmoid Function Plot




## 📚 References

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [UCI Breast Cancer Dataset](https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)



# Author

This project was created as part of a machine learning assignment on classification using logistic regression.

