---
layout: single
title: Sprinter Ranking
permalink: /sprinters/
---

Sprinters are the fastest riders on the peloton, they can reach speeds of over 60 kilometres per hour to win a stage. The most common way to rank sprinters is by counting the number of victories they have in the current season. This is not a reliable way of ranking them as not all the races have the same starting lineup, what makes the popular races harder to win. In order to take this factor into consideration, an ELO ranking system has been used to make this ranking system.

Sprinters are a type of rider that is suitable for a ranking like this, because unlike climbers, they always go flat out to win the stage without taking into consideration factors like tactics and the general classification. Fast riders usually dispute flat stages where the peloton arrives full to the finish line and a high top speed is required to win.

Almost half of the races throughout the season end in a bunch sprint, so a lot of races are considered in the elaboration of the ranking. The database where the results are saved also has a binary variable that indicates if the stage finished on a bunch sprint or not. To simplify the calculations, races from 2020 and later are considered for this ranking.

Most of the widely used ELO raking systems, like the one used on chess, are designed to rank by taking into account one versus one matches. The sprints are a free for all fight for the win, so another ELO algorithm needs to be used. [TrueSkill](https://trueskill.org/) algorithm was designed by Microsoft to rank Xbox online players with the goal to make more balanced matches. 

Although flat stages tend to be the easiest stages, crashes, flat tyres or bad placement can make a sprinter miss the fight for the stage and decrease the ELO ranking. As the goal is to determine who is the best sprinter, only the first fifteen riders of each stage have been considered. The ranking also considers the importance of the races as the changes in the ranking are bigger when the race is important.

### Current ranking (End of May 2024)

| Ranking | Rider            | Rating |
|---------|------------------|--------|
| 1       | Jasper Philipsen | 172.4  |
| 2       | Jonathan Milan   | 166.6  |
| 3       | Mads Pedersen    | 164.3  |
| 4       | Wout Van Aert    | 162.4  |
| 5       | Tim Merlier      | 161.9  |
| 6       | Fabio Jakobsen   | 159.2  |
| 7       | Olav Kooij       | 159.1  |
| 8       | Sam Bennett      | 159.1  |
| 9       | Arnaud Demare    | 157.9  |
| 10      | Kaden Groves     | 157.7  |

### Ranking at the end of 2021

| Ranking | Rider            | Rating |
|---------|------------------|--------|
| 1       | Fabio Jakobsen   | 185.7  |
| 2       | Sam Bennett      | 181.3  |
| 3       | Caleb Ewan       | 170.7  |
| 4       | Jasper Philipsen | 170.0  |
| 5       | Mark Cavendish   | 165.9  |
| 6       | Peter Sagan      | 164.9  |
| 7       | Arnaud Demare    | 164.6  |
| 8       | Pascal Ackermann | 160.6  |
| 9       | Nacer Bouhanni   | 160.5  |
| 10      | Wout Van Aert    | 160.4  |

### Ranking at the end of 2022

| Ranking | Rider            | Rating |
|---------|------------------|--------|
| 1       | Fabio Jakobsen   | 173.7  |
| 2       | Sam Bennett      | 171.2  |
| 3       | Wout Van Aert    | 169.1  |
| 4       | Jasper Philipsen | 168.5  |
| 5       | Peter Sagan      | 166.1  |
| 6       | Mads Pedersen    | 165.2  |
| 7       | Arnaud Demare    | 164.8  |
| 8       | Mark Cavendish   | 164.7  |
| 9       | Caleb Ewan       | 162.2  |
| 10      | Nacer Bouhanni   | 159.9  |

### Ranking at the end of 2023

| Ranking | Rider             | Rating |
|---------|-------------------|--------|
| 1       | Jasper Philipsen  | 174.2  |
| 2       | Mark Cavendish    | 166.8  |
| 3       | Mads Pedersen     | 165.4  |
| 4       | Fabio Jakobsen    | 164.4  |
| 5       | Wout Van Aert     | 164.3  |
| 6       | Sam Bennett       | 161.5  |
| 7       | Arnaud Demare     | 160.5  |
| 8       | Caleb Ewan        | 159.2  |
| 9       | Dylan Groenewegen | 158.5  |
| 10      | Phil Bauhaus      | 158.3  |