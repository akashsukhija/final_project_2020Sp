## Team members: Siddharth Shetty, Akash Sukhija

###  Contributions:
###  Siddharth : Worked on create_map, assign_traffic, add_routes, initializemap, accidents_per_edge, accidents_per_roadtype, route_display, run_experiment, main function, doctests and docstrings.
###  Akash : Worked on create_map, assign_traffic, add_routes, accidents_per_edge (Stats), run_experiment, final_stats, main function. Travis CI integration, doctests and docstrings.
###  Equal contribution in making presentations.


**Determining the probability of a crash of a vehicle under different conditions using Monte Carlo Simulation**

Many lives are lost and countless people are injured all around the world due to driving under the influence of alcohol or due to distracted driving because of cellphone usage. In 2018, there were 319,146 crashes involving motor vehicles in Illinois. Injury crashes accounted for 21.1% of these crashes (67,453), while fatal crashes (951) accounted for less than 1% of these crashes. There was an average of 1.1 deaths per fatal crash.

As part of our project we are trying to simulate the number of crashes for an autonomous vehicles and comparing it to the number of crashes occuring due to driving under the influence of alcohol and distracted driving due to cellphone usage.

**Project Proposal:**
We plan to use the Monte Carlo Simulation technique to calculate the probability of autonomous vehicles colliding with another object in its route.
We are keeping the following variables constant:
Number of Turns
Speed Limit
Country (Driving Rules)
Type of Route (Highway, In City)
 
**Hypothesis 1:**
     The number of overall accidents decreases when people who consume alcohol travel only in autonomous vehicles (Do not drive cars).
**Hypothesis 2:**
    The number of overall accidents decreases when people can use cell phones only in Autonomous vehicles. (Do not use cell phones and drive cars)

**Assumptions:**
Percentage of Car Collisions per 100 Vehicles: 3%
Percentage of Collisions per 100 Vehicles including Drivers under Influence of Alcohol:  3.3%
Percentage of Collisions per 100 Vehicles including Drivers distracted due to Cell phone usage: 3.24%
Percentage of Collisions of Autonomous Vehicles per 100 Vehicles: 2%


References: 
1. https://www.willenslaw.com/distracted-driving-a-leading-cause-of-car-accidents-in-chicago/
2. http://www.idot.illinois.gov/Assets/uploads/files/Transportation-System/Resources/Safety/Crash-Reports/crash-facts/2018%20Crash%20Facts.pdf
3. https://networkx.github.io/documentation/stable/reference/classes/digraph.html
4. https://docs.scipy.org/doc/numpy-1.9.2/reference/generated/numpy.random.binomial.html
5. https://docs.python.org/3/library/random.html
6. https://pandas.pydata.org/docs/
7. https://stackoverflow.com/questions/30362391/how-do-you-find-the-first-key-in-a-dictionary 
8. https://www.nhtsa.gov/sites/nhtsa.dot.gov/files/100carmain.pdf
