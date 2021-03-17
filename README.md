# Customer-Churn-Prediction
This case requires both statistical analysis and creativity/judgment for the understanding  customer information and to build a predictive model for customer churn.

# Insights from the work
. Data cleaning including missing values, outliers and multi-collinearity is being performed

. After building various predictive churn model, Random Forest Classifier is choosed as Final Predictive Model

. variables to be included in the model:

    * After One hot encoding (get_dummies), internet_no_service dupilicated columns are removed
    * Other columns like Monthly charges and Phone service are removed because they  involved in Multicollinearity effect
    * All other variables are taken into predictive_modelling.

. The performance of the model:

    * F1_score: It is the harmonic mean of Recall and Precision
    * F1_score for our modeling is  73%
    * Roc_Auc_score is 87%


. Key Factors in predicting customer_churn are

    * TotalCharges  ---> makes sense
    * tenure        ---> makes sense
    * Payment_mode  ---> not makes sense
