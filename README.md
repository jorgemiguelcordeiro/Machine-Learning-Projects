# Abstract

The New York Workers’ Compensation Board (WCB) faces significant challenges in manually processing claims, a time-intensive task impacting efficiency. To address this, we developed machine learning models to automate the prediction of claim outcomes. Given these circumstances, we approached the claim injuries problem from two perspectives. Firstly, we developed a multiclass classification model capable of accurately predicting the WCB’s final decision on claim injury types. Secondly, a binary model to predict if a worker would reach an agreement or not. Utilizing labeled data from claims filed between 2020 and 2022, this project includes an exploratory data analysis, rigorous data preprocessing, feature selection, and modeling. In the feature selection section, we implemented various techniques: Spearman correlations, LASSO, Mutual Information for encoded categorical columns, Decision Trees, and Random Forest. Finally, in the modeling section were tested several machine learning models such as Logistic Regression, K-Nearest Neighbors, Decision Trees, Gaussian Naive Bayes and MLP Classifier; and ensemble models such as Random Forest, AdaBoost, Gradient Boosting, XGBoost, LightGBM, CatBoost and Bagging Classifier. For multiclass, a voting classifier with Random Forest and LightGBM as base estimators produced the best results: the highest f1 score (0.4549). For the binary classification, a voting classifier with Logistic Regression, Gaussian Naive Bayes and Gradient Boosting as base estimators yielded the best results: the highest f1 score (0.6284).

To download other necessary things: https://liveeduisegiunl-my.sharepoint.com/:f:/g/personal/20230083_novaims_unl_pt/EkvfYn9s0UpMgLeSkQteCVcBaRuXNhLBVwmiu1B8llVeTQ?e=XjOuHL
