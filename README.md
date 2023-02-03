# Robotic_Arm_Real_Time_Control_Matlab_GUI
Real Time simulation of a Robotic Arm Using Solidworks For Conception And Matlab Simulink Simscape for Simulation
<center>

[<img src = "imgs-ReadMe/Win.png" alt = "On how to install proTeXt" width="50" height="50">](https://www.tug.org/protext/)				[<img src = "imgs-ReadMe/Linux.jpeg" alt = "On how to install TeX Live" width="40" height="50">](https://www.tug.org/texlive/)				[<img src = "imgs-ReadMe/Mac.jpeg" alt = "On how to install Mac TeX" width="50" height="50">](https://www.tug.org/mactex/)

</center>
## Main Flow

This section shows the main steps I followed to achieve the goal.

   - first use solidworks to draw the links then assemble them together.
   - Install matlab simulink third guide to solve forward 
   - use solidworks to export robot.xml file.
   In matlab at the command window smimport('robot6dof.xml').
 finally create 6dof robot interface control.

   - Adapt The simulink slx file to what you need
  - finally create 6dof robot interface control.



## Requirements
1. [MATLAB](https://mathworks.com/products/matlab.html) (tested with r2018A and r2019A)
1. [MATLAB GUI](https://mathworks.com/products/matlab.html) (tested with r2018A and r2019A)
2. [Simulink](https://mathworks.com/products/simulink.html)
3. [Simscape](https://mathworks.com/products/simscape.html) 
4. [Simscape Multibody](https://mathworks.com/products/simmechanics.html)

5. [SW-Simscape-Multibody-Link-Plugin]

6. [SolidWorks]

Hello everyone in this video I would like to introduce to you to use Matlab simulink + solidworks to simulate 6 dof robot forward kinematics.
first use solidworks to draw the links then assemble them together.
 second guide to install matlab simulink third guide to solve forward kinematics problem. fourth use solidworks to export robot6dof.xml file.
In matlab at the command window smimport('robot6dof.xml').
 finally create 6dof robot interface control.

 so to do this first we will model our robot using Solidworks and we export the model into Matlab using Simscape multibody link so that we can build the control algorithm and simulate the real behavior of the robot