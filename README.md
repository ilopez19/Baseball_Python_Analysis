# Let’s Talk About Baseball: Age vs. Performance


## Project Summary

This project explores the relationship between **age and player performance in Major League Baseball** using a cleaned and curated version of a public MLB dataset. We focused on batting, pitching, and salary stats to evaluate how performance changes as players age.

## Goal

**Does age significantly impact a player’s performance, and what model best captures that trend?**

## Tools & Methods

- Data cleaning in **R**, modeling in **PySpark**
- Used a **70/30 train-test split**
- Ran **linear regression models** on:
  - **Batting stats:** HRs, RBIs, Hits  
  - **Pitching stats:** ERA, Wins/Losses, Strikeouts  
  - **Salary data:** Height, Weight, Salary

## Key Findings

- Performance typically **peaks between ages 27–32**
- Salary data shows irregular spikes, often near retirement
- **Linear models had low predictive accuracy** (low R², high RMSE)
- Data suggests a **non-linear (bell-curve) pattern** may model age-performance better

## Conclusion

Age alone isn't a strong linear predictor of performance, but analyzing it with other variables can yield deeper insights. Future work should explore **non-linear models** to better reflect real-world performance trends in baseball.