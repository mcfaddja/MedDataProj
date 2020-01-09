# Medical Data Project

Helping someone out . . . . more deets later

## 1 - PLANS

* 1 - Initial Plan Ideas
* 2 - What to do with the plan ideas

### 1.1 - Initial Plan Idea

Consider five "*__top__ levels*" of data analysis, with each level becoming progressively more complex.  These levels are:

* __A) -__ Analyze data "*as-is*" : use algorithms that are robust to missing data like decision trees or random forests.
* __B) -__ Do simple imputations for the missing data and then analyze the resulting "*completed*" dataset
* __C) -__ Do imputation using Machine Learning algorithms to fill in the missing data, taking care to use different techniques for imputation and analysis.
* __D) -__ Do some more complicated imputations (*read composite methods*) such as multiple imputation or interpolation, then analyze the resulting "*completed*" dataset.  The imputation methods used here should have **NO** ability to analyze data (*ie no random forests, decision tress, etc*) so these algorithms can be saved for use in analysis of the data here.
* __E) -__ Employ very high level imputation methods including variants on PCA/MCA as well as deep learning methods, then analyze the resulting "*completed*" data with the fullest suite of applicable and available algorithms.

#### 1.1 A) - *As-is*

I suggest creating models from the *incomplete* data using the algorithms:

* Decision Trees
* Random Forests
* AdaBoost
* Gradient Boosting
* XGBoost

and then calling the "*importances*" (or equivalent) command to quantitatively rank features by their importance in determining outcomes.

#### 1.1 B) - *Simple Imputations*

In this level, first carry out imputations to fill in the missing data using the simple imputation methods:

* Hot/Cold deck imputation
* Regression imputation
* Stochastic Regression imputation

to fill in the *incomplete* data, followed by using models based on the algorithms:

* Decision Trees
* Random Forests
* AdaBoost
* Gradient Boosting
* XGBoost

to determine feature importances.

#### 1.1 C) - *Machine-Learning Imputations*

Here, carry out imputations using the Machine-Learning algorithms:

* Decision Trees
* Random Forest
* AdaBoost
* Gradient Boosting

to fill in the *incomplete* data, followed by using models based on the algorithms:

* Multi-Linear Regression
* Logistic Regression
* Decision Trees
* Random Forests
* AdaBoost
* Gradient Boosting
* XGBoost
* PCA/MCA (*PCA = Principal Component Analysis; MCA = Multiple Correspondence Analysis*)

to determine feature importances, taking care to use different techniques for imputation and analysis.

#### 1.1 D) - *Complicated Imputations*

In this level, first carry out imputations to fill in the missing data using the more advanced imputation methods:

* Interpolation
* Extrapolation
* Multiple Imputation

to fill in the *incomplete* data, followed by using models based on the algorithms:

* Decision Trees
* Random Forests
* AdaBoost
* Gradient Boosting
* XGBoost
* PCA/MCA (*PCA = Principal Component Analysis; MCA = Multiple Correspondence Analysis*)
* SVD (*SVD = Singular Value Decomposition*)
* Support Vector Machines

to determine feature importances.

#### 1.1 E) - *High-Level Imputations*

Finally, the imputations can be carried out using the high level methods:

* Bayesian PCA/MCA
* Fuzzy K-Means
* MICE (*MICE = Multiple Imputation by Chained Equations*)
* Multiple Imputation PCA/MCA
* Deep-Learning methods (*such as those in the __Datawig__ library*)

to fill in the *incomplete* data, followed by using models based on the algorithms:

* Multi-Linear Regression
* Logistic Regression
* Decision Trees
* Random Forests
* AdaBoost
* Gradient Boosting
* XGBoost
* SVD (*SVD = Singular Value Decomposition*)
* Support Vector Machines

### 1.2 - What to do with the plans

First, you need to choose the methods(s) and algorithm(s), this will depend entirely on what the data looks like.  This document should not be interpreted as suggesting that **ALL** of them should be used, it's just listing (*most*) of what's available for use.  

Once the algorithms and methods have been chosen, carry out the first three steps.  If the results from these steps agree, then stopping there is fine, if the results do not agree, then proceed to each additional step until a majority (*or at least a plurality*) is reached.  The last two steps can be done if someone is feeling "extra".  

Additionally, don't this this means doing all of this is hard: there are libraries for doing **ALL** of this.

## 2 - EXAMPLES

I will next give a list of examples for the various techniques and algorithms I mentioned above . . . 

**COMING . . . . at some point**
