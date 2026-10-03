# ATC24 Comm Helper | (https://frequencyswitcheratc24.vercel.app/)

This is a simple simulation of a Garmin GTR-225 Aviation Radio intended to help you switch frequencies easily on ATC24. Simply input the correct frequency and press 'Enter' or use the swap button on the right to be taken to the right frequency.

## Functionality/User Manual

1. Double-click on the frequency labeled 'COM STBY' to input a new frequency. Input takes a maximum of 5 digits, starting from the tenth (2nd) digit of the frequency you want to change to. Zeroes are autofilled at the end.
2. Press 'Enter' or use the swap button located to the right of the Standby frequency to swap frequencies. Upon swapping a dialog will open asking you to open the app, and you should be taken to the right FREQ.
3. If you disconnect or forget to click the dialog, the TX com on the left can be clicked to reopen the dialog and bring you to the correct VC.
4. All ATC24 frequencies (excluding event freq's) are supported! Simply type in the right frequency number to get to the correct VC (eg. typing '24850' will bring you to 'IRCC' upon swapping).

## Future Implements

- Adding different radio styles (Airbus, Boeing, etc.)
- Implementing a functional "Tune" knob(s) on the right, potentially operated by scroll wheel or dragging the mouse.
- Adding a transponder tab to identify your aircraft with the ATC24 API.
- A TCAS warning system with voiceover and visual cues.
