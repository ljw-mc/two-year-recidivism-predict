# two-year-recidivism-predict
built a regression model and Neural-Network model to predict two-year recidivism rates for past offenders using the COMPAS dataset.

# Part 1:

This part of the project involves working with the COMPAS dataset and reproduces results from two scientific papers. It's divided into two sub-tasks:

Building a Logistic Regression Model: constructed a logistic regression model that predicts two-year recidivism. This model meets the calibration standard but fails to satisfy false-positive parity. 

Adjusting Thresholds: Based on the idea from Corbett-Davies and Goel's paper, we adjust the thresholds for different demographics in the classifier. The goal is to create an algorithm that satisfies false-positive parity but may not meet the calibration standard.

# Part 2:

Part 2 of the project is about leveraging insights from the Deep Learning Training Playbook to train a challenging system. 

We train a network architecture that predicts both a demographic and the outcome of interest. 
The cost function is designed in such a way that it predicts the demographics as poorly as possible and the outcome as well as possible.
We deal with issues like mode collapse and improving the performance of the system, using techniques suggested in the Deep Learning Training Playbook.
