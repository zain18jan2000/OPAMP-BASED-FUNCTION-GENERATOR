# OPAMP-BASED-FUNCTION-GENERATOR

<p>This Function Generator is capable of generating three types of signals which are as follow,</p>
1- Square Wave <br>
2- Triangular Wave <br>
3- Sine wave <br>
<br>
<p>On the basis of simulation results it is obsereved that the function generator can generate signal in the frequency range of 3kHz to 16 KHz. Hence the bandwith of function generator is 13 kHz.</p>
<br>
<h1>WORKING OF THE CIRCUIT:</h1>
<p>The circuit of function generator consists of 5 op-amp stages. The first stage is square wave generator. Second stage is integrator converting square wave to triangular wave. Because this integrator is also a low pass filter hence attenuates the triangular output as frequency increases. To overcome this attenuation, the  second stage is followed by a high pass active filter (the third stage). The amplified triangular output is provided to another low pass active filter (the fourth op-amp stage) which convert the wave into sinosoidal shape. Again, to overcome the attenuation effect, I used the fifth stage of op-amp which is high pass active filter to amplify the sine wave.</p>
