# randomtalkcode

small pieces of code used to create animations and figures for a [talk about randomness](ezsolti.github.io/randomtalk).

The scripts are written from scratch or based on openly available code. References are included within the notebooks.


## Content

- MemicoLogicSimulation: code to implement an algorithm behind the 80s hungarian game called Memico.
- MemicoPhysicsSimulation: code using pygames and pymunk to create a physics based animation of the game Memico.
- doublependulum: simple implementation of a double pendulum. Plotting based on open source scripts.
- RandomNumberGenerator: implementing a simple LCG and visualizing it's cycle. Plots inspired by A. Haghighat: Monte Carlo Methods for particle transport, CRC Press (2020). Furthermore, some testing of randomness is covered.
- RandomWalk: Implementing a 2D random walk, and comparing to deterministic solution. Inspired by https://www.coursera.org/learn/modeling-simulation-natural-processes
- FluidDynamicsLBM: Fluid dynamics simulation based on https://palabos.unige.ch/get-started/lattice-boltzmann/lattice-boltzmann-sample-codes-various-other-programming-languages/, only additional obstacles have been added.

## Dependencies

Most notebooks only rely on typical scientific packages (numpy, matplotlib, scipy), however for MemicoPhysicsSimulation one requires pygames and pymunk as well.

## Contribution

If you spot any mistakes, please shout out.
