---
title: Assembly Guide
---

![balenaEtcherPro_logo_dark](https://user-images.githubusercontent.com/15323961/89873050-c3451400-dbb1-11ea-8330-3029ea6f75f8.png)

<br/>

# Assembly guide
EtcherPro [v1.1.3](https://github.com/balena-io-hardware/etcherPro/tree/v1.1.3)

## Contents

- [EtcherPro ready to ship](#EtcherPro-ready-to-ship)
  - [EtcherPro packed](#EtcherPro-packed)
    - [Cable bag subassembly](#Cable-bag-subassembly)
    - [EtcherPro in bag](#EtcherPro-in-bag)
      - [EtcherPro device](#EtcherPro-device)
        - [Top subassembly](#Top-subassembly)
          - [Top shell complete](#Top-shell-complete)
            - [Top shell with UV resin](#Top-shell-with-UV-resin)
            - [Fan blower complete](#Fan-blower-complete)
            - [Magnets complete](#Magnets-complete)
              - [PCBA complete-testing](#PCBA-complete-testing)
          - [PCBA complete](#PCBA-complete)
            - [CM subassembly](#CM-subassembly)
            - [DC harness](#DC-harness)
        - [Bottom subassembly](#Bottom-subassembly)
          - [PSU complete](#PSU-complete)
            - [AC harness](#AC-harness)

## AC harness

| Tools | Image |
|-|-|
| Cable cutter-stripper | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Sub-processes/Wire%20cutting-stripping%20photos/Cable-cutter-stripper.jpg?raw=true" width="250" /> |
| Cable crimper | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Sub-processes/Cable-crimping-photos/Crimping-machine.jpg?raw=true" width="250" /> |
| Manual cable cutter | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/cable-cutter.jpg?raw=true" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| AWG14 - 2.5mm² brown insulated single core cable spool | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Cables/brown-single-core.jpg?raw=true" width="250" /> |
| AWG14 - 2.5mm² blue insulated single core cable spool | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Cables/blue-single-core.jpg?raw=true" width="250" /> |
| AWG14 - 2.5mm² yellow insulated single core cable spool | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Cables/yellow-single-core.jpg?raw=true" width="250" /> |
| Insulated blue quick connect terminals 6.4x0.8mm for 16-14AWG/ 1.5-2.5mm² | 6 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/blue-quick-connect.jpg?raw=true" width="250" /> |

#### Steps

1. Cut the following length of Cables

- Follow the AC-DC wire cutting-stripping [instructions](https://github.com/balena-io-hardware/etcherPro-assemblyGuide/blob/master/output/Sub-processes/AC-DC-wire-cutting-stripping.md)

  - 1 x **40cm** - brown
  - 1 x **40cm** - blue
  - 1 x **40cm** - yellow
  - 1 x **14cm** - brown
  - 1 x **14cm** - blue
  - 1 x **14cm** - yellow

2. Install a terminal to one side of each cable using the crimper

- Follow the crimping [instructions](https://github.com/balena-io-hardware/etcherPro-assemblyGuide/blob/master/output/Sub-processes/Cable-crimping.md)

  - Do not remove the trimmed insulation on the other side of the cables

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Cables/AC-cables-plus-terminals.jpg?raw=true" width="600" />
</p>

## PSU complete

| Parts | Qty | Image |
|-|-|-|
| [AC harness](#AC-harness) | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Cables/AC-cables-plus-terminals.jpg?raw=true" width="250" /> |
| Meanwell UHP-200A-5 | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Meanwell%20PSU.jpg?raw=true" width="250" /> |
| 3M VHB 5952 double-sided foam pads | 2 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/3m-double-tape.jpg?raw=true" width="250" /> |

#### Steps

1. Install the foam pads on the bottom of the power supply as in the picture below
  - Do not remove the red foam pad cover

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Power-supply-pads.jpg?raw=true" width="600" />
</p>

2. Install the AC cables to the power supply

- The brown cables should be connected to 'L'
- The blue cables should be connected to 'N'
- The yellow cables should be connected to '⏚'
- Install the 14cm cable and the 40cm on the AC side of the PSU. Leave them straight by having the stripped edge of the sort wire on the left side of the screw and other edge of the longer wire on the right side and then screw them in place.

- For BOSCH GSR12V screwdriver use speed **1** - torque **5**
- For BOSCH GSB120 screwdriver use speed **1** - torque **3** (should be set to 'Screw', not 'Drill' or 'Hammer')

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/PSU-complete.jpg" width="600" />
</p>

## Bottom subassembly

| Tools | Image |
|-|-|
| File | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/File.jpg" width="250" /> |
| M3x8mm torx countersunk screw | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/M3x8mm%20torx%20screw.jpg" width="250" /> |
| Countersink drill bit 6.3mm | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/countersink-6.3.jpg" width="250" /> |
| PSU & cable base jig (PSU1) | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Jigs/PSU%20%26%20cable%20base%20jig%20(PSU1).jpg" width="250" /> |
| Insulated flat or Phillips screwdriver | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/phillips-screwdriver.jpg" width="250" /> <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/flat-screwdriver.jpg" width="250" /> |
| BOSCH screwdrivers | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/Bosch-GSR-12V-GSB-120LI.jpg" width="250" /> |
| Metal label jig (ML2) | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Jigs/Metal%20label%20jig%20(ML2).jpg" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| [PSU complete](#PSU-complete) | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/PSU-complete.jpg" width="250" /> |
| Bottom shell | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Bottom%20shell.jpg" width="250" /> |
| Power entry module C14 | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Entry%20module%20C14.PNG" width="250" /> |
| Power entry module C13 | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Entry%20module%20C13.PNG" width="250" /> |
| Long brown cable with terminals (section 1.1) | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Cables/long-brown-cable-with-terminals.jpg" width="250" /> |
| Long blue cable with terminals (section 1.1) | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Cables/long-blue-cable-with-terminals.jpg" width="250" /> |
| Long yellow cable with terminals (section 1.1) | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Cables/long-yellow-cable-with-terminals.jpg" width="250" /> |
| Short brown cable with terminals (section 1.1) | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Cables/short-brown-cable-with-terminals.jpg" width="250" /> |
| Short blue cable with terminals (section 1.1) | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Cables/short-blue-cable-with-terminals.jpg" width="250" /> |
| Short yellow cable with terminals (section 1.1) | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Cables/short-yellow-cable-with-terminals.jpg" width="250" /> |
| Metal label | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Metal%20label.jpg" width="250" /> |

#### Steps

1. Inspect the top shell for any imperfections and use the file to remove any rough edges

2. Inspect the 4 x M3 countersunk holes of the bottom shell
  - Use the M3 countersunk screw and make sure it sits flush with the surface
  - If need be, use the medium countersink drill bit to increase the countersunk of the plastic so that the screw sits flush with the surface
  - Use a vacuum cleaner to remove any plastic debris

<p align="center">
   <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/M3-countersunk-holes.jpg?raw=true" width="600" />
   </p>

<p align="center">
   <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/M3-sits-flush.jpg?raw=true" width="600" />
   </p>

3. Install the power supply using the PSU jig.
  - Make sure the AC power input is placed on the right-hand side
  - Make sure the power supply is securely fastened in place via the double-sided tape

  <p align="center">
     <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/PSU-jig.jpg?raw=true" width="600" />
     </p>

4. There are two rectangular openings for the entry modules, one on the left-hand side of the bottom shell and one on the right-hand side.
  - Insert the C14 connector on the smaller opening, the connector's terminals should be on the inner part of the bottom shell
  - Make sure the snap-on system is engaged and the connector can't be pushed out
  - Make sure the '⏚' terminal is placed towards the bottom

5. Insert the C13 connector on the larger opening, the connector's terminals should be on the inner part of the bottom shell
  - Make sure the snap-on system is engaged and the connector can't be pushed out
  - Make sure the '⏚' terminal is placed towards the bottom

6. Connect the 14cm cables to the C13 connector
  - The brown cables should be connected to 'L'
  - The blue cables should be connected to 'N'
  - The yellow cables should be connected to '⏚'

7. Connect the 40cm cables to the C14 connector
  - Guide the 3 cables behind the power supply
  - The brown cables should be connected to 'L'
  - The blue cables should be connected to 'N'
  - The yellow cables should be connected to '⏚'

8. Inspect that all cables and connectors are securely fastened and properly aligned

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Bottom-plus-PSU-mounted.jpg" width="600" />
  </p>

9. Remove the double-side tape protection film from the metal label and install it using the label jig
  - Pay attention on the orientation of the label, ideally use a magnet to help you hold the label
  - Make sure the metal label is securely fastened in place

<p align="center">
   <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Metal-label-plus-magnet.jpg?raw=true" width="600" />
   </p>


## DC harness

- AC-DC wire cutting-stripping [instructions](https://github.com/balena-io-hardware/etcherPro-assemblyGuide/blob/master/output/Sub-processes/AC-DC-wire-cutting-stripping.md)

- Crimping [instructions](https://github.com/balena-io-hardware/etcherPro-assemblyGuide/blob/master/output/Sub-processes/Cable-crimping.md)

| Tools | Image |
|-|-|
| Cable cutter-stripper | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Sub-processes/Wire%20cutting-stripping%20photos/Cable-cutter-stripper.jpg?raw=true" width="250" /> |
| Cable crimper | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Sub-processes/Cable-crimping-photos/Crimping-machine.jpg?raw=true" width="250" /> |
| Manual cable cutter | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/cable-cutter.jpg?raw=true" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| AWG16 - 1.5mm² red and black insulated cable spool | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Cables/red-black-dual-core.jpg" width="250" /> |
| Insulated blue fork M4/4.3mm for 16-14AWG/ 1.5-2.5mm²| 7 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Insulated%20fork.jpg" width="250" /> |

#### Steps

1. Cut the following length of Cables

    - 2 x **27cm** - red (dual core)
    - 2 x **27cm** - black (dual core)
2. Install a fork terminal to the 7mm side of each cable using the crimper
  - Do not remove the trimmed insulation on the other side of the cables

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Cables/DC-cables-with-terminals.jpg?raw=true" width="600" />
</p>

## CM subassembly

| Tools | Image |
|-|-|
| BETA screwdriver | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/Beta-screwdriver.jpg" width="250" /> |
| File | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/File.jpg" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| Compulab iMX8 compute module | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/boards/Combulab-iMX8%20compute%20module.jpg?raw=true" width="250" /> |
| Heatsink | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Heatsink.png?raw=true" width="250" /> |
| M2x3.5mm phillips countersunk screw	 | 2 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/M2x3.5mm%20phillips%20screw.png?raw=true" width="250" /> |
| Thermal compound paste | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/thermal-paste.png?raw=true" width="250" /> |
| Flexible antenna | 2 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Flexible%20antenna.jpg?raw=true" width="250" /> |
| Antenna connector clip | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Jigs/Antenna%20connector%20jig.jpg?raw=true" width="250" /> |

#### Steps

1. Place the compute module down with the CPU facing upwards
2. Apply a small amount of thermal compound and spread it to cover the CPU's top surface
3. Place a heatsink on top with the fins pointing upwards. Align the screw holes making sure to place the hole with the single fins closer to the compute modules pin and the hole with the double away from the pins

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/heatsink-orientation.png?raw=true" width="600" />
</p>

4. Install the 2 screws and tighten them very carefully
5. Install both antennas by connecting the w.FL connector of the antenna to the bottom w.FL connector of the compute module
6. Apply gentle vertical pressure with the File and make sure the connector is properly mounted by giving them a few twists.
- **Caution** Before you put pressure on mount the w.FL connectors between the CM and the antennas make sure that
both of the connectors are perfectly aligned to prevent damage them.
7. Carefully insert the antenna connector clip to secure the w.FL connectors in place

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/CM-sub-assembly.jpg" width="600" />
</p>

8. Flash the CMs after assembly using the Flashing board.

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Flashboard.jpg" width="600" />
</p>

- Make sure that the power is off
- Place the CM on the board.
- Power on the board

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Power-on-the-flashboard.jpg" width="600" />
</p>


- If the CM is functional and flashing you should see a green LED blinking.
* Tip: Try again using another CM slot in a different mainboard to the flashing board if you don't see any green LED blinking.
If the problem continues, please set it away for troubleshooting and repair.
- After the LED stops blinking the CM is flashed.

## PCBA complete

| Tools | Image |
|-|-|
| BOSCH screwdrivers  | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/Bosch-GSR-12V-GSB-120LI.jpg" width="250" /> |
| 5mm HEX socket driver  | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/5mm-Hex-nut.jpg" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| [DC harness](#DC-harness) | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Cables/DC-cables-with-terminals.jpg" width="250" /> |
| [CM subassembly](#CM-subassembly) | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/CM-sub-assembly.jpg" width="250" /> |
| EtcherPro mainboard | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/boards/EtcherPro%20mainboard%20v2.3.4.jpg" width="250" /> |
| USB_to_SD_Slot v1.1 | 16 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/boards/USB-to%20SD%20slot.jpg" width="250" /> |
| M3 female to male 20mm standoffs | 2 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/M3-standoff-20mm.jpg" width="250" /> |

#### Steps

1. Remove excess plastic parts from the mainboard, if any

- Use the pliers to remove any additional plastic pieces, but make sure you are just holding the piece you want to get rid of before applying any pressure.

2. Using the 9mm side of each cable that is lacking the fork terminal, attach the DC cables to the mainboard, then tighten them down using the BOSCH screwdriver.

- Pay extra attention to make sure the **red** cables are connected to the terminals marked with **+5v** and the **black** cables are connected to the terminals marked with **GND**
- For BOSCH GSR12V screwdriver use speed **1** - torque **1**
- For BOSCH GSB120 screwdriver use speed **1** - torque **1** (should be set to 'Screw', not 'Drill' or 'Hammer')

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/boards/DC-cables-installed.jpg" width="600" />
</p>


3. Orient the mainboard so that the header connectors pointing upwards
4. Install the compute module on the SODIMM connector
  - Before you put the CM into position, it should be at approximately 20-degree angle. Then push it in place.

  <p align="center">
    <img src=".https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Properly-algned-CM.jpg" width="600" />
  </p>


  - Check that the side springs of the SODIMM connector are properly engaged
  - Gently pull one of the springs so it disengages and check if the CM lifts, then check the other spring
  - If the CM lifts when either of the springs disengages, remove the CM, push the springs towards the inside of the SODIMM connector to preload them, and then go back to step 3
  - For a final check, gently try to move the CM by pushing the heatsink to ensure it's properly secured

5. Install 16 card reader adapters by carefully connecting them to the header connectors
  - The card readers have a small peg that should also fit in the respective mainboard hole

6. Check if any of the LEDs is accidentally bent
  - Make sure to avoid touching or accidentally pushing the LEDs during installation

7. Take the 5mm HEX socket driver and attach it to the BOSCH screwdriver if it isn't already installed. Install the 20mm standoffs into the holes on the right and left flaps of the mainboard from the card reader's side, keeping the small blue box containing them next to you and on the workbench.
- For BOSCH GSR12V screwdriver use speed **2** - torque **1**
- For BOSCH GSB120 screwdriver use speed **2** - torque **1** (should be set to 'Screw', not 'Drill' or 'Hammer')

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/boards/Mainboard-subassembly.jpg?raw=true" width="600" />
</p>


## Magnets complete

| Tools | Image |
|-|-|
| Tweezers | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/tweezers.jpg" width="250" /> |
| Lancet | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/Lancet.jpg" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| 25x5x5mm N52 Neodymium magnets | 2 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/N52%20Neodymium%20magnet.jpg?raw=true" width="250" /> |
| Adhesive tape (MG1) | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/3M-adhesive-tape.jpg?raw=true" width="250" /> |

#### Steps

1. Apply the 3M adhesive tape to a whole magnet row and use the lancet to cut the 3M adhesive tape.

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Magnets-plus-adhesive-tape.jpg?raw=true" width="600" />
  </p>

2. Separate 1 piece of magnet using the Lancet.
  - Do not remove the protective film

## Fan blower complete

| Parts | Qty | Image |
|-|-|-|
| Fan blower | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Fan%20blower.jpg?raw=true" width="250" /> |
| 3M VHB 5952 double-sided foam pads | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/3m-double-tape.jpg?raw=true" width="250" /> |

#### Steps

1. Install the foam pad on the plastic back side of the fan blower
  - Do not remove the protective film
  - Position the foam pad accordingly, making sure to leave one of the fan's air exits uncovered as indicated in the photo.
  - Make sure the foam pad is within the fan's limitations and not beyond them.

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Fan-blower-complete.jpg" width="600" />
</p>

## Top shell with UV resin

| Tools | Image |
|-|-|
| File | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/File.jpg" width="250" /> |
| UV curing station | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Sub-processes/UV-curing-photos/Curing-station.jpg" width="250" /> |
| UV protective goggles | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Sub-processes/UV-curing-photos/protection-goggles.jpg" width="250" /> |
| Protective gloves | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Sub-processes/Painting-process-photos/disposable-gloves.jpg" width="250" /> |
| Syringe and needle | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Sub-processes/UV-curing-photos/Syringe-plus-needle.jpg" width="250" /> |
| Paper towel | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Sub-processes/UV-curing-photos/Paper-towel.jpg" width="250" /> |
| Cardboard | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Sub-processes/UV-curing-photos/Cardboard.jpg" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| Top shell | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Top%20shell.jpg?raw=true" width="250" /> |
| UV resin in bottle | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Sub-processes/UV-curing-photos/Resin-bottle.jpg?raw=true" width="250" /> |
| Plastic weld solvent | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/plastic-weld-solvet.png?raw=true" width="250" /> |

#### Steps

1. Inspect the top shell for any imperfections and use the file to remove any rough edges

2. Inspect the injection moulded inserts and make sure everything is properly welded in place.
  - If any inserts are loose, apply 1-2 drops of plastic weld solvent with the syringe from the inside of the top shell to weld it in place
  - Make sure the solvent won't drip on the front side
  - Always use a small thick cardboard under the top shell to create a small lift

3. Prepare for the UV-curing process
  - Wear protective gloves and goggles
  - Bring and keep the UV-curing station next to you and turn on both of the  LED lamps
  - Load the syringe with resin without the needle being installed
  - Keep the resin bottle closed at all times
  - Install the needle on the syringe
  <p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Sub-processes/UV-curing-photos/Needle-installation.jpg?raw=true" width="600" />
  </p>

  - Hold the syringe upwards and press the plunger slowly to remove excess air, always covered by a paper towel
  <p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Sub-processes/UV-curing-photos/Remove-excess-air.jpg?raw=true" width="600" />
  </p>

  - Be sure that your protective gloves are clean without any remaining resin on them to avoid contaminating the Top-shell

4. Place the top shell upside down and place the cardboard under the slots
  <p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Sub-processes/UV-curing-photos/Cardboard-under-the-shell.jpg?raw=true" width="600" />
  </p>

5. Direct the needle close and above the LED hole and press the plunger extremely gently and slowly, a tiny drop is enough
  - Be careful as the needle may keep dripping
  - The holes should be perfectly clear, if plastic debris blocks the holes remove them using tweezers
  <p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Sub-processes/UV-curing-photos/Proper-hight-applying-resin.jpg?raw=true" width="600" />
  <br/>
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Sub-processes/UV-curing-photos/Properly%20applied%20resin.jpg?raw=true" width="600" />
  </p>

6. After the resin is applied to 16 holes place the top shell halfway through to the curing station making sure that both LED lamps are pointing to the LED holes
  - You can use a toothpick to gently push the cured resin to make sure it feels solid and therefore is properly cured
  <p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Sub-processes/UV-curing-photos/Curing.jpg?raw=true" width="600" />
  </p>

## Top shell complete

| Tools | Image |
|-|-|
| 5mm HEX socket driver | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/hex-socket-5.jpg" width="250" /> |
| BOSCH screwdrivers | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/Bosch-GSR-12V-GSB-120LI.jpg" width="250" /> |
| Stand-off alignment jig (HT1) | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Jigs/Heat%20threaded%20insert%20jig%20(HT1).jpg" width="250" /> |
| Fan blower jig (FB1) | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Jigs/Fan%20blower%20jig%20(FB1).jpg" width="250" /> |
| Lancet | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/Lancet.jpg" width="250" /> |
| Glue-gun | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/Glue-gun.jpg" width="250" /> |
| 2-part epoxy mixing nozzle | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/Epoxy-mix-nozzle.jpg" width="250" /> |


| Parts | Qty | Image |
|-|-|-|
| M3x8mm HEX male to female self threading standoffs | 8 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Self-threated-8mm-stanoff.jpg" width="250" /> |
| [Magnets complete](#Magnets-complete) | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Magnets-plus-adhesive-tape.jpg" width="250" /> |
| [Fan blower complete](#Fan-blower-complete) | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Fan-blower-complete.jpg" width="250" />  |
| Maxen 7in screen | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/7in%20screen%26%20i2c%20touchpanel.jpg" width="250" /> |
| 2-part structural adhesive liquid glue | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/2-part-adhesive-glue.jpg" width="250" /> |

#### Steps

1. Place the top shell up-side-down and install the standoffs, use the stand-off alignment jig to find the correct locations
  - Use only **BOSCH GSR12V screwdriver**  use speed  **1** - torque **1**

<p align="center">
   <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Stand-offs-alignment.jpg" width="600" />
</p>

2. Insert the magnet to magnet holder with the tape side facing the bottom of the holder

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Installing-magnet.jpg?raw=true" width="600" />
</p>

3. Repeat the previous step for the remaining magnet holder

4. Use the 'Fan blower jig (FB1)' to install the fan blower in place

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/fan-aligned-assembled.jpg?raw=true" width="600" />
</p>

5. Take a screen module (touch panel + display) and carefully remove the double-sided mounting tape on the touchpanel from the backside of the screen module
  - Do not remove the screen's protection film
  - The 2 flat cables should be orientated towards the EtcherPro slots

  <p align="center">
    <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Mounting-tape.jpg" width="600" />
  </p>

6. Insert the screen in the respective opening and make sure it's properly aligned
  - Make sure the screen is properly attached to the top shell

  <p align="center">
    <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Proper-alignm..jpg" width="600" /> <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Install-screen.jpg" width="600" />
  </p>

7. To properly mount the screen, flip the shell over and push the top shell in the direction of the screen where the adhesive tape is located.

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Push-in-place.jpg" width="600" />
  </p>

- Use the glue gun with the nozzle attached to apply the 2-part adhesive glue to the screen's four corners.
- Make sure that the glue is properly applied by covering both the screen and the plastic surface.

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Glue-applied.jpg" width="600" /> <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Screen-installed.jpg" width="600" />
</p>

## Top subassembly

| Tools | Image |
|-|-|
| 5mm HEX socket driver | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/hex-socket-5.jpg?raw=true" width="250" /> |
| BOSCH screwdrivers | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/Bosch-GSR-12V-GSB-120LI.jpg?raw=true" width="250" /> |
| Tweezers | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/tweezers.jpg?raw=true" width="250" /> |
| Logo sticker jig (LS1) | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Jigs/Logo%20sticker%20jig%20(LS1).jpg?raw=true" width="250" /> |
| Methylated spirits or IPA alcohol | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/methylated-spirit.png?raw=true" width="250" /> |
| Cotton rug | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/Cotton-rug.png?raw=true" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| [PCBA complete](#PCBA-complete) | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/boards/Mainboard-subassembly.jpg" width="250" /> |
| [Top shell complete](#Top-shell-complete) | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Complete-Top-shell.jpg" width="250" /> |
| M3x8mm HEX male to female standoffs | 4 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/M3%20male-female%206mm%20standoff.jpg" width="250" /> |
| M3x10mm HEX male to female standoffs | 4 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/M3x7mm%20male-female%20standoff.jpg" width="250" /> |
| Logo sticker | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Logo%20sticker.jpg" width="250" /> |

#### Steps

1. Install the mainboard subassembly inside the top shell making sure the adapters sit in the injection molded inserts properly and the PCB holes are aligned with the standoffs
- Make sure that the display ribbon cable has passed through the PCB slot and the touch panel ribbon cable is folded towards the screen.

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/ribbon-through-PCB.jpg?raw=true" width="600" />
</p>

2. Secure the mainboard using the longer standoffs on the top row and the shorter standoffs on the bottom row
- For BOSCH GSR12V screwdriver use speed **2** - torque **1**
- For BOSCH GSB120 screwdriver use speed **2** - torque **1** (should be set to 'Screw', not 'Drill' or 'Hammer')

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/mainboard-inside-top-shell.jpg?raw=true" width="600" />
</p>

3. Connect the screen ribbon cable to the screen connector
- The screen connector has a small plastic flap that should be lifted up to accept the ribbon cable and then pushed down to secure the cable in place
- Make sure that the ribbon cable is gently pushed all the way in the connector before pushing down the connector flap

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Connect-ribbon.jpg?raw=true" width="600" />
</p>

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Ribbon-flap-down.jpg?raw=true" width="600" />
</p>

4. Connect the touchpanel ribbon cable to the touchpanel connector
- The touchpanel connector has a small plastic flap that should be lifted to accept the ribbon cable and then pushed down to secure the cable in place
- Make sure that the ribbon cable is gently pushed all the way in the connector before pushing down the connector flap

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Touchpanel-ribbon.jpg?raw=true" width="600" />
</p>

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Flap-up.jpg?raw=true" width="600" />
</p>

5. Remove the double-sided tape protection layer from the antennas and attach the antennas to the top shell
- Make sure the antennas are securely fastened in place via the double-sided tape and aligned as shown in the picture
- Pay attention not to bend the antenna cable too much
- Make sure the cable is not under tension

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/antenna-right-place.jpg?raw=true" width="600" />
</p>

6. Connect the fan blower's cable to the mainboard
- Fold the cable under the mainboard as indicated in the photo

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/fan-blower's-cable.jpg?raw=true" width="600" />
</p>

7. Using the tweezers, grab a logo sticker without removing the top protective film

8. Use the logo jig to align and install the sticker.

- Only if you are certain that the alignment is perfect should you push the sticker into place.

9. Carefully remove the protective layer using the tweezers.
- Make sure the logo sticker remains in place
- If there is residue from the sticker, use a rug with a bit of methylated spirits or alcohol to remove it

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Logo-sticker-with-jig.jpg?raw=true" width="600" />
</p>

## EtcherPro device

| Tools | Image |
|-|-|
| Torx screwdriver no 10 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/torx-10.jpg" width="250" /> |
| BOSCH screwdrivers | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/Bosch-GSR-12V-GSB-120LI.jpg" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| [Top subassembly](#Top-subassembly) | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/mainboard-inside-top-shell.jpg" width="250" /> |
| [Bottom subassembly](#Bottom-subassembly) | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Bottom-plus-PSU-mounted.jpg" width="250" /> |
| M3x8mm torx countersunk screw | 4 | <img src="./output/Assembly-guide-photos/parts/M3x8mm torx screw.jpg" width="250" /> |

#### Steps

1. Bring the bottom shell next to the top shell and secure the DC cables to the power supply output
- The red cables need to be connected to '+5V'
- The black cables need to be connected to 'GND'
- Use **only** the BOSCH GSR12V screwdriver, set speed 1 - torque 1

2. Carefully bring the 2 bottom openings of the bottom shell towards the front pegs of the top shell

3. Gently close the device
- Make sure the DC cable is free and unobstructed
- Gently pull the connectors downwards if needed
- If the connectors can’t sit in place properly most likely something is misplaced inside the device, inspect all equipment and try again

4. Install the 4 x M3 screws to secure the bottom shell to the top shell
- For the BOSCH screwdrivers, set speed  **1** - torque **1**

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Top-Bottom-open-assembled.jpg" width="600" /><img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Device-sealed.jpg" width="600" />
</p>


## EtcherPro in bag

| Parts | Qty | Image |
|-|-|-|
| Getting started sticker | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Getting-started-sticker.jpg" width="250" /> |
| EtcherPro bag | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/EP-Bag.jpg" width="250" />  |

#### Steps

1. Use a cotton rug to wipe the EtcherPro device

2. Install the Getting Started sticker near the top right corner of the screen

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/output/Batch-production-photos/Getting-started-stick-orientation.jpg" width="600" />
</p>

- Make sure the rubber feet are in place
- Make sure the screen protection film is in place
- Make sure the device doesn't have any marks or fingerprints

3. Put the device in the bag and fold the bag towards the bottom

## Cable bag subassembly

| Parts | Qty | Image |
|-|-|-|
| Cable bag | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Cable-bag.jpg" width="250" /> |
| Power cable contents | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Power-cable.jpg" width="250" /> |
| balenaEtcherPro sticker | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/EP-sticker.jpg" width="250" /> |
| I am Pro sticker | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/I-am-pro-sticker.jpg" width="250" /> |

#### Steps

1. Open the cable bag and place both of the stickers inside, seal it again.

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Cable-bag-sub-assembly.jpg" width="600" /> <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/output/Batch-production-photos/Ep-sticker-box.jpg" width="600" />
</p>

## EtcherPro packed

| Tools | Image |
|-|-|
| Packing tape dispenser gun | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/tape-dispenser.jpg?raw=true" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| [EtcherPro in bag](#EtcherPro-in-bag) | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/EP-in-the-bag.jpg" width="250" /> |
| [Cable bag subassembly](#Cable-bag-subassembly) | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Cable-bag-sub-assembly.jpg" width="250" /> |
| EtcherPro printed box | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/EtcherPro-printed-box.jpg" width="250" /> |
| Box left foam padding | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Box-left-foam.jpg" width="250" /> |
| Box right foam padding | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Box-right-foam.jpg" width="250" /> |
| Packing tape 3M 313 75ΜΜΧ66Μ | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/3M-313-packing-tape.jpg" width="250" /> |

#### Steps

1. Take a flat box and fold the bottom flaps

2. Carefully apply tape across the bottom side of the box to secure the flaps
- Make sure the tape is consistent without wrinkles

3. Place the cable bag subassembly inside the box

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/Power-cord-inside-the-box.jpg" width="600" />
</p>


4. Attach the left and right foam paddings on the EtcherPro device
- Make sure the EtcherPro bag is tidy in place

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/output/Batch-production-photos/Device-plus-foam.jpg" width="600" />
</p>

5. Place the EtcherPro device with the paddings inside the Box and ensure that the Balena logo sticker is in line with the one on the carton box
before you seal it.

6. Close the top flaps and carefully apply tape across the top side of the box to secure the flaps
- Make sure the tape is consistent without wrinkles

<p align="center">
  <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/instructions/EP-box-closed.jpg?raw=true" width="600" />
</p>

## EtcherPro ready to ship

| Tools | Image |
|-|-|
| Shipping label printer | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/Tools/Printer.jpg" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| Shipping label paper | 1 | <img src="https://github.com/balena-io-hardware/etcherPro-assemblyGuide-doc/blob/master/docs/images/Assembly-guide-photos/parts/Shipping-label.jpg" width="250" /> |

#### Steps

1. Print the shipping label

2. Attach it on the top side of the box
