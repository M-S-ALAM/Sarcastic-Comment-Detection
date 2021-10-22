# Sarcastic-Comment-Detection
Machine Learning/Deep Learning
# 1.Business Problem

### 1.1 Problem Description

### What is sarcasm?

<pre>A sarcastic phrase or comment is one that is caustic, harsh, or piercing. Although sarcasm is not always humorous, it might include ambivalence. Sarcasm is most visible in spoken word and is generally context-dependent. It is mostly identified by the inflection by which it is pronounced.
For example: “Excuse me” is sincere. “Excuuuuuse me” is sarcastic, meaning, “I’m not sorry.”</pre>

### Problem Statment:-

<pre>People nowadays prefer to respond sarcastically to almost everything. Sarcasm recognition can help in a better comprehension of the comment and, as a result, the much more appropriate response. For example, if a user makes a sarcastic comment about a product on an e-commerce website, recognizing it will aid in taking the appropriate respond to that comment.</pre>

### 1.2  Features in the Dataset
<pre> Data field:-train-balanced-sarcasam.csv
Source:-https://www.kaggle.com/sherinclaudia/sarcastic-comments-on-reddit</pre>
<pre>
(1) label:-Target variable(sarcastic or non sarcastic)
(2) Author:-Person who commented.
(3) Comment:-Reply to a parent_reddit comment.
(4) ups:-No. of upvotes.
(5) downs:-No. of downvotes.
(6) score:- ups-downs
(7) date:- Comment date.
(8) subreddit:- Topic
(9) created_utc:-comment time in UTC timezone.
(10) parent_comment:-The Parent Reddit comment to which sarcastic replies are made</pre>
## 1.3 Source
<pre>
<li> https://www.kaggle.com/sherinclaudia/sarcastic-comments-on-reddit </li>
<li> https://www.kaggle.com/asifranaar/sarcastic-comments-eda-and-classification </li>
<li> https://medium.com/@roy.aditya1605/reddit-sarcastic-comment-detection-dc665d8d21b9 </li>
<li> https://www.kaggle.com/yudhagalang/lstm-text-classification-on-reddit-sarcasm </li>
<li> https://arxiv.org/pdf/1610.08815.pdf</pre>
## 1.4 Bussnies Objective and Constraints:-
<pre>Data is provided by kaggle https://www.kaggle.com/sherinclaudia/sarcastic-comments-on-reddit,to predict the comment is sarcastic or non sarcastic.This problem is classification problem(Supervised Learning).The features we have in train data label,author,comment,ups,downs,score, subreddit,created_utc,parent_comment.

<li> The target is to solve the problem suggest that a given comment is sarcastic or non sarcastic.</li>
<li> No strict latency constraints,because the problem demand to suggest a highly.</li> </pre>
##  2.Machine Learning Problem
<pre> We need to categorise a given data point into one of two classes indicating whether the statement is sarcastic or non sarcastic.This is Binary classification Problem.</pre>

### 2.2 Example Data Point
<pre> 0,NC and NH.,Trumpbart,politics,2,-1,-1,2016-10,2016-10-16 23:55:23,"Yeah, I get that argument. At this point, I'd prefer is she lived in NC as well."
-------------------------------------------------------------------------------------------------
0,You do know west teams play against west teams more than east teams right?,Shbshb906,nba,-4,-1,-1,2016-11,2016-11-01 00:24:10,The blazers and Mavericks (The wests 5 and 6 seed) did not even carry a good enough record to make the playoffs in the east last year.
-------------------------------------------------------------------------------------------------
0,"They were underdogs earlier today, but since Gronk's announcement this afternoon, the Vegas line has moved to patriots -1",Creepeth,nfl,3,3,0,2016-09,2016-09-22 21:45:37,They're favored to win.</pre>
### 2.3 Type of Machine Learning Problem

<pre> We need to categorise a given data point into one of two classes indicating whether the statement is sarcastic or non sarcastic.This is Binary classification Problem.</pre>
### 2.4 Performance metric
<pre> 
<li>Confusion metric </li> 
<li>Accuracy</li></pre>

### Blog link:-https://medium.com/@mdshahbazpatna012/sarcastic-comments-detection-reddit-an-end-to-end-case-study-e0de7fb275a4
