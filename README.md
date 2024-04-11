# IPL-Case-Study

This repository contains datasets related to the Indian Premier League (IPL) matches from 2008 to 2022. The dataset comprises two main files:

1. **IPL_Matches_2008_2022.csv**: This file contains details of each match, including venue, toss decision, match winner, man of the match, squads, etc.
2. **IPL_Ball_by_Ball_2008_2022.csv**: This file provides ball-by-ball data for each match, including batsman on strike, bowler, extras, runs, wicket ball, etc.

## Attribute Information

### IPL_Ball_by_Ball_2008_2022.csv

1. **ID**: Match ID given by ESPNCricinfo.
2. **Innings**: Inning number (1 for the first inning, 2 for the second inning).
3. **Overs**: Over number (0-19).
4. **Ballnumber**: Ball number within the over.
5. **Batter**: Batsman on strike.
6. **Bowler**: Bowler.
7. **Non-striker**: Non-striker batsman.
8. **Extra_type**: Type of extra if the ball is an extra (possible values: byes, legbyes, wides, noballs).
9. **Batsman_run**: Runs scored by the batsman for the ball.
10. **Extras_run**: Extra runs for the ball.
11. **Total_run**: Total runs for the ball.
12. **Non_boundary**: Indicates whether the 4 or 6 scored was not via an actual boundary (1 if overthrow).
13. **isWicketDelivery**: Indicates whether the ball is a wicket delivery.
14. **Player_out**: Batsman getting out.
15. **Kind**: Type of wicket-taking ball.
16. **Fielders_involved**: Fielders involved in the wicket-taking ball.
17. **BattingTeam**: Batting team.

### IPL_Matches_2008_2022.csv

1. **ID**: Match ID given by ESPNCricinfo.
2. **City**: City where the game was played.
3. **Date**: Date of the match.
4. **Season**: IPL season.
5. **MatchNumber**: Match number for that IPL season. For qualifiers and finals, the match number would be Final, Qualifier 2, Qualifier.
6. **Team1**: Team 1.
7. **Team2**: Team 2.
8. **Venue**: Stadium.
9. **TossWinner**: Team winning the toss.
10. **TossDecision**: Toss decision (the toss winner either choosing field or bat).
11. **SuperOver**: Indicates whether the match had a super over.
12. **WinningTeam**: Winner of the match.
13. **WonBy**: Winning margin (runs or wicket).
14. **Margin**: Margin of win.
15. **Method**: Whether the Duckworth-Lewis (D/L) method was applied in the match.
16. **Player_of_Match**: Player of the match.
17. **Team1Players**: Team 1 squad array value.
18. **Team2Players**: Team 2 squad array value.
19. **Umpire1**: Umpire 1.
20. **Umpire2**: Umpire 2.

## Task Overview

In this analysis, we aim to perform data wrangling steps such as error checks, missing values treatment, outlier checks, and duplicate values checks. We will also conduct non-visual data analytics, including uni-variate and bi-variate analysis, to derive interesting insights from the dataset. Additionally, we will answer specific questions based on the analysis, such as:

1. Identify the over with the most runs scored on average.
2. Determine the top 10 umpires who were part of the most matches.
3. Calculate the team with the highest probability of winning a match given that they won the toss.
4. Identify the top 10 most successful bowlers in terms of the number of wickets taken.
5. Calculate the number of playoff matches played for each team.
6. Determine the venue where the team batting second has the most advantage.
7. Identify the batsman in IPL history who has been caught out the most.
8. Determine the bowler who has taken the wicket of the batsman mentioned in question 7.

For the detailed analysis and findings, please refer to the Jupyter Notebook or script provided in this repository.

