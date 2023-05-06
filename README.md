Download Link: https://assignmentchef.com/product/solved-ee316-laboratory-3
<br>



<strong>Part 1: Op-Amp Integrator and Differentiator Circuits</strong>

<strong>Purpose</strong>

The goal of this laboratory is to examine the circuit characteristics of the Op-Amp Integrator and Op-Amp Differentiator circuits.

<strong>Theoretical Background</strong>

<h1>Integrator</h1>

If the resistor is replaced by a capacitor in the negative feedback loop in the basic Inverting OpAmp configuration, a simple integrator circuit can be realized. The basic configuration is shown in Figure 3.1. Once an input signal is applied, the output will appear as an integration of input.

The integrator’s output voltage can be written as










In this equation, it assumes that initially there is no charge on the capacitor.







Figure 3.1




The integrator is useful for turning square waves into triangular waves, and triangular waves into sine waves.

<h1>Differentiator</h1>

A differentiator circuit can be achieved by replacing the resistor with a capacitor at the input of a basic Inverting Op-Amp configuration. This configuration is shown in Figure 3.2. The differentiator output voltage can be written as







<strong>Figure 3.2</strong>




Notice that according to above mentioned equation, the differentiator does the opposite of the integrator.

<strong><u>Simulation Section (Multisim):</u></strong>

<h1>Integrator</h1>

(Refer to Figure 3.1)

Let R=1kΩ, C=0.1 µF, f = 1 kH<sub>Z,</sub>  V<sub>IN </sub> = 2Vpp sinusoidal.

V<sub>IN </sub> = 2Vpp triangle.

V<sub>IN </sub> = 2Vpp square.




<ul>

 <li>Plot the input and output waveforms on the same graph for two complete cycles.</li>

 <li>Comment on the gain and input-output phase relationship.</li>

</ul>




<strong><em>Repeat for C = </em></strong>1<strong><em> µF and compare to your results with C = 0.1 µF.</em></strong>

<h1>Differentiator</h1>

(Refer to Figure 3.2)

Repeat all steps as mentioned for integrator.




<strong>Laboratory Procedure: Use +/- </strong><strong><sub>21</sub> Volts to power Op-Amp.</strong>

Build both Integrator and Differentiator circuits in the lab. Repeat all the steps from the Simulation section. Compare your results with Simulation. Comment on and explain any discrepancies. Use the same voltage and resistance values that were used in the simulation. <em> </em>




<strong>Note:</strong> some of circuits will produce distorted or clipped outputs for the given inputs. For the lab report, comment on what causes this and what can be changed so that these distortions do not occur. What happens to the gain of these circuits based on your recommended changes? It is recommended that you use Multisim to help you with this.




Solve for the output of the integrator and differentiator circuits for each input by hand.