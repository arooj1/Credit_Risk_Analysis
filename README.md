# Credit Risk Analysis
## Overview of the Analysis:

Purpose of this exercise is to evaluate credit card risk analysis for the loan purposes. Unfortunately, there is very less data related to the risky loan situation and plenty for the good credit. It has been observed that `easyensembleclassifier` has out performed all other strategies and model by giving high recall of 92/% for `highrisk` loans and overall accuracy of 93/%. 

![summary](Images/summary.jpg)


### Data Distribution per class 

![y_labels](Images/Labels.JPG)

### Data Cleaning:
It is important to prepare the dataset for the training purposes. Besides all basic data cleaning (code already existed), oneHotEncoding for the categorical data is done using `pd.dummies` function. 

### Evaluation Tools:

Through this excercise, various strategies related to unbalanced datasets are used and evaluated in term of 
- Precision
- Recall
- Accuracy
- Confusion Matrix. 

## Results: 

### Findings:

![Evaluation](Images/Evaluation_Summary.JPG)

- It is evident from the results that all data balancing strategies' (undersampling and oversampling) `accuracy` alone cannot be considered a valid model evaluation as it is more or less the same for all of them.

- Unbalanced emsemble models have out performed sampling techniques with logistic regression. (Accuracy increased to 75/% and 93/%). 
- Easy Emsemble Classifier has out performed all of the tried strategies and model. 
- For this specific case it is important to have a reliable results for `highrisk` loan cases (High Recall for `highrisk` category). Again EasyEnsembleClassifier has shown quite outstanding results with Recall close to 92/%.  


![EvaluationGraph](Images/Evaluation_Summary_graph.JPG)


## Summary
It is critical to select unbalanced ensemble classifiers and data balancing strategies while handling imbalanced datasets. I strongly believe that in this scenario not just rely on the accuracy of the model but `recall` and `precision` to get the better performance picture. 
 
