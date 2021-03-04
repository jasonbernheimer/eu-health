# eu-health

Well hello friends!

Our Research Question: Does the proportion of primary care providers have an impact on health care spending on a country level basis. 

Conjecture: More primary care providers = less health care spending

OECD website: < https://data.oecd.org/searchresults/?r=+f/type/datasets >

Start looking at different OECD data and the things we can control for (could maybe do for between years as well).

1) Introduction: introduces the general topic, specifies your specific research question, and discusses briefly how you answer it and your findings.

2) Optional, and discouraged, literature review: COPY JASONS

3) Data: description of the data you’ll use in your analysis. You should provide summary statistics of key variables used and discuss any important features of the data (e.g., problems or limitations, things that stand out that might impact the analysis). You might include a graph or graphs to support your explanations. See below for additional details.

4) Methods: description of the econometric methods you use to answer your research question. You should discus whatever regression equation(s) you estimate. If there are obvious limitations to your methods or important or controversial assumptions required, you should discuss these as well. Note that the data and methods sections can be combined or separate. Choose the structure you feel best presents your research.

5) Results: present the results of your research. What is the answer to your research question? You should include table(s) of coefficients and some measure of significance (e.g., standard errors, *’s to indicate p-values). You should discuss the economic meaning of your results. That is, do not simply report a coefficient of 0.123. You need to interpret what 0.123 means, explain if it is statistically significant, and explain what real-world importance it carries (e.g., is 0.123 a lot or a little in the context of your question?). What are the limitations of your results? For example, are you missing a key variable that might impact your results? If so, what are you missing and how might this impact your results (e.g., would your results be “weaker” or “stronger” if you had the missing key variable)?

6) Conclusion: summarize your research question and answer, and briefly discuss areas of potential further research.


List of ideas for other variables:
- public/private healthcare or social protection
- childhood vaccination rates
- age/life expetency
- health education programs
- avoidable deaths
- prices of health equipment
- obesity/bad health
- 

How many of these are accounted for by country fixed effects?


To Do: ONLY LOOK AT 2015-2017

Look for what make sense to measure, for all the countries we need (most should be listed in line 147 as countries Keep). Jason already did this for the ratio of primary care to specialists (can see on line 194 in measures)

Write down variable codes! 

Un-commment and run the lines:

44-48 Nora

50-51 Bella

53-54 Jason

Then look through cost table and look at variables

Maps!! We gotta make global maps :) Nora has got it. We just need country lines, don't need state or county data. OECD 3 digit country code called "location" will need to match with map

Notes: 
1. Health spending: measures the final consumption of health care goods and services (i.e. current health expenditure) including personal health care (curative care, rehabilitative care, long-term care, ancillary services and medical goods) and collective services (prevention and public health services as well as health administration), but excluding spending on investments. Health care is financed through a mix of financing arrangements including government spending and compulsory health insurance (“Government/compulsory”) as well as voluntary health insurance and private funds such as households’ out-of-pocket payments, NGOs and private corporations (“Voluntary”). This indicator is presented as a total and by type of financing (“Government/compulsory”, “Voluntary”, “Out-of-pocket”) and is measured as a share of GDP, as a share of total health spending and in USD per capita (using economy-wide PPPs).

2. Health expenditure and financing: Health spending by disease
This dataset presents data on expenditure by disease, age and gender under the System of Health Accounts (SHA) Framework. Current health spending by disease (ICD) includes inpatient/hospital spending by disease, outpatient/ambulatory spending by disease, medical goods spending by disease, and current health spending by age.
https://www.oecd-ilibrary.org/social-issues-migration-health/data/health-expenditure-and-financing/health-spending-by-disease_beeaad76-en. Have to download datasets for each years. 

3. 