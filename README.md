# -Diabetes-
This project focused on analyzing diabetes data.
1. Introduction
In this project, we aimed to develop a predictive model for diabetes classification. The project encompassed data exploration, preprocessing, modeling, and evaluation.
2. Data Exploration and Preprocessing
The dataset, from the National Institute of Diabetes and Digestive and Kidney Diseases, targets the diagnosis of diabetes in females of Pima Indian heritage, at least 21 years old. It includes medical predictor variables and an "Outcome" variable for diabetes classification. The dataset had a shape of (768, 9) with no missing values. We handled zero values in specific columns by replacing them with NaN.
3. Data Visualization
We employed histograms to gain insights into feature distributions.
4. Data Preprocessing
Missing values in the columns 'Glucose,' 'BloodPressure,' 'SkinThickness,' 'Insulin,' and 'BMI' were imputed with the median, considering the data distribution. Outliers were detected and treated.
5. Modeling
We split the data into training and testing sets, scaling it with StandardScaler.
6. Model Selection and Hyperparameter Tuning
We evaluated various models, including Logistic Regression, K-Nearest Neighbors, Decision Tree, Random Forest, Gradient Boosting, Support Vector Machine (SVM), and Multi-layer Perceptron (MLP) Classifier. Hyperparameters were optimized through grid search.
7. Model Evaluation
SVM with a linear kernel outperformed other models, achieving 76.39% accuracy. We compared the performance of other models as well.
8. Conclusion
The project effectively addressed diabetes classification, highlighting SVM's superiority. Proper data preprocessing, feature engineering, and model selection played a crucial role. These findings can guide future work in diabetes classification and medical decision-making.
