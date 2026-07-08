## The Story Behind Specter V1
Welcome to the Specter V1! This is a custom 9-key macropad that I designed from the ground up. I wanted a dedicated board for productivity and custom shortcuts, but more importantly, I wanted to challenge myself to handle every single step of the hardware and software design process.

While I have a lot of experience with 3D modeling in Onshape, designing a custom 2-layer PCB from scratch in KiCad was a massive learning experience for me. 

## Hardware & Features
* **The Brain:** The whole board is powered by a Seeed Studio XIAO RP2040, which packs a ton of processing power into a tiny footprint.
* **Inputs & Control:** It features 9 mechanical switches and a tactile rotary encoder (with a push-button) that is perfect for volume control, scrolling, or custom macros.
* **Display:** I integrated a small OLED screen at the top to display active macro layers and real-time status updates.
* **Custom PCB:** The board is a custom 2-layer design. To give it a personal touch, I added a custom New York Knicks logo to the front silkscreen to rep my city!
* **Enclosure:** The physical case is a custom two-part 3D-printed shell I modeled in Onshape. It is designed to fit snugly around the components and is secured together using M3 screws.
* **Firmware:** The macropad is fully programmable using QMK. Wrestling with the C code to get the rotary encoder to compile perfectly was easily the toughest part of the software side, but it runs flawlessly now.

## Screenshots
Overall Hackpad:

<img width="1264" height="894" alt="image" src="https://github.com/user-attachments/assets/5c6a182f-0b30-49f7-97b3-42f20f759fd4" />

Schematic:

<img width="1544" height="828" alt="image" src="https://github.com/user-attachments/assets/7e724150-d7d7-45da-af14-be019aafc76e" />

PCB:

<img width="776" height="684" alt="image" src="https://github.com/user-attachments/assets/c55253c8-4e6e-4d1e-84f6-82f185afd037" />
<img width="1454" height="1282" alt="image" src="https://github.com/user-attachments/assets/8fdf1046-41f8-4198-a9c9-59100185028b" />

Case:

<img width="1266" height="860" alt="image" src="https://github.com/user-attachments/assets/1eab2fe1-3317-499c-abb5-bc2c0a18239a" />
I plan on fitting the two parts of the case together by threading the M3 screws into them.

## Bill of Materials (BOM)
* 1x Seeed Studio XIAO RP2040
* 9x Mechanical Switches
* 9x 1N4148 Diodes
* 1x Rotary Encoder (with push-button)
* 1x OLED Display
* 3D Printed Case (Top and Bottom)
