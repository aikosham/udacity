# Data Science Nanodegree

This repo contains the files for the Data Science nanodegree, project 1. The goal is to write a datascience blog post for a non-technical audience.

I chose the [Titanic dataset available from Kaggle](https://www.kaggle.com/c/titanic/data?select=train.csv).

- [`1-blog`](./1-blog) contains the files for the data science blog post

## Pre-requisites
`requirements.txt` contains the exact virtualenv and versions that were used to develop all the files for this nanodegree.

However, for this project, only the following libraries were utilized:

```
numpy==1.19.4
matplotlib==3.3.3
pandas==1.1.5
```

## Project Motivation
Titanic was one of the marvels of engineering in the early 20th century. As part of the nanodegree program, I wanted to analyse some of the data from the dataset available via Kaggle. I wanted to answer the following questions after looking at the dataset:

- Were you more likely to survive as a man or a woman?
- Did children have higher chances of survival?
- What role did Passenger Class play in the survival numbers?

## Repo layout

The repo contains the following files under the `1-blog` folder.
```
.
├── README.md
├── titanic.ipynb
└── train.csv
└── requirements.txt
```

`README.md` is this file, `titanic.ipynb` is the python notebook and `train.csv` contains the dataset from Titanic.

`requirements.txt` contains the exact virtualenv setup that was used. However not all libraries were used in this project.

## Blog Post
The blog post that uses the files is located on Medium: https://aikosham.medium.com/surviving-the-titanic-3f996bf4b8de

## Acknowledgements
I took help from multiple blogs on medium that did orthogonal analysis of the same dataset that I was using. (e.g. especially helpful was this article: https://humansofdata.atlan.com/2016/07/machine-learning-python/)

## Summary
In this analysis we conclude that most of the female passengers survived the ill fated shipwreck. 

Most men perished. Their best chance would be if they were aged 27–31 and in first class.

63% of the passengers in Class 1 survived whereas only 24% of the Class 3 passengers survived. 

Out of 144 females in class 3, 72 survived. Out of 347 men in the same class only 47 survived.

Young children survived as a high percentage in all classes.
