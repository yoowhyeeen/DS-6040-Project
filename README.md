# Project Team:  Uyen Nguyen and Carol Moore 

# Topic:  Estimating the Occurrence of Lyme Disease

Lyme disease is difficult to predict.  First, the geographic distribution of Lyme (and other tick-borne illnesses) in the United States is shifing with the warming climate and migration to rural areas.  Furthermore, measurement at the national and state levels is uncertain: a recent study covering 2010-2018 found that Lyme diagnoses in insurance claims data were 6 to 8 times more frequent than in public health surveillance reports. Finally, Lyme is often has vague symptoms (only 20% have the famous bulls-eye rash) and experts and patient advocates belive it to be under-diagnosed.  According to the advocacy group Lymedisease.org, 20% to 30% of tests for a Lyme antibody are false negatives because the disease can suppress the immune systems.

The objective of our project is to use Bayesian modeling to forecast the variance and expected value of case counts in a geographic area over a specified time frame, such as one year.  Features may include tick prevalence, climate and weather data, % population that is rural, the age distribution of the population (Lyme is most commmon in children and adults aged 55-69), and others that we will identify through research.  

# Motivation

Results from this project can help public health authorities account for or plan around certain seasonal trends or become aware of certain upticks in disease prevalence. For example, Virginia is considered a high incidence state for Lyme disease, being able to predict or forecast disease occurrences could help state health departments to mobilize educational material in high incidence jurisdictions and help prevent citizens from being exposed to an infected blacklegged tick bite, which causes Lyme disease. Moreover, being able to forecast or predict case counts will also help health care providers to plan out and stock antibiotic treatments so the disease can be detected early and treated in a timely manner. Additionally, since pre-exposure prophylaxis vaccines are being developed for Lyme disease, the CDC will likely offer these vaccines to localities with high incidence of Lyme. Our results can also aid in predicting places that would most benefit from receiving the vaccine.  

# Data

Our core dataset will be the CDC "County Level Lyme Disease Data 2010-2019", which reports the number of cases.  This is a small file that we will augment with feature data collected from state and local public health sites, the US Census, weather agencies, and other relevant sources. 

# Foresight

We don't foresee needing to use any extensive computational resources for this project, however, if time permits, we could experiment with working on the cloud using AWS or Azure to simulate working with prediction data in a productionized environment. Some bottleneck that this project might encounter could be data size or undocumented stretches of data where new electronic processes emerged, such as retroactive upload of case counts which could lead to artificial inflation of cases, or changes in policies and disease classification per Morbidity and Mortality Weekly Report (MMRW) which lead to new threshold of cases being counted. 

Our strategy is to use the county as the level of analysis and to collect county-level data.  The primary challenge will be getting enough richness and precision in the data to make predictions that enhance what public health experts already know.  Can we reduce the time it takes to detect an increase in the disease, whether it is a seasonal change or one that is long-term?  Can we make forecasts more reliable?  Can we identify healthcare utilization patterns that could predict an uptick?  Certain features that would add value are extremely costly (only available from vendors), or not available at all because they include PII.  This information inlcudes linked data on lab tests ordered and results, and diagnoses for Lyme and related conditions, such as fatigue.  

####################

our 1-page project proposal can contain any of your thoughts for your project. There is no prescribed structure for the document. Here are some suggestions and ideas for you as you get started. I hesitate to assign point/percentage weights to each of these three categories. Different "types" of projects will emphasize different areas.
1. *Data:* are your data "interesting?"
For example:
- is your data set large (e.g. rows and/or columns, total filesize, etc.)
- is your data set rare, expensive, or in some sense hard to come by?
- is your data set interesting for some other reason (needs a special data type in Python, etc.)
2. *Motivation:* why will people care about your work?
You might address the following points:
- is your goal primarily parameter inference or prediction/forecasting?
- are you interested in making causal conclusions?
- why will your insights matter? (socially, economically, etc.)
- which aspects of your project are theoretical? which are more applied?
- are you genuinely interested in this topic? will your enthusiasm be evident?
3. *Foresight:* how will this project turn out, and what will be the primary challenges be?
You don't need to be able to answer all of these, but you should definitely start thinking about them:
- Will you be able to get close to "state of the art"
- What will your project's primary shortcoming be? Will it be excusable?
- What is/are the "bottleneck(s)" of your project (e.g. theory, computations, data size, etc.) How will you resolve these issues?
- Do your group members have complementary skill sets?
- Will you require some special resource (computer cluster access, database access, etc.)


  

