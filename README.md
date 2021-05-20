# USA, Income Distibution Analysis

![alt text](https://github.com/petergeorge649/US-Income-Distribution/blob/main/png/USA.jpeg)
       𝒫𝒾𝒸𝓉𝓊𝓇𝑒 𝓈𝑜𝓊𝓇𝒸𝑒:𝓐𝓲𝓻 𝓟𝓪𝓷𝓸
      
## **Exploring, Wrangling, Visualisation and Analysis of USA Income Distribution Data.**

## **Contents**

**[Introduction](#introduction)**

**[Project Outline](#project-outline)**

**[Objective](#objective)**

**[Variables-description](#variables-description)**

**[Data](#data)**

**[Visualisation](#visualisation)**

**[Conclusion](#conclusion)**

## Introduction


## Project Outline
The project is about predicting people's income above 50k annually in the USA. Observation was mainly from people with different working class, education, education numbers attended,race,marital status, occupation, relationship, sex, capital gain, capital loss, native country, hours per week. The project started by importing the data.Logistic regression and Decision tree regression was used for the prediction. Tableau, seaborn, matplotlib,pywedge, was used for the visualization.

![alt text](https://github.com/petergeorge649/US-Income-Distribution/blob/main/png/Peter.png)

## Objectives
1. Can features predict if someone earns annual Income of above 50k?
2. Is number of male and female equally earns above 50k?
3. What is the income differences between races?


## Variables

 **Age**, as one among independent variables. Age has provided insights on how age it is important factor when it comes to to income.The data set revealed intially the higher the age the higher the income on this case it was above 50k annually . However after some time in mid 50's majority their annual income begins to drop drastically.In other words it can be said the low income (below 50k annually) were mainly teenagers and older people. The results can be also be confirmed by other similar studies. For example, a study in Newzeland also confirmed low income are mostly teenagers and people who are in early 20s.The main reason stated was education or school training. The same study confirmed in Newzeland without superannuation priviledge, some older individuals would have been facing income challenges [source](https://teara.govt.nz/en/income-and-wealth-distribution/page-4).


 **Workclass**,private, seems to be receaving high income, in this case 50k usd annually. While **Education**, the study also revealed the higher the education the higher the income the work class is divided into Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th,10th, Doctorate, 5th-6th, Preschool.Education-num
continuous.

  **Marital-status** Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.**Occupation** Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.

   **Race**, The study revealed that there is huge income gap based on race. From the study the data exposed that whites rae paid relative higher compare to other races.While blacks and other races income is at the bottom. The findings are also confirmed by other studies.For example Pew research center in 2020 showed that, the black-white income gap in the US is relative higher and remained that way for sometime now, and the income gap continues to grow further. For example, $23,800 in 1970 to around $33,000 in 2018 (as measured in 2018 dollars) [source](https://www.pewresearch.org/fact-tank/2020/02/07/6-facts-about-economic-inequality-in-the-u-s/). 

  **Sex**, the sex variable was also important in the study, as it provided results that was managed to inform the objectives. The data set from kaggle revealed women are paid less than men. To dig in details the data set was enhanced to see is what in happening curently when it comes to gender income gap. The data provided income information about male and female in all USA states. This also confirmed the results of the firts data set that women are paid less than men in all USA states. For example [source](https://blog.dol.gov/2021/03/19/5-facts-about-the-state-of-the-gender-pay-gap#:~:text=Women%20earn%2082%20cents%20for,for%20many%20women%20of%20color) Bureau of Labor Statistics data, in 2020 revealed that women’s yearly earnings were 82.3% of men’s, and the interval is very high when compared to women of color . Also **Relationship** revealed that husband earn more 50k annually than the rest others were wife , own-child, Not-in-family, Other-relative, Unmarried.

**Capital-gain** and **Capital-loss** were also important variables in the study.**Hours-per-week** many individuals who work 40 hours confirmed to be earning more than 50k annaully than the rest.

**Native-country** United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.

**Income >50K** This is binary dependent variable which has 0 and 1 in a column. That means individuals labeled 0 yearly earning income below 50k usd while 1 indicates a person is earning above 50k usd annually.This variable posed as dependent variable. It depends on other features such as working class, education, education numbers attended,race,marital status, occupation, relationship, sex, capital gain, capital loss, native country, hours per week. It's classification problem on the data set, made to opt for the logistic regression and decision tree.

## Data
The data was mainly obtained from Kaggle, however the data set was enhanced from other different sources, for example department of labour.The enhanced data set provided insights on what is happening recently. As the one from Kaggle is a historical data set. Such data sets includes household income data set, Education and income data set and poverty income data set. The data folder can be explored from the following link [link](https://teara.govt.nz/en/income-and-wealth-distribution/page-4). 

## Visualization
Tableau,Matplolib Pywedge and Plotly provided assitance in plotting charts and get some insights from them.The relationship between different variables were revealed by visualization. The detailed investigation in this research was aided by visualization , for example identifying the income gaps, obtain income relationships in working class, education, education numbers attended,race,marital status, occupation, relationship, sex, capital gain, capital loss, native country, hours per week. 
![alt text](https://public.tableau.com/profile/peter.george.ngugulu#!/vizhome/Income_16213356544040/Dashboard1)

Tableau visualization for this project can be found under this link;

[link to tableau](https://public.tableau.com/profile/peter.george.ngugulu#!/vizhome/Income_16213356544040/Dashboard1)

## Conclusion
Logistic regression and Decision tree models helped to solve the classification problem. Confusion matrix Python was used to check the accurancy of the model.Confusion matrixwas useful since it gives direct comparisons of values such as True Positives, False Positives, True Negatives and False Negatives.Because the data was imbalanced SMOTE (Synthetic Minority Over-sampling Technique) was applied to get the rid of the imbalanced data. Furthermore,ROC (Receiver operating characteristic) was applied to check the accuracy of the model. 

## References
Data
Image
Code
Tableau




