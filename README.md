# Gestational-Diabetes

**Overview**
Gestational diabetes is diabetes diagnosed for the very first time during pregnancy. When your pancreas doesn’t produce enough insulin to control the amount of sugar(glucose) in your blood. Like other types of diabetes, gestational diabetes affects how your cells use sugar (glucose). In other words we can say that GDM occurs when body can’t make enough insulin during pregnancy.Doctors recommends GCT(Glucose Challenge Test), OGTT(Oral Glucose Tolerance Test) or both tests to diagnose gestational diabetes.

**GCT(Glucose Challenge Test)**
The glucose challenge test, also called the one-hour glucose tolerance test, measures your body’s response to sugar (glucose). The glucose challenge test is done during pregnancy to screen for gestational diabetes.
Blood sugar values < 140 mg/dL are normal. You don’t need additional testing for gestational diabetes.
If blood sugar value >= 140 mg/dL then will recommend the three-hour glucose tolerance test.

**OGTT(Oral Glucose Tolerance Test)**
If your blood glucose is higher than 140 mg/dL (7.8 mmol/L), the next step is the oral glucose tolerance test. This test will show if you have gestational diabetes. Oral glucose tolerance tests (OGTT) are used to measure how well the body can process a larger amount of sugar.
Normal blood values for a 3-hour 100-gram oral glucose tolerance test are:
Fasting: <95 mg/dL (5.3 mmol/L)
1 hour: <180 mg/dL (10.0 mmol/L)
2 hours: <155 mg/dL (8.6 mmol/L)
3 hours: <140 mg/dL (7.8 mmol/L)
Here I have taken a sample dataset of 256 columns and 600 rows.
In this dataset, i have done some initial cleaning in Excel and used Tableau for further analysis.
 **
Specific steps and approaches to clean the dataset**
•	Cleaned irrelevant data by using TRIM, SPLIT, REPLACE, IF, UPPER functions.
•	Filled blanks in Text columns to NA, Date columns to 01/01/2099, Boolean and Numeric column to -1.
•	Deleted 42 records, because the target column “Dx with GDM” was blank for these entries.
•	Changed decimals and made it consistent throughout the columns.
•	Column names were modified to more business relevant names.
Removed Duplicate and non-relevant columns.
Types of Noise occurred in data
Blanks, >, very low and high values, irrelevant date, redundant columns, field data type are not correct.
Challenges encountered during the data cleaning process
Understanding context of column name from the header, duplicate columns, identifying null/blank values.
According to GDM dataset 49.46% screened with OGTT and 50.53% screened with GCT method.
 **
Key Findings and Outcome**
Initial dataset contained 600 rows and 256 columns.After cleaning, the dataset was reduced to 558 rows and 153 columns, found 74 people diagnosed with GDM.
 
Identify “Dx with GDM” as the target column.
According to the analysis, found various critical factors for GDM.
Hereditary GDM and Previous GDM History
The data shows 20.29% people having previous GDM history and 57.14% people having Hereditary GDM.
 
 
**Obese and Overweight**
The data shows 21.5% people who are Obese are diagnosed with GDM versus 10.93% people who are Overweight versus 10.42% people who are not Obese and Overweight.
 
**Age and BMI Factor**
The data shows 14.8% people with Age>30 are diagnosed with GDM versus 10.4% people with Age < 30.The data shows 22.2% people with BMI>30 are diagnosed with GDM versus 11.3% people with BMI< 30.
 
Ethnicity, Medication,Miscarried > 28 weeks and Gestational Age
The data shows 72 people with Ethnicity White are diagnosed with GDM versus 2 people with other Ethnicities.
The data shows 72 people who do not take medications are diagnosed with GDM versus 2 people who took medication.
The data shows 1.35% people miscarried after 28 weeks due to GDM versus 0.41% people who did not have GDM.
 
**Blood Pressure**
More GDM Patients are having Abnormal BP(Blood pressure)levels in visit3 compared to visit1. Women with high BP are at higher risk of developing GDM during pregnancy.
 
**HbA1c (HemoglobinA1c )**
GDM Patients are having Abnormal HbA1c(hemoglobin a1c)levels in visit3 compared to visit1.
 
**Hemoglobin**
GDM Patients are having abnormal HB (Hemoglobin )levels in visit3 compared to visit1.Hemoglobin levels are not directly involved in the diagnostic criteria for GDM.
 
**Calcium**
Abnormal Range of Calcium increases in GDM patients. Low calcium levels during pregnancy may be associated with an increased risk of gestational diabetes.
 
**Albumin and U Albumin**
Albumin is a protein produced by the liver. Level of Albumin is low for GDM patients during visit 3.The presence of albumin in the urine. Level of Albumin is low for GDM patients during visit 3.
 
 
**Impact of GDM**
GDM has many impacts on patients and their babies. GDM leads to overweight babies, birth injuries, stillbirth, caesarean, shoulder dystocia or other nerve damage etc.
Treatment for Gestational Diabetes
Treatment for gestational diabetes focuses on keeping blood glucose levels in the normal range. Go to all your prenatal appointments and follow your treatment plan, including:
•	Checking your blood sugar to make sure your levels stay in a healthy range.
•	Eating healthy food in the right amounts at the right times.
•	Follow a healthy eating plan created by your doctor or dietitian.
•	Being active.
•	Monitoring your baby. Your doctor will check your baby’s growth and development.
•	Take Insulin, if needed.
•	Regular Exercise.

**Conclusion**
GDM can have serious effects on both mother and fetus if not treated properly. A major part of managing GDM involves educating the patient about diet, exercise, blood glucose self-monitoring, and self-administration of insulin.



