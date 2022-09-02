# Assembly_Temperature_Changer
This is a program for changing temperature between Celsius, Fahrenheit and Kelvin build using Assembly for a MSP430FR6989 Microcontroller.


## How to use it:

### "TMPCHG" Start Menu:

*"TMPCHG" will be displayed on screen to indicate the start of the program.*  

1. Press the S1 Button repeatedly to cycle through the names of each member of the team.  
2. After the LCD displays one of the names, press the S2 button to enter the FROM menu.  


Figure 2: TMPCHG Start Menu(left) Name Display(Right)
### "FROM" Menu:

1. Press the S1 button repeatedly to cycle through the 3 temperature units. F for Fahrenheit , C for Celsius, and K for Kelvin.  
2. Press  the S2 button to confirm the temperature unit  selection and move on to the TO menu.


### "TO" Menu:

1. Press the S1 button repeatedly to cycle through the remaining temperature units. For example, if F was selected in the FROM menu only C and K will appear as available options in the TO menu.  
2. Press the S2 button to confirm selection and move on to the TMP Input menu.  


Figure 3: FROM Menu(left) TO Menu(right)
### Temperature Input menu:
*Values in the Input menu are selected from left to right.*  

1. For Celsius and Fahrenheit temperature units, press the S1 button to cycle through negative symbol (-) and no symbol for nonnegative.  
2. Then press the S2 button to confirm whether the value is negative or nonnegative. NOTE: for Kelvin temperature units the value is always positive therefore there is no sign selection.  
3.  Press the S1 button to cycle through values from 0 to 9. Press the S2 button to confirm selection and move on to the next digit to the right.  
4. Repeat the previous step until the final digit is confirmed.  

Figure 4: TMP Input Celsius Or Fahrenheit(left)  TMP Input Kelvin(right)

### Result Display Menu:
*The conversion result will be displayed on screen.*  

1. Press the S1 or S2 button to return to the From menu.  

Figure 5: Result Display Menu
