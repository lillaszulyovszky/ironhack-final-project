# Ironhack Project - Data Analytics Bootcamp Slack Insights 
<br/><br/>
## Analysing Interaction on Slack

![Slack](https://github.com/lillaszulyovszky/ironhack-final-project/blob/main/presentation/slack.png =250x250)

## Table of content

- [Project Intro](https://github.com/lillaszulyovszky/ironhack-case-study-classification/blob/main/README.md#project-intro)
- [Process](https://github.com/lillaszulyovszky/ironhack-case-study-classification#process--tools)

## Project Intro
Remote environments give very little chance for teachers to gain feedback and optimize their content towards better student performance. So I thought I could run some analysis and provide a tool for teachers to gauge student activity/engagement/mood based on Slack data.

**Challenge:**
- low amount of features coming with the data, so there was a lot of feature engineering to be done
- digging into natural language processing steps which is new to me and is outside of the scope of this bootcamp
- create a product which dynamicly pulls data from the Slack API and working as a Slack App

**Predictive Question:**
Can we predict what do we need to do to get a reply to our message?

**Insight which I looked into**
- distribution of messages between participants (students and teachers) in the top 5 most used channels
- distribution of messages during the day
- identifying influencers by activity
- mood changes during the bootcamp in the top 5 most used channels
- top perfoming emojis
- top 15 important features to look out for when you're looking for a reply
- most used words in the bootcamp


## Process

Ways of working included an iterative/agile approach circling through the following steps:

- **Loading JSON files:** creating a function to load each file into a dataframe<br/>
- **Data cleaning & wrangling in Python:** transoforming data set to help visualise insights, feature engineering<br/>
- **Prepocessing:** 2 methods (Normalizer, Dummies) for Predictions and several NLP preprocessing steps like removing emojis, links, stemming<br/>
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
