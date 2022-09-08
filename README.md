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


phase angle = atan(XL−XC}/R

If the angle is positive, then the voltage is leading. 

Test Tip: ALL the answers to these questions are 14 degrees. For the test, remember: __if XC>XL, voltage lags__.

## E9 F05

What is the approximate physical length of a solid polyethylene dielectric coaxial transmission line that is electrically 1/4 wavelength long at 14.1 MHz?

- A. 4.3 meters
- B. 3.5 meters
- C. 5.3 meters
- D. 10.6 meters

Answer : B

The velocity factor of solid polyethylene dielectric coax is 66%

$${300000} \over {14100}$$ = 21.3m. Divide by 4. Muitiply by 0.66

--> Merker (wenngleich falsche Berechnung) 14.1/4 --> 3.5

## E5 A12
What is the half-power bandwidth of a resonant circuit that has a resonant frequency of 3.7 MHz and a Q of 118?

- A. 436.6 kHz
- B. 15.7 kHz
- C. 218.3 kHz
- D. 31.4 kHz

Answer: D

$BWhalfpower$ = $${f}\over{Q}$$


## E9 B03

In the antenna radiation pattern shown in Figure E9-1, what is the front-to-side ratio?

- A. 18 dB
- B. 14 dB
- C. 12 dB
- D. 24 dB

This is simply a case of taking the difference between the value of the peak front radiation and the peak side radiation. The front is 0dB and the side is less than -12 and more than -24, much nearer the -12 value. So, the front-to-side ratio is greater than 0 - -12dB or 12dB but only a little greater so given the answers shows 14dB looks more likely than 18dB. A Silly HINT: All distractors are multiples of 6 (12, 18, 24) except for the correct answer, 14


## E5 D15

What is the power factor of an RL circuit having a 45-degree phase angle between the voltage and the current?

- A. 0.707
- B. 1.0
- C. 0.5
- D. 0.866

Answer: A

cos(angle)

## E8 B04

What is the modulation index of an FM-phone signal having a maximum carrier deviation of plus or minus 6 kHz when modulated with a 2 kHz modulating frequency?

- A. 2000
- B. 6000
- C. 3
- D. 1/3

= (carrier deviation) / modulated frequency

## E5 A16

What is the resonant frequency of an RLC circuit if R is 33 ohms, L is 50 microhenries and C is 10 picofarads?

- A. 7.12 kHz
- B. 23.5 kHz
- C. 7.12 MHz
- D. 23.5 MHz

Answer: C

R is irrelevant for the calculation!!!! use $f$ = $${1}\over{2*\pi*\sqrt{L*C}}$$

## E8 C05

What is the approximate bandwidth of a 13-WPM International Morse Code transmission?

- A. 26 Hz
- B. 52 Hz
- C. 104 Hz
- D. 13 Hz

Answer: B

= WPM * 4(Hz)

## E4 C06

A CW receiver with the AGC off has an equivalent input noise power density of -174 dBm/Hz. What would be the level of an unmodulated carrier input to this receiver that would yield an audio output SNR of 0 dB in a 400 Hz noise bandwidth?

- A. -148 dBm
- B. -164 dBm
- C. -155 dBm
- D. -174 dBm

Answer: A

$$-174db + (10* log(400))$$

## E4 B03

Which S parameter is equivalent to forward gain?

- A. S21
- B. S11
- C. S22
- D. S12

Answer: A

S11 = input reflection coefficient
S12 = reverse gain
S21 = forward gain
S22 = output reflection coefficient

## E4 B04

Which S parameter is equivalent to forward gain?

- A. S21
- B. S11
- C. S22
- D. S12

Answer: B

S11 = input reflection coefficient
S12 = reverse gain
S21 = forward gain
S22 = output reflection coefficient

## E5 A11

What is the half-power bandwidth of a resonant circuit that has a resonant frequency of 7.1 MHz and a Q of 150?

- A. 157.8 Hz
- B. 47.3 kHz
- C. 23.67 kHz
- D. 315.6 Hz

Answer: B

B = f / Q

## E9 E10

Which of these choices is an effective way to match an antenna with a 100-ohm feed point impedance to a 50-ohm coaxial cable feed line?

- A. Connect a 1/4-wavelength open stub of 300-ohm twinlead in parallel with the coaxial feed line where it connects to the antenna
- B. Insert a 1/2 wavelength piece of 300-ohm twinlead in series between the antenna terminals and the 50-ohm feed cable
- C. Insert a 1/4-wavelength piece of 75-ohm coaxial cable transmission line in series between the antenna terminals and the 50-ohm feed cable
- D. Connect a 1/2 wavelength shorted stub of 75-ohm cable in parallel with the 50-ohm cable where it attaches to the antenna

Answer: C

$$\sqrt({50*100})$$

## E9 C02

What is the radiation pattern of two 1/4-wavelength vertical antennas spaced 1/4-wavelength apart and fed 90 degrees out of phase?

- A. Omni-directional
- B. A figure-8 broadside to the axis of the array
- C. A figure-8 end-fire along the axis of the array
- D. Cardioid

Answer: D

## E9 C03

What is the radiation pattern of two 1/4-wavelength vertical antennas spaced 1/2-wavelength apart and fed in phase?

- A. A Figure-8 broadside to the axis of the array
- B. A Figure-8 end-fire along the axis of the array
- C. Omni-directional
- D. Cardioid

Answer: A

## E1 C01

What is the maximum bandwidth for a data emission on 60 meters?

- A. 170 Hz
- B. 60 Hz
- C. 1.5 kHz
- D. 2.8 kHz

Answer: D


## E7 D05

Which of the following types of linear voltage regulator places a constant load on the unregulated voltage source?

- A. A series regulator
- B. A constant current source
- C. A shunt current source
- D. A shunt regulator

Answer: D
