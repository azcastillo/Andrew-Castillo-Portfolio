
## [Project 1: CoverMyMeds Erdos Bootcamp Prior Authorization Predictor](https://github.com/azcastillo/covermymeds_project)
Two part project in which I created two models to make predictions based on prior authorization information. 

### Project Overview:

Part 1 of the project consisted of creating a model predicting whether a prior authorization would be needed based upon pharmacy claims data. This portion of the prject also consisted of exploratory data analysis in which the following questions were answered: 

  * Which insurance companies had the most approved pharmacy claims? 
  * Which drug was approved the most (numerically)? Which rejection code seemed to appear the most with each drug? 
  * What about a scaled version of this? Relatively, how much did each code appear for each drug?

Part 2 of the project consisted of creating a model predicting whether a prior authorization is likely to be approved. This model was based on data contained on the PA such as correct diagnosis, has already tried and failed a generic drug alternative, has health-related reasons not to take certain medications (contraindications), and claims data. Moreover, this portion consisted of exploratory data analysis in which the following questions were answered (based only on the prior authorization data): 

  * What is the relationship between the correct diagnosis, tried and failed, and contraindication and the prior authorization being approved? 
  * Of the people who have or have not tried and failed a generic alternative, how many of them had contraindications or a correct diagnosis? 
 
![](https://github.com/azcastillo/Andrew-Castillo-Portfolio/blob/main/images/reject_code_with_drug.jpg)
![](images/reject_code_with_drug.jpg)

## [Project 2: NFL Big Data Bowl Erdos Bootcamp Project](https://github.com/azcastillo/erdos2021_nfl_predmodel)

This project was completed as part of the The Erdős Institute Data Science Boot Camp 2021. The NFL Big Data Bowl is an annual analytics contest that explores statistical innovations in football. NFL data from the 2018 season was analyzed to provide recommendations and summaries for optimal defensive coverages, first down analysis, and penalty analysis. To successfully create a prediction model that NFL teams can benefit from, it is important to understand football and its related data. This will allow data scientists to identify significant data for building a model.    

### Project Overview:

**1. Optimal Defensive Coverages:**

Passing plays are the most efficient way for the offensive team to gain field position. Over the course of its history, the NFL has increasingly become a passing focused league. The chart and table below show the increasing efficiency of pass plays vs run plays over the years:

**GOAL:** Significant data from the 2018 NFL season will be analyzed to find out which defensive coverages result in the smallest EPA and smallest average passing yards to provide recommendations and summaries for optimal defensive coverages.


**2. First Down Analysis:**

An offense has four downs or fewer to advance the 10 yards required to gain a first down, which allows them to maintain possession and earns them another four downs. The goal of the offensive team is to secure first downs and eventually score, while the goal of the defensive team is to prevent first downs and to secure turnovers. Because of this, it is important to find out which offensive formations are best at securing first downs and which defensive formations are best at preventing first downs.

**GOAL:** Analysis will consist of examining factors such as quarter, down, yards to go, play result, play type (pass or sack), and offensive and defensive personnel from the 2018 NFL season to find out the first down success percentage of different offensive and defensive formations. 

**3. Penalty Analysis:**

When either the offense or defense violates the rules of the game, they are assessed a penalty. The teams and fans know a penalty has been called when an official throws a yellow flag on the field. Penalties award field position to either the offensive or defensive team based on which team committed the penalty. Penalties range from 5 yards, 10 yards, 15 yards, to potentially the entire length of the field when it comes to pass interference. Because of this, it is important to find out which formations are generally prone or averse to committing penalties. 

**GOAL:** Analysis will consist of examining data from the 2018 NFL season to find out which offensive and defensive formations are more or less likely to commit penalties. Moreoever, we aim to predict penalties based on week 1 player tracking data as well as plays data.

![](images/personnelD_pass_rushers.jpg)
