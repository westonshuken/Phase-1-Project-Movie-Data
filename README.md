# Phase-1-Project-Movie-Data

## Microsoft Movie Studio Business Analysis

**Authors**: [Madoria Thomas](https://github.com/madoriathomas), [Gregory Han](https://github.com/gregoryhhan), [Nathaniel Martin](https://github.com/UpGoerFive), [Weston Shuken](https://github.com/westonshuken)

## Overview

Microsoft wants to launch a new movie studio.

By analyzing historical data, we uncovered data-driven tips for ensuring a the company's production is high performing with an efficient return on investment. We suggest ideas for genres, runtime, and studio acquisitions.

## Business Problem

Microsoft does not know anything about creating movies, yet they want to create a new movie studio. 
We need to make sure that Microsoft is going to be profitiable from their movies as well as build a good brand reputation.


## Data Understanding

We are using movie datasets from 5 different sources:

* [IMDB]()
* [ROTTEN TOMATOES]()
* [TheMovieDB]()
* [Box Office Mojo]()
* [The Numbers]()

The data includes information on movie genres, titles, runtime, production expense, foreign & domestic box office gross, production studio name, and release dates.

With these datasets, we will search for insights in box office performence and user ratings compared to various factors like genre, personel, runtime, production budget and release time.

***
Questions to consider:
* Where did the data come from, and how do they relate to the data analysis questions?
* What do the data represent? Who is in the sample and what variables are included?
* What is the target variable?
* What are the properties of the variables you intend to use?
***

## Methods

We analyzed hundreds of thousands of data records across multiple sources to conduct descriptive statistics and visualizations.

However, much of the data was irrelevant to our needs:

* Dating back to 1915
* $0 Box Office Gross (likely due to streaming only releases)
* Extremely low budget films 
* Missing entries

We cleaned, merged, and built data frames thay would best suit our analysis for a modern movie studio, interested in movie theater releases, and with a budget sufficient budget for major film productions.


## Results

***
1) Suggested list of personel and publishers to work with.
2) Importance of foreign vs. domestic revenue sources.
3) Consider creating a vertically integrated studio to streaming service.
***
Questions to consider:
* How do you interpret the results?
* How confident are you that your results would generalize beyond the data you have?
=======
We will use descriptive analysis to discover trends in the data. We will also look at correlation and distributions to visualize
our findings.

Describe the process for analyzing or modeling the data. For Phase 1, this will be descriptive analysis.

*Questions to consider:
* How did you prepare, analyze or model the data?
* Why is this approach appropriate given the data and the business problem?
***
*

## Results

***
1) Suggested list of personel and publishers to work with.
2) Importance of foreign vs. domestic revenue sources.
3) Consider creating a vertically integrated studio to streaming service.
***

Here is an example of how to embed images from your sub-folder:

### Visual 1
![graph1](./images/viz1.png)

### Visual 2
![graph1](./images/viz1.png)

### Visual 3
![graph1](./images/viz1.png)

### Visual 3
![graph1](./images/viz1.png)



## Recommendations

*Keep the film runtime to around 1.5 hours.
*Best M&A option: Neon and Orchard Film Studios.
*Create films with a historically high ROI: horror, mystery & thriller.
*Avoid releasing horror movies in November & December.

## Next Steps

* Better Datasets
  * Net to Studio -> strengthen analysis
  * Other Expense Data -> Cap. Budgeting
  * Financial Performance -> M&A
* Outside the Box Office
  * $0 Box Office -> Direct to licensing	

Provide your conclusions about the work you've done, including any limitations or next steps.

***
Questions to consider:
* What would you recommend the business do as a result of this work?
* What are some reasons why your analysis might not fully solve the business problem?
* What else could you do in the future to improve this project?
***

## For More Information

Please review our full analysis in [our Jupyter Notebook](./dsc-phase1-project-template.ipynb) or our [presentation](./DS_Project_Presentation.pdf).

For any additional questions, please contact **Madoria Thomas, Gregory Han, Nathaniel Martin, and Weston Shuken — Collectively known as, 'The Four Forks'**

## Repository Structure

```
├── README.md                                         <- The top-level README for reviewers of this project
├── Microsoft Movie Studio Business Analysis.ipynb    <- Narrative documentation of analysis in Jupyter notebook
├── DS_Project_Presentation.pdf                       <- PDF version of project presentation
├── data                                              <- Both sourced externally and generated from code
└── images                                            <- Both sourced externally and generated from code
