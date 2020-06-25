Exoplanet Exploration


Logistic_regression:

	Models			Accuracy
	Base Model		83.295%
	Select Features Model	82.551%
	Tuned Model		86.556%

Model perfomed better when it was tuned using gridsearchcv compared to the base logistic regression model and the select features model.

Random_forest_tree classification:


	Models			Accuracy
	Base Model		90.16%
	Select Features Model	89.588%
	Tuned Model		89.817%

In this case the base model performed better compared to the gridsearch tuned model and the select features model.

K Nearest Neighbors classification:


	Models		Accuracy
	Base Model	82.78%
	Tuned Model	82.437%

Both the base model and tuned model predict almost the same. 


Random forest tree classification predicted better of all the three: logistic regression, KNN and Random forest tree classification

Random forest tree model is good enough to predict new exoplanets. Tuned model could be better by trying different options in param_grids.