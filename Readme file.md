Here’s your updated project description with the addition of using an HMI:

---

# PID Control System for Liquid Level Simulation

## Project Overview  
This project focuses on implementing a PID (Proportional-Integral-Derivative) control system to regulate the liquid level in a tank. We used Siemens TIA Portal and Factory I/O to simulate and test our control system.

## Key Features  
- **PID Compact Block:** We used the PID Compact block available in TIA Portal to implement our control algorithm, tuning it for optimal system response.  
- **Simulation in Factory I/O:** To mimic real-world industrial applications, we created a liquid level system simulation in Factory I/O, allowing us to test and analyze the PID controller before real-world implementation.  
- **Integration with TIA Portal:** The control logic was developed and tested within TIA Portal, where we configured the PID controller to maintain a stable liquid level.  
- **Human-Machine Interface (HMI):** An HMI was used to provide real-time monitoring and manual adjustment of the liquid level setpoint. This interface allows operators to visualize the current liquid level, adjust setpoints, and observe system performance through intuitive graphical elements.  
- **Fine-Tuning and Optimization:** We adjusted the PID parameters (proportional, integral, and derivative gains) to achieve a smooth and responsive control system without excessive overshoot or delay.  

## How It Works  
1. The liquid level in the tank is monitored using a simulated sensor in Factory I/O.  
2. The PID Compact block in TIA Portal processes the sensor input and adjusts the control output to maintain the desired setpoint.  
3. The HMI provides a user-friendly interface to visualize the tank's current liquid level and adjust the desired setpoint as needed.  
4. The system continuously adapts to changes, ensuring precise liquid level control.  
5. The simulation allowed us to validate the PID tuning and performance before applying it to a real-world scenario.

## Tools Used  
- **Siemens TIA Portal** (for PLC programming and PID control implementation)  
- **Factory I/O** (for creating and running the liquid level system simulation)  
- **HMI** (for real-time monitoring and manual control of the system via a graphical user interface)

## Conclusion  
This project provided hands-on experience in designing and tuning a PID controller for a liquid level system. By integrating simulation in Factory I/O, the PID Compact block in TIA Portal, and an HMI for real-time monitoring, we were able to test and refine our control strategy efficiently before real-world deployment.



