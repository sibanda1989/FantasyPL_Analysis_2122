# Fantasy Premier League Analysis
In this python notebook, I used python data analysis libraries to analyse and clean Fantasy Premier League data for the English Premier League season 2021-2022.

## The Process
Data was obtained from an [API](https://fantasy.premierleague.com/api/bootstrap-static/) using Python's requests library. There were various tables with different information on players, matches, teams etc but I cleaned it out and merged it to form one table with the information I needed. I used pandas and numpy in my cleaning and analysis, before exporting the clean dataset to Microsoft Power BI for further analysis.

## Useful Insights
Some interesting insights came out of the analysis:

- Goalkeepers presented the best value for money in terms of points returns vs cost
- Forwards were underwhelming during the season in question, providing the lowest value returns
- Wolves players Conor Coady (a defender), Jose Sa (a goalkeeper) topped the players list of returns vs cost
