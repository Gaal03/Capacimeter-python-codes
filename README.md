# Capacimeter-python-codes

This folder agregattes all the codes we use to comunicate with the Lock-in SR830 and perform the self-assembling process with an Arduino UNO.

The file Lock-in SR830 defines couple of functions that starts the communication with the equipment and performs an auto sensing procedure to auto adjust the voltage range of the Lock-in input signal. The MonoLayer_analysis code defines other functions designed to ask to the equipment to acquire the output signal after the deposition of a single layer of material. This deposition routine is done with an Arduino UNO controlled by a couple of functions defined in this routine. Finally, after all the calibration and positioning of the substrate, we use the Capacimeter_LbL routine to perform an automated deposition with capacitance measurements done in between deposited monolayers.
