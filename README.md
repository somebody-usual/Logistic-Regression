# Logistic-Regression

Logistic Regression is a variation of Linear Regression, useful when the observed dependent variable, y, is categorical. It produces a formula that predicts the probability of the class label as a function of the independent variables.

Logistic regression fits a special s-shaped curve by taking the linear regression function and transforming the numeric estimate into a probability with the following function, which is called the sigmoid function π:

β_π(π₯)=π(πππ)=π(π_0+π_1π₯_1+π_2π₯_2+...)1+π(π_0+π_1π₯_1+π_2π₯_2+β―)
 
Or:
ππππππππππ‘π¦ππππΆπππ π _1=π(π=1|π)=π(πππ)=ππππ1+ππππ
 
In this equation,  πππ  is the regression result (the sum of the variables weighted by the coefficients), exp is the exponential function and  π(πππ)  is the sigmoid or logistic function, also called logistic curve. It is a common "S" shape (sigmoid curve).

So, briefly, Logistic Regression passes the input through the logistic/sigmoid but then treats the result as a probability:



The objective of the Logistic Regression algorithm, is to find the best parameters ΞΈ, for  β_π(π₯)  =  π(πππ) , in such a way that the model best predicts the class of each case.
