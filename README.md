# Fall-21_COVID-Team_4

We are a Team of four students, 3 Graduate and 1 Under Graduate and the Team details is described below.

<li>Deepa Jayanna - Graduate</li>
<li>Heng Tan - Under Graduate</li>
<li>Poojitha Kalidindi - Graduate</li>
<li>Shipra Shanu - Graduate</li>

## Table of Contents
* [General Information](#General-Information)
* [The project status](#The-project-status)
  + [Stage 1 Enrichment Data assignment Information](#Stage-1-Enrichment-Data-assignment-Information)
  + [Stage 3](#Stage-3)
* [Technologies](#Technologies)
* [Setup](#Setup)

## General Information
In this repository, there are beginners getting aquainted with covid-19 data set and enrichment data set. Also one can read the data set, draw graphs to learn about trends of Covid spread and
merge multiple data sets into single dataset using joins on index keys. The end goal of this project is to develop an analytical framework to study the data coming from United States to understand patterns of COVID-19 effect and spread.
 
## The project status 
Currently the project is in Stage-1, where we are trying to understand the data and highlight our inference for each Dataset in the form of report.Starting with the use of Pandas, Dataframe and operations on it, we are trying to play around with multiple Covid Dataset and merge them using join on index keys.

Project Stage 1 is completed and we are in Stage 2 where we are analysing the dataset statistically in terms of mean, median and mode, fitting the best possible distribution and understanding the correlatioh hypothesis.

### Stage 1 Enrichment Data assignment Information

<li>ACS Social, Economic, and Housing Dataset - Shipra</li>
<li>Presidential Election Results (Political leanings) - Poojitha</li>
<li>Hospital Beds Dataset - Heng</li>
<li>Census Demographic ACS - Deepa</li>


## Stage 3 
The main agenda of this stage is to fit a linear or non-linear regression model for new covid cases and death cases dataset and predict the future infection count. We first calculate the x i.e number of days from where the first covid cases occurred upto recent date the dataset has. Y is the number of new cases registered for that day. Similarly, death cases dataset is built for first death case occurred upto recent date and corresponding number of death cases. Two different models are generated, one for new cases and other for death cases. We calculate the Rsquared and RMSE values for each model and find the best fit model.


## Technologies
* python 3.8 plus
* pandas library

## Setup
Download the github repository either using https or SSH, and open the required file in jupyter notebook from the src folder and you're all set. One can also go through the report for the understanding of Datasets used.

