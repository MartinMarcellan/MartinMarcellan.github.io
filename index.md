---
layout: default
---

# Classification: is the stage suitable for the breakaway to arrive?
## Model description
The goal of this classification project is to predict whether the breakaway survives and arrives to the finish line, or it is absorbed by the bunch. The breakaways are the usual way the humble teams get wins in world tour races, so predicting which stages are more suitable for a breakaway to arrive can have a big impact on the tactics of a team, especially in a grand tour where the energy management is crucial.

To make a prediction a definition of breakaway must be given: any rider or group of riders that get away from the bunch at a distance bigger than 20 kilometres from the finish line will be considered as breakaway. This means that if, for instance, a general classification rider manages to make a solo ride attacking 21 kilometres away from the finish it will be classified as a breakaway win for this classification model.

The independent variables used to make the predictions are the following ones
-	Distance of the stage measured in kilometres.
- Vertical ascension of the stage measured in meters.
- Profile score of the stage given by [Pro Cycling Stats](https://www.procyclingstats.com/).
- The stage number.
- The date in when the stage is held.
- A standarized name of the race.
  
Regarding to the race name standardization, a standard name has been assigned to each race to prevent races that got their name changed be considered as different races. For example, the Benelux Tour, which was called Eneco Tour from 2005 to 2015, BinckBank Tour from 2016 to 2020 and Renewi Tour in 2023, will be called Benelux Tour as in 2021 to train the model.

The adjusted model has an accuracy of 82% which I believe is quite acceptable knowing that factors like the quality of the riders in the race, the strength or interest of the sprinters’ teams in keeping the breakaway controlled or the quality and quantity of the riders in the breakaway are not considered.
## Prediction
As an example, here are the predictions for the 2023 Tour de France:

![Imagen con el grafico de las predicciones](/assets/images/Prediccion.png)

As it can be seen, there are many stages that have high probability of a breakaway win, so stage hunters should target stages like stage 10, stage 12 or stage 14 which are the most probable ones.

## Prediction analysis
The prediction does not give many hopes to the breakaway in the first four racing days as the teams aiming for the leader jersey will not allow big breakaway groups. The second stage, however, has a remarkable breakaway probability, this is because of the presence of the climb of Jaizkibel which will be crowned at only 17.5 kilometres away from the finish line. The possibility of a small strong group being formed during the climb at more than 20 kilometres away from the line is not negligible. All the stage profile photos are taken from the [Tour de France website](https://www.letour.fr/en/).

![Imagen del perfil de la etapa 2](/assets/images/ET2.jpeg) 

The fourth stage is the one with less breakaway possibilities, this can be explained easily, is the first stage of the Tour that is almost completely flat so all sprinter teams will be aiming for it. The third stage is also suitable for sprinters but is has some hills that give a small chance to the breakaway.

![Imagen del perfil de la etapa 4](/assets/images/ET4.jpeg) 

The following two stages are the first ones with predicted breakaway win. Stage number five goes from Pau to Laruns and as in second stage, the reason for such high breakaway win probability is the presence of Col de Marie Blanque summit 19 kilometres away from the finish. The stage has two possibilities for a breakaway stage win:
-	Early breakaway makes it to the end.
-	As in 2020 a small group of favourites breaks from the peloton and manages to stay away from others.

![Imagen del perfil de la etapa 5](/assets/images/ET5.jpeg)  

The sixth stage has also two possible scenarios for a successful breakaway
-	Early breakaway manages to arrive like it did in a similar stage in 2015.
-	A strong group of not general classification contender climbers goes away from the peloton in Tourmalet.

![Imagen del perfil de la etapa 6](/assets/images/ET6.jpeg) 

Stages seven and eight are a great chance for sprinters to fight for stage wins.

The final stage of the first week carries the riders from Saint-Léonerd-de-Noblat to the climb of Puy de Dôme. A breakaway win is predicted so the model predicts some strong climber in the break who would be able to hold to their advantage with the general classification contenders who will try to distance each other in the last climb. 

![Imagen del perfil de la etapa 9](/assets/images/ET9.jpeg) 

Two of the three first stages of the second week have the highest breakaway probabilities of the race, both are quite similar: hilly stages that finish with large downhill or flat sections and both have around 3000 meters of climbing. The first kilometres of these stages are suitable form a group of punchy riders.

![Imagen del perfil de la etapa 12](/assets/images/ET12.jpeg) 

The last three stages of the second week are made for a general classification fight at the alps but the model considers that the Tour will follow the trend of the 2023 Giro and the high mountain stages are going to be won by breakaways.

Stage 13 finishes in the long climb of Grand Colombier which leaves the only possibility for the break to form way earlier and resist the high pace of the yellow jersey contenders’ teams. That is why this has the lower breakaway win probability of this second weekend stages.

![Imagen del perfil de la etapa 13](/assets/images/ET13.jpeg) 

In contrast, the next stage is suitable for long range attacks in the same way the stage featuring Col de Marie Blanque was: the hardest climb of the day is crowned 13 kilometres away from Morzine, the town where the finish is located. Leaving Two possible scenarios for a breakaway win: the early break or the long-range attack from a GC contender. 

![Imagen del perfil de la etapa 14](/assets/images/ET14.jpeg) 

The last stage of the second week ends with a climb to Saint-Gervais and has eight previous categorised climbs making it a great chance for an early breakaway. Is not probable for GC favourites to try an attack in Col de la Croix Fry or Col des Aravis, so the only chance for a breakaway win is the early break.

![Imagen del perfil de la etapa 15](/assets/images/ET15.jpeg) 

For the stages of the last week the model does not give many chances to breakaways. The only stage with predicted breakaway win is the first one, the one ending in Courchevel. As in other stages mentioned earlier, this stage can be won by an early breakaway formed in Col des Saises or Cormet de Roselend and by a GC contender who decides to launch his attack at the beginning of the long final climb to the Col de la Loze.

![Imagen del perfil de la etapa 17](/assets/images/ET17.jpeg) 

The rest of the stages of the final week are suitable for sprinters except the twentieth one, which will be the last chance for a change in the yellow jersey classification. Because of this the model does not give many chances to breakaways despite the large number of climbs throughout the stage.

![Imagen del perfil de la etapa 20](/assets/images/ET20.jpeg) 

## Conclusions

The model has performed with the expected accuracy as it predicted correctly 17 out of 20 stages a success rate of 85%. 

In the first race week the model predicted correctly all nine stages, there were only three stages with predicted breakaway win: 
  -	The fifth stage finishing in Laruns was won by Jai Hindley who was part of the break formed in the first part of the stage and managed to maintain the difference despite the attack of Jonas Vingegaard in the last climb of Col de Marie Blanque.
  -	Col du Tourmalet was decisive in the sixth stage, where Jonas Vingegaard launched an attack more than 20 kilometres away from the finish that allowed Tadej Pocagar and him to join the breakaway. In the end Pogacar managed to drop Vingegaard and secure the second breakaway win of the tour.
  - The last breakaway win of the first week arrived in the ninth stage. Michael Woods was the strongest rider of the break which was formed in the first kilometres of the day.

The second week of the Tour was predicted to be a very suitable week for the breakaways and so it was, the break of the day managed to stay away from the peloton in stages ten, twelve, thirteen and fifteen. The first error of the model came in the fourteenth stage which was won by Carlos Rodriguez who was not part of the break. 

The prediction error can be explained by the strategy Team Jumbo Visma adopted for this stage, one of the hardest of this years Tour: Jumbo Visma’s goal was to make the stage the hardest possible in order to repeat what they did in the hardest stages of last years tour, distance Pogacar as Vingegaard is stronger in long and hard days. This tactic resulted in not letting a  break full of climbers like Thibaut Pinot, Guillaume Martin, Mikel Landa, Michael Woods, Julian Alaphilippe, Tobias Halland Johannessen, Giulio Ciccone and many other gain enough time on the peloton to compete for the stage.

In the last week, the only stage which had a breakaway win predicted was won by the Austrian rider Felix Gall who came from the break. The model made two errors predicting not breakaway wins in the next two stages.
  - From Moûtiers to Bourg-en-Bresse, the eighteenth stage was expected to finish in a bunch sprint by the model but a break with three rouleurs such as Victor Campenaerts, Jonas Abrahamsen and Kasper Asgreen were able to steal the win. In the middle of the stage Pascal Eenkhoorn joined these three and played a key role in keeping the peloton away being able to maintain the break alive with an advantage over the peloton of less than a minute in most of the last kilometres.
  - The next day, after a really hard fight to form the breakaway, a big group including some of the main sprinters escaped from the peloton and made it to the finishing town of Poligny where Matej Mohoric won the stage.
