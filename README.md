# FIFA23WomensWorldCup
Predicting the winner of FIFA Women's World Cup 2023

## Context
The perfect opportunity to combine two of my great loves- football and data science! The tournament is held once every four years, so you can imagine the anticipation! I enjoyed every bit of the process, even the frustrating parts when the function never seemed to output quite what I wanted it to!

Now, about the project. I chose it mainly to highlight (and develop) my web scraping skills as well as statistical modelling. After web scraping several Wikipedia pages and collecting the data, I cleaned it and organized it into appropriate groups. I also tried my hand at building a predictive model based on Poisson Distribution to try and predict the winner of the tournament based on historical match data.

## Skills
Skills shown:

 *   Web scraping
 *   Data cleaning
 *   Statistical modelling (Poisson Distribution)

New Skills Learnt:

 *   Web scraping over multiple webpages
 *   A deeper understanding of statistical models
 *   The fact that complicated machine learning models aren't always necessary to make predictions, in some cases a simple yet effective statistical model can do the job just fine

## Process

*    I first used the Beautiful Soup library to parse content from Wikipedia pages related to past matches of FIFA Women's World Cup. Then I scraped data about this year's fixtures and group divisions.
*    Next I started to clean the data. It involved renaming columns, changing the score format and splitting it into two different columns, among other things. As the world cup had already started while I was working on this project, the Wikipedia page was being updated rapidly, so I resetted the values to make sure my project works whenever I run the notebook.
*    The Poisson distribution is a discrete probability distribution that expresses the probability of a given number of events occurring in a fixed interval of time or space. Here, a goal is an event that might happen in the 90 minutes of a football match, and we could calculate the probability of the number of goals that could be scored in a match between two given teams.
*    A major roadblock that I faced, apart from the updating webpages, was my predictive model. I struggled a lot with different machine learning models, but then found that a simple statistical model is all I needed (shoutout to <a href='https://thepycoach.com/'>PyCoach's article on Towards Data Science</a>!).
*    Another problem was effectively scraping similar data from multiple webpages (one for each world cup year). I knew a little web scraping such as how to do web scraping for one page but not for multiple pages, especially when they are not simply one large table that's been paginated, but different webpages altogether. I was doing a lot of repetitive work before realising that I could just use a function and a formatted string to replace the world cup year.

## Sources
* https://en.wikipedia.org/wiki/2023_FIFA_Women's_World_Cup
* https://en.wikipedia.org/wiki/1991_FIFA_Women%27s_World_Cup
* https://en.wikipedia.org/wiki/1995_FIFA_Women%27s_World_Cup
* https://en.wikipedia.org/wiki/1999_FIFA_Women%27s_World_Cup
* https://en.wikipedia.org/wiki/2003_FIFA_Women%27s_World_Cup
* https://en.wikipedia.org/wiki/2007_FIFA_Women%27s_World_Cup
* https://en.wikipedia.org/wiki/2011_FIFA_Women%27s_World_Cup
* https://en.wikipedia.org/wiki/2015_FIFA_Women%27s_World_Cup
* https://en.wikipedia.org/wiki/2019_FIFA_Women%27s_World_Cup

Check out my notebook for the final result!
