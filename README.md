# PredictFutureSales-Kaggle
Repository for the solution to the Predict Future Sales Competition on Kaggle

My solution is split over four notebooks:

1 . PFS-DataAnalysis&cleanup: simple version of EDA, cleanup of outliers and misspellings, putting together monthly data

2 . PFS-Feature Engineering 1: Label Encoding, Mean Encoding, Feature Generation.

3 . PFS-Model: Train, validation, test split. Model is Light GBM —— it scored 0,90692 on the public leaderboard
    
    This notebook generates finalized_model.sav
    
4 . PFS-Ensembling: Linear Regression + Light GBM with simple mix and stacking with LR
    
    This notebook generates finalized_ensemble_model.sav
