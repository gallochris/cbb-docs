---
title: Luck
slug: luck
type: "post"
weight: 3
---

Luck doesn't factor into a team's rating. It's a metric that compares a team's record to what they deserved based on their game-by-game efficiency.

If a team is involved in a lot of close games, it shouldn't win or lose all of them. If a team wins all of the close games, they're viewed as a lucky. An unlucky team would lose all of their close games.

Luck is measured using [Dean Oliver's correlated Gaussian method](http://www.rawbw.com/~deano/helpscrn/corrgauss.html).

If this sounds complicated, it definitely is.

Oliver explains it as something similar to a [bell curve](http://www.rawbw.com/~deano/articles/BellCurve.html).

`Luck = NORM (AdjOE - AdjDE) / SD(Rating Difference)`

```text
                                             
            |           (Rtg-Opp.Rtg)           |
Win% = NORM |-----------------------------------|
            |       SD(Rating Difference)       |
```

The components:

* Rtg: points scored per 100 possessions \(offensive rating\)
* Opp.Rtg: points allowed per 100 possessions \(defensive rating\)
* SD\(\): statistical standard deviation of quantity in parentheses \(\)
* Var\(\): statistical variance of quantity in parentheses \(\)
* Cov\(\): statistical covariance of quantities in parentheses \(\)

### What does that mean?

Luck tells you the difference between a team's expected winning percentage and its actual winning percentage.

Luck **doesn't** use Pythagorean Winning Percentage \(Pyth\) as the expected winning percentage. Pyth is calculated by a team's offensive and defensive efficiencies.

The correlated Gaussian method uses the distribution of a team's game efficiencies to determine the expected winning percentage. It includes both the **average margin of victory** and the **variation in a team's margin of victory**.

This method takes into account that the majority or teams play to the level of their competition.

### Examples

In the 2018-2019 season, UNC Greensboro was viewed as the luckiest team in Division-I.

UMBC was 29-7. Its actual winning percentage was 0.8056.

Using the correlated Gaussian method, UNC Greensboro's expected winning percentage was 0.64.

UNC Greensboro's actual winning percentage was 0.143 points higher than its expected. This translates into roughly 5 wins that were attributed to luck.

If you take a glance at UNC Greensboro's results, the Spartans won 7 games by 5 points or less, which can be viewed as _lucky_.

In comparison, the 2018-2019 Clemson squad team finished 20-14. The Tigers ranked 320th out of 353 teams in luck.

Clemson's actual winning percentage was 0.5882.

It's expected winning percentage using Oliver's method was 0.65.

This is -0.066 points lower than expected. This means about 2 losses were attributed to luck.

Taking a look at Clemson's game-by-game results, you'll find 6 losses by a 2 points or less. This can be seen as _unlucky_.

#### Remember luck doesn't factor into ratings

Luck isn't used when rating a team. It gives you an idea on how a team performs in close game and how it plays to its competition.

A lucky team will likely be rated lower by [KenPom](http://kenpom.com/).

Where an unlucky team could be rated higher.
