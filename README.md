## Udacity's Data Scientist Nanodegree - Project 3: *"Recommendation systems with IBM"*

### Table of Contents

1. [Installation](#installation)
2. [Project motivation and components](#motivation_components)
3. [Repository's structure](#structure)

## Installation <a name="installation"></a>

The project utilizes the following Python libraries included in the Anaconda distribution:

- The fundamentals: Pandas and Numpy. 

- ML model saving and loading: Pickle. 

- Static visualizations: Matplotlib and Seaborn. 

The code should run with no issues using Python versions 3.*.

## Project motivation and components <a name="motivation_components"></a>

This project is part of the requirements for Unit 3 in Udacity's Data Scientist Nanodegree. 

The project involves utilizing data from [IBM](https://ibm.com/) to develop a recommendation system for articles and users. The dataset contains two files that include descriptive information about all the articles and the users' interactions with them. 

Overall, the main objective of the project is to use this data to develop a recommendation system that provides personalized and relevant article recommendations to users based on their interests and past interactions with the articles.

The project consists of the following steps:

1. Exploratory data analysis. 
2. Rank based recommendations. 
3. User-user based collaborative filtering. 
4. Content based recommendations. 
5. Matrix SVD factorization. 



## Repository's structure <a name="structure"></a>

The repository is structured as follows:

~~~~~~~
        DSND-Project-3                 
          |-- data
                |-- articles_community.csv     
                |-- user-item-interactions.csv     
          |-- projec_test.py
          |-- Recommendations_with_IBM.html
          |-- Recommendations_with_IBM.ipynb
          |-- top_5.p
          |-- top_10.p
          |-- top_20.p
          |-- user_item_matrix.p
          |-- README
~~~~~~~