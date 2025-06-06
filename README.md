Project Overview
This project aims to predict the survival status (Alive or Dead) of breast cancer patients using machine learning techniques. The dataset contains demographic, clinical, and pathological information. We applied logistic regression for binary classification and evaluated the model's performance using various metrics and visualizations.
 Dataset Description
The dataset (Breast_Cancer.csv) includes 4,024 patient records with the following features:

Demographic: Age, Race, Marital Status

Tumor Characteristics: T Stage, N Stage, Tumor Size, Grade

Biomarkers: Estrogen Status, Progesterone Status

Outcome: Status (Alive/Dead) – used as the target variable

 Tools & Libraries Used
Python 3

pandas, numpy

scikit-learn

matplotlib, seaborn

Workflow
Data Preprocessing

Encoded categorical variables using LabelEncoder

Normalized features using StandardScaler

Split the data into training and testing sets (80/20)

Model Training

Applied LogisticRegression from scikit-learn

Trained on scaled data for optimal convergence

Evaluation Metrics

Accuracy

Classification Report (Precision, Recall, F1-score)

Confusion Matrix

Visualizations

Confusion Matrix Heatmap

Class Distribution Bar Chart

Correlation Heatmap for numerical features

Sample Results
Model Accuracy: ~82–85% (depending on data split)

Visualization Outputs:

Heatmap of Confusion Matrix

Correlation Matrix showing relationships among numeric features

