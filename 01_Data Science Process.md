
# The Data Science Process

![](https://miro.medium.com/max/1400/0*5j1SYsfzlt_u2DcN)

Photo by  [Lukas Blazek](https://unsplash.com/@goumbik?utm_source=medium&utm_medium=referral)  on  [Unsplash](https://unsplash.com/?utm_source=medium&utm_medium=referral)

Data Science is a buzzword that’s been sizzling in the tech industry over the last few years. What happens in a data science project? Is it just that a problem statement is given and a model is applied to data to get the desired solution? Well, that's  _partially right_.  
So to make these concepts clear, let's go through the process of what happens right after a problem statement is set in a data science project.

> One shall find different explanations of the data science process, it changes with the type of project, organisation and the very perception of how a problem can be  **solved**. It must be noted that this process may not just include one person but people from varying positions like  **Data Analyst, Data engineer, Machine learning Engineer** and **Data Scientist**.

![](https://miro.medium.com/max/1400/1*LJapdF7C_qzwaABD_kLpZA.png)

Illustration on the Data Science Process

# Phase 1: Understanding the Problem

This phase deals with small significant actions like discovering a problem, understanding the problem and then framing a problem statement. Questions are asked and hypotheses are tested to find an optimal solution.  
For most problem statements in data science, this is the borderline where a business problem transforms into a data-oriented problem(_Dataset Discovery & Analysis_).

# Phase 2: Data Collection & Wrangling

After understanding the problem statement, the next step is collecting data. Data is acquired in its raw form which means there are missing values, duplicates, wrong entries and domain errors in the data collected. This data should be cleaned and wrangled according to the problem statement’s requirements. If you're using python for the project then pandas shall be your magic wand for this phase of wrangling Data.

# Phase 3: Exploratory Data Analysis

The collected data doesn't always speak for itself. But when statistics and visualisations are brought into the picture it does wonders. This phase has a lot to do with uncovering hidden patterns from the data -Descriptive Analysis. Visualisation speaks for itself. Analysing trends of the data happen to be one of the most crucial steps in the process because this analysis is directly proportional to what you conclude from the data and which model you plan to run on the data. Tools used (Python: matplotlib, plotly packages),(Tableau).

# Phase 4: Model Planning & Building

Here, the information gathered from EDA is used for making connections between factors in the data that can be utilized to create a predictive model. This step stands as a base for the model building. A model is then built for predictive analysis of the data that uses specific machine learning algorithms like regression, classification, clustering and so on. sklearn, Tensorflow and PyTorch are the most used for Model Building.

# Phase 5: Model Deployment

So now the model built, is run on different datasets for training and testing that shall help in identifying the underfitting and overfitting problems of the machine learning model. If everything is okay, the model is used as a predictive model to meet the goals created in the very first phase of Understanding the Problem.

> And obviously, the process doesn't end after these 5 major phases.. it might cycle through itself depending on situations demanding specified data-wrangling or model improvements.

## Related Links :

[Sentimental Analysis of Covid Vaccine related Tweets](https://www.kaggle.com/code/amartyanambiar/covid-19-vaccine-sentitmental-analysis)

[5 PyTorch Functions you must know!](https://amartyanambiar.medium.com/5-pytorch-tensor-functions-you-should-know-38fe12ff982f)

[Delivering High-Quality Analytics at Netflix](https://youtu.be/nMyuCdqzpZc)
