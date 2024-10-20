# Titanic survival classification
This notebook claffifies wether a titanic passenger is survived or not based on a set of covariates. 
The predictions take into account the relation within the member of the same family (assumed to be 
observations sharing the surname and the embarked harbor) or group (assumed to be observations 
sharing the cabin and the embarked harbor). These assumption create multiple structures (such 
as big families, small families, individuals...) that are assessed through different models. 
As of may 2024 the leaderboard accuracy is of 0.81339.
