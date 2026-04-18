# Electric-Machines-PID-vs-FUZZY-controller-in-PMSM-motor

#  PMSM Speed Control using PID and Fuzzy Logic Controller

##  Overview
This project presents the design, simulation, and comparative analysis of **PID** and **Fuzzy Logic Controllers (FLC)** for the speed control of a **Permanent Magnet Synchronous Motor (PMSM)**.  
The system is modeled and simulated in MATLAB/Simulink to evaluate performance under varying load conditions.

---

##  Objectives
- Design a PMSM speed control system
- Implement PID and Fuzzy Logic Controllers
- Compare performance based on:
  - Rise Time
  - Settling Time
  - Overshoot
  - Disturbance Rejection
- Analyze system behavior under load torque variations

---

##  Tools & Technologies
- MATLAB
- Simulink
- Fuzzy Logic Toolbox

---

##  System Description
The PMSM is modeled using its mechanical equation:

ω(s) / T(s) = 1 / (Js + B)

Where:
- J = Moment of inertia  
- B = Damping coefficient  

Two controllers are implemented:
- **PID Controller** – classical control method
- **Fuzzy Logic Controller** – rule-based intelligent control

---

##  Fuzzy Controller Design
- Inputs: Error (e), Change in Error (Δe)
- Output: Control Torque
- Membership Functions: NB, NS, Z, PS, PB
- Rule Base: 25 IF-THEN rules

---

##  Simulation Details
- Platform: MATLAB/Simulink
- Load Disturbances Applied:
  - 20 Nm at 0.2 s  
  - 25 Nm at 0.4 s  
  - 30 Nm at 0.6 s  

---

##  Results
- Fuzzy controller shows:
  - Faster response  
  - Reduced overshoot  
  - Better disturbance rejection  
- PID controller shows:
  - Slower recovery  
  - Larger speed dips under load  

---

##  Conclusion
The fuzzy logic controller outperforms the PID controller in handling nonlinearities and load disturbances, making it more suitable for PMSM speed control applications.

---

##  Repository Contents
- Simulink Models (.slx)
- MATLAB Files (.m)
- Fuzzy Logic Files (.fis)
- Project Report / Paper
- Result Graphs

---

##  Future Scope
- Implementation on real hardware
- Adaptive or hybrid control techniques
- Optimization using AI/ML methods

---

##  Author
Keerthi Kamineni 

---

##  License
This project is for academic and educational purposes.
