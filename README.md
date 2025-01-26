# Data Science Assignment 1: Statistical Analysis and Hypothesis Testing

This repository contains my work for **Data Science Assignment 1**, which focuses on statistical analysis and hypothesis testing. The assignment is divided into three main sections: **Monte Carlo Simulation**, **Central Limit Theorem (CLT)**, and **Hypothesis Testing**. Below is a detailed explanation of each section and the corresponding code in the Jupyter notebook.

## 1. Monte Carlo Simulation

### Pi Calculation
In this section, I implemented a Monte Carlo simulation to estimate the value of Pi. The simulation involves randomly generating points within a square and determining how many fall inside a circle inscribed within the square. By comparing the ratio of points inside the circle to the total number of points, I approximated the value of Pi. The simulation was repeated with different numbers of points to analyze the accuracy of the estimation.

### Mensch Game
I also analyzed a simplified version of the Mensch game, where each player has only one piece, and the game is purely based on chance. Using Monte Carlo simulation, I calculated the probability of winning for each of the four players. The simulation was run multiple times to ensure accurate probability estimates.

## 2. Central Limit Theorem (CLT)

In this section, I explored the Central Limit Theorem by selecting three different probability distributions (e.g., uniform, exponential, and normal) and generating random samples from each. For each distribution, I performed the following steps:

1. Generated a large number of random samples with a specific sample size.
2. Calculated the mean of each sample.
3. Plotted the histogram of the sample means and overlaid it with the expected normal distribution based on the CLT.
4. Repeated the process for increasing sample sizes to observe how the distribution of sample means changes.

The results demonstrated that as the sample size increases, the distribution of sample means approaches a normal distribution, aligning with the principles of the CLT.

## 3. Hypothesis Testing

### Unfair Coin
I simulated an unfair coin that is biased toward landing on one face more often than the other (approximately 10% more probable). Using both the confidence interval and p-value approaches, I performed hypothesis testing to determine whether the coin is fair. The tests were conducted with different sample sizes (30, 100, 1000), and the results were analyzed to understand the impact of sample size on hypothesis testing.

### T-Test
I performed a t-test to determine if there is a significant difference between the means of two groups. Specifically, I tested the common belief that working alongside studying has a negative impact on students' grades. The dataset provided information about students' job status and their grades. I split the students into two groups based on their job status, calculated the t-statistic and degrees of freedom, and determined the p-value using the t-distribution. The test was repeated using the SciPy library for comparison.

## Notebook Structure
The Jupyter notebook is organized as follows:
- **Pi Calculation**: Implementation of the Monte Carlo simulation for estimating Pi.
- **Mensch Game**: Simulation and probability calculation for the simplified Mensch game.
- **Central Limit Theorem**: Exploration of the CLT with three different distributions.
- **Unfair Coin**: Hypothesis testing for an unfair coin using confidence intervals and p-values.
- **T-Test**: Hypothesis testing to analyze the impact of job placement on students' grades.
