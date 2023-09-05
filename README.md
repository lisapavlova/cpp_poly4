{\rtf1\ansi\ansicpg1251\cocoartf2709
\cocoatextscaling0\cocoaplatform0{\fonttbl\f0\fswiss\fcharset0 Helvetica;}
{\colortbl;\red255\green255\blue255;}
{\*\expandedcolortbl;;}
\paperw11900\paperh16840\margl1440\margr1440\vieww11520\viewh8400\viewkind0
\pard\tx566\tx1133\tx1700\tx2267\tx2834\tx3401\tx3968\tx4535\tx5102\tx5669\tx6236\tx6803\pardirnatural\partightenfactor0

\f0\fs24 \cf0 ## Examples of coding and ML modeling\
\
This repository contains examples of my work to demonstrate the skills of writing and formatting Python code, working with data, and applying ML methods.\
___\
#### Project 01: _poly4.ipynb_ - March 2022\
_Master's Degree study project, Kaggle, Regression, Jupyter Notebook_\
Employed _Custom transformers, Pipelines, DataFrameMapper, ElasticNet, Polynomial Features_.\
\
Solving the problem of predicting the price of a used car by its parameters. \
Evaluation metric - RMSE. \
The task was held as a [private Kaggle competition] based on [this Kaggle dataset].\
First place among the students of the course.\
---\
#### Project 02: _[final_price_predictor]_ - Apr-May 2022\
_Master's Degree study project, Regression, PyCharm, Docker_\
Employed _Flask, CatBoost_\
\
End-to-End ML study project: web-service predicting cost of an apartment based on Yandex.Realty data. \
Focus on the full cycle of the project from setting the task to deploying the solution.\
More practice with Git, Docker containers, Python scripts. \
\
> __[final_price_predictor]__ - a separate repository of the project on GitHub: \
README, link to docker hub, more details and instructions for launching the app\
\
---\
#### Project 03: *salary_by_skill* - Nov-Dec 2022\
_Applied project, NLP, text vectorization, Regression, Web-scraping, Jupyter_\
Employed *Selenium, ScikitLearn, Catboost, KNN Regressor, GloVe, TF-IDF, word2wec*\
\
> **Project is documented in [slides]**:\
visualized EDA, model comparison by metrics, more details about ML approaches used\
\
The first step of a larger project to create a recommendation system of skills for job seekers to study in the field of AI/ML. After scraping job postings from the a relevant [job board], I carried out EDA and tried to create a regression model with min.salary for listing as target variable. Using the best model I filled in salary where it was missing, and retrained this best model of the full dataset.\
During 2 weeks of work on the regression model, I managed to reduce MAPE by more than 4 times. Lots of effort was put to working with text of job description: cleaning, translation, text vectorization; also worked lots with skill tags as a binary matrix. \
\
The repository contains part of project files for demonstration:\
- *FinalPreprocessing.ipynb* - chosen preprocessing methodology\
- *full_dataset.csv* - full data array (after scraping, before processing)\
- *modeling_dataset.csv* - preprocessed dataset used by at the final stages of modeling\
- *FinalModeling.ipynb* - creation of final model *cb_final.pkl*\
- *preprocessor.pkl* - the final data transformer used for modeling at later stages\
\
![preprocessor](/images/preprocessor.png) \
Structure of the final preprocessing transformer \
\
\
---\
### Footnotes\
\
![first_entry](/images/first_entry.png) \
**Project 01** - first experience on Kaggle. \
The first entry beat both baselines set by the course instructor.\
\
![jobboard](/images/jobboard.png) \
Job postings' source used for **Project 3** \
\
\
\
\
\
\
\
[//]: # (These are reference links used in the body of this note and get stripped out when the markdown processor does its job. There is no need to format nicely because it shouldn't be seen. Thanks SO - http://stackoverflow.com/questions/4823468/store-comments-in-markdown-syntax)\
\
\
   [final_price_predictor]: <https://github.com/lisapavlova/final_price_predictor>\
   [private Kaggle competition]: <https://www.kaggle.com/competitions/gsom-22sm1-mlbda-ht1>\
   [this Kaggle dataset]: <https://www.kaggle.com/datasets/adityadesai13/used-car-dataset-ford-and-mercedes>\
   [job board]: <https://ai-jobs.net>\
   [slides]: <https://drive.google.com/file/d/1a7PYm2io8FFlqMEsmokq2LYuCOj18WCy/view?usp=share_link>}