# cohens-kappa
 COMP8240 Applications of Data Science: Cohen's Kappa Calculation in Python and Excel

## Overall Goal
Tweets are annotated for sentiments from two annotators using a survey, and calculated the level of agreement in the annotations.

## Data
50 random tweets are gathered from two users (in this example, tweets from US politician Alexandria Ocasio-Cortez ([@AOC](https://twitter.com/AOC)) and celebrity Kim Kardashian ([@KimKardashian](https://twitter.com/KimKardashian)) were collected).  The tweets were a mix of of positive, negative and neutral.

## Packages Used

## Method
1.	Two people were asked to independently annotate all of the 50 tweets; each tweet were annotated with one of positive / negative / neutral sentiment. A Qualtrics survey link were provided to the annotators. A screenshot is attached below:

<p align="center">
  <img src="https://github.com/jarvipuz/cohens-kappa/blob/main/qualtrics_survey.png" />
</p>

2.	A comma-separated value file was created with the text of one tweet per row, and with 3 columns per row: the first column contains annotator 1's label for that row's tweet, the second column annotator 2's label, and the third column the text of the tweet.
3.	An Excel file was created containing an annotation agreement matrix of the sort. This file also includes the values of Observed Agreement and Expected Agreement for the data, and the value of Cohen's Kappa.
4. A Python notebook was created to calculate Cohen's Kappa too.
