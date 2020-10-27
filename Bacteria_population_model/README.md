## Summary

This code is used for the analysis of the population dynamics of the RootPatch GM bacteria, and the Wildtype B. mycoides and its interactions with each other and the environment. The files contain a system of ODEs to represent the bacterial populations, and the analysis on each parameter.

## Overview

The code defines a set of Ordinary Differential Equations (ODEs) that represent the bacterial population over time. We took two different bacteria in this model, Our GMO and the Non-GMO counterpart of this bacteria that is already in the soil (B.mycoides). Additionally it calculates the importance of different parameters, and it shows the visual results of the ODEs. The code is validated based on the ratkowski square root equation, lotka Volterra competitie interactions and diffusion of the bacteria.

## Instruction to using the model

The model contains three files. For the files to work best, download them and then open them in mathematica. Use "Shift -Enter " to run the code, start with the running the Quit[] to clear previous calculations.

### The first file: RootPatch_Bacteria_Bifurcation_Population
Contains the overall bacterial population plots, as well as a manipulate plot for the different parameters and the bifurcation analysis. 

### the second file: RootPatch_Bacteria_Initial_Population 
Contains the code used to analyze the effect of starting with a different of bacteria in the soil.

### The third file: RootPatch_Bacterial_Sensitivity_Parameters 
Contains the code used for the sensitivity analysis, the sensitivity analysis was with a 2% change in parameter value.
