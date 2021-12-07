# Gender-Bias
Reducing bias in pre-process phase using DisparateImpactRemover algorithm provided by IBM Research, available in aif360 (https://aif360.mybluemix.net/).

Data
https://datahub.io/machine-learning/adult

adult-data.csv in Data directory
32561 rows, 14 columns (features)

Data columns (total 15 columns):
 #   Column          Non-Null Count  Dtype 
---  ------          --------------  ----- 
 0   age             32561 non-null  int64 
 1   workclass       32561 non-null  object
 2   fnlwgt          32561 non-null  int64 
 3   education       32561 non-null  object
 4   education_num   32561 non-null  int64 
 5   marital_status  32561 non-null  object
 6   occupation      32561 non-null  object
 7   relationship    32561 non-null  object
 8   race            32561 non-null  object
 9   sex             32561 non-null  object
 10  capital_gain    32561 non-null  int64 
 11  capital_loss    32561 non-null  int64 
 12  hours_per_week  32561 non-null  int64 
 13  country         32561 non-null  object
 14  ann_salary      32561 non-null  object
 
Data gender counts
  #   gender          Female   Male
      Female: 0       -------  ----- 
      Male:   1         10771  21790  
                    
Output
ann_salary feature
2 classes
<=50K    24720
>50K      7841
