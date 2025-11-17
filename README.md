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


<img width="629" height="802" alt="Screenshot 2025-10-09 152640" src="https://github.com/user-attachments/assets/f12b9317-58d0-4595-a347-7e3b21a5417c" />


Output Graph


<img width="1574" height="809" alt="Screenshot 2025-10-09 152708" src="https://github.com/user-attachments/assets/7e7d9cdb-23be-443f-91ba-ca2c312ad3b7" />



Tablular Column
![WhatsApp Image 2025-10-09 at 16 02 46_212c8f25](https://github.com/user-attachments/assets/c93c44d5-5571-4e5b-93ae-09aa1e1d835a)

# Calculation:
![WhatsApp Image 2025-10-09 at 16 02 47_e3f973a4](https://github.com/user-attachments/assets/7b1563a0-37f0-47cb-b523-eb634da434f4)




Result

Thus the DSB-SC-AM Modulation and Demodulation is generated.

