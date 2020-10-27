## Overview

This code is used for the analysis of the population dynamics of the **RootPatch** GM _B. mycoides_, the Wild-type _B. mycoides_, and their interactions with each other and the environment. The code defines a set of ordinary differential equations (ODEs) that represent the bacterial population over time. Additionally it predicts the influence of different parameters on the bacterial population dynamics, and it shows the model shows visual outcome of the solved ODEs. The code is validated based on the Ratkowski square root equation, Lotka-Volterra competition equations, and the diffusion of the bacteria.

## Instruction to using the model

The model contains three files. Prior to working with them you need to download the Mathematica package. The files should be opened with Mathematica. Use "Shift-Enter" to run the code, start with running the Quit[] to clear the previous calculations.

### The first file: RootPatch_Bacteria_Bifurcation_Population

Contains the overall bacterial population plots, where the bacterial density can be plotted over time throughout the season. This file also contains the manipulate plots, which could be used to see the impact of changing a certain parameter on the bacterial density course. 

### the second file: RootPatch_Bacteria_Initial_Population 

Contains the code used to analyze the effect of starting with a different of bacteria in the soil.

### The third file: RootPatch_Bacterial_Sensitivity_Parameters 

Contains the code used for the sensitivity analysis, the sensitivity analysis was with a 2% change in parameter value.

Author: Ronja Hulst
