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

### Career points distribution

Normally, riders are specialists in a certain type of races, which means that most of the points they earn come from one category of one day races, stage race stage wins, general classifications or individual time trials. The goal of the plot is to help to classify the more balanced riders by showing the UCI points they earn by category and to provide an extra breakdown of those UCI points.

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

### Best teams boxplot

In statistics, an outlier is a data point that differs significantly from other observations. One way to spot them is by using a boxplot type of plot, in the resulting graphic the outlying data points will be displayed outside the box. Applied to cycling, this plot is useful to spot the best riders of each team, as they will appear as outliers. Below a plot including the best ten teams of 2023 season is showed.

{% include Boxplot.html %}

The plot shows as points the leaders of each team. It also shows how the team roles are distributed, for example, Alpecin-Deceuninck team has the lowest point median but is not the worst team in terms of UCI points because of the four riders that scored more than a thousand points each.

The best two teams in the world, UAE Team Emirates and Jumbo-Visma have a lot of riders with more than a thousand points, but the median punctuation of the UAE riders is much higher than the median of Jumbo-Visma, thus excluding the leaders, the rest of the riders get more points, resulting in a better ranking. 

### Team points breakdown

Not only riders are specialists in certain types of races, teams also can be classified using the points breakdown shown below. The size of the boxes indicates the share of points the speciality or rider regarding the team total. The first example is the team that obtained the most points in 2023, UAE Team Emirates. In this case, the GC points are the most important ones as Pogacar, Almeida and Yates reached podium positions in grand tours. One day races are the second most important speciality due to the wins of Pogacar in monuments like Il Lombardia and Ronde van Vlaanderen and the great results obtained by Hirschi in numerous races. Stage wins are and team trials are not that important as in other teams like Alpecin-Deceuninck.

{% include UAE_tm.html %}

Alpecin-Deceuninck is a team dedicated to one day races and to winning stages without caring about the general classification or the team trials. As it can be seen in the boxplot and in the graph below Mathieu Van der Poel and Philipsen are great one day racers with great results in Milano-Sanremo, Ronde van Vlaanderen, Paris-Roubaix and the world championship. Regarding to the stage wins, Philipsen won four stages at the Tour de France and Caden Groves won one at the Giro d’Italia and three at the Vuelta a España.

{% include Alpecin_tm.html %}

### Team race days analysis

The best teams in the world take part in many races throughout the year and the distribution of which riders ride each race is crucial to give everyone a chance to ride as many races as desired and to avoid overloading riders with too many races. These plots are made to be a quick overview of the workload of each rider considering the age. 

In the first plot each point shows the age of the rider at the end of the season and the trail ends at the age the rider joined the team. For example, Shane Archbold is going to finish the season being almost 35 years old and as he joined the team in 2019, the wake ends at the age of almost 30. The green coloured riders are the new riders of the team, in this case, Bora-Hansgrohe signed riders such as Nico Denz or Bob Jungels for the 2023 season. 

Bora-Hansgrohe did not make a lot of signings, only three new riders one of them being Victor Koretzky who is more focused on mountain bike races more than road races. Florian Lipowitz is not considered a signing as he rode for the team as trainee in 2022. The roster is quite valanced, most of the riders are between 27 and 32 years old and except two riders everyone rode more than 40 races and almost no one rode more than 80.


[![Bora ages](/assets/images/BORA_ages.png)](/assets/images/BORA_ages.png)

The second plot of the section breaks down the distribution of race categories each rider has taken part in. Riders that score more points ride world tour races most of their year and the riders that are not part of the best lineups tend to race lower category races. Both riders with less ridden races did not rode any world tour race.

[![Bora categories](/assets/images/BORA_categories.png)](/assets/images/BORA_categories.png)

### Historic performance analysis

Cycling teams tend to change names almost year to year but the structures remain the same despite all the sponsor changes, this allows a multiyear performance analysis. These plots provide information about performance in certain race types since 2010.

The first image is dedicated to show the result crisis Soudal Quick-Step is suffering in cobblestones classics. Historically this structure has been a clear dominator of this type of races by using the strength of the team and the individual talents of generational talents like Tom Boonen, but the last two years the results, as the colours of the plot indicate, are not comparable to the previous years. For the first time since 2013, Soudal Quick-Step has not won any race of these.

[![QS paves races](/assets/images/Paves_QS.png)](/assets/images/Paves_QS.png)

Rabobank was a successful team in the 2000’s but the beginning of the 2010’s was not the best time for the team as performance began to drop reaching the worst moment in 2015, that year they only won 6 times, a really low number compared to the 65 victories of 2023. In the image the improvement can be seen as until 2018 the team did not win a major one week race. Since then, the team has dominated many one week and three week races and in 2023 they managed to win all three grand tours and four out of seven major one week races.

[![Jumbo one week races performance](/assets/images/JUMBO_oneweek.png)](/assets/images/JUMBO_oneweek.png)

Another drastic change in performance has happened in the UAE team, since the change of main sponsor and the correspondent budget increase, the results of the team in grand tours have drastically improved. At the beginning of the decade, the team was an Italian team who cared more about the Giro d’Italia than the other grand tours as the results show, but when Michele Scarponi, who had won the Giro for the team, left the structure the lack of a leader with the ability to win a grand tour was clear. In 2017 the team changed hands and from the next year they started signing grand tour riders and young talents. This policy has been successful as since 2019 the team has won two grand tours and has reached the podium of a grand tour eight times.

[![UAE GT](/assets/images/UAE_GT.png)](/assets/images/UAE_GT.png)

The same way Jumbo-Visma and Team UAE seem to be in the beginning of a winning cycle, Team INEOS seems to be at the end of it. The most successful team of the 2010 decade in terms of grand tours has not won one since the Giro d’Italia 2021, this should not be a problem for any team but for team INEOS which was founded in 2010 being two years without winning a grand tour is a thing that has never happened before. Since 2010 team INEOS has won a grand tour every year except four: 2010 the foundation year, 2014 the year that the reigning champion of the Tour de France Chris Froome could not finish the race due to injuries and the last two years when the team has been close to win the Giro but has not been able to achieve a win. They have a very promising rider in Carlos Rodriguez, but it does not seem that they will be able to win a grand tour the next year.

[![INEOS GT](/assets/images/INEOS_GT.png)](/assets/images/INEOS_GT.png)

The historical performance graphics are also available for nationalities, where the performance of riders born in a country can be analysed. In this case the performance of French riders in grand tours is displayed. Nobody could have predicted in 1995 when Laurent Jalabert won the Vuelta a España that the win would be the last until at least 2024. An historic country like France home to many legends is in a deep crisis of grand tour winners. Many riders have been able to reach the top ten of the grand tours but no one of them has been able to be a true hazard for the winner. This result crisis could end any year as the French cycling academies are an endless source of great talents, so is a matter of time that another big winner appears in French cycling.

[![FRANCE GT](/assets/images/FRANCE_GT.png)](/assets/images/FRANCE_GT.png)