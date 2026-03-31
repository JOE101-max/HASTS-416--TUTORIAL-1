# HASTS-416--TUTORIAL-1
R solutions for HASTS 416 Tutorial 1 on Markov chains, including chain diagrams, trajectory simulations, steady-state analysis, limiting behavior, and traffic-state modeling.
# HASTS 416 Tutorial 1 in R


## Topics Covered

### Question A1: 5-State Markov Chain
- Plotting the Markov chain diagram
- Identifying communicating classes
- Identifying transient and recurrent states
- Identifying absorbing and reflecting states
- Finding the period of each state
- Simulating trajectories
- Computing steady-state probabilities
- Assessing whether the chain is ergodic
- Plotting unconditional probabilities over time

### Question A2: 7-State Markov Chain
- Plotting the Markov chain diagram
- Identifying recurrent and transient classes
- Finding state periods
- Checking for absorbing and reflecting states
- Simulating trajectories
- Computing stationary probabilities
- Interpreting limiting behavior
- Showing the period-2 oscillation in the recurrent class \{S1, S2\}

### Question A3: Traffic Conditions Markov Chain
- Modeling traffic states: **Light, Heavy, Jammed**
- Using different transition matrices for different time periods
- Computing the distribution of traffic states at 6 PM
- Verifying the analytical result using **10,000 simulations**

## Important Note

For **Question A3**, the lecturer clarified that in the **second row of the first transition matrix**, the entry **0.5 should be replaced with 0.4**.  
So the corrected row used in this repository is:

```text
0.3  0.4  0.3
