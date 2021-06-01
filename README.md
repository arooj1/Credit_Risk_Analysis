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

- It is evident from the results that `accuracy` along cannot be considered a valid model evaluation as it is more or less the same for all strategies and models. 
- 


![EvaluationGraph](Images/Evaluation_Summary_graph.JPG)





## Summary


 
