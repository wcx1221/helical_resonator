# Design of Helical Resonator for Ion Traps

Based primararily on "On the application of radio frequency voltages to ion traps via helical resonators" - Silverns, Simkins, Weidt, Hensinger. ([arXiv:1106.5013v3](https://arxiv.org/abs/1106.5013))

Helical resonator is a wire helix (inductor) surrounded by cylindrical conductive shield (conductor) that allows for impedence matching between the RF source and the ion trap to enable high voltage while reducing noise.

The code (helical_res.py) follows the Silverns paper which guides through the design and construction of such a resonator for any given ion trap system. Particularly, the program outputs contour plots of quality factor (Q) as a function of the coil diameter (d) and the coil to shield diameter ratio (d/D) for given input paramters described below. 

![Design Paramters](design_paramters.png)
