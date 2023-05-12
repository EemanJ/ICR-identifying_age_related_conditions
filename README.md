# ICR-identifying_age_related_conditions
Kaggle Competition-Identifying Age Related Conditions

https://www.kaggle.com/competitions/icr-identify-age-related-conditions/overview

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

