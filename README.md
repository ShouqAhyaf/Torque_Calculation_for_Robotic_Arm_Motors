# Torque Calculation for Robotic Arm Motors
The required torque for each joint of the robotic arm was calculated using appropriate physical equations. Based on the calculated values, suitable motors were selected to ensure balanced and safe performance of the robot.

## Given Data:
Arm Lengths:
- First arm: 0.15 m
- Second arm: 0.10 m
- Third arm: 0.04 m

Hanging Weight: 1 kg

Gravitational Acceleration: 9.81 m/s

## Step 1: Calculate the Force (F)
![image](https://github.com/user-attachments/assets/98520db3-fcd4-419a-abc0-1575ad8a12d9)

## Step 2: Calculate Torque for Each Joint
Use the formula:

![image](https://github.com/user-attachments/assets/07ae6306-8799-4c0d-849f-ced37ea53273)

Joint 1 (Base):

![image](https://github.com/user-attachments/assets/4ce7742a-c87b-4567-9173-6daea68bf80a)

Joint 2 (Middle):

![image](https://github.com/user-attachments/assets/1ea35db9-1284-4ded-a1ed-301e7464d20d)

Joint 3 (End-Effector):

![image](https://github.com/user-attachments/assets/2d15b266-6f45-4d13-b4cc-7d0bf8dfb682)


## Step 3: Select Motors
Joint 1: Motor with torque > 2.84 N.m

Joint 2: Motor with torque > 1.37 N.m

Joint 3: Motor with torque > 0.39 N.m

### Suggested Motors:
Joint 3: MG996R Servo Motor (9.4 N.m)

Joints 1 & 2: Higher torque motors based on calculated values.


## Purchase Links
- [MG996R Servo Motor on Amazon](https://www.amazon.com/s?k=MG996R)
- [High Torque Servo Motors](https://www.amazon.com/s?k=high+torque+servo+motor)
