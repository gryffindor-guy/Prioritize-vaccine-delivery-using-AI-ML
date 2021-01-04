# Prioritize-vaccine-delivery-using-AI-ML 🚚

### Objective :dart:
As the country gears up to unveil, register and approve its choice of vaccine candidates against COVID-19, the first set of population expected to be immunized may be frontline health workers, doctors, people over 50 years of age and people with co-morbidities. The challenge for healthcare administrators would be  prioritizing within this population, considering limited availability of vaccines initially.

An AI-based solution can help identify priority targets groups (e.g. which regions, what demography, which clusters etc.) for various levels of vaccine access. Relevant and publicly available data sources (e.g. population demographics, electoral rolls, health survey information, city/region density, spread, clusterization etc.) can be used to develop prioritization maps, factoring the limited resources (supply of vaccine, healthcare personnel, cold-chain facilities etc.) available to health authorities and showing how it will change as more of this population gets vaccinated over a period of time.

# Solution :

To provide predictive model to find the most affected people who are suffering from to supply vaccine for them first (present people suffering from covid, frontline health workers, doctors, people over 50 years of age and people with co-morbidities) and then for the remaining people based on vaccine delivery


<h1> Solution Approach :</h1>

### Data Collection: 

Gather the data based on covid-19 from states and central resources and health survey information in India

  1. https://www.kaggle.com/imdevskp/covid19-corona-virus-india-dataset?select=patients_data.csv
  2. https://www.kaggle.com/imdevskp/corona-virus-report
  (These are the datasets we refered till now)

### Data Analysis 🔍

:diamond_shape_with_a_dot_inside: **To find the hidden patterns and relationship between features**

:arrow_right: Feature engineering and Feature selection :
Selecting the best features that are more correlated to find the target label.

:arrow_right: Machine Learning Models :
Train the data on multiple clustering models (K-means, Hierarchical clustering) with hyper parameters. 

:arrow_right: Evaluate ranking algorithm :
Evaluate a ranking algorithm to identify prioritization metrics.

:arrow_right: Prediction :
Supply the vaccine in the area, which was clustered with the more of covid cases, frontline health workers, doctors, people over 50 years of age and people with co-morbidities

### **Currently under feature engineering process, we will soon continue the further clustering and prediction processes**

### Technology and tools:

Python and several python libraries includes matplotlib, pandas, numpy and seaborn.

# Team name:  
Team Fusion

<h1>Team members:</h1>

<ul>
  <li>Mounika</li>
  <li>Pavitra</li>
  <li>Mahesh</li>
  <li>Ganesh babu</li>
  <li>Abhishek</li>
</ul>




