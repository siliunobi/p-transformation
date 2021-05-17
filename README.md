# The P Transformation (work in progress)

We have implemented in Maude the P transformation using Maude's meta-level facilities.

The entire transformation mechanism consists of two components:

- The "Transformation" component implements the P transformation and includes the probability distribution library. 
- The "Simulation" component applies the simulation transformation to the resulting module and also includes an extensible sampling library. 

The "maude-impl" folder contains P's implementation in Maude, as well as some toy examples.
