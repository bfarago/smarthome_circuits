# smarthome_circuits
Theoretical schematics and simulations.

LTspice projects
---------------
- Some knowledge in electricity. :)
- LTspice (Analog Devices) https://www.analog.com/en/design-center/design-tools-and-calculators/ltspice-simulator.html#

smartsw_N
---------
How capacitors works in the "well known" circuit... You can simulate with different values for different load.
![fig1](img/smartsw_N_fig1.png?raw=true "fig1")

smartsw_alternate
-----------------
I wrote ltspice modells for spdt and cross switches. I drow 3 switch alternate configuration, and try to find how can we get necessary power for a smart device.
The problems are actually: half-sine may harm the device (not sure). With diodes, the capacitor could double the transients.
Because of the home switches could switch any point/phase , a dc step can occure with the capacitors. So diodes should tolerate more than 400V.
![fig2](img/smartsw_alternate_fig2.png?raw=true "fig2")
![fig3](img/smartsw_alternate_fig3.png?raw=true "fig3")


