# Design-of-Folded-Cascode-Operational-Amplifier
Design of Folded Cascode Operational Amplifier in closed loop configuration in Cadence Virtuoso using tsmcN65 technology. the transistors used from this technology is nch_lvt,pch_lvt and the resistors,capacitors,voltage,current sources, iprobe are taken from the analog library
The default Channel length of nch_lvt,pch_lvt is 60nm. The channel length I have taken is greater than 2 times of the default channel lenght i.e 225nm.

The primary advantage of the folded structure is in the choice of the voltage levels because if doesn't stack the cascode transistor on the top of the input device. 
It has comparatively superior frequency response then two stage op-amp.
Better PSRR then two stage op-amp.
Power consumption nearly equals to two stage op-amp. 

The Specifications of this opamp are as follows:
Vdd = 1.2v  Vss =0 , Closed loop Gain = 60dB , Phase margin = 79 degrees

The configuration which I have implemented can used for multiple common modes(which can be used for wide range common modes without changing the gain) in open loop configuration.
The second stage has also being used along with the compensation.
In the same circuit, for the biasing of the current mirror loads, the direct bias fro the dc voltage source is not given instead biasing was made using a current mirror and diode connected in series which ensures the internal generation of that bias voltage and giving as a bias.

The simulation results has been attached.
