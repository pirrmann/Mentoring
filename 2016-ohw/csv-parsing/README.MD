# CSV parsing assignment

## Read CSV data

Let's try to read data from a CSV file.

The input can be downloaded at<br>
https://raw.githubusercontent.com/pirrmann/Kaggle-Titanic/master/Titanic/Data/training.csv

First step, let's just try to parse the file content and load it into `string array array`

Beware! Some fields are escaped!

## Add types

* create a type to represent an entry in the file
* load the file into an array of the type you've just created

## Explore data

Try to answer the following questions:
* How many childen below 10 years old were there on the Titanic?
* What is the name of passager with ticket 345572?
* Who paid the most expensive fare to onboard?<br>Did he/she survive?
* Who paid the least expensive fare to onboard?<br>Did he/she survive?
* Among the female 3rd class passagers, what is the survival rate?

## Generic differ

I've taken the file we've just played with, and introduced a few changes in it.

The new file is at<br>
https://raw.githubusercontent.com/pirrmann/Kaggle-Titanic/master/Titanic/Data/training-modified.csv

Can you list me all the differences?

#### Tricks:

 - Try to decompose the problem in smaller problems
 - You might want to try to find a primary key in this data
