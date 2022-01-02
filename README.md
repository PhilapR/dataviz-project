# NBA Historical Player Performance Data Visualization Project

The most up to data vizhub can be found [here](https://vizhub.com/PhilapR/1dc660e128334c8b9e2637f1354bf155?edit=files&file=index.js&mode=full)

## Data

The data I am using for my project is NBA career statistics. Sourced directly from the [nba](stats.nba.com) endpoints with python and [nba-api](https://github.com/swar/nba_api).

Players are organized by a player ID
All seasons played by players are separated by Preseason, Regular, Allstar and PostSeason  
I've discovered that active players are treated differently than retired ones. Active players have stats from their last season, while reired players have career stats.
Physical Stats are also recorded  
The focus here will be on the stats themselves. Points, Assists and Rebounds.

## Prototypes

The following shows 10 players and how long they played for. Further filtering and grouping needs to be applied. 

[![image](https://raw.githubusercontent.com/PhilapR/dataviz-project-template-proposal/master/Screenshot%202021-09-22%20205711.png)](https://vizhub.com/PhilapR/84bb71dc5b7a453c8ba42877002185e0)



## Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * What players had the best per-game stats?
 * Are those players consistantly the best across stats?
 * What era of players lasted the longest in the NBA?
 * Are there statistics that are indicitive of when a player played?

## Comments and State of the Project

This iteration added frist included a lot of back end cleaning and preparation of data. Then I was able to add a dropdown that allows the viewer to select the stat they are interested in viewing. For now it is stuck sorted by points. A few issues are present first off all active players are treated differently than retired players. Their data is from the last season while retired players have their career stats. I will be adding a toggle to look at past season vs retired players. Unfortunatly this messes with some of the analysis I wanted to do but Ill adapt. I also want to add a slider that allows you to choose the years to look at.



