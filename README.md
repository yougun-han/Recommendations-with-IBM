# Recommendations-with-IBM

## Table of Contents
1. [Description](#Description)
2. [Getting Started](#gettingstarted)
    1. [File Description](#FileDescription)
    2. [Run Program](#RunProgram)
3. [Author](#Author)
4. [Acknowledgements](#Acknowledgements)

## Description <a name="Description"></a>
This project is completed as a part of Udacity Data Scientist Nanodegree Program.

The goal of the project is to build a framework for article recommendation system for users in [IBM Watson Studio platform](https://jp-tok.dataplatform.cloud.ibm.com/login?context=cpdaas).


The project consists of five parts:

- Exploratory Data Analysis
- Rank Based Recommendations
    - Rank the articles based on the number of interation with users
    - This method is particularly useful when there is no information regarding users and articles (ex. new users).
- User-User Based Collaborative Filtering
    - Find similar users in the system based on their article intraction history and recommend articles read by similar users but not by a target user
- Content Based Recommendations (Not done yet. It's for future work)
    - Extract the features of article using NLP and caclulate similarity between articles
    - This method can recommend articles similar to those read by users 
- Matrix Factorization
    - Extract latent features and its relationship between articles and users from matrix decomposition. 
    - We may be able to predict a new particles that user might read

## Getting Started <a name="gettingstarted"></a>

### File Description <a name="FileDescription"></a>
<pre>
- Recommendations-with-IBM    
|- data
|   |- articles_community.csv       # article data
|   |- user-item-interactions.csv   # user and item interaction data
|
|- Recommendations_with_IBM.ipynb   # Main workfile / output of the project
|- Recommendations_with_IBM.html    # Main workfile / output of the project in html format for readers
|- project_tests.py                 # test algorithm file prepared by udacity. used in main owrk file
|- top_10.p                         # test data prepared by udacity. used in main owrk file
|- top_20.p                         # test data prepared by udacity. used in main owrk file
|- top_5.p                          # test data prepared by udacity. used in main owrk file
|- user_item_matrix.p               # test data prepared by udacity. used in main owrk file
|- README.md
|- LICENSE
</pre>

### Run Program <a name="RunProgram"></a>
- Open "Recommendations_with_IBM.ipynb" and run cell one by one. This is a framework not final recommendation engine product.

## Author <a name="Author"></a>
[Yougun Han](https://www.linkedin.com/in/yougun-han/)

## Acknowledgements <a name="Acknowledgements"></a>
I would like to thank Udacity and IBM for designing the project.
