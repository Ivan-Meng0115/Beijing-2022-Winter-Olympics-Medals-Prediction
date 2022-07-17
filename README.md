# [Winter Olympic Games ---  Exploratory Data Analysis](https://github.com/Ivan-Meng0115/R-for-Data-Visualization/blob/main/Result%20of%20Project.PDF)

#### The Project focuses on data wrangling and visualization. I combine thrre sources of datasets, tidy the resulting datasets, create summary statistics and visualization to find a trend between the number of athletes from different countries and the total medals they acquire during the events and a relationship between the number of coaches and the total number of medals for that specific country.

## Dataset Description
#### This is the Olympic Winter Games dataset that describes medals, results, athletes, coaches, and other records for Beijing 2020. MoreThe data was created from Beijing Olympics.

#### Almost 3000 Athletes, 200 Coaches and Technical Officials (with some personal data: date and place of birth, height, etc.), 600 Medas, 600 Events, 15 Disciplines, and Results (Hockey & Curling) of the XXIV Olympic Winter Games you can find here.

#### Disciplines: Alpine Skiing, Biathlon, Bobsleigh, Cross-Country Skiing, Curling, Figure Skating, Freestyle Skiing, Ice Hockey, Luge, Nordic Combined, Short Track Speed Skating, Skeleton, Ski Jumping, Snowboard, Speed Skating

#### athletes.csv : personal information about all athletes
#### coaches.csv : personal information about all coaches
#### medals.csv: general information on all athletes who won a medal

## Reprocessing Data
* drop duplicated and missing data
* split and create new features dataset
* merge the related datasets
* reformate the dataset

## Exploratory Data Analysis (EDA)

![](https://github.com/Ivan-Meng0115/R-for-Data-Visualization/blob/main/Top%2010%20country%20with%20medals.png)


![](https://github.com/Ivan-Meng0115/R-for-Data-Visualization/blob/main/medals%20for%20each%20country.png)
#### In this graph, we can see that for countries with more athletes, they relatively have more medals earned in the Olympics. Countries with less than 50 athletes usually earned around 10 medals, where countries with more than 200 athletes earned more than 80 medals. Among all the countries, the US, Russia and Canada have the most athletes playing in the Olympic, which corresponded to a relatively high number of medals.



#### To further investigate the exact relationship, we used a point plot to calculate the effects of athletes’ count on medals.
![](https://github.com/Ivan-Meng0115/R-for-Data-Visualization/blob/main/Relationship%20between%20number%20of%20athletics%20and%20number%20of%20medals.png)


![](https://github.com/Ivan-Meng0115/R-for-Data-Visualization/blob/main/linear%20regression%20model%20statistical%20summary.png)

#### The graph shows the correlation between number of athletes and number of medals for countries with medals. When the country has one more athletes participate in the tournament, the number of medal of the country would increase 0.29 unit with standard error by 0.046. The predicted model would be Y = X(0.29) - 1.83.


![](https://github.com/Ivan-Meng0115/R-for-Data-Visualization/blob/main/elationship%20between%20number%20of%20coaches%20and%20number%20of%20medals.png)

![](https://github.com/Ivan-Meng0115/R-for-Data-Visualization/blob/main/linear%20model.png)


#### In this graph, we can see that there is a weak relationship between the number of coaches and the number of total medals earn by a country. It does seems like more coaches would result in more medals for the country that the coaches came from, but there were still many countries who earned a lot of medals with only one coach. The relationship between these two variables are not very obvious.

