The cell unit has the sensors. It needs to be cheap and easy to install at every production cell. A cell that has multiple WIP at a time needs the ability to time them all at once, for example a mill with dual pallets needs a HE sensor for each pallet and a painting booth that paints multiple pieces the same colour at once needs a bunch of HE sensors.
The most basic cell unit is one of each sensor attached to an arduino with the ability to send data to the server.
It is possible to make both battery driven and stationary ac-connected cell units. When a PCB-design is made it should have the circuits for both and populate only necessary components for the application.
Andon should have a connector for external buttons.

Different cell unit designs will be placed in this folder.

Raspberry Pi module for when a screen is needed, like with the paint booth, multi-pallet mill, order picking or info displays.
NodeMCU for when input complexity and output resolution allows.