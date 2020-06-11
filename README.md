# Challenge Analysis Template
What this project is: A template project for post-challenge analysis with template R markdown files describing important common post-challenge analyses, and a general explanation of how they are done.

What this project isn't: A codebase for running analyses.

## Template structure

`/analysis`: Contains all code notebooks and rendered `html` notebooks.
`/data`: Small data files can be stored here if need be, but storing the data on the Synapse project for the challenge is recommended and preferred. 

## The Template Challenge
You should insert the name and description of your Challenge here, with a link to the Challenge project. 

## Post-challenge analyses

This table captures all of the post challenge analysis and allows anyone visiting the repo to easily find the analyses. If you are using R or JuPyteR notebooks, you should knit them to html and push them to Github so that they can be displayed on github.io. In order to set this up, you should enable Github Pages in the Settings for your project, and configure it to use the `gh-pages` branch as source. Once you've done this, any `html` files in the `gh-pages` branch will be rendered on github.io. 

|analysis|description|
|--|--|
|[Determining top performers](https://sage-bionetworks-challenges.github.io/challenge-analysis/analysis/determine-top-performers.html)|A simple description of a bootstrap analysis to determine the top performers in a challenge.|
|[Comparison to baseline/comparator model](https://sage-bionetworks-challenges.github.io/challenge-analysis/analysis/compare-models-to-baseline.html)|A simple description of a bootstrap analysis to determine the performance of participants relative to a comparator model.|
|[Survey analysis](https://sage-bionetworks-challenges.github.io/challenge-analysis/analysis/survey-analysis.html)|A simple description of a post-challenge survey analysis.|
|[Ensemble analysis](https://sage-bionetworks-challenges.github.io/challenge-analysis/analysis/ensemble-analysis.html)|A simple description of an ensemble analysis for a challenge.|
