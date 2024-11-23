# A Sentiment Analysis of Dallas-Fort Worth Sports Teams using Transformers

On the day of 2/8/24, the Rangers re-signed one of their star players in Adolis
Garcia, the Cowboys hired a new defensive coordinator, and the Mavericks traded for two new players at the trade deadline.
As a result, I was curious to see recent fan sentiment given the big day of moves. To bring this to the test, I gathered the
newest comments for each subreddit (r/Cowboys, r/Mavericks, r/TexasRangers), and I hypothesized that the fans of each team 
would show positivity for the new moves that each team had made.

To test fan sentiment, I used two different methodologies - VADER and BERT. The VADER model was ineffective in accurately 
sorting comments when analyzing various comment samples of each category, and definitive conclusions regarding fan sentiment
could not accuractly be drawn.

The BERT model, although not perfect (and requiring a much greater training time), proved far more reliable in sorting
comments when analyzing various comment samples. While the VADER model characterized all three subreddits as generally 
positive, the BERT model characterized all three as showing a majority amount of comments as neutral, with the Rangers then
showing more positive comments than negative, and the Cowboys and Mavericks being mostly negative. Although this disproves
my hypothesis, the sentiment scores make sense when realizing that the Rangers had just won their first World Series, the 
Mavericks had been struggling lately, and the Cowboys had just been eliminated early in the playoffs when they had been 
expected to contend for a championship.

In all, although more computationally expensive, the BERT model showed highly effective in determining fan sentiment and
is highly recommended for analyzing sentiment due to its contextual awareness.

BERT Results:
![sentimentanalysisvisualization](https://github.com/user-attachments/assets/a9295804-8b78-439c-a61c-4c5def6edd31)
