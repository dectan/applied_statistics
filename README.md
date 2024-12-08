# Applied_Statistics

<p>G00364639</p>
<p>This repository is used for the project given during the Applied Statistic module on Higher Diploma in Data Analytics course from ATU.</p>

<p>I have created Jupyter Notebook in Visual Studio Code, & I have added added comments to explain work, along with references<br>

<p>For this markup sheet, I used the following websites as guides.<br>

<ol>
<li><a href="#">https://www.markdownguide.org/basic-syntax</a></li>
<li><a href="#">https://www.w3schools.io/file/markdown-cheatsheet/</a></li></p>
</ol>

# **Table of contents**
* [FUNDAMENTALS-OF-DATA-ANALYSIS](FUNDAMENTALS-OF-DATA-ANALYSIS)
    1. [Introduction](#Introduction)
    2. [How to run program](#How-to-run-program)
    3. [Additional Information](#Additional-Information)
    4. [Imported Libraries](#Imported-Libraries)

# Introduction #

<p>This repository is used for the project given during the FUNDAMENTALS-OF-DATA-ANALYSIS module on Higher Diploma in Data Analytics course from ATU.</p>

<p>For this module I created two notebooks.</p>

<p>
<li>tasks.ipynb, which contains all the work relating to tasks section</li>
<li>project.ipynb, which contains all the work relating to project section</li>
</p>
<p> The tasks section scope is as follows
<ol>
<li> *Task 1* : Permutations and Combinations
Suppose we alter the Lady Tasting Tea experiment to involve twelve cups of tea. Six have the milk in first and the other six having tea in first. A person claims they have the special power of being able to tell whether the tea or the milk went into a cup first upon tasting it. You agree to accept their claim if they can tell which of the six cups in your experiment had the milk in first.

Calculate, using Python, the probability that they select the correct six cups. Here you should assume that they have no special powers in figuring it out, that they are just guessing. Remember to show and justify your workings in code and MarkDown cells.

Suppose, now, you are willing to accept one error. Once they select the six cups they think had the milk in first, you will give them the benefit of the doubt should they have selected at least five of the correct cups. Calculate the probability, assuming they have no special powers, that the person makes at most one error.

</li>
====================================================================================
<li> *Task 2* : numpy's Normal Distribution
In this task you will assess whether numpy.random.normal() properly generates normal values. To begin, generate a sample of one hundred thousand values using the function with mean 10.0 and standard deviation 3.0.

Use the scipy.stats.shapiro() function to test whether your sample came from a normal distribution. Explain the results and output.

Plot a histogram of your values and plot the corresponding normal distribution probability density function on top of it. </li>
====================================================================================
<li> *Task 3* :  </li> 
====================================================================================
<li> *Task 4* :</li> 
===================================================================================
<li> *Task 5*   </li>
===================================================================================
</ol>
</p>

<p> The project scope is as follows
<ol>
<li>  </li>
<li> </li>
<li>  </li>   
<li>  </li> 
<li> 
</li>
</ol>
</p>

# How to run program #
<ol>
<li> Install Anaconda </li>
<li> Install Visual Studio Code </li>   
<li> Clone repository </li> 
<li> Open repository in Visual Studio Code </li>
</ol>

# Additional Information #
<ol>
<li> My github repository is @ <a href="#">https://github.com/dectan/FUNDAMENTALS-OF-DATA-ANALYSIS</a></li>
<li> My github Repository is called "Applied Statistic</li>
<li> This repository contains a .gitignore file, 2 *  Jupyter notebooks, and a readme file and a folder with images. </li>   
<li> My Jupyter notebooks are called "project.ipynb" and "tasks.ipynb"</li> 
<li> There are no additional files required to run program as dataset is loaded from seaborn </li>
<li> images are stored in a folder called "img" in this repository </li>
<li> Libraries that need to be imported are contained in first *text* cell of both Jupyter notebooks </li> 
</ol>

# Imported Libraries #
<ol>
<li>import numpy as np</li>
<p> NumPy is short for "Numerical Python". It allows for matematical and logical operations on arrays efficiently. NumPy also enables user to reshape,slice ,stack and join arrays.</p>
<li>import pandas as pd</li>
<p>Pandas is an open source Python library that provides high performance data manipulation tools and analysis tools. It also allows for reading and writing from various file formats, such as .csv. Pandas has functions for analyzing, cleaning , exploring and manipulating data</p>
<li>import matplotlib.pyplot as plt</li>
<p>Matplotlib is a low level graph plotting library in python. It is open source. Using Mathplotlib, different types of plots can be created, such as scatter plots, histograms,box plots etc.</p>
<li>import seaborn as sns</li>
<p>Seaborn is a Python data visualization library based on matplotlib. It provides a high-level interface for drawing attractive and informative statistical graphics.It is designed to work well with dataframes from Pandas
</ol>

Purpose
The purpose of the assessment is for you to demonstrate ability in the following.

Describe the stochastic nature of real-world measurements.

Source documentation to programmatically perform a statistical test.

Select an appropriate statistical test to investigate a claim.

Perform a statistical test on a data set.

The assessment consists of three overlapping parts: a GitHub repository containing all your work (20%), a series of tasks (40%), and a small project (40%).

Feedback
Guidance on your expected progress will be provided during lectures. At certain points during the semester, submitted repositories will be reviewed. Feedback may be given individually, to the whole class, or both, depending on what is necessary. To get the most benefit from the feedback, ensure you regularly commit and push your work to GitHub.

If you have any questions, ask them well in advance of the deadline. Pay close attention to the marking scheme and the advice below. They are based on feedback given to previous students in this and other modules. You should treat it as a form of feed-forward to help you improve.

Repository (20%)
Start by creating a new repository on GitHub. Include in it only work that is part of your submission. Make sure your final submission is in the main branch, though you can use other branches for development. Your grade will be based on the last commit made on or before the deadline.

Submit Your Repository Info
Immediately submit your GitHub username and repository name using this form. The form is only accessible through your ATU student account.
You can find your username and repository name in the browser's address bar when viewing your repository on GitHub. In the browser's location bar your will see something like github.com/<username>/<repository_name>/

Organize Your Repository
Your work should be easy to showcase during a technical interview. An interviewer should be able to understand and interact with your work without any assistance. This will have a significant impact on your mark for this and other components.

To this end, make sure your repository is well-structured and includes:

A clear README.md.
A relevant .gitignore file.
No unnecessary files or folders.
Lowercase file and folder names, except for files like README.md.
No spaces or special characters in filenames. Underscores, hyphens, and full stops are okay.
Private Repositories
You can make your repository private. If you do, add ianmcloughlin as a collaborator.

Choosing a GitHub Username
Your GitHub username will be visible to potential employers. Choose wisely. You can use your real name, but a pseudonym is also fine if it’s reasonable. Avoid using your student number. You can change your username by following the instructions on GitHub.

Tasks (40%)
Complete all tasks in a notebook called tasks.ipynb in your repository.

For each task, you should write your code in code cells while using MarkDown cells to give explanations and insights into your code. Break up your code into smaller, manageable cells whenever possible. Each code cell should focus on a single step in your overall solution.

Include comments in all code cells to tell the reader what each statement does. Write clean, readable, and efficient code, using meaningful variable names and consistent formatting. You should follow Python coding standards and guidelines such as PEP8.

Make regular commits to your repository while completing the tasks. Your commit history should demonstrate how each solution to each task evolved. There should be several commits for each task demonstrating incremental improvements, clarifications, and revisions.

Task 1: Permutations and Combinations
Suppose we alter the Lady Tasting Tea experiment to involve twelve cups of tea. Six have the milk in first and the other six having tea in first. A person claims they have the special power of being able to tell whether the tea or the milk went into a cup first upon tasting it. You agree to accept their claim if they can tell which of the six cups in your experiment had the milk in first.

Calculate, using Python, the probability that they select the correct six cups. Here you should assume that they have no special powers in figuring it out, that they are just guessing. Remember to show and justify your workings in code and MarkDown cells.

Suppose, now, you are willing to accept one error. Once they select the six cups they think had the milk in first, you will give them the benefit of the doubt should they have selected at least five of the correct cups. Calculate the probability, assuming they have no special powers, that the person makes at most one error.

Would you accept two errors? Explain.

Task 2: numpy's Normal Distribution
In this task you will assess whether numpy.random.normal() properly generates normal values. To begin, generate a sample of one hundred thousand values using the function with mean 10.0 and standard deviation 3.0.

Use the scipy.stats.shapiro() function to test whether your sample came from a normal distribution. Explain the results and output.

Plot a histogram of your values and plot the corresponding normal distribution probability density function on top of it.

Task 3: t-Test Calculation
Consider the following dataset containing resting heart rates for patients before and after embarking on a two-week exercise program.

Patient ID	0	1	2	3	4	5	6	7	8	9
Before	63	68	70	64	74	67	70	57	66	65
After	64	64	68	64	73	70	72	54	61	63
Calculate the t-statistic based on this data set, using Python. Compare it to the value given by scipy.stats. Explain your work and list any sources used.

Task 4: ANOVA
In this test we will estimate the probability of committing a type II error in specific circumstances. To begin, create a variable called no_type_ii and set it to 0.

Now use a loop to perform the following test 10,000 times.

Use numpy.random.normal to generate three samples with 100 values each. Give each a standard deviation of 0.1. Give the first sample a mean of 4.9, the second a mean of 5.0, and the third a mean of 5.1.

Perform one-way anova on the three samples and add 1 to no_type_ii whenever a type II error occurs.

Summarize and explain your results.

Project (40%)
Complete the project in a single notebook called project.ipynb in your repository. The same style should be used as detailed above: explanations in MarkDown and code comments, clean code, and regular commits. Use plots as appropriate.

In this project, you will analyze the PlantGrowth R dataset. You will find a short description of it on Vicent Arel-Bundock's Rdatasets page. The dataset contains two main variables, a treatment group and the weight of plants within those groups.

Your task is to perform t-tests and ANOVA on this dataset while describing the dataset and explaining your work. In doing this you should:

Download and save the dataset to your repository.

Describe the data set in your notebook.

Describe what a t-test is, how it works, and what the assumptions are.

Perform a t-test to determine whether there is a significant difference between the two treatment groups trt1 and trt2.

Perform ANOVA to determine whether there is a significant difference between the three treatment groups ctrl, trt1, and trt2.

Explain why it is more appropriate to apply ANOVA rather than several t-tests when analyzing more than two groups.

Marking Scheme
Each component will be graded based on the following four categories. Each category carries equal weight.

Remember, your repository is what will be evaluated. It should demonstrate evidence of the criteria outlined for each category. That said, the examiners' overall impression of the submission may affect marks in each category.

You are expected to make steady progress on the assessment throughout the semester. This should be reflected in your commit history. Huge commits, especially late in the semester, will not be accepted. At any stage you may be asked to discuss the work to date in your repository.

If you encounter issues with your repository, seek help well before the deadline. Do not delete any files or commits without first consulting the lecturer.

Research
Evidence of research on relevant topics.
Appropriate referencing.
Building upon the literature and documentation.
Comparisons to similar work.
Development
Clear, concise, and correct code.
Appropriate tests.
Knowledge of different approaches and algorithms.
Clean architecture.
Documentation
Clear explanations of concepts.
Concise comments in code and elsewhere.
Appropriate README for repository.
Consistency
Tens of commits, each representing a reasonable amount of work.
Literature, documentation, and code evidencing work on the assessment.
Evidence of reviewing and refactoring.
Advice
The freedom provided in open-style assessments such as this one can feel challenging. You need to decide how to start, what content to include, how much to cover, and how to make the work your own.

The assessment is designed to provide you with opportunities for independent thinking and decision-making. Employers value graduates who can take initiative, work independently, and make design decisions with minimal guidance. We expect you to have basic programming knowledge and be able to find information on your own.

You should have a clear plan before you start coding. Your submission should include both your plan and an explanation of any design choices you made.

Make sure to follow ATU's policies and regulations which are on the Student Hub. Pay particular attention to any policies on plagiarism and the Student Code. If you're unsure about anything, ask the lecturer.