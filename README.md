# Roulette Simulation Using the Monte Carlo Method

The Monte Carlo method works by using a known probability distribution and drawing from it a specified number of times. To explore this concept, I created a simulation of a roulette game in Wolfram Mathematica. In this project, I explore how to calculate expected value using the monte carlo method and how using a popular betting method affects our results.

![gif](/img/simGif.gif)

## Analysis
To have an analytical baseline to compare results with, I calculated the expected value of betting on red (using $5 bets). The simulation results should be in line with these analytical results

![Eq1](https://latex.codecogs.com/gif.latex?E%28X%29%3D%5Csum%20%28P%28x%29%5Ccdot%20x%29)<br>
![Eq2](https://latex.codecogs.com/gif.latex?E%28X%29%3DP_%7Bwin%7D%20%5Ccdot%20Payout%20&plus;%20P_%7Blose%7D%20%5Ccdot%20Bet)<br>
![Eq3](https://latex.codecogs.com/gif.latex?E%28X%29%3D%28%5Cfrac%7B18%7D%7B38%7D%29%285%29%20&plus;%20%28%5Cfrac%7B20%7D%7B38%7D%29%28-5%29%20%3D%20-0.263158)

It's always nice when the analytical and the experimental results converge. This will be a good way to check that. 

## Mathematica Code

The Mathematica code is set up to let the user explore different betting strategies and game configurations. The user can modify variables like bankroll, minimum and maximum bet, rouletty style, etc. The default values are numbers that I have seen in most casino games (except for the bank roll amount, I haven't seen much of that). The live plot view feature works well with trials under 1000 but times out if evaluation takes too long. 

An interactive web version is also avaialble here (account needed?): https://mathematica.wolframcloud.com/app/objects/bd9c0c88-9011-47c7-9dff-afd74bc8e404

## Results

You can view results in the img directory. Here are some of them:

15-bet games. Random black or red betting strategy and double down after every loss strategy
![randomBet15Games](/img/randomBet15Games.png)
![doubleDown15Games](/img/doubleDown15Games.png)

20-bet games. Random black or red betting strategy and double down after every loss strategy
![randomBet20Games](/img/randomBet20Games.png)
![doubleDown20Games](/img/doubleDown20Games.png)

100-bet games. Random black or red betting strategy and double down after every loss strategy
![randomBet100Games](/img/randomBet100Games.png)
![doubleDown100Games](/img/doubleDown100Games.png)


*Video coming soon*

----

Resources
-[Good Monte Carlo explanation video](https://youtu.be/OgO1gpXSUzU)
-[Link 1](https://en.wikipedia.org/wiki/Monte_Carlo_method)


To see more projects please visit [http://ajumpa.com/](http://ajumpa.com/)

