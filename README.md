# Implementation of BSM1 in Python

**Author**: Lukas Vandenberge

**Supervisors**: dr. David Fernandes del Pozo, Prof. dr. ir. Ingmar Nopens

**Affilitation**: Department of Data Analysis and Mathematical Modelling (BIOMATH), Ghent University.

**Academic year**: 2023-2024

**Contact details**: david.fernandesdelpozo@ugent.be, fernandesdelpozodavid@gmail.com

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

### References

- Henze, Mogens., & International Water Association. Task Group on Mathematical Modelling for Design and Operation of Biological Wastewater Treatment. (2000). 
``Activated sludge models ASM1, ASM2, ASM2d and ASM3``. IWA Pub.

- Alex, J., Benedetti, L., Copp, J., Gernaey, K., Jeppsson, U., Nopens, I., Pons, M., Rieger, L.,
Rosen, C., Steyer, J., et al. (2008). ``Benchmark simulation model no. 1 (bsm1)``. Report by the
IWA Taskgroup on benchmarking of control strategies for WWTPs.

- Takács, I., Patry, G. G., and Nolasco, D. (1991). ``A dynamic model of the clarification-
thickening process``. Water research, 25(10):1263–1271.
