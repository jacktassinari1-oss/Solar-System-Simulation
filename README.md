# 🪐 High-Fidelity Solar System N-Body Simulation

A mathematically accurate, 3D interactive simulation of the Solar System built in Python. 

Unlike basic orbital simulators that assume planets move in perfect circles around a stationary Sun, this simulation uses a Full N-Body Newtonian Gravity model. Every celestial body exerts a gravitational pull on every other body. The differential equations are integrated using a Symplectic Velocity Verlet algorithm to ensure energy and momentum are mathematically conserved over time.

 Features
* Real-time 3D rendering via WebGL (VPython)
* Dynamic camera tracking (snap to any planet)
* Dropdown UI to easily locate outer planets like Uranus and Neptune
* Solar System Barycenter momentum correction
* Accurate relative masses, starting positions, and velocities
