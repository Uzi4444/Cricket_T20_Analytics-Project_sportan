# Cricket_T20_Analytics-Project_sportan-:cricket_game:

![made-with-PowerBI](https://img.shields.io/badge/made%20with-PowerBI-blue.svg)

Data analysis of best 11 from the T20 world cup.  In this end-to-end sports data analytics project I have used data from the ESPN Cricinfo website and  using python, pandas, and Power BI performed analyses on T20 world cup cricket data.
---

## Parameters set:
1**The team should be able to score at least 180 runs on an average**

2**They should be to defend 150 runs on an average**

===========================
# 1) OPENERS

| PARAMETERS | DESCRIPTION | CRITERIA |
| --- | --- | --- |
| Batting Average | Average runs scored in an innings | > 30 |
| Strike Rate | No of runs scored per 100 balls | > 140 |
| Innings Batted | Total Innings batted | > 3 |
| Boundary % | % of runs scored in boundaries | > 50 |
| Batting Position | Order in which the batter played | < 4 |

# 2) ANCHORS/MIDDLE ORDER

| PARAMETERS | DESCRIPTION | CRITERIA |
| --- | --- | --- |
| Batting Average|  Average runs scored in an innings | > 40 |
| Strike Rate | No of runs scored per 100 balls | > 125 |
| Innings Batted|  Total Innings batted | > 3 |
| Avg. Balls Faced | Average balls faced by the batter in an innings | > 20 |
| Batting Position | Order in which the batter played | > 2 |

# 3) ALL-ROUNDERS/LOWER ORDER

| PARAMETERS | DESCRIPTION | CRITERIA |
| --- | --- | --- |
|Batting Average | Average runs scored in an innings | > 15|
|Strike Rate | No of runs scored per 100 balls | > 140 |
|Innings Batted | Total Innings batted | > 2|
|Batting Position | Order in which the batter played | > 4 |
|Innings Bowled | Total Innings bowled | > 2 |
|Bowling Economy | Average runs allowed per over | < 7 |
|Bowling Strike Rate | Average no. of balls required to take a wicket | < 20 |

# 4) SPECIALIST FAST BOWLERS

| PARAMETERS | DESCRIPTION | CRITERIA |
| --- | --- | --- |
| Innings Bowled | Total Innings bowled | > 4 |
| Bowling Economy | Average runs allowed per over | < 7 |
| Bowling Strike Rate | Average no. of balls required to take a wicket | < 16 |
| Bowling Style | Bowling style of the player | = "%Fast%" |
| Bowling Average | No. of runs allowed per wicket | < 20 |
| Dot Ball % | % of dot balls bowled | > 40 |
