# p_vs_np_challenge
P vs NP Challenge by @Sirajology on [Youtube](https://youtu.be/9MvbNPQiEE8)



Overview
============
This is the code for 'Why is P vs NP Important?' by @Sirajology on [Youtube](https://youtu.be/9MvbNPQiEE8). In this demo code, I go over a brute force approach to the Traveling Salesman Problem. The [TSP](https://developers.google.com/optimization/routing/tsp) problem states that given a list of cities, what's the shortest possible route a traveling salesman could take to visit all of them and return back to his home city? The way the demo code solves this is to try every possible path. Since the number of cities is low, this works. But if we added more cities, this would quickly get really computationally expensive.

Dependencies
============

None! Just good old Python 3.

Usage
===========

To run the demo code just run the following in terminal

``python demo.py``


Challenge
===========

The challenge for this video is to add a function to the demo code that gives a best estimate for the shortest route. Instead of trying every possible path, use another strategy to estimate the shortest route. Some examples of possible strategies you could use are Random path, Greedy, 2-Opt, or Simulated Annealing. 

Credits
===========
Credit for the vast majority of code here goes to [westphal](https://github.com/westphal). I've merely created a wrapper around all of the important functions to get people started. 

