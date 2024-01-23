# Implementation of BSM1 in Python

**Author**: Lukas Vandenberge

**Supervisors**: dr. David Fernandes del Pozo, Prof. dr. ir. Ingmar Nopens

**Affilitation**: Department of Data Analysis and Mathematical Modelling (BIOMATH), Ghent University.

**Academic year**: 2023-2024

**Contact details**: david.fernandesdelpozo@ugent.be, fernandesdelpozodavid@gmail.com

**Master thesis title**: Implementation of a wastewater treatment plant model in Python

### Summary

Environmental regulations and standards are becoming increasingly stringent nowadays. The role of Waste Water Treatment Plants (WWTPs) plays a crucial role in achieving these goals.
 By modeling WWTPs, their operation can be better controlled and optimised, facilitating compliance with strict discharge norms and regulations. 
 In this thesis, the focus lies on implementing a simple WWTP configuration with the use of a publicly accessible programming language to address several drawbacks of currently existing models. 
 Python was chosen for coding, as this programming language is gaining worldwide popularity and emphasises code readability. 
 Implementations in Python include the modelling of the Activated Sludge Model No.1, presented by Henze et al. (2000) describing the biokinetic part combined with a secondary settler for the general implementation of a conventional WWTP layout. 
 The configuration is based on the Benchmark Simulation Model No.1 (BSM1) described in Alex et al. (2008). Initially, a point settler model was implemented. 
 Although this led to a successful working implementation, it offered less satisfactory results when compared to the BSM1 results in the report. 
 To improve its accuracy, the Takács settler model (Takács et al. 1991) was implemented and numerically verified. 
 Excellent results were obtained when compared to the open-loop steady-state plant simulation results, demonstrating the feasibility of implementing a simple WWTP model in Python. 
 Additionally, the model was tested with three different dynamic file inputs. The results at the plant effluent showed some differences with the reported averaged values, indicating that the model should be further tested and debugged.  
 Despite this, a partially accurate approximation was achieved and is considered satisfactory for its intended purposes. 

### References

- Henze, Mogens., & International Water Association. Task Group on Mathematical Modelling for Design and Operation of Biological Wastewater Treatment. (2000). 
*Activated sludge models ASM1, ASM2, ASM2d and ASM3*. IWA Pub.

- Alex, J., Benedetti, L., Copp, J., Gernaey, K., Jeppsson, U., Nopens, I., Pons, M., Rieger, L.,
Rosen, C., Steyer, J., et al. (2008). *Benchmark simulation model no. 1 (bsm1)*. Report by the
IWA Taskgroup on benchmarking of control strategies for WWTPs.

- Takács, I., Patry, G. G., and Nolasco, D. (1991). *A dynamic model of the clarification-
thickening process*. Water research, 25(10):1263–1271.
