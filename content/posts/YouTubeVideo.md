+++
date = '2024-06-02T21:57:28+08:00'
draft = false
title = 'YouTube Video Popularity Analysis'
tags = ["Python","Stata"]
+++

This is a project that used Stata to analyze videos on YouTube trend. There are datasets of YouTube trend videos from 10 countries, including channel name, channel id, video id, video type, number of likes, number of dislikes, etc.

I selected the data of South Korea to study what factors influenced the popularity of these videos, so that they could occupy a position in trend. I put forward four hypotheses as below:

+ For all categories, views, comments, tags and description have positive effects on likes, while disabled comments and ratings provide negative effects.
+ Videos posted at night (6p.m. – 12a.m.) are more likely to get likes.
+ Videos posted in July are more likely to get likes.
+ Entertainment category is more likely to be popular.
    
In terms of data processing, I first used Python for basic preprocessing, including removing duplicates and deleting illegal values. The data distribution diagram and the correlation diagram of attributes are drawn using Python. I used different regression models to test the hypothesis, which are detailed in the document.

*[YouTube Video Popularity Analysis](https://drive.google.com/drive/folders/1bUYhiD0EL1z536NYN2l7fKbMMSoolC9y?usp=sharing)*