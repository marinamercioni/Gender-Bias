# Gender-Bias
Reducing bias in pre-process phase using DisparateImpactRemover algorithm provided by IBM Research, available in aif360 (https://aif360.mybluemix.net/).

Data
https://datahub.io/machine-learning/adult

adult-data.csv in Data directory
32561 rows, 14 columns (features)

Data columns (total 15 columns): 
	age 
	workclass 
	fnlwgt
	education
	education_num
	marital_status
	occupation
	relationship
	race
	sex
	capital_gain
	capital_loss
	hours_per_week
	country
	ann_salary
 
Data gender counts

       gender          Female   Male
      Female: 0       -------  ----- 
      Male:   1         10771  21790  
                    
# Output

ann_salary feature
2 classes

<=50K    24720
>50K      7841
