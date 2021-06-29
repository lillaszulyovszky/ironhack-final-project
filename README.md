<img src="https://github.com/lillaszulyovszky/ironhack-final-project/blob/main/presentation/slack.png" width="250" height="250">

# DA Bootcamp Slack Insights 
<br/><br/>
## Analyse student engagement/activity/mood with insights from your Slack Team's data.

## Project Intro
Remote environments give very little chance for teachers to gain feedback and optimize their content towards better student performance. So I thought I could run some analysis and provide a tool for teachers to gauge student activity/engagement/mood and even predict what's the best way to get a reply (aka get help in this context) all based on Slack data. I only used data from public channels.

## Notebooks
The notebooks in the code folder could be used to 
- clean & wrangle json data to extract features into a dataframe
- run ML models for predictions
- run NLP preprocessing steps and sentiment analysis
if you have your exported files at in hand.

If you don't know how to export, read up here> https://slack.com/intl/en-hu/help/articles/201658943-Export-your-workspace-data

The notebooks are fully annotated and include all the modules which needs to be imported to make the code work.

## Future scope
Enhanced scope for this will include 
- dynamically pulling data from Slack API (so insights can be drawn anytime/anywhere)
- loading publicly shared files into a google sheet for the whole cohort
- working as a Slack App, providing insights for teachers on the Slack space they are in.

## Couple of insights to share
- **distribution of messages between participants (students and teachers) in the top 5 most used channels**

![Slack logo](https://github.com/lillaszulyovszky/ironhack-final-project/blob/main/presentation/participant_activity.png)

- **distribution of messages during the day in the homework(lab) help channel**

![Slack logo](https://github.com/lillaszulyovszky/ironhack-final-project/blob/main/presentation/labhelp_activity.png?raw=true)

- **identifying influencers by messages sent**

![Slack logo](https://github.com/lillaszulyovszky/ironhack-final-project/blob/main/presentation/student_activity.png?raw=true)

- **mood changes during the bootcamp in April on the homework(lab)help channel**

![Slack logo](https://github.com/lillaszulyovszky/ironhack-final-project/blob/main/presentation/labhelp_positivity.png)

- **top perfoming emojis**

![Slack logo](https://github.com/lillaszulyovszky/ironhack-final-project/blob/main/presentation/reactions.png?raw=true)

- **top 15 important features to look out for when you're looking for a reply**

![Slack logo](https://github.com/lillaszulyovszky/ironhack-final-project/blob/main/presentation/top15_features.png?raw=true)

- **most used words in the bootcamp**

![Slack logo](https://github.com/lillaszulyovszky/ironhack-final-project/blob/main/presentation/wordcloud.png?raw=true)


## Methods used

- **Loading JSON files:** creating a function to load each file into a dataframe<br/>
- **Data cleaning & wrangling in Python:** transforming data set to help visualise insights, feature engineering<br/>
- **Prepocessing:** 2 methods (Normalizer, Dummies) for Predictions and several NLP preprocessing steps like removing punctuations, emojis, links, stemming<br/>
- **Machine Learning Models**<br/>
linear regression, logistics regression, random forest, random forest classification
- **Natural Language Processing**<br/>
wordcloud, VADER analyis, Sentiment analyis <br/>

**Thank you for reading!** <br/>
Any questions, hit me up at
lilla.szulyovszky@gmail.com<br/><br/>
