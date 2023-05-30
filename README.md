# Gasket-in-Salome-Meca-Code_Aster
A simple example of a gasket in between two plates subjected to internal pressure.

This very simple example shows how a gasket and the clamping pressure/force of the two plates may be simulated with contact in Salome-Meca/Code_Aster. The model is a quarter of a very simple fuel cell stack. The gasket is frictionless and has a round shape, it features an internal wire, that is connected to springs. Basically, these springs may be tuned to hold the gasket in place when internal pressure is applied.

SOFC operating temperatures are quite high, anywhere between 650-1000°C depending on the design and materials used. Heating the stack is not done in this simple example. Instead, we just use elastic moduli somewhat reflecting the operating temperature of 800°C. 
In t=1 a pressure is applied to the inner part above the ceramic medium (lower value of -5MPa) and to the region above the gasket (higher value of -100MPa). In t=2 an internal pressure of 0.8MPa is applied. 
