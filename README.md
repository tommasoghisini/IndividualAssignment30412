# Individual Assignment 30412
### **30412 - Machine Learning @ Università Commerciale L. Bocconi**  
_2021 Individual Project for the BEMACS course_

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tommasoghisini/IndividualAssignment30412/blob/main/Notebook.ipynb)


### Author
- Tommaso Ghisini

### Task Description

This dataset is composed of 1300 samples with 31 features each. The first column is the sample id. The second column in the dataset represents the label. There are 4 possible values for the labels. The remaining columns are numeric features, except for the last column which is categorical (with 3 categories).

Notice that the classes are unbalanced: some labels are more frequent than others. You need to decide whether to take this into account, and if so how.

Your task is the following: you should compare the performance of Logistic Regression (implemented by `sklearn.linear_model.LogisticRegression`) with that of a Random Forest (implemented by `sklearn.ensemble.RandomForestClassifier`). Try to optimize both algorithms' parameters and determine which one is best for this dataset. At the end of the analysis, you should have chosen an algorithm and its optimal set of parameters: write this choice explicitly in the conclusions of your notebook.

Your notebook should detail the procedure you have used to choose the optimal parameters (graphs are a good idea when possible/sensible).

The notebook will be evaluated not only based on the final results, but also on the procedure employed, which should balance practical considerations (one may not be able to exhaustively explore all possible combinations of the parameters) with the desire for achieving the best possible performance in the least amount of time.

Bonus points may be assigned for particularly clean/nifty code and/or well-presented results.

You are also free to attempt other strategies beyond the one in the assignment (which however is mandatory!)

-----
**The submission deadline is _Friday 28th of May 2021 at 23:59 pm CET_.**

-----

### File Structure
```
IndividualAssignment30412
|
+-- Notebook.ipynb
|
+-- mldata_000308XXXX -> contains dataset and description
|   |
|   +-- mldata_000308XXXX.csv
|   +-- mldata_000308XXXX.description.txt
|
+-- README.md

```
