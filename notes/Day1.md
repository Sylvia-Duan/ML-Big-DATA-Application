# *Morning Session*

Everyone introduced themselves, including grade, school, what they want to learn through this course, future plan and hobbies.

# *Afternoon Session*

## Introduction to Machine Learning (ML)
On the class, we first watched a video about the fight between Iron Man and Captain America. Then, we were assigned to different groups to discuss what data should we collect in this video. Through the discussion and conversation, our group concluded several focuses: the speed & force & direction of attacking action, the distance between the close-in weapons and Iron Man itself, and etc. And the next question was how to collect these data. The gathering method might be experiments with different combinations of the data discussed above in various values.

Here comes the true topic, MACHINE LEARNING. It is a method of data analysis that automates analytical model building. It is a branch of artificial intelligence based on the idea that systems can learn from data, identify patterns and make decisions with minimal human intervention. (Definition from [here](https://www.sas.com/en_us/insights/analytics/machine-learning.html))

## Supervised Learning
Data types
* Explanatory variables (X)
* Response variables (Y)
  1. Continuous
  2. Discrete
Supervised learning is defined by its use of labeled datasets to train algorithms that to classify data or predict outcomes accurately. (Definition from [here](https://www.ibm.com/cloud/learn/supervised-learning))
-If Y is continuous, we have a regression problem.
-If Y is discrete, we have a classification problem.

During the class, I found that the terms of "continuous" and "discrete" is slightly different from what I learned in my school or in the IB Math system. In the IB Math system, "continous" means that a continous random variable can take any value within some interval on the number line, while "discrete" means that a discrete random variable has a set of distinct possible values. In data science, the occurrence of "discrete" indicates a classification problem, and this is more like the term "categorical random variable" which is distinguished from the general term "numerical random variable" includes continous ones and discrete ones. And the occurrence of "continuous" indicates a regression problem.

## Pipeline
1. Stage I
Data→Process→Machine learning→Backtest
Using X to make educate guess on Y such that yhat which is based on f(X) is accurate at predicting Y
2. Stage II - final production
