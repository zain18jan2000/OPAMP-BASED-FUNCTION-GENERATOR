# OPAMP-BASED-FUNCTION-GENERATOR

<p>This Function Generator circuits is capable of generating following three types of signals,</p>
1- Square Wave <br>
2- Triangular Wave <br>
3- Sine wave <br>
<br>
<p>On the basis of simulation results it is obsereved that the function generator can generate signal with in the frequency range of 3kHz to 16 KHz. Hence the bandwith of function generator is 13 kHz.</p>
<br>
<h1>WORKING OF THE CIRCUIT:</h1>
<p>The circuit of function generator consists of 5 op-amp stages,hence just for the purpose of understanding its working, it can be broken down into  five parts.<br><br>
The first stage is square wave generator. Here the opamp is provided with positive feedback by means of a resistor and capacitor. Therefore the first stage is acting as an oscillator, producing a square wave continously. Its frequency can be varied by changing the value of either the resistor or capacitor and is given by:<br>
      <h3> <center> F = (1/2RC) x ln(R1/(R1+2R2)) </center> </h3> 
Second stage is an integrator converting square wave to triangular wave. Because this integrator is also a low pass filter hence also attenuates the triangular output as frequency increases. To overcome this attenuation, the  second stage is followed by a high pass active filter (the third stage). The amplified triangular output is provided to another low pass active filter (the fourth op-amp stage) which convert the wave into sinosoidal shape. Again, to overcome the attenuation, I used the fifth stage of op-amp which is high pass active filter to amplify the sine wave. The amount of amplification increases as the frequecy of  the signal increases. This technique is used to achieve linearity in the the amplification, in other words to overcome the greater attenuating effect at higher frequencies.</p>
<p>Frequency of the signal can be varied using the potentiometer in place of feedback resistor in first stage. All three signals will have same frequency for a given position of potentiometer wiper. For designing the circuit, I have used the op-amp LM-318 in each stage because of its high slew rate. Low cost op-amp like UA-741 or LM741 will have low slew rate, therefore will distort the shape of waveform. The amplitude of wave produced by function generator circuit can be varied by varying the input DC voltage.</p>
