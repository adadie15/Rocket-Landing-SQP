# Rocket-Landing-SQP
Rocket vertical landing project with trajectory optimization and control barrier functions.

![Rocket Landing](https://andrewadie.com/wp-content/uploads/2026/05/Autonomous_Rocket_Landing.gif)

Vertical landing for reusable rockets has the potential to save to reduce launch costs by up to 85 percent. This project simulates an optimzation method (Sequential Quadratic Programming) to achieve this soft, vertical landing autonomously. SQP is a time-varying linearization (LTV) technique that enables rapid convext optimization solutions.

Future Improvements:
- Implement fuel use constraints
- Model to produce good warmstarts for the trajectory optimizer
- Improve the trajectory optimizer to be robust to wind disturbances
- Using a more complex rocket model.
- Incorporate more complex constraints, like state-triggered constraints, signal temporal logic constraints, state-dependent control constraints.
- Apply CBF / CLF filters

> *Adapted from coursework in University of Washington's mulivariable linear controls course.*
