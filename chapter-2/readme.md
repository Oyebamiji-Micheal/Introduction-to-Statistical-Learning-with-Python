# Introduction to Statistical Learning with Python
## Chapter 2: Statistical Learning 
Chapter 2 introduces the fundamentals of statistical learning such as parametric and non-parametric method of learning, reducible and irreducible errors, the trade-off between prediction accuracy and model interpretability, and so on.

### Learning Outcomes
Below are some of the concepts I learned in chapter 2
- <p align="justify">Statistical learning is broadly divided into supervised and unsupervised learning. In supervised learning, we have some set of inputs and outputs. However, there are no labels or outputs in unsupervised learning.</p>
- <p align="justify">Ultimately, the goal of supervised learning is to predict some output given one or more input. Mathematically, we can expressed this in the form $Y = f(X) + ϵ$. $f$ is some fixed but unknown function of X (input), ϵ is a random error term.</p> 
- <p align="justify">In a real-world setting, we generally do not understand the form (shape) of the function $f$. Hence, we make an assumption about the functional shape of f. For example, we can may assume a linear relationship between our inputs and targets. This method of learning is referred to parametric / inflexible method of learning. Examples include linear regression, logistic regression, polynomial regression, and so on. While statistical tools which employ this form of learning are computationally less expensive and more interpretable, they however make assumptions about the shape or underlying distribution of f which makes them less robust and perform poorly on complex data. </p>
- <p align="justify">Non parametric learning methods are also referred to as flexible statistical learning methods. They do not make any assumptions about the shape or underlying distribution of f. This makes them more efficient and robust in capturing non-linear relationships in the data. Examples include k-nearest neighbors, decision trees, random forests, neural networks, etc. However, they can be computationally expensive and also they are not easily interpretable like their counterpart.</p>
- <p align="justify">Highly flexible models tend to have high variance i.e. any small changes in the training data results in a large changes in the prediction function. Less flexible models such as linear regression have low variance - any change in the data will only cause the fitted line to shift slightly.</p>
- <p align="justify">As a general rule, as we use more flexible methods, the variance will increase and the bias will decrease.</p>

### Applied Exercises
Python implemented solution to the applied exercise in chapter 2 can be found [here](https://github.com/Oyebamiji-Micheal/Introduction-to-Statistical-Learning-with-Python/tree/main/chapter-2).

### Articles written
- [Parametric vs Non-Parametric Learning Methods](https://medium.com/@oyebamijimicheal10/parametric-vs-non-parametric-statistical-learning-methods-a03f45431619)