# euros-goals
A side project I did in Summer 2020, looking at how many points a 3rd placed team will get.
It is based on analysis from Moroney(1951), that showed that the number of goals in football is well modelled by a poisson distribution
Using this, the number of points needed to qualify in 3rd place can be calculated.

There is an assumption here that the numbers of goals scored by teams is random, which is clearly not true. While there is undoubtedly a random element to football, it is also true that some teams are more likely to score goals than others.
Despite this, the random assumption does seem to give fairly realistic predictions.

The script is written in python, using Jupyter.

Euro_goalspg.ipynb contains the information on the previous tournaments, to get the mean number of goals per team per game for a poisson distribution

