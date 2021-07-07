# Introduction
Hello There! 
I'm an Aerospace/Aeronautical Engineering Students currently diving too much time in MATLAB With further intrest in Java and Phyton.<br>
As this is my second time uploading my works to GitHub, Please do forgive me for doing something wrong.<br>
Further Feedback is welcomed as i dont get one from my proffesor.<br>

# Story Behind this Program
Coming from the last repositories of heat conduction 1D equation and easily implemented into wave equation by changing the General solution and CN.<br>
Further addition for CN forming as it usually have more than one initial conditions. <br>

# What can this program do
- Calculating the temperature for one dimensional heat conduction with each end are fixed With the equations below<br>
  <img src = "https://github.com/mluckyw/AN_wave_eq_1D/blob/main/Wave_Equation_Homogeneous_test_run/General_equation.PNG" /><br>
  <img src = "https://github.com/mluckyw/AN_wave_eq_1D/blob/main/Wave_Equation_Homogeneous_test_run/Cn_value.PNG" /><br>
- With input at the command window such as :<br>
  - String length<br>
  - Order of Fourier Series<br>
  - (a) constant as a function from periode<br>
  - Step of iteration in the string<br>
  - Initial condition (Polynominal or constant) with separation for each section<br>
  - Time elapsed<br>
- With Output of : <br>
  - Cn Variable and General Equation of U(x,t)<br>
  - Velocity Distribution across the wave<br>
  - Plotting the Velocity based on order and time categorizations<br>
  <p align = "center"> Velocity Plotting from V1.0 <p/>
  <p align = "center"> Grouping based on Time input <p/>
  <img src = "https://github.com/mluckyw/AN_wave_eq_1D/blob/main/Wave_Equation_Homogeneous_test_run/Wave_Equation_Homogeneous_1D_V1_0_Time_Based.jpg" />
  <p align = "center"> Grouping based on Order input  <p/>
  <img src = "https://github.com/mluckyw/AN_wave_eq_1D/blob/main/Wave_Equation_Homogeneous_test_run/Wave_Equation_Homogeneous_1D_V1_0_Order_Based.jpg" />

# What this program does not do (yet)
- Calculating the temperature for one dimensional wave equation with each/one end is a non fixed boundaries (Non - Homogeneous)<br>

# What's The difference in difference version? <br>
This program has only one version as it is derived from the 2.0 heat conduction with significatly faster computing time.<br>
- Version 1.0 <br>
  - Computation of Velocity are splitted into two loops with Cn and U(x,t) separated by using Matlab int function for Cn at each desired section of initial conditons<br>
  - Displaying equation for Cn and U(x,t) in the command window<br>
  - Computational is unlimited with as much as user input for order count and time elapsed (Though only debugged at max 3 each)<br>
  - Plotting Based on categorization of order and time elapsed<br>

# Disclaimer
- If you are using this code to do a calculation i did not held any responsiblility of any wrong data outputs that may affected you (altough Feedback is very much welcomed)<br>
- This is copyrighted by using MIT license with the details in the license file<br>
