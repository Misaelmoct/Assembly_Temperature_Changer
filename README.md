# Assembly_Temperature_Changer
This is a program for changing temperature between Celsius, Fahrenheit and Kelvin build in IAR Embedded Workbench using Assembly for a MSP430FR6989 Microcontroller.
This project was part of the course CIIC4082 - Computer Arquitecture 2 at the University of Puerto Rico Mayaguez.



## How to use it:



### "TMPCHG" Start Menu:  
<br>

*"TMPCHG" will be displayed on screen to indicate the start of the program.*  

![image](https://user-images.githubusercontent.com/70610617/188250840-7609e91e-644d-4d02-a76c-cdd6a3090327.png)
   
1. Press the S1 Button repeatedly to cycle through the names of each member of the team.  
2. After the LCD displays one of the names, press the S2 button to enter the FROM menu.  
<br>
<br>



### "FROM" Menu:   

![image](https://user-images.githubusercontent.com/70610617/188250859-5be3e025-e30e-4506-8bd1-d6a021ca1f92.png)


1. Press the S1 button repeatedly to cycle through the 3 temperature units. F for Fahrenheit , C for Celsius, and K for Kelvin.  
2. Press  the S2 button to confirm the temperature unit  selection and move on to the TO menu.
<br>
<br>



### "TO" Menu:

![image](https://user-images.githubusercontent.com/70610617/188250864-13f57089-2fe0-4ec1-80d3-4c0c4b5a3a38.png)

1. Press the S1 button repeatedly to cycle through the remaining temperature units. For example, if F was selected in the FROM menu only C and K will appear as available options in the TO menu.  
2. Press the S2 button to confirm selection and move on to the TMP Input menu.  
<br>
<br>



### Temperature Input menu:
*Values in the Input menu are selected from left to right.*  

1. For Celsius and Fahrenheit temperature units, press the S1 button to cycle through negative symbol (-) and no symbol for nonnegative.  
2. Then press the S2 button to confirm whether the value is negative or nonnegative. NOTE: for Kelvin temperature units the value is always positive therefore there is no sign selection.  
3.  Press the S1 button to cycle through values from 0 to 9. Press the S2 button to confirm selection and move on to the next digit to the right.  
4. Repeat the previous step until the final digit is confirmed.  
<br>
<br>



### Result Display Menu:
*The conversion result will be displayed on screen.*  

1. Press the S1 or S2 button to return to the From menu.  

