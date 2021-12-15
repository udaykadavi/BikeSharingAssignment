# BikeSharing Assignment


## Table of Contents
* [General Info](#general-information)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information

Background & Data:

A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state.

In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.

They have contracted a consulting company to understand the factors on which the demand for these shared bikes depends. Specifically, they want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:

- Which variables are significant in predicting the demand for shared bikes
- How well those variables describe the bike demands

Based on various meteorological surveys and people's styles, the service provider firm has gathered a large dataset on daily bike demands across the American market based on some factors. 

***Business Goal:***
You are required to model the demand for shared bikes with the available independent variables. It will be used by the management to understand how exactly the demands vary with different features. They can accordingly manipulate the business strategy to meet the demand levels and meet the customer's expectations. Further, the model will be a good way for management to understand the demand dynamics of a new market. 
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
 Final list of variables in decreasing order of size of impact(positive or negative)

- **weathersit_3[extreme weather conditions for biking]:**   -1.330571 (Negative effect)
- **yr[Year 2019]:**              1.051845 (Positive effect)
- **season_4[Winter]:**        0.724146 (Positive effect)
- **mnth_9[Sep]:**         0.538348 (Positive effect)
- **season_2[Summer]:**        0.525488 (Positive effect)
- **atemp[Feels like temperature]:**           0.412762 (Positive effect)
- **holiday[Holiday flag]:**        -0.385588 (Negative effect)
- **season_3[ZFall]:**        0.377814 (Positive effect)
- **weathersit_2[Cloudy weather]:**   -0.362133 (Negative effect)
- **mnth_8[Aug]:**          0.277839 (Positive effect)
- **mnth_5[May]:**          0.209645 (Positive effect)
- **mnth_6[Jun]:**          0.195376 (Positive effect)
- **mnth_10[Oct]:**         0.177703 (Positive effect)
- **mnth_3[Mar]:**          0.170554 (Positive effect)

Overall we can see that broadly, the factors that have an effect on bike sharing demand are weather & climate conditions, along with some seasonality factors like holiday and the year 2019
<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
Python libraries used:
- pandas
- numpy
- matplotlib
- seaborn
- skelearn
- statsmodels
- warnings

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements

This assignment is part of the Linear Regression module in the Master's in Ml & AI


## Contact
Created by [@udaykadavi] - feel free to contact me!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->