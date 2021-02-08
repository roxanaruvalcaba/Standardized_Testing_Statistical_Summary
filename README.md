# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Testing, Statistical Summaries and Inference

### Overview

This was my first project in the Data Science immersive program and it covers:
- Basic statistics (distributions, confidence intervals, hypothesis testing)
- Many Python programming concepts
- Programmatically interacting with files and directories
- Visualizations
- EDA
- Working with Jupyter notebooks for development and reporting

For my first project, I took a look at aggregate SAT and ACT scores and participation rates from each state in the United States to identify trends in the data and combine data analysis with outside research to identify likely factors influencing participation rates and scores in various states.

### Problem Statement
The average participation rate for the SAT is lower than that of the ACT. How should the College Board invest resources to increase SAT participation rates?

### Executive Summary
The SAT/ACT data provided a few insights that were built on with external research. The data analysis shows that there is a strong negative correlation between participation and test scores. That means that the more students taking the test, the lower the average state score. The data also shows that many times there is one test that is more popular than other. This may be because, as the external research showed, students are more likely to only take one test. In addition some states have a mandate for students to take one test. These mandates changing led to a shift in participation in states such as Colorado. Regarding scores, Math scores appeared lower than Reading and Writing Scores in the SAT. However, the average SAT score did appear to increase from 2017 to 2018 whereas the ACT score did not.

As a member of the College Board, I recommend that resources are invested in Utah to increase SAT participation. Utah currently requires the ACT but not the SAT to be taken by all high school students, free of charge. The Utah state government is already open to using a standardized test for students. Our job will be to convince them that the SAT is a good alternative test to offer. Reasons for them to also offer the SAT include our improvements from the 2016 new format, diversifying their test suppliers, and providing students the chance to use the test that best reflects their strengths.

As we see participation go up, we will also want to invest in student preparation and test accessibility so that the test is seen as a fair measurement of student preparedness. If not, states and colleges may not believe using the SAT as a metric is fair and they'll decide on not using either. In addition, the better prepared students are for the SAT, the more likely they are to choose to take the SAT over the ACT.

### Conclusion
I selected Utah as the state to invest in to increase the participation rate that in 2018 was at 3%. The College Board can increase Utah's participation rate by working with the government to allow students to take either the SAT or the ACT. Research shows that students are more likely to take the test they are best prepared for. That is why I also recommend the College Board to invest in test prep (with a strong focus on math) and college prep for students as well as offering the date on weekdays since some students may work on weekends. Additional data that would better inform my investigation is income level per state.

### Content

- [PPT](./SAT_Investment_Opportunities.pdf)
- [Code](./code/Jupyter-Notebook-SAT-Investment-Analysis.ipynb)

#### Provided Data

For this project, we have five datasets:

- [2017 SAT Scores](./data/sat_2017.csv)
- [2017 ACT Scores](./data/act_2017.csv)
- [2018 SAT Scores](./data/sat_2018.csv)
- [2018 ACT Scores](./data/act_2018.csv)
- [2017 SAT & ACT Scores](./data/scores_2017.csv)

These data give average SAT and ACT scores by state, as well as participation rates, for the graduating class of 2017.
The 2017 SAT & ACT Scores file is a combination of the ACT and SAT data for 2017

#### Additional Data

The web was searched to find additional information on what caused changes in trends. For example, why the SAT participation in Colorado increased from 2017 to 2018 or why states with higher participation had lower scores.
