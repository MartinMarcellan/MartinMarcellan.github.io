---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---

Data science is nowadays almost everywhere, even in sports data science is used to enhance players performance, measure their impact in the game by creating different metrics or to predict the outcome of difficult decisions like deciding which player is more suitable for the club. Despite the global trend, data science in cycling seems to be growing slower than in other team sports, this can be due to the lack of public data and to the number of external factors that can influence the performance of one rider even in the time trials which I believe are the “easiest” stages to predict. 

The aim of this website is to apply some of the techniques of data science to public data and see how accurate the predictions can be. As it can be seen in the bar above, the page is divided into four different parts:
- [Breakaway predictions](/breakaway/): In this section I try to predict the suitability of each stage for a breakaway to be successful. Learn more about the model in the dedicated page and look for the predictions in the posts section below.
- [Time trial predictions](/itt/): Knowing that getting the exact predictions every time is impossible, I try to predict the time each rider is going to spend in each time trial.
- [Sprinter ranking](/sprinters/): A ranking of sprinter type riders based on an ELO system. The idea is to be able to determine who is the best sprinter of the moment based on who beats and in which race does it.
- [Data visualization](/visualization/): This section is dedicated to the graphics that will allow to summarize relevant information.

All these applications would not be possible without a database, in this case I am using a database I made myself by using web scraping techniques. The database contains data of around 250 different races and all its editions since 2010, data from earlier years can be easily found but is usually incomplete and some races are missing, so I decided to take 2010 as the first year for my database.
