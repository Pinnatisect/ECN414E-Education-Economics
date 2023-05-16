# ECN414E-Education-Economics

This repository contains a sample project done for Education Economics course @Istanbul Technical University.
The master data  comes from the World Values Survey (WVS) dataset of Wave 7, which can be accessed through the link: https://www.worldvaluessurvey.org/WVSDocumentationWV7.jsp
The data is filtered for Turkey, and a logit model was built using following columns and variable names. Please check data.xlsx to understand the column references.
The data cleaning follows for excluding minus values as an answer to question. Please check the codebook for WVS for references.
The filtered data is placed as eval.xlsx. \\


AA: urban, rural 
CJ: happiness: Q46
LW: Q260: sex
LY 
Q262: age
MQ
Q273: marital status
MS
Q275: highest educational level 
NE
Q279: employment level
NO
Q288R: income level (recoded)
NP
Q289: religious level

only 2291 include the answers to the data. filtered for minus values.


hap = male + age + married + emp + rel + urb


