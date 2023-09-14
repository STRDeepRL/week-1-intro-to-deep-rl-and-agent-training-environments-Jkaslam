

---
# Assignment 1: Intro to Deep RL with Single Agent Training Environments

## Due Date
- **Due Date:** Thursday, September 14, 6:00 PM

# Question 1

Based on your observations in this exercise, in your own words, please briefly describe the impact of having the right scale of dense rewards in respect to the total horizon of the game.

# Answer

Having the correct scale for rewards drastically affects how quickly the agent converges to an optimal policy. I did a 3 way comparison where the penalty for using the pickup command was -.2, -.2/100 and -.2/1280. At step 124,000 the mean episode lengths were 1280, 1263 and 16.62 respectively. As tasks get more complicated and convergence becomes slower, I can see how choosing the right rewards scale will be vitally important. 
