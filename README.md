# 🌸 Iris Dataset – Decision Tree Classifier

📌 Project Overview

This project applies a Decision Tree Classifier to the famous Iris dataset to classify iris flowers into three species: Setosa, Versicolor, and Virginica.
The model is trained using both Gini Index and Entropy criteria, and hyperparameters are tuned using GridSearchCV.

🎯 Purpose of Analysis

Explore the dataset using Exploratory Data Analysis (EDA).

Build a classification model to predict iris species based on sepal and petal measurements.

Evaluate model performance using accuracy, precision, recall, and f1-score.

Visualize the decision tree and feature importance.

📊 Dataset

Source: Built-in Seaborn Iris dataset (150 samples, 4 features, 3 classes).

Features:

Sepal Length (cm)

Sepal Width (cm)

Petal Length (cm)

Petal Width (cm)

Target: Species (Setosa, Versicolor, Virginica)

🛠️ Steps Followed

Data Loading & Exploration – Checked class distribution and feature statistics.

EDA – Boxplots, pairplots, and outlier detection.

Preprocessing – Outlier treatment using IQR method.

Train-Test Split – 80/20 split with stratification.

Model Training – Decision Tree Classifier with entropy & gini.

Hyperparameter Tuning – GridSearchCV for max_depth, min_samples_split, min_samples_leaf.

Model Evaluation – Accuracy, classification report, and confusion matrix.

Visualization – Decision Tree plots and confusion matrix heatmap.

✅ Results

Test Accuracy: 93%

Setosa: 100% precision & recall

Versicolor & Virginica: 90% precision & recall (some overlap observed)

📈 Key Insights

Petal length & petal width are the most important features for classification.

Setosa is easily separable, while Versicolor and Virginica overlap.

GridSearchCV optimized the tree, but accuracy remained ~93% (dataset is simple).

🚀 Future Work

Apply Random Forest and Gradient Boosting for improved classification.

Deploy the model using Streamlit for interactive predictions.

🤚Author 

Sonia Firdous
