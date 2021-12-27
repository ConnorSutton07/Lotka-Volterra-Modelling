#  Comparison of Numerical Integrators Applied to the Lotka-Volterra Equations

## Introduction

Within a given habitat, a number of species occupying a variety of ecological niches form a dynamic system in which the population of a given species is dependent on its birth and death rates, the number of predators, the availability of food sources, etc. Biologists and ecologists may want to understand how, given initial populations, the sizes of both a predator species and a prey species will evolve over time. 
The Lotka-Volterra equations, also referred to as the predator-prey equations, describe the dynamics of an ecological predator-prey system:

![equation](https://latex.codecogs.com/svg.image?%5Cbegin%7Balign*%7D%20%20%20%20%5Cfrac%7Bdx%7D%7Bdt%7D%20&=%20%5Calpha%20x%20-%20%5Cbeta%20xy,%20%5C%5C%20%20%20%20%20%5Cfrac%7Bdy%7D%7Bdt%7D%20&=%20%5Cdelta%20xy%20-%20%5Cgamma%20y.%5Cend%7Balign*%7D)
