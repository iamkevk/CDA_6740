# Behavioral Analysis of Highly Involved Online Poker Players Using Machine Learning

This exploratory project overview is a class group project for `Team 5` in Georgia Tech's ISYE 6740 Computational Data Analysis / Machine Learning I, a graduate elective course offered as part of the [Online Master of Science in Analytics - OMSA](https://pe.gatech.edu/degrees/analytics). The ISYE 6740 class, taught by Prof. Yao Xie in Fall 2023, **is designed to give graduate students a thorough grounding in the methods, theory, mathematics, and algorithms needed to do research and applications in machine learning. The course covers topics from machine learning, classical statistics, and data mining**.

Disclaimer: The views and opinions expressed in this project are those of the authors and do not necessarily reflect the views or positions of Georgia Tech.

## Problem Statement

Technology advancement and regulation changes have led to a growth boom in the online gambling and betting industry with an estimated size amounting to 61.5 billion U.S dollars in 2021 according to statista.com [^1]. Based on estimates, the global online gambling and betting industry is forecast to rise to 114.4 billion U.S. dollars by 2028, representing an increase of over 86 percent.

Compared to other online casino games such as Slot, online Poker contributes to a smaller revenue share with worldwide revenues of 4.1 billion U.S dollars in 2022 or about 14 percent of 29.2 billion dollars of online casino revenues.[^2] These significant projections in revenue growth warrant a better understanding of the behavior of online poker players and potential societal risks.

## Project Overview

Gambling involves risk-taking and potentially can lead to problematic behaviors such as addiction. Our team was interested in applying various machine-learning methods to a publicly available dataset [^3] of online poker activity to examine and model the behavioral patterns of online poker players. 

Among these players, a subset can be categorized as "Highly Involved Players" (HIPs) – individuals who engage in online poker with higher financial involvement, higher intensity, frequency, and duration than the average player. While there are benefits associated with being a dedicated player, such as skill improvement and potential monetary gains, there are also concerns related to addiction, financial distress, and other negative socio-psychological implications.

## Methodology

The methodology for analyzing Highly Involved Players (HIPs) in gaming is a comprehensive multi-step process and allows us to leverage various machine learning techniques. Figure 1 is a summarization of the methodology used.

![Figure 1: Methodology Flowchart](https://github.com/iamkevk/CDA_6740/assets/66114561/37958736-d18b-4362-979e-46ee6109edd1)*Figure 1: Methodology Flowchart*

## Key findings

### Exploratory Data Analysis (EDA) 

> Modified from [^4]

- **Demographic**: The final sample analyzed contained 2245 males (89.9%) and 252 females (10.15). The average age was 29.58 years, with a standard deviation of 8.99 years. The median age was 27, and 75% were under 35 years old. The oldest player was 69. Geographically, the top three countries of player residence were France (27.75%), Germany (26.51%), and Belgium (5.93%).
- **Poker Activity**: See Table 1, a Summary of Statistics of Poker Activity Measures for the entire analytic sample (N = 2497).

![Table 1: Summary Statistics of Poker Activity Measures for the entire analytic sample (N = 2497)](https://github.com/iamkevk/CDA_6740/assets/66114561/7093a9f2-76ac-4aba-a161-3af3e166e6a5)*Table 1: Summary Statistics of Poker Activity Measures for the entire analytic sample (N = 2497)*

***Note***: Negative loss means gains 

- **Financial Activity**: Players deposit an average of €1,144.80, but with a very high standard deviation (€4,370.28), indicating some users deposit significantly more than others. The highest amount deposited by a single user is €112,337.90. The average amount deposited per day a user makes a deposit is €62.40, but this varies widely (std. dev. €158.82). The highest average amount deposited per day is €3,114.82.

- **Highly Involved Players**: We identified the most engaged players using their total overall spend and total stakes in cash and tournament games. See Figure 2 and Table 2 for a percentile plot of total overall spending details.

![Figure 2: Percentile Plot of Total overall spend](https://github.com/iamkevk/CDA_6740/assets/66114561/fdf217ba-7591-45bc-99f2-639596087ada)*Figure 2: Percentile Plot of Total overall spend*

![Table 2](https://github.com/iamkevk/CDA_6740/assets/66114561/42fa0716-929b-49b2-b848-10bf7c3863fe)**






## References

[^1]: [Market size of the online gambling industry worldwide in 2022, with a forecast for 2032](https://www.statista.com/statistics/270728/market-volume-of-online-gaming-worldwide/)
[^2]: [Online Gambling Market Size, Share & Trends Analysis Report](https://www.grandviewresearch.com/industry-analysis/online-gambling-market)
[^3]: [Second Session at the Virtual Poker Table](http://thetransparencyproject.org/Availabledataset.htm)
[^4]: [Second Session at the Virtual Poker Table: A Contemporary Study of Actual Online Poker Activity)](https://link.springer.com/article/10.1007/s10899-022-10147-1)


