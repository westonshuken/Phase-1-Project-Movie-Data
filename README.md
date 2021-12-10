# Phase-1-Project-Movie-Data
![banner](./images/microsoft-banner.jpg)
# Microsoft Movie Studio Business Analysis

**Authors**: [Madoria Thomas](https://github.com/madoriathomas), [Gregory Han](https://github.com/gregoryhhan), [Nathaniel Martin](https://github.com/UpGoerFive), [Weston Shuken](https://github.com/westonshuken)

## Overview

Microsoft wants to launch a new movie studio.

By analyzing historical data, we uncovered data-driven tips for ensuring a the company's production is high performing with an efficient return on investment. We suggest ideas for genres, runtime, and studio acquisitions.

## Business Problem

Microsoft does not know anything about creating movies, yet they want to create a new movie studio. 

There are many unknown factors associated with how to make a profit.

* *How long should the films be?*
* *What genre should Microsoft produce?*
* *Should Microsoft start from scratch or acquire a studio?*

Using the data provided and additional resources, we devised a plan to answer these questions about how best Microsoft can break into the movie studio market and ensure profitability.

## Data Understanding

We are using movie datasets from 5 different sources:

* [IMDB]()
* [ROTTEN TOMATOES]()
* [TheMovieDB]()
* [Box Office Mojo]()
* [The Numbers]()

The data includes information on movie genres, titles, runtime, production expense, foreign & domestic box office gross, production studio name, and release dates.

With these datasets, we will search for insights in box office performence and user ratings compared to various factors like genre, personel, runtime, production budget and release time.

## Methods

We analyzed hundreds of thousands of data records across multiple sources to conduct descriptive statistics and visualizations.

However, much of the data was irrelevant to our needs:

* Dating back to 1915
* $0 Box Office Gross (likely due to streaming only releases)
* Extremely low budget films 
* Missing entries

We cleaned, merged, and built data frames thay would best suit our analysis for a modern movie studio, interested in movie theater releases, and with a budget sufficient budget for major film productions.

## Analysis and Visualisations
We used descriptive analysis to discover trends in the data. We also looked at trends, frequencies and distributions to visualize our findings.

### Runtime Frequency 
![graph1](./images/runtime_distribution_ROI50.png)

### Top Studios by Profit Margin
![graph1](./images/topstudios_profitmargin.png)

### Frequency of Releases by Genre
![graph1](./images/movie_freq_genre.png)

### Mean ROI by Genre
![graph1](./images/mean_ROI_genre.png)

### Median ROI by Genre
![graph1](./images/median_ROI_genre.png)


## Recommendations

This analysis leads to three recommendations for Microsoft when creating a movie studio:

1. **Don't make cliffhangers or movies too long.** Runtime for movies should be made between 90-120 minutes; movies with ROI above 50% were made in this range.
2. **Acquire Neon or Orchard Film Studios.** Both Neon and Orchard are ranked highly in profits for both domestic and worldwide markets. Acquiring either one of these two would allow Microsoft to make movies that are competitive in the box office.
3. **Create horror, mystery, or thriller movies.** Adding these genres as part of the production portfolio would garner Microsoft a higher return on investment.


## Next Steps

Further analyses could provide additional insights to having a more successful movie studio for Microsoft:

* **Net Profit to Studio Data.** As of now we are seeing the net profit of the film at box office but not what profits are returning directly to the studios involved. Having the net profit by film to studio would increase the strength of our analysis of when to release movies.
* **Other expense data.** Further inspection to types of expense could also help for your capital budgeting. E.g. marketing expense, distribution expense, etc.
* **Competitors' financial performance.** Deeper understanding of competitive landscape — to have organized data on competitors financial performance would help strengthen our M&A recommendations. E.g. historical market cap data
* **Straight to streaming and licensing.** Although the box office is important for new films, much the data had $0 box office gross which led us to believe some films sell straight to streaming licensing. Exploring data related to streaming and licensing would also provide a realistic prediction of how a film could be exploited.


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
