# MPC-for-LunarLander

A simulation is created in Julia to apply ModelPredictive Control to a lunar lander. The dynamics included in the simulation are vertical and horizontal positions and velocities,as well as a rotation of the lander. Real world tuning parameterswere found and scaled down to values that would allow for fasterconvergence. This work successfully randomizes an initial statewithin the vicinity of a landing pad and accomplishes the taskof landing the lunar lander safely on the pad, which works forall tested cases.
