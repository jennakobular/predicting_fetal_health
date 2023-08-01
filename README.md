# Using Cardiotocograms to Predict Fetal Health

This repository contains the code used to build several machine-learning models which were used to predict fetal health. 

# Summary
The reduction of child mortality is considered a key indicator of human progress. Fetal death refers to the intrauterine death of a fetus during pregnancy. Newborn death accounts for 47% of all child deaths under the age of 5. Fetal health is monitored prior to and during labor by using cardiotocography. A cardiotocogram measures fetal heart rate and uterine contractions. The results have generally required a specialist to review them and assess if further action needs to be taken. This study looks to see if machine learning can help accurately predict fetal health. Using the results from 2126 records, it was found that machine learning can be an asset to maternal-fetal health. After implementing five different machine learning algorithms, a random forest classifier was able to predict fetal health with 94.6% accuracy. While machine learning will not replace the need for human review, it can help reduce medical errors and increase cost-effectiveness. 

## Necessary libraries:
- numpy
- pandas
- scikit-learn
- seaborn
- matplotlib

## 4 Machine Learning Algorithms were evaluated. 
- decision tree
- K-Nearest-Neighbors
- Random Forest
- Logistic Regression (2 models)

## Introduction

Artificial Intelligence (AI) has the potential to make the healthcare system much more efficient and cost-effective. AI and machine learning can also fill holes in access to medical care in poorer nations and reduce medical errors that cost people their lives. In recent years, more algorithms and machine learning models are being introduced into the medical field. One field of medicine that has begun to bring machine learning into the equation is maternal-fetal medicine. Fetal health can be predicted by using machine learning algorithms. Looking specifically at evaluating cardiotocographs - which is something that previously required an obstetrician's review. 

 Fetal death refers to the intrauterine death of a fetus at any time during a pregnancy. Deaths that occur later in pregnancy are sometimes referred to as stillbirths. Reduction of child mortality is one of the Sustainable Development Goals of the United Nations and is a key indicator of human progress. There are around 6,700 newborn deaths every day, which amounts to 47% of all child deaths under the age of 5 (World Health Organization, 2021). Cardiotocograms (CTGs) are an effective and inexpensive way for healthcare providers to monitor fetal health. A cardiotocography visually represents fetal heart rate (FHR) and uterine contractions (Pettker and Campbell, 2018). Fetal heart rate is recognized as an important indicator of fetal health. Pregnancies can be complicated if the mother has a medical condition such as diabetes or high blood pressure, which can impact the health and development of the fetus. Cardiotocographs aim to help identify situations where potential complications may occur and then effectively intervene to improve outcomes.
 
 A carditocograph is a continuous electronic record of the fetal heart rate which is obtained via an ultrasound transducer placed on the mother’s abdomen (Grivell, Alfirevic, Gyte, and Devane, 2015). Cardiotocography is widely accepted and used in maternity care in the stages of antepartum (before labor) and intrapartum (during labor). If the CTG shows that the fetus is not responding well, it may mean the baby is not getting enough oxygen or that the placenta is not working as it should (Bellani, 2022). If after further testing it is decided the baby is not doing well, the doctor may induce labor or perform a C-section. 
 
  When a CTG is performed, generally an obstetrician, a doctor who specializes in pregnancy, childbirth, and a woman’s reproductive system, reviews the result and classifies the risk. Whenever humans are involved, there is a risk of error or oversight. Introducing machine learning algorithms may be able to adequately identify suspect and pathological results. Using a dataset comprised of records from 2126 cardiotocograms, which were classified by expert obstetricians into three classes: normal, suspect, and pathological, this paper looks to see if machine learning algorithms can correctly identify cardiotocograms that indicate suspect and pathological results. Machine learning can add value to the medical field and result in better health outcomes for mothers and their babies. 

## Overview of repository 
- Analysis - contains EDA and the first logistic regression which used all features
- Decision Tree - decision tree model
- KNN - KNN model
- Logreg - Logistic regression model
- Random Forest = random forest model
- visualizations - data visualizations
- Report - Entire report and analysis 
