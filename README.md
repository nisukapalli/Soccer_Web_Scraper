# Soccer_Web_Scraper

A web scraper to extract data from a database of 2021-22 Fantasy Premier League footballers and all 380 FBref match reports for the 2021-22 Premier League season.

## About the Project
The goal of the project is to determine how we can make defensive midfielders more valuable picks in Fantasy Premier League. Since they tend not to register many goal contributions, they usually only gain 1-2 points for playing minutes, 1 point for a clean sheet, and minus points for yellow or red cards. As a result, defensive midfielders are often avoided in FPL. If users do select one for their fantasy teams, it is mainly to serve as a cheap bench option that can make more funds available for premium attacking players.

One solution is to not award clean sheet points to attacking midfielders and wingers (wingers are considered midfielders in FPL), and possibly increase the clean sheet reward to 2 points for defensive midfielders. However, this introduces the problem of how we distinguish between a defensive and attacking midfielder. Some midfielders don't strictly fall under either category, or serve different roles for their clubs.

A viable solution would be to award 1 point for every 3 ball recoveries (interceptions + tackles won) made during a match. Since defensive midfielders are far more likely to register meaningful numbers for interceptions and successful tackles than attacking midfielders and wingers, this new scoring system would help close the large gap in points between them. This web scraper pulls position and points data from the GitHub FPL archive, and tackles and interceptions statistics from FBref.

## Sources
https://fbref.com/en/comps/9/2021-2022/schedule/2021-2022-Premier-League-Scores-and-Fixtures

https://github.com/vaastav/Fantasy-Premier-League/tree/master/data/2021-22
