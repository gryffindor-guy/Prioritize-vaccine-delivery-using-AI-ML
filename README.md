# Prioritize-vaccine-delivery-using-AI-ML 🚚

### Objective :dart:
As the country gears up to unveil, register and approve its choice of vaccine candidates against COVID-19, the first set of population expected to be immunized may be frontline health workers, doctors, people over 50 years of age and people with co-morbidities. The challenge for healthcare administrators would be  prioritizing within this population, considering limited availability of vaccines initially.

An AI-based solution can help identify priority targets groups (e.g. which regions, what demography, which clusters etc.) for various levels of vaccine access. Relevant and publicly available data sources (e.g. population demographics, electoral rolls, health survey information, city/region density, spread, clusterization etc.) can be used to develop prioritization maps, factoring the limited resources (supply of vaccine, healthcare personnel, cold-chain facilities etc.) available to health authorities and showing how it will change as more of this population gets vaccinated over a period of time.

# Solution :

To provide predictive model to find the most affected people who are suffering from covid-19 to supply vaccine first to required people who might be in critical status(present people suffering from covid, frontline health workers, doctors, people over 50 years of age and people with co-morbidities) and then for the remaining people based on vaccine production status


<h1> Solution Approach :</h1>

## Steps of the Solution 🐾 

We can divide the whole process of this solution into small parts as mentioned below.  
1. Data Collection and Preprocessing
2. Performing Exploratory Data Analysis 
3. Feature Engineering
4. Traing Machine Learning Model
5. Model Deployment
6. Building Interactive Dashboard

# Strategy

# Clear Explaination of Solution Approach :
 
## Data Collection and Preprocessing:

Here we have collected data from various sources from internet in order to analysis the data, so that we can train our model to prioritize the locations for vaccine delivery. For that purpose we have collected the below Data:
1. State and district-wise data on COVID-19 containing confirmed, active, recovered and death cases.
2. Population density data including gender data
3. Health Workers and Doctors data in the states
4. Age distribution of population
5. People data with comorbidities

### Data-Sources ℹ️ 
We have collected data from the below resources:

  1. https://www.kaggle.com/imdevskp/covid19-corona-virus-india-dataset?select=patients_data.csv
  2. https://www.kaggle.com/imdevskp/corona-virus-report
  3. https://www.kaggle.com/danofer/india-census?select=india-districts-census-2011.csv

### Data preprocessing 

Here we have combined the data that we collected from various resources and cleaned the data by taking care of NAN values.

## Exploratory Data Analysis:

Here we have visualized the data in order to observe the hidden insights from the data which are very useful in model predictions. Here we have performed several visualizations using several libraries and packages. You can have a look of our Exploratory Data Analysis through below links and through Dashboard.

Link for Exploratory Data Analysis :

## Feature Engineering:

:arrow_right: Feature engineering and Feature selection :

Here we have selected the features for model prediction by performing feature engineering.
1. Selecting the best features that are correlated and contributing to our current prioritization problem.
2. For that we have observed data by plotting scatter plots and Heat maps between the features available.
3. Here we have identified the contributing features like Age group, Health workers, comorbidities, population density, Gender,etc..

Here You can have a look on our Feature Engineering Work : LINK

## Training Machine Learning Model :

Here we can divide the whole process of this solution into two parts. 

#### **1. Prioritization for India**  

Here, we'll have to predict that which state or population-distribution should get the vaccine first. For that, we have to consider some metrics.  
> States can be prioritized based on the below criteria:  
> 1. Affect of COVID-19  
>   * by ***zone*** (red, orange and green zone by gove.)  
>   * by ***percentage*** of population **affected**, out of total  
>   * by ***death VS recovery*** ratio  
> 2. Population Distribution
>   * by ***age-group***  
>   * by ***employment status***  
>   * by ***literacy-rate***
>   * by ***gender*** (Males are highly infected when compared to Female in India)
>   * by ***comorbidities data***

#### **2. Prioritization in district Level** 

It would be a good idea to provide another **prioritization in district-level**. We can also prioritize the districts based on the above metrics, so that the vaccine delivery  will reach to the each and every corner of our country by considering their priority of need of vaccine.

For Prioritising We have used ML clustering algorithms with hyper parameters through all the features and trained model used our ranking algorithms (considering several metrics) to figure out the urgency of vaccine delivery in each state.

You can have a look into our model prediction using machine learning : LINK

## Building Interactive Dashboard :

We have builded an Interactive Dashboard for visual Representation of covid 19 Risk Analysis and our Results.

You can check our dashboard here : LINK

### Technology and tools:
python
reactjs
machine learning (Pandas, numpy, matplotlib, seaborn,K-means)
recat redux
react hooks
html
css
js
jsx

# Team name:  
Team Fusion

<h1>Team members:</h1>

<ul>
  <li>Mounika(19pa1a0562)</li>
  <li>Pavitra(19pa1a0532)</li>
  <li>Mahesh(19pa1a0534)</li>
  <li>Ganesh babu(19pa1a05b3)</li>
  <li>Abhishek(19pa1a0548)</li>
</ul>





