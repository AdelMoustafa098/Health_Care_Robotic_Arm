# Health_Care_Rootic_Arm
This is my graduation project from Systems and Biomedical Engineering, Cairo University, 2021 Class 

# Overview
The purpose of this project was to build a fully controlled robotic arm that could reduce the risk of infectious disease transmission especially coronavirus to frontline medical staff by making them able to perform their tasks such as measuring vital signs without being at a close distance from the patients. Methods: A humanoid right robotic arm from plywood sheets consisted of four links of different lengths. The healthcare robotic arm had four Degrees of Freedom (DOF). The total arm length was 60 cm with four continuous servo motors. We simulated the arm by AUTOCAD at first to test the mechanism capabilities. We inserted XYZ point of the position we wanted the arm to move. Using inverse kinematics in MATLAB simulation, we got some angles. We converted the resultant angles into Pulse Width Modulation (PWM) by using an excel sheet to map the angles into PWM. The motors stopped at the wanted position using bang-bang control. Results: The arm could reach any inserted point within the range of the DOF. Conclusion: In summary, we built a fully controlled prototype for a humanoid robotic arm to assist the medical staff. Significance: The proposed robotic system can help all medical staff in fighting against the outbreak of the coronavirus by protecting them from infection, thus reducing the burden on them and protecting them from the virus.

# Files Description   
A detailed description of the project can be found in the following files     
1. Design.pdf -> Contains the design of the robotic arm.
2. ik4dof.m -> MATLAB code, which is used to simulate the arm movements and calculates the angle of movement of each servo motor.
3. servo_motors.ino -> code used for STM32 microcontroller to control and move servomotors to the given position. 
4. Paper.pdf -> paper of our graduation project.
5. Report.pdf -> detailed description of our project.

# Tools
- MATLAB
- STM32F103C8T6
- 4 large servomotors with magnetic encoder 
- magnetic encoder
- temperature sensor 
- power supply
- I2C motor driver
- Arduino IDE

# Demo
You can view a demo of the project by clicking [here](https://youtu.be/o14xiIMUBvY).
