# EXPERIMENT-2-OPTICAL-COMMUNICATION
## 🔍 EX.NO: 2 – Verification of Fiber Losses

**Aim:**  
To measure propagation and bending losses for two wavelengths in plastic fiber.

**Equipments Required:**  
- Link-B Kit  
- Patch chords  
- Oscilloscope  
- Function Generator  
- Fiber cables  

**Theory:**  
- Losses due to absorption, scattering, bending  
- Plastic fiber loss ~180 dB/km  
- Bending loss increases with reduced loop diameter  

**Procedure:**  
- 	Connect the power supply with proper polarity to the kit link-B and switch it on.
	Keep all Switch Faults in OFF position.
	Keep switch SW8 towards TX position.
	Keep switch SW9 towards TX1 position.
	Keep Jumper JP5 towards +12V position.
	Keep Jumpers JP6, JP9, JP10 shorted.
	Keep Jumper JP8 towards sine position.
	Keep Intensity control pot P2 towards minimum position.
	Feed about 2Vpp sinusoidal signal of 1 KHz from the function generator to the IN post of Analog Buffer.

<img width="476" height="192" alt="image" src="https://github.com/user-attachments/assets/02637258-47a1-4bae-abb7-4eace5a9d6e6" />


	Connect the output post OUT of Analog Buffer to the post TX IN of Transmitter.
	Slightly unscrew the cap of SFH756V (660nm). Do not remove the cap from the connector. Once the cap is loosened, insert the one meter fiber into the cap. Now tighten the cap by screwing it back.
	Connect the other end of the Fiber to detector SFH350V (Photo Transistor Detector) very carefully.
	Observe the detected signal at post ANALOG OUT on oscilloscope. Adjust Intensity control pot P2 Optical Power control potentiometer so that you receive signal of 2Vpp amplitude.

<img width="459" height="189" alt="image" src="https://github.com/user-attachments/assets/b8f1dbfb-eace-4ed8-9900-000d5a3c624c" />


	Measure the peak value of the received signal at ANALOG OUT terminal. Let this value be V1.
	Now replace 1 meter Fiber by 3 Meter Fiber. Do not disturb any settings. Again take the peak voltage reading and let it be V2.
 
 
<img width="446" height="183" alt="image" src="https://github.com/user-attachments/assets/44392144-8228-4748-8896-05524f72fa36" />


	If a is the attenuation of the Fiber then we have. P1/P2 = V1/V2 = e [ -a (L1+L2 ) ]

Where
a = nepers/ Meter
L1 = Fiber Length for V1 L2 = Fiber Length for V2 This a is for peak wavelength of 660nm
	Keep switch SW9 towards TX2 position.
	Keep Jumper JP7 towards +12V position.
	Remove fiber cable from SFH756V (660nm) & SFH350V and insert one meter fiber between SFH450V (950nm) & SFH350V.
	Observe the detected signal at post ANALOG OUT on oscilloscope.



	Measure the peak value of the received signal at ANALOG OUT terminal. Let this value be V1.
	Now replace 1 meter Fiber by 3 Meter Fiber. Do not disturb any settings. Again take the peak voltage reading and let it be V2.
	If a is the attenuation of the Fiber then we have. P1/P2 = V1/V2 = e [ -a (L1+L2 ) ]
Where
a = nepers/ Meter
L1 = Fiber Length for V1 ; L2 = Fiber Length for V2 This a is for peak wavelength of 950nm
	Compare the two a values.


**Tabulation:**

### Propagation Loss

| Fiber Length | Input Amplitude (V) | Output Amplitude (V) |
|--------------|---------------------|------------------------|
|     0.5m     |     10v             |      4v                |
|     1m       |     10v             |      3.6v              |

### Bending Loss

| Bending Diameter | Input Amplitude (V) | Output Amplitude (V) |
|------------------|---------------------|------------------------|
|     0.5m         |    10v              |     3.2v               |
|     1m           |    10v              |     3.6v               |

### Calculation
<img width="1040" height="780" alt="image" src="https://github.com/user-attachments/assets/cdd56d3d-04d3-4e55-a64b-189089b9d042" />


**Result:**  
Attenuation and bending loss characteristics verified.

---
