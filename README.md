# 6-key HackPad by Ondkos
<img src=assets/Render.png alt="Render"/>

This MacroPad was made for [Hackclub Hackpad](https://hackpad.hackclub.com). 

It's a 6-key macropad witch uses XIAO RB2040. It also has  2 LEDs and runs on KMK. It is upgraded version of the [tutorial one](https://hackpad.hackclub.com/guide).

Through the process of making this one, I beceme interested in PCB design and all the stuff around the hackpad. I don't have much time now (because of school), but durning the summer holidays I would like to try to make entire keyboard (with keys in matrix) 

### Chalanges
I had never used KMK or QMK before. I tried QMK but then eventually decided that KMK was easier to understand and use.

## PCB
Here's my PCB! It was made in KiCad. Because it only has 6 keys, it doesn't use matrix to make it easier.

#### Schematic

<img src=assets/Schematic.png alt="Schematic"/>

#### PCB

<img src=assets/PCB.png alt="PCB"/>


## CAD Model:

It has 2 separate printed pieces. The bottom is where everthing is housed, and the top secures the PCB in place. It has big hole so you can see the electronics (not the best decision, I know).

<img src=assets/CAD.png alt="CAD"/>
<img src=assets/CAD2.png alt="CAD2"/>

Made in Fusion360.

## Key mapping

It can do anything that you like, but at this point it does this

| Keys | Action |
| :--- | :--- |
| <kbd>1st</kbd> | Makes screenshot |
| <kbd>2nd</kbd> | Delete |
| <kbd>3rd</kbd> | Testing macro |
| <kbd>4th</kbd> | < |
| <kbd>5th</kbd> | > |
| <kbd>6th</kbd> | Restart hackpad |

## Specifications

BOM: 
- 6x Cherry MX Switches
- 2x SK6812 MINI Leds
- 1x [XIAO RP2040](https://wiki.seeedstudio.com/XIAO-RP2040/)
- 6x Blank DSA Keycaps
- 4x M3x16 Bolt
- 4x M3 Heatset

Others:
- [KMK Firmware](https://github.com/OndrejVacekSPSCL/6-key-HackPad-by-Ondkos/blob/main/production/main.py)
- [Top.step](https://github.com/OndrejVacekSPSCL/6-key-HackPad-by-Ondkos/blob/main/production/Top.step)
- [Bottom.step](https://github.com/OndrejVacekSPSCL/6-key-HackPad-by-Ondkos/blob/main/production/Bottom.step)
- [Custom PCB](https://github.com/OndrejVacekSPSCL/6-key-HackPad-by-Ondkos/blob/main/PCB)

#### Cool HackPads by other HackClubers
[RoyTyper](https://github.com/hackclub/hackpad/tree/main/hackpads/RoyTyper)

[1 Up Hackpad](https://github.com/hackclub/hackpad/tree/main/hackpads/1-Up-Hackpad)

[B-Deck](https://github.com/hackclub/hackpad/tree/main/hackpads/B-Deck)

[Minecraft Circle Hotbar](https://github.com/hackclub/hackpad/tree/main/hackpads/MinecraftCircleHotbar)

[Macro Pad V.1](https://github.com/hackclub/hackpad/tree/main/hackpads/Macro%20Pad%20V.1)
