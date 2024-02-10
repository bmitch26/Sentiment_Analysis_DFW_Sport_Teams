# Sentiment_Analysis_DFW_Sport_Teams

2/8/2024 was a big day for Dallas-Fort Worth sports fans - On this day, the Cowboys hired a new defensive coordinator, the
Rangers resigned one their all-star players, and the Mavericks traded for two key players right before the NBA trade 
deadline. As a result, I was curious to find out fan sentiment for all three teams. As a result, I scraped the most recent
Reddit data from all three teams and compared the results to see which set of fans are the most generally positive and
negative about their team.

I predicted that each team would show a mostly positive sentiment about their team, with the Rangers showing the most. The
Rangers are coming off of their first World Series win and after months of waiting, finally re-signed arguably their best
playoff contributor. As for the Cowboys, I predicted that their fans would show the most negative sentiment towards their team,
as they suffered a huge playoff loss and the new defensive coordinator hire may be a bit controversial.

As for the VADER model, I predicted that it will show a very high level of accuracy in predicting sentiment of the web scraped
Reddit comments due to its high level of previous training data and its well-known regard for sentiment analysis.

My hypothesis for the teams proved true - that is, the Rangers showed the greatest ratio of positive-to-negative comments. On
the other hand, the Cowboys had the worst positive-to-ratio.

As for the VADER model, my hypothesis was moderately accurate. The model inaccurately classified some comments, and it had
trouble classifying any score at all for a number of other comments as well. Therefore, definitive numbers cannot be
conclusively drawn from the model, but general conclusions can be.
