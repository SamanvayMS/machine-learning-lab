# Projects for IE517 Machine Learning Lab

## Project 1: [Treasury Squeeze Prediction 1](HW1.ipynb)

- **Models Used**: SGDClassifier with StandardScaler
- **Results**:
    train accuracy: 0.611
    test accuracy: 0.595

## Project 2: [Treasury Squeeze Prediction 2](HW2.ipynb)

- **Models Used**: KNeighborsClassifier with StandardScaler(manhattan and euclidean distance)
- **Results**:
    train accuracy: 0.71
    test accuracy: 0.65

## Project 3:[Corporate Bond Rating Exploratory Data Analysis](HW3.ipynb)

- **Models Used**: Scatterplots, Heatmaps, Boxplots, Pairplots

## Project 4: [Home price prediction with OLS, Ridge, Lasso regression with comparitive R2 score study](HW4.ipynb)

- **Models Used**: OLS, Ridge, Lasso
- **Results**:
    OLS R2 score: 0.668
    Ridge R2 score: 0.668
    Lasso R2 score: 0.650

## Projects 5: [Bond price prediction using Treasure Yield Curve Data](HW5.ipynb)

- **Models Used**: StandardScaler, PCA, SGDRegressor(L1 and L2 penalty), SVMRegressors(kernel=linear, rbf, poly, penalty=L1, L2)

## Projects 6: [Credit card Default prediction 1](HW6.ipynb)

- **Models Used**: Decision Tree Classifier with Stratified KFold
- **Results**:
    train accuracy: 0.99939
    test accuracy: 0.72250

## Projects 7: [Credit card Default prediction 2](HW7.ipynb)

- **Models Used**: RandomForest with Stratified KFold and GridSearchCV
- **Results**:
    trees: 200
    train accuracy: 0.99936
    test accuracy: 0.81720

## Final Project 1: [Corporate Bond Credit Rating Classfication](group_project_Credit_Score.ipynb)

- **Models Used**: TSNE, StandardScaler, Pipeline, RandomForestClassifier, AdaBoostClassifier, GridSearchCV, StratifiedKFold, LinearDiscriminantAnalysis, LogisticRegression, DecisionTreeClassifier, MLPClassifier
- **Results**:
    best model: RandomForestClassifier
    train accuracy: 1.0
    val/dev accuracy: 0.870
    test accuracy: 0.817

## Final Project 2: [Economic Cycle Prediction](group_project_Credit_Card_Default.ipynb)

- **Models Used**: StandardScaler, PCA, RFE, RandomForestRegressor, Lasso, Ridge, KNeighborsRegressor, SVR, DecisionTreeRegressor
- **Results**:
    Random Forest R^2 Score (3-month) with Lasso features: 0.9623
    Random Forest R^2 Score (6-month) with Lasso features: 0.9748
    Random Forest R^2 Score (9-month) with Lasso features: 0.9875
    Random Forest R^2 Score (12-month) with RFE features: 0.9638
    Random Forest R^2 Score (15-month) with RFE features: 0.9756
    Random Forest R^2 Score (18-month) with RFE features: 0.9895
    Adaboost R^2 Score (3-month) with Lasso features: 0.9034
    Adaboost R^2 Score (6-month) with Lasso features: 0.9239
    Adaboost R^2 Score (9-month) with Lasso features: 0.9409
    Adaboost R^2 Score (12-month) with RFE features: 0.9005
    Adaboost R^2 Score (15-month) with RFE features: 0.9230
    Adaboost R^2 Score (18-month) with RFE features: 0.9388
    