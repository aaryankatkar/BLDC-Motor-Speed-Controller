# BLDC-Motor-Speed-Controller
# 🚗 BLDC Motor Speed Controller using MATLAB/Simulink

![MATLAB](https://img.shields.io/badge/MATLAB-Simulink-orange)
![Project](https://img.shields.io/badge/Project-BLDC%20Motor-blue)
![EV Tech](https://img.shields.io/badge/Field-Electric%20Vehicles-blue)

## 📌 Project Overview
This project focuses on designing and simulating a BLDC motor speed control system using MATLAB/Simulink.

## ⚡ Working Principle
The BLDC motor speed is controlled using a closed-loop control system.

- The reference speed is compared with actual speed  
- Error is fed into a PID controller  
- PID output controls MOSFET switching  
- This regulates motor speed efficiently  

The system ensures stable operation with minimal overshoot and steady-state error.

## ⚙️ Features
- Complete BLDC motor model
- Speed control mechanism
- Performance analysis using waveforms

## 📊 Outputs
- Speed vs Time graph
- Torque characteristics
- Voltage/current analysis

## 🛠 Tools Used
- MATLAB
- Simulink

## 📈 Results

- The motor successfully reaches the desired reference speed
- Smooth speed response observed with minimal overshoot
- Stable torque characteristics under varying conditions
- PID controller effectively reduces steady-state error

## 🎯 Learning Outcome
- Understanding of EV motor control systems
- Hands-on experience in simulation and control design


## 📝 Resources
📁 Simulink Model (.slx file):
Download here: [BLDC.zip](https://github.com/user-attachments/files/26251368/BLDC.zip)

🎥 Project Workflow Video:
Watch here: https://github.com/user-attachments/assets/660f9d6a-f7af-4795-8518-7c244d936f6a

### 🔌BLDC Motor Circuit : 
<img width="1920" height="1080" alt="Screenshot 2026-01-29 213752" src="https://github.com/user-attachments/assets/35cebad8-18cc-4165-bc19-e2119fb536ee" />

### 🔌PID Controller Circuit : 
<img width="1920" height="1080" alt="Screenshot 2026-01-29 213832" src="https://github.com/user-attachments/assets/a032b03d-6a58-40a6-a9b5-c207c6994f25" />

### 🔌Voltage Measurement (Scope) : 
<img width="1920" height="1080" alt="Screenshot 2026-01-29 212953" src="https://github.com/user-attachments/assets/580c17a6-4391-4931-9fa2-f3e4efc89dbf" />

### 🔌Gain Scope (Scope1) : 
<img width="1920" height="1080" alt="Screenshot 2026-01-29 213037" src="https://github.com/user-attachments/assets/5c57e56f-39f0-484c-8688-491329fc352f" />

### 🔌Electromagnetic Torque Te (N*m) (Scope2) : 
<img width="1920" height="1080" alt="Screenshot 2026-01-29 213052" src="https://github.com/user-attachments/assets/f2078098-58f0-4728-9928-f239ddb34bb8" />

### 🔌Stator current _a, _b, _c (Scope3) : 
<img width="1920" height="1080" alt="Screenshot 2026-01-29 213014" src="https://github.com/user-attachments/assets/07b334f3-8199-499d-8717-010524f5efbb" />

### 🔌PID Controller (Scope4) : 
<img width="1920" height="1080" alt="Screenshot 2026-01-29 212933" src="https://github.com/user-attachments/assets/03cd877c-44ab-4d4a-a49d-62d30985eb0e" />

### 🔌Mosfet Controller (AT, AB, BT, BB, CT, CB) (Scope5) : 
<img width="1920" height="1080" alt="Screenshot 2026-01-29 213127" src="https://github.com/user-attachments/assets/48489e78-4625-4804-9bdd-6bc1572d99f7" />

## ▶️ How to Run the Project

1. Download the .zip file from Resources
2. Extract the Simulink (.slx) file
3. Open it in MATLAB/Simulink
4. Run the simulation
5. Observe outputs in scope blocks

## 🚀 Future Scope

- Implementation on real hardware using microcontroller
- Integration with Electric Vehicle drivetrain systems
- Optimization using advanced control techniques (Fuzzy Logic, AI)
- Real-time monitoring using IoT

## 🔗 Connect with me
[LinkedIn](https://www.linkedin.com/in/aaryankatkar)
