'![Alt Text](/images/Reddit.png)' # Project 3: Predicting Subreddit Classification using NLP


### Problem Statement

Our consumer research firm is collaborating with a client to gain insights into the distinct behavior and preferences of customers who have children and those who do not. We will be analyzing the text content of posts from two subreddits, r/childfree and r/parenting, using natural language processing techniques to predict which subreddit the text belongs to. By accurately predicting the subreddit a particular text belongs to, we can help our client gain a better understanding of the language and tone preferred by each subreddit's users. This will enable our client to tailor their products and services to the specific needs and preferences of each group, and create targeted advertising that resonates with their intended audience. 

Our analysis will create a model that can take in text data from our client and predict the most suitable language for advertisement in either community. This will help our client gain a deeper understanding of the needs and preferences of these two groups, and inform their marketing and product development strategies.

--- 

### Subreddit Selection and Descriptions

The two subreddits that we will be analyzing with our Natural Language Processing (NLP) Model are r/Parenting and r/Childfree. Below are the descriptions of both subreddits.

From r/Parenting: (https://www.reddit.com/r/Parenting/)

"/r/Parenting is the place to discuss the ins and out as well as ups and downs of child-rearing. From the early stages of pregnancy to when your teenagers are finally ready to leave the nest (even if they don't want to) we're here to help you through this crazy thing called parenting. You can get advice on potty training, talk about breastfeeding, discuss how to get your baby to sleep or ask if that one weird thing your kid does is normal."

From r/childfree: (https://www.reddit.com/r/childfree/)

"r/childfree is a subreddit for people who have chosen to live a child-free lifestyle. Members of the community typically do not have or do not want children, and use the subreddit to share experiences, offer support, and discuss topics related to their decision not to have children.

The subreddit is a space for people to discuss the challenges and benefits of living a child-free life, as well as to share stories of dealing with social pressures and expectations surrounding parenthood. Discussions on the subreddit can cover a wide range of topics, including relationships, career goals, travel, hobbies, and personal growth."


Both subreddits will serve our client well and help them further their mission in correctly reaching prospective customers.

--- 

### Subreddit Statistics

Before we proceed with the analysis of our subreddits, it's beneficial to evaluate their relative differences in terms of popularity on Reddit.

Both r/Parenting and r/Childfree are popular subreddits that have both experienced significant growth over the past 6 years. The growth for each subreddit is shown below:

| Year | r/childfree subscribers | &nbsp; | Year | r/parenting subscribers |
|------|------------------------|--------|------|------------------------|
| 2018 | 180,000                | &nbsp; | 2018 | 345,000                |
| 2019 | 480,000                | &nbsp; | 2019 | 660,000                |
| 2020 | 790,000                | &nbsp; | 2020 | 1 million              |
| 2021 | 1.1 million            | &nbsp; | 2021 | 1.4 million            |
| 2022 | 1.3 million            | &nbsp; | 2022 | 1.6 million            |
| 2023 | 1.4 million            | &nbsp; | 2023 | 1.7 million            |


In 2023, r/childfree has ~1.5 million pageviews and 158,000 unique visitors per day, while r/parenting has an estimated 2.2 million pageviews and 258,000 unique visitors per day.

---

### Conclusion

Our NLP analysis on the two subreddits, r/childfree and r/parenting, has resulted in the development of a highly accurate and effective model using the Random Forrest algorithm. The model was specifically designed to predict the subreddit to which a particular text belongs to, and it was developed with a priority on accuracy and F1 score.

For our client, who is building an ad campaign targeting specific clients, our model selection was crucial in ensuring that their advertising strategy is tailored to the specific needs and preferences of each group. By targeting the right audience with the right advertising, our client can expect a positive response to their advertisement for clients that are targeted by the correct ad.

Our analysis also revealed that the sentiment in the childfree subreddit was generally more positive and less negative when compared to the parenting subreddit. This information can be incredibly useful for our client in tailoring their products and services to the specific needs and preferences of each group, and creating targeted advertising campaigns that resonate with their intended audience.

Overall, our model can help our client gain deeper insights into the language and tone preferred by each subreddit's users, which will be instrumental in developing effective marketing and product development strategies. By leveraging the power of natural language processing and machine learning, our client can stay ahead of the curve in understanding and catering to the distinct behaviors and preferences of customers who have children and those who do not.

---

### Recommendations

1. Use the insights gained from the sentiment analysis to tailor products and services for each subreddit's users. This can help improve customer satisfaction and loyalty.

2. Continue to use the Random Forest algorithm in future analyses as it proved highly effective in predicting the subreddit to which a particular text belongs to.

3. Collect and analyze more data from subreddits or other online communities to gain a deeper understanding of the language and tone preferred by different groups of customers.

4. Develop targeted advertising campaigns that resonate with the intended audience, based on the insights gained from the analysis. This can help improve the effectiveness of advertising campaigns and lead to increased sales and revenue.

--- 

### Data Dictionary

| Column Name | Description | Data Type |
|-------------|-------------|-----------|
| id          | Unique identifier of the post | string |
| author      | Username of the author of the post | string |
| title       | Title of the post | string |
| body        | Body text of the post | string |
| subreddit   | Name of the subreddit where the post was made | string |
| created_utc | Unix timestamp of when the post was created (UTC) | integer |
| score       | Net score of the post (upvotes - downvotes) | integer |
| num_comments| Number of comments on the post | integer |
| permalink   | Permanent URL of the post | string |
| url         | URL of the post content | string |
| is_self     | Boolean indicating if the post is a self-post or not | boolean |

--- 

### References

1. SlidesGo (Presentation Template)
2. Reddit (https://www.reddit.com/)
3. Medium- Sentiment Analysis (https://medium.com/@kiddojazz/reddit-sentiment-analysis-f8a1a790124a)
4. Learn Data Sci (https://www.learndatasci.com/tutorials/sentiment-analysis-reddit-headlines-pythons-nltk/)
5. Modelling & NLP (https://dailynlp.com/nlp-modeling/)
6. PushShift API
