# PoliticsinTurkey

This is my final project for my STAT 4380: Data Science class at Villanova University, and the aim here is to explore political ideologies and opinions supported in Turkey, and analyze the relation of politics to everyday life. After giving some background information on Turkey, Turkey's political chronology and most recent general election results are presented. Then, the influence of politics on opinions regarding controversial topics (like education reform, economical situation, abortion bans, alcohol bans, state of emergency) is explored, and by comparing Turkey to its neighbors and Europe overall, the political position of Turkey is determined.

The project is implemented in R using 5+ datasets. The packages that I used in this project are tidyverse, lubridate, ggmap, ggrepel, ggcorrplot, ggstance, wordcloud, tidytext, slam, tm, janitor, rvest, nnet, MASS, dplyr, klaR, and psych. I built functions to produce univariate and bivariate summary graphs, produced a correlation matrix and displayed the correlations statistically significant, came up with prediction models using Simple Logistic Regression, Multinomial Logistic Regression, and Linear Discriminant Analysis, and chose the best model for this case as Simple Logistic Regression. 

The datasets used in the project are from:
https://www.kaggle.com/uyasarkocal/turkishpolitics (many thanks to Yaşar Koçal, has the political alignments and ideologies of the parties founded in Turkey's history)
https://www.kaggle.com/yemregundogmus/turkey-political-opinions?select=data.csv (many thanks to Yunus Emre Gündoğmuş, has three datasets on the results of an online, volunteering-based survey, asking people's opinions on controversial matters)
https://tr.wikipedia.org/wiki/T%C3%BCrkiye%27de_se%C3%A7imler (for Turkey's general election results)
https://rsf.org/en/ranking_table (for press freedom)
https://developers.google.com/public-data/docs/canonical/countries_csv (used for finding centroids of countries to position the labels)

In this repository, you can find the presentation that I gave in class to summarize my results and my journey with this project, the R Markdown file, a knitted version of it exported as .docx, and the datasets I got from Kaggle (credits given above).
