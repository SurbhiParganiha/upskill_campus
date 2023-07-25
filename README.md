# Upskill-Campus_Quality_Prediction_Project

# Project Title : Quality Prediction in a Mining Process
// Submitted by Vishesh Tamrakar & Surbhi Parganiha

### Links to Dataset :


Github link - https://github.com/Vishesh-tamrakar/UpSkill-Campus/blob/main/MiningProcess_Flotation_Plant_Database.csv

Google Drive link - https://drive.google.com/file/d/1mZl1j2m_YiLFCSvduw0MpsBPkgJy396y/view

### Links to Code :

Github link - https://github.com/Vishesh-tamrakar/UpSkill-Campus/blob/main/QualityPredictionInAMiningProcess_VisheshTamrakar_USC_UCT.ipynb

Google Colab link - https://colab.research.google.com/drive/1FhkhYdsoZJ7wx_vjYZVCwfvGqt_0oyGy

### Links to Report :

Github link - https://github.com/Vishesh-tamrakar/UpSkill-Campus/blob/main/QualityPredictionInAMiningProcess_VisheshTamrakar_USC_UCT.docx

Google Docs link - https://docs.google.com/document/d/1zG5TxcSXK4JvDEYPo2E2_SaVTuvHdyaD

## CONTEXT

The main goal is to use this data to predict how much impurity is in the ore concentrate. As this impurity is measured every hour, if we can predict how much silica (impurity) is in the ore concentrate, we can help the engineers, giving them early information to take actions. Hence, they will be able to take corrective actions in advance (reduce impurity, if it is the case) and also help the environment (reducing the amount of ore that goes to tailings with the reduction of silica in the ore concentrate). Hence We decided to work upon this Industrial manufacturing and production problem by using machine learning algorithms to perform the necessary predictions.

## DATASET INFORMATION

The dataset was obtained from a mineral processing plant separating silica from iron ore using the reverse cationic flotation method. Continuous process data were collected from 1 a.m. on March 10, 2017 to 11 p.m. on September 9, 2017. Each row of data consists of 23 measurements that can be categorized into four types:

Raw materials (column 2-3);

Environment variables (column 4-8);

Process variables (column 9-22);

Processed materials (column 23-24).

Raw materials and processed materials were sampled on an hourly basis while the others were sampled every 20 seconds

The first column shows time and date range (from march of 2017 until september of 2017). The second and third columns are quality measures of the iron ore pulp right before it is fed into the flotation plant. Column 4 until column 8 are the most important variables that impact the ore quality at the end of the process. From column 9 until column 22, we can see process data (level and air flow inside the flotation columns, which also impact ore quality. The last two columns are the final iron ore pulp quality measurement from the lab.

## INFERENCES FORMED

-> % SILICA CONCENTRATION EVERY MINUTE

-> % SILICA CONCENTRATION FORECAST TIME CALCULATION

-> PREDICTION OF % SILICA CONCENTRATE WITH AND WITHOUT USING % IRON CONCENTRATE COLUMN

## CONCLUSION

In the context of predicting % Silica concentration in a mineral processing plant, we conducted computations and calculations utilizing 12 GB of system RAM and 50 GB of hard drive disk space. The goal was to analyze the correlation between % Silica and % Iron and forecast the % Silica with minimum error using a dataset obtained from the mineral processing plant and hence it was achieved. 

The forecasts largely follow the pattern of actual values and are contained within the 95% confidence interval and when excluding % iron in concentrate from the features, % silica in concentrate were forecasted one hour ahead and with error below 1 (based on RMSE, MAE). As per the dataset MAE and RMSE of 1±0.2 is a satisfactory result. The forecasts thus show a promising method for the engineers to make timely assessments of concentrated purity and take corrective actions in advance, especially when purity deviates from the acceptable values and yes it is possible to predict % Silica in Concentrate without using % Iron Concentrate column but here we also observe that the R^2 value with inclusion of % Iron Concentrate column is greater than when not included, which means it did really help in the prediction because of the high correlation between them.
