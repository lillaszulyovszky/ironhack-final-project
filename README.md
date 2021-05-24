# DA Bootcamp Slack Insights 
<br/><br/>
## An education tool to analyse student engagement/activity/mood with insights from your Slack Team's data.

## Project Intro
Remote environments give very little chance for teachers to gain feedback and optimize their content towards better student performance. So I thought I could run some analysis and provide a tool for teachers to gauge student activity/engagement/mood and even predict what's the best way to get a reply (aka get help in this context) all based on Slack data.

**Challenge:**
- very few features coming with the json≠ files from the API, so there was a lot of feature engineering to be done 
- natural language processing steps
- create a product which dynamicly pulls data from the Slack API and working as a Slack App

**Couple of insights to share**
- distribution of messages between participants (students and teachers) in the top 5 most used channels
- distribution of messages during the day in the homework(lab) help channel
- identifying influencers by messages sent
- mood changes during the bootcamp in April on the homework(lab)help channel
- top perfoming emojis
- top 15 important features to look out for when you're looking for a reply
- most used words in the bootcamp


## Process
Ways of working included an iterative/agile approach circling through the following steps:

- **Loading JSON files:** creating a function to load each file into a dataframe<br/>
- **Data cleaning & wrangling in Python:** transforming data set to help visualise insights, feature engineering<br/>
- **Prepocessing:** 2 methods (Normalizer, Dummies) for Predictions and several NLP preprocessing steps like removing punctuations, emojis, links, stemming<br/>
- **Machine Learning Models** using scikit learn<br/>
**- linear regression:** <br/>
**- logistics regression:** <br/>
**- random forest:** <br/>
**- random forest classification:** <br/>
- **Natural Language Processing** using nltk<br/>
**- wordcloud:** <br/>
**- VADER analyis:** <br/>
**- Sentiment analyis:** <br/>

## Visualizations

For further visualisations check out my Tableau dashboard or the presentation we've done below.

Tableau coming soon <br/>
[Presentation](https://docs.google.com/presentation/d/1qMoWoY_3LL31Y4WvFe2di2z1FIUNOo3gU2yuRwjrI6o/edit?usp=sharing)


**Thank you for reading!** <br/>
If you have any questions, please reach out to me.<br/><br/>
