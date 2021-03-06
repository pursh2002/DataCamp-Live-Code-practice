https://blog.modeanalytics.com/resources-for-data-science-job-seekers/
https://sebastianraschka.com/pdf/manuscripts/model-eval.pdf

by dat tran
My machine learning/data science workflow that I've been practicing for years (Part 1):

1. Scoping:

First you scope the problem that you want to solve. Is that a classification or clustering problem? Do you have enough data? If not can we collect it. API First - where will our machine model be used? What is the latency requirement? How can we re-train our model? What is a good model evaluation?

2. Data Review:

Jupyter Notebook and "import pandas as pd" are my best friends. Do a lot of summaries (min, max, mean, median etc.). Check for outliers. Understand the definition of each column. For classification, check target variables. A lot of plots... matplotlib and seaborn FTW

3. Feature Engineering:

Normalize data, convert data so that it can be used by scikit-learn e.g. one-hot encoding for categorical variables or text data into vectors (bag of words, tf-idf), clean data etc...

4. Feature Review:

Review transformed input data before the modelling. A lot of errors can happen during a transformations e.g. in one hot encoding we forgot one column...

Please kindly share it if you find this workflow useful! Tarry Singh, Han Xiao, Eric Weber, Kyle McKiou, Mike Richardson (迈克尔), Andriy Burkov

P.S. LinkedIn has a limit on characters. 
Here's Part 2: https://lnkd.in/gFcGViR

My machine learning/data science workflow that I've been practicing for years (Part 2):

5. Model Building:

Start with the simplest model e.g. for classification take linear models then use tree-models and then go to neural networks.

6. Model Evaluation:

Evaluate your model. Use simple split then cross-validation. MSE, RMSE for regression. Accuracy, precision, recall and F1 for classification...

7. Operationalization:

Bring your model into production. Only models that are out generate business value. Pickle your scikit-learn model or export your Tensorflow model. Create RESTful API for web applications. Embed it on your device if latency is important.


P.S. LinkedIn has a limit on characters. 
Here's Part 1: https://lnkd.in/g_cpY-W


- - -
Breakdown of Importance
Linear Algebra (35%)
Statistics & Probability (25%)
Calculus (15%)
Optimization & Algorithms (15%)
Other (10%)

➤ Linear Algebra
Matrices, Vectors, Eigenvalues & Eigenvectors, Linear Transformations & Equations
https://lnkd.in/gW6_F_3

➤ Inferential Statistics
Sampling Distribution, Central Limit Theorem, Hypothesis Testing, Types of Errors, Regression, ANOVA, Chi-Square, T-Test
https://lnkd.in/gbh3aRj

➤ Probability Theory
Random Variables, Types of Distributions, Sampling, Confidence Intervals, Z Scores
https://lnkd.in/gJ442c8

➤ Basic Calculus
https://lnkd.in/gEUFDaS

➤ Linear Programming
Formulating a Real Problem to a Mathematical Model
https://lnkd.in/gGBpjaK

➤ Optimization
Gradient Algorithms & Objective Functions
https://lnkd.in/g_e9sJu

➤ Graph Theory
https://lnkd.in/gYUgBhA

➤ Data Structures
https://lnkd.in/gT_8_Fc
