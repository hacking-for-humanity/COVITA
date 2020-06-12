# COVITA
Covid19 Text Analyzer

Report: https://docs.google.com/document/d/1sIdA-4sH0JO_LTlDMBZzsz34aHPQxm3D79LRMskjEp0/


## Inspiration
Build a comprehensive Text Analysis App and Dashboard to help gain real-time insights from Covid-19 documents and social messages. There is an enormous opportunity to help people suffering from mental anxiety through positive messages and share relevant insights with corresponding agencies

## What it does
The goal for project COVITA (Covid19 Text Analyzer) is to analyze the Covid19 texts like
medical research documents and tweets in order to find the relevant topics, understand user
intents, find geospatial outbreaks, identify and heal mental anxieties , find availability of medical
kits. Once we showcase the capability of our text analysis, we would like to extend it further to
perform medical document recommendation, identify sensitive information, spread positive
uplifting messages , predict outbreaks and create a marketplace for medical kit providers.

## How I built it
Development Environments:  Databricks, Google Colab, Azure, Google Notebook Instance 
Technologies: Spark( Spark-SQL,  Spark-NLP)  Python (Core libraries, Spacy, Pandas, Helium, Numpy) 

## Challenges I ran into

We faced challenges in terms of storing large data, processing massive volume of tweets. But we relentlessly fixed issues and leveraged multiple cloud platforms like Azure and Google and used multiple development environments like Colab Notebook , Databricks , Dataproc and Google VMs in order to store data and utilize the free compute power as much as possible.
We also also faced issues running Spark-NLP licensed version inside Databricks instance. 

## Accomplishments that I'm proud of

I am able to explore many different areas and gain insights as explained in this document https://github.com/hacking-for-humanity/COVITA/blob/master/Project%20COVITA%201.0.pdf
- Analyze the Hash-tags, User-mentions, Follower and Favourite count data
- Extract & Analyze the Entities like (Persons, Organizations, Events, National Groups,
Locations) from Tweets
- Analyze the Biological Named Entities in Tweet and Research Literature
- Create the Topic clusters over a period of time
- Analyze the sentiments associated with the Topics
- Analyze the Mental Anxiety Pattern
- GeoSpatial Analysis of Outbreaks
- Build and augment prediction model for outbreak
I have found a lots of new problems to solve while working on this hackathon and I am very much excited about it.


## What I learned

Spark-NLP , Biological NER , GeoSpatial Visualization

## What's next for COVITA
We would like to extend our work further to perform medical document recommendation, identify sensitive information, spread positive uplifting messages , predict outbreaks and create a marketplace for medical kit providers.
We shall build a recommendation model based on the creating clusters of topics for recommending hashtags.
We also want to use different types of models like en_core_web_lg and en_core_web_md
Next we want to cluster the different entities based on different metrics like sentiment, followers, frequency with different statistical variations (rate_of_change , moving average, std dev etc.)
We shall create a time-series data of the above statistical variations to detect anomaly and patterns.
We need to create more sophisticated geospatial maps by correlating infection rate with outbreak locations 
