# A Simple Threshold Rule is Sufficient to Explain Sophisticated Collective Decision Making

This repository contains a re-implementation of [Robinson et. al (2011)]([url](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0019981)). 

## Project Objective
The main objective of this project is to recreate the results of observed ants in their choice of a new nest selection via simulations. 

## Threshold Rule
The threshold rule described in the paper states that each ant (scout or otherwise) has an inherent threshold, based on which, they determine if a nest is suitable for migration or not. If the nest quality k assessed by the ant upon reaching a new nest (with a random assessment error e, so k+e combined) is greater than the ant's inherent threshold value, then the ant decides to stay at the new nest, otherwise, it moves on to search for another nest.
This model assumes no use of an active memory in ants while moving from one nest to another (memory independent state transitions).

## Result described in the Paper

![Screenshot 2024-10-28 115211](https://github.com/user-attachments/assets/3f48ea6b-8bbc-4ecf-8430-d94b9ccf3d74)

The 'far nest' corresponds to the 'good nest' and the 'near nest' corresponds to the 'bad nest'.

## Recreating the Result

![Screenshot 2024-10-28 114350](https://github.com/user-attachments/assets/53b2a755-226c-4b63-ab8d-cc13ab7a2d34)

## Change in interpretation

One of the changes that has been made in the visualization of the result is that instead of multiple bars, the same bar is being used to convey the amount of ants that switched or stayed at a 'good site' or a 'poor site'
