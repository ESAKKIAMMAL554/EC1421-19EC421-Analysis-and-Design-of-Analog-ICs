# EC1421-19EC421-Analysis-and-Design-of-Analog-ICs
# DESIGN OF ACTIVE LOW PASS,HIGH PASS AND BAND PASS FILTERS USING OP-AMP 

## AIM: 

To design and obtain the frequency response of 
i) First order Low Pass Filter (LPF) 
ii) First order High Pass Filter (HPF) 
iii) Band pass filter
 
## APPARATUS REQUIRED

<img width="625" height="170" alt="image" src="https://github.com/user-attachments/assets/900fc8b3-3a8c-4208-bf52-98cc9e281e21" />

## THEORY
## LOW PASS FILTER 
 A LPF allows frequencies from 0 to higher cut of frequency, fH.  At fH the gain is 0.707 
Amax, and after fH gain decreases at a constant rate with an increase in frequency.  The gain 
decreases 20dB each time the frequency is increased by 10.  Hence the rate at which the gain 
rolls off after fH is 20dB/decade or 6 dB/ octave, where octave signifies a two fold increase in 
frequency.  The frequency f=fH is called the cut off frequency because the gain of the filter at this 
frequency is down by 3 dB from 0 Hz.  Other equivalent terms for cut-off frequency are -3dB 
frequency, break frequency, or corner frequency.
# HIGH PASS FILTER 
The frequency at which the magnitude of the gain is 0.707 times the maximum value of 
gain is called low cut off frequency.  Obviously, all frequencies higher than fL are pass band 
frequencies with the highest frequency determined by the closed –loop band width all of the op
amp. 
# BAND PASS FILTER 
A band pass filter has a pass band between two cutoff frequencies fH and fL such that fH > 
fL.  Any input frequency outside this pass band is attenuated.  There are two types of band-pass 
filters.  Wide band pass and Narrow band pass filters.  We can define a filter as wide band pass if 
its quality factor Q <10.  If Q>10, then we call the filter a narrow band pass filter.  A wide band 
pass filter can be formed by simply cascading high-pass and low-pass sections.  The order of 
band pass filter depends on the order of high pass and low pass sections.

## CIRCUIT DIAGRAM: 
## LOW_PASS
![WhatsApp Image 2026-03-25 at 2 24 09 PM](https://github.com/user-attachments/assets/2f79906f-0c6b-4bc1-8e3b-5432234e81bd)

## HIGH-PASS

![WhatsApp Image 2026-03-25 at 2 24 08 PM](https://github.com/user-attachments/assets/d82eea87-5265-4c3d-b3d0-b7ce57b91a48)

## BAND-PASS

![WhatsApp Image 2026-03-25 at 2 24 05 PM](https://github.com/user-attachments/assets/7da0b9d5-f75d-46b9-b911-321e0a028c2c)


## MODEL GRAPH:
## LOW_PASS
![WhatsApp Image 2026-03-25 at 2 24 08 PM (1)](https://github.com/user-attachments/assets/2cfd7d20-fa57-4e09-b15b-8e0c52a3a51f)

## HIGH-PASS

![WhatsApp Image 2026-03-25 at 2 24 06 PM](https://github.com/user-attachments/assets/92108bfa-206a-4d4a-9aa9-c5074f3f38a5)

## BAND-PASS

![WhatsApp Image 2026-03-25 at 2 24 04 PM](https://github.com/user-attachments/assets/6e15f380-aefe-46b2-b2fe-833118ba18fa)


## PROCEDURE - (LPF & HPF): 
1. Connect the circuit as shown in the circuit diagram. 
2. Select the corresponding cut-off frequency (higher or lower) and determine the value of C&R. 
select the value of R1 & Rf depending on desired passband gain Af.. 
3. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
4. Tabulate the output voltage Vo with respect to different values of input frequency. 
5. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to  get approximately the same characteristic as shown in the model graph. 
# PROCEDURE:BAND PASS FILTER 
1. Select the lower and higher cut-off frequency and calculate the value of R & C for the given 
frequencies. 
2. Design for LPF & HPF separately and then combine the circuit by first placing the HPF 
followed by a LPF (i.e) HPF in series with LPF. 
3. Connect the circuit as shown in the circuit diagram. 
4. Apply a constant voltage input sinusoidal signal to the non-inverting terminal of op-amp. 
5. Tabulate the output voltage Vo with respect to different values of input frequency. 
6. Calculate passband gain and plot the graph of frequency versus voltage gain & check the 
graph to get approximately the same characteristic as shown in the model graph

## DESIGN:LPF & HPF:

<img width="429" height="324" alt="image" src="https://github.com/user-attachments/assets/b0f0ac0a-3006-494c-9096-e91ae2d6e87c" />

# DESIGN: BAND PASS FILTER
Design a BPF to pass a band of 400Hz to 2KHz with a pass band gain of 4.  
1. Select the highest cut-off frequency of LPF as fH = 10 KHz and the lowest cut-off frequency 
of HPF as fL = 1 KHz.  
2. Design the HPF first by taking fL = 1KHz. Assume the value of C < 1μf.  
Let C = 0.1μf.  
3. Calculate R from the expression.  
Given: fH = 2KHz  = 1/ (2πR1C1) 
   Let C1 = 0.1 µF, R1 = 7.9 KΩ 
Given: fL = 400Hz  = 1/ (2πR2C2) 
   Let C2 = 0.1 µF, R2 = 39.8 KΩ 
  Pass band Gain=4 
   Now   Ao = 1 + (Rf / R1)  
               2-1=(Rf / Ri) 
                Ri = Rf 
                 Let  Ri = Rf = 10 KΩ
## TABULATION:
## LOW_PASS
![WhatsApp Image 2026-03-25 at 2 34 01 PM](https://github.com/user-attachments/assets/418f141d-4674-4d17-8d90-c464f647c45e)

## HIGH-PASS

![WhatsApp Image 2026-03-25 at 2 21 46 PM](https://github.com/user-attachments/assets/76769a85-6aae-4d90-ad29-12d12def3976)

## BAND-PASS
![WhatsApp Image 2026-03-25 at 2 22 54 PM](https://github.com/user-attachments/assets/d4c64369-2ec7-478d-9dc3-b32c43421788)

## GRAPH:

## LOW_PASS
![WhatsApp Image 2026-03-25 at 2 27 04 PM](https://github.com/user-attachments/assets/e67e265b-9af2-4326-99fd-2f4ea5a279cb)

## HIGH-PASS

![WhatsApp Image 2026-03-25 at 2 28 21 PM](https://github.com/user-attachments/assets/6b6ca584-90aa-4259-a43e-76e95083fc6d)

## BAND-PASS

![WhatsApp Image 2026-03-25 at 2 27 45 PM](https://github.com/user-attachments/assets/7acd8efc-903f-44a0-9621-89828c039fb1)

 ## RESULTS:
Thus an Active Low pass, High pass and Band Pass Filters are designed and 
tested using op-amp IC 741. 

