# Wine Classification

[Presentation (slide-deck)](https://github.com/zunicd/Wine-Classification/blob/master/Wine_Classification.pdf)

### Objective

- Wine is an alcoholic beverage made from fermented grapes. It is a seemingly simple beverage that becomes more complex the more you study it. The good thing is, it doesn’t matter how much you know, nearly everyone can appreciate wine.
- It will definitely be interesting to analyze the physicochemical attributes of wine and understand their relationships and significance with wine quality and types classifications.
- We will follow standard machine learning and data mining workflow to try to predict the quality of a wine (low, medium, high) and its type (red, white) from the physicochemical attributes
- Such insight could be useful to support the oenologist wine tasting evaluations and help winemakers to look for wines of better qualities and improve wine production. Wine stores and large distributors could qualify new wines, even before acquiring them. That way they could better evaluate their purchase cost and their opportunity to sell.



### Summary

- We analyzed the physicochemical attributes of wine and their relationships and significance with wine quality and types classifications. Two datasets (one for red and one for white wines) were downloaded from UCI Machine Learning Repository, combined and prepared for Exploratory Data Analysis.
- We followed standard machine learning and data mining workflow for data analysis and for predicting a) the type of wine (red or white) and b) the quality of wine (low, medium, high).
- For Exploratory Data Analysis, description statistics, correlations and Seaborn visualization (several plot types) were used.
- We have used cross-validation pipeline that included standardization and classifiers. Logistic Regresion was used for wine type prediction while Decision Tree, Random Forest and Support Vector Machine for quality prediction.
- Heatmaps of normalized confusion matrices were used for better visual performance evaluation.
- In the first task (type of wine classification) a simple model was able to obtain an excellent result with 99.49% accuracy.
- In the second challenge, wine quality classification (low, medium, high), simple models could not obtain better results due to variation in data, especially of high quality wines. The best accuracy, 81.13%, was obtained with Random Forest Classifier.



### Tools / Techniques Used:

- Python

- Pandas

- Matplotlib

- Jupyter Notebook

- Seaborn

- Sklearn

- Numpy




### About Data

**Source:**

UCI Machine Learning Repository - https://archive.ics.uci.edu/ml/datasets/Wine+Quality

 There are two input datasets with the same columns. They will be merged into one dataset with one new column: `type`.

1. ***Wine_Data/winequality-red.csv*** - contains red wine attributes:

- **Number of records:**      1,599
- **Columns**: 12



2. ***Wine_Data/winequality-white.csv*** - contains white wine attributes:

- **Number of records:**    4,898

- **Columns**: 12

  

3. ***Wine_Data/winesdz.csv*** - combined dataset:

- **Number of records:**    6,497

- **Columns**: 13
  - type
  - fixed acidity
  - volatile acidity
  - citric acid
  - residual sugar
  - chlorides
  - free sulfur dioxide
  - total sulfur dioxide
  - density
  - pH
  - sulphates
  - alcohol
  - quality
  - quality class







