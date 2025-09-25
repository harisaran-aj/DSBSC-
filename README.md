# DSBSC


EX NO: 2	DSB-SC-AM MODULATOR AND DEMODULATOR

AIM:

To write a program to perform DSBSC modulation and demodulation using SCI LAB and study its spectral characteristics

EQUIPMENTS REQUIRED

•	Computer with i3 Processor
•	SCI LAB

Note: Keep all the switch faults in off position

Algorithm:

1.	Define Parameters:
•	Fs: Sampling frequency.
•	T: Duration of the signal.
•	Fc: Carrier frequency.
•	Fm: Frequency of the message signal.
•	Amplitude: Maximum amplitude of the message signal.
2.	Generate Signals:
•	Message Signal: A sinusoidal signal that will be modulated.
•	Carrier Signal: A high-frequency sinusoidal signal used for modulation.
3.	DSBSC Modulation:
•	Modulated Signal: Multiply the message signal by the carrier signal to produce the DSBSC signal.
4.	DSBSC Demodulation:
•	Multiplication: Multiply the modulated signal by the carrier signal to get the product of the message signal with itself (i.e., the original message signal plus high-frequency components).
•	Low-pass Filtering: Apply a Butterworth low-pass filter to remove the high- frequency components and recover the original message signal.
5.	Visualization:
Plot the message signal, carrier signal, DSBSC modulated signal, and the recovered signal after demodulation.
PROCEDURE

•	Refer Algorithms and write code for the experiment.
•	Open SCILAB in System
•	Type your code in New Editor
•	Save the file
 
•	Execute the code
•	If any Error, correct it in code and execute again
•	Verify the generated waveform using Tabulation and Model Waveform

Model Waveform

<img width="703" height="679" alt="image" src="https://github.com/user-attachments/assets/e7c7c7f8-ccf2-41ac-b1f3-325989941a6f" />

Program
<img width="1920" height="1080" alt="Screenshot 2025-09-25 152534" src="https://github.com/user-attachments/assets/63017ac0-9fb4-4409-b053-2e67c9c3d9f5" />

Output Graph
<img width="1920" height="1080" alt="Screenshot 2025-09-25 152605" src="https://github.com/user-attachments/assets/f5c192e7-c257-4ffb-a73b-85bc3e1cb375" />


Tablular Column
![WhatsApp Image 2025-09-25 at 15 54 07_9a1fe357](https://github.com/user-attachments/assets/519aee14-7139-4600-b941-2c97c945f5d4)


Result

Thus the DSB-SC-AM Modulation and Demodulation is generated.

