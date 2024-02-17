---
name: Twitter data collection and analysis [Data Engineering Project]
tools:
  [
    R,
    R Markdown,
    RStudio,
    Microsoft Teams,
    Twitter API,
    Data Engineering,
    Data Collection,
    Data Pre-processing,
    Data Analysis,
    Data Visualisation,
    Teamwork,
    Uni Project,
  ]
image: /assets/images/dataEngineering/dataEngineering_wordcloud.png
description: Use the power of Twitter API to collect, analyse and visualise one week of data related to Elon Musk to gain insights into the social media behavior of Twitter users.
external_url:
---

# Data Engineering Project

---

{% capture list_items %}
Screenshots
Overview
Technical details
Key findings
My contribution
Source code
{% endcapture %}
{% include elements/list.html title="Table of Contents" type="toc" %}

# Screenshots

{% capture carousel_images %}
/assets/images/dataEngineering/dataEngineering_1.png
/assets/images/dataEngineering/dataEngineering_2.png
/assets/images/dataEngineering/dataEngineering_3.png
/assets/images/dataEngineering/dataEngineering_4.png
/assets/images/dataEngineering/dataEngineering_5.png
/assets/images/dataEngineering/dataEngineering_6.png
/assets/images/dataEngineering/dataEngineering_7.png
/assets/images/dataEngineering/dataEngineering_8.png
/assets/images/dataEngineering/dataEngineering_9.png
/assets/images/dataEngineering/dataEngineering_10.png
/assets/images/dataEngineering/dataEngineering_11.png
{% endcapture %}
{% include elements/carousel.html %}

# Overview

The purpose of this group project (3 people) was to use the `Twitter API` to **collect** and **analyse** **data** related to a recent global event involving Elon Musk, with the goal of exploring the impact of powerful influencers on Twitter and investigating what people were saying about the event. The project involved conducting **exploratory data analysis**, **natural language processing**, and **network analysis** using `R`, and the results were presented in an interactive `.html` report using `R Markdown`. The project aimed to provide insights into the social media behavior of Twitter users and to apply **data engineering skills** to a real-world problem.

# Technical details

## Technologies and Tools used

| **Tech/Tool**   | **Usage**                       |
| --------------- | ------------------------------- |
| R               | Programming language            |
| R Markdown      | Markup language                 |
| R Studio        | IDE                             |
| Twitter API     | Data collection                 |
| Microsoft Teams | Communication and collaboration |

## Data Collection, Storage, Analysis and Visualisation techniques used

- Data collection: Use `rtweet` and `Twitter API`
- Data storage: save data collected in `csv` and `json` files
- Exploratory Data Analysis:
  - Twitter data over time
  - The most retweeted and most liked tweets
  - Ratio of Replies/Retweets/original Tweets
  - Sources of the tweets
  - Tweets location
  - Top 10 most mentioned accounts
  - Top Hashtags according to unique tweets
  - Topic clusters
- Natural Language Processing:
  - Unique tweets versus all data
  - Analysis of tweets’ topics
  - Sentiment analysis of unique tweet content
- Network Analysis:
  - Find Elon Musk’s tweets
  - Identify influential users

# Key findings

Our analysis revealed that the majority of verified Twitter users shared original tweets related to Elon Musk's acquisition of Twitter from the USA. Among all the tweets, Elon Musk's tweet received the highest number of retweets. Additionally, the sentiment of the majority of the tweets was positive. Please refer to the table below for a summary of our findings.

| **Factor**                         | **Finding**                                                                               |
| ---------------------------------- | ----------------------------------------------------------------------------------------- |
| Range time                         | May 6 to May 14 2022                                                                      |
| Number of tweets                   | 17204                                                                                     |
| Original Tweets                    | 10079 \~ 58.59 %                                                                          |
| Replies                            | 919 \~ 5.34 %                                                                             |
| Retweets                           | 6206 \~ 36.07 %                                                                           |
| Top sources of the tweets          | Twitter for iPhone, Twitter Web App                                                       |
| Location of the majority of tweets | USA                                                                                       |
| Most mentioned accounts            | elonmusk, twitter                                                                         |
| Most popular hashtags              | elonmusk, twitter, donaltrump                                                             |
| Ratio of unique tweets             | 69%                                                                                       |
| Top 4 popular words                | twitter, musk, elon, trump                                                                |
| Topic clusters                     | #twitter #musk, \$44 billion, ceo tesla, free speech, temporarily hold deal, social media |
| Dominant sentiments                | Positive \> Trust \> Negative                                                             |
| Influential users                  | elonmusk, business                                                                        |

# My contribution

- Contributed significantly to the successful outcome of the project, demonstrating technical proficiency and teamwork skills to achieve a perfect score of 100/100
- Proposed ideas and outlined the solution to the problem
- Planned and managed project progress, including allocating tasks to team members based on their different skill levels
- Used `RStudio` and `R Markdown` to conduct **exploratory data analysis**, **natural language processing**, and **network analysis**
- Created an interactive `HTML` report to effectively communicate complex information.

# Source code

Unfortunately, this is a uni project so the source code and the whole report **cannot be shared** due to academic integrity and intellectual property concerns.
