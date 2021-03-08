# Fault diagnosis via Neural ODE

This in an hydrib approach for fault diagnosis, using model and data-based methods combined, that enables to combine a natural deep learning technique with an estimated model of the system, making the training simpler and more efficient. For evaluation of this methodology, a nonlinear benchmark system is used by simulation of faults in actuators, sensors, and process. 
We embedded a preliminary plant model in the Neural ODE network; this network receives the measurements and inputs of the plant, given in state-space representation, and mirrors its corresponding dynamics. The training is performed in two phases; the Neural ODE (Chen 2019) is trained in the first stage in order to mimic the plant dynamics, and later it is conditioned to be used for the fault diagnosis system, which is trained in the second stage. 

