# twitter-data-sentiment-analysis
Analysis of live tweets</br></br>
**Description:**</br>
This Project analysis Sentiments of a twitter user based on the last n (input) tweets .</br>

It Calculates the subjectivity and Polarity of the tweets and based on that assigns a value</br>
1) If the value is bigger than 0 then Positive</br>
2) If the value is smaller than 0 the negative</br>
3) If the value is equal to 0 then neutral 
</br></br>
**Requirements:**</br>
You need elevated access to twitter API which will let you use endpoints and fetch live tweets</br>
All the required keys are imported from a CSV file 
**Text Processing:**</br>
1) Remove all @ mentions</br>
2) Remove Hashtags</br>
3) Remove URLs</br>
4) Remove Emojis
Regex is used to process all the tweets and convert into clean text
</br></br>


**Note:**</br>The Project is done on google colab
[Twitter for Developers](https://developer.twitter.com/en)
## Authors
- [Jayesh Jain](https://github.com/jayesh15)
