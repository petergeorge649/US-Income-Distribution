# Income Prediction Analysis the Case of USA

![alt text](https://github.com/petergeorge649/US-Income-Distribution/blob/main/png/map.png)
    𝓣𝓱𝓮 𝓶𝓪𝓹 𝓼𝓱𝓸𝔀𝓼 𝓹𝓮𝓸𝓹𝓵𝓮 𝔀𝓱𝓸 𝓮𝓪𝓻𝓷𝓼 𝓲𝓷𝓬𝓸𝓶𝓮 𝓪𝓫𝓸𝓿𝓮 50𝓴 𝓪𝓷𝓷𝓾𝓪𝓵𝓵𝔂 𝓲𝓷 𝓽𝓱𝓮 𝓤𝓢 𝓫𝓪𝓼𝓮𝓭 𝓸𝓷 𝓽𝓱𝓮 𝓷𝓪𝓽𝓲𝓿𝓮 𝓬𝓸𝓾𝓷𝓽𝓻𝔂.

## **Contents**

**[Introduction](#introduction)**

**[Project Outline](#project-outline)**

**[Objectives](#objectives)**

**[Variables](#variables)**

**[Data](#data)**

**[Visualization](#visualisation)**

**[Conclusion](#conclusion)**

**[References](#references)**


## Introduction
Many countries around the world experience income inequality. According to Norwitch University, ***income inequality in developing countries is decreasing while income discrepancies have increased in developed countries*** [source](https://online.norwich.edu/academic-programs/resources/global-economic-inequality%E2%80%93and-what-might-be-done-about-it#:~:text=Even%20though%20income%20inequality%20in,%2410%2C000%20USD%20in%20total%20wealth). Given the problem stated, USA is chosen as a case study to study the income gap problems using machine learning.

## Project Outline
Predicting people's incomes above 50k annually in the US is the goal of the project. The observation was primarily performed on people from different categories of working class, education, number of educational degrees, race, marital status, occupation, occupation, relationship, sex, capital gain, capital loss, native country, and number of work hours. Importing data was the first step in the project. Predictions were made using logistic regression and decision tree regression. The visualization was done using Tableau, sea-born, matplotlib, and PyWedge. The project involved exploring, wrangling, visualizing and analyzing income data from the USA.

![alt text](https://github.com/petergeorge649/US-Income-Distribution/blob/main/png/Peter.png)

## Objectives
1. Can features predict if someone earns annual Income of above 50k?
2. Is number of male and female equally earns above 50k?
3. What is the income differences between races?


## Variables

 **Age**, One of the independent variables. Age has provided insight into the importance of age when it comes to income. The data set revealed initially that the older you are, the higher your income is. Nevertheless, after a certain period of time during the mid-50s, the majority of their annual income begins to drastically drop. In other words, it can be said that the low income (below 50k annually) was mostly associated with teenagers and older adults. Similar studies have also confirmed the results. A study in Newzeland also found that low income people tend to be teenagers and people who are in their early twenties. Education or school training was cited as the main reason. The same study confirmed some older individuals in New Zealand would have struggled to make ends meet without superannuation privilege [source](https://teara.govt.nz/en/income-and-wealth-distribution/page-4).
 
 The following shows the snapshot of the findings;
 
![alt text](https://github.com/petergeorge649/US-Income-Distribution/blob/main/png/age..png)

**Workclass**, private, seems to be receiving high income, in this case 50k. While **Education**, the study also revealed the higher the education the higher the income, the work class is divided into Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th,10th, Doctorate, 5th-6th, Preschool,Education-num.


**Marital-status** Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.**Occupation** Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.

**Race**,The study revealed a large income gap based on race. According to the study, whites are paid relative higher than other races. Blacks and other races have the lowest incomes. In addition, other studies confirmed these findings. The Pew research center showed in 2020 that the black-white income gap in the US is relatively higher and has remained that way for a while, and the gap is still growing. $23,800 in 1970 to around $33,000 in 2018 (measured in 2018 dollars) [source](https://www.pewresearch.org/fact-tank/2020/02/07/6-facts-about-economic-inequality-in-the-u-s/). 
   ![alt text](https://github.com/petergeorge649/US-Income-Distribution/blob/main/png/race.png)

**Sex**, The sex variable also played a crucial role in the study, as it provided results that allowed one of the objectives to be achieved. Based on Kaggle data, women earn less than men. In order to dig deeper, data from the set was supplemented with current information about the gender income gap, especially. The data provided information on male and female incomes in all states in the USA. The new data set confirmed that women in all USA states earn less than men. For example [source](https://blog.dol.gov/2021/03/19/5-facts-about-the-state-of-the-gender-pay-gap#:~:text=Women%20earn%2082%20cents%20for,for%20many%20women%20of%20color) Bureau of Labor Statistics data, in 2020 revealed that women’s yearly earnings were 82.3% of men’s, and the interval is very high when compared to women of color . Also **Relationship** revealed that husband earn more 50k annually than the rest others were wife , own-child, Not-in-family, Other-relative, Unmarried.

**Capital-gain** and **Capital-loss** were also important variables in the study.**Hours-per-week** many individuals who work 40 hours confirmed to be earning more than 50k annaully than the rest.

**Native-country** involved United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.

**Income >50K** A binary dependent variable contains 0 and 1 in a column. Those labeled 0 yearly earning income below 50k usd while those labeled 1 yearly earning income above 50k usd. This variable was posed as a dependent variable. There are other factors involved, such as working class, education, the number of years of education attended, race, marital status, occupation, relationship, sex, capital gain, capital loss, native country, and hours per week. A classification problem on the data set led to using logistic regression and decision trees.

## Data
In addition to Kaggle data, the data set was enhanced with data from other different sources, for example, the Department of Labor. The enhanced data set provided insights into recent market trends. Kaggle's data set is historical. Data sets include household income, education and income, and poverty and income. Here are the options for exploring the data folder [link](https://github.com/petergeorge649/US-Income-Distribution/tree/main/csv). 

## Visualization
Tableau,Matplolib,Pywedge and Plotly provided assitance in plotting charts and get some insights from them.The relationship between different variables were revealed by visualization. The detailed investigation in this research was aided by visualization , for example identifying the income gaps, obtain income relationships in working class, education, education numbers attended,race,marital status, occupation, relationship, sex, capital gain, capital loss, native country, hours per week. 
![alt text](https://github.com/petergeorge649/US-Income-Distribution/blob/main/png/right%20dashboard.png)

**Tableau visualization for this project can be found under this link;**

[link to tableau](https://public.tableau.com/profile/peter.george.ngugulu#!/vizhome/Income_16213356544040/Dashboard1)

## Conclusion
Logistic regression and Decision tree models helped to solve the classification problem. Confusion matrix Python was used to check the accurancy of the model.Confusion matrix useful since it gives direct comparisons of values such as True Positives, False Positives, True Negatives and False Negatives.Because the data was imbalanced SMOTE (Synthetic Minority Over-sampling Technique) was applied to get the rid of the imbalanced data. Furthermore,ROC (Receiver operating characteristic) was applied to check the accuracy of the model. 

## References

**[csv](https://github.com/petergeorge649/US-Income-Distribution/tree/main/csv)**

**[png](https://github.com/petergeorge649/US-Income-Distribution/tree/main/png)**

**[code](https://github.com/petergeorge649/US-Income-Distribution/tree/main/code)**

**[pywedge charts](https://github.com/petergeorge649/US-Income-Distribution/tree/main/pywedge%20charts)**

**[powerpoint](https://github.com/petergeorge649/US-Income-Prediction/tree/main/Powerpoint)**



