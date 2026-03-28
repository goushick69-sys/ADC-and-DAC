## Experiment 7 (a): Analog to Digital Converter (ADC) using Proteus
## Aim
To design and simulate an Analog to Digital Converter (ADC) circuit using Proteus and observe the conversion of an analog input voltage into its equivalent digital output.
## Apparatus / Software Required
•	Proteus Design Suite
•	ADC IC (ADC0804)
•	Resistors
•	Capacitor
•	Potentiometer (for analog input)
•	Clock components
•	LED display / Logic probe
•	Power supply (5V)
## Theory
An Analog to Digital Converter (ADC) converts a continuous analog signal into a digital representation. ADCs are widely used in digital systems where analog signals from sensors need to be processed by microcontrollers or computers.
The ADC0804 is an 8-bit ADC that uses the successive approximation technique for conversion. It converts the analog input voltage into an equivalent 8-bit binary number.
Important Features
•	Resolution: 8-bit
•	Input voltage range: 0–5 V
•	Conversion method: Successive approximation
•	Output: Digital binary (D0–D7)
The digital output is proportional to the input analog voltage.
## Circuit Diagram
<img width="1086" height="589" alt="Screenshot 2026-03-10 140019" src="https://github.com/user-attachments/assets/b21c00ae-a6c1-4236-85de-c35c8eb099d0" />

Design the circuit in Proteus using ADC0804 with:
•	Analog input from potentiometer
•	Clock using resistor and capacitor
•	Output connected to LEDs or logic probes
## Procedure
1.	Open Proteus Design Suite.
2.	Select the following components from the library:
o	ADC0804
o	Resistor
o	Capacitor
o	Potentiometer
o	LEDs
3.	Connect the analog input pin (VIN+) to the potentiometer.
4.	Connect VIN− to ground.
5.	Create the clock using resistor and capacitor between CLK pins.
6.	Connect output pins D0–D7 to LEDs.
7.	Apply 5V supply to the ADC.
8.	Run the simulation.
9.	Vary the potentiometer and observe the digital output.

## Tabulation
| S.No | A | B | C | D | Digital Value | Theoretical Vout (V) |
| ---- | - | - | - | - | ------------- | -------------------- |
| 1    | 0 | 0 | 0 | 0 | 0             | 0                    |
| 2    | 0 | 0 | 0 | 1 | 1             | -0.3125              |
| 3    | 0 | 0 | 1 | 0 | 2             | -0.625               |
| 4    | 0 | 0 | 1 | 1 | 3             | -0.9375              |
| 5    | 0 | 1 | 0 | 0 | 4             | -1.25                |
| 6    | 0 | 1 | 0 | 1 | 5             | -1.5625              |
| 7    | 0 | 1 | 1 | 0 | 6             | -1.875               |
| 8    | 0 | 1 | 1 | 1 | 7             | -2.1875              |
| 9    | 1 | 0 | 0 | 0 | 8             | -2.5                 |
| 10   | 1 | 0 | 0 | 1 | 9             | -2.8125              |
| 11   | 1 | 0 | 1 | 0 | 10            | -3.125               |
| 12   | 1 | 0 | 1 | 1 | 11            | -3.4375              |
| 13   | 1 | 1 | 0 | 0 | 12            | -3.75                |
| 14   | 1 | 1 | 0 | 1 | 13            | -4.0625              |
| 15   | 1 | 1 | 1 | 0 | 14            | -4.375               |
| 16   | 1 | 1 | 1 | 1 | 15            | -4.6875              |

## Result
The Analog to Digital Converter circuit was successfully designed and simulated in Proteus, and the analog input voltage was converted into the corresponding digital output.


## Applications of ADC and DAC
•	Data acquisition systems
•	Digital signal processing
•	Microcontroller interfacing
•	Audio and video processing
•	Instrumentation systems
