# Current_Mirror-Analog_Circuit_Design

A current mirror is a circuit designed to copy a current through one active device by controlling the current in another active device of a circuit, keeping the output current constant regardless of loading.

## Problem Statement

<br>
<strong>Design a common source stage with current source load (implement using current mirror) for the following specifications:</strong> <br>
 <br>
  &emsp;Gain (A<sub>v</sub>) = 20 <br>
  &emsp;Power budget < 20 mW <br>
  &emsp;Supply voltage (V<sub>dd</sub>) = 1.8 V <br>
  &emsp;Threshold Voltage (V<sub>th</sub>) = 0.5 <br>
  &emsp;U<sub>n</sub>C<sub>ox</sub> = 100 uA/V<sup>2</sup>  <br>
  &emsp;U<sub>p</sub>C<sub>ox</sub> = 200 uA/V<sup>2</sup>  <br>
  &emsp;Output Swing Limit = 0.5 peak to peak <br>
  &emsp;λ<sub>1</sub> = 0.1 V<sup>-1</sup> <br>
  &emsp;λ<sub>2</sub> = 0.2 V<sup>-1</sup>

## Schematic

![Current_Mirror(Schematic) (1)](https://github.com/rishab9878/Current_Mirror-Analog_Circuit_Design/assets/130205508/f0febc88-97ff-4102-a743-9b71af76b5a6)

## DC Analysis

![Current_mirror(DC) (1)](https://github.com/rishab9878/Current_Mirror-Analog_Circuit_Design/assets/130205508/4b459bad-aedf-407a-a40d-25a51a95bc59)

## Transient Analysis

![Current_mirror(trans) (1)](https://github.com/rishab9878/Current_Mirror-Analog_Circuit_Design/assets/130205508/a82c0881-74b8-4bb2-8c60-ecc8fab7e725)

When we compare peak to peak voltage of output we get the following values:<br>
<br>
  &emsp; Upper peak - 1.02 V <br>
  &emsp; Lower peak - 811.07 mV

