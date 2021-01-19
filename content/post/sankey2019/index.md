---
# Documentation: https://wowchemy.com/docs/managing-content/

title: "Data Science: Python or R?"
subtitle: ""
summary: "According to Kaggle users: What is the dominating programming language in data science - when it comes to frequency of use and recommended go-to language?"
authors: []
tags: ["data science"]
categories: []
date: 2019-09-26T13:44:25+01:00
lastmod: 2020-11-26T13:44:25+01:00
featured: false
draft: false

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
# Focal points: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight.
image:
  caption: ""
  focal_point: ""
  preview_only: false

# Projects (optional).
#   Associate this post with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["internal-project"]` references `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects: []
---
**What is the dominating programming language in data science - when it comes to frequency of use and recommended go-to language?**

In 2018, the [Kaggle](kaggle.com) community was asked to answer a set of questions on preferred data science tools and methods, as well as professional experience. 
An overwhelming number of 23860 users from around the world submitted their answers. The following insights are based on the [publicly available dataset](https://www.kaggle.com/kaggle/kaggle-survey-2018).

Python, or R? This question has the potential to kick off lively, controverse debates, as can be seen on [medium](https://medium.com/@data_driven/python-vs-r-for-data-science-and-the-winner-is-3ebb1a968197) or [quora](https://www.quora.com/Which-is-the-right-place-to-start-for-AI-ML-Data-science-career-Python-or-R-or-something-else).
Or can another language jump in? Kagglers, at least, can give quite a clear answer...

### Python is used most often

When asked for the one specific, most often used programming language, the majority of the 15222 respondents name Python, namely 53.7%.

*Of the 23860 participants, 8637 didn't answer this question.*

{{< render-plotly kaggle_2018_primary_language >}}

### Python recommended even by users of other languages

Even of those participants that do not use Python most frequently, a high number would recommend it to data science aspirants as first language to learn.

{{< render-plotly kaggle_2018_suggested_language >}}

*If one of the two questions was not answered by a respondent, it was counted as "None".
Participants who didn't answer both questions where excluded (n=5052). Thus, a total of 18807 responses were analyzed.*

### Majority recommends Python as first language to learn

Python is recommended by 75.48% of the 18788 respondents as first language to learn when practicing data science.

*5071 participants didn't answer.*

{{< render-plotly kaggle_2018_sankey >}}

### Python increasingly popular

Python's popularity has increased, as becomes obvious when looking at how experienced the respondents are in doing data science.
While "only" 39.18% of respondents with a data science experience of 30-40 years claim to most often use Python, this value increases up to 59.89% for respondents with 1-2 years of experience. 
For newcomers (< 1 year or never written code to analyze data), having coding experience from different fields, we can observe a slightly more diverse range of programming languages that are currently used most often - but still with a dominance of Python.

*5326 participants didn't answer. 41 participants who* ``have never written code and do not want to learn`` *were also excluded.*

{{< render-plotly kaggle_2018_language_experience >}}