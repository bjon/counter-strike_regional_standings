### Roster Details<br />
Team Name: Lore<br />
Roster: hyza, JoJo, ondyey, seNsite, SlooKy<br />
Global Rank: [280](../../standings_global_2025_02_24.md)<br />
<br />
Region: [Europe]( ../../standings_europe_2025_02_24.md)<br />
Regional Rank: [157]( ../../standings_europe_2025_02_24.md)<br />
<br />
Final Rank Value:  405.0<br />
<br />
Final Rank Value (405.0) = Starting Rank Value (400.0) + Head To Head Adjustments (5.0)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.000[<sup>1</sup>](#table2)
- Bounty Collected: 0.000[<sup>2</sup>](#table1)
- Opponent Network: 0.000[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.000<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 400.0
- 400 + ( ( 0.000 - 0.000 ) / ( 0.840 - 0.000 ) ) * 1600 = 400.0


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent          | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|            6 |     2437 | 2024-10-02 | Legacy            | L   | 0.234      | -            | -                | -                | -         |    -0.46 | hyza, JoJo, ondyey, seNsite, SlooKy     |
|            5 |     2769 | 2024-09-24 | InControl         | W   | 0.181      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.83 | hyza, JoJo, ondyey, seNsite, SlooKy     |
|            4 |     2857 | 2024-09-22 | USA               | W   | 0.167      | 0.371        | 0.000 (0.000)    | 0.006 (0.000)    | 0 (0.000) |     2.62 | hyza, JoJo, ondyey, seNsite, SlooKy     |
|            3 |     2963 | 2024-09-18 | What’s for dinner | W   | 0.141      | 0.371        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.22 | hyza, JoJo, ondyey, seNsite, SlooKy     |
|            2 |     3087 | 2024-09-14 | Final Form        | L   | 0.115      | -            | -                | -                | -         |    -1.25 | hyza, JoJo, Mak, nico1ajus, SlooKy      |
|            1 |     3152 | 2024-09-12 | Canada            | L   | 0.101      | -            | -                | -                | -         |    -1.00 | JoJo, maeggi, nico1ajus, ondyey, SlooKy |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($0.00)
- Divide that value by the 5th highest value among all rosters ($371,464.45)
- The final value (0.00) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />
