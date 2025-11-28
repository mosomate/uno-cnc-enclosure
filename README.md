# What is UNO CNC Enclosure?
An easy to print and assemble enclosure for [Arduino UNO](https://docs.arduino.cc/hardware/uno-rev3/) and CNC Shield V3. The fan at the front keeps the electronics cool and the patch panel at the back ensures easy cable management.

![Actual photo of the enclosure](https://raw.githubusercontent.com/mosomate/uno-cnc-enclosure/main/docs/enclosure_irl.png)

# Disclaimer
**I don't take any responsibilities for injuries and/or any damage caused by this design. Build at you own risk!**

# 3D printing
You can download all the necassary STL files for 3D printing from the project's Thingiverse page:

[Enclosure for Arduino UNO + CNC shield](https://www.moddiy.com/products/Special-Mini-Low-Profile-ATX-Power-GPU-PCIE-Connector-for-PCB-Board.html)

There are multiple versions from either the bottom and the top part. Please refer the Thingiverse page to pick the right one for your needs.

# BOM
- 1 pc of 3D printed **bottom** part
- 1 pc of 3D printed **top** part
- 1 [Arduino UNO](https://docs.arduino.cc/hardware/uno-rev3/) board
- 1 CNC shield and [Pololu steppers](https://www.pololu.com/product/1182) (or stepper boards with the same form factor) for each axis
- 2 pcs of **M3x4** screws. These are not easy to source, you better shorten longer screws
- 4 pcs of **M3x25** screws
- 1 fan. It can be a **25x25x10 mm** fan, or **Ebm-papst** fabulous **25x25x8 mm** fan. If you pick this, a fan grill (STL can be found on the Thingiverse page) is also needed
- Prototyping PCB to make the patch panel (see details below)
- ? pcs of any wire-to-board connector with 0.1" pitch for the patch panel. My recommendation is **JST**'s [XH series](https://www.jst-mfg.com/product/pdf/eng/eXH.pdf) connectors. The number and version of these is heavily dependent on your needs, we'll cover this topic below
- ? pcs of pin header connectors to wire the patch panel to the CNC shield. **Ninigi**'s [NSR series](https://ninigi.com/gb/en/product/ninigi/pin-headers/nsr-01/112937/) connectors are a good example
- Some 20-24 AWG wire