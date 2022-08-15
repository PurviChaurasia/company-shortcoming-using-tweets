# company-shortcoming-using-tweets
This projects make used of NLP based concepts to analyze public tweets regarding a company and determine it's shortcomings. 

With the growing number of companies catering to the needs of the public, it has become the need of the hour to come up with more refined approaches towards customer review analysis. In order for a company to grow, there needs to be a positive and interactive customer-company relationship which can only exist if organizations are responsive to the needs of their customers.

In today’s world, information through mediums like Facebook, Instagram, Twitter and other social media platforms has become the key resource for organizations to analyze customer opinions, reviews and complaints.

We have used roBERTa model for the traditional sentiment analysis if the tweets and then finetuned it using ABSA (Aspect Based Sentiment Analysis)

# Aspect Based Sentiment Analysis

This model is used in referance with "Back to Reality: Leveraging Pattern-driven Modeling to Enable Affordable Sentiment Dependency Learning." Research paper. Aspect Based sentiment analysis does not only determine the nature of the sentence but also the polarity of each word associated with it.
This is used by our project to extract those aspects from the tweet having a negetive sentiemnt towards the company to better understand the company's weak area.

![alt text](https://media.springernature.com/lw685/springer-static/image/art%3A10.1007%2Fs10489-020-02095-3/MediaObjects/10489_2020_2095_Fig1_HTML.png)

As we can see, although the overall sentiment of this sentence is neutral there are certain target words with polarities attatched to them. 

