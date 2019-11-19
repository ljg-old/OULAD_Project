
<img src="https://bit.ly/2VnXWr2(14 kB)
https://bit.ly/2VnXWr2
" alt="Ironhack Logo" width="100" align="right"/>


<img src="https://www.google.com/url?sa=i&source=images&cd=&ved=2ahUKEwj8uc3cuPblAhUMExoKHdy6DScQjRx6BAgBEAQ&url=https%3A%2F%2Fmedium.com%2F%40danielitohead%2Flearning-analytics-para-no-especialistas-justo-lo-que-necesitas-saber-d48cf94cf797&psig=AOvVaw1chcy9uhYcXi2T0Cj-SwbI&ust=1574258661442447
" alt="Learning Analytics" width="300"/>

#  Ironhack Final Project | #EdTech Learning Analytics

Laura Jiménez
Data Analytics PT | Barcelona | May 2019

## Content

- [Overview](#Overview)
- [Data & Pre-processing](#Data)
- [EDA](#EDA)
- [Model](#Model)
- [Conclusions](#conclusions)
- [Improvements](#improvements)

<a name="Overview"></a>

## Overview

The number of <b>e-Learning</b> platforms has been exponentially growing over the past years (EdX, Coursera, LinkedIn, Duolingo, Miríadax, CodeAcademy, DataCamp, Mimo, Google Academy...).

Since e-Learning is a growing business, <b>learning analytics</b> is becoming a very important part in order to make a difference.

We get information about users and every interaction they make with the <b>Virtual Learning Environment</b>. We can analyze all this data later on and using to either classify our students/customers or predict their success.

This way, we will be able to constantly improve our e-learning platform, our methodology, our syllabus and many more aspects of the <b>educational product</b>.

In this project, we will be aplying prediction algorithms.

<a name="Data"></a>

## Data & Pre-processing

The Data used in this project was provided by The Open University (UK) under a Creative Commons license.
The dataset is named OULAD (Open University Learning Analytics Dataset) and it contains 7 different tables:

<img src="https://analyse.kmi.open.ac.uk/resources/images/model.png
" alt="OULAD table relationship" />

Regarding the pre-processing:

- Merge several tables into one final dataset.
- Change data types from string to integer and vice versa.
- 

<a name="EDA"></a>

## EDA

In the Exploratoty Data Analysis we check the variable types and also check the distribution of the numerical ones.
On the other hand, we check the correlation between the numerical columns.

<a name="Model"></a>

## Model

We chosed to apply a <b>prediction</b> algorithm.

We tried two of them:

- Linear regression
- RandomForestRegressor

<a name="Conclusions"></a>

## Conclusions

The conclusion is that our data relations are not good enough to train and accept the model.
We'll need to check the relationship between the tables to see if we can add more information to our data in order to improve the model.

<a name="Improvements"></a>

## Improvements

- Add more data to the model, such as Virtual Learning Environment data (clicks per page, attempts per submission...).
- Apply classification algorithms.
- Interactive visualization.
- Dig deeper into regression.



