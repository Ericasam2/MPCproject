# MPCproject
## Introduction
For the MPC project, we will work on the control of the Keen Model[1]. Keen Model is an
essential macroeconomic model – – based on Goodwin Model[2], it introduces the bank
investment and debt rate. The dynamic model of the Keen Model is given below:
 
![alt text](https://github.com/Ericasam2/MPCproject/blob/main/img/MPC%20project%20topic%20selection.jpg "Logo Title Text 1")

* $\omega$ is the wage share
* $\lambda$ is the employment rate
* d is the debt rate
* k(.) is a function of the rate of new investment (user defined)
* phi(.) is the Phillips Curve (an increasing function)
* r is a constant interest rate

The dynamic system itself is autonomous, to implement MPC, we can separate the function k(.) and design two parameters [a,b] as the input, thus the original k becomes k(a, b).

## Goal and approach:
Our goal is to implement an MPC controller to control the interest rate so that 
* the system can be stabilized ;
* the unemployment rate & debt rate can be constrained under a certain
level at the steady state; 
* the overall control effort can be minimized. 

We will use the MPC to control the plant, and the knowledge from linear/nonlinear MPC
design will be applied.

## References
1. [THE DYNAMICAL SYSTEMS APPROACH TO MACROECONOMICS](https://ms.mcmaster.ca/~grasselli/PhD_Thesis_Bernardo_R_C_Costa_Lima_Final_Submission.pdf)
2. []()
