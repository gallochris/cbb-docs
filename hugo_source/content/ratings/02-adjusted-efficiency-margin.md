---
title: Adjusted Efficiency Margin
slug: adjusted-efficiency-margin
type: "post"
weight: 2
---

Adjusted Efficiency Margin, or AdjEM, is the difference between a team’s offensive and defensive efficiency.

`AdjEM = AdjOE - AdjDE`

AdjEM is used to rate teams. It was introduced by [KenPom](http://kenpom.com/) prior to the 2016-2017 season, and it's detailed in [this blog post](http://kenpom.com/blog/ratings-methodology-update/). Prior to this metric, ratings were built on log5 and the Pythagorean expectation.

### What does this mean?

The adjusted efficiency margin shows the number of points a team would be expected to outscore the average Division-I team over 100 possessions without adjusting for location of the game.

For example, in the 2017-2018 season, if Villanova played the average Division-I team on a neutral court, on average, Villanova would win a 100-possession game by about 34 points.

Villanova's AdjOE is 127.8 and AdjDE is 94.0.

`AdjEM = 127.8 - 94.0 = 33.8`

#### Why use AdjEM and not log5 and the Pythagorean expectation?

AdjEM is used because it's simpler and it's a linear measure. [Kenpom](http://kenpom.com/) explains in this [blog post](http://kenpom.com/blog/ratings-methodology-update/).

The Pythagorean expectation, from the mind of [Bill James](https://en.wikipedia.org/wiki/Pythagorean_expectation), originated from baseball. It estimates how many games a team should have won based on the amount of runs it scored or allowed.

It applied to college basketball by giving you a team's expected winning percentage against the average Division-I team.

`Pyth = (AdjOE^11.5) / (AdjOE^11.5 + AdjDE^11.5)`

It's clear the Pythagorean expectation is complicated. AdjEM is subtraction. That's it. A team's offensive efficiency minus its defensive efficiency.

The difference when comparing teams using AdjEM versus log5 or the Pythagorean expectation is important too. The Pythagorean expectation for one team could be .96 and for another could be .93. The difference of .3 there is not the same as comparing teams with a .70 and .67 expected winning percentage because of the team's strength. It's murky.

[KenPom](http://kenpom.com/) describes AdjEM as a linear measure giving the example of a team with a +31 AdjEM and a team with a +28 AdjEM the same as the difference between +4 and +1.

It's more clear.

