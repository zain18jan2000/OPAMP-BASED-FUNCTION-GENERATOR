# OPAMP-BASED-FUNCTION-GENERATOR

<p>This Function Generator circuits is capable of generating following three types of signals,</p>
1- Square Wave <br>
2- Triangular Wave <br>
3- Sine wave <br>
<br>
<p>On the basis of simulation results it is obsereved that the function generator can generate signal with in the frequency range of 3kHz to 16 KHz. Hence the bandwith of function generator is 13 kHz.</p>
<br>
<h1>WORKING OF THE CIRCUIT:</h1>
<p>The circuit of function generator consists of 5 op-amp stages,hence just for the purpose of understanding its working, it can be broken down into  five parts.<br>
 The first stage is square wave generator. Here the opamp is provided with positive feedback by means of a resistor and capacitor.<br>
  Second stage is integrator converting square wave to triangular wave. Because this integrator is also a low pass filter hence attenuates the triangular output as frequency increases. To overcome this attenuation, the  second stage is followed by a high pass active filter (the third stage). The amplified triangular output is provided to another low pass active filter (the fourth op-amp stage) which convert the wave into sinosoidal shape. Again, to overcome the attenuation effect, I used the fifth stage of op-amp which is high pass active filter to amplify the sine wave.</p>
<p>Frequency of the signal can be varied using the potentiometer. All three signals will have same frequency for a given position of potentiometer knob. For designing the circuit, I have used the op-amp LM-318 in each stage because of its high slew rate. Low cost op-amp like UA-741 or LM741 will have low slew rate, therefore can distort the shape of waveform. The amplitude of wave produced by function generator circuit can be varied by varying the input DC voltage.</p>
