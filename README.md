# Erik Cheekes - Data Analysis Portfolio

This is a repository to showcase my data analyst/data science skills and experience through discussing my past education, work experience, and personal projects I have done.

## Table of contents

- [About me](#about-me)
- [Academic Work](#academic-work)
  + [Descriptive Statistics](#descriptive-statistics)
  + [Multiple Linear Regression](#multiple-linear-regression)
  + [Interrupted Time Series Analysis](#interrupted-time-series-analysis)
- [Work Experience](#work-experience)
  + [Creativity Survey Analysis](#creativity-survey-analysis)
- [Data Projects](#data-projects)
  + [Kickstarter Project Analysis and Prediction](#kickstarter-project)

# About me

I hold a PhD, a MSc in Social Science Research Methods, and a BSc econ in Criminology and Sociology from Cardiff University. I have experience in conducting general activities related to data analysis (descriptive statistics, bivariate analysis, hypothesis testing, exploratory data analysis, inferential statistics, data cleaning, data collection, and data visualisation). 

Since finishing my PhD I personally undertook several online course to improve my programming skills and to get a better idea of how data analysis is used outside of academia. These course include:

+ [Google Data Analytics Professional Certificate (Google/Coursera)]( https://www.credly.com/badges/21c664e4-98f2-4a93-9304-93e65cb87646)
+ [Data Analysis with Python (IBM/Coursera)](https://www.credly.com/badges/f0b20b99-012d-4bbe-9d6a-d16baafba1ed)
+ [Scientific computing with Python (FreeCodeCamp)]( https://www.freecodecamp.org/certification/fcc89409c3b-7009-4e97-a874-a13282364529/scientific-computing-with-python-v7)
+ [Introduction to the Intellectual Enterprises of Computer Science and the Art of Programming (CS50x)](https://certificates.cs50.io/104743cd-576d-471e-bf20-10daa265fb4b.pdf?size=letter)

During my time in academia, in freelance work, personal data projects, and online courses, I have used various tools for data analysis including python, R, SQL, and spreadsheets. Regarding general purpose languages I have mostly use R, however, recently I have transitioned to python and prefer it over R in most data analysis use cases.

# Academic Work

My thesis "How does legalising cannabis influence the purchasing choices of cannabis consumers and the modus operandi of illicit cannabis suppliers?" required me to conduct several data analysis tasks. Here I summarise these data tasks which showcase my quantitative data analysis skills and experience. You can view my thesis as a pdf [here](https://orca.cardiff.ac.uk/id/eprint/152022/). 

The relevant sections to demonstrate my quantitative data analysis skills is section 3.3 (in chapter 3), chapter 6 and chapter 7.

## Descriptive Statistics

**Data collection:**  A necessary pre-prerequisite for my PhD was to use real world data to answer my questions. I identified suitable data sources, collected the data, and compiled them together in a dataset. I also cleaned the data before attempting any analysis. Section 3.3 in chapter 3 covers this process.

**Descriptive Statistics:**  I ran descriptive statistics on my dataset containing longitudinall illicit cannabis price data that stretched between 2005 to early 2020 for the United States. I analysed the data across time, by geography (i.e., by state), cannabis regulation, and proximity to legalised states. Data analysis involved summary statistics and visualisations. Chapter 6 contains this analysis.<br/> 
**Technology:** R, RStudio, Tidyverse, ggplot2.<br/>
**Results:** A descriptive overview of illicit cannabis price data for the United States.<br/>

## Multiple Linear Regression

**Description:** For my thesis I constructed a multiple linear regression model that estimated the association between operational Coloradoan retail cannabis store licenses and illicit cannabis prices in neighbouring states, while controlling for other potential confounder influences. This analysis required the collection of data from several secondary data sources. Such data covered Coloradoan store licenses, law enforcement arrest rates, medical cannabis regulation laws (which were coded into categories), distance between cities, household county income, and population sizes. Bivariate analysis and hypothesis testing was used to identify which variables or confounder influences to include in the multiple linear regression model. Chapter 7 contains this analysis while parts of section 3.3 in chapter 3 outlines the methodology of the statistical models.<br/>
**Technology:** R, RStudio, Tidyverse, ggplot2.<br/>
**Results:** A formal estimation of a negative association between Colorodoan retail store licenses and illicit cannabis prices in neighbouring states which accounted for  other potential confounder influences.<br/>

## Interrupted Time Series Analysis

**Description:** For my thesis I also constructed an interrupted time series model using segmented regression which contrasted illicit cannabis prices before and after legal sale started. This model estimated the initial level change in price (commencing from Colorado first implementing legal sale) and the subsequent trend change per month. Model assumptions were also checked and seasonality controlled for.<br/> 
**Technology:** R, RStudio.<br/>
**Results:** An estimated negative association between Colorado's legal sale implementation date and illicit cannabis prices in neigbhouring states.<br/>

# Work Experience

Where I can (with permission) I discuss private data analysis work I've done for clients (note due to client confidentiality I can not directly show any analysis as I can with my own personal data projects or PhD thesis).

## Creativity Survey Analysis

**Description:** I was commissioned by MAMA Marketing LTD to be the lead data analyst on a quantitative survey study which the SW&T (Somerset West and Taunton) Council and CICCIC (Creative Innovation Centre CIC) funded. The survey focused on young people (aged between 14-24) in the SW&T area. The survey contained 19 questions from 702 submissions (after cleaning, these submissions lowered to 646). Specifically, the study had three overarching research questions regarding current levels of creativity and provision, the demand and opportunity for improved creative programmes, and attitudes towards creativity becoming a career. I cleaned, analysed, and visualised the data from the survey answers for the stakeholders.<br/>
**Technology:** R, Rstudio, Microsoft Excel.<br/>
**Results:** A report outlining and discussing the analysis with specific focus on answering the stakeholders’ three research questions.<br/>

# Data Projects

Personal data projects conducted on publicly available datasets.

## Kickstarter Project

**Analysis:** [Kickstarter Analysis](https://github.com/etcheekes/portfolio_ds/blob/main/kickstarter/kickstarter_analysis.ipynb)<br/>
**Description:**  This project involves analysing a dataset of 331,465 Kickstarter projects which aims to finance themselves through crowdfunding. The main steps of the project are, 1) exploring the dataset descriptively to understand its features and distributions, 2) cleaning and wrangling the data to prepare it for further analysis, 3) examining the associations between various variables and Kickstarter project success/failure (which is defined as whether the project achieved its funding goal or not), 4) building and evaluating a logistic regression model that attempts to predict whether a Kickstarter project will be successful or not. To evaluate the model, I split the data into separate training and testing sets and only used the testing set for testing the final model.<br/>
**Technologies:** Python (pandas, numpy, matplotlib, seaborn, scipy, scikit-learn, sqlalchemy), SQL (SQLite 3).
