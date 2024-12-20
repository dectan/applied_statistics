# Applied Statistics

<p>Student Number: G00364639</p>
<p>This repository is used for the project given during the Applied Statistic module on Higher Diploma in Data Analytics course from ATU.</p>

<p>I have created Jupyter Notebook in Visual Studio Code, & I have added comments to explain work, along with references<br>

<p>For this markup sheet, I used the following websites as guides.<br>

<ol>
<li><a href="#">https://www.markdownguide.org/basic-syntax</a></li>
<li><a href="#">https://www.w3schools.io/file/markdown-cheatsheet/</a></li></p>
</ol>

# **Table of contents**
* [Applied_Statistics](Applied_Statistic)
    1. [Introduction](#Introduction)
    2. [How to run program](#How-to-run-program)
    3. [Additional Information](#Additional-Information)
    4. [Imported Libraries](#Imported-Libraries)

# Introduction #

<p>This repository is used for the project given during the Applied Statistics module on Higher Diploma in Data Analytics course from ATU.</p>

<p>For this module I created two notebooks.</p>

<p>
<li>tasks.ipynb, which contains all the work relating to tasks section</li>
<li>project.ipynb, which contains all the work relating to project section</li>
</p>

# Additional Information #
<ol>
<li> My github repository is @ <a href="#">https://github.com/dectan/applied_statistics</a></li>
<li> My github Repository is called "applied_statistic</li>
<li> This repository contains a .gitignore file, 2 *  Jupyter notebooks, 1 * README file, folder called "datafolder" which contains dataset and a folder with images. </li>   
<li> My Jupyter notebooks are called "project.ipynb" and "tasks.ipynb"</li> 
<li> There are no additional files required to run program as dataset and images have been saved in folders in this repoitory </li>
<li> images are stored in a folder called "img" in this repository </li>
<li> Libraries that need to be imported are contained in first *text* cell of both Jupyter notebooks </li> 
</ol>

# How to run program #
<ol>
<li> Install Anaconda </li>
<li> Install Visual Studio Code </li>   
<li> Clone repository </li> 
<li> Open repository in Visual Studio Code </li>
</ol>


# Imported Libraries & functions #
<ol>.
<li>import numpy as np</li>
<p> NumPy is short for "Numerical Python". It allows for matematical and logical operations on arrays efficiently. NumPy also enables user to reshape,slice ,stack and join arrays.</p>
<li>import pandas as pd</li>
<p>Pandas is an open source Python library that provides high performance data manipulation tools and analysis tools. It also allows for reading and writing from various file formats, such as .csv. Pandas has functions for analyzing, cleaning , exploring and manipulating data</p>
<li>import matplotlib.pyplot as plt</li>
<p>Matplotlib is a low level graph plotting library in python. It is open source. Using Mathplotlib, different types of plots can be created, such as scatter plots, histograms,box plots etc.</p>
<li>import seaborn as sns</li>
<p>Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.It is designed to work well with dataframes from Pandas</p>
<li>from scipy import stats</li>
<p>scipy.stats module in SciPy provides a wide range of statistical functions, probability distributions, and statistical tests.</p>
<li>from scipy.stats import shapiro</li>
<p>The Shapiro-Wilk test tests the null hypothesis that the data was drawn from a normal distribution.</p>
<li>from scipy.stats import norm</li>
<p>The scipy.stats.norm module in SciPy provides functions for working with the normal distribution. It includes methods for generating random variates</p>
<li>from scipy.stats import ttest_rel</li>
<p>ttest_rel calculates the t-test on two variables.</p>
<li>import math</li>
<p>math is a standard module</p>
<li>from math import comb</li>
<p>math.comb() method returns the number of ways picking k unordered outcomes from n possibilities</p>
<li>import statsmodels.api as sm</li>
<p>powerful Python library used for statistical modeling</p>
<li>from statsmodels.stats.multicomp import pairwise_tukeyhsd</li>
<p>is used to perform Tukey's Honestly Significant Difference (HSD) test </p>

</ol>

# Task details #
<p> The tasks section scope is as follows
<ol>
<li> **Task 1** : Lady Tasting Tea Permutations and Combinations
Suppose we alter the Lady Tasting Tea experiment to involve twelve cups of tea. Six have the milk in first and the other six having tea in first. A person claims they have the special power of being able to tell whether the tea or the milk went into a cup first upon tasting it. You agree to accept their claim if they can tell which of the six cups in your experiment had the milk in first.  

Calculate, using Python, the probability that they select the correct six cups. Here you should assume that they have no special powers in figuring it out, that they are just guessing. Remember to show and justify your workings in code and MarkDown cells.  

Suppose, now, you are willing to accept one error. Once they select the six cups they think had the milk in first, you will give them the benefit of the doubt should they have selected at least five of the correct cups. Calculate the probability, assuming they have no special powers, that the person makes at most one error.

</li>
==============================================================================
<li> **Task 2** : numpy's Normal Distribution  

In this task you will assess whether numpy.random.normal() properly generates normal values. To begin, generate a sample of one hundred thousand values using the function with mean 10.0 and standard deviation 3.0.  

Use the scipy.stats.shapiro() function to test whether your sample came from a normal distribution. Explain the results and output.  

Plot a histogram of your values and plot the corresponding normal distribution probability density function on top of it.  

 </li> 
==============================================================================

<li> **Task 3** :  t-Test Calculation  

Consider the following dataset containing resting heart rates for patients before and after embarking on a two-week exercise program.  


Patient ID	0	1	2	3	4	5	6	7	8	9
Before	63	68	70	64	74	67	70	57	66	65
After	64	64	68	64	73	70	72	54	61	63

Calculate the t-statistic based on this data set, using Python. Compare it to the value given by scipy.stats. Explain your work and list any sources used.

</li> 
==============================================================================

<li> **Task 4** : ANOVA   

In this test we will estimate the probability of committing a type II error in specific circumstances. To begin, create a variable called no_type_ii and set it to 0.  

Now use a loop to perform the following test 10,000 times.  

Use numpy.random.normal to generate three samples with 100 values each. Give each a standard deviation of 0.1. Give the first sample a mean of 4.9, the second a mean of 5.0, and the third a mean of 5.1.  

Perform one-way anova on the three samples and add 1 to no_type_ii whenever a type II error occurs.  

Summarize and explain your results

</li> 
</ol>
</p>
==============================================================================

# Project details #

<p> The project scope is as follows
<ol>
<li> Analyze the PlantGrowth R dataset </li>
<li> Describe what a t-test is, how it works, and what the assumptions are </li>
<li> Perform t-tests </li>   
<li> Perform ANOVA </li> 
<li> Explain why it is more appropriate to apply ANOVA rather than several t-tests when analyzing more than two groups.</li>
</li>
</ol>
</p>