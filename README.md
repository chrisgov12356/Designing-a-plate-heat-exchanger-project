# Designing-a-plate-heat-exchanger-project
In this work, we revisit a hand-calculated plate heat exchanger sizing for heating up a miscella from 10℃ to 70℃. We will go a step further by doing a sensitivity analysis.
Initial model will attempt to confirm predicted success in heating the mixture to the target temperature using the previously-calculated heat exchanger parameters. Next step will include a sensitivity analysis which can be used to determine robustness of the heat exchanger design by modeling the outcome of the unit operation when certain input variables are changed (e.g. oil:hexane ration in input stream, adding or removing plates, changing flow rates).

*Inputs:*
  - Micellar composition​
    - Oil / hexane​
    - Oil chain length? Type? Properties?​
  - Corrugation​
  - Dimensions​
  - Flow rate​
  - Input pressure​
  - Metal properties

*Relevant Physics:*
  - Diffusion​
  - Heat capacity​
  - Conduction​
  - Convection​
  - Fluid dynamics​
  - Heat exchange correlations

*Outputs:*
  - Temperatures​
  - Flow rates​
  - Phase separation​ (to be avoided; will enter flash tank in next step)​
  - Pressure drop across heat exchanger​
  - Pumping cost​
  - Heating cost


**Model #1**
Confirming design of plate-and-frame heat exchanger.

Locked-in parameters/assumptions:
  - Oil content = 7 wt% in incoming stream
  - Incoming stream starts at temperature of 10 degrees C
  - Outgoing stream will reach 70 degrees C
  - Heating fluid is water entering the heat exchanger at 90 degrees C
  - Plate material will not be changed (we will define the plate material to be either Duplex 2205 or 316L SS)
  - No phase change will occur (both oil and hexane remain liquid inside heat exchanger; subsequent step is a flash tank in which the hexane will vaporize)
  - For simplicity heat exchanger is assumed to be well-insulated, therefore no heat is lost to the surrounding environment
​​


**Model #2**
Sensitivity analysis to determine robustness of heat exchanger design.

Locked-in parameters/assumptions:
  - Plate material will not be changed (we will define the plate material to be either Duplex 2205 or 316L SS)
  - No phase change will occur (both oil and hexane remain liquid inside heat exchanger; subsequent step is a flash tank in which the hexane will vaporize)
  - For simplicity heat exchanger is assumed to be well-insulated, therefore no heat is lost to the surrounding environment

Variable parameters/conditions:
  - Oil content in incoming stream (fluctuating > and < 7 wt%)
  - Starting temperature of incoming stream
  - Starting temperature of heating medium (hot water)
  - Flow rate of oil/hexane stream through heat exchanger
  - Flow rate of hot water through heat exchanger
  - Number of plates used
​​​
