# ICR-identifying_age_related_conditions
Kaggle Competition-Identifying Age Related Conditions

https://www.kaggle.com/competitions/icr-identify-age-related-conditions/overview

The goal of this competition is to predict if a person has any of three medical conditions. You are being asked to predict if the person has one or more of any of the three medical conditions (Class 1), or none of the three medical conditions (Class 0). 

    train.csv - The training set.
        Id Unique identifier for each observation.
        AB-GL Fifty-six anonymized health characteristics. All are numeric except for EJ, which is categorical.
        Class A binary target: 1 indicates the subject has been diagnosed with one of the three conditions, 0 indicates they have not.
    test.csv - The test set. Your goal is to predict the probability that a subject in this set belongs to each of the two classes.
    greeks.csv - Supplemental metadata, only available for the training set.
        Alpha Identifies the type of age-related condition, if present.
            A No age-related condition. Corresponds to class 0.
            B, D, G The three age-related conditions. Correspond to class 1.
        Beta, Gamma, Delta Three experimental characteristics.
        Epsilon The date the data for this subject was collected. Note that all of the data in the test set was collected after the training set was collected.
    submission.csv - A submission file in the correct format.

The growing field of bioinformatics includes research into interventions that can help slow and reverse biological aging and prevent major age-related ailments. Data science could have a role to play in developing new methods to solve problems with diverse data, even if the number of samples is small.

Currently, models like XGBoost and random forest are used to predict medical conditions yet the models' performance is not good enough. Dealing with critical problems where lives are on the line, models need to make correct predictions reliably and consistently between different cases.
