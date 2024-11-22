# Agent-Based Modelling 

### Overview

Here, we explore a number of agent based models using [NetLogo](https://ccl.northwestern.edu/netlogo/), 
the multi-agent programmable modelling environment.

What is agent-based modelling? 

[Wilensky and Rand (2015)](https://mitpress.mit.edu/9780262731898/an-introduction-to-agent-based-modeling/) provide a good definition.

<p align="center">
"An agent is an autonomous computational individual or object with particular properties and actions. Agent-based modelling is a form of computational modelling whereby a phenonenon is modelled in terms of agents and their interactions."
</p>

This page presents a number of different agent-based models that are implemented in NetLogo.

### 1. The Door Colour Models

The three [Door colour imitation models](https://github.com/JimDuggan/EPE/tree/main/ABM/01%20Doors), which:

* Models the idea of the spread of ideas, which is this case is the decision to paint a door either gray (default) or blue (new colour).
  
* Represents dwellings as NetLogo agents known as [patches](https://ccl.northwestern.edu/netlogo/bind/primitive/patches.html).
  
* Locates the dwellings  on a grid, so each dwelling has four neighbours that influence it (north, south, east and west).
  
* Creates a number of rules for each agent/patch which causes them to change colour. Effectively, it's a form of mimicry, and if your neighbours turn blue, you are more likely to also turn blue.

* Uses probability (e.g. somewhat like throwing a dice) to decide whether to change colour.

