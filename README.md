# Build a traffic light with Arduino

[![Open in MATLAB Online](https://www.mathworks.com/images/responsive/global/open-in-matlab-online.svg)](https://matlab.mathworks.com/open/github/v1?repo=mathworks/Build-a-Traffic-Light-with-Arduino&file=README.mlx)

<img width="444" height="249" alt="image" src="https://github.com/user-attachments/assets/bc26b708-e26c-4d30-8f77-5a4911f5f1ae"/> <img width="200" height="249" alt="image" src="https://github.com/user-attachments/assets/a7c387f3-942f-407a-ba16-e290c0b5987d" />

This repository provides two hands-on MATLAB Live Scripts and starter Simulink models, designed to teach students how to model a traffic light as a state machine in Stateflow and Simulink. In the first set, the Live Script and accompanying starter Simulink model guides students through building a model of a traffic light only, demonstrating key Stateflow concepts. In the second set, the Live Script and accompanying starter model guide students through deploying the traffic light model on an Arduino board, using LEDs to represent traffic light bulbs. This interactive, hands-on activity provides students with an opportunity to practice embedded programming skills and code generation with MATLAB and Simulink.

## Set-up
**Required MathWorks® Products (https://www.mathworks.com)**

Requires MATLAB release R2025b or newer
- [MATLAB](https://www.mathworks.com/products/matlab.html)
- [Simulink](https://www.mathworks.com/products/simulink.html)
- [Stateflow®](https://www.mathworks.com/products/stateflow.html)
- [Simulink Support Package for Arduino Hardware](https://www.mathworks.com/matlabcentral/fileexchange/40312-simulink-support-package-for-arduino-hardware?s_tid=FX_rc1_behav)

**Required Hardware for Arduino deployment**
- Arduino Board (Uno or Mega)
- USB Type A to B cable (Arduino to computer connection)
- Small breadboard
- 3 220 Ohm resistoers
- 3 LEDs (ideally in traffic light colors)
- Connecting wires

## Instructions

1. Open this repository in MATLAB Online, or clone and download this repository to your local machine and open in MATLAB.
2. Install the Simulink Support Package for Arduino Hardware in MATLAB.
3. Connect your Arduino board to your computer via USB.
4. From the "Model Only" folder, open the "TrafficLight_Model_Instructions.mlx" Live Script to follow the step by step instructions.
5. Modify and run the "traffic_start.slx" starter Simulink model.
6. If needed, review the completed version of the model in "traffic.slx".
7. From the "Implement Model Arduino" folder, open the "Traffic_Light_Arduino_Instructions.mlx" Live Script to follow the step by step instructions.
8. Modify the "traffic_arduino_start.slx" starter Simulink model. Wire up the Arduino board to LEDs as instructed in the Live Script. Follow instructions to deploy the Simulink model on the Arduino board conneected to LEDs.
9. If needed, review the completed version of the model in "traffic_arduino.slx".

## License

The license is available in the License.txt file in this GitHub repository.

## Community Support

[MATLAB Central](https://www.mathworks.com/matlabcentral/)

Copyright 2025 The MathWorks, Inc.
