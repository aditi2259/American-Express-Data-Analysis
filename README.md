This project analyzes structured customer data for predictive modeling and classification, inspired by the American Express Data Challenge. The dataset used is covid_old.csv, which contains anonymized patient features and a target classification (e.g., severity or disease presence).

The goal is to preprocess the data, handle missing values, train classification models, and visualize results — including a 3D PCA representation of feature space.

📁 Dataset
Filename: covid_old.csv

Features include (simulated example):

Age

BMI

Blood Pressure

Glucose

Cholesterol

Severity (Target)

📌 Note: The dataset simulates the structure of a real-world health/patient classification dataset, used here for modeling and evaluation purposes.

🧰 Tools & Libraries Used
Python (Jupyter Notebook)

pandas, numpy

sklearn: for preprocessing, model training, PCA

matplotlib, seaborn: for data visualization

⚙️ Workflow Summary
Data Import & Exploration

Loaded the dataset using pandas

Handled missing values

Performed basic statistical analysis and visualizations

Preprocessing

Imputation using SimpleImputer

Feature scaling using StandardScaler

Label encoding for categorical features (if any)

Train-Test Split

Split into X_train and X_test using train_test_split

Model Building

Trained classification models (e.g., Logistic Regression, KNN)

Evaluated performance with accuracy, confusion matrix

3D PCA Visualization

Applied PCA to reduce dimensionality to 3 components

Visualized data in 3D scatter plot with labels using matplotlib

📈 3D PCA Visualization
A principal component analysis (PCA) is performed to project high-dimensional features into 3D space. The target classes are visualized in color-coded clusters for better intuition of class separation.
