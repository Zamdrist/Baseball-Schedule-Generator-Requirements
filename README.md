# Baseball-Schedule-Generator-Requirements

HIgh-Level Goal: Create a C# class library that will produce a realistic proposed 162 game schedule for all 30 MLB teams.

Known Facts:

* There are 30 teams
* Every team plays 162 games
* Every team plays 81 HOME games
* Every team plays 81 AWAY games
* Matchups should be distributed as evenly as possible. For example, two teams should not play a disportionate number of their 
in games succession.

* In division:
** 2 3 4 at home, 3 3 4 on the road
** 3 3 3 at home, 3 3 4 on the road
** 3 3 4 at home, 2 3 4 on the road
** 3 3 4 at home, 3 3 3 on the road

* For interdivision play:
** 3 teams are 3 at home, 4 on the road
** 3 teams are 4 at home, 3 on the road
** 4 teams are 3 at home, 3 on the road

* Interleague play:
** 2 teams are 3 at home
** 2 teams are 3 at the road
** 1 team is 2 at home, 2 on the road
** 2 at home and 2 on the road
