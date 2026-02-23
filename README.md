## Experiment No: 2
## NON-INVERTING AMPLIFIER USING OP-AMP (μA741)
## Aim
To design and simulate a Non-Inverting Amplifier using μA741 in Proteus Design Suite and verify its voltage gain.
## Apparatus Required
•	μA741 Op-Amp
•	Resistor R1 = 10 kΩ
•	Resistor Rf = 100 kΩ
•	Signal Generator (1 kHz sine wave)
•	Dual Power Supply (±15V)
•	CRO / Oscilloscope
•	Connecting wires
## Circuit Diagram
(Draw neatly in record OR paste Proteus circuit screenshot)
Pin Configuration:
•	Pin 3 → Input (Non-inverting)
•	Pin 2 → Feedback network
•	Pin 6 → Output
•	Pin 7 → +15V
•	Pin 4 → −15V

<img width="1612" height="750" alt="LIC 741 NONINVERTER" src="https://github.com/user-attachments/assets/7bfe44b5-d445-4877-84be-661f9a3ec59e" />

## Theory
A Non-Inverting Amplifier is a closed-loop amplifier configuration in which the input is applied to the non-inverting terminal (+) of the op-amp.
The output signal is amplified and remains in phase with the input signal.
## Procedure
1.	Open Proteus software.
2.	Select μA741, resistors, signal generator, and CRO.
3.	Connect circuit in non-inverting configuration.
4.	Set R1 = 10kΩ and Rf = 100kΩ.
5.	Apply ±15V supply.
6.	Give input sine wave of 1V, 1kHz.
7.	Run simulation.
8.	Observe input and output waveforms.
## Waveform
<img width="798" height="800" alt="LIC 741NONINVERTER" src="https://github.com/user-attachments/assets/cbd87e06-bb64-4a88-afaf-8a50b2a58432" />

## Tabulation
S.No	Vin (V)	Theoretical Gain	Theoretical Vout (V)	Practical Vout (V)
<img width="957" height="278" alt="image" src="https://github.com/user-attachments/assets/061407fe-7d09-4c8f-b235-114b2c4c3f8f" />

## Result
The Non-Inverting Amplifier using μA741 Op-Amp was designed and simulated successfully.
The voltage gain obtained is approximately 11.
The output waveform is in phase with the input waveform.
## Conclusion
•	Gain depends on resistor ratio (Rf/R1).
•	Output is amplified without phase reversal.
•	Practical values are close to theoretical values.
## Viva Questions
1.	What is a Non-Inverting Amplifier?

A Non-Inverting Amplifier is an operational amplifier (Op-Amp) configuration in which the input signal is applied to the non-inverting (+) terminal, and the output is fed back to the inverting (–) terminal through a feedback resistor.

2.	What is the gain formula?
The voltage gain Av of a on-inverting amplifier is:
Av=1+Rf/R1

3.	Why is output in phase?
In a non-inverting amplifier, the input signal is applied directly to the non-inverting (+) terminal of the op-amp.
Since the output moves in the same direction as the input (increase → increase, decrease → decrease), there is no phase reversal.
Therefore, the output is in phase (0° phase shift) with the input.

4.	What happens if Rf increases?
	* Voltage Gain Increases
  * Output Voltage Increases
  * Possible Output Saturation
  * Bandwidth Decreases

5.What is the input impedance of non-inverting amplifier?
Because the input signal is applied directly to the non-inverting (+) terminal of the op-amp, and the op-amp itself has very high input impedance.
so practically:
Zin~=2Momega

