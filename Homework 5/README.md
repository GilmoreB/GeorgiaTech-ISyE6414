**Background**<br />
Selected molecular descriptors from the Dragon chemoinformatics application were used to predict bioconcentration factors for 779 chemicals in order to evaluate QSAR (Quantitative Structure Activity Relationship).  This dataset was obtained from the UCI machine learning repository.

 

The dataset consists of 779 observations of 10 attributes. Below is a brief description of each feature and the response variable (logBCF) in our dataset:

**Variables**
1. nHM - number of heavy atoms (integer)
2. piPC09 - molecular multiple path count (numeric)
3. PCD - difference between multiple path count and path count (numeric)
4. X2Av - average valence connectivity (numeric)
5. MLOGP - Moriguchi octanol-water partition coefficient (numeric)
6. ON1V -  overall modified Zagreb index by valence vertex degrees (numeric)
7. N.072 - Frequency of RCO-N< / >N-X=X fragments (integer)
8. B02[C-N] - Presence/Absence of C-N atom pairs (binary)
9. F04[C-O] - Frequency of C-O atom pairs (integer)
10. logBCF - Bioconcentration Factor in log units (numeric)

Note that all predictors with the exception of B02[C-N] are quantitative.  For the purpose of this assignment, DO NOT CONVERT B02[C-N] to factor.  Leave the data in its original format - numeric in R.

**Question 1:** Full Model <br />
**Question 2:** Full Model Search<br />
**Question 3:** Stepwise Regression<br />
**Question 4:** Ridge Regression<br />
**Question 5:** Lasso Regression<br />
**Question 6:** Elastic Net<br />
**Question 7:** Model Comparison<br />
