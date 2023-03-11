<h1 align="center">Supervised Leaning Modelings</h1>
<h6 align="center">Wine Quality Data | UCI Machine Learning</h6>
<p align="center"><b>#K-nearest neighbor algorithm (KNN)  &emsp; #Logistic regression &emsp; <br> #Linear Discriminant Analysis (LDA) &emsp; #Quadratic Discriminant Analysis(QDA) <br> #Naive Bayes  &emsp; #Decision Tree (CART) &emsp; #Random Forest (Classification) <br> #Bagging  &emsp; #Boosting &emsp; #Support Vector Machine (SVM) &emsp; #Neural Net Work <br></b></p>

<p align="center">
<a href="https://github.com/Sang-Buster/Wine-Quality-Modeling" target="_blank">
<img src="asset\img\logo.svg" width="200"/>
</a>
</p>

<h2 align="center">Preamble</h2>

Consider the wine quality dataset from [UCI Machine Learning Respository](https://archive.ics.uci.edu/ml/datasets/Wine+Quality) [^1]. We will focus only on the data concerning white wines (and not red wines). Dichotomize the `quality` variable as `good`, which takes the value 1 if `quality` ≥ 7 and the value 0, otherwise. We will take `good` as response and all the 11 physiochemical characteristics of the wines in the data as predictors. Develop a good classifier and justify your choice of that classifier.

<h2 align="center">File Tree</h2>

```
📦Wine-Quality-Modeling
 ┣ 📂_freeze
 ┣ 📂_site              // Repository Website
 ┣ 📂asset              // Website Assets
 ┃ ┣ 📂css
 ┃ ┗ 📂img
 ┣ 📂src                // Source Code
 ┃ ┣ 📂dataset
 ┃ ┃ ┣ 📂model
 ┃ ┃ ┣ 📂plot
 ┃ ┣ 📄analysis.qmd
 ┃ ┣ 📄bagging.qmd
 ┃ ┣ 📄boosting.qmd
 ┃ ┣ 📄decisionTree.qmd
 ┃ ┣ 📄knn.qmd
 ┃ ┣ 📄lda.qmd
 ┃ ┣ 📄logit.qmd
 ┃ ┣ 📄naiveBayes.qmd
 ┃ ┣ 📄nnet.qmd
 ┃ ┣ 📄qda.qmd
 ┃ ┣ 📄randomForest.qmd
 ┃ ┣ 📄summary.qmd
 ┃ ┣ 📄svm.qmd
 ┃ ┗ 📄xgboost.qmd 
 ┣ 📄.gitignore
 ┣ 📄index.html
 ┣ 📄LICENSE
 ┣ 📄README.md
 ┣ 📄index.qmd
 ┗ 📄_quarto.yml
```

<p align="right">
<a href="https://github.com/Sang-Buster/Wine-Quality-Modeling" target="_blank">
<img src="https://img.shields.io/github/last-commit/theRealLeif/STAT387?label=Last%20commit"/>
</a>
</p>

<h3 align="center">Reference</h3>

[^1]: P. Cortez, A. Cerdeira, F. Almeida, T. Matos and J. Reis. Modeling wine preferences by data mining from physicochemical properties. In Decision Support Systems, Elsevier, 47(4):547-553, 2009.
