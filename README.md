# NetLogo Agent-Based Simulation: Emergence of Ethnocentrism

Coursework project developed for Economic Cybernetics at ASE Bucharest describing agent-based dynamics through the standard ODD - Overview, Design concepts, Details protocol.

## Overview
This project evaluates the emergence of ethnocentric behavior and social segregation among autonomous agents using an evolutionary game theory model in NetLogo.

The study tracks how simple decentralized rules of local cooperation and genetic drift foster homogeneous geographic clusters without top-down coordination.

## ODD Protocol Summary
* Purpose and Patterns: Investigating how in-group favoritism evolves over time, observing the macro-level dominance of ethnocentric strategies.
* Entities and State Variables: Agents possess individual group tags (color), interaction strategies, and reproductive fitness on a two-dimensional toroidal grid.
* Process Scheduling: At each discrete tick, agents interact locally with neighbors, pay cooperation costs, collect payoff rewards, reproduce proportionally to fitness, and undergo mutation.
* Design Concepts:
  * Emergence: Spatial segregation and group clustering arise purely from decentralized local interactions.
  * Adaptation and Rationality: Agents do not deliberate globally; reproductive survival serves as the selection mechanism.
  * Stochasticity: Randomness dictates initial placements, immigrant arrivals, partner availability, and strategy mutations.
* Strategy Classifications:
  * CC: In-group cooperate, out-group cooperate, altruists
  * CD: In-group cooperate, out-group defect, ethnocentrics
  * DC: In-group defect, out-group cooperate
  * DD: In-group defect, out-group defect- pure defectors

## Key Observations
* Over extended time horizons, the ethnocentric strategy CD consistently outperforms and dominates competing strategies.
* Spatial clustering protects cooperative agents from out-group exploitation, creating stable clusters of similar color tags across the grid.

## Repository Contents
* Ethnocentrism.docx: Complete documentation formatted according to the seven steps of the ODD protocol, featuring interface snapshots and strategy trajectory plots.
