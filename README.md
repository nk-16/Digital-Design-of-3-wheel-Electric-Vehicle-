# Digital-Design-of-3-wheel-Electric-Vehicle-
Project under Team Trinity, SAE Collegiate Club, IIT(BHU) for EnCode Competition, UDGAM 2023. This is based on design, hand-in calculation, and validation of hand-in calculation through MATLAB. My Team Trinity, won first place in the EV segment of the EnCode Competition.

* **Designing** - I contributed to skateboard chassis design in SOLIDWORKS. Since this is an innovation in the chassis of EVs, we go ahead with this.

![image](https://github.com/nk-16/Digital-Design-of-3-wheel-Electric-Vehicle-/assets/128499808/e364cb34-5e93-4cfd-9437-e42f54591911)

I also designed an eDrive showing all components and the flow between them.

![image](https://github.com/nk-16/Digital-Design-of-3-wheel-Electric-Vehicle-/assets/128499808/40ebc530-bc39-4ce6-8c5e-7d4280f0b8cd)

* **Hand-in calculation** - I did hand-in calculations for motor capacity and did a literature survey to find valid equations and parameters upon which motor capacity will depend. The results of my calculations are as follows:-

For 100 kmph
*  Rolling resistance power = 5.71 kW
*  Aerodynamic resistance power = 9.66 kW
*  Tolerance(including gradient resistance power) = 4.63kW
*  Total Power = 20kW
  
For 60 kmph
*  Rolling resistance power = 3.43 kW
*  Aerodynamic resistance power = 2.08 kW
*  Tolerance(including gradient resistance power) = 0.49 kW
*  Functional Power = 6 kW

Reference - https://ieeexplore.ieee.org/document/9106538

* **Validation** -  We used MATLAB and Simulink to validate hand-in calculations. We made a model of a 3-wheel EV with our specifications, and then we observed plots such as torque and acceleration plots.

<div align="center">
  <img src="https://github.com/nk-16/Digital-Design-of-3-wheel-Electric-Vehicle-/assets/128499808/f95d6b1a-21ab-47ca-9a43-0c199ed4a39a" alt="Image 2" width="800"/>
    <p>Torque vs Time plot</p>
</div>


