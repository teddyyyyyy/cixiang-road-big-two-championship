# 🃏 Cixiang Road Big Two Championship

### A Friendly Card Game, an Unnecessary Statistical Investigation

What started as an argument between two friends about who was better at cards eventually turned into a 20-round Big Two championship—and a nine-page statistical research report.

Big Two is a four-player card game where players compete to get rid of all their cards. Under our house rules, the winner earns the points lost by the other three players, including applicable penalties.

The question was simple: **Does winning a 20-round championship mean you're actually the strongest player?**

## 🏆 Final Standings

| Rank | Player | Rounds Won | Total Score |
|---|---|---:|---:|
| 1 | Terry | 4 | +14 |
| 2 | Teddy | 5 | +8 |
| 3 | Popo | 7 | −1 |
| 4 | Flower | 4 | −21 |

Interestingly, Popo won the most rounds but finished third in total points.

## 📊 Statistical Analysis

We treated the 20 rounds as paired observations and performed:

- Six pairwise paired t-tests
- Holm correction for multiple comparisons
- Exact paired sign-flip sensitivity tests
- Confidence interval estimation
- Sample-size planning for future games

**Main finding:** None of the six player comparisons was statistically significant after Holm correction.

This does not prove that the players are equally skilled. It means the available data are insufficient to establish a long-term mean-score advantage.

## 📄 Full Research Report

[**Read the complete nine-page statistical report (PDF)**](cixiang-road-big-two-championship.pdf)

The report includes the complete house rules, all 20 rounds of recorded scores, statistical methods, results, limitations, and sample-size calculations.

## 🔬 What's Next?

Our preliminary sample-size calculations suggest that approximately **400–1,100 rounds** may be required to detect a true mean difference of three points per round with 80% power for an individual player comparison, under the stated assumptions.

We plan to continue playing and collecting data more systematically, using the current 20 rounds as pilot data.

Apparently, settling a friendly card game argument may require a thousand more games.

---

*An independent personal side project exploring statistical inference, experimental design, and uncertainty—with a little help from playing cards.*
