# Roulette Simulation Using the Monte Carlo Method
----
The Monte Carlo method works by using a known probability distribution and drawing from it a specified number of times. To explore this concept, I created a simulation of a roulette game where one bets either black or red. We can calculate our expected value (for $5 bets) the following way:

```
E(X)  = ∑X * P(X)
E_RedWin = (18/38)(5) + (20/38)(-5) = -0.263158
```

In this project I explore how we can calculate this value using the monte carlo method and how using a popular betting method affects our results.


![gif](/img/simGif.gif)


----
## Theory

[Link 1](https://en.wikipedia.org/wiki/Monte_Carlo_method)

----
## Mathematica Code

The Mathematica code is set up to let the user explore different betting strategies and game configurations. The user can modify variables like bankroll, minimum and maximum bet, rouletty style, etc. The default values are values that I have seen in most casino games (except for the bank roll amount, I haven't seen that). The live plot view feature works well with trials under 1000 but times out if evaluation takes too long. 

An interactive web version is also avaialble here (account needed?): https://mathematica.wolframcloud.com/app/objects/bd9c0c88-9011-47c7-9dff-afd74bc8e404

----
## Demo

*Video coming soon*

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

----


To see more projects please visit [http://ajumpa.com/](http://ajumpa.com/)

