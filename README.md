# IDEAL SAMPLING
## AIM :
To study and analyze Ideal Sampling (Impulse Sampling), where a continuous-time signal is sampled using an impulse train, and observe its effects in both time and frequency domains. The experiment aims to verify the sampling theorem, analyze spectral characteristics, and understand signal reconstruction.
## TOOLS REQUIRED :
Personal computer with installed with scilab.
## PROGRAM :
~~~......~~clf; // Clear the current figure
t = 0:0.001:1; // Time vector from 0 to 1 with a small step
f = 5; // Frequency of the sine wave (5 Hz)
x = sin(2 * %pi * f * t); // Continuous-time signal (sine wave)
// Plot the continuous-time signal
subplot(5,1,1);
plot(t, x);
title('Continuous-time Signal');
xlabel('Time (s)');
ylabel('Amplitude');
legend('Continuous-time Signal with freq 5Hz'); ~~......~~
// Step 2: Sample the signal at different samp

## OUTPUT WAVEFORM :
![dc 1st exp](https://github.com/user-attachments/assets/d815252c-8ec5-41b5-a234-37b33e0fde01)
## RESULT :
The result of ideal sampling is a discrete-time signal that retains all the information of the original continuous-time signal is obtained and output is verified.
