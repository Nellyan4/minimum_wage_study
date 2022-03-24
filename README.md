# minimum_wage_study
Project name: Study on the effect of the minimum wage

Project member: Xi Yan, Pang-Cheng Liu

## Access to final report
[Final report (jupyter notebook)](https://github.com/Nellyan4/minimum_wage_study/blob/main/Final.ipynb)

Please open the jupyter notebook in local machine, since Altair charts are rendered via javascript, and github scrubs all javascript output from display. Unfortunately, Altair has no control over that policy

[Recorded presentation in Youtube](https://youtu.be/c303cyhCUzU)

## Key Findings:
1. Although the nominal minimum wage increases throughout decades, the real minimum wage does not increase from 1968 to 2020.
2. Democratic states generally have higher minimum wage than Republican states.
3. Since the minimum wage on Republican States barely increases from 1970 to 2020, considering the inflation, the minimum wage workers earn less now than 1970 in Republican states.
4. The movement of labor productivity in individual state follows the minimum wage, which indicates a positive correlation between these two measures.
5. It is difficult to find the correlation between unemployment rate and the real minimum wage due to volatility of unemployment rate.

## Implications of Findings:
Democratic state and governors have done sufficient work to increase the minimum wage so that to protect their workers from being harm by the inflation. Yet, due to the unchanged minimum wage in many Republican states, workers in those states are harmed by earning less hourly rate from 1970 and 2020. This needs to be changed in Republican states.

The increases of minimum wage could be beneficial to labor productivity, as exhibited in data. State governors should not be too afraid to increase minimum wage since the increase in labor productivity could substitute the cost for labor.

## Motivation

Xi Yan spent his undergraduate study at the University of Washington in Seattle. He served as a dishwasher for almost two years in the campus cafeteria. The hourly rate for a student dishwasher at the University of Washington is 16 dollar, a little bit higher than the Washington State minimum wage. When he begins his graduate study at Carnegie Mellon University, he serves as the Teaching Assistant of one of the Statistics Classes, his hourly rate for being a Teaching Assistant is 15 dollar, a dollar less than his previous job as a dishwasher. He then found out that the minimum wage of Pennsylvania State is only 7.25 dollar. At that moment, Xi Yan was irritated and wanted to rather work as a dishwasher in Washington State.

It is unfair, that we all live in the United States, and the prices for commodities and foods do not vary a lot from state to state. The minimum wage, however, in some states is over 100% than some other states.

However, the State of Pennsylvania persists in keeping the minimum wage to be $7.25 for decades. People are urging an increase in the minimum wage, yet some scholars argue that a minimum wage increase is not necessary or it would not affect labor productivity or it would even make people be lazier.

Therefore, in this project, we want to know **how does (increasing) the minimum wage really affects people and the industry?** Is it necessary for a state government to increase the minimum wage? If we are able to figure this out, we could draft a policy memo to propose our idea to the state governors so they might be able to return benefits to all hard-working workers.

## Related Work

We find out about this topic through our personal experience and also the increasing minimum wage topic is popular in the State of Pennsylvania. We also find many academic articles that discuss minimum wage.

Related news:
1. [Related news articles: Gov. Wolf Fulfills Commitment to Raise Minimum Wage for Commonwealth Workers](https://www.governor.pa.gov/newsroom/gov-wolf-fulfills-commitment-to-raise-minimum-wage-for-commonwealth-workers/#:~:text=Overall%2C%2030%20other%20states%20have,with%20planned%20increases%20for%202022) (Thank god! Finally!)
2. [Franklin & Marshall College Poll: March 2021 that 67% register voters support increasing minimum wage](https://www.fandm.edu/uploads/files/463875674302125332-fmmarch2021-summaryoffindings.pdf)
3. [A Regional Minimum Wage](https://www.thirdway.org/memo/a-regional-minimum-wage?campaign_id=9&amp;emc=edit_nn_20210317&amp;instance_id=28148&amp;nl=the-morning%C2%AEi_id=61152705&amp;segment_id=53576&amp;te=1&amp;user_id=581dce38e6e45ed65bf9ab3cd49f9fe4)

Related academic articles:
1. [Raising the standard: Minimum wages and firm productivity](https://www.sciencedirect.com/science/article/abs/pii/S0927537116303487?via%3Dihub)
2. [Income Inequality, Ethnic Diversity, and State Minimum Wages](https://onlinelibrary.wiley.com/doi/10.1111/ssqu.12580)

## Data

[State productivity data](https://www.bls.gov/lpc/state-productivity.htm):
- The data is in one table 
- It is yearly data from 2007 to 2020 By States
- Rows: around 2000
- Columns: 19
- The data is clean and only need a little cleaning then is ready to be analyzed

| Area Name | Measure | 2007 | … | 2020 |
| ----------- | ----------- | ----------- | ----------- | ----------- |
| Alabama | Employment | -3.2 | … | -4.6 |
| Alabama | Hourly Labor Compensation | 4.7 | … | 6.4 |


[Unemployment](https://www.bls.gov/charts/state-employment-and-unemployment/state-unemployment-rates-animated.htm):
- Everything is in one table
- It is unemployment data by year by states
- Columns: 122
- Rows: 53

[Minimum Wages](https://www.kaggle.com/lislejoem/us-minimum-wage-by-state-from-1968-to-2017):
- Everything is in one table
- It is minimum wage data by year by states
- Columns: 15
- Rows: 2863
