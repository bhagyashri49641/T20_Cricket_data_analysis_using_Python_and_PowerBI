# T20 Cricket Data- Power-BI Dashboard
## Problem Statement
- Finding the world's best 11 cricket players who fulfill the specified criteria to make an all-balanced team.
- Team must score at least 180 runs on an average based on T20 Cricket World Cup Data
- The team should be to defend 150 runs on an average.

## Parameter Estimation
Drawing from the T20 World Cup 2022 data, I aimed to identify top-performing Batters, Bowlers, and All-Rounders each with specific selection criteria.

OPENERS: they are the power hitters -> two players
filters - batting average, strike rate, balls faced, boundary %

ANCHORS /MIDDLE ORDER: -> Three players
filters - batting average, strike rate, balls faced, average balls faced

FINISHER / LOWER ORDER ANCHOR: -> one player
filters - batting average, batting strike rate, average balls faced, bowling strike rate

ALL-ROUNDERS /LOWER ORDER: -> two players
filters - batting average, batting strike rate, economy, bowling strike rate

SPECIALIST FAST BOWLERS: -> three players 11 filters - bowling average, bowling strike rate, economy, dot balls %

### Steps followed 
- Step 1: convert the JSON data into CSV format using Python libraries in jupyter notebook
- Step 2: clean data using pandas for Data Manipulation
- Step 3: Load the data into the power query editor for basic data transformations and to create required DAX measures
- Step 4: Create dashboard visuals with Power BI

Follow the link below to view the interactive Power BI dashboard 
#### Dashboard Link: https://www.novypro.com/project/cricketteamselection-power-bi




![t20_1](https://github.com/bhagyashri49641/T20_Cricket_data_analysis_using_Python_and_PowerBI/assets/53085622/48227e70-0efd-443b-a472-60fc5cfe3cc6)

![t20_2](https://github.com/bhagyashri49641/T20_Cricket_data_analysis_using_Python_and_PowerBI/assets/53085622/1119558c-904e-479b-b57b-5d60547b0283)

![t20_3](https://github.com/bhagyashri49641/T20_Cricket_data_analysis_using_Python_and_PowerBI/assets/53085622/2b7e45f1-40b2-4256-889d-ba904a7e98a6)

![t20_4](https://github.com/bhagyashri49641/T20_Cricket_data_analysis_using_Python_and_PowerBI/assets/53085622/9712ffd4-cadf-49b0-895d-4a4378ba2fab)

![t20_5](https://github.com/bhagyashri49641/T20_Cricket_data_analysis_using_Python_and_PowerBI/assets/53085622/59b46458-2a31-4a97-9562-2ef02f76b905)

![t20_6](https://github.com/bhagyashri49641/T20_Cricket_data_analysis_using_Python_and_PowerBI/assets/53085622/ce3172fd-f1d2-4e41-b575-a7af83cc0a6a)






