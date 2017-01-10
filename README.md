# fctoolz
A set of tools to aid fantasy teams contest for FC.
Consist of the following:
* RankingApp
* TeamSelectorApp

**RankingApp**
RankingApp is a script that calculates points scored by each fantasy teams with the help of statistics read from cricclubs.com.
It is a simple GUI app with the following functionality:
  * Read stats from cricclubs.com
  * Update stats in to an excel spreadsheet (CriccclubsStatsDB). 
  * Read fantasy teams from a spreadsheet (Created from participants teams) and calculate points 
  * Create tables/graphics for upload in to cricclubs that includes
    - Winning fantasy team of the current game
    - Names of winners
    - Overall standing
    
**TeamSelectorApp**
Stand alone executable that allows participants to select their playing 11.
Forces constraints in to the selection process so that the selected team is complaint with with Fantasy team composition rules
Once the selcted team passes complaince, it can be copied over and submitted via google forms to the competition moderator



