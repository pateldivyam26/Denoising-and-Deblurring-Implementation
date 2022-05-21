# Signals and Systems Programming Assignment
## Denoising and Deblurring Algorithm Implementation
### Problem Statement
One of the many applications of Internet of Things (IoT) consists of continuous monitoring of temperature in an area. To that end, several temperature sensors are installed at different locations. These sensors measure and store the recorded value of temperature over time. However, due to limitations of hardware, the sensor memory needs to be cleared periodically and this is done by transmitting the stored values to a base unit. Assume that x[n] denotes the samples of the true value of temperature recorded by a sensor. However, it is found that the received signal y[n] at the base unit suffers from blur distortions and noise (additive). Hence, the signal y[n] needs to be first processed so that we can recover x[n] from it. Assume that blur happens via a system characterized an impulse response h[n] = 1/16 [1 4 6 4 1] (assume that the center value of 6/16 corresponds to n = 0). Then, implement the following two approaches to recover the original signal x[n] from distorted signal y[n].
1. Denoising then Deblurring. (x1[n])
2. Deblurring then Denoising. (x2[n])

Now, compare x1[n] and x2[n] with x[n]. What conclusions can you draw from your observations?

### Solution
The [Report](https://github.com/pateldivyam26/EEL2010-Signals-and-Systems-Assignment/blob/main/SNS%20ProgrammingmAssignment%20Report.pdf) explains the approaches taken in depth and key findings of this problem.

The [Python Notebook](https://github.com/pateldivyam26/EEL2010-Signals-and-Systems-Assignment/blob/main/Programming%20Assignment.ipynb) provides the scratch implementation of Discrete Time Fourier Transform and its application.
