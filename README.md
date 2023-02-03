# Robotic_Arm_Real_Time_Control_Matlab_GUI
Real Time simulation of a Robotic Arm Using Solidworks For Conception And Matlab Simulink Simscape for Simulation

Using Matlab simulink + solidworks to simulate 7 dof robot forward kinematics
<center>
<img src="https://github.com/ingeniously/Robotic_Arm_Real_Time_Control_Usin_Matlab_GUI/blob/main/Overview/SolidWorks-Logo.png?raw=true" alt="MarineGEO circle logo" style="height: 200px; width:200px;"/>
<img
src="https://github.com/ingeniously/Robotic_Arm_Real_Time_Control_Usin_Matlab_GUI/blob/main/Overview/LOGO-matlab.jpg?raw=true?raw=true?raw=true" alt="MarineGEO circle logo" style="height: 200px; width:200px;"/>		
</center>

## Main Flow


This section shows the main steps I followed to achieve the goal.

   - first use solidworks to draw the links then assemble them together.
   - Install matlab simulink third guide to solve forward 
   - use solidworks to export robot.xml file.
  
         In matlab at the command window smimport('robot6dof.xml').
 

  - Adapt The simulink slx file to what you need
  - finally create  robot interface control in matlab Grphical User Interface.



## Requirements
1. [MATLAB](https://mathworks.com/products/matlab.html) (tested with r2018A and r2019A)
1. [MATLAB GUI](https://mathworks.com/products/matlab.html) (tested with r2018A and r2019A)
2. [Simulink](https://mathworks.com/products/simulink.html)
3. [Simscape](https://mathworks.com/products/simscape.html) 
4. [Simscape Multibody](https://mathworks.com/products/simmechanics.html)

5. [SW-Simscape-Multibody-Link-Plugin](https://ch.mathworks.com/help/smlink/ug/installing-and-linking-simmechanics-link-software.html)

6. [SolidWorks](https://www.solidworks.com/fr/support/free-downloads/)




