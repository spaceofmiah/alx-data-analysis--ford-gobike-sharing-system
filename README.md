# Ford GoBike Sharing System

## Dataset

This data set includes information about individual rides made in a bike-sharing system covering the greater San Francisco Bay area.

## Summary of Findings

Ford GoBike Sharing System recorded a total of 183,412 ( one hundred and eighty thousand, four hundred and twelve ) rides for Febraury, 2019. Majority of the record tracked are for Millenials who are subscribers to the ride sharing system. Most ride happens on Tuesdays and Thursday at 8am and 5pm respectively. The busiest route has a record of 337 and most ride start station was tracked from **Market St at 10th St**

## Key Insights for Presentation

In the presentation a couple of question. The answered questions spans across

- Demography
- Rides Metrics
- Route/Trip Analytics

## Understanding Code Base

All exploration are done in `exploratory.ipynb` file. The exploration approach taken is 

- Define: which says / answers - What do you want to do ?
- Prepare: fine tunes the dataset to a subset of variable that's relevant to the exploration definition
- Confirm/Evaluate: Checks that the preparation step is as neeeded to proceed with further exploration
- Plot (optional) : Only done when necessary to find trends and graphically reconfirm findings from evaluation step

For ease in understanding our exploration there's an `explanatory.ipynb` file. This file relays findings gotten from `exploratory.ipynb` file in a presentable and easily comprehensible manner.

## Libraries

- matplotlib
- seaborn
- pandas
- numpy


## TODO

Explore `bike_id` variable and see if it can be used to answer

- Are the number of rides affected by the number of bike available ?
- Is there any correlation between bike usage and ride duration ?
- Could the decrease in other station be an issue of bike unavailability ?


