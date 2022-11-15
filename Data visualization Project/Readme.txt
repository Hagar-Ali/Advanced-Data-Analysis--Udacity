-Movies Dataset consist of 24 columns and 45466 rows but I worked with 17 column only and I end up working with 31K rows, then I worked with more than 20K rows with genres (Drama, Action, Comedy, Horror), At the end I worked with Arabic movies only for my interest, it was a pretty small subset but it was so exciting to me.

Findings Summary:

Correlation between Features.
budget and revenue =0.76
budget and vote_count 0.67
popularity and revenue = 0.5
popularity and vote_count = 0.55
revenue and vote_count =0.8

-Movies most frequent status is Released more than 30k released movies in the dataset.

-Movies most frequent Languages are  (English, French, Japaness, Italian, deutch, Spanish,...), but the most frequent language is English with more than 20k occurances.

-Vote_average is normally distributed but there's approximately 1000 vote_average ==0, It might be sth wrong in the data, or missing values in the original data that replaced with 0

-popularity needed transformation, after transformation it became skewed to the left.

What is the top 10 countries with the highest count of production companies?
 United states of America has the highest number of production companies with more than 1600 companies, United Kingdom came in the second place with more than 250 companies

What is the most productive country of movies? 
The highest production country is United states of America with less than 6000, then United kingdom with more than 2000. Japan is the sixth productive country to movies in this dataset but it's in the seventh place in the number of production companies, while Spain is the tenth productive country to movies in this dataset but it's the eighth place in the number production companies. seems like number of production companies in each country is not a big indicator of the country movies production in some cases.

What is the vote average among years (1950-2018)? 
the highest vote average was around 1960 and the lowest was before 1970

What are Budget and Revenue distributions? 
Both budget and revenue are skewed to the right, Most movies budget and revenue are higher than million dollar

What is the correlation and between Budget and Revenue? 
There's high and strong correlation between budget and revenue

What is Budget, Revenue and Profit Trend among years(1950-2018)? 
revenue and profit are approximately identical in many years, but before 1980 profit started to be a lot less than revenue and that became obvious and increased among years.

Drama, Comedy, Action, Horror Movies Dataframe
Here we subset our dataframe to work with the most common movies genres, We got 21405 rows in this new dataframe

Multivariate Visualizations with Drama, Comedy, Action, Horror Movies Dataframe
What is the highest Vote Average and in which status and in which movie genre?
- Lowest vote count is in Rumored status except Comdey movies, Comedy Movies vote count is lower in post production status.
- The highest movies with vote_count are Action Movies in Planned status.
- Planned status don't have Horror Movies!
- Action Movies have the highest vote count in Planned and In-Production and Released status among other movies genres.

What is the highest Vote Average and in which status and in which movie genre?
-Highest vote average are Comedy Movies in Planned status. (make sense to me)
-No Action Movies in In-production and Post Production statues.
-No Horror Movies in Planned status.
-The highest vote average in Released status are Drama Movies, then Comedy, Action and Horror Movies comes at the end of the list.

-Drama, Comedy and Action are the most movies with vote_average and most if not all movies are for all Released and tiny percentage are Rumored or in Post Production phase or in production or planned


Arabic Movies
As an Arabic, Egyptian citizen I'm interested in arabic movies, so I filtered the dataset based on original language (ar), I know most of the Egyptian movies and these are some master pieces in the film making production history in Egypt**
- I got only 26 Arabic movies in the dataset, But I worked with it anyway.

Egypt ( My country YAY ) is the most productive country in this subset 
Egypt and Lebanon are the most two productive countries which their movies original language is Arabic
- Wow! There were some British production companies produced Arabic Movies
- the highest vote average among Arabic movies goes to a Lebanon movie (Comedy Movie)
- the highest vote count among Arabic movies goes to Saudi Arabian movie (Drama)
>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>>
Key insights:
..............
-Most of Movies in the Dataset are Released, We have so much less info about other movies in other phases of production.
-Most common movies genres are Drama, Comedy, Action and Horror, it was surprising to me that Animation movies isn't that popular !
-Comedy movies are highly voted, but in Released phase Drama movies are get the highest vote average.
-US has the biggest numbers of production companies and number of movies producted.
-Having a lot of production companies in one country doesn't mean it has a lot of movies beind produced, as we saw with Japan and Spain.
-There is a high correlation in Budget, Revenue, and profit. "if u spend a lot u will gain a lot"
- Budget and Revenue and Profit all have an upward trend among years, seems like production companies put a lot of money in Movies industry and it is getting bigger through years


Arabic Movies insights:
>>>>>>>>>>>>>>>>>>>>>>>>>>
- Surprisingly! some Arabic Movies are produced by British companies.
- Egypt is the most producing Arabic country for movies in this Dataset. 
