<img src="images\competition_logo.jpg" alt="competition_logo" width=200px height="auto" align="right">

# PredictFutureSales-Kaggle

Repository for the solution to the Predict Future Sales Competition on Kaggle

<b>Description of the competition:</b>
In this competition you will work with a challenging time-series dataset consisting of daily sales data, kindly provided by one of the largest Russian software firms - 1C Company. 
We are asking you to predict total sales for every product and store in the next month.


My solution is split over four notebooks:

1 . PFS-DataAnalysis&cleanup: simple version of EDA, cleanup of outliers and misspellings, putting together monthly data

2 . PFS-Feature Engineering 1: Label Encoding, Mean Encoding, Feature Generation.

3 . PFS-Model: Train, validation, test split. Model is Light GBM --—— it scored 0,90692 on the public leaderboard (top 20% at the time of submission, not bad for a newbie)   
    -> This notebook generates finalized_model.sav
    
4 . PFS-Ensembling: Linear Regression + Light GBM with simple mix and stacking with LR    
    -> This notebook generates finalized_ensemble_model.sav
    
<img src="images\MonthlySalesWithPrediction.jpg" alt="Monthly Sales with Prediction" align="center">
