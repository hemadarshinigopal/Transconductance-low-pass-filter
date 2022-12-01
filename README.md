# Transconductance-low-pass-filter

Designing a Transconductance-C (Gm-C) low pass filter in 0.35 μm CMOS technology node from TSMC using LTSpice circuit simulator  for the given specifications.

BROAD EXPECTATIONS:

Realizing an ideal Gm-C Filters 

a) Ideal Filer using RLC circuit which meets the specifications.

b) Ideal Gm-C filter for the specifications using macromodel for the Gm. 

2. Designing the transconductor in 0.35 μm CMOS technology node from TSMC and validating its use as a Gm-C integrator. 
The capacitor calculated to be used in the first node of the filter may be used as the integrating capacitor for testing the Gm-C 
integrator.

3. Realize the transistor level Gm-C filter for the given specification.

COMMON SPECIFICATIONS:
1. Fourth order Maximally flat response
2. Power supply 3.3 V
3. Use length of 0.5 μm for all transistors
4. Use even number of fingers for the transistors.

TRANSCONDUCTOR SPECIFICATIONS:
1.	Gm 						= 1 mS
2.	Gate overdrive for input transistors 	= 200 mV
3.	Input/output common-mode voltage 	= 1.65 V

FILTER SPECIFICATIONS:
1.	Attenuation at pass band edge 		= 2 dB
2.	Band-edge					= 110 MHz
