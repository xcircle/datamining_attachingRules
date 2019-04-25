# datamining_attachingRules
## Introduction
This is a simple Implement of Apriori in python.

## file
winemag-data-130k-v2.csv is my data which is a list of wine parameters.<br/>
apriori.py is my code which rely on python2.

## prePocesses
As Apriori requires a lot of time to process with the grows of data numbers,I deside to cut the data to retain 1000 items in there so that my algorism can finish with in 1s.

## result
I set the minSupport = 0.15 and minConfidence = 0.6 and the result is like below:<br/>
 ![image](https://github.com/xcircle/datamining_attachingRules/blob/master/image/1.jpg)
