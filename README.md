![Microsoft Header Logo](https://blogs.microsoft.com/wp-content/uploads/prod/2012/08/8867.Microsoft_5F00_Logo_2D00_for_2D00_screen-1920x500.jpg)
# Microsoft Movie Industry Analysis -- Data Science Module 1, Flatiron School

Author: Blake McMeekin

## Overview

This is the Q1 project for Flatiron School, with the objective of creating a professional-level analysis and presentation. Three databases were selected, integrated, cleaned, and processed with python and SQL, with a number of graphs and findings presented in a slideshow. Some of the findings were that science fiction is the most profitable genre of film, Shakespeare is in the bottom 5 profitable hollywood writers, and the bulk of the money made in hollywood comes from blockbuster high-budget productions.

## Business Problem

The scenario here is that Microsoft is wanting to enter the streaming and film industry - how can media databases help with this decisionmaking? Determining the goal for the analysis was a back-and-forth between exploratory data analysis and the larger business context. Movie rating, gross, and profitability were analyzed for correlation and ultimately profitability was decided on as a main data-point characterizing film and business success. A correlation matrix was made to analyze how other fields related to film profitability and more significant correlations were analyzed further.

## Data

The data in this project consisted of three pubically available databases, one from "IMDB", one from "The Numbers", and one from "The Movie Database", together characterizing more than 100000 films. Financial information was more limited, with about 5000 films having financial data. Over 70000 average film reviews were considered from IMDB. More than 100000 writers/directors were considered.

## Methods

This process uses descriptive analysis looking at trends over time and correlations between different factors. These measures look to assist higher-level decisionmaking and steer film production.

## Results

The industry is carried by the runaway successes.
![Profitability histogram](https://github.com/thegrandblooms/dsc-phase-1-project-v2-4/blob/08ccc9a3df17f74b65fedff25574d007a195bf0f/graphics/profitability%20histogram.png)

Science fiction is the most profitable genre, followed by Adventure and Animation
![Science Fiction Histogram](https://github.com/thegrandblooms/dsc-phase-1-project-v2-4/blob/d0e0c14e8b25b8817b090e0819463aef356e1485/graphics/Average%20profit%20by%20genre.png)

Films are not getting more profitable over time, Rating is not a perfect correlation with profitability
![Scatter plot of movies and profitability over time, colored by Rating](https://github.com/thegrandblooms/dsc-phase-1-project-v2-4/blob/08ccc9a3df17f74b65fedff25574d007a195bf0f/graphics/Profit%20Across%20Time%20Scatter%20Plot.png)

Genre fluctuates in profitably from year to year
![Genres and Profitability over Time](https://github.com/thegrandblooms/dsc-phase-1-project-v2-4/blob/08ccc9a3df17f74b65fedff25574d007a195bf0f/graphics/Genre%20by%20Year.png)

## Conclusions

The biggest business recommendations are:
- Making big-budget, blockbuster films is way more profitable than smaller, arthouse style films.
- Quality writers and directors, a well-funded production, and best-selling genres are the data-supported ways to ensure profitability.
- Making a critically acclaimed movie and making a profitable movie are about 30% correlated. Optimize for profitability in order to be profitable, but know that rating still matters and likely impacts branding.

## Next Steps

- Future analysis could collect more data on production companies and collaboration networks between actors and directors as predictors of profitability. 
- Larger financial datasets could be incorporated into the analysis for more accurate numbers. 
- More information on smaller-budget films and persons could help steer early investment.

## For more information

See the full analysis in the Jupyter Notebook or review the presentation here.

For additional information, contact Blake McMeekin at blakemcme@gmail.com

## Repository Structure

```
├── data
│   ├── im.db
│   ├── tmdb.movies.csv
│   └── tn.movie_budgets.csv
├── graphics
├── Presentation.pdf
├── README.md
└── Data Analysis Notebook.ipynb
```
