# Baseball-Schedule-Generator-Requirements

HIgh-Level Goal: Create a C# class library that will produce a plausible 162 game schedule for all 30 MLB teams.

Considerations to set aside (for now): Unplanned events that would require adjusting the schedule, such as weather or known events that would normally
have to be scheduled around (stadium is unavailable due to a concert or event). These possibilities may be considered in the future.

Known Facts:

* There are 30 teams
* Every team plays 162 games
* Every team plays 81 HOME games
* Every team plays 81 AWAY games
* Matchups should be distributed as evenly as possible. For example, two teams should not play a disportionate number of their 
in games succession.
* Searies of games occur in increments of 3 or 4 matchups against the same team. Two-game matchups can be scheduled to fill any gaps.
* 19 games × 4 opponents within same division (76 games), 6 or 7 games x 10 opponents interdivision within same league (66 games), 20 interleague games
