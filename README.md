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

----
## Demo

*Coming soon*

----


To see more projects please visit [http://ajumpa.com/](http://ajumpa.com/)

