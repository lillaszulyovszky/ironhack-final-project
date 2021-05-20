# Ironhack Project - Data Analytics Bootcamp Slack Insights 
<br/><br/>
## Analysing Interaction on Slack

![Slack](https://github.com/lillaszulyovszky/ironhack-final-project/blob/main/presentation/slack.png)

## Table of content

- [Project Intro](https://github.com/lillaszulyovszky/ironhack-case-study-classification/blob/main/README.md#project-intro)
- [Data](https://github.com/lillaszulyovszky/ironhack-case-study-classification/blob/main/README.md#data)
- [Process](https://github.com/lillaszulyovszky/ironhack-case-study-classification#process--tools)
- [Key Take Aways](https://github.com/lillaszulyovszky/ironhack-case-study-classification#key-take-aways)

## Project Intro
Remote environments give very little chance for teachers to gain feedback and optimize their content towards better student performance. So I thought I could run some analysis and provide a tool for teachers to gauge student activity/engagement/mood based on Slack data.

**Challenge:**
- time limit
- wrangling json data
- digging into natural language processing steps which is new to me and is outside of the scope of this bootcamp

**Predictive Question:**
Can we predict what do we need to do to get a reply to our message?

## Data

Using the downloaded [json files](https://github.com/lillaszulyovszky/ironhack-final-project/tree/main/data) arranged in folders, I used Python to clean and wrangle the data, used ![Machine Learning Models](https://github.com/lillaszulyovszky/ironhack-final-project/blob/main/code/ironhack_DA_slack_ML.ipynb) to do predictions and ![Natural Language Processing](https://github.com/lillaszulyovszky/ironhack-final-project/blob/main/code/ironhack_DA_slack_NLP.ipynb) and finally Tableau as a tool to visualise insights and explore the relationships between features. <br/> <br/>
To find out more about the distribution of the important features I highlighted, you can have a look on my Tableau project below:<br/>
![Tableau](https://public.tableau.com/profile/szulyovszky.lilla#!/vizhome/Slack_Data_Insights/moodofmessagesvspartsofthedaychannel)

<br/>
<br/>For further details on all features, please refer to the [wrangling notebook](https://github.com/lillaszulyovszky/ironhack-final-project/blob/main/code/ironhack_DA_slack_wrangling.ipynb).


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

For further visualisations check out our Tableau workbook or the presentation we've done below.

[Tableau](https://public.tableau.com/profile/szulyovszky.lilla#!/vizhome/Slack_Data_Insights/moodofmessagesvspartsofthedaychannel) <br/>
[Presentation](https://docs.google.com/presentation/d/1qMoWoY_3LL31Y4WvFe2di2z1FIUNOo3gU2yuRwjrI6o/edit?usp=sharing)

## Key Take Aways

### 1. My model can predict what features to use to get a reply with an accuracy of 86%
  - length of message (lengthier the better)
  - tone of the message
  - how many reactions the message got
  - was it sent early in the morning

**Thank you for reading!** <br/>
If you have any questions, please reach out to me.<br/><br/>
