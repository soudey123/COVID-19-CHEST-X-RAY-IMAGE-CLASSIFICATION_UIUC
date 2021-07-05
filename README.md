## COVID-19-CHEST-X-RAY-IMAGE-CLASSIFICATION

This repository contains project deliverarbles related to Covid-19 chest x-ray image classification exercise. The purpose of this project is to build image classification model to detect Covid-19 and Pneumonia cases from chest X-ray images.

Data Source: https://www.kaggle.com/prashant268/chest-xray-covid19-pneumonia

The downloaded 20% test dataset split into 10% validationa and 10% test dataset for this project purpose.

Project Methodology:

1) Radom model initialization as a part of model selection process (pre-trained and simple CNN model)
2) Trained each model with the training dataset separately.
3) Evaluate each trained model on validation set, adjusting hyperparameters to improve validation accuracy.
4) Select the best model based on validation accuracy.
5) Evaluate the best model using test data and report final test accuracy.

Experimental results:

![image](https://user-images.githubusercontent.com/38169031/124501931-1571c380-dd88-11eb-8637-067aacfdfd63.png)


Main source code Jupyter Notebook:

https://github.com/soudey123/COVID-19-CHEST-X-RAY-IMAGE-CLASSIFICATION_UIUC/blob/main/DLH_COVID_FINAL_CODE.ipynb

DLH_COVID model experimental results are shown here: 
https://github.com/soudey123/COVID-19-CHEST-X-RAY-IMAGE-CLASSIFICATION_UIUC/blob/main/Our_Model_Experiemental_Results.xlsx


