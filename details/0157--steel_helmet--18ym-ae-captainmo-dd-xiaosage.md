### Roster Details<br />
Team Name: Steel Helmet<br />
Roster: 18yM, AE, captainMo, DD, xiaosaGe<br />
Region: [Asia]( ../standings_asia.md)<br />
<br />
Global Rank: [157](../standings_global.md)<br />
Regional Rank: [17]( ../standings_asia.md)<br />
Final Rank Value:  665.8<br />
<br />
Final Rank Value (665.8) = Starting Rank Value (685.1) + Head To Head Adjustments (-19.2)<br />

#### Starting Rank Value<br />
To figure out a rosters's Starting Rank Value, first take the average of these four factors:<br />
- Bounty Offered: 0.383[<sup>1</sup>](#table2)
- Bounty Collected: 0.212[<sup>2</sup>](#table1)
- Opponent Network: 0.003[<sup>2</sup>](#table1)
- LAN Wins: 0.000[<sup>2</sup>](#table1)

The average of these factors is 0.150<br />
<br />
Next, take the maximum and minimum average across all teams and compute the following:<br />
- 400 + ( ( Roster_Average - Min_Average ) / ( Max_Average - Min_Average ) ) * 1600 = 685.1
- 400 + ( ( 0.150 - 0.000 ) / ( 0.840 - 0.000 ) ) * 1600 = 685.1


#### Factors<br />
Below you can see a table of all of the matches that contributed to this roster's Final Rank Value.<br />
Note:<br />

- For Bounty Collected, Opponent Network, and LAN Wins, we consider only the ten best results over the past 6 months.
- Raw values for those factors are multiplied by Age Weight. Bounty and Opponent Network values are also multiplied by Event Weight. The adjusted value is shown in parenthesis.
- The final value for a factor is the total of its adjusted values divided by 10. Bounty Collected is further scaled by the curve function[<sup>3</sup>](#curveFunction)
- Head to head adjustments are based on rosters' starting rank values. The results shown below are adjusted by Age Weight and not Event Weight
<span id="table1"></span><br />


| Match Played | Match ID | Date       | Opponent  | W/L | Age Weight | Event Weight | Bounty Collected | Opponent Network | LAN Wins  | H2H Adj. | Roster                                  |
| -: | -: | :- | :- | :- | :- | :- | :- | :- | :- | -: | :- |
|           13 |      719 | 2024-04-09 | Nemiga    | L   | 1.000      | -            | -                | -                | -         |    -1.19 | 18yM, AE, captainMo, DD, xiaosaGe       |
|           12 |      749 | 2024-04-08 | Astralis  | L   | 1.000      | -            | -                | -                | -         |    -0.27 | 18yM, AE, captainMo, DD, xiaosaGe       |
|           11 |     2188 | 2024-02-01 | GR        | L   | 0.565      | -            | -                | -                | -         |    -9.82 | 18yM, AE, captainMo, DD, xiaosaGe       |
|           10 |     2191 | 2024-02-01 | Newhappy  | L   | 0.564      | -            | -                | -                | -         |    -8.81 | 18yM, AE, captainMo, DD, xiaosaGe       |
|            9 |     2332 | 2024-01-23 | The Huns  | L   | 0.505      | -            | -                | -                | -         |    -8.51 | 18yM, Attacker, captainMo, DD, xiaosaGe |
|            8 |     2336 | 2024-01-23 | Eruption  | W   | 0.504      | 0.143        | 0.000 (0.000)    | 0.067 (0.005)    | 0 (0.000) |     4.11 | 18yM, Attacker, captainMo, DD, xiaosaGe |
|            7 |     2359 | 2024-01-22 | GR        | W   | 0.499      | 0.143        | 0.005 (0.000)    | 0.217 (0.015)    | 0 (0.000) |     6.91 | 18yM, Attacker, captainMo, DD, xiaosaGe |
|            6 |     2442 | 2024-01-20 | Newhappy  | L   | 0.484      | -            | -                | -                | -         |    -7.33 | 18yM, AE, captainMo, DD, xiaosaGe       |
|            5 |     2446 | 2024-01-19 | Nirvana   | W   | 0.483      | 0.143        | 0.000 (0.000)    | 0.019 (0.001)    | 0 (0.000) |     2.48 | 18yM, AE, captainMo, DD, xiaosaGe       |
|            4 |     2505 | 2024-01-18 | Wings Up  | L   | 0.476      | -            | -                | -                | -         |    -8.73 | 18yM, AE, captainMo, DD, xiaosaGe       |
|            3 |     2782 | 2024-01-12 | Rare Atom | W   | 0.431      | 0.143        | 0.025 (0.002)    | 0.189 (0.012)    | 0 (0.000) |     7.33 | 18yM, AE, captainMo, DD, xiaosaGe       |
|            2 |     2784 | 2024-01-12 | Nirvana   | W   | 0.431      | 0.143        | 0.000 (0.000)    | 0.019 (0.001)    | 0 (0.000) |     2.33 | 18yM, AE, captainMo, DD, xiaosaGe       |
|            1 |     2787 | 2024-01-12 | WDNMD     | W   | 0.430      | 0.143        | 0.000 (0.000)    | 0.000 (0.000)    | 0 (0.000) |     2.27 | 18yM, AE, captainMo, DD, xiaosaGe       |

<br />
<span id="table2"></span><br />
To calculate a roster's Bounty Offered:<br />

- First, take the sum of their top 10 scaled winnings ($4,000.00)
- Divide that value by the 5th highest value among all rosters ($162,092.66)
- The final value (0.02) is scaled by the curve function.[<sup>3</sup>](#curveFunction)

Top ten winnings for this roster:<br />

| Event Date | Age Weight | Prize Winnings | Scaled Winnings |
| :- | -: | :- | :- |


<span id="curveFunction"></span>_The Curve Function: 1 / ( 1 + abs( log10( x ) ) )_<br />

---
_Event data for Regional Standings provided by HLTV.org_<br />