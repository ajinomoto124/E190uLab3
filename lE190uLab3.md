# E190uLab3
## Lab3 Write-Up
#### Introduction:
Tested controller viability vs another controller in Lugaru

#### Design Methodology:
After looking through the code for both Lugaru and Cube2 Andy and I felt it would be more interesting and much easier to work with.  We first went through the files and checked for the values we wanted to track. We then used the C++ file io to write those values out in a csv file format every time the player either one or lost a challenge level.

Andy's lab report can be found at: https://github.com/euclio/video-game-console-design/tree/master/lab3

#### Testing Methodology:
For the sake of simplicity, we decided to run all of our tests using the first challenge level in Lugaru.  The level is simple.  There are three enemy rabbits and the player must defeat all of them in battle.  The statistics we logged were: the level played, the system time that the test was completed, whether the player won or lost,the total time the player survived,the number of attacks, the number of "rabbit kick" attacks, the number of successful attacks, the number of times the player pulled off a reversal, the number of times the player's attack was reversal'ed by an enemy, the difficulty played on, and the score for that round.  We used the ABBA testing methodology with four rounds for each controller.  Some users played 4 rounds with my controller, 8 rounds with Andy's and then another 4 rounds with my controller.  Results were all compiled and compared in a csv file.

#### Results and Discussion
Though the sample size was relatively small, we did recieve some mildly useful results.  After calculating the average values for each statistic, we came up with the following table:
![alt text](https://github.com/ajinomoto124/E190uLab3/blob/master/Stats.png)

Where numKicks is the number of successful attacks, numAttacks is the number of attacks in general, numReversals is the number of times the player successfully reversed an enemy attack and numReversaled is the number of times the player's attacks were reversed by the enemy.  

Most of the values were fairly similar across the two controller types but the win/loss rate was slightly higher on my controller (20/4 to 15/9) and the average score was also higher (~440 to ~360).  Among the three test users including myself, my controller was noted for being more comfortable to play with but had the downside of the jump button being difficult to reach. 

#### Conclusions
Time spend on lab: about 11.5 hours.
Again, with such a small sample size (48 matches total played by 3 players) it is difficult to say how much the difference in data really speaks about the controllers themselves.  There is also some bias introduced since Andy and I had a lot of practice playing with our own controllers when we were testing our code for printing the correct values.

