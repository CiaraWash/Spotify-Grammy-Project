




*Question 1** 
Does seasonality impact what genre of music people listen to throughout the year?


*Caveats* 
Spotify is a popular streaming company that currently holds 433 million active monthly users in 2022 . 
Spotify owns 36% of the worldwide music streaming market, so it is the number one music streaming platform. North America comes in at the number 2 spot holding 22% of the share. Naturally as humans we like to play music in all type of settings. We love to curate playlist geared towards our moods and specific occasions. So we decided to dive into whether specific genres grow popularity in different seasons of the year. To keep the data cohesive with our Grammy statistics,  we decided to dive into Spotify's 2019 Top Weekly Songs in the US that were eligible for the 62nd Grammy Awards (2020). 


*Definitions* 
To create a sample size we choose the first week of top songs of a chosen month to represent a specific season.

- January 2019 represents our Winter season
- April 201 9represents our Spring season
- July 2019 represents our Summer season
-October 2018 represents our  Autumn season 

Each Top Weekly Chart holds 200 songs, which brings our sample size to 800 songs and a grand total of 2,350,492,289 streams. 

*Methodology* 

1. We combined the seasonal dataset and were able to calculate the total numbers of streams using the "Streams" column for each genre. We turned this into a bar chart to show what genre's are the most popular across the data. 
 
2. After looking at the data we decided to focus on the Top 5 genre's out of the grand total and break those "Streams" down to each season. 

3. Lastly, we created a bar chart to how listening preferences are effected by seasonality. 



*Statisical Analysis* 

When we created the "Top 5 Genre's Per Season in 2019" chart, we automatically saw a drastic chnage with the "Pop" category. In Autumn the "Pop" category started at 7.68%,  reached its peak in the Summer with a 11.8% increase then made a total decline of 7% by Winter. 

Across all seasons the" Rap/HipHop" genre reigns over the other genres but makes a huge decline from autumn to spring by 25%. 


*Conclusion* 

So coming back to our original question...Does seasonality impact what genre of music people listen to throughout the year ? 

Absolutely. 





**Question 2 ** 



























**Question 3**

**Are the most monetized artists on Spotify the ones with the most weeks on the charts?**

A statistical analysis of this question in two periods: before and after the 62nd Grammy Awards show.

**Caveats**

    1. For purposes of this question, the Grammys serve as a point in time from where to divide our data and 
        findings into pre and post-Grammy periods as detailed below. 

**Definitions** 

    1. Grammy effect: For our purposes this term is defined as the discernible impact that the airing of 
        the Grammys has on an artist's Spotify monetization.
    2. Eligibility period: Evaluation timeframe used by the Grammy awards committee for the 62nd Grammy awards 
        (1 October 2018 (Autumn 2018) to 31 August 2019 (Summer 2019). We've also included the period following 
        the airing of the Grammys in January 2020. This period is captured in the Winter 2020 data. 
        
**Methodology** The most salient points of this process. 

    1. We identified columns containing continuous data which could be used to help us answer our 
        aforementioned question. Namely, the "streams" and "weeks on charts" columns. Streams were converted 
        into monetization data using the industry standard rate of .004 cents per stream. 
        
    2. With this in mind, we created a dataframe which depicts the top-10 monetized artists during the 
        pre-Grammy period. This dataframe is found below as the "pre_gram_mon_total" dataframe. 
        
    3. We then created a dataframe which depicts the top-10 streamed artists during the 
        post-Grammy period, wherein we added the period following the airing of the Grammys to the above dataframe.  
        This dataframe is found below as the "post_gram_mon_total" dataframe.  
            
**Statistical analysis**

    1. From the "pre_gram_mon_total" and "post_gram_mon_total" dataframes mentioned above we created scatter plots 
        designed to depict a pre-Grammy and post-Grammy period. 

    2. The pre-Grammy scatter plot was designed to establish a baseline of the monetizataion vs weeks on charts 
        behavior.   
        
    3. The post-Grammy scatter plot was designed to detect changes to the aforementioned baseline scatter plot (monetization vs weeks on charts) following the airing of the Grammys. 
    
**Findings**

    1. While we can clearly observe the positive relationship between "weeks on chart" and "monetization," with 
        a correlation of .957 for our baseline period (preceding the Grammys), and a correlation of .964 in the 
        period following the Grammys, the broader point as it pertains to our original question regarding a
        discernible impact that the airing of the Grammys has on an artist's Spotify monetization, we can observe 
        a small increase in the positive correlation between our variables following the Grammys.  
 
