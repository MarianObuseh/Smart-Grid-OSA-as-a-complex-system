# Modeling of Smart Grid Control Center Operations: The Operators Standpoint 
Here, I make an attempt to model the smart grid control room as a chaotic complex system whose operator states evolve by the presence or absence of a social concept called Vigilance Training and certain rules of engagement.
I incorporate chaos theory where small perturbations lead to a drastic change in evolving states of agents.
I also incorporate Cellular Automata Simulations.
Most of the codes are written in Python but the actual Agent-Based Modeling is done using a Personal Learning Edition of AnyLogic.
The cellular automata grid is assumed to have fixed boundary conditions (no particular theoretical backing is given for this). It is more heuristic than it is hinged on any particular basis.
I also have a lattice structure with network graphs where a 1st order Moore Neighborhood is implemented.
Iterations are done randomly. This is based off on the assumption that in a control room, there's no particular order to which operators interact with each and/or one another.
Operators are assumed to be in one and only one of the following states at each time in the model: <br/>
      **1. Before Training <br/>
      2. During Vigilance Training <br/>
      3. After Vigilance Training without Improved Situation Awareness <br/>
      4. After Vigilance Training with Improved Situation Awareness** <br/>
