# Data science in cycling

## Classification: Is the stage suitable for the breakaway to arrive?
The goal of this classification project is to predict whether the breakaway survives and arrives to the finish line, or it is absorbed by the bunch. The breakaways are the usual way the humble teams get wins in world tour races, so predicting which stages are more suitable for a breakaway to arrive can have a big impact on the tactics of a team, especially in a grand tour where the energy management is crucial.

To make a prediction a definition of breakaway must be given: Any rider or group of riders that get away from the bunch at a distance bigger than 20 kilometres from the finish line will be considered as breakaway. This means that if, for example, a general classification rider manages to make a solo ride attacking 21 kilometres away from the finish it will be classified as a breakaway win for this classification model.

The independent variables used to make the predictions are the following ones
-	Distance of the stage measured in kilometres.
- Vertical ascension of the stage measured in meters.
- Profile score of the stage given by Pro Cycling Stats. (https://www.procyclingstats.com/)
- The stage number.
- The date in when the stage is held.
- A standarized name of the race.
  
Regarding to the race name standardization, a standard name has been assigned to each race to prevent races that got their name changed be considered as different races. For example, the Benelux Tour, which was called Eneco Tour from 2005 to 2015, BinckBank Tour from 2016 to 2020 and Renewi Tour in 2023, will be called Benelux Tour as in 2021 to train the model.

The adjusted model has an accuracy of 82% which I believe is quite acceptable knowing that factors like the quality of the riders in the race, the strength or interest of the sprinters’ teams in keeping the breakaway controlled or the quality and quantity of the riders in the breakaway are not considered.
As an example, here are the predictions for the 2023 Tour de France:

*** FOTO PREDICCIÓN *** 

The prediction does not give many hopes to the breakaway in the first four racing days as the teams aiming for the leader jersey will not allow big breakaway groups. The second stage, however, has a remarkable breakaway probability, this is because of the presence of the climb of Jaizkibel which will be crowned at only 17.5 kilometres away from the finish line. The possibility of a small strong group being formed during the climb at more than 20 kilometres away from the line is not negligible.

*** FOTO ETAPA 2 *** 

The fourth stage is the one with less breakaway possibilities, this can be explained easily, is the first stage of the Tour that is almost completely flat so all sprinter teams will be aiming for it. The third stage is also suitable for sprinters but is has some hills that give a small chance to the breakaway.

*** FOTO ETAPA 4 *** 

The following two stages are the first ones with predicted breakaway win. Stage number five goes from Pau to Laruns and as in second stage, the reason for such high breakaway win probability is the presence of Col de Marie Blanque summit 19 kilometres away from the finish. The stage has two possibilities for a breakaway stage win:
-	Early breakaway makes it to the end.
-	As in 2020 a small group of favourites breaks from the peloton and manages to stay away from others.

*** FOTO ETAPA 5 *** 

The sixth stage has also two possible scenarios for a successful breakaway:
-	Early breakaway manages to arrive like it did in a similar stage in 2015.
-	A strong group of not general classification contender climbers goes away from the peloton in Tourmalet.

*** FOTO ETAPA 6 *** 

Stages seven and eight are a great chance for sprinters to fight for stage wins.

The final stage of the first week carries the riders from Saint-Léonerd-de-Noblat to the climb of Puy de Dôme. A breakaway win is predicted so the model predicts some strong climber in the break who would be able to hold to their advantage with the general classification contenders who will try to distance each other in the last climb. 

*** FOTO ETAPA 9 ***

Two of the three first stages of the second week have the highest breakaway probabilities of the race, both are quite similar: Hilly stages that finish with large downhill or flat sections and both have around 3000 meters of climbing. The first kilometres of these stages are suitable form a group of punchy riders.

*** FOTO ETAPA 12 ***

The last three stages of the second week are made for a general classification fight at the alps but the model considers that the Tour will follow the trend of the 2023 Giro and the high mountain stages are going to be won by breakaways.

Stage 13 finishes in the long climb of Grand Colombier which leaves the only possibility for the break to form way earlier and resist the high pace of the yellow jersey contenders’ teams. That is why this has the lower breakaway win probability of this second weekend stages.

*** FOTO ETAPA 13 ***

In contrast, the next stage is suitable for long range attacks in the same way the stage featuring Col de Marie Blanque was: The hardest climb of the day is crowned 13 kilometres away from Morzine, the town where the finish is located. Leaving Two possible scenarios for a breakaway win: The early break or the long-range attack from a GC contender. 

*** FOTO ETAPA 14 ***

The last stage of the second week ends with a climb to Saint-Gervais and has eight previous categorised climbs making it a great chance for an early breakaway. Is not probable for GC favourites to try an attack in Col de la Croix Fry or Col des Aravis, so the only chance for a breakaway win is the early break.

*** FOTO ETAPA 15 ***

For the stages of the last week the model does not give many chances to breakaways. The only stage with predicted breakaway win is the first one, the one ending in Courchevel. As in other stages mentioned earlier, this stage can be won by an early breakaway formed in Col des Saises or Cormet de Roselend and by a GC contender who decides to launch his attack at the beginning of the long final climb to the Col de la Loze.

*** FOTO ETAPA 16 ***

The rest of the stages of the final week are suitable for sprinters except the twentieth one, which will be the las chance for a change in the yellow jersey classification. Because of this the model does not give many chances to breakaways despite the large number of climbs throughout the stage.

*** FOTO ETAPA 20 ***
