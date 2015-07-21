FPU Simulation, by Andrew Barrette

This program demonstrates the famous FPU result, which is that a slightly nonlinear system can exhibit periodic, rather than ergodic, bahavior. Simply run fpusim.exe. You'll see the evolution of two vibrating strings. The red string exhibits no nonlinearity (i.e. points on the string are only affected by adjascent points). The white string exhibits slight nonlinearity. After a few seconds, you should see the asymmetric sawtooth-esque periodic behavior of the nonlinear string.

CONTROLS:
=/-	Zoom in/out, respectively
arrows	Move side to side or up and down
p	Pause simulation

BUGS:
After a minute or so, the program will freeze. I haven't figured out why this happens, but I suspect it has something to do with the fact that the amplitude of the string oscillations gets larger and larger over time.