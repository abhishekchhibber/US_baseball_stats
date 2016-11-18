# US Baseball Stats

### In this project, I have analysed the tenure and success of various baseball managers in the US. 

The analysis answers the following questions:
* How many managers and teams are there in the dataset?
* How many managers managed more than one team?
    * What is the average number of teams managed by a manager?
    * What is the break-up of managers as per number of teams managed?
    * Which managers managed maximum teams?
* What was the tenure of different managers with different teams?
    * What was the average tenure of a manager with a team?
* During the course of a manager's tenure with a team, did the team's average ranking (as compared to that of year of joining):
    * Increase
    * Decrease
    * Remain Same
* Which were the top managers and teams that achieved highest increase in average ranking?
* What is the correlation between a manager's tenure, and team's increase in average ranking?
* During the course of a manager's tenure with a team, did the team's average winning % (as compared to that of year of joining):
    * Increase
    * Decrease
    * Remain Same
* Which were the top managers and teams that achieved highest increase in average winning % increase?
* What is the correlation between a manager's tenure, and team's increase in average winning % increase?

_I have used Pandas and Numpy on Python 3.5_   


### Limitations of the analysis

* The analysis is done considering only few specific attributes related to managers and teams. It does not take into account other attributes that might have impacted the teams' performances and ranking, directly or indirectly.
* Correlation between managers' tenure and teams' ranking, and between managers' tenure and teams's winning % does not establish causation. Hence, the analysis cannot confirm if teams' perfomance increased because managers stayed more with the teams, or managers's tenure was increased because the teams were performing well. Further, there can be a third factor establishing cause-effect relationship.
* For Correlation, I have considered Delta Degree of Freedom (DDOF) = 0 for maximum likelihood estimate.
