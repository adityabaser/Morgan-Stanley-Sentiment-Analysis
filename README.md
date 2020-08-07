# Theme and Sentiment Prediction - Morgan Stanley Competition

## Goal of the Project 

To provide business insights to Morgan Stanley about the themes people are talking about and their sentiment towards wealth management and financial service. To take a cross-sectional view on how these insights differ between different companies. 

## What was Acheived

1) Implemented Topic Modeling using LDA to determine the themes related to wealth management that people are talking about. 

2) Conducted sentiment analysis on 1.6 million twitter tweets to flag the emotions as positive, negative, or neutral. 

3) Used TensorFlow and Deep Learning concepts to predict themes and sentiments for real time twitter data with 70 % accuracy and build a website to make it interactive and user-friendly for the end user. 

   **Link to the website** - http://twitter-prediction.herokuapp.com/


4) Provided business insights on the topics people are talking about & their sentiments towards wealth management by creating a Tableau dashboard and presenting it to Morgan Stanley. 

   **Link to the Live Tableau DashBoard** - https://cutt.ly/udAokvl

## Objective and Methodology of the Project

The below picture represents the general storyline and thinking behind the project. 

![picture](https://github.com/adityabaser/Morgan-Stanley-Sentiment-Analysis/blob/master/screenshots/Objective.PNG)

The below flowchart represents the steps in which the project was executed. 

![picture](https://github.com/adityabaser/Morgan-Stanley-Sentiment-Analysis/blob/master/screenshots/Methodology-Project.PNG)

We performed Topic Modeling using LDA to identify 7 topics from the twitter data that people were talking about. Above, represents the wordcloud visualization of it. 

![picture](https://github.com/adityabaser/Morgan-Stanley-Sentiment-Analysis/blob/master/screenshots/Identified%20Themes.PNG)

Using the Tableau Dashboard we identified insights on these 7 themes and why people were interested in them.

### Topic 1 - Stocks & Trading

1) Markets have gotten more volatile now and it fluctuates based on various factors and external events like COVID heighten the risk and threaten the long term returns, proper consultation with financial advisors avoids short-term thinking and rather focus on the long-term proposition.

2) There has been a trend towards negative sentiment in June and July 2020 towards stocks and trading starting from April 2020 throughout all the service models

### Topic 2 - Investment

1) General positive sentiment even during COVID months for robo-advisors, whereas bank brokerage has seen a negative trend throughout 2019 and 2020.

### Topic 3 - Cryptocurrency

1) Consumer demand for platforms like crypto that help them easily purchase and manage their digital assets in a safe, legal, and compliant manner.

2) Cryptocurrency generally has a neutral sentiment towards all service models, but it has a continuous trend of negative sentiment in full brokerage service sector from September 2019 to July 2020, with positive sentiment only in April and July.

3) Robo-advisors has always seen a positive sentiment, but there was a sudden negative sentiment in the month of November.

### Topic 4 - Digital Channels & Fintech

1) Surfing the digital wave is important to stay significant in the WM sector. 66% of HNWI’s would consider switching financial firms due to their digital shortcomings. 
Digital and fintech had highest positive sentiment as compared to all the other topics, with most positive sentiment for robo-advisors in the month of October , November and December.

2) In general there has not been a drop in sentiment for this theme across all the sectors even during COVID months.

3) A similar trend like insurance is observed in digital and fintech, though the trend is not as negative as insurance.

### Topic 5 - Advisors & Client Experience 

1) HNWI’s trust experts to secure better returns and to save time. The percentage of advisors who are allocating to crypto for their clients will hit 13% in 2020, up from 6% in 2019. On the other hand, the transfer of wealth from boomers to their children might result into dislocation of advisor-client relationship. 

2) Advisors have a general neutral to positive trend over the year but there has been a sudden drop in sentiment polarity from 0.285 to 0.0345 from March to April in bank brokerage.There has been a similar trend in full brokerage as well, but full brokerage has seen a drop in sentiment from January and it has been fluctuating between neutral and negative since then. 

### Topic 6 - Retirement Planning

1) Many HNWI’s simply want assurance that they can generate enough income in retirement to  continue their current standard of living. Engaging with clients earlier might help in retirement planning prospects. 

2) This theme had the highest variations between positive, neutral and negative sentiments as compared to all the other themes.

3) Bank brokerage always has a very negative sentiment in this topic, followed by full brokerage.

4) But there was sudden increase in the sentiment during December 2019 for financial and retirement planning throughout all the sectors. 

### Topic 7 - Insurance 

1) Compared to highly positive sentiment towards investment across all fronts in September 2019 to December 2019, there has been a drop and trend of negative sentiment from May 2020 especially for bank brokerage and discount brokerage service models.

2) Insurance has very positive sentiment in discount brokerage service model with highest in the months of September, November and December, but it has seen a drop in sentiment starting from January 2020 to June 2020.

3) Bank brokerage always has a negative sentiment for this topic.

## Comparing Different Service Models on Tableau and Developing Insights

The Tableau Dashboard link is https://cutt.ly/udAokvl


![picture](https://github.com/adityabaser/Morgan-Stanley-Sentiment-Analysis/blob/master/screenshots/Methodology-Analyzing%20verticals.PNG)


## Website 

We developed a web application to gain real time understanding of the topics of discussion within the twitter community regarding wealth management:

The link to the website is - https://twitter-prediction.herokuapp.com/

### Website Backend Flowchart 

![picture](https://github.com/adityabaser/Morgan-Stanley-Sentiment-Analysis/blob/master/screenshots/Website%20Backend.PNG) 

## Recommendations

1) Bank Brokerages have a negative sentiment towards retirement planning and insurance throughout the entire period of 1 and half year. It’s more negative as compared to other service models where the sentiment is positive. Hence, they should look at the retirement planning, financial planning and insurance services. 

2) Full Brokerage has a general negative sentiment towards cryptocurrency as compared to other service models which have a neutral sentiment. Robo Advisors have the most positive sentiment related to cryptocurrency. Hence, Full Brokerage can focus on AI tools for cryptocurrency to provide a better service. 

3) Robo advisors as compared to other service models are performing extremely well in the digital and fintech channels and hence, other service models could research on their technology.

