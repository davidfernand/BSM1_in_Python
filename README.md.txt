# Implementation of BSM1 in Python

Authors: Lukas Vandenberge, David Fernandes del Pozo

Affilitation: Department of Data Analysis and Mathematical Modelling (BIOMATH), Ghent University.

Academic year: 2023-2024

### Summary

Environmental regulations and standards are becoming increasingly stringent nowadays. 
The role of Waste Water Treatment Plants (WWTPs) plays a crucial role in achieving these goals. 
By modeling WWTPs, their operation can be better controlled and optimised, facilitating compliance with strict 
discharge norms and regulations. In this thesis, the focus lies on implementing a simple WWTP configuration with 
the use of a publicly accessible programming language to address several drawbacks of currently existing models. 
Python was chosen for coding, as this programming language is gaining worldwide popularity and emphasises code readability. 
Implementations in Python include the modelling of the Activated Sludge Model No.1, presented by Henze et al. (2000) describing 
the biokinetic part combined with a secondary settler for the general implementation of a conventional WWTP layout according to 
 the configuration presented in the Benchmark Simulation Model No.1 (BSM1), prepared by Alex et al. (2008). 
Initially, a point settler model is implemented, which led to a successful working implementation, but less satisfactory results. 
However, after the successful verification of the Takács settler model, introduced by Takács et al. (1991), 
excellent results were obtained, which demonstrated the feasibility of implementing a simple WWTP configuration in a publicly 
accessible programming language, suitable for further simulations.
