                                             Build A Twitter Trend Analyzer With AI - Analyse  Bollywood Trends					
                                                  

Abstract:
Everyday a twitter user faces different kinds of data based on many fields. It is almost like a dream to analyze that huge amount of data and find the latest trend going on. Every tweet has certain purpose and talks about a problem or discussion. By the analysis of twitter data most of the companies can crack the code to success in today’s world, they can easily obtain information about, what is going on today. So this way, we can understand the importance of twitter trend analysis.

Problem Statement:
To build a twitter trend analyzer which will analyze a set of tweets using NLP and text-processing techniques. The trend analyzer will work on a given set of tweets, seeded on Bollywood to generate:
1. A tag cloud depicting what topics or celebrities were being talked about on Twitter
2. A chart showing which hashtag related to Bollywood trended (Hashtags are words or phrases beginning with # eg. #ShahrukhKhan
3. A share of voice chart to show which celebrities dominated conversation on Twitter.

Programming Language:
Python 3.7

Python Libraries Used:

1.Numpy [array manipulation]
2.Pandas [making dataframes for visualization]
3.Re [for extracting url dataset]
4.Matplotlib [for Data visualization in graphs and charts]
5.Warnings [Ignore Unwanted Warnings]
6.Wordcloud [For drawing a word chart of most frequently used Words]





Methdology:

1.Getting the twitter dataset for analysis: https://spotleai.sgp1.digitaloceanspaces.com/course/data/tweets_bollywood.txt  
This URL provides us a dataset for analysing tweets from twitter users.

2.Data preprocessing and displaying Wordcloud:
Data preprocessing involves removing unwanted string literals or characters and stopwords used frequently from all the tweets. Using Matplotlib’and Wordcloud’ Libraries we generate the word cloud.This can be modified according to different background styles, number of words, figure size etc.
Below You can see a wordcloud:



![wordcloud](https://user-images.githubusercontent.com/54790163/180709570-597d11f4-bb16-4916-ae83-0e68569187af.png)




Observations:
In the above wordcloud we See that “Salman” word was most frequently used in the user tweets followed by “SRK”.Rest of the actors such as Katrina, Alia, and Amir were mentioned almost equally by twitter users

3.Determining top trending Hashtags from Dataset and Visualizing a Bar Graph:
As we Know hashtags start with ‘#’ so using regex library for pattern matching we determine all the hashtags and find the top Hashtags being used and determining their popularity. This is visualized using a bar graph by comparing the number of tweets posted for every top hashtag

![bar graph](https://user-images.githubusercontent.com/54790163/180709372-e6024c49-e599-4bbb-a210-54c7219776c5.png)




Observations:

From the above Fig we can see that #BB13 Trended the most on twitter.
Also if we analyze these hashtags most of them are related to Salman Khan or his on screen projects such as Big Boss, Dabangg.

4.Determining which Actor had the maximum share of voice in the analyzed tweets.

Actors Analyzed for this project:
[Alia Bhatt, Shah Rukh Khan, Salman Khan, Aamir Khan, Anushka Sharma, Ranbir Kapoor, Hrithik, Deepika Padukone]

For comparing above list of actors with each other Pie charts are best to use. They do not show changes over time.They not only visualize but also determine the % share of its labels(actors tweets) in its visualization .This helps in drawing Comparitive Statistics.




![Pie Chart](https://user-images.githubusercontent.com/54790163/180709780-636522e8-ecc3-412b-beaf-956877c524d2.png)



Observations:

Salman Khan shared the maximum voice dominating all other indian celebrities. He had a 57% voice share, Deepika Padukone while had minimum twitter user talking about her with just 1.1% which is quite shocking considering she is one of the top actresses of the country and has great number of twitter followers.

