# Estimating the Occurrence of Lyme Disease

## Project Proposal for DS 6040

## Uyen Nguyen and Carol Moore

## June 17, 2022

# Description

We will develop a model to estimate the number of new Lyme disease cases at the county level in the U.S. Because Lyme disease incidence is believed to be undercounted, the true case count will be modeled as a censored or latent variable. The model will incorporate key predictors of Lyme disease risk including tick populations, climate and weather, percentage of the population that is rural, and the age distribution of the population (Lyme is most common in children and adults aged 55-69).

# Motivation

The occurrence of Lyme disease is difficult to assess and predict. A study covering 2010-2018 found that Lyme diagnoses in insurance claims data were 6 to 8 times more frequent than in public health surveillance reports. Although the CDC has recently started to incorporate insurance claims into its national estimates, undercounting is still an acknowledged problem in epidemiological reporting, especially in low-incidence states. An additional source of undercounting is that Lyme testing is subject to high error rates, leading to under-diagnosis. According to the advocacy group Lymedisease.org, 20% to 30% of tests for a Lyme antibody are false negatives because the disease can suppress the immune system.
Understanding the incidence of Lyme can help health officials plan for education campaigns to help prevent citizens from being exposed to an infected blacklegged tick bite. It could also help health care providers plan out and stock antibiotic treatments so the disease can be detected early and treated in a timely manner. Additionally, since pre-exposure prophylaxis vaccines are being developed for Lyme disease, the CDC will likely offer these vaccines to localities with high incidence of Lyme. Our results could aid in determining places that would most benefit from receiving the vaccine.

# Data

For official case counts, we plan to use the CDC "County Level Lyme Disease Data 2010-2019", which reports the number of confirmed and probable cases on an annual basis. We will augment epidemiological data with features collected from state and local public health sites, the US Census and the National Weather Service. Ongoing estimates of tick populations are available from the National Ecological Observatory Network.

Our ideal dataset would combine public health surveillance data with insurance claims to get a holistic view of the number of diagnosed and potential cases. However, insurance claims data are costly and highly restricted. Files accessible to the public include the Synthetic Healthcare Database for Research (Agency for Healthcare Research and Quality). This data set includes diagnoses and is intended to replicate the structure and marginal distributions of original insurance claims data. However, it does not apply to the state or local levels.
Given limitations on insurance claims data, we need to treat the case count as a latent variable. We will combine available insurance data with the results of past studies using claims data to inform our estimate of the true case count.

# Foresight

One challenge that case-count methods and disease classification change over time, which lead to new thresholds of cases being counted. We will need to research and adjust for such changes in our data. We don't foresee needing to use any extensive computational resources for this project, however, if time permits, we could experiment with working on the cloud using AWS or Azure to simulate working with prediction data in a productionized environment.
