# USA, Income Distibution Analysis

![alt text]()
       𝒫𝒾𝒸𝓉𝓊𝓇𝑒 𝓈𝑜𝓊𝓇𝒸𝑒:𝐿𝒶𝓃𝑔𝒶𝓃.𝒸𝑜𝓂, 𝑀𝒶𝓅 𝓈𝑜𝓊𝓇𝒸𝑒: 𝒯𝒶𝒷𝓁𝑒𝒶𝓊
      
# Exploring, Wrangling, Visualisation and Analysis of USA Income Distribution Data.

# Contents
*[Project Outline](#project-outline)

*[Project Outline](#project-outline)

*[Scenario](#scenario)

*[Objective](#objective)

*[Variables-description](#variables-description)

*[Data](#data)

*[Database](#database)

*[Visualisation](#visualisation)

*[Conclusion](#conclusion)

# Introduction


# Project Outline
The project is about predicting people's income above 50k annually in the USA.Observation was mainly from people with different working class, education, education numbers attended,race,marital status, occupation, relationship, sex, capital gain, capital loss, native country, hours per week. The project started by importing the data.Logistic regression and Decision tree regression was used for the prediction.

![alt text](https://github.com/petergeorge649/US-Income-Distribution/blob/main/png/Peter.png)

# Objectives
1. Can features predict if someone earns annual Income of above 50k?
2. Is number of male and female equally earns above 50k?
3. What is the income differences between races?


# Variables

1. Age, as one among independent variables. Age has provided insights on how age it is important factor when it comes to to income.The data set revealed intially the higher the age the higher the income on this case it was above 50k annually . However after some time in mid 50's majority their annual income begins to drop drastically.In other words it can be said the low income (below 50k annually) were mainly teenagers and older people. The results can be also be confirmed by other similar studies. For example, a study in Newzeland also confirmed low income are mostly teenagers and people who are in early 20s.The main reason stated was education or school training. The same study confirmed in Newzeland without superannuation priviledge, some older individuals would have been facing income challenges [source](https://teara.govt.nz/en/income-and-wealth-distribution/page-4).

2.Workclass, private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked.

3.Education, the study also revealed the higher the education the higher the income 
Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.

4.Education-num
continuous.

5.Marital-status
Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.

6.Occupation
Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.

7.Relationship
Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.

8.Race
White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.

9. Sex, the sex variable was also important in the study, as it provided results that was managed to inform the objectives. The data set from kaggle revealed women are paid less than men. To dig in details the data set was enhanced to see is what in happening curently when it comes to gender income gap. The data provided income information about male and female in all USA states. This also confirmed the results of the firts data set that women are paid less than men in all USA states. For example [source](https://blog.dol.gov/2021/03/19/5-facts-about-the-state-of-the-gender-pay-gap#:~:text=Women%20earn%2082%20cents%20for,for%20many%20women%20of%20color) Bureau of Labor Statistics data, in 2020 revealed that women’s yearly earnings were 82.3% of men’s, and the interval is very high when compared to women of color .

10.Capital-gain
continuous.

11.Capital-loss
continuous.

12.Hours-per-week
continuous.

13. Native-country
United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.

14.Income >50K
This is binary dependent variable which has 0 and 1 in a column.

# Data
The data was mainly obtained from Kaggle, however the data set was enhanced from other different sources, for example department of labour.The enhanced data set provided insights on what is happening recently. As the one from Kaggle is a historical data set. Such data sets includes household income data set, Education and income data set and poverty income data set. The data folder can be explored from the following link [link](https://teara.govt.nz/en/income-and-wealth-distribution/page-4). 
Investigating the data given and considering approximately how to interface it together,
# Visualization
Tableau,Matplolib Pywedge and Plotly provided assitance in plottin charts and get some insights from it.
![alt text](https://public.tableau.com/profile/peter.george.ngugulu#!/vizhome/Income_16213356544040/Dashboard1)

Tableau visualization for this project can be found under this link;

[link to tableau](https://public.tableau.com/profile/peter.george.ngugulu#!/vizhome/Income_16213356544040/Dashboard1)

# Conclusion
Python was used to clean and sent out a few datasets. Utilizing the data at that point built a machine learning and use MySQL to meet our numerous objectives. As the data given was moderately straight forward, we had parcels of time to test with the visualisations in Scene through the use of Tableau , making a collection of outwardly engaging dashboards that offer curiously understanding.

# References



