## EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
## SIMULATION OF DIGITAL TO ANALOG CONVERTER

## AIM:
To Design and simulate the digital to analog converter (DAC) circuit using LT Spice

## SOFTWARE REQUIRED:
LT-Spice

## PROCEDURE:
1. Double click on LT Spice icon.

2. New schematic window open.

3. Pick and paste the required component from the library and draw the circuit diagram .

4. Complete the connection.

5. Select 1 voltage and select pulse width as 
Vinitial [V]: 5
       Von [V]: 0
       Tdelay [s]: 0
       Trise [s]: 1u
       Tfall [s]: 1u
               Ton [s]: 10m
        Tperiod [s]: 20m
        Ncycles: 100
Change the values of Ton = 20m , 40m, Tperiod  = 40m , 80m
For v2 and v3  keeping the other values constant.
6. Save the file by giving file name.

7. Click on the run option -->click advanced open -->select select transient analysis -->enter the amplitude time delay stop time value as (.tran 0 200 0 0.01).

8. Click on the run option -->simulation window opens-->place the probe -->output graph is obtained.

## CIRCUIT DIAGRAM:
### DAC:
![WhatsApp Image 2026-03-21 at 7 11 12 PM](https://github.com/user-attachments/assets/412e36c9-b07b-4df7-ac74-409d7e6b01bb)


## OUTPUT GRAPH:
### DAC:
![WhatsApp Image 2026-03-21 at 7 11 03 PM](https://github.com/user-attachments/assets/c072efbf-93af-4aee-b953-8cdf7e62e3fa)

## RESULT:
Thus the LT-SPICE tool has been studied and digital to analog converter (DAC) circuit is simulated.
