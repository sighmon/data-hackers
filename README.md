# Data Hackers
[GovHack 2017 entry for team DataHackers](https://2017.hackerspace.govhack.org/project/vaas-visualisation-atoabs-social-economics)

![Power BI dashboard for ATOh DataHackers](https://raw.githubusercontent.com/sighmon/data-hackers/master/screenshots/powerbi-dashboard.jpg)

## Source code

You can find the PowerBI source in the [source](source) folder.

To have a play with the reports yourself, sign up for a free 60-day trial of [PowerBI](https://powerbi.microsoft.com/en-us/) with a Microsoft account. Download the [desktop app](https://powerbi.microsoft.com/en-us/desktop/), and open either `ATOh_Dashboard_1.pbix` or `ATOh_Dashboard_2.pbix`. The first is our experiments with a dashboard, the second with forecasting.

## Proof of Concept

Currently, there is no clean way of visualising the ATO and ABS data. We are creating dashboards that will solve this issue and provide more visually appealing and easy to understand dashboards. 

The future is not predetermined, nor is it predictable, however, we can use the past, analyse the trend and predict the near future. Using ATO data for GovHack, we are aiming to predict the plausible future for 2030
It will try to analyse the following:
•    Demographic change (population growth, ageing, rental changes, marital status etc. for each suburb and state
•    Economic shifts in each suburb and state on how the tax income and return are changing.
And depict the changes and trend on Australian location map.


Below image shows the entity relationships between the different data headers from the ATO dataset. We have restructured the given data to some more usable data.

![Entity Relationships](https://raw.githubusercontent.com/sighmon/data-hackers/master/screenshots/entity-relationships.png)

Below image shows one of the dashboards created that visualise the ATO data in some easily comprehendable data. You can select different states and years. 

![Dashboard 1](https://raw.githubusercontent.com/sighmon/data-hackers/master/screenshots/dashboard1.png)

The below image shows a second dashboard with some more data represented in graphs and charts.

![Dashboard 2](https://raw.githubusercontent.com/sighmon/data-hackers/master/screenshots/dashboard2.png)

The below image shows how we can forecast the population in a given postcode for the next 10 years, with a confidence of 95% 

![Forecasting population](https://raw.githubusercontent.com/sighmon/data-hackers/master/screenshots/test-forecast-population.png)
