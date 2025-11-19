
Exp 5 Experimental verification of frequency response of Digital fiber optic link
# Digital Fiber Optic Link Analysis (600nm)

## AIM
To analyze the relationship between input and received signal of a 600nm fiber optic cable using digital link.

---

## EQUIPMENTS REQUIRED
- Fiber optic trainer kit ST 2502  
- Power supply  
- Patch cords  
- CRO (Cathode Ray Oscilloscope)  
- 660 nm fiber cable  

---

## THEORY

Fiber optic links can be used for transmission of digital as well as analog signals. A fiber optic link typically consists of three main elements:
- **Transmitter**: Converts the electrical input signal into optical (light) energy.
- **Optical Fiber**: Serves as the transmission medium for the light signal.
- **Receiver**: Converts the received light back into an electrical signal, preserving the original signal pattern.

---

## PROCEDURE

1. Connect the power supply to the board.  
2. Ensure that all switched faults are set to ‘Off’.  
3. Make the following connections:  
   a. Connect the 1 KHz square wave output to emitter 1's input.  
   b. Connect the fiber optic cable between emitter output and detector input.  
   c. Connect detector 1's output to comparator 1’s input.  
   d. Connect comparator 1's output to AC amplifier 1's input.  
4. On the board, switch emitter 1's driver to digital mode.  
5. Switch on the power.  
6. Monitor both the inputs to comparator 1 (TP13 & TP14). Slowly adjust the comparator's bias preset until the DC level on TP13 lies midway between the high and low levels of the signal on TP14.  
7. Observe the input to emitter 1 (TP5) and the output from AC amplifier 1 (TP28). Verify that both signals are identical.  
8. Vary the frequency between 10 Hz to 1 MHz and observe the output voltage for a constant input voltage of 5V.  
9. Calculate the bandwidth by determining the gain in decibels (dB).  

---

## BLOCK DIAGRAM
![WhatsApp Image 2025-11-16 at 15 38 04_b9f63c99](https://github.com/user-attachments/assets/bed1f472-2e56-4b05-bddc-fa0831151b4c)

---


## CONNECTION DIAGRAM  
**Setting up a Digital Link**

![WhatsApp Image 2025-11-19 at 22 58 15_c6971d7c](https://github.com/user-attachments/assets/e445d1d1-f35e-4f32-9af6-862a2e0474d8)


---

## TABULATION  
![WhatsApp Image 2025-11-19 at 23 00 03_7732724d](https://github.com/user-attachments/assets/1ec10bf1-0736-4be5-9fd8-ee31cf2bfb7d)

---

## MODEL GRAPH
![WhatsApp Image 2025-11-19 at 23 00 31_38ea64cd](https://github.com/user-attachments/assets/27382e22-58d1-47c1-9ff2-19f6af18ce9f)

---
![WhatsApp Image 2025-11-19 at 23 01 08_d7a0c1f1](https://github.com/user-attachments/assets/b7f5924d-3450-4af0-b1f4-db2c977bfbfd)

---

## RESULT
*Thus the experimental verification of frequency response of digital fiber optic link was studied and verified successfully.*


---

