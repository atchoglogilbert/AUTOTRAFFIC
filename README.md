# AUTOTRAFFICSIM
Developing a Simulink application that simulates autonomous vehicles navigating through urban traffic scenarios. This project will cover key topics from Simulink Onramp, providing hands-on experience in modeling, simulating, and analyzing complex systems.

** Drag dynamics, why sine wave, cruise control and modelling, signals & systems inc. moving average filter, why 1rad/sec, shortcuts and accessibility, relation replication of logical

For example, how would you output any negative values of the sine wave as zero (a half-wave rectifier)? What about outputting any negative values as positive (a full-wave rectifier)?

states in dymisci systems, sample time delay unit

laplace

why always set intial condition in integrator


Simulink enables you to model different kinds of systems easily using the same processes you just learned. Check out the documentation for more examples.
 
For instance, you can model systems with many degrees-of-freedom, like this half-car suspension model, or nonlinear systems, such as this friction model with hard stops.


When Simulink runs a simulation, it numerically solves the dynamic equations represented in the model. Characteristics of dynamic systems can vary widely; for example, they can be discrete, continuous, fast, or slow. To account for this, Simulink includes many types of numerical solvers.


u've modeled a discrete, proportional-integral controller in Simulink! Try changing the values of K
p
,K
i
, and T
s
 and see how they affect the controller output.
