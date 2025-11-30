# What is UNO CNC Enclosure?
An easy to print and assemble enclosure for [Arduino UNO](https://docs.arduino.cc/hardware/uno-rev3/) and CNC Shield V3. The fan at the front keeps the electronics cool and the patch panel at the back ensures easy cable management.

![Actual photo of the enclosure](https://raw.githubusercontent.com/mosomate/uno-cnc-enclosure/refs/heads/main/docs/enclosure_irl.png)

# Disclaimer
**I don't take any responsibilities for injuries and/or any damage caused by this design. Build at you own risk!**

# 3D printing
You can download all the necassary STL files for 3D printing from the project's Thingiverse page:

[Enclosure for Arduino UNO + CNC shield](https://www.thingiverse.com/thing:7212313)

Please refer the Thingiverse page to pick the right STL for your needs and for printing tips!

# BOM
**General**
- 1 pc of 3D printed **bottom** part
- 1 pc of 3D printed **top** part
- 1 [Arduino UNO](https://docs.arduino.cc/hardware/uno-rev3/) board
- 1 CNC shield and [Pololu steppers](https://www.pololu.com/product/1182) (or stepper boards with the same form factor) for each axis
- 2 pcs of **M3x4** screws. These are not easy to source, you better shorten longer screws
- 4 pcs of **M3x25** screws
- 1 fan. It can be a **25x25x10 mm** fan, or **Ebm-papst** fabulous **25x25x8 mm** fan. If you pick this, a fan grill (STL can be found on the Thingiverse page) is also needed
- 1 patch panel (see details below)

**For the patch panel**
- Prototyping PCB with the measurements shown below: ![Raw patch panel](https://raw.githubusercontent.com/mosomate/uno-cnc-enclosure/refs/heads/main/docs/raw_patch_panel.png)
- ? pcs of any wire-to-board connector with 0.1" pitch. My recommendation is **JST**'s [XH series](https://www.jst-mfg.com/product/pdf/eng/eXH.pdf) connectors
- ? pcs of pin header connectors to wire the patch panel to the CNC shield. **Ninigi**'s [NSR series](https://ninigi.com/gb/en/product/ninigi/pin-headers/nsr-01/112937/) connectors are a good example
- Some 20-24 AWG wire

# Assembly
1. Tap M3 threads into the bottom part's four corner holes and the two Arduino mounting points (idicated by yellow arrows). A regular M3 tap drill may be sufficient for the corner holes, but not for the mounting points. I simply got a M3 screw and cut a vertical notch into it with a hacksaw.
![Raw patch panel](https://raw.githubusercontent.com/mosomate/uno-cnc-enclosure/refs/heads/main/docs/assembly_1.png)
2. Mount the Arduino UNO with the **M3x4** screws (mounting point are indicated with yellow arrows). Then, attach the CNC shield.
![Raw patch panel](https://raw.githubusercontent.com/mosomate/uno-cnc-enclosure/refs/heads/main/docs/assembly_2.png)

# License
Shield: [![CC BY-NC 4.0][cc-by-nc-shield]][cc-by-nc]

This work is licensed under a
[Creative Commons Attribution-NonCommercial 4.0 International License][cc-by-nc].

[![CC BY-NC 4.0][cc-by-nc-image]][cc-by-nc]

[cc-by-nc]: https://creativecommons.org/licenses/by-nc/4.0/
[cc-by-nc-image]: https://licensebuttons.net/l/by-nc/4.0/88x31.png
[cc-by-nc-shield]: https://img.shields.io/badge/License-CC%20BY--NC%204.0-lightgrey.svg