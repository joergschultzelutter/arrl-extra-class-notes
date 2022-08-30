# arrl-extra-class-notes

Personal notes for the ARRL FCC Extra Class Exam. Work in progress.

## E8 B05
What is the deviation ratio of an FM-phone signal having a maximum frequency swing of plus-or-minus 5 kHz when the maximum modulation frequency is 3 kHz?

- A. 0.167
- B. 60
- C. 0.6
- D. 1.67

Answer: D

$DeviationRatio$ = $${MaximumFrequencySwing} \over {MaximumModulationFrequency}$$

# E8 C07
What is the bandwidth of a 4800-Hz frequency shift, 9600-baud ASCII FM transmission?

- A. 15.36 kHz
- B. 5.76 kHz
- C. 4.8 kHz
- D. 9.6 kHz

Answer: A

$$BW=(K⋅shift)+baud rate=(1.2⋅4800 Hz)+9600=15,360 Hz=15.36 kHz$$

## E5 B04

What is the time constant of a circuit having two 220-microfarad capacitors and two 1-megohm resistors, all in parallel?

- A. 440 seconds
- B. 220 seconds
- C. 55 seconds
- D. 110 seconds

Answer: B

$\tau$ = $R * C$ = $500 M\Omega * 440 pF$


## E4 C14

What transmit frequency might generate an image response signal in a receiver tuned to 14.300 MHz and that uses a 455 kHz IF frequency?

- A. 14.755 MHz
- B. 13.845 MHz
- C. 14.445 MHz
- D. 15.210 MHz

Answer: D

An image response signal may be located at the tuned frequency ± $2×$ the intermediate frequency:

$$14.300 MHz+(455 kHz⋅2)=15.210 MHz$$
$$14.300 MHz−(455 kHz⋅2)=13.390 MHz$$
Of the two results, only one is in the list of possible answers: 15.210 MHz.

## E5 C12

Which point on Figure E5-1 best represents the impedance of a series circuit consisting of a 300-ohm resistor and a 19-picofarad capacitor at 21.200 MHz?

- A. Point 3
- B. Point 1
- C. Point 8
- D. Point 7

Answer: B

$Xc$ = $${1} \over {2 * \pi * f * c}$$ = ≈ $−j395.1\Omega$

The impedance of a capacitor has a negative j value. --> 300 right, 400 down


## E5 B11

What is the phase angle between the voltage across and the current through a series RLC circuit if XC is 25 ohms, R is 100 ohms, and XL is 50 ohms?

- A. 76 degrees with the voltage leading the current
- B. 14 degrees with the voltage leading the current
- C. 76 degrees with the voltage lagging the current
- D. 14 degrees with the voltage lagging the current

Answer: B


phase angle ϕ=$$ tan−1 {XL−XCR}\over R$$

If the angle is positive, then the voltage is leading. 

Test Tip: ALL the answers to these questions are 14 degrees. For the test, remember: if XC>XL, voltage lags.
