# Prioritize-vaccine-delivery-using-AI-ML 🚚

### Objective :dart:
As the country gears up to unveil, register and approve its choice of vaccine candidates against COVID-19, the first set of population expected to be immunized may be frontline health workers, doctors, people over 50 years of age and people with co-morbidities. The challenge for healthcare administrators would be  prioritizing within this population, considering limited availability of vaccines initially.

An AI-based solution can help identify priority targets groups (e.g. which regions, what demography, which clusters etc.) for various levels of vaccine access. Relevant and publicly available data sources (e.g. population demographics, electoral rolls, health survey information, city/region density, spread, clusterization etc.) can be used to develop prioritization maps, factoring the limited resources (supply of vaccine, healthcare personnel, cold-chain facilities etc.) available to health authorities and showing how it will change as more of this population gets vaccinated over a period of time.

# Solution :

To provide predictive model to find the most affected people who are suffering from to supply vaccine for them first (present people suffering from covid, frontline health workers, doctors, people over 50 years of age and people with co-morbidities) and then for the remaining people based on vaccine delivery


<h1> Solution Approach :</h1>
## Steps of the Solution 🐾  
We can divide the whole process of this solution into three major parts.  
1. Prioritization for the whole **nation**  
2. Prioritization for the every individual **disrtict**  
3. UI intigration for the solution  

### Elaborating Further  

#### **1. Prioritization for India** 🔝  
Here, we'll have to inform that which part or state or population-distribution should get the vaccine, first. For that we have to keep various things into consideration.  
> States can be classified on the following criterion:  
> 1. Affect of COVID-19  
>   * by **zone** (red, orange and green zone by gove.)  
>   * by **percentage** of population **affected**, out of total  
>   * by **death VS recovery** ratio  
> 2. Population Distribution
>   * by **age-group**  
>   * by **employment status**  
>   * by **literacy-rate**  
> 3. Economy & Development
>   * **Connectivity** to other states/district (through transportation etc..)  
>   * **Interaction** among the population  

#### **2. Prioritization for a Particular State** ☝️  
For a better estimate and results, it is good idea to provide another **prioritization in the state-level**. It will be helpful for the **state governments** to manage the delivery in an optimal way.  
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

#### **3. UI Integration** 💻  
We wish the home screen to have the following structure:  

```
    HOME
    .
    ├── Map (India)        # Bubble Chart for Priority (district-wise)
    │
    ├── 5-States           # with hishest priority 
    │
    ├── 5-Districts        # with hishest priority 
    │
    ├── Population-Wise    # with hishest priority 
    │   │
    │   ├── Top Age-Group 
    │   │
    │   └── Top Employees
    │
    ├── Live COVID-19 Stats   # Overall India 
    │
    └── SEARCH                # Detailed info for any perticular state
        .
        .
        └── ...         
```

One should be able to discover the information about any perticuler **state** on searching.  
This new page should consist of the following:  

```
    STATE
    .
    ├── Map (State)        # Bubble Chart for Priority (district-wise)
    │
    ├── 5-Districts        # with hishest priority 
    │
    ├── Population-Wise    # with hishest priority 
    │   │
    │   ├── Top Age-Group 
    │   │
    │   └── Top Area          # rural or urban
    │
    └── Live COVID-19 Stats   # For current State 
```

<br />  

## Data-Sources ℹ️  

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




