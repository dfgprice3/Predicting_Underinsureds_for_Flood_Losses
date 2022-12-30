# Predicting_Underinsureds_for_Flood_Losses

Using claims data acquired from the NFIP, we will build a model to predict whether a policyholder is underinsured. Underinsured policies occur when a flood loss exceeds the limits specified in the flood insurance contract. 

Our analysis will not predict the probability of a household incurring a flood loss. This problem would require a specific listing of flood policies and historical information about floods within each geographic area. Because most households acquire a loan to purchase a property, and because banks compel homeowners to carry flood insurance when risks are present, a model predicting probability of a loss feels unnecessary.

Various modeling approaches were used to predict underinsurance. Only a small portion of total claims are underinsured, the notebook also uses oversampling to generate a balanced sample for prediction.
