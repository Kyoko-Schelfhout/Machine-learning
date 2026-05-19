# Assignment BIT07 – Mushroom Edibility Classification: A Machine Learning Analysis
This repository contains an assignment completed for BIT07 – Machine Learning, part of my Bioinformatics studies at Howest University of Applied Sciences in Bruges, Belgium.


## 🍄 About the Assignment
This notebook applies a full machine learning pipeline to the Mushroom Edibility Classification dataset, sourced from Kaggle. The dataset contains over 8,000 mushroom observations across 22 physical features (e.g. cap shape, gill color, habitat, season), with the central research question being: Can the physical characteristics of a mushroom tell us whether it is edible or poisonous?
The analysis covers regression, classification, and clustering, comparing multiple models across each task.


## 🤖 Models & Methods Used
* Regression, predicting cap-diameter as a continuous target:
Linear Regression, Ridge (L2), Lasso (L1), Polynomial Features + Ridge
* Classification, predicting edible vs. poisonous:
Logistic Regression, Multinomial & Gaussian Naive Bayes, Decision Tree, Random Forest, Gradient Boosting, AdaBoost
* Clustering, unsupervised structure discovery:
K-Means with WCSS elbow method, PCA for dimensionality reduction & visualisation, Logistic Regression on PCA features


## 🛠️ Tools & Packages Used
Python (Jupyter Notebook), with the following packages: pandas, numpy, matplotlib, seaborn, scikit-learn


## 📁 Files
* Assignment_BIT07_Kyoko_Schelfhout_Mushrooms.ipynb - Jupyter Notebook containing the full analysis
* secondary_data.csv - dataset file (place in the same folder as the notebook before running)


## ▶️ How to Run
Open the .ipynb file in Jupyter Notebook or JupyterLab. Make sure secondary_data.csv is downloaded (the link can be found below under "Link to the data") and placed in the same directory as the notebook before running, or update the file path in the data-loading cell accordingly.


## Link to the data
From this link it is possible to download the data used in this assignment: 
https://www.kaggle.com/datasets/devzohaib/mushroom-edibility-classification 
