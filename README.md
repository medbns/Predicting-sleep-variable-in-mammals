# A predictive model for sleep variables in mammals-FINAL

## Introduction
The goal of this project is to predicte the sleeping and dreaming time for mammals.

## Data Sources 
To meet the objectives.

    - The dataset provides sleep attributes for 87 mammals. It provides general attributes of the species. 
    - This dataset contains a range of information designed to facilitate an in-depth exploration of factors that could influence the quality of sleep in mammals. 

 

## Research questions
    - Does a large mammal have a better sleep than a small mammal?
    - Do predators have a better sleep than preys?
    - Who has the longer dreams?

## Methodology
I, first, conduct secondary research to gain general understanding about Goodreads platform and its user’s behaviors using online articles and social media posts about Goodreads and its users. I found that the most indicative factor of book sales is it's number of rating and thus, I will use book ratings as the dependent variable in my predictive model. Then, I performed quantitative analysis using data collected from Goodreads API through three major steps:

    •	Exploratory data analysis on the dataset. The outcome of this steps is to understand the dataset and define relevant input of my models
    •	Predictive Modeling on Total Sleep and Dreaming

## Models
    •	We tried to model our data using different models, first using a linear regression model, Gradient boost regressor, Ridge regressor...
    •	Classification models after switching the continous variable Total Sleep to classes.

## Challenges
The one major challenge of this project is the quality of the data. While dataset provides several useful information such as Total sleep dreaming time predation and danger index. But most of this information has a lot of missing values and we need to deal with them without dropping data because it's limited.
Another challenge is to have a good model with this 87 data points.

## Results & Recommendations

Concerning the limitations of our machine learning model, the constrained size of the dataset posed a notable challenge, as it could have impacted the model's ability to capture a more comprehensive representation of the underlying patterns and complexities within the data. Another aspect worth noting is the inclusion of all mammal types, irrespective of their habitats, which could present both advantages and disadvantages. The diversity in natural habitats among animals significantly influences their lifestyles. A recent study (Smeltzer et al., 2022) mentioned how sleep expression differs drastically in birds and marine mammals in comparison to terrestrial mammals. Therefore finding commonalities between them might be more challenging than we envision. Hence, the ensuing body of work can be regarded as a proof of concept, serving as a foundation for future researchers keen on delving into this particular area of study.



