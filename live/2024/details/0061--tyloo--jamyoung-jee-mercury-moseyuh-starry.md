### Roster Details<br />
Team Name: TYLOO<br />
Roster: JamYoung, Jee, Mercury, Moseyuh, Starry<br />
Global Rank: [61](../standings_global_2024_08_14.md)<br />
<br />
Region: [Asia]( ../standings_asia_2024_08_14.md)<br />
Regional Rank: [4]( ../standings_asia_2024_08_14.md)<br />
<br />
Final Rank Value:  986.1<br />
<br />
Final Rank Value (986.1) = Starting Rank Value (950.6) + Head To Head Adjustments (35.5)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.442[<sup>1</sup>](#table2)
- Bounty Collected: 0.281[<sup>2</sup>](#table1)
- Opponent Network: 0.057[<sup>2</sup>](#table1)
- LAN Wins: 0.336[<sup>2</sup>](#table1)

The average of these factors is 0.279<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 950.6
- 400 + ( ( 0.279 - 0.000 ) / ( 0.811 - 0.000 ) ) * 1600 = 950.6


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                   |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           15 |      281 | 2024-08-06 | Chinggis Warriors | W   | 1.000      | 0.380        | 0.013 (0.005)    | 0.180 (0.069)    | 1 (1.000) |    13.44 | JamYoung, Jee, Mercury, Moseyuh, Starry  |
|           14 |      305 | 2024-08-05 | Rare Atom         | W   | 1.000      | 0.380        | 0.009 (0.003)    | 0.448 (0.170)    | 1 (1.000) |    13.75 | JamYoung, Jee, Mercury, Moseyuh, Starry  |
|           13 |      341 | 2024-08-04 | Gaimin Gladiators | W   | 1.000      | 0.380        | 0.032 (0.012)    | 0.326 (0.124)    | 1 (1.000) |    13.13 | JamYoung, Jee, Mercury, Moseyuh, Starry  |
|           12 |      410 | 2024-08-02 | Rare Atom         | L   | 1.000      | -            | -                | -                | -         |   -17.41 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|           11 |      452 | 2024-08-01 | Rare Atom         | W   | 1.000      | 0.143        | 0.009 (0.001)    | 0.448 (0.064)    | 0 (0.000) |    13.35 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|           10 |      459 | 2024-08-01 | CatEvil           | W   | 1.000      | 0.143        | 0.000 (0.000)    | 0.228 (0.033)    | 0 (0.000) |     4.90 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            9 |     1151 | 2024-07-13 | Rare Atom         | L   | 0.985      | -            | -                | -                | -         |   -18.98 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            8 |     1153 | 2024-07-13 | CatEvil           | W   | 0.985      | 0.143        | 0.000 (0.000)    | 0.228 (0.032)    | 0 (0.000) |     3.89 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            7 |     1165 | 2024-07-12 | Chinggis Warriors | W   | 0.977      | 0.143        | 0.013 (0.002)    | 0.180 (0.025)    | 0 (0.000) |    15.14 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            6 |     1168 | 2024-07-12 | Alter Ego         | W   | 0.977      | 0.143        | -                | 0.075 (0.010)    | 0 (0.000) |     2.48 | JamYoung, Jee, Mercury, Moseyuh, zhokiNg |
|            5 |     1635 | 2024-06-08 | Lynn Vision       | L   | 0.752      | -            | -                | -                | -         |   -10.41 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |
|            4 |     1689 | 2024-06-07 | GR                | W   | 0.745      | 0.416        | 0.007 (0.002)    | 0.067 (0.021)    | 0 (0.000) |     3.93 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |
|            3 |     1758 | 2024-06-06 | The QUBE          | W   | 0.738      | 0.416        | 0.005 (0.001)    | 0.056 (0.017)    | 0 (0.000) |     4.03 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |
|            2 |     1811 | 2024-06-05 | Lynn Vision       | L   | 0.732      | -            | -                | -                | -         |   -10.02 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |
|            1 |     1857 | 2024-06-04 | LYG               | W   | 0.725      | 0.416        | 0.003 (0.001)    | -                | -         |     4.27 | JamYoung, k4Mi, Mercury, Moseyuh, zdr    |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($17,547.37)
- Divide that value by the 5th highest value among all rosters ($320,160.38)
- The final value (0.05) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |
| 2024-08-06 |      1.000 | $13,755.00     | $13,755.00      |
| 2024-06-09 |      0.758 | $5,000.00      | $3,792.37       |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />