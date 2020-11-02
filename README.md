# Data Science
Udacity Data Science Nanodegree project repository.

Code for the first blog post in Medium:
https://medium.com/@annett.saarik/most-popular-languages-and-frameworks-used-by-developers-2a70cf7189

## Libraries
Python, jupyter notebook, numpy, pandas, matplotlib

## Motivation for the project
Real motivation was the curiosity to find out what languages and frameworks do developer use at the moment and to find out what developers are looking forward to use in the future. This is useful to consider a putting in the time to learn a new language and what should it be.

## Files in the repository 
There is a .ipynb file that contains the Python code that is used to find out and display in a table the results of top 10 in every category: "Most used language", "Most want to use language", "Most used framework" and "Most want to use framework". In addidtion there is a folder named images that consist of plot images from the data results.

## A summary of the results
New popular language to look out for are Rust and Go. Flask is the new lightweight framework to maybe learn more about. 


## Project Questions
### Business Understanding - Brief description
Trying to understand the usage and trends in language and dataframe usage with developers in the StackOverFlow 2020 Survey.
#### Question 1
What are most popular languages and frameworks that developers have used?
#### Question 2
What are most popular languages and frameworks that developers want to use in the future?
#### Question 3
Is there any new languages or frameworks that developers want to use? Are there any supprising trends?

## Data Understanding
#### Access and Explore
Data was downloaded from StackOverflow website.
#### Prepare Data
Reading in the dataset to Jupyter Notebook in the Pandas framework. Left original column names.
#### Wrangle and Clean
Did not clean or remove Nan values from dataset. 
#### Modeling
Only selected columns that I needed to answear my questions. 

#### Question 1 - What are most popular languages and frameworks that developers have used?
After cleaning the data and getting only the columns of interest, I found out that in 2020 to most popular language developers have used is JavaScript. Followed by a close second HTML/CSS (which is not an official language, but let’s move forward with it) and the popular database query language SQL as third.

![1](https://github.com/annetts/datascience/blob/master/images/1.PNG)

Now languages that developers wanted to work within a year. The top of the list seems to look pretty much the same with little differences. Two languages that developers wanted to use in the future but hadn’t used in the last year of coding: Rust and Go. Both new and interesting languages with a growing fan base.

![2](https://github.com/annetts/datascience/blob/master/images/2.PNG)

#### Question 2 - What are most popular languages and frameworks that developers want to use in the future?
Not that surprised by the popularity of jQuery, React, and Angular. Although the fact that React is the second most popular language is sort of mind-boggling. A few years back I did not know anybody who had used it in a work project. On a side project maybe, but not at work.

![3](https://github.com/annetts/datascience/blob/master/images/3.PNG)

Seems like jQuery has lost it’s popularity and React has gained a lot of attention.
One completely new framework in the top ten is Flask. It’s a lightweight Python web application framework, that has gained considerable popularity in a short period of time.

![4](https://github.com/annetts/datascience/blob/master/images/4.PNG)

#### Question 3 - What are the trends and suprising new languages gainig popularity?
JavaScript still very very relavant in the development world. With it React and Angular have gained a lot of popularity. JQuery on the other hand has lost fans. Some newcomers include developers are more and more excited to use are Flask, Rust and Go. 

#### Evaluation and findings
In conclusion it can be read from the data that mostly the languages and frameworks don't change from what is used and what developers want to use in a year or so. Some new languages and frameworks did pop up. Some that I think are not well known. Popularity of Javascript, Python and Java seems like neverending.  

## Necessary acknowledgements 
Big thanks to Udacity reviews for the comments to make this project better.
