**Question 1**

    Does seasonality impact what genre of music people listen to throughout the year?


**Caveats**

    Spotify is a popular streaming company that currently holds 433 million active monthly users in 2022. Spotify owns 36% of the worldwide music streaming market, so it is the number one music streaming platform. North America comes in at the number 2 spot holding 22% of the share. Naturally as humans we like to play music in all type of settings. We love to curate playlist geared towards our moods and specific occasions. So we decided to dive into whether specific genres grow popularity in different seasons of the year. To keep the data cohesive with our Grammy statistics,  we decided to dive into Spotify's 2019 Top Weekly Songs in the US that were eligible for the 62nd Grammy Awards (2020). 


**Definitions**

    To create a sample size we choose the first week of top songs of a chosen month to represent a specific season.

    - January 2019 represents our Winter season
    - April 201 9represents our Spring season
    - July 2019 represents our Summer season
    -October 2018 represents our  Autumn season 

    Each Top Weekly Chart holds 200 songs, which brings our sample size to 800 songs and a grand total of 2,350,492,289 streams. 

**Methodology**

    1. We combined the seasonal dataset and were able to calculate the total numbers of streams using the "Streams" column for each genre. We turned this into a bar chart to show what genre's are the most popular across the data. 
 
    2. After looking at the data we decided to focus on the Top 5 genre's out of the grand total and break those "Streams" down to each season. 

    3. Lastly, we created a bar chart to how listening preferences are effected by seasonality. 



**Statisical Analysis**

    When we created the "Top 5 Genre's Per Season in 2019" chart, we automatically saw a drastic chnage with the "Pop" category. In Autumn the "Pop" category started at 7.68%,  reached its peak in the Summer with a 11.8% increase then made a total decline of 7% by Winter. 

    Across all seasons the" Rap/HipHop" genre reigns over the other genres but makes a huge decline from autumn to spring by 25%. 


**Conclusion**

    So coming back to our original question...Does seasonality impact what genre of music people listen to throughout the year? 

    Absolutely. 


**Question 2**

    Is there a link between artist streams and award show recognition?


**Caveat**

    Members of the Recording Academy: The Recording Academy represents the voices of performers, songwriters, producers, engineers, and all music professionals. Dedicated to ensuring the recording arts remain a thriving part of our shared cultural heritage, the Academy honors music’s history while investing in its future through the GRAMMY Museum, advocates on behalf of music creators, supports music people in times of need through MusiCares, and celebrates artistic excellence through the GRAMMY Awards - music’s only peer-recognized accolade and highest achievement. As the world’s leading society of music professionals, we work year-round to foster a more inspiring world for creators.


    Voting: Members of the Grammy Awards, an elite group of music industry members, vote to choose the greatest in music and to reward work that they believe will stand the test of time. But, do Spotify users agree? 

    As a result, we decided to analyze whether there is a relationship between an artist spotify streams and award show recognition. 

    We pulled the US Top Weekly Songs between October 1, 2018 - September 30,2019 from Spotify. The data was limited to the Top 200 songs per week and the numerical data was constantly changing from week to week, but we found that we were able to group by Artist Name & Song Title based on the number of Spotify Streams. Therefore our analysis is solely based on Spotify because it was difficult to find openly available data from Spotify's biggest competitor, Apple Music over the same time period 

    Additionally, we pulled Spotify data from October 1, 2018 - September 30,2019 because this is the same period for song / album eligibility for the 62nd Grammy Awards (2020)

    For Spotify data, We are taking out analysis from the top 10 artist based on spotify streams & we are highlighting the top 10 songs/track names based on spotify streams 

    For Grammy data, we focusing on the following categores: Best New Artist, Record of the Year, Song of the Year, Best Rap Song, Best R&B Song, Best Rock Song, and Best Country Song.


**Definition**

    To construct the top 10 artist Spotify dataset, we selected the artist from the 52 week period to examine the total number of streams accumulated 

    To construct the top 10 Spotify songs/track names dataset, we selected the top songs from the 52 week period to further examine the total number of streams accumulated 

    We examined the Spotify streams for the top 10 artists and compared them to the candidates and winners of six Grammy categories.


    Each Top Weekly Chart features 200 songs, bringing the total number of songs in our sample to 10401, with a total of 30,503,387,078 streams.


**Method**

    1. We combined the top weekly songs dataset with the Grammy 62nd dataset to compute the total amount of streams for each artist using the "Streams" column. 

    We utilized two charts (a bar chart and a pie chart) to indicate if the top 10 artists in terms of streaming were nominated in the big five Grammy categories.

    2. We constructed bar charts to see if any of the top songs with the most streaming were nominated in any of the major five Grammy categories.

    3. Finally, we examined each category separately to see if the winner in each category produced streams.


**Findings**

    The Grammy Awards are decided by members' votes in the music industry. Even if a song is deemed "popular," in spotify it may not receive a nomination or win an award.

    From the a sample of six Grammy categories we analyzed the biggest disparity is in the Big three categories: Best Country song, Best Rock Song, Best R&B song.

    The winners of the three categories (Best Country song, Best Rock Song, Best R&B song) generated 0 streams in all 54 weeks combine.

    The Best Rap Song category recognizes artists with large Spotify streams as nominees but not as winners

    Winners and Nominees for Record and Song of the Years are closely related to Spotify streams. 


**Conclusion**

    Based on the findings above, we agree there is no relationship between artists streams and award show recognition.




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
 
