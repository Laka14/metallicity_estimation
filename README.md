# metallicity_estimation
How to measure metallicity from five-band photometry with supervised machine learning algorithms 
Perfomance of each Algorithm
Algo's used :
SVM
ERT
AdaBoost
Randomized trees

We demonstrate that it is possible to measure metallicity from the SDSS five-band photometry to better than 0.1 dex using supervised machine learning algorithms. Using spectroscopic estimates of metallicity as ground truth, we build, optimize and train several estimators to predict metallicity. We use the observed photometry, as well as derived quantities such as stellar mass and photometric redshift, as features, and we build two sample data sets at median redshifts of 0.103 and 0.218 and median r-band magnitude of 17.5 and 18.3, respectively. We find that ensemble methods, such as random forests of trees and extremely randomized trees and support vector machines all perform comparably well and can measure metallicity with a Root Mean Square Error (RMSE) of 0.081 and 0.090 for the two data sets when all objects are included. The fraction of outliers (objects for which |Ztrue − Zpred| > 0.2 dex) is 2.2 and 3.9 per cent, respectively and the RMSE decreases to 0.068 and 0.069 if those objects are excluded. Because of the ability of these algorithms to capture complex relationships between data and target, our technique performs better than previously proposed methods that sought to fit metallicity using an analytic fitting formula, and has 3× more constraining power than SED fitting-based methods. Additionally, this method is extremely forgiving of contamination in the training set, and can be used with very satisfactory results for sample sizes of a few hundred objects. We distribute all the routines to reproduce our results and apply them to other data sets.
