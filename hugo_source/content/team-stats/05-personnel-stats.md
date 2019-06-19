---
title: Personnel Stats
slug: personnel-stats
type: "post"
weight: 5
---

A team's personnel can be measured across 5 different categories:

1. **Height**: total height of a team weighted by minutes played
2. **Bench Minutes**: the number of minutes a team's bench plays
3. **Continuity**: minutes played season-to-season
4. **Experience**: year in school weighted by minutes played
5. **Defensive Fingerprint**: identifies the style of a team's defense
6. **2-Foul Participation**: percentage of time a starter with 2 fouls plays in the first half 

Assumptions are made for each of these components, and detailed explanations are below.

### Height

[KenPom](http://kenpom.com/) calls height is the [most talked about physical trait](http://www.basketballprospectus.com/article.php?articleid=82) in basketball. You can't teach it, right?

It does have a slight correlation to a team's offensive and defensive efficiency. And it makes sense, a taller team might defend well and score at ease in the paint versus a shorter team. But it's not the _only metric_ that matters.

**Average Height**

This is measured by gathering the average listed height of every player on a team, weighted by the minutes played.

It _excludes players that play less than 10% of their team's minutes_.

Syracuse led the country in average height at 79.4 inches in the 2018-2019 season.

The shortest player featured in over 10% of the team's minutes was 6'3 or 73 inches.

**Positional Height**

This can also be broken down into positional height, meaning by each of the 5 positions on the court.

It takes the minutes played for each team ordered by height. For example, 20% of minutes played by the tallest players are likely the center's minutes.

For example, UCF's average height at the center position was +6.4 inches taller than the average of all teams.

UCF's starting center, Tacko Fall, was 7'6 or 90 inches. 

**Effective Height**

Effective height is the average of the center and power forward position. The same UCF squad posted an effective height of 3.9 inches for these 2 positions.

### Bench Minutes

Bench minutes, defined by [KenPom](http://kenpom.com/), makes an assumption that the starters of a team are the 5 players that have played the most minutes on the year.

The remaining minutes are assumed to be the bench minutes. If a player has played less than _10% of their team's minutes, the player is excluded_ in the bench minutes.

New Meixco State's bench played in 49.5% of its minutes in the 2018-2019 season. That ranked 1st in the country. No one on the team played more than 62.2% of the team's minutes. 

In contrast, Hartford's bench played in only 24.8% of its minutes. That's last or 353rd amongst all Division-I teams.

Whether a team relies on its bench is more of an attribute than a driving factor of its success. It can certainly be a factor if there is foul trouble, injuries, or a stretch of several games played in a short period.

### Continuity

Continuity is the percentage of a team’s minutes that are played by the same player or players from last season to this season.

It answers more than are the same players playing this season?

It uses a percentage of a players minutes played because of injuries and a player's increased or decreased minutes season to season.

[KenPom](http://kenpom.com/) takes each player on the current roster, uses the minimum minutes \(on a percentage basis\) he played comparing this season and last season, and then takes the sum for all players.

Let's use the 2015-16 North Carolina team as an example. Below are the minutes from the 2014-2015 season to the 2015-2016 team. The far column includes the minimum value.

```text
Player  |   %Min 14-15  | %Min 15-16  | Min
--------+---------------+-------------+-----+
Paige   |    16.5       |   13.4      | 13.4
Johnson |    12.2       |   14.0      | 12.2
Jackson |    13.3       |   14.1      | 13.3
Hicks   |    7.35       |   9.00      | 7.35
Meeks   |    11.2       |   8.48      | 8.48
Berry   |    5.20       |   15.4      | 5.20
Pinson  |    3.92       |   9.33      | 3.92
Britt   |    7.60       |   7.50      | 7.50
James   |    4.99       |   3.61      | 3.61
Maye    |    0.00       |   2.22      | 0.00
Williams|    0.00       |   1.52      | 0.00
White   |    0.30       |   0.40      | 0.30
Coleman |    0.24       |   0.21      | 0.21
Coker   |    0.00       |   0.20      | 0.00
Dalton  |    0.03       |   0.20      | 0.03
Egbuna  |    0.00       |   0.24      | 0.00
--------+---------------+-------------+-----+
```

The sum of the last column is **75.5**. North Carolina players played around 76% of the minutes from 2014-2015 to 2015-2016 season. That was good for 12th amongst all Division-I teams in the 2015-16 season.

Continuity is a new, and fascinating, stat. It tells more of a story, and as [KenPom](http://kenpom.com/) describes teams with [better continuity](http://kenpom.com/blog/measuring-continuity/), tend to perform better too.

In a landscape where the best teams often feature players headed to the NBA after one year, continuity is a fun metric to follow.

For example, below is Kentucky's continuity over the last 5 seasons:

```text
Year    |   Continuity  | Division-I Rank |
--------+---------------+----------------+
18-19   |   21.8        |   326
17-18   |   11.2        |   348
16-17   |   30.2        |   322
15-16   |   22.0        |   335
14-15   |   49.6        |   176
--------+---------------+----------------+
```

Kentucky continuity is often low, but it doesn't mean they're not winning games.

### Experience

Experience is another storytelling stat. [KenPom](http://kenpom.com/) makes the assumption that a player's eligibility class determines their experience.

Under this assumption, the following class has these levels of experience:

```text
Year       | Experience |
-----------+------------+
Freshmen   |   0        |
Sophomore  |   1        |
Junior     |   2        |
Senior     |   3        |
-----------+------------+
```

Experience uses minutes played similar to the average height calculation. Players that play in _less than 10% of their team's minutes are excluded_.

In the 2018-2019 season, Hartford ranked 1st in the country with 2.90 years of experience. This squad also had the lowest amount of bench minutes, which could explain why it relied on its upperclassman more. 

For a comparison, Duke ranked 350th in the country with 0.65 years of experience, as the Blue Devils played multiple freshman players. 

### Defensive Fingerprint

Does a team play man-to-man? Zone? Both?

The answer can be found in a team's defensive fingerprint. [KenPom](http://kenpom.com/) uses a variety of stats to breakdown teams into 4 defensive categories:

1. **Mostly man**: team plays mostly man-to-man defense
2. **Inconclusive**: can't identify a specific defensive tendency
3. **Some zone**: team is in zone defense for a good amount of its defensive possessions
4. **Mostly zone**: team plays most its defensive possessions in a zone defense

[KenPom](http://kenpom.com/) describes defensive fingerprint as raw. It uses assist percentage, 3-point attempt percentage, free throw attempt percentage, turnover percentage, and defensive rebounding percentage.

It weights these stats to develop a profile, and place a team in a certain fingerprint category. For example, zone teams tend to have higher a defensive assist percentage and 3-point attempt percentage.

Syracuse is known for its 2-3 zone. It statistically is near the bottom of all teams in defensive assist percentage and 3-point attempt percentage.

In the 2018-2019 season, Syracuse ranked 352nd in defensive A% at 67.8 and 347th in defensive 3PA% at a 48.1% clip.

### 2-Foul Participation 

When a player picks up his second foul in the first half, does he head to the bench? 

2-foul participation attempt to answer this question and reveal more of a coaching philosophy around fouls. The measurement is the percentage of time that a starter with 2 fouls in the first half has been allowed to play as detailed in [this blog post](https://kenpom.com/blog/introducing-2-foul-participation/). 

For example, starters for Virginia played 3.8% of minutes with 2 fouls in the first half in the 2017-18 season. Virginia, and coach Tony Bennett, ranked 331st in the country in this metric. 

_Remember when Virginia lost to 16-seed UMBC in the NCAA Tournament?_ Both Isaiah Wilkins and Devon Hall [picked up 2 fouls](https://virginiasports.com/boxscore.aspx?id=3540&path=mbball) in the first half, and both exited the game for the remainder of the first half after doing so.

KenPom also includes a few other measurements: 

* total amount of time starters have 2 fouls
* total time starters with 2 fouls are on the floor 
* adjusted 2-foul participation: accounts for backcourt players being allowed to play more
* percentage of bench minutes