# Red-Wine-Case-Study.ipynb
Predicting alcohol content in red wines using linear regression based on chemical properties.

## Overview
For this project, I worked with a dataset of red wines to figure out what makes some wines more alcoholic than others. I used linear regression to try and predict the alcohol content based on different chemical features in the wine, like density and sulphates.

## Goal
The main goal was to build a model that could predict alcohol content and help understand which features have the strongest impact. I also wanted to get more practice with data exploration, regression modeling, and interpreting the results.

## What I Did
- Cleaned and explored the red wine dataset
- Looked at correlations between alcohol and other features
- Picked the most relevant features and trained a linear regression model
- Evaluated the model using R² and RMSE to see how accurate it was

## Results
- **R² Score:** 0.425 → So the model explains around 42.5% of the variation in alcohol levels
- **RMSE:** 0.85 → On average, the predictions are off by about 0.85% alcohol
- One of the biggest takeaways was that **density** had a strong negative relationship with alcohol, which makes sense since alcohol is less dense than water.

## Final Thoughts
This was a great intro to working with linear regression. The model wasn’t perfect, but it gave me useful insights and helped me understand how small chemical differences can affect alcohol content. I'd be curious to try other modeling techniques or include more features next time to improve the results.

