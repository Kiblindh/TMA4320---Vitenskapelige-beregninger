# Projects in TMA4320: Introduction to Scientific Computation.

## Project 1: Biophysics

Introduction:

This project is separated into two parts; first we want to perform a simple simulation of how differently charged monomers behave in a 2D solution, and second we will use and compare this to a solution with uniformly charged polymers. Polymers are simulated as a group of monomers of the same charge that are bound together with covalent bonds. The objective is to examine how the mono/polymers cluster under different temperatures. We examine this by a monte carlo simulation where the probability of two particles forming a group is dependent on their charge relative to the temperature, higher temperatures giving a smaller probability of differently charged mono/polymers staying together.

Alongside these simulations we calculate the potential energy of the system, where larger clusters correspond to a smaller potential energy of the system. For a qualitative examination of our monte carlo simulation, we plotted the potential energy of a system for both 200K and 500K, comparing the equilibria levels and obtaining an estimate for the steps needed to reach equilibrium. For two random groups of monomers we plotted the mean cluster size at ten different temperatures from 100K to 1000K, after a number of steps deemed to bring us qualitatively close enough to equilibrium. In part two we perform similar simulations for groups of monomers.

## Project 2: Engineering Physics

Introduction:

In this project we examine the rolling behavior of a ship by modeling it as a long half-cylinder. With a given mass and radius of the model semi-cylinder we can calculate common ship parameters (metacentre, centre of buoyancy, etc.) and then simulate the ships rolling behavior based on given initial conditions. In the first part of the project we assume the buoyancy to be constant for a simplified model. In the second part we recalculate the buoyancy together with the other forces at each step, later adding in a frictionless transversally sliding point mass on the deck, simulating the behavior of our model with and without a railing preventing the mass from sliding off deck. In this project we mainly used the RK4 method to solve the differential equations of the model system numerically, and plotted the roll and heave of the ship.

## Project 3: Industrial Mathematics

Introduction:

In this project we are using non-negative matrix factorization (NMF) to compress the data needed to store several low-resolution images called non-fungible tokens (NFTs) that lend themselves to this purpose by having several common features.
We first implement an NMF algorithm and test it on a set of simple matrices. Then we will apply our algorithm to a set of 500 NFTs, where we will be plotting 64 of them.
Then, we demonstrate how the NMF extracts common features and how accurate the reconstruction is, visually and by computing the Frobenius norm.

In the last part of this project we add random noise to the NFTs and then apply the NMF to se how effectively it can denoise the images. We will then again provide a plot of the Frobenius norm of the difference between the original images and the reconstructions for several dimensions of the NMF.

Note: The projects are done in Norwegian, but the readme file is translated to english.
