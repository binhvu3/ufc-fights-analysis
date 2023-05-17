# :boxing_glove: UFC Fights Analysis :martial_arts_uniform:
Comprehensive UFC fights analysis using machine learning models and stats technics. Contain a written report, code, and data  

## :bar_chart: Result: 
Able to predict a fight with a 66.7% accuracy score using logistic regression with only data engineering (see below for more info).

## :card_file_box: Tech-stack 
- Data Cleaning: Numpy, Pandas, sklearn (LabelEncoder, SimpleImputer, train_test_split, StandardScaler), xgboost (XGBClassifier).
- Data Visualization: mathplotlib.pyplot, seaborn, sklearn (plot_tree).
- Machine Learning Model: Random Forest, Logistic Regression, Linear Discriminant Analysis, Ridge Regression, Boosting. 
- Optimization: Standardization, Cross-validation, and Feature selections


## :bookmark_tabs: Abstract
As combat sports increase in popularity, causal viewers often overlook the complexity of mixed martial
art (MMA). In the early day of the UFC, when fighters' skills are more one-dimensional (wrestling only or
boxing only), one may have a higher chance of predicting a winner based on the fighting style. However,
to compete in today's competition, successful fighters often have a multifarious understanding of all
MMA which directly contributes to the complexity of about. In this paper, we will attempt to predict the
winner of a fight based on historical fight data combined with the fighter’s records and the fighter's
physical attributes. Along the way, we will explore the advantage of physical attributes and try to find
the best machine-learning model to predict the winner. We will first perform some feature engineering
on the given dataset. Then we will use the random forest as a baseline model to compare logistic
regression (LR), linear discriminant analysis (LDA), ridge regression, and boosting. After, we will utilize
some optimization technics such as standardization, cross-validation, and feature selections to attempts
to find a better accuracy score. As it turns out, you can predict a fight with a 66.7% accuracy score using
logistic regression with only data engineering. Additionally, based on the dataset, a positive correlation
of fight winners is drawn based a clear advantage with reach/age. This finding is interesting because it
suggests a cycle in a combat sport where skills advantage beats physical attributes, but physical
attributes play a bigger role when both fighters are equally skilled. In other words, you can beat a bigger
man with skills but not if that bigger man also has the same thing
