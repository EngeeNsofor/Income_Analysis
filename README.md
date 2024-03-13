# Income_Analysis
#Classification #SupervisedLearning

### Background

DeltaSquare is an NGO that works with the Government on matters of social policy to bring about a change in the lives of underprivileged sections of society. 
They are tasked with coming up with a policy framework by looking at some data obtained from WHO. 

### Problem

This project aims to answer the following key questions:
- What are the different factors that influence the income of an individual?
- Are these factors things that can be controlled or influenced by creating new laws or amending current ones?
- What are the measures the government can take to incentivize or disincentivize the laws?
- Is there a good predictive model for income that exists? What does the performance assessment look like for such a model?

### Objectives

The goal of this project is to: 
- Discover and analyse the different factors that influence the income of an individual
- Identify the underprivileged persons in society by using various factors to predict their income class (<50K).

The developed model would be optimised for recall because the government needs to identify as many underprivileged persons in society as possible to design a 
policy framework that would be suitable for these groups of people.

### Data Description

The data contains characteristics of the people:

- **age**: Age of a Person
- **workclass**: Type of employment e.g Private, Self-emp-not-inc, Self-emp-inc, Federal-gov, Local-gov, State-gov, Without-pay, Never-worked
- **fnlwgt**: This weight is assigned by the Current Population Survey (CPS). People with similar demographic characteristics should have similar weights since it is a feature aimed to allocate similar weights to people with similar demographic characteristics
- **education**: Degree the person has - Bachelors, Some-college, 11th, HS-grad, Prof-school, Assoc-acdm, Assoc-voc, 9th, 7th-8th, 12th, Masters, 1st-4th, 10th, Doctorate, 5th-6th, Preschool.
- **education-num**: Number of years a person studied
- **marital-status**: Married-civ-spouse, Divorced, Never-married, Separated, Widowed, Married-spouse-absent, Married-AF-spouse.
- **occupation**: Tech-support, Craft-repair, Other-service, Sales, Exec-managerial, Prof-specialty, Handlers-cleaners, Machine-op-inspct, Adm-clerical, Farming-fishing, Transport-moving, Priv-house-serv, Protective-serv, Armed-Forces.
- **relationship**: Wife, Own-child, Husband, Not-in-family, Other-relative, Unmarried.
- **race**: White, Asian-Pac-Islander, Amer-Indian-Eskimo, Other, Black.
- **sex**: Female, Male.
- **capital-gain**: Investment gain of the person other than salary
- **capital-loss**: Loss from investments
- **hours-per-week**: Number of hours a person works
- **native-country**: United-States, Cambodia, England, Puerto-Rico, Canada, Germany, Outlying-US(Guam-USVI-etc), India, Japan, Greece, South, China, Cuba, Iran, Honduras, Philippines, Italy, Poland, Jamaica, Vietnam, Mexico, Portugal, Ireland, France, Dominican-Republic, Laos, Ecuador, Taiwan, Haiti, Columbia, Hungary, Guatemala, Nicaragua, Scotland, Thailand, Yugoslavia, El-Salvador, Trinadad&Tobago, Peru, Hong, Holand-Netherlands.
- **salary**: >50K, <=50K (dependent variable, the salary is in Dollars per year)
