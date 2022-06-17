# Estimating the Occurrence of Lyme Disease

### Project Proposal for DS 6040

### Uyen Nguyen and Carol Moore

### June 17, 2022

## Description

We will develop a regression model to forecast the probability distribution of getting Lyme disease in a given state or county over a specified period of time.

Model features that measure Lyme disease risk include estimates of tick populations, climate and weather, percentage of the population that is rural, and the age distribution of the population (Lyme is most common in children and adults aged 55-69).

Information about false positives / negatives in testing, and discrepancies between public health data and insurance claims will be used to perform Bayesian updating.

## Motivation

The occurrence of Lyme disease is difficult to assess and predict, as is often controversial. Our goal is to better predict the risk of Lyme. A recent study covering 2010-2018 found that Lyme diagnoses in insurance claims data were 6 to 8 times more frequent than in public health surveillance reports (e.g., CDC). Further, Lyme testing is subject to high error rates and the disease is understood to be under-diagnosed. According to the advocacy group Lymedisease.org, 20% to 30% of tests for a Lyme antibody are false negatives because the disease can suppress the immune system. Delayed and under-treatment can lead to chronic Lyme disease, a debilitating condition, which advocates believe is drastically overlooked by doctors and epidemiologists.
Public health officials deploy educational material and help prevent citizens from being exposed to an infected blacklegged tick bite, which causes Lyme disease. It could also help health care providers to plan out and stock antibiotic treatments so the disease can be detected early and treated in a timely manner. Additionally, since pre-exposure prophylaxis vaccines are being developed for Lyme disease, the CDC will likely offer these vaccines to localities with high incidence of Lyme. Our results could aid in determining places that would most benefit from receiving the vaccine.

## Data

We will compile monthly data on case counts at the level of the state and county.
We will augment epidemiological data with feature collected from state and local public health sites, the US Census, weather agencies, health claims data, and other relevant sources.

Obtaining the health insurance data is more challenging and no ideal file is accessible due to cost and privacy restrictions. Datasets accessible to the public include the Synthetic Healthcare Database for Research (Agency for Healthcare Research and Quality). This data set includes diagnoses and is intended to replicate the structure and marginal distributions of original insurance claims data. However, this file does not apply to the state or local levels.

## Foresight

If monthly county level data are not adequate, we will use the CDC "County Level Lyme Disease Data 2010-2019", which reports the number of confirmed and probable cases on an annual basis.

The Synthetic Healthcare Database for research is, so far, our leading contender for claims data. To gain access, we must submit a signed user agreement to AHRQ for their review. If the review is delayed, we would need to fall back on another source.
If suitable health insurance data proves unavailable, we will use point estimates and confidence intervals from previous claims-based studies to develop synthetic datasets for Bayesian updating.

Another project risk that policies and disease classification change over time, which lead to new threshold of cases being counted. We will need to research and adjust for such changes in our data.

We don't foresee needing to use any extensive computational resources for this project, however, if time permits, we could experiment with working on the cloud using AWS or Azure to simulate working with prediction data in a productionized environment.
