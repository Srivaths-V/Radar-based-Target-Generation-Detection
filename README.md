# Radar-based-Target-Generation-Detection
<img src="Flowchart.png" width="700" />

FMCW - Frequency Modulated Continous Wave

<img src="System req.png" width="700" />

## Project Objective 

* To design a FMCW waveform and model a Signal propagation for a moving target scenario.
* To calculate the beat signal based on modeled transmitted and received signals.
* Implement 1D FFT for target range detection and 2D FFT to generate 'Range Doppler Map' for finding target's range, velocity.
* Implement 2D CFAR (Constant False Alarm Rate) on the Range Doppler Map to suppress the noise.

The initial position of the target is set to 80m and the initial velocity is set to 35m/s.

## My Results 

<img src="1.Range from FFT 1D.jpg" width="700" />

* Target Range detection from Fast Fourier Transform 1D and the detection is around 80 close to the initial position of the target

<img src="2. Range Doppler Response.jpg" width="700" />

* The Range Doppler Response obtained here

<img src="3.CFAR_Implementation.jpg" width="700" />

*The Constant False Alarm Rate Implemented here

