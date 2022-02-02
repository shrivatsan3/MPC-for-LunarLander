# MPC-for-LunarLander

A simulation is created in Julia to apply ModelPredictive Control to a lunar lander. The dynamics included in the simulation are vertical and horizontal positions and velocities, as well as a rotation of the lander. Real world tuning parameters were found and scaled down to values that would allow for faster convergence. This work successfully randomizes an initial state within the vicinity of a landing pad and accomplishes the task of landing the lunar lander safely on the pad, which works for all tested cases.
