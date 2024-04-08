# BERT and VADER for Sentiment Analysis of Dallas-Fort Worth Sports Teams

On the day of 2/8/24, the Rangers re-signed one of their star players in Adolis
Garcia, the Cowboys hired a new defensive coordinator, and the Mavericks traded for two new players at the trade deadline.
As a result, I was curious to see recent fan sentiment given the big day of moves. To bring this to the test, I gathered the
newest comments for each subreddit, I hypothesized that the fans of each team would show positivity for the new moves that 
each team had made.

The VADER model was modertately effective in accurately sorting comments when analyzing various comment samples of each
category. It generally sorted positive vs. negative comments accurately, but it did not show effectiveness in determining 
sentiment of a large number of comments for comments scraped from all 3 subreddits. Therefore, definitive conclusions cannot
be drawn. It generally characterized all 3 teams as mostly showing a positive sentiment.

The BERT model, although not perfect, and trading off for a much greater training time, proved far more reliable in sorting
comments when analyzing various comment samples. While the VADER model characterized all three subreddits as generally 
positive, the BERT model characterized all three as showing a majority amount of comments as neutral, with the Rangers then
showing more positive comments than negative, and the Cowboys and Mavericks being mostly negative. Although this disproves
my hypothesis, the sentiments make sense when realizing that the Rangers had just won their first World Series, the 
Mavericks had been struggling lately, and the Cowboys had just been eliminated early in the playoffs when they had been 
expected to contend for a championship.

In all, although more computationally expensive, I believe the BERT model showed greater results, and for this set of data
was the best choice.
