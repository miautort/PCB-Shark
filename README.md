This is a simple project given as an assignment. The conditions were for the board to be within 100x100mm, and to use the specified microprocessor. 

The task itself was to draw something with LEDs. As just placing some LEDs was just boring, I decided to make it interesting through shape as well, and use the components themselves to make it look better. The rat with pink bow meme exploded just about in time to inspire me, so here we are, with a shark with a pink shiny bow.

Here's the component list:

| Component  | Number and/or Type |
| ------------- | ------------- |
| Microcontroller  | MSP430G2553IN20 (U1) | 
| LED  | 12* ; both 3mm and 5mm are compatible    |
| Capacitors | 1x1nF (C1) ; 1x10uF (C3) ; 1x22uF (C2) |
| Connectors | Micro-USB B for power (J2) ; 4-pin for programming (J1) |
| Resistors | 1x100kOhm (R1) ; 6x330** Ohm |
| Quartz Crystal | 32kHz (Y1) |
| Voltage Regulator | TLV1117-33 (U2) |

*I used 10 pink for the bow and 2 blue for the eye

**The resistor values depend on the chosen LED color

Below is a screenshot of the electric circuit itself; below that the PCB design, first without mass plan, then with.

<img width="914" height="623" alt="image" src="https://github.com/user-attachments/assets/86bd527a-af78-4e02-9bc0-3a3d2d9862e2" />

<img width="465" height="426" alt="image" src="https://github.com/user-attachments/assets/38b4a51e-d39f-4111-b310-59ea679592a5" /> <img width="475" height="425" alt="image" src="https://github.com/user-attachments/assets/58a64adb-09d4-4b14-876d-09d8a68e2a94" />



