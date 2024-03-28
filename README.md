 <font size="+2">**New Movie Studio Decision Analysis:** </font>

by  Karina Baculima, Monica Pecha, and Rick Lataille for Flatiron School

![Title](https://github.com/rjlatail/Phase_2_Repo/blob/main/Images/title.png)

<font size="+1">**Repository Contents**</font>  
Within our repository, you will find our final Jupyter Notebook titled "New_Studio_Analysis.ipynb". You will also find a pdf version of our Powerpoint presentation labeled "Studio_Recommendations.pdf". At the bottom of this README you will find a link to the interactive Tableau dashboard of our analysis.


<font size="+1">**Business Understanding**</font>  
Calculated Craft Studios is a new start-up movie studio looking to make films in order to generate healthy and reliable returns.  They have asked for three recommendations as to how to enter this market

<font size="+1">**Source of Data**</font>  
Our initial data came from IMDB, The Numbers, and Box Office Mojo.

<font size="+1">**Important Features and Limitations of the Data**</font>

- We encountered significant flaws in the data which limited our ability to perfectly match records across data sources.
- The dataset includes films completed and released to the market, and some films which are scheduled to be released, but does not include films which were never released, or their budgets. 
- Some spot checks of the data suggest that worldwide gross in particular is not reliable across all films.
- Financial reporting across studios can differ, in particular due to the manner in which compensation is paid, which could alter any profitability analysis.
- There are many below-the-line costs, such as press & advertising and cinema revenue-sharing, that differs from film to film and could have an effect on this analysis.


<font size="+1">**Analysis**</font>  
We used the ratio of domestic box office sales to production budget as our proxy for how profitable each film was.  Since production budget represents Calculated Craft's investment dollars, it is important to scale gross revenues by investment dollars to determine how successful each investment dollar is.

Our analysis showed:
- Smaller budgets lead to more profitable films over time
- Certain genres typically have much higher profitability metrics, such as horror, romance, mystery and thriller
- Producers who are more prolific have higher profitability on average


<font size="+1">**Smaller Budgets Lead to Higher Profitability**</font>
![Smaller_Budgets](https://github.com/rjlatail/Phase_2_Repo/blob/main/Images/smaller_budgets.png)

As film budgets decrease in size, profitability increases significantly, doubling over the overall profitability.  This is because, if a film does not perform well, the loss is limited to the whole investment, but a wildly successful film can sell just as many tickets as a blockbuster.  On average, there is much more upside potential for smaller investments.


<font size="+1">**Some Genres Are More Profitable Than Others**</font>
![Genre](https://github.com/rjlatail/Phase_2_Repo/blob/main/Images/genre.png)

We examined particular genres to determine whether any of them showed higher profitability patterns.  Several do.  Horror, romance, mystery and thriller all outperform the overall mean, and significantly outperform genres that typically have much higher budgets, such as sci-fi, fantasy, animation and adventure.  The data does not suggest why this is the case, but from our domain research we believe it is due to the story-centric nature of the more profitable genres.  In other words, the expense base of sci-fi, fantasy and adventure is not just the cost of the story or the talent, but also the special effects, travel and location costs, and other expenses tied to larger tentpole films.


<font size="+1">**Prolific Producers Are More Profitable**</font>
![Producers](https://github.com/rjlatail/Phase_2_Repo/blob/main/Images/producers.png)

Finally, we investigated whether producers who make movies frequently are typically more profitable than those who make fewer movies over time.  We found that they are.  Again, the data do not suggest why this is the case, but from our domain research we discovered that the most prolific filmmakers (Tyler Perry, Blumhouse, Working Title, Hallmark) ascribe their success to identifying successful story patterns and formats and using them repeatedly and maintaining cost discipline.  This addresses a specific market demand component and allows them to improve through iteration.


<font size="+1">**Conclusion**</font>  
Our data analysis shows that:
- Keeping budgets small leads to higher profitability over time
- Horror, myster, thriller and romance movies are more reliably profitable
- Making more movies leads to more profitability


<font size="+1">**Interactive Dashboard:**</font>  

https://public.tableau.com/views/Movie_Statistics/Budgets-Scaled?:language=en-US&publish=yes&:sid=&:display_count=n&:origin=viz_share_link