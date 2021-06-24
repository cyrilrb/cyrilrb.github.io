# cyrilrb.github.io
Drop location to put visualization for easier access for presentation


Files work up data from draft.csv that has 12,140 entries that documents every draft pick from 1977. 

Process to filter through data is as follows:
1) Imported data into python and used pandas and numpy to eliminate extra data so that a unique player identifier (playerId), draft year (draft), round pick (round), number picked in draft (pick)
the team they were  drafted to (draftTeam), the player's position (position) and team id (teamID) were kept for analysis.
2) Data set was filtered based on Atlanta and draft picks from 2000 - 2010. 
3) Data set was further filtered to give top 5 positions to allow for more effective presentation of position per draft decade.
4) Data was exported to a new csv holder.
5) Data in csv holder was used to populate d2 radial bar chart that visually expresses draft trend for the 2000-2010 decade for the Atlanta Falcons.
