# World-Happiness-Score
World Happiness Score Visualizations

## Motivation 
### r/dataisbeautiful - Battle 2019-06  
   [battle](https://www.reddit.com/r/dataisbeautiful/comments/bwocis/battle_dataviz_battle_for_the_month_of_june_2019/)  
   [post](https://www.reddit.com/r/dataisbeautiful/comments/bxm50z/oc_economy_health_freedom_and_happiness_by_country/)  
  
  *I found some mismatched countries after my submission, so this code acctually display a better visualization than the submited.
  
### World Happines Report  
   [data](https://www.kaggle.com/henosergoyan/happiness/data)  
   [dataset info](https://www.kaggle.com/unsdsn/world-happiness)  

Original field names from Kaggle dataset were changed in excel as bellow:  

        Happiness.Rank - Happiness Rank
        Happiness.Score - Happiness Score
        Whisker.low - Whisker low
        Whisker.high - Whisker high
        Economy..GDP.per.Capita. - Economy (GDP per Capita)
        Health..Life.Expectancy. - Health (Life Expectancy)
        Trust..Government.Corruption - Trust - Government Corruption
        Dystopia.Residual - Dystopia Residual

### Python Imports

    geopandas
    pandas
    numpy
    seaborn
    matplotlib
    
### Other Tools Used

    Photoshop
    Excel
    
## Project
  
Variables score compared to happiness score:  
![Imgur](https://i.imgur.com/JJf2re7.png)  
Histograms of the distribution for some variables:  
![Imgur](https://i.imgur.com/4rreXGl.png)  

Variables correlation with the overall happiness score:  
![Imgur](https://i.imgur.com/6SvsQJk.png)  
Variables correlation with themselfs:  
![Imgur](https://i.imgur.com/uR1RUuz.png)  

### Analysis overview
##### Correlation
Economy and Health were the most related to the overall score, followed by Family and Freedom, while Trust and Generosity were the least related.
I decided to keep Economy and Health for the visualization and remove Trust and Generosity.

##### Family and Freedom
Family had a strong relation with happiness score and also with Economy and Health, its distribution is left-skewed and most of its values were around 1\~1.5 while Freedom was around 0.3\~0.5. This stronger correlation can be partly explained by the way the Happiness score is calculate which is a sum of all the variables, so as Family scores are generally higher than Freedom they will have a higher impact on the overall score.  
Freedom didn't had such a high relation with Economy and Health so it can help explaining what wasn't accounted by those, also as much as it wasn't strong, Freedom had a better relation with the excluded variables (generosity and trust) than any other.

##### Selected Variables
    Economy | Health | Freedom
    
### Maps
Economy:  
![Imgur](https://i.imgur.com/kBQh7Wo.png)  
Health:
![Imgur](https://i.imgur.com/PDA6zZF.png)  
Family:  
![Imgur](https://i.imgur.com/MLhLNth.png)  
Fredoom:  
![Imgur](https://i.imgur.com/V9WQ88S.png)  
Trust:  
![Imgur](https://i.imgur.com/KbEVFdk.png)  
Generosity:
![Imgur](https://i.imgur.com/e3pbUB9.png)  
Happiness Score:
![Imgur](https://i.imgur.com/dmqLaMj.png)  

### Ranking
Made with Excel  
![Imgur](https://i.imgur.com/fYj0xcX.png)  

### Submission
Made with Photoshop  
![Imgur](https://i.imgur.com/DmrnXxN.png)


