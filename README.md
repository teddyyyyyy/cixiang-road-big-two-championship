# Cixiang Road Big Two Championship 🃏

*A friendly card game that turned into an exploratory statistical analysis.*

## Overview

Four players—Flower, Popo, Terry, and Teddy—competed in 20 rounds of Big Two under Taiwanese house rules.

We recorded the net scores from every round and investigated whether the observed differences provided evidence of long-term differences in player performance.

## Results

| Player | Total Score | Rounds Won |
|---|---:|---:|
| Terry | +14 | 4 |
| Teddy | +8 | 5 |
| Popo | −1 | 7 |
| Flower | −21 | 4 |

Terry won the championship, while Popo won the most individual rounds.

However, none of the six pairwise comparisons reached statistical significance after Holm correction.

## Statistical Methods

- Two-sided paired t-tests for six player comparisons
- Holm correction for multiple comparisons
- Normal Q–Q plots and Shapiro–Wilk tests for normality diagnostics
- Exact paired sign-flip tests as sensitivity analyses
- Exploratory sample-size estimation for future games

The analysis is exploratory. With only 20 rounds, considerable score variability, and departures from normality in some paired differences, the results do not establish a definitive ranking of long-term playing ability.

## Full Report

📄 [Read the full statistical report](https://teddyyyyyy.github.io/cixiang-road-big-two-championship/cixiang-road-big-two-championship.pdf)

## Conclusion

**Terry won the championship. Whether Terry is the strongest player in the long run remains an open question.**
