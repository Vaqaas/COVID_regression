## Predicting Gold Differences in G2 Esports League of Legends Games.

# Description

A new source of entertainment has been drawing the attention of a large portion of the professional sports audience.
Esports has become an industry that generates multi millions of dollars in revenue, drawing attention from Advertisers and
sponsors, and professional gamers are now boasting contracts worth millions in US Dollars. I believe an interesting and
valuable problem to address is which distribution of stats result in wins. But since win/loss is a categorical value.
We decided to study Gold Difference Value. This value correlates highly with wins.

# Features and Target

We utilized dozens of features and studied their importance in the model and their pairwise correlation. However,
Gold Difference is the main topic of interest. Gold is a currency used within matches so players can become stronger.
Stronger players are highly likely to win the game over weaker players. This is not only anecdotally accurate, but can
also be demonstrated statistically.

# Data

Our primary data set contained about 1120 observations, and also we scaped another 500+ points of data to determine
the relationship between gold difference and wins. Data was obtained from:

<ul>
<li>Games of Legends Esports</li>
<li>Riot Games Developer API</li>
</ul>

# Algorithms

<ul>
<li>Basic Regression</li>
<li>Polynomial Regression</li>
<li>Ridge Regression</li>
<li>LASSO</li>
</ul>

# Tools used

<ul>
<li>Scikit-learn</li>
<li>Numpy</li>
<li>Pandas</li>
<li>Selenium/Chromewebdriver</li>
<li>BeautifulSoup</li>
<li>Matplot</li>
<li>Seaborn</li>

# Conclusions and Further studies

Further results look very promising as there are few data outlets for Esport League of Legends data. Furthermore,
the data collected only concerns the G2 Esports League of Legends team. Following the study on this team, the same
methods can be used for other Esports teams. The game of League of Legends is incredibly nuanced, and we only studied
numerical data, while champion picks, player substitutions, champion bans, neutral objectives, and map data can be
looked into as well. In conclusion, research into this field is very promising.





