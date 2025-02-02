# ML-AI4Econ

Short course of Machine Learning and AI for Economists and other enthusiasts.

### Main Goals

This very short course is designed to give an introduction to statistical learning and the main techniques of machine learning and artificial intelligence for non-STEM students that find valuable to understand more advanced techniques deeply, not just from the coding point of view but from the mathematical one as well.

### Instructions

Please go to the [Course_Notebooks](Course_Notebooks/) folder and enter the notebooks in order. For the slides with the theory, please go to this [file](Course_PPT_Week1.pdf).

### Structure

The course is entirely done through Python Notebooks, which allow to explain the mathematical and statistical theory behind each aspect with a code example. The structure of the course is mostly based on *Elements of Statistical Learning* by *Hastie, Tibshirani* and *Friedman*, and will be structured as follows:

1) We will first do a refresher in multivariate statistics, and then we will introduce some important concepts of statistical learning theory. Notebooks: [1](Course_Notebooks/1_Stats_Refresher.ipynb) and [2](Course_Notebooks/2_StatLearn_Theory.ipynb).

2) Then, we will start by looking at the most basic but useful models in practice: linear models. This will allow us to introduce the regression problem with a little bit more depth and look at interesting features of these models and also useful variants of the most basic ones.

3) After looking at linear regression, we will go to linear models but for classification, which allows to introduce classification problems and investigate important models such as the SVM.

4) Once linear models have been covered, we will go to more complex ones which makes us go from a linear relationships world to a non-linear one. We introduce decision trees and related methods, which are easily understandable and expands the types of methodologies we can use for both regression and classification problems.

5) Because we have now seen trees, it is useful to go into bagging, boosting and ensemble methodologies, which allows us to understand famous models like the random forest and XGBoost.

6) To delve deeper into non-linear relationships, we will introduce deep learning and neural networks, which is the foundation of the so-called artificial intelligence. However, we will be introducing the matter for easy applications that do not need to use complex architectures and models.

7) Finally we will introduce causal inference and causal machine learning, a newly developed field at the moment, which is one of the most promising fields for economists due to their huge implications for macroeconomics and microeconomics.