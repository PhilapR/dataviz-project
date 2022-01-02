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

![image](https://github.com/PhilapR/dataviz-project/blob/master/Data%20Vis%20Sketching%202.png?raw=true)

![image](https://github.com/PhilapR/dataviz-project/blob/master/IMG_0635.png?raw=true)

## Itterations (All images link to vizhub)

The following shows 10 players and how long they played for. Further filtering and grouping needs to be applied. 

[![image](https://raw.githubusercontent.com/PhilapR/dataviz-project-template-proposal/master/Screenshot%202021-09-22%20205711.png)](https://vizhub.com/PhilapR/84bb71dc5b7a453c8ba42877002185e0)

The next itteration properlly loaded in the data, allowing for sorting and interaction with a dropdown menu to select the stat.

[![image](https://github.com/PhilapR/dataviz-project/blob/master/sorting.png?raw=true)](https://vizhub.com/PhilapR/2080ec9560d548ac9e31c74e9f6b43f3)

Following this I had a few things that felt really important. First of all, if you watch the NBA, you might have noticed so issues with the above screenshot. The active players had stats from their last season, while retired players had their career stats. The other thing was sometimes the graph felt like it was cutting of some of the data (if you flip it to assits.) I was tired of this and didn't know any better so I moves away from react.

[![image](https://github.com/PhilapR/dataviz-project/blob/master/grouping.png?raw=true)](https://vizhub.com/PhilapR/8c50e49e89d24ca4948345df589f9fd2?mode=full)

After struggling for a long time with checkboxes, I decided to move on. I knew grouping was going to be a huge part of my project so I went ahead and got started on grouping by Year and Country. While the produced visual is a bit difficult to get anything other than most of the players have historically been from the US, it was a step towards setting up the D3 graphs I would use from here on out. 

[![image](https://github.com/PhilapR/dataviz-project/blob/master/filters.png?raw=true)](https://vizhub.com/PhilapR/01f20f4af7b0451bb0fd3cca61a1d5d6?mode=full)

This itteration finaly includes filtering. While nothing too fancy, active and inactive players are now separated and grouping now works as intended allowing for a variety of grouping methods to be selected. 

[![image](https://github.com/PhilapR/dataviz-project/blob/master/horzTimline.png?raw=true)](https://vizhub.com/PhilapR/5dca65a0ce4d4143b88bc4f50a6438ab?mode=full)

Using the core behind the existing bar chart I turned it into a timeline to show how the selected stat changed overtime.

[![image](https://github.com/PhilapR/dataviz-project/blob/master/vertTimeline.png?raw=true)](https://vizhub.com/PhilapR/61f5f675969f40c2a4429ffaf5eb2f69?mode=full)

From there I swaped the axis to make the timeline make more sense. For awhile here I was stuck upsidedown and for some reason some years disappear from the axis labels, but only some of the time.

[![image](https://github.com/PhilapR/dataviz-project/blob/master/together.png?raw=true)](https://vizhub.com/PhilapR/1dc660e128334c8b9e2637f1354bf155?edit=files&file=index.js&mode=full)

The last itteration involved bringing the two graphs together, while not perfect most of the project funtions as intended. I mentioned some of my struggles above, but will touch on some more of what I wish were included below.

## Inital Questions & Tasks

The following tasks and questions will drive the visualization and interaction decisions for this project:

 * What players had the best per-game stats?
 * Are those players consistantly the best across stats?
 * What era of players lasted the longest in the NBA?
 * Are there statistics that are indicitive of when a player played?

##Debrief




