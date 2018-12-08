# ML_project

Group Name: Wolves of Howard Street

Members: Eddie Owens, Brian Wright, Darren Thomas, Tyler Ursuy

compile.py was used for data pre-processing to merge game play by play and spread scores.

The R folder contains various wrangling and EDA focused R scripts.

The Regression Models folder contains notebooks exploring different algorithms including SVM, KNN, Decision Trees, Random Forests, and Linear Regression. SVM and KNN performed significantly worse than Linear Regression and RF, so these were abandoned quickly. DT and RF notebook explores hyperparameter tuning as an attempt to outperform linear regression. We found that it took intense tuning and longer runtimes just to get close to linear regression results. This lead us to choose linear regression using a bagging regressor, which is comparable to a random forest of linear regressions. Linear_Regression.ipynb includes experiments using different datasets and variables. Linear_Regression_Tuning.ipynb includes experiments for variable selection, iterative fitting, grid-searching, and leads to a final model.

The Final_Model.ipynb notebook includes our final model and the RMSE and R^2 on a train test split.

The Live_Demo folder contains a regular notebook, Predict_Thursday.ipynb, to simulate Thursday night's Jaguars vs Titans game. This includes training our final model on our entire dataset, recording halftime statistics, Vegas score prediction, our prediction, actual score, and the comparisons. Predict_Thursday_Presentation.ipynb is identical to the previous notebook, except adapted to a RISE presentation for an in-class demonstration. plotly.ipynb was used in our presentation to show the relationship between pre-game predictions, halftime scores, and final scores in a 3D plot. The folder also includes various screenshots for presenting purposes.
