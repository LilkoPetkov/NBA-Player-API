# NBA player API
![my badge](https://badgen.net/badge/hello/world/red?icon=twitter)

NBA player API with full information about each player in NBA history.
The API can provide information about the player's general data, career highs,
regular season stats and post season stats. NBA teams and games will be added as well. 

# Table of contents
* [Endpoints](#Endpoints)
* [Technologies](#Technologies)
* [License](#License)

## Endpoints
 - https://nba-api-vxlu.onrender.com/get-player/$id (int) - Get Player Data
 - https://nba-api-vxlu.onrender.com/search-player/$name (string) - It is advisable to search for a last name, the result will be all players that match the name along with their IDs
 - https://nba-api-vxlu.onrender.com/regular-seasons/player/$id (int) - Search for all regular season stats for a given player
 - https://nba-api-vxlu.onrender.com/post-seasons/player/$id (int) - Search for all post season stats for a given player 
 - https://nba-api-vxlu.onrender.com/career-high/player/$id (int) - Search for career high 

---
**NOTE**

All information was last updated after the 2022-2023 season. New players from the latest draft are not added.

---

## Technologies
 - Python 3.9
 - PostgreSQL 15 
 - Flask Restful


## License

[MIT](https://choosealicense.com/licenses/mit/)
