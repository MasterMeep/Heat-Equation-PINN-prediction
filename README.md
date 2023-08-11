# Heat-Equation-PINN-prediction
using a PINN architecture, this model generates a predicted solution of the heat equation over a timeframe

used heat equation ${\displaystyle {\frac {\partial u}{\partial t}}=\alpha \left({\frac {\partial ^{2}u}{\partial x^{2}}}\right)}$

epochs per example: 15000

thermal diffusivity: 0.8

timeframe: 2

# Gaussian initial condition, 0-degree boundary conditions

2d version:

![image](https://github.com/MasterMeep/Heat-Equation-PINN-prediction/assets/51376656/79078922-452b-42c5-ab52-a592fd6e6b1a)

3d version:

![image](https://github.com/MasterMeep/Heat-Equation-PINN-prediction/assets/51376656/dcaed8a3-c26a-4d98-b115-b6001f94f7fc)

input boundary and initial conditions

![image](https://github.com/MasterMeep/Heat-Equation-PINN-prediction/assets/51376656/5056a07d-b1e2-4666-b081-66447da98624)

# Step function initial condition, maintained temp boundary conditions (half +10°, half -10°)

![image](https://github.com/MasterMeep/Heat-Equation-PINN-prediction/assets/51376656/798b3c15-deb3-4d76-a8dd-0b7c136c7605)

input boundary and initial conditions

![image](https://github.com/MasterMeep/Heat-Equation-PINN-prediction/assets/51376656/6d3261db-44e8-4e03-b844-bffc840540d7)
