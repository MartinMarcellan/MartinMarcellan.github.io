---
layout: single
title: Data visualization
permalink: /visualization/
---

The main goal of a plot should be to display information in an image concisely to the reader. The idea of this section is to show some plots that summarize the performance of riders, teams and nations throughout many years or in a selected year.

Before showing the plots, some concepts that will appear on them need to be clarified:

-	Grand Tours (GT): The three races which are considered as grand tours are Giro d’Italia, Tour de France and Vuelta a España.

-	One week races: When referring to one week races the big seven one week races are considered, namely, Paris-Nice, Tirreno-Adriatico, Volta a Catalunya, Itzulia Basque Country, Tour de Romandie, Critérium du Dauphiné and Tour de Suisse. 

-	Monuments: Five one day races are the monuments: Milano-Sanremo, Ronde van Vlaanderen, Paris-Roubaix, Liège-Bastogne-Liège and Il Lombardia.

-	Race categories: The international cycling union (UCI) classifies the races in different categories, the first and highest category races are known as world tour races, marked as WT in the plots, and second category races are marked as PRO races.

-	Sprint: Indicates if the points were won in a race that finished in a bunch sprint. The same could have been done with a breakaway win but since not every rider that gets points in a race does not have to be part of the break the metric would not be useful.

Note: All the plots are interactive, you can click on them to show more information.

### Career points distribution:

Normally, riders are specialists in a certain type of races which means that most of the points they earn come from one category of one day races, stage race stage wins, general classifications or individual time trials. The goal of the plot is to help to classify the more balanced riders by showing the UCI points they earn by category and to provide an extra breakdown of those UCI points.

As an example, Peter Sagan decided to end his road cycling career at the end of the 2023 season, he was classified as a one day races specialist as well as a sprinter, which allowed him to win many stages in different stage races. As shown in the plot, most of his points were won in one day races, specifically in world tour one day races. On the contrary, the team time trials were not his speciality, and he did not get almost any point compared to the other categories.

{% include Sagan_sb.html %}

The best rider in the world, Tadej Pogacar, is a complete rider, he can win in almost any field, so his point distribution plot is quite balanced.

{% include Pogacar_sb.html %}

In the current peloton there are many other riders that can win in many fields, such as Remco Evenepoel or Primoz Roglic.

{% include Evenepoel_sb.html %}

{% include Roglic_sb.html %}

Some riders are still specialists in their fields, for example, a pure sprinter like Jasper Philipsen, an individual time trial specialist like Stefan Bissegger, a one day race master like Mathieu van der Poel and a general classification rider like Mikel Landa.

{% include Philipsen_sb.html %}

As a sprint specialist, Philipsen’s most points come from one day races and stage wins, most of them won in bunch sprints.

{% include Bissegger_sb.html %}

Bissegger is a clear example of a time trial specialist, almost 70% of his career points come from individual time trials.

{% include MvdP_sb.html %}

More than 8 out of ten of Van der Poel’s points were obtained in one day races.

{% include Landa_sb.html %}

Landa is a pure climber so most of his points come from general classifications.

### Best teams boxplot:

In statistics, an outlier is a data point that differs significantly from other observations. One way to spot them is by using a boxplot type of plot, in the resulting graphic the outlying data points will be displayed outside the box. Applied to cycling, this plot is useful to spot the best riders of each team, as they will appear as outliers. Below a plot including the best ten teams of 2023 season is showed.

{% include Boxplot.html %}

The plot shows as points the leaders of each team. It also shows how the team roles are distributed, for example, Alpecin-Deceuninck team has the lowest point median but is not the worst team in terms of UCI points because of the four riders that scored more than a hundred points each.

The best two teams in the world, UAE Team Emirates and Jumbo-Visma have a lot of riders with more than a hundred points, but the median punctuation of the UAE riders is much higher than the median of Jumbo-Visma, thus excluding the leaders, the rest of the riders get more points, resulting in a better ranking. 

### Team points breakdown:

Not only riders are specialists in certain types of races, teams also can be classified using the points breakdown shown below. The size of the boxes indicates the share of points the speciality or rider regarding the team total. The first example is the team that obtained the most points in 2023, UAE Team Emirates. In this case, the GC points are the most important ones as Pogacar, Almeida and Yates reached podium positions in grand tours. One day races are the second most important speciality due to the wins of Pogacar in monuments like Il Lombardia and Ronde van Vlaanderen and the great results obtained by Hirschi in numerous races. Stage wins are and team trials are not that important as in other teams like Alpecin-Deceuninck.

{% include UAE_tm.html %}

Alpecin-Deceuninck is a team dedicated to one day races and to winning stages without caring about the general classification or the team trials. As it can be seen in the boxplot and in the graph below Mathieu Van der Poel and Philipsen are great one day racers with great results in Milano-Sanremo, Ronde van Vlaanderen, Paris-Roubaix and the world championship. Regarding to the stage wins, Philipsen won four stages at the Tour de France and Caden Groves won one at the Giro d’Italia and three at the Vuelta a España.

{% include Alpecin_tm.html %}

### Historic performance analysis:

aqui

{% include Paves_QS.html %}

aqui

![Jumbo one week races performance](/assets/images/JUMBO_oneweek.png) 

aqui

{% include UAE_GT.html %}

aqui

{% include INEOS_GT.html %}

aqui

{% include FRANCE_GT.html %}

aqui