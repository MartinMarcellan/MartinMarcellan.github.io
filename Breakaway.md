---
layout: single
title: Breakaway predictor
permalink: /breakaway/
---

## Model description
The goal of this classification project is to predict whether the breakaway survives and arrives to the finish line, or it is absorbed by the bunch. The breakaways are the usual way the humble teams get wins in world tour races, so predicting which stages are more suitable for a breakaway to arrive can have a big impact on the tactics of a team, especially in a grand tour where the energy management is crucial.

To make a prediction a definition of breakaway must be given: any rider or group of riders that get away from the bunch at a distance bigger than 20 kilometres from the finish line will be considered as breakaway. This means that if, for instance, a general classification rider manages to make a solo ride attacking 21 kilometres away from the finish it will be classified as a breakaway win for this classification model.

The independent variables used to make the predictions are the following ones
- Distance of the stage measured in kilometres.
- Vertical ascension of the stage measured in meters.
- Profile score of the stage given by [Pro Cycling Stats](https://www.procyclingstats.com/).
- The stage number.
- The date in when the stage is held.
- A standarized name of the race.
  
Regarding to the race name standardization, a standard name has been assigned to each race to prevent races that got their name changed be considered as different races. For example, the Benelux Tour, which was called Eneco Tour from 2005 to 2015, BinckBank Tour from 2016 to 2020 and Renewi Tour in 2023, will be called Benelux Tour as in 2021 to train the model.

The data used to adjust the model consists of all the races that have all the variables explained above. Vertical ascension meters and PCS profile score are not available for most of the races from 2016 and earlier, so these races are filtered.

The adjusted model has an accuracy of 82% which I believe is quite acceptable knowing that factors like the quality of the riders in the race, the strength or interest of the sprinters’ teams in keeping the breakaway controlled or the quality and quantity of the riders in the breakaway are not considered.

Predictions made by this model are available in the posts section of the web, where predictions for grand tours from Tour de France 2023 are shown.

| Race                 | Success rate | Post                                                                           |
|----------------------|--------------|--------------------------------------------------------------------------------|
| Tour de France 2023  | 85%          | [Breakaway predictions]({% post_url 2023-06-30-Tour-breakaway-prediction %})   |
| Vuelta a España 2023 | 79%          | [Breakaway predictions]({% post_url 2023-08-25-Vuelta-breakaway-prediction %}) |