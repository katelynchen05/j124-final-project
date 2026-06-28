# Diving deeper into the party life of New York in 2016 through noise complaints.

In the year of 2026, it's the year of nostalgia for the aesthetic of the 2016 era-- from fashion to music to nightlife. Known for its wild night life, New York bars and restaurants often held late-night parties. Though the party scene of New York created some defining moments of pop culture, behind it are also the voices of nearby residents in annoyance. 

[Dataset](https://www.kaggle.com/datasets/somesnm/partynyc) 

## Source and Potential Challenges
Today, we look at this dataset from Kaggle. The dataset here gives us a look at how late into the night parties were called for noise complaints and which areas of New York were most frequently called on. 

While Kaggle is the hosting platform, the data originally comes from the NYC Open Data portal, which publishes records collected by NYC's 311 hotline. The data from there is collected by an independent government agency, which can generally be considered trustworthy. However, a journalist might want to verify that the Kaggle set matches with the official NYC Open dataset. Another thing to note is that the title is misleading. While it is titled "2016 Parties in New York", there are only parties that received noise complaints filtered out. This is an undercount of all the parties in NYC since some may not have been reported. 

## Analysis
Looking at the table, I created two pivot tables. One gathered the number of calls per zip code and the other gathered the complaints per borough. In order to visualize the data better, I made two bar charts. 
[Google Sheets Pivot Tables](https://docs.google.com/spreadsheets/d/1cfzXrNzI_6SlZYy_uSdleGT2Yw8QC1hdAapSgwwKPrE/edit?usp=sharing)
![Borough Complaints](borough-complaint) ![Top 10 Zips](top-10-zip)

In the first chart (complaints filed in each borough), data shows that Manhattan has by far the highest number of complaints at approximately 39000. That's around 40% more than Brooklyn and over ten times Staten. This data might suggest that nightlife activity and the resulting noise complaints were much more concentrated in Manhattan in New York.

The second chart (describing the top 10 ZIPs that received calls) shows that there is far from an even distribution. After the top few ZIPs, the complaint totals decline noticeably. This might suggest that there are really a few neighborhoods that have a disproportionate large share of complaints. Looking at the ZIP codes 10009, 10002, 10034, 10014, 11103, and 10003, many belong to Manhattan which aligns with what the borough chart shows. 

## Summary/Ethical Concerns

The data suggests that noise complaints were highly concentrated in certain areas. Rather than being spread evenly throughout NYC, they typicaly clustered in Manhattan. One likely reason for this pattern might be that Manhattan has the highest density of restaurants, bars, clubs, etc, increasing the likelihood of nearby residents filing noise complaints. Based on the data, it seems to indicate that in 2016, night-life related noise was more of a neighborhood-level issue instead of a widespread city issue. 

However, to tell a full story ethically, a journalist might want to do additional reporting. For instance, the data only shows noise complaints with the location type being "Club/Bar/Restaurant". Thus, we don't know the actual proportion of complaints about club/bar locations to the entire area's calls. This may portray certain neighborhoods or cities as more noisy when in reality a smaller neighborhood might have the same proportion of calls. Providing more context would help avoid misleading conclusions and stigmatization of certain communities. 
