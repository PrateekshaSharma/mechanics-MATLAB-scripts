# Beam-deflection-curve
This MATLAB script calculates and plots the deflection curve of a simply supported beam under a central point load using classical beam theory.
Formula used:δ(x)=48EIP⋅x(L3−2Lx2+x3)​
P = applied load
L = span length
E = Young’s modulus
I = moment of inertia

The code:
Takes material and geometry inputs (E, I, span, load)
Discretizes the beam along its length
Plots the deflection curve in mm
