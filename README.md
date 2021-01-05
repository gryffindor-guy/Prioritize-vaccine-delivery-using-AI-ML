# Prioritize-vaccine-delivery-using-AI-ML 🚚

### Objective :dart:
As the country gears up to unveil, register and approve its choice of vaccine candidates against COVID-19, the first set of population expected to be immunized may be frontline health workers, doctors, people over 50 years of age and people with co-morbidities. The challenge for healthcare administrators would be  prioritizing within this population, considering limited availability of vaccines initially.

An AI-based solution can help identify priority targets groups (e.g. which regions, what demography, which clusters etc.) for various levels of vaccine access. Relevant and publicly available data sources (e.g. population demographics, electoral rolls, health survey information, city/region density, spread, clusterization etc.) can be used to develop prioritization maps, factoring the limited resources (supply of vaccine, healthcare personnel, cold-chain facilities etc.) available to health authorities and showing how it will change as more of this population gets vaccinated over a period of time.

# Solution :

To provide predictive model to find the most affected people who are suffering from covid-19 to supply vaccine first to required people who might be in critical status(present people suffering from covid, frontline health workers, doctors, people over 50 years of age and people with co-morbidities) and then for the remaining people based on vaccine production status


<h1> Solution Approach :</h1>

## Steps of the Solution 🐾 

We can divide the whole process of this solution into three major parts.  
1. Prioritization for the whole **nation**  
2. Prioritization for the every individual **disrtict**  

### Clear Explaination  

#### **1. Prioritization for India**  

Here, we'll have to predict that which part or state or population-distribution should get the vaccine, first. For that, we have to consider some attributes.  
> States can be classified on the following criterion:  
> 1. Affect of COVID-19  
>   * by ***zone*** (red, orange and green zone by gove.)  
>   * by ***percentage*** of population **affected**, out of total  
>   * by ***death VS recovery*** ratio  
> 2. Population Distribution
>   * by ***age-group***  
>   * by ***employment status***  
>   * by ***literacy-rate*** 
> 3. Economy & Development status
>   * **Connectivity** to other states/district i.e; through transportation etc.. 
>   * **Interaction** among the population  

#### **2. Prioritization for a Particular State** 

For a better estimate and results, it is good idea to provide another **prioritization in the state-level**. It will be helpful for the **state governments** to manage the delivery of the vaccine according to the vaccine production level.

This prioritization can be done district-wise. 

> District can be classified on the following criterion:  

> 1. Affect of COVID-19  
>   * by **zone** (red, orange and green zone by gove.)  
>   * by **percentage** of population **affected**, out of total  
>   * by **death VS recovery** ratio  
> 2. Population Distribution
>   * by **age-group**  
>   * by **rural VS urban** ratio  
>   * **Interaction** among the population  

# Strategy

## Data-Sources ℹ️  

### Data Collection:

Here we have to collect data from various sources in order to analysis the data so that we can train our model to prioritize the locations(by clustering) for vaccine delivery. For that we have to gather real-world data from various sources

Gather the data based on covid-19 from states and central resources and health survey information in India

  1. https://www.kaggle.com/imdevskp/covid19-corona-virus-india-dataset?select=patients_data.csv
  2. https://www.kaggle.com/imdevskp/corona-virus-report
  These are the datasets we refered till now

### Data Analysis 🔍

:diamond_shape_with_a_dot_inside: **To find the hidden patterns and relationship between features**

:arrow_right: Feature engineering and Feature selection :
Selecting the best features that are more correlated to find the target label.

:arrow_right: Machine Learning Models :
Train the data on multiple clustering models (K-means, Hierarchical clustering) with hyper parameters. 

:arrow_right: Evaluate ranking algorithm :
Evaluate a ranking algorithm to prioritize the clusters(locations). This includes several attributes, as clearly mentioned in solution approach above for prioritizing

:arrow_right: Prediction :
Supply the vaccine in the area, which was clustered with the more of covid cases, frontline health workers, doctors, people over 50 years of age and people with co-morbidities (by considering various discussed attributes)

:arrow_right: UI Integration :



### Technology and tools:

Python and several python libraries includes matplotlib, pandas, numpy and seaborn.

## Link To Colab File:
https://colab.research.google.com/drive/1a356cJeAS9zz6903pgDIT9tOepc8BM9w?usp=sharing

# Team name:  
Team Fusion

<h1>Team members:</h1>

<ul>
  <li>Mounika(19pa1a0562)</li>
  <li>Pavitra(19pa1a0532)</li>
  <li>Abhishek(19pa1a0548)</li>
  <li>Ganesh babu(19pa1a05b3)</li>
  <li>Mahesh(19pa1a0534)</li>
</ul>




