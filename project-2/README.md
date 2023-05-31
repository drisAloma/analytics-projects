<h1>Introduction</h1>
<p>The dataset is the tweet archive of Twitter user <a href="https://twitter.com/dog_rates">@dog_rates</a>, also known as <a href="https://en.wikipedia.org/wiki/WeRateDogs">WeRateDogs</a>. WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. The account has over * million followers, this company was started by Matt Nelson. The WeRateDogs asks people to send photos of their dogs, then tweets selected photos rating and a humorous comment. Dos are rated on a scale of one to ten, but are invariably given rating in excess of the maximum such as "13/10". Popular posts are often re-posted on Instagram and Facebook.</p> 
<p align="center"><img src="https://video.udacity-data.com/topher/2017/October/59dd378f_dog-rates-social/dog-rates-social.jpg" width="800"></p>

The final dataset used for this project was a combination of the following datasets:
<p><h3>1. Enhanced Twitter Archive</h3>
The WeRateDogs Twitter archive contains basic tweet data for all 5000+ of their tweets, but not everything. This data was later filtered for tweets with ratings only, resulting in 2356 tweets.</p>
<p><h3>2. Additional Data via the Twitter API</h3>
Retweet count and favorite count are two of the notable column omissions in the twitter archive data. Fortunately, this additional data can be gathered by anyone from Twitter's API. Leveraging on  the access I have to the archive data, specifically the tweet IDs within it, I was able to query the Twitter's API to gather this valuable data.</p>
<h3>3. Image Predictions File</h3>
This dataset contain a table full of image predictions (top three three only by a neutral network) alongside each tweet ID, image URL, and the image number that corresponded to the most confident prediction (numbered 1 to 4 since tweets can have up to four images).

<h1>Insights</h1>
<p>After thorough cleaning of quality and tidiness issues, i was able to draw the following conclusions:</p>

* Most rated dogs breed is **golden_retriever**, probably because they are more in the dataset. 

* 25% of the dogs' ratings is above 1.2 and 75% of the ratings is below 1.2.

* Dog breed with the highest rating is golden_retriever , a dog named Sam.

* Dog breed with the lowest rating is **Maltese_dog** and **Great_Dane**.

* Most common dog names are Charlie and Cooper.

* On average a dog is rated 1.09 (~10/10).

* On average a tweet has ~8003 likes and ~2250 retweets.
