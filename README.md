# DS-6040-Project

Your 1-page project proposal can contain any of your thoughts for your project. There is no prescribed structure for the document. Here are some suggestions and ideas for you as you get started. I hesitate to assign point/percentage weights to each of these three categories. Different "types" of projects will emphasize different areas.

We would like to apply Bayesian Machine Learning on health-related data for this project, specifically health questions available through public sources or government open-data portals. We have considered several benefits for using public facing data for the project, such as ease of data acquisition, promotion of data transparency between organizations and citizens, along with prospect of reproducible research, to name a few. However, some disadvantages that come packaged with these nice pluses could be the lack of standardization between datasets (agency dependent), missing data without context, lack of descriptions on major events that could impact data or data quality and so on. Some data wrangling is necessary to remedy some of the disadvantages mentioned, but if there is too much missing data in any specific features that are relevant to the analysis and can't be saved using imputation, we might have to rethink feature selection or switch to another dataset entirely. Our project will mainly deal with forecast or prediction of disease counts for a particular national notifiable disease over a period of time.  

1. *Data:* are your data "interesting?"
For example:
- is your data set large (e.g. rows and/or columns, total filesize, etc.)
- is your data set rare, expensive, or in some sense hard to come by?
- is your data set interesting for some other reason (needs a special data type in Python, etc.)

Since our focus mainly resides within the realm of national notifiable disease, results from this project can help public health authorities account for or plan around certain seasonal trends or become aware of certain upticks in disease prevalence. For example, Virginia is considered a high incidence state for Lyme disease, being able to predict or forecast disease occurences could help state health departments to mobilize educational material in high incidence jurisdictions and help prevent citizen from being exposed to an infected blacklegged tick bite, which causes Lyme disease. Moreover, being able to forecast or predict case counts will also help health care providers to plan out and stock antibiotic treatments so the disease can be detected early and treated in a timely manner. Additionally, since pre-exposure prophylaxis vaccines are being developed for Lyme disease, the CDC will likely offer these vaccines to localities with high incidence of Lyme. Our results can also aid in predicting places that would most benefit from receiving the vaccine.    

2. *Motivation:* why will people care about your work?
You might address the following points:
- is your goal primarily parameter inference or prediction/forecasting?
- are you interested in making causal conclusions?
- why will your insights matter? (socially, economically, etc.)
- which aspects of your project are theoretical? which are more applied?
- are you genuinely interested in this topic? will your enthusiasm be evident?

We don't foresee needing to use any extensive computational resources for this project, however, if time permits, we could experiment with working on the cloud using AWS or Azure to simulate working with prediction data in a productionized environment. Some bottleneck that this project might encounter could be data size or undocumented stretches of data where new electronic processes emerged, such as retroactive upload of case counts which could lead to artificial inflation of cases, or changes in policies and disease classification per Morbidity and Mortality Weekly Report (MMRW) which lead to new threshold of cases being counted.   

3. *Foresight:* how will this project turn out, and what will be the primary challenges be?
You don't need to be able to answer all of these, but you should definitely start thinking about them:
- Will you be able to get close to "state of the art"
- What will your project's primary shortcoming be? Will it be excusable?
- What is/are the "bottleneck(s)" of your project (e.g. theory, computations, data size, etc.) How will you resolve these issues?
- Do your group members have complementary skill sets?
- Will you require some special resource (computer cluster access, database access, etc.)
