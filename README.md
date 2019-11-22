# data_mining/数据挖掘
data_analysis

一、十六种回归算法
	01)LineaRegrssion
	02)KNeighuborsRegresspr
	03)SVR
	04)Lasso
	05)Ridge
	06)MLPRegressor
	07)DecisionTreeRegressor
	08)ExtraTreeRegressor
	09)AdaBoostRegressor
	10)GradientBoostingRegressor
	11)BaggingRegressor
	12)XGBRegrrssor
	13)RandomFroestRegressor
	14）Xgbosst
	15）LightGBM
	16）Catboost
	
二、
	Gaussian Naive Bayes (GNB)
	Bernoulli Naive Bayes (BNB)
	Multinomial Naive Bayes (MNB)
	Logistic Regression (LR)
	Stochastic Gradient Descent (SGD)
	Passive Aggressive Classifier (PAC)
	Support Vector Classifier (SVC)
	K-Nearest Neighbor (KNN)
	Decision Tree (DT)
	Random Forest (RF)
	Extra Trees Classifier (ERF)
	AdaBoost (AB)
	Gradient Tree Boosting (GTB)
	
数据描述
特征选择
	Removing features with low variance（剔除低方差的特征）
	Univariate feature selection（单变量特征选择）
	Recursive feature elimination（递归功能消除）
	Feature selection using SelectFromModel（使用SelectFromModel进行特征选择）
		首先想到的是利用单变量特征选择的方法选出几个跟预测结果最相关的特征
		对于回归问题: f_regression, mutual_info_regression
		对于分类问题: chi2, f_classif, mutual_info_classif
		空值处理问题：Imputation of missing values


模型选择
模型集成
