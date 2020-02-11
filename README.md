# Probability-Lottery-Addiction-Mobile-App
# Lottery Addiction mobile app
## Introduction
Many people start playing the lottery for fun, but for some this activity turns into a habit which eventually escalates into addiction. Like other compulsive gamblers, lottery addicts soon begin spending from their savings and loans, they start to accumulate debts, and eventually engage in desperate behaviors like theft.
## Goal
In this project, we will help develop a mobile app meant to help lottery addicts better estimate their chances of winning.
Our stakeholders want to focus on 6/49 lottery and answer these questions:
- What is the probability of winning the big prize with a single ticket?
- What is the probability of winning the big prize if we play 40 different tickets (or any other number)?
- What is the probability of having at least five (or four, or three, or two) winning numbers on a single ticket?
## Data description
We will be using 6/49 lottery dataset from Kaggle with 3665 drawings, dating from 1982 to 2018. The dataset can be found here:
https://www.kaggle.com/datascienceai/lottery-dataset
Lanuched in 1982, 6/49 lottery is very popular in Canada. As the name implies, six numbers are drawn from a set of 49 numbers that range from 1 to 49. A player wins the big prize if the six numbers on their tickets match all the six numbers drawn. If a player has a ticket with the numbers {13, 22, 24, 27, 42, 44}, he only wins the big prize if the numbers drawn are {13, 22, 24, 27, 42, 44}. If only one number differs, he doesn't win. The drawing is done without replacement, which means once a number is drawn, it's not put back in the set.
