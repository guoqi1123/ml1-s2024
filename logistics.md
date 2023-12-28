---
layout: page
title: Information
permalink: /info/
nav_orders: 2
---
# ECE 50024 / STAT 59800 Machine Learning

## Course Description
This is a graduate-level machine learning course at Purdue ECE. Compared to the various machine learning classes offered on the Internet, this one will focus on the mathematics behind some traditional and fundamental topics in machine learning. The goal of this class is to help students gain a deeper understanding of the mathematical intuition and connection behind a variety of machine learning methods rather than programming per se. 

The four clusters of topics that will be covered in this course are listed below. 

**Mathematical Preliminaries.** Matrices, vectors, Lp norm, geometry of the norms, symmetry, positive definiteness, eigen-decomposition. Unconstrained optimization, graident descent, convex functions, Lagrange multipliers, linear least squares. Probability space, random variables, joint distributions, multi-dimensional Gaussians.

**Linear/nonlinear Classifiers.** Linear discriminant analysis, separating hyperplane, multi-class classification, Bayesian decision rule, geometry of Bayesian decision rule, linear regression, logistic regression, perceptron algorithms, support vector machines, nonlinear transformations, intro to neural networks.

**Learning Theory.** Bias and variance, training and testing, generalization, PAC framework, Hoeffding inequality, VC dimension.

**Robustness.** Adversarial attack, targeted and untargeted attack, minimum distance attack, maximum loss attack, regularization-based attack. Perturbation through noises. Robustness of SVM.

These topics could help you understand the principles and limitations of machine learning methods, which can be generalized to various popular tools nowaday not covered in this class. If you are taking this course as your *first* class in machine learning, it could lay a solid mathematical foundation for you as you journey on in this field. If you already have machine learning backgrounds, the class could possibly provide you addtional understanding of machine learning from a mathematical perspective.

## Pre-requisites
**Linear Algebra:** MIT 18.06 ([textbook](http://math.mit.edu/~gs/linearalgebra/)) / Stanford ENGR 108 ([textbook](https://web.stanford.edu/~boyd/vmls/)) / Purdue MA 511  
**Optimization:** MIT 6.079 / Stanford EE 364A ([textbook](https://stanford.edu/~boyd/cvxbook/)) / Purdue ECE 647  
**Probability:** MIT 6.012 ([textbook](https://www.amazon.com/Introduction-Probability-2nd-Dimitri-Bertsekas/dp/188652923X)) / Purdue ECE 302 ([textbook](https://engineering.purdue.edu/ChanGroup/eBook.html))

To help you determine if you have adequate pre-requisites, we encourage you to try homework 0:

[Homework 0: (PDF.)](/assignments/hw0.pdf)

## Grades
All students will be graded by the rubrics listed below. Everyone (PhD, MS, undergrad, online) will be graded on the same curve. 
If you choose Pass-No Pass, you still need to do everything. If you are above the cut off, you will pass. 


**Homework (8%).** There are five homeworks. I will drop the worst one. Each homework will have 2 points: If you complete the homework, you get 2. If you are partially done with the homework, you get 1. If you do not submit, you get 0. I do not accept late homework.

**Quiz (32%).** There will be five *in-class* quizzes. Each quiz is 40 minutes long. Each quiz will carry 8%. The quizzes are conducted in class after the due date of the homework. Please bring your laptop to the class as you will need to do the quiz on the laptop. During the quiz, I will ask you lecture questions. I will also ask you homework questions. For example, if in the homework I ask you to plot a figure, I may ask you to change a parameter and re-plot the figure. Quizzes will be open-book, open-note, open-computer. However, with only 60 minutes, you probably will not have time to read anything besides answering the questions. So, please do the homework.

**Mini Challenge (10%).** There will be a classwide mini-challenge between homework 3 and 4. The entire class will compete on a [Kaggle Challenge](https://www.kaggle.com/). Each student will develop a machine learning model to solve the challenge and the grade will be based on the accuracy of your model. See homework page for more information. 

**Final Project (50%).** Due Apr 26. You will form teams of five to do the final project. The final project involve developing a deep understanding of a machine learning approach that I assign you, reimplement the approach from scratch, and use your implementation to solve a real world problem that you are interested in. See the project page for the list of topics. You will need to form teams during the first week of the class and I will assign you the topic on the second week. Please refer to the project page for more details of the final project. Selected groups will present their work in class at the end of the semester. 

## Textbook and References
There is no official textbook for this course. Please refer to the lecture note section of the website for our lecture materials.

A few good reference books for this course are:

[Introduction to Probability for Data Science](https://engineering.purdue.edu/ChanGroup/eBook.html), by Stanley Chan, draft. 1st edition. 2020.

[Pattern Classification](https://www.amazon.com/Pattern-Classification-Pt-1-Richard-Duda/dp/0471056693), by Duda, Hart and Stork, Wiley-Interscience; 2 edition, 2000.

[Learning from Data](https://work.caltech.edu/telecourse.html), by Abu-Mostafa, Magdon-Ismail and Lin, AMLBook, 2012.

[Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/), by Hastie, Tibshirani and Friedman, Springer, 2 edition, 2009.

[Pattern Recognition and Machine Learning](https://www.springer.com/us/book/9780387310732), by Bishop, Springer, 2006.



## Programming
We will be primarily using Python. As such, I expect you to have elementary programming skills, e.g., writing a hello world program. More information and resources on how to use Python can be found in the [resource section](../resources/python.html) of this website. 

Besides Python, we use optimization packages to solve optimization problems. Of particular importance is CVX.


## FAQ
- **Am I ready to take the course?**

    There is no official pre-requisite of the course (e.g., taking a prior course), although we expect students to have good background in linear algebra, optimization and probability.

    Historically, undergraduate students and non-ECE PhD students have found this course difficult.

    Pleaes check out the information about pre-requisite to see if you are ready for the course.

- **What is the difference between ECE 595 and other machine learning courses on campus?**

    We focus on general principles of learning.

    Our goal is to provide an in-depth discussion of the subject, rather than superficially glancing through different topics.

    We put significant emphasis on understanding the mathematics behind the algorithms.

    We have plenty of hands-on programming exercises.

- **What will I learn after taking ECE 595?**

    You will know what a linear model is, such as Bayesian decision rule, perceptron algorithm, logistic regressoin, support vector machine, etc.

    You will know how to understand a linear classifier from a geometric perspective.

    You will know how to attack a classifier.

    You will know the how much a machine learning algorithm can do, and what a machine learning algorithm cannot do.

    You will know how to implement machine learning algorithms using Python and CVX.

- **Can I audit the class?**

    Unfortunately, sorry.

- **Where can I get help for programming problems?**

    Please reach out to our teaching assistants.