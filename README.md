# NBA_Assisted
Interactive plot of assisted field goals vs eFG% in the NBA from 2013 to 2020

LINK: https://nba-assisted.herokuapp.com/

Created in Python using the Dash package for web apps.

Data collected from stats.nba.com

------- Analysis -------

I conceived of the idea for this plot when thinking about a particular type of roster construction. Specifically, when teams have a star player but "just need to surround him with shooters". These stars might have a questionable jump shot like Giannis or Ben Simmons, or the entire offense might be built around the ball being in their hands like James Harden and the Rockets. In these cases, spot up perimeter shooters just need to be able to knock down shots when the defense collapses and the ball is kicked out to them. However, in thinking about teams like the Rockets, I realized that Clint Capela is not a three-point shooter, but still has a crucial role as an outlet for James Harden to dish on a drive, pick and roll or slip. This caused me to reframe my target into simply players that excel without the ball in their hands.

This, like many nuanced elements of basketball, is not easily quantifiable. But this two-dimensional representation does a good job of sorting players visually into separate categories, and allows different teams' styles to be contrasted easily. On the x-axis is the percentage of a player's field goals that were assisted. The y-axis is the effective field goal percentage of each player, which accounts for the added value of three-point shots. Using eFG% instead of FG% gives skilled shooters a more even playing field against bigs who usually take higher-percentage two-point shots closer to the basket.

Players on the left tend to be isolation-heavy players like James Harden, or point guards who pound the ball and control the offense out of pick-and-roll like Kemba Walker. Players on the far right tend to be spot-up shooters like Kyle Korver and Joe Harris who rarely create off the dribble. Players a little to the left of the spot-up shooters, but higher in eFG% tend to be roll men like Clint Capela or Rudy Gobert, who take high-percentage shots close to the basket but have slightly more unassisted field goals due to post-ups or (more likely) second chance buckets from offensive rebounds.
