# Medical Data Project

Helping a homie out . . . . more deets later


## 1 - Initial Plan Idea

Consider four "*__top__ levels*" of data analysis, with each level becoming progressively more complex.  These levels are:

* __A__ Analyze data "*as-is*" : use algorithms that are robust to missing data like decision trees or random forests.
* __B__ Do simple imputations for the missing data and then analyze the resulting "*completed*" dataset, taking care to use different techniques for imputation and analysis.
* __C__ Do some more complicated imputations (*read composite methods*) such as multiple imputation or interpolation, then analyze the resulting "*completed*" dataset.  The imputation methods used here should have **NO** ability to analyze data (*ie no random forests, decision tress, etc*) so these algorithms can be saved for use in analysis of the data here.
* __D__ Employ very high level imputation methods including variants on PCA/MCA as well as deep learning methods, then analyze the resulting "*comlpeted*" data with the fullest suite of applicable and available algorithms.