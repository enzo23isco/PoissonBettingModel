# PoissonBettingModel

For this project, I ventured into the world of football data to develop a betting model that goes beyond the typical surface statistics. My journey began with the extraction of sophisticated metrics like Expected Goals, Expected Assists, and Expected Points from football events. These metrics, obtained from the specialized website understat.com, provided invaluable insights into the real dynamics of the game.

To streamline the data processing, I developed a Python program and leveraged APIs for data cleansing and manipulation. The primary goal was to apply this refined dataset to a Poisson Distribution Model, a mathematical tool that effectively simulates and assigns probabilities to games with over 1.5, 2.5, and 3.5 goals, respectively. For a deeper dive into the mathematical formula, I encourage you to explore the attached documentation, which includes examples.

I then loop the Poisson function across all the games within the same matchdays of the top 5 European leagues (EPL, La Liga, Bundesliga, Ligue 1, Seria A). Subsequently, I created interactive dashboards and visualizations, which are pivotal for generating comprehensive analytics reports. These visualization tools offered valuable insights into the probabilities of various game outcomes, enhancing the decision-making process.

In the final phase of this project, I utilized these probabilities to optimize my betting strategies. To minimize the risk of losing, I applied the Kelly Criterion. This strategic approach determines the optimal percentage of one's bankroll to wager based on the expected value of the bet in relation to the bookmakers' odds. The use of the Kelly Criterion ensures a methodical and calculated approach to sports betting, driven by data-backed insights and a commitment to long-term success.
