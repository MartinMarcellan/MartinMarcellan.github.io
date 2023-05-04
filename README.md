# Data science in cycling

## Classification: Is the stage suitable for the breakaway to arrive?
The goal of this classification is to decide whether the breakaway survives and arrives to the finish line, or it is absorbed by the bunch. The breakaways are the usual way the humble teams get wins in world tour races, so predicting which stages are more suitable for a breakaway to arrive can have a big impact on the tactics of a team, specially in a grand tour where the energy management is crucial.  
To make a prediction a definition of breakaway must be given: Any rider or group of riders that get away from the bunch at a distance bigger than 20 kilometres from the finish line will be considered as breakaway. This means that if, for example, a general classification rider manages to make a solo ride attacking 21 kilometres away from the finish it will be classified as a breakaway win for this classification model.  
The independent variables used to make the predictions are the following ones: Distance of the race or stage, the vertical ascension of the race, the stage number, the date, and the name of the race. The distance is measured in kilometres and the vertical ascension is measured in meters. Regarding to the race names, a standard name has been assigned to each race to prevent races that have got their name changed look like different races. For example, the Benelux tour which was called Eneco Tour from 2005 to 2015 and BinckBank Tour from 2016 to 2020, in this case, the name used to train the algorithm will be Benelux Tour.
wenas
