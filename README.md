# Employee Burnout Prediction Using Neural Networks

## Project Overview

This project uses R and neural network modeling to predict employee burnout using work-from-home behavioral data.

The goal was to determine whether employee behaviors such as workload, screen time, meetings, breaks, sleep, and task completion could be used to predict burnout intensity.

## Tools

- R
- Neural Networks
- Data Preprocessing
- Min-Max Scaling
- RMSE

## Dataset

The dataset contains 1,800 daily records of work-from-home employee behavior.

The explanatory variables used in the models include:

- Day Type
- Work Hours
- Screen Time Hours
- Meetings Count
- Breaks Taken
- After-Hours Work
- Sleep Hours
- Task Completion Rate

The response variable is Burnout Score.

## Methodology

The data was divided into 60% training data and 40% validation data.

Two neural network models were created:

 **Model 1:** One hidden layer with three nodes
 **Model 2:** Two hidden layers with two nodes each

The models were evaluated using Root Mean Squared Error (RMSE).

## Results

Both models produced an RMSE of **23.8253** on the validation data.

Because the more complex model did not improve predictive performance, the simpler Model 1 was selected.

## Key Takeaway

Increasing neural network complexity did not improve predictive performance for this dataset. The simpler neural network provided comparable results while requiring fewer training steps.

## Project File

- `Github 1.Rmd` — R Markdown analysis containing the data preprocessing, neural network modeling, and results.
