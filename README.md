# Data Preprocessing for Titanic dataset
Project Overview
This project focuses on analyzing and preprocessing the [Titanic] dataset, originally sourced from Kaggle. The aim of this project was to clean, prepare, and optimize the data for further analysis or modeling.

Dataset Information

    Source: Kaggle - https://www.kaggle.com/c/titanic/data
    Dataset Description:
    training set (train.csv)
    test set (test.csv)
    The training set should be used to build your machine learning models. For the training set, we provide the outcome 
    (also known as the “ground truth”) for each     passenger. Your model will be based on “features” like passengers’ 
    gender and class. You can also use feature engineering to create new features.

    The test set should be used to see how well your model performs on unseen data. 
    For the test set, we do not provide the ground truth for each passenger. It is    
    your job to predict these outcomes. For each passenger in the test set, use the model you trained to 
    predict whether or not they survived the sinking of the         Titanic.
    File format: .csv

Data Dictionary 

    Variable	Definition	                                     Key
    survival:	Survival	                                     0 = No, 1 = Yes
    pclass: 	Ticket class	                                1 = 1st, 2 = 2nd, 3 = 3rd
    sex: 	    Sex	
    Age:	    Age in years	
    sibsp:	    # of siblings / spouses aboard the Titanic	
    parch:	    # of parents / children aboard the Titanic	
    ticket:	    Ticket number	
    fare:	    Passenger fare	
    cabin:	    Cabin number	
    embarked:	Port of Embarkation	                             C = Cherbourg, Q = Queenstown, S = Southampton

Tools & Libraries Used

    Python: pandas, numpy, matplotlib, sklearn, plotly, seaborn
    collab for interactive exploration
    Kaggle for data sourcing

After preprocessing, the dataset was cleaned, normalized, and ready for further analysis.

      Missing values handled and outliers removed.
      Dublicates removed
