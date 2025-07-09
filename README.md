#BOP Index
# Predicting the 'Bop Index' for Songs on Spotify

## Introduction and Problem

Welcome to **Ctrl+Shift+Intelligence 2024**. This competition aims to predict the **'Bop Index'** of various songs on Spotify!

The **Bop Index** is a feature influenced by a number of factors, such as:
- The theme of the song
- Its commercial viability

Your objective is to **train a model** capable of accurately predicting the Bop Index using the provided training data.

> **Note:** Your Kaggle leaderboard score will **not** be the only factor determining your performance.  
> **Other factors such as**:
> - Code quality  
> - Novelty of your approach  
> - Exploratory data analysis  
> - Data preprocessing  
> will **also play a significant role** in final evaluation.

---

## Some General Guidelines

-  There will be a **public leaderboard** and a **private leaderboard**.
-  After the competition, **top performers will be asked to submit their code**. Final standings will be based on **code evaluation**.
-  Use of **any external dataset is not allowed**. You must only work with the **provided dataset**.
-  **Predictions must be made on the test data.**
-  **Only individual participation** is allowed.

---
##  Evaluation

The submissions are evaluated using **Mean Squared Error (MSE)**.  
MSE is a commonly used metric to evaluate the accuracy of a regression model.  
It measures the **average magnitude of the errors** between predicted values and the actual values.

The formula to calculate MSE is:

\[
\text{MSE} = \frac{1}{n} \sum_{i=1}^{n}(y_i - \hat{y}_i)^2
\]

🔗 [Learn more on Wikipedia](https://en.wikipedia.org/wiki/Mean_squared_error)

In simple terms, MSE is calculated as the **average of the squared differences** between predicted and actual target variable values.

