# SSB
## Priyanka B (212224060197)

EXP NO: 3	SSB-SC-AM MODULATION using SCILAB

AIM: To write a program to perform SSBSC modulation and demodulation using SCI LAB and study its spectral characteristics

EQUIPMENTS REQUIRED:
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
•	Message Signal: The baseband signal that will be modulated.
•	Carrier Signal: A high-frequency signal used for modulation.
•	Analytic Signal: Constructed using the Hilbert transform to get the in-phase and quadrature components.
3.	SSBSC Modulation:
•	Modulated Signal: Create the SSBSC signal using the in-phase and quadrature components, modulated by the carrier.
4.	SSBSC Demodulation:
•	Mixing: Multiply the SSBSC signal with the carrier to retrieve the message signal.
•	Low-pass Filtering: Apply a low-pass filter to remove high-frequency components and recover the original message signal.
5.	Visualization:
•	Plot the message signal, carrier signal, SSBSC modulated signal, and the recovered signal after demodulation.


PROCEDURE:
•	Refer Algorithms and write code for the experiment.
•	Open SCILAB in System
•	Type your code in New Editor
•	Save the file
 
•	Execute the code
•	If any Error, correct it in code and execute again
•	Verify the generated waveform using Tabulation and Model Waveform

Model Waveform:
<img width="704" height="178" alt="image" src="https://github.com/user-attachments/assets/32ee29b3-0d95-4192-9762-972d50c05c90" />
<img width="706" height="167" alt="image" src="https://github.com/user-attachments/assets/bff0d8fd-d679-444e-af37-0b34585853c1" />

PROGRAM:


OUTPUT:
<img width="1200" height="1200" alt="ssb_code" src="https://github.com/user-attachments/assets/43176342-aa48-42e2-875a-dadb9c49d185" />
(OUTPUT WAVEFORM)
<img width="1200" height="1200" alt="ssb_final" src="https://github.com/user-attachments/assets/70b940d2-7de1-49f3-a00d-954660c89289" />


TABULATION:
<img width="915" height="1280" alt="image" src="https://github.com/user-attachments/assets/a5436066-2c2e-47b5-9819-bfe6f50b3980" />
<img width="768" height="1280" alt="image" src="https://github.com/user-attachments/assets/b49d0ef9-11a7-46eb-9d6f-63a2ab14cb01" />




RESULT: Thus, the SSB-SC-AM Modulation and Demodulation is experimentally done and the output is verified.





