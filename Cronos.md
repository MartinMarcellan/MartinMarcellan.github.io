---
layout: single
title: Individual Time Trial Prediction
permalink: /itt/
---

Time trials are a special kind of race, each rider fights alone against the clock with the goal of covering the route spending the less possible time. It is special because it does not involve team tactics, just effort management trying to finish the stage as empty as possible. This conditions make the time trial suitable for predictions as normally riders who fight for the win or the general classification do their best. The goal of this model is to predict as closely as possible the mean speed of each rider starting a time trial.

### Model description

To build the model many factors have been taken into account, all of them taken from the database described at the home page. These factors can be divided into three groups, route factors, rider factors and predicted factors.

Despite some riders are called time trial specialists not all the time trials suit them for equal, some of them prefer short and flat routes, while others tend to perform better in longer and hillier routes, so the route is a decisive factor, and the variables below are included to describe it as best as possible.

- Distance of the time trial measured in kilometres.
- Vertical ascension meters.
- Profile score of the time trial given by [Pro Cycling Stats](https://www.procyclingstats.com/).
- The date in which the time trial was held. 
- UCI Category of the race.
- Race nationality.
- Race length in terms of how many stages have been ridden and how many are left to ride.

The historic performance of each rider affects the future performances, so many coefficients have been created to summarize the past time trials of each rider.

- Rider age at the moment he rode the time trial.
-  Rider nationality.
- Team of the rider and its category.
- Number of time trials ridden in the past and amount of UCI points obtained in those. 
- Rider time trial performance coefficient.
- Rider time trial performance coefficient regarding only recent races.
- Rider time trial performance coefficient in similar routes.
- Rider time trial performance coefficient in similar time of the year.

Finally, some generic predictions are made to help the model estimate the speed of each rider. The expected mean velocity is calculated considering the distance and the vertical ascension meters and the expected winning speed is calculated by using distance, vertical ascension meters and predicted mean velocity.

All these factors sum up to 22 different variables. Adding to the variables, some races and riders are discarded in order to gain precision. First, almost all the national championships are discarded due to the lack of a considerable amount of professional riders takin part in them. Secondly, races of .2 category are also discarded for the same reason. Thirdly, all the races with missing data and riders who did not start or finish the race are also discarded. Lastly, riders riding for third tier teams are discarded.

### Results

With all this said, the model has a mean error of 2.198% and a coefficient of determination of 0.97. The prediction results are not as good as they look due to the multiple factors that have not been considered. An error of 2.198% can lead to deviations of more than a minute in one hour time trials.

### Ways of improvement 

The result would be much better if data to model the following factors would be available.

- Meteorology: Rain, wind, humidity and temperature have a great influence on the performance of the riders.
- A record of mechanical accidents and crashes could help to explain some bad results that condition the predictions.
- A record of the riders who really went as deep as they could to discard the results of riders who did not gave their best in the race.
- A gpx file of each route to be able to describe better the route, including things like number of turns or more data about the climbs.
- Many other smaller factors like the starting order that influence the race in a minor way.
