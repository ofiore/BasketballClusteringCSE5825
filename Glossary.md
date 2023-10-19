# Terms used in the data
### As there is a lot of basketball jargon and very similar statistics, I have compiled a list of every column header in the dataframe and its meaning

"They/their" will refer to the player, as each row denotes 1 player playing for a particular team
+ **Player** is the player
+ **Pos** is their primary position
+ **Age** how old they are
+ **Team** is what team they played for in a particular season
+ **G** is how many games they appeared in
+ **GS** is how many games they were in the starting lineup for
+ **MP** is the average number of minutes they played a game
+ **FG** is the average number of made field goals they make in a game
+ **FGA** is the average number of field goals they attempt in a game
+ **FG%** is the percent of field goals they made in the season
+ **3P** is the average number of 3 pointers they make in a game
+ **3P%** is the percent of 3 pointers they made in the season
+ **2P** is the average number of 2 pointers they make in a game
+ **2P%** is the percent of 2 pointers they made in the season
+ **eFG%** is calculated as (FG + 0.5 * 3P)/FGA.  If Player A shoots 8 for 10 with 4 threes and 4 2s and scores 20 points and Player B shoots 10 for 10 with 10 twos, then both players have 20 points from the field on 10 shots and the same eFG%
+ **FT** is the average number of free throws they make in a game
+ **FTA** is the average number of free throw attempts they make in a game
+ **FT%** is the percent of free throws they made in the season.
+ **ORB** is the average number of offensive rebounds they grab in a game
+ **DRB** is the average number of defensive rebounds they grab in a game
+ **TRB** is the average total number of rebounds they grab in a game
+ **AST** is the average number of assists they have in a game
+ **STL** is the average number of steals they have in a game
+ **BLK** is the average number of blocks they have in a game
+ **TOV** is the average number of turnovers they have in a game
+ **PF** is the average number of personal fouls they commit in a game
+ **PTS** is the average number of points they score in a game
+ **TMP** is the total number of minutes they played in a season
+ **ORtg** is the average number of points produced per 100 possessions
+ **DRtg** is the average number of points allowed per 100 possessions
+ **PER** is Player Efficiency Rating which is a measure of a per-minute rating of a player's performance.  For more information: https://www.basketball-reference.com/about/per.html
+ **TS%** is true shooting percentage for the season and is calculated as PTS / (2* FGA + 0.44 * FTA)
+ **FTr** is the number of free throw attempts per FG attempt
+ **ORB%** is an estimate of the percent of offensive rebounds a player grabbed while on the floor
+ **DRB%** is an estimate of the percent of defensive rebounds a player grabbed while on the floor
+ **TRB%** is an estimate of the percent of total rebounds a player grabbed while on the floor
+ **AST%** is an estimate of the percent of teammate field goals a player assisted while they were on the floor
+ **STL%** is an estimate of the percent of opponents possessions that resulted in a steal by the player while they were on the floor
+ **BLK%** is an estimate of the percent of opponent's 2 point shots that resulted in a block by the player while they were on the floor
+ **TOV%** is an estimate of turnovers per 100 plays and calculated as 100*TOV/(FGA + 0.44 * FTA + TOV)
+ **USG%** is an estimate of the percent of team plays used by a player while they were on the floor
+ **OWS** is Offensive Win Shares which is a calculation that estimates the players contribution to the number of team wins in a season. For more information: https://www.basketball-reference.com/about/ws.html.
+ **DWS** See offensive win shares
+ **WS** is total win shares which is OWS + DWS
+ **WS/48** is an estimate of the number of wins contributed by the player per 48 minutes. The league average is roughly 0.1
+ **BPM** and its derivatives is a calculation that estimates the points per 100 possessions that a player contributed above an average player on an average team. For more information: https://www.basketball-reference.com/about/bpm2.html
+ **VORP** is Value Over Replacement Player and is an estimate of the points per 100 possesions that a player contributed above a replacement level player, to an average team that plays 82 games. For more information: https://www.basketball-reference.com/about/bpm2.html (Towards the bottom of the link)
+ **PG%** is the percent of minutes during a season a player played the point guard position
+ **SG%** is the percent of minutes during a season a player played the shooting guard position
+ **SF%** is the percent of minutes during a season a player played the small forward position
+ **PF%** is the percent of minutes during a season a player played the power forward position
+ **C%** is the percent of minutes during a season a player played the center position
+ **OnCourt** is their plus/minus per 100 possessions
+ **On-Off** is their plus/minus net per 100 possessions
+ **BadPass** is their season total of turnovers caused by bad pass
+ **LostBall** is their season total of lost ball turnovers
+ **ShootFC** is their season total of shooting fouls committed
+ **OffFC** is their season total of offensive fouls committed
+ **ShootFD** is their season total of shooting fouls drawn
+ **OffFD** is their season total of offensive fouls drawn
+ **PGA** is their season total of points generated through assists.
+ **And1** is their season total of field goals made in which they also drew a foul
+ **Blkd** is their season total of field goal attempts that were blocked
+ **Dist.** is their average field goal distance away from the hoop
+ **%2PFG** is the percent of field goal attempts that were 2 point shots
+ **0-3%FGA** is the percent of field goal attempts that were from 0 to 3 feet
+ **3-10%FGA** is the percent of field goal attempts that were from 3 to 10 feet
+ **10-16%FGA** is the percent of field goal attempts that were from 10 to 16 feet
+ **16-3P%FGA** is the percent of field goal attempts that were from 16 feet to the three point line
+ **%3PFG** is the percent of field goal attempts that were 3 point shots
+ **0-3FG%** is the percent of made field goals that were attempted between 0 and 3 feet
+ **3-10FG%** is the percent of made field goals that were attempted between 3 and 10 feet
+ **10-16FG%** is the percent of made field goals that were attempted between 10 and 16 feet
+ **16-3PFG%** is the percent of made field goals that were attempted between 16 feet and the 3 point line.
+ **2P%A** is the percent of made 2 point field goals made that they were assisted on
+ **3P%A** is the percent of made 3 point field goals made that they were assisted on
+ **Dunk%FGA** is the percent of field goal attempts that were dunks
+ **Dunks** is the season total of dunks that a player made
+ **C3%3PA** is the percent of three point attempts that were taken in the corner
+ **C33P%** is their shooting percentage of three points attempts that were taken in the corner
+ **FG+**, **2P+**, **3P+**, **eFG**, **FT+**, **TS+**, **FTr+**, **3pA+** are
adjusted shooting stats.  More information can be found here: https://www.sports-reference.com/blog/2020/06/adjusted-shooting-stats-added-to-basketball-reference/
+ **FGAdd** is the number of extra points added by field goal attempts made above the league average
+ **TSAdd** is the number of extra points added by true shot attempts made above the league average
+ **Season** denotes the season the player accumulated these stats
+ **Salary** denotes how much they were paid. Still need to add
+**%Cap** denotes the percent of that year's salary cap they were paid. Still need to add






