# ![](https://ga-dash.s3.amazonaws.com/production/assets/logo-9f88ae6c9c3871690e33280fcf557f33.png) Project 1: Standardized Testing, Statistical Summaries and Inference

### Overview

Our first module in DSI covers:
- basic statistics (distributions, confidence intervals, hypothesis testing)
- many Python programming concepts
- programmatically interacting with files and directories
- visualizations
- EDA
- working with Jupyter notebooks for development and reporting


For our first project, we're going to take a look at aggregate SAT and ACT scores and participation rates from each state in the United States. We'll seek to identify trends in the data and combine our data analysis with outside research to identify likely factors influencing participation rates and scores in various states.


> The new format for the SAT was released in March 2016. As an employee of the College Board - the organization that administers the SAT - you are a part of a team that tracks statewide participation and recommends where money is best spent to improve SAT participation rates. Your presentation and report should be geared toward **non-technical** executives with the College Board and you will use the provided data and outside research to make recommendations about how the College Board might work to increase the participation rate in a **state of your choice**.

---

### Problem Statement
The average participation rate for the SAT is lower than that of the ACT. How should the College Board invest resources to increase SAT participation rates?


### Executive Summary
The SAT/ACT data provided a few insights that were built on with external research. The data analysis shows that there is a strong negative correlation between participation and test scores. That means that the more students taking the test, the lower the average state score. The data also shows that many times there is one test that is more popular than other. This may be because, as the external research showed, students are more likely to only take one test. In addition some states have a mandate for students to take one test. These mandates changing led to a shift in participation in states such as Colorado. Regarding scores, Math scores appeared lower than Reading and Writing Scores in the SAT. However, the average SAT score did appear to increase from 2017 to 2018 whereas the ACT score did not.

As a member of the College Board, I recommend that resources are invested in Utah to increase SAT participation. Utah currently requires the ACT but not the SAT to be taken by all high school students, free of charge. The Utah state government is already open to using a standardized test for students. Our job will be to convince them that the SAT is a good alternative test to offer. Reasons for them to also offer the SAT include our improvements from the 2016 new format, diversifying their test suppliers, and providing students the chance to use the test that best reflects their strengths.

As we see participation go up, we will also want to invest in student preparation and test accessibility so that the test is seen as a fair measurement of student preparedness. If not, states and colleges may not believe using the SAT as a metric is fair and they'll decide on not using either. In addition, the better prepared students are for the SAT, the more likely they are to choose to take the SAT over the ACT.

### Conclusion
I selected Utah as the state to invest in to increase the participation rate that in 2018 was at 3%. The College Board can increase Utah's participation rate by working with the government to allow students to take either the SAT or the ACT. Research shows that students are more likely to take the test they are best prepared for. That is why I also recommend the College Board to invest in test prep (with a strong focus on math) and college prep for students as well as offering the date on weekdays since some students may work on weekends. Additional data that would better inform my investigation is income level per state.

### Datasets

#### Provided Data

For this project, we have five datasets:

- [2017 SAT Scores](./data/sat_2017.csv)
- [2017 ACT Scores](./data/act_2017.csv)
- [2018 SAT Scores](./data/sat_2018.csv)
- [2018 ACT Scores](./data/act_2018.csv)
- [2017 SAT & ACT Scores](./data/scores_2017.csv)

These data give average SAT and ACT scores by state, as well as participation rates, for the graduating class of 2017.
The 2017 SAT & ACT Scores file is a combination of the ACT and SAT data for 2017

You can see the source for the SAT data [here](https://blog.collegevine.com/here-are-the-average-sat-scores-by-state/), and the source for the ACT data [here](https://blog.prepscholar.com/act-scores-by-state-averages-highs-and-lows). **Make sure you cross-reference your data with your data sources to eliminate any data collection or data entry issues.**

#### Additional Data

The web was searched to find additional information on what caused changes in trends. For example, why the SAT participation in Colorado increased from 2017 to 2018 or why states with higher participation had lower scores.

(_This data is for your reference only. It is not needed to complete the project. You are required to include all of the above csv data._)

2018 state-by-state average results and participation for the SAT are available in PDF reports [here](https://reports.collegeboard.org/sat-suite-program-results/state-results). 2018 ACT state-by-state mean composite scores and participation rates are [here](http://www.act.org/content/dam/act/unsecured/documents/cccr2018/Average-Scores-by-State.pdf) .

**This data has been compiled into CSV files which are also included in the *data* directory of this repo**

---

### Deliverables

The deliverables include:
- This README markdown file called "README.md" provides an introduction to and overview of your project.
- A Jupyter notebook called "Jupyter-Notebook-SAT-Investment-Analysis" that describes ACT/SAT data with visualizations & statistical analysis (located in the "code" folder). This file includes the steps to clean the data, merging data frames, finding interesting stats, sorting tables, plotting, external research, and more.
- A presentation slideshow called "SAT Investment Opportunities" rendered as a .pdf file summarizing the recommendation to be presented to the board.




---

### Technical Report Starter Code

Future projects will require you to decide on the entire structure of your technical report. Here, we provide you with [starter code](./code/starter-code.ipynb) in a Jupyter notebook that will help to guide your data exploration and analysis. **If you choose to edit the core structure of this notebook, make sure you don't exclude any of the requested operations**.

---

### Style Guide and Suggested Resources

[Tim Dwyer](https://www.linkedin.com/in/jtimdwyer/) (former DSI student and TA) put together [this style guide](https://git.generalassemb.ly/DSI-US-10/style_guide). Some recommendations are geared toward future projects (which will include modeling and span multiple notebooks), but generally these are great recommendations.

Here's a link on [how to give a good lightning talk](https://www.semrush.com/blog/16-ways-to-prepare-for-a-lightning-talk/), which provides some good recommendations for short presentations.

[Here's a great summary](https://towardsdatascience.com/storytelling-with-data-a-data-visualization-guide-for-business-professionals-97d50512b407) of the main points of the book _Storytelling with Data_, which I can't recommend enough. [Here's a blog post](http://www.storytellingwithdata.com/blog/2017/8/9/my-guiding-principles) by the author about his guiding principles for visualizations.

---

### Submission

**Materials must be submitted by the beginning of class on December 20.**

Your technical report will be hosted on Github Enterprise. Make sure it includes:

- A README.md (that isn't this file)
- Jupyter notebook(s) with your analysis (renamed to describe your project)
- Data files
- Presentation slides
- Any other necessary files (images, etc.)

**Check with your local instructor for how they would like you to submit your repo for review.**

---

### Presentation Structure

- **Must be within time limit established by local instructor.**
- Use Google Slides or some other visual aid (Keynote, Powerpoint, etc).
- Consider the audience. Assume you are presenting to non-technical executives with the College Board (the organization that administers the SATs).
- Start with the **data science problem**.
- Use visuals that are appropriately scaled and interpretable.
- Talk about your procedure/methodology (high level, **CODE IS ALWAYS INAPPROPRIATE FOR A NON-TECHNICAL AUDIENCE**).
- Talk about your primary findings.
- Make sure you provide **clear recommendations** that follow logically from your analyses and narrative and answer your data science problem.

Be sure to rehearse and time your presentation before class.

---

### Rubric
Your local instructor will evaluate your project (for the most part) using the following criteria.  You should make sure that you consider and/or follow most if not all of the considerations/recommendations outlined below **while** working through your project.

**Scores will be out of 21 points based on the 7 items in the rubric.** <br>
*3 points per section*<br>

| Score | Interpretation |
| --- | --- |
| **0** | *Project fails to meet the minimum requirements for this item.* |
| **1** | *Project meets the minimum requirements for this item, but falls significantly short of portfolio-ready expectations.* |
| **2** | *Project exceeds the minimum requirements for this item, but falls short of portfolio-ready expectations.* |
| **3** | *Project meets or exceeds portfolio-ready expectations; demonstrates a thorough understanding of every outlined consideration.* |
    
**Project Organization**
- Are modules imported correctly (using appropriate aliases)?
- Are data imported/saved using relative paths?
- Does the README provide a good executive summary of the project?
- Is markdown formatting used appropriately to structure notebooks?
- Are there an appropriate amount of comments to support the code?
- Are files & directories organized correctly?
- Are there unnecessary files included?
- Do files and directories have well-structured, appropriate, consistent names?

**Clarity of Message**
- Is the problem statement clearly presented?
- Does a strong narrative run through the project?
- Does the student provide appropriate context to connect individual steps back to the overall project?
- Is it clear how the final recommendations were reached?
- Are the conclusions/recommendations clearly stated?

**Python Syntax and Control Flow**
- Is care taken to write human readable code?
- Is the code syntactically correct (no runtime errors)?
- Does the code generate desired results (logically correct)?
- Does the code follows general best practices and style guidelines?
- Are Pandas functions used appropriately?
- Does the student demonstrate mastery masking in Pandas?
- Does the student demonstrate mastery sorting in Pandas?

**Data Cleaning and EDA**
- Does the student fix data entry issues?
- Are data appropriately labeled?
- Are data appropriately typed?
- Are datasets combined correctly?
- Are appropriate summary statistics provided?
- Are steps taken during data cleaning and EDA framed appropriately?

**Visualizations**
- Are the requested visualizations provided?
- Do plots accurately demonstrate valid relationships?
- Are plots labeled properly?
- Plots interpreted appropriately?
- Are plots formatted and scaled appropriately for inclusion in a notebook-based technical report?

**Research and Conceptual Understanding**
- Were useful insights gathered from outside sources?
- Are sources clearly identified?
- Does the student provide appropriate interpretation with regards to descriptive and inferential statistics? 

**Presentation**
- Is the problem statement clearly presented?
- Does a strong narrative run through the presentation building toward a final conclusion?
- Are the conclusions/recommendations clearly stated?
- Is the level of technicality appropriate for the intended audience?
- Is the student substantially over or under time?
- Does the student appropriately pace their presentation?
- Does the student deliver their message with clarity and volume?
- Are appropriate visualizations generated for the intended audience?
- Are visualizations necessary and useful for supporting conclusions/explaining findings?

In order to pass the project, students must earn a minimum score of 1 for each category. 
- Earning below a 1 in one or more of the above categories would result in a failing project.
- While a minimum of 1 in each category is the required threshold for graduation, students should aim to earn at least an average of 1.5 across each category. An average score below 1.5, while it may be passing, means students may want to solicit specific feedback in order to significantly improve the project before showcasing it as part of a portfolio or the job search.

### REMEMBER:

This is a learning environment and you are encouraged to try new things, even if they don't work out as well as you planned! While this rubric outlines what we look for in a _good_ project, it is up to you to go above and beyond to create a _great_ project. **Learn from your failures and you'll be prepared to succeed in the workforce**.
