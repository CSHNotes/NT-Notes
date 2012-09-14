# Network Troubleshooting

# Decibels (dB)

- baseline measurement standard
	- 0dB = 1W   0dBm = 1mW
- originally for sound intensity
- same unit can be used for power, voltage, optics, wireless, etc.
- log scale
	- graphing and some calculations are easier
	- also a ratio of comparison
	- ex. 
		- dB = 10 log (P+/Pi)
		- dB = 20 log (Vf / Vi)
- used for measuring things with exponential growth
- most cabling (copper + fiber) measurements are in dB
	- some are max values, some are min

## Signal to noise ration (SNR)

- Want signal to be 1000x greater than the noise
- The amount of thermal noise (and others) present
- When converting from power we use dB = 10log(S/N)
- a S/N of 20 = 100x
	- 30 = 1000x
- shoot for 1000x but actual goal is ~35dB (> 3000x)
- but some noise increases as the power dies
	- increasing power is not always the answer

## dB Rules

- doubling power +3dB
- halving power -3dB
- x10 power +10dB
- power / 10 -10db

# Ohm's Law

P = VI = V^2/R = I^2R

V = IR

**NOTE**: Doubling the voltage quadruples the power

# What do we measure?

- distance
	- 100m max ethernet length
- attenuation
- crosstalk
- return