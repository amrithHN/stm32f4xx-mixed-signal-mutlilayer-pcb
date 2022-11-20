# Documentation
## PCB design tips
### Rules
First thing is these rules are not enough, because there can be 100s of Rules for a complex PCB.
1. ground plane boards are better because they allow signal routing in a microstrip or stripline configuration. It also significantly reduces the ground impedance and, therefore, the ground noise;
2. high speed signals should be "routed" on intermediate layers located between the various levels. In this way, ground planes can act as a shield and contain the radiation coming from the tracks at high speed
3. a signal layer must always be adjacent to a plane
4.  Multiple ground planes are very advantageous, since they lower the board's ground impedance and reduce radiation in a common way;
5. the power to Power or GND to GND planes must be rigorously coupled together;
6. Configurations should be symmetric. For example, on an eight-layer PCB, if level 2 is a plane, level 7 should also be a plane
7. Put the signal levels next to the levels of the plane (ground or power) the return current can flow on an adjacent plane reducing the inductance of the return path to a minimum;
8. to further improve noise and EMI performance, insulation between a signal layer and its adjacent plane can be made even thinner;
9. an important consideration to be done is the thickness of each signal layer. There are standard thicknesses together with the properties of different types of printed circuit material. When selecting the materials, it is advisable to consider their electrical, mechanical and thermal properties;

### Some Advantages of MultiLayer Board
- increases the board's ability to distribute energy
- reduces cross-interference, eliminates electromagnetic interference
supports high-speed signals
- While a stackup level allows you to get multiple electronic circuits on a single board through the various layers of PCB board
- a stack of PCB layers can help minimize the circuit vulnerability to external noise, as well as minimize radiation and decrease impedance and crosstalk problems on high-speed systems
- good PCB stacking can also contribute to efficient and low-cost final production;
- a correct stack of PCB layers can improve the electromagnetic compatibility of the project.
- The higher the number of layers, the more the designer is free to unravel his circuit, with less chance of stumbling into "impossible" solution
### Following Factors we have to thing Before and during the design
- No of Layer 
- Number of Planes and Type of Planes 
- Sequence of Layers 
- Spacing b/w the Layers
