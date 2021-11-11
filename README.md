# Success of a Kickstarter Campaign: Feature Analysis

## Overview
In this project, we conducted data analysis to determine the relationship between funding goal, main category, and location of a Kickstarter campaign and its success. We wanted to determine what factors of a campaign relate to a higher chance of its success.

We found that campaigns with lower goal amounts (US$) had much a higher proportion of money pledged and therefore a higher success rate. Campaigns with high goal amounts had proportion pledged almost equal zero. On the other hand, we found no significant relationship between country and success rate or between main category and success rate.

## Research Question
- What is the relationship between funding goal, main category, and location of a Kickstarter campaign and its success?

## Background & Prior Work

- ***An Introduction to the platform*** : Kickstarter is an American public benefit corporation based in Brooklyn, New York, it maintains a global crowdfunding platform focused on creativity. The company's stated mission is to "help bring creative projects to life".As of December 2019, Kickstarter has received more than $4.6 billion in pledges from 17.2 million backers to fund 445,000 projects, such as films, music, stage shows, comics, journalism, video games, technology, publishing, and food-related projects.

- ***How it works***: Every project creator sets their project's funding goal and deadline. If people like the project, they can pledge money to make it happen. If the project succeeds in reaching its funding goal, all backers' credit cards are charged when time expires. Funding on Kickstarter is all-or-nothing. If the project falls short of its funding goal, no one is charged.

The main question that pops up is "What exactly makes a project that successful?" We believe that there is a possibility that successful projects do possess some common features. Thus, we plan to look into the data available from past Kickstarter projects - whether fails or successes - and see why the outcome was so.

While our preliminary dataset search involved Google, our main source of datasets were portals such as Kaggle that specialize in Data Science projects. We came across the "Kickstarter Projects" and the "Kickstarter Project Statistics" datasets that fulfilled our requirements. Links to both of these are available below.

Kickstarter Projects: There are two available files here from both December 2016 as well as January 2018. Each of these files are composed of around 300,000 to 400,000 unique projects.

Kickstarter Project Statistics: Once again, there are two files available. This time, one of them gives us 4000 projects that were live at that point in time, and the other covers 4000 of the most backed projects at the time.

Upon further inspection, we narrowed down to the "Kickstarter Projects" dataset as it was larger in size. We concur that it could likely lead to a more accurate analysis.

We decided to analyze the dataset of 2018, considered the number of projects and the recent year of the dataset.

*References*:

1) https://www.kickstarter.com/help/taxes (How it works)
2) https://en.wikipedia.org/wiki/Kickstarter (Introduction)
3) https://www.kaggle.com/socathie/kickstarter-project-statistics (Kickstarter Project Statistics Dataset)

## Hypothesis
We hypothesize that the main category, funding goal, and location of a Kickstarter campaign will determine the success of a campaign. We predict that a lower funding goal will lead to a higher chance of success and that campaigns located in western countries in the category of Technology will have a higher chance of success.


## Dataset(s)
- Dataset Name: ks-projects-201801.csv
- Link to the dataset: https://www.kaggle.com/kemical/kickstarter-projects
- Number of observations: 378660
Kickstarter Project Dataset "ks-projects-201801.csv" has 378660 observations and 16 features. This dataset contains data on a number of factors that contribute to the success or failure of the project. After, We analyzed 16 features and add new features such as ‘duration’ by computing the duration between launched date and the deadline and remove unnecessary columns.



