dataset: https://www.kaggle.com/sakshigoyal7/credit-card-customers

index:
Client number. Unique identifier for the customer holding the account

target: 
Attrition_Flag (Existing 0 or Attrited 1)*

features:
Customer_Age (int>=0)* - Customer's Age in Years
Gender (cat: F,M; mapped to 0 or 1)*
Dependent_count (int>=0)* - Number of dependents
Education_Level (cat: not all is known) - Educational Qualification of the account holder 
Marital_Status (cat: not all is known) - Married, Single, Divorced, Unknown
Income_Category (cat: < $40K, $40K - 60K, $60K - $80K, $80K-$120K, > $120K, Unknown but can predict) - Annual Income Category of the account holder
Card_Category (cat: Blue, Silver, Gold, Platinum) - Type of Card

Months_on_book (int>=0)* - Period of relationship with bank
Total_Relationship_Count (int>=0)* - Total no. of products held by the customer
df.Months_Inactive_12_mon (int>=0)* - No. of months inactive in the last 12 months
df.Contacts_Count_12_mon (int>=0)* - No. of Contacts in the last 12 months

df.Credit_Limit (flt>=0)* - Credit Limit on the Credit Card
df.Total_Revolving_Bal (flt* - Total Revolving Balance on the Credit Card
df.Avg_Open_To_Buy (flt* - Open to Buy Credit Line (Average of last 12 months)

df.Total_Amt_Chng_Q4_Q1 (flt* - Change in Transaction Amount (Q4 over Q1)
df.Total_Ct_Chng_Q4_Q1 (flt* - Change in Transaction Count (Q4 over Q1)
df.Total_Trans_Amt (int* - Total Transaction Amount (Last 12 months)
df.Total_Trans_Ct (int>=0)* - Total Transaction Count (Last 12 months)
df.Avg_Utilization_Ratio (flt, 0 to 1)* - Average Card Utilization Ratio