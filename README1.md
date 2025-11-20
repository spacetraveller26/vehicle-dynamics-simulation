**Vehicle Motion Simulation: Acceleration, Velocity, and Distance Model:**



It models the relationship between:

* Acceleration
* Velocity
* Distance (Displacement)



based on simple kinematic equations and a power-based driving force model.



**Project Overview**



The goal of this project is to simulate how a vehicle accelerates from rest using:



* Engine power
* Rolling resistance
* Aerodynamic drag
* Newton’s laws of motion



The model calculates:



* Acceleration at each time step
* Velocity by integrating acceleration
* Distance by integrating velocity



This creates a simple but realistic representation of how a car picks up speed.



**What the Simulation Outputs**



The program generates:



* Acceleration vs Time graph
* Velocity vs Time graph (0–100 km/h)
* Distance vs Time graph



These graphs help visualize how the vehicle’s motion evolves over time.

**Physics Used:

1. Driving Force:**

F\_drive = P / v



2\. Resistive Forces:



* Rolling resistance:

&nbsp;	F\_rr = m \* g \* Crr

* Aerodynamic drag:

&nbsp;	F\_drag = 0.5 \* ρ \* Cd \* A \* v²



3\. Net Force \& Acceleration:

F\_net = F\_drive - F\_drag - F\_rr

a = F\_net / m



4\. Euler Integration:

v\_new = v\_old + a \* dt

s\_new = s\_old + v\_old \* dt





**Conclusion**



This simulation forms the foundation of a full automotive dynamics model.

Even with only kinematic modeling, it shows:



* How a car accelerates
* Why acceleration decreases with speed
* How distance builds over time



This project demonstrates early engineering thinking and is a great start toward automotive studies.



