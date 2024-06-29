# WebGL Gross-Pitaevskii Equation
A WebGL implementation of a 2D Gross-Pitaevskii Equation numerical solver. The solver runs in real time and is directly interactive.

# Original Website
https://georgestagg.github.io/webgl_gpe/

# Targeted Improvements for this fork:
- spawning arbitrary vortices with arbitrary angular momentum and velocity
- adding persitent static obstacles

currently added functions:
> gpe.drawbox(x,y,z) <x coordinate, y coordinate, radius>
> gpe.spawnvortex(x,y,x) <x coordinate, y coordinate, polarity>
> > The third component here determines the spin of the vortex at -1 and 1, otherwise it does not spawn a vortex
