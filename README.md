# Time-series-cross-validation-using-crossval
The details of the codeset and plots are included in the attached Adobe Acrobat reader (.pdf) file in this repository. 
You need to download the same to view the contents. There are referrals to other contents in BLUE colour also to follow.

A Brief Introduction
======================

Time series cross-validation is now available in crossval, using function crossval::crossval_ts. Main parameters for crossval::crossval_ts include:

    1.fixed_window described below in sections 1 and 2, and indicating if the training set’s size is fixed or increasing through cross-validation iterations
    2.initial_window: the number of points in the rolling training set
    3.horizon: the number of points in the rolling testing set

Yes, this type of functionality exists in packages such as caret, or forecast, but with different flavours. We start by installing crossval from its online repository (in R’s console):

library(crossval)

Cross Validation wiki: https://en.wikipedia.org/wiki/Cross-validation_(statistics)
