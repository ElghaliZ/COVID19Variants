# COVID19Variants

The projects code is structured in 6 main components. It is advised to run them successively.

1.Design of the independent and dependent variables: creates the feature set and the dependent variable which is here the count of cases per million
2.Summary statistics, distribution and sensitivity analysis: enables a descriptive analysis of the variables obtained
3.Variants distribution evolution: plots the distribution of variants over time in every country
4.Waves heterogeneity and entropy: analyzes infection waves in every country with their heterogeneity and entropy values
5.Predictive model - 1 week: Designs the predictive model based on 1 week observation period
6.Predictive model - 2 weeks: Designs the predictive model based on 2 weeks observation period

The folder "generated_data" gathers the data sets progressively generated at every step of the program. A generated data set could re-used in the following parts of program without being re-computed.

To work successfully, the program needs:
- GISAID SARS-CoV-2 sequence Metadata obtained from: https://www.gisaid.org/
- Our World in Data COVID-19 database obtained from: https://ourworldindata.org/coronavirus
- Our World in Data on gathering restrictions database obtained from: https://ourworldindata.org/grapher/public-gathering-rules-covid
- Our World in Data on public events restrictions database obtained from: https://ourworldindata.org/covid-cancel-public-events
