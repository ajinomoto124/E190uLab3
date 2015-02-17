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


#### Conclusions
Time spend on lab: about 6 hours.
Buttons a switch and two control sticks were attached to a wooden board as a make-shift controller.  Learning how to solder and making mistakes along the way was probably the most time consuming part of this lab.  In the future, it might be better to ensure that everyone in the class can solder properly.
