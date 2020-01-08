# Medical Data Project

Helping a homie out . . . . more deets later

## 1 - Initial Plan Idea

Consider five "*__top__ levels*" of data analysis, with each level becoming progressively more complex.  These levels are:

* __A) -__ Analyze data "*as-is*" : use algorithms that are robust to missing data like decision trees or random forests.
* __B) -__ Do simple imputations for the missing data and then analyze the resulting "*completed*" dataset
* __C) -__ Do some more complicated imputations (*read composite methods*) such as multiple imputation or interpolation, then analyze the resulting "*completed*" dataset.  The imputation methods used here should have **NO** ability to analyze data (*ie no random forests, decision tress, etc*) so these algorithms can be saved for use in analysis of the data here.
* __D) -__ Do imputation using Machine Learning algorithms to fill in the missing data, taking care to use different techniques for imputation and analysis.
* __E) -__ Employ very high level imputation methods including variants on PCA/MCA as well as deep learning methods, then analyze the resulting "*completed*" data with the fullest suite of applicable and available algorithms.

## 1 A) - *As-is*

I suggest creating models from the *incomplete* data using the algorithms:

* decision trees
* random forests
* gradient boosting
* xgboost

and then calling the "*importances*" (or equivalent) command to quantitatively rank features by their importance in determining outcomes.

## 1 B) - Simple Imputations

First, carry out imputations to fill in the missing data using the simple algorithms:

* Hot/Cold deck imputation
* (Stochastic) Regression imputation
* Interpolation/Extrapolation

to fill in the *incomplete* data, followed by using the algorithms:

* decision trees
* random forests
* gradient boosting
* xgboost

to determine feature importances.