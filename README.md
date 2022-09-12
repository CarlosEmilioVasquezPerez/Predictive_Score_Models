# Predictive_Score_Models

#This scripts are sample codes of predictive models. These models are based on a logistic regressions and measured by roc and gini.

#The script credit_modelling was used to predict future defaults in credits (credit cards and loans with different segmentations). 
#The combination of good selections of variables and modelling with woes was giving at least a 0.68 gini in test and validation sample. (origination of credits, 
#12 months of default). The random forest (not in this sample) gives a higher gini, but an adjustment of 50-50 has to be made in order to make 
#a Distribution Table with probabilites that makes better sense.
#This script uses oracle connection to import and extract data.

#The script of transaction_fraud_model was used to score future transactions (approved and denied) as fraud.
#This script uses NoSQL to import and extract data.
