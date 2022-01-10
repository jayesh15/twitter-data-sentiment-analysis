# twitter-data-sentiment-analysis
Analysis of live tweets</br></br>

**Description:**</br>
This Project analysis Sentiments of a twitter user based on the last n (input) tweets .Use the twitter API to create endpoints and fetch real time tweets of any user. Tweepy python library was used to authentication and extraction. The tweets are then cleaned using regular expressions ( removing hashtags, @mentions , RTs, emojis and URLs). Used pandas to converts the raw data into data frame and used NLP and sklearn libraries to generate the subjectivity and polarity from the data strings. Made a scoring system to generate a new column ( sentiment ) which holds positive , negative and neutral and values based on the polarity score , generated graphs and word cloud for better data visualization .</br>

**Sentiment Analysis:**</br>
It Calculates the subjectivity and Polarity of the tweets and based on that assigns a value</br>
1) If the value is bigger than 0 then Positive</br>
2) If the value is smaller than 0 the negative</br>
3) If the value is equal to 0 then neutral 
</br></br>

**Requirements:**</br>
1) You need elevated access to twitter API which will let you use endpoints and fetch live tweets</br>
2) All the required keys are imported from a CSV file </br></br>
3) Tweepy python library is used to communicate between python and twitter

**Text Processing:**</br>
1) Remove all @ mentions</br>
2) Remove Hashtags</br>
3) Remove URLs</br>
4) Remove Emojis
Regex is used to process all the tweets and convert into clean text
</br></br>


**Note:** The Project is done on google colab</br>

[Twitter for Developers](https://developer.twitter.com/en)
## Authors
- [Jayesh Jain](https://github.com/jayesh15)


