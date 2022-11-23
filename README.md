![balenaEtcherPro_logo_dark](https://user-images.githubusercontent.com/15323961/89873050-c3451400-dbb1-11ea-8330-3029ea6f75f8.png)

<br>

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
          - [PCBA complete](#PCBA-complete)
            - [CM subassembly](#CM-subassembly)
            - [DC harness](#DC-harness)
        - [Bottom subassembly](#Bottom-subassembly)
          - [PSU complete](#PSU-complete)
            - [AC harness](#AC-harness)

## AC harness

| Tools | Image |
|-|-|
| Cable cutter-stripper | <img src="./docs/images/Sub-processes/Wire cutting-stripping photos/Cable-cutter-stripper.jpg" width="250" /> |
| Cable crimper | <img src="./docs/images/Sub-processes/Cable-crimping-photos/Crimping-machine.jpg" width="250" /> |
| Manual cable cutter | <img src="./docs/images/Assembly-guide-photos/Tools/cable-cutter.jpg" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| AWG14 - 2.5mm² brown insulated single core cable spool | 1 | <img src="./docs/images/Assembly-guide-photos/Cables/brown-single-core.jpg" width="250" /> |
| AWG14 - 2.5mm² blue insulated single core cable spool | 1 | <img src="./docs/images/Assembly-guide-photos/Cables/blue-single-core.jpg" width="250" /> |
| AWG14 - 2.5mm² yellow insulated single core cable spool | 1 | <img src="./docs/images/Assembly-guide-photos/Cables/yellow-single-core.jpg" width="250" /> |
| Insulated blue quick connect terminals 6.4x0.8mm for 16-14AWG/ 1.5-2.5mm² | 6 | <img src="./docs/images/Assembly-guide-photos/parts/blue-quick-connect.jpg" width="250" /> |

#### Steps

1. Cut the following length of Cables

  - 1 x **40cm** - brown
  - 1 x **40cm** - blue
  - 1 x **40cm** - yellow
  - 1 x **14cm** - brown
  - 1 x **14cm** - blue
  - 1 x **14cm** - yellow

2. Install a terminal to one side of each cable using the crimper
  - Do not remove the trimmed insulation on the other side of the cables

<p align="center">
  <img src="./docs/images/Assembly-guide-photos/Cables/AC-cables-plus-terminals.jpg" width="600" />
</p>

## PSU complete

| Parts | Qty | Image |
|-|-|-|
| [AC harness](#AC-harness) | 1 | <img src="./docs/images/Assembly-guide-photos/Cables/AC-cables-plus-terminals.jpg" width="250" /> |
| Meanwell UHP-200A-5 | 1 | <img src="./docs/images/Assembly-guide-photos/parts/Meanwell PSU.jpg" width="250" /> |
| 3M VHB 5952 double-sided foam pads | 2 | <img src="./docs/images/Assembly-guide-photos/parts/3m-double-tape.jpg" width="250" /> |

#### Steps

1. Install the foam pads on the bottom of the power supply as in the picture below
  - Do not remove the red foam pad cover

<p align="center">
  <img src="./docs/images/Assembly-guide-photos/instructions/Power-supply-pads.jpg" width="600" />
</p>

2. Install the AC cables to the power supply

- The brown cables should be connected to 'L'
- The blue cables should be connected to 'N'
- The yellow cables should be connected to '⏚'
- Install the 14cm cable and the 40cm on the AC side of the PSU. Leave them straight by having the stripped edge of the sort wire on the left side of the screw and other edge of the longer wire on the right side and then screw them in place.

- For BOSCH GSR12V screwdriver use speed **1** - torque **5**
- For BOSCH GSB120 screwdriver use speed **1** - torque **3** (should be set to 'Screw', not 'Drill' or 'Hammer')
 Updating-assembly-guide
- For BOSCH GSB120 screwdriver use speed **1** - torque **3** (should be set to 'Screw', not 'Drill' or 'Hammer')

<p align="center">
  <img src="./docs/images/Assembly-guide-photos/instructions/AC-Wires-to-the-PSU.jpg" width="600" />
</p>

## Bottom subassembly

| Tools | Image |
|-|-|
| File | <img src="./docs/images/Assembly-guide-photos/Tools/File.jpg" width="250" /> |
| Countersink drill bit 6.3mm | <img src="./docs/images/Assembly-guide-photos/Tools/countersink-6.3.jpg" width="250" /> |
| M3x8mm torx countersunk screw | <img src="./docs/images/Assembly-guide-photos/parts/M3x8mm torx screw.jpg" width="250" /> |
| PSU & cable base jig (PSU1) | <img src="./docs/images/Assembly-guide-photos/Jigs/PSU & cable base jig (PSU1).jpg" width="250" /> |
| Insulated flat or BOSCH screwdriver | <img src="./docs/images/Assembly-guide-photos/Tools/flat-screwdriver.jpg" width="250" /> |
| BOSCH screwdrivers | <img src="./docs/images/Assembly-guide-photos/Tools/Bosch-GSR-12V-GSB-120LI.jpg" width="250" /> |
| Metal label jig (ML2) | <img src="./docs/images/Assembly-guide-photos/Jigs/Metal label jig (ML2).jpg" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| [PSU complete](#PSU-complete) | 1 | PHOTO |
| Bottom shell | 1 | <img src="./docs/images/Assembly-guide-photos/parts/Bottom shell.jpg" width="250" /> |
| Power entry module C14 | 1 | <img src="./docs/images/Assembly-guide-photos/parts/Entry module C14.PNG" width="250" /> |
| Power entry module C13 | 1 | <img src="./docs/images/Assembly-guide-photos/parts/Entry module C13.PNG" width="250" /> |
| Long brown cable with terminals (section 1.1) | 1 | <img src="./docs/images/Assembly-guide-photos/Cables/long-brown-cable-with-terminals.jpg" width="250" /> |
| Long blue cable with terminals (section 1.1) | 1 | <img src="./docs/images/Assembly-guide-photos/Cables/long-blue-cable-with-terminals.jpg" width="250" /> |
| Long yellow cable with terminals (section 1.1) | 1 | <img src="./docs/images/Assembly-guide-photos/Cables/long-yellow-cable-with-terminals.jpg" width="250" /> |
| Short brown cable with terminals (section 1.1) | 1 | <img src="./docs/images/Assembly-guide-photos/Cables/short-brown-cable-with-terminals.jpg" width="250" /> |
| Short blue cable with terminals (section 1.1) | 1 | <img src="./docs/images/Assembly-guide-photos/Cables/short-blue-cable-with-terminals.jpg" width="250" /> |
| Short yellow cable with terminals (section 1.1) | 1 | <img src="./docs/images/Assembly-guide-photos/Cables/short-yellow-cable-with-terminals.jpg" width="250" /> |
| Metal label | 1 | <img src="./docs/images/Assembly-guide-photos/parts/Metal label.jpg" width="250" /> |

#### Steps

1. Inspect the top shell for any imperfections and use the file to remove any rough edges.

2. Inspect the 4 x M3 countersunk holes of the bottom shell
  - Use the M3 countersunk screw and make sure it sits flush with the surface
  - If need be, use the medium countersink drill bit to increase the countersunk of the plastic so that the screw sits flush with the surface
  - Use a vacuum cleaner to remove any plastic debris

<p align="center">
   <img src="./docs/images/Assembly-guide-photos/instructions/M3-countersunk-holes.jpg" width="600" />
   </p>

<p align="center">
   <img src="./docs/images/Assembly-guide-photos/instructions/M3-sits-flush.jpg" width="600" />
   </p>

3. Install the power supply using the PSU jig.
  - Make sure the AC power input is placed on the right-hand side
  - Make sure the power supply is securely fastened in place via the double-sided tape

  <p align="center">
     <img src="./docs/images/Assembly-guide-photos/instructions/PSU-jig.jpg" width="600" />
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
   <img src="./docs/images/Assembly-guide-photos/instructions/AC-wires-to-the-en.mod.jpg" width="600" />
   </p>


9. Remove the double-side tape protection film from the metal label and install it using the label jig
  - Pay attention on the orientation of the label, ideally use a magnet to help you hold the label
  - Make sure the metal label is securely fastened in place

<p align="center">
   <img src="./docs/images/Assembly-guide-photos/instructions/Metal-label-plus-magnet.jpg" width="600" />
   </p>

## DC harness

| Tools | Image |
|-|-|
| Cable cutter-stripper | <img src="./docs/images/Sub-processes/Wire cutting-stripping photos/Cable-cutter-stripper.jpg" width="250" /> |
| Cable crimper | <img src="./docs/images/Sub-processes/Cable-crimping-photos/Crimping-machine.jpg" width="250" /> |
| Manual cable cutter | <img src="./docs/images/Assembly-guide-photos/Tools/cable-cutter.jpg" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| AWG16 - 1.5mm² red/black insulated dual core cable spool | 1 | <img src="./docs/images/Assembly-guide-photos/Cables/red-black-dual-core.jpg" width="250" /> |
| Insulated blue fork M4/4.3mm for 16-14AWG/ 1.5-2.5mm²| 7 | <img src="./docs/images/Assembly-guide-photos/parts/Insulated fork.jpg" width="250" /> |

#### Steps

1. Cut the following length of Cables

    - 2 x **27cm** - red/black (dual core), with fork terminals on one side

2. Install a fork terminal to one side of each cable using the crimper
  - Do not remove the trimmed insulation on the other side of the cables.

<p align="center">
  <img src="./docs/images/Assembly-guide-photos/Cables/DC-cables-with-terminals.jpg" width="600" />
</p>

## CM subassembly

| Tools | Image |
|-|-|
| Phillips screwdriver bit PH0 | <img src="./docs/images/Assembly-guide-photos/Tools/PH0-bit.jpg" width="250" /> |
| Plastic spudger | <img src="./docs/images/Assembly-guide-photos/Tools/spudger.jpg" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| Compulab iMX8 compute module | 1 | <img src="./docs/images/Assembly-guide-photos/boards/Combulab-iMX8 compute module.jpg" width="250" /> |
| Heatsink | 1 | <img src="./docs/images/Assembly-guide-photos/parts/Heatsink.png" width="250" /> |
| M2x3.5mm phillips countersunk screw	 | 2 | <img src="./docs/images/Assembly-guide-photos/parts/M2x3.5mm phillips screw.png" width="250" /> |
| Thermal compound paste | 1 | <img src="./docs/images/Assembly-guide-photos/parts/thermal-paste.png" width="250" /> |
| Flexible antenna | 2 | <img src="./docs/images/Assembly-guide-photos/parts/Flexible antenna.jpg" width="250" /> |
| Antenna connector clip | 1 | <img src="./docs/images/Assembly-guide-photos/Jigs/Antenna connector jig.jpg" width="250" /> |

#### Steps

1. Place the compute module down with the CPU facing upwards
2. Apply a small amount of thermal compound and spread it to cover the CPU top surface
3. Place a heatsink on top with the fins pointing upwards. Align the screw holes making sure to place the hole with the single fins closer to the compute modules pin and the hole with the double away from the pins

<p align="center">
  <img src="./docs/images/Assembly-guide-photos/instructions/heatsink-orientation.png" width="600" />
</p>

4. Install the 2 screws and tighten them very carefully - don't apply too much torque
5. Install both antennas by connecting the w.FL connector of the antenna to the bottom w.FL connector of the compute module
6. Apply gentle vertical pressure with the plastic spudger and make sure the connector is properly mounted
7. Carefully insert the antenna connector clip to secure the w.FL connectors in place

## PCBA complete

| Tools | Image |
|-|-|
| BOSCH screwdrivers  | <img src="./docs/images/Assembly-guide-photos/Tools/Bosch-GSR-12V-GSB-120LI.jpg" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| [DC harness](#DC-harness) | 1 | <img src="./docs/images/Assembly-guide-photos/Cables/DC-cables-with-terminals.jpg" width="250" /> |
| [CM subassembly](#CM-subassembly) | 1 | PHOTO |
| EtcherPro mainboard | 1 | <img src="./docs/images/Assembly-guide-photos/boards/EtcherPro mainboard v2.3.4.jpg" width="250" /> |
| USB_to_SD_Slot v1.1 | 16 | <img src="./docs/images/Assembly-guide-photos/boards/USB-to SD slot.jpg" width="250" /> |

#### Steps

1. Remove excess plastic parts from the mainboard, if any
2. Install the DC cables on the mainboard and secure them in place using the BOSCH screwdriver

- Pay extra attention to make sure the **red** cables are connected to the terminals marked with **+5v** and the **black** cables are connected to the terminals marked with **GND**
- For BOSCH GSR12V screwdriver use speed **1** - torque **1**
- For BOSCH GSB120 screwdriver use speed **1** - torque **1** (should be set to 'Screw', not 'Drill' or 'Hammer')


3. Orient the mainboard so that the header connectors pointing upwards
4. Install the compute module on the SODIMM connector
  - Check that the side springs of the SODIMM connector are properly engaged
  - Gently pull one of the springs so it disengages and check if the CM lifts, then check the other spring
  - If the CM lifts when either of the springs disengage, remove the CM, push the springs towards the inside of the SODIMM connector to preload them, and then go back to step 3
  - For a final check, gently try to move the CM by pushing the heatsink to ensure it's properly secured

5. Install 16 card readers adapters by carefully connecting them to the header connectors
  - The card readers have a small peg that should also fit in respective mainboard hole

6. Check if any of the LEDs is accidentally bent
  - Make sure to avoid touching or accidentally pushing the LEDs during installation

<p align="center">
  <img src="./docs/images/Assembly-guide-photos/boards/Mainboard-subassembly.jpg" width="600" />
</p>

## Magnets complete

| Tools | Image |
|-|-|
| Tweezers | <img src="./docs/images/Assembly-guide-photos/Tools/tweezers.jpg" width="250" /> |
| Knife | <img src="./docs/images/Assembly-guide-photos/Tools/Box-cutter.jpg" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| 25x5x5mm N52 Neodymium magnets | 2 | <img src="./docs/images/Assembly-guide-photos/parts/N52 Neodymium magnet.jpg" width="250" /> |
| Adhesive tape (MG1) | 1 | <img src="./docs/images/Assembly-guide-photos/parts/3M-adhesive-tape.jpg" width="250" /> |

#### Steps

1. Apply the 3M adhesive tape to a whole magnet row

<p align="center">
  <img src="./docs/images/Assembly-guide-photos/instructions/Magnets-plus-adhesive-tape.jpg" width="600" />
  </p>

2. Separate 1 piece of magnet using the knife
  - Do not remove the protective film

## Fan blower complete

| Parts | Qty | Image |
|-|-|-|
| Fan blower | 1 | <img src="./docs/images/Assembly-guide-photos/parts/Fan blower.jpg" width="250" /> |
| 3M VHB 5952 double-sided foam pads | 1 | <img src="./docs/images/Assembly-guide-photos/parts/3m-double-tape.jpg" width="250" /> |

#### Steps

1. Install the foam pad on the plastic side on the fan blower
  - Do not remove the protective film

## Top shell with UV resin

| Tools | Image |
|-|-|
| File | <img src="./docs/images/Assembly-guide-photos/Tools/File.jpg" width="250" /> |
| 1ml syringe with metal needle | <img src="./docs/images/Assembly-guide-photos/Tools/syringe.png" width="250" /> |
| UV curing station | <img src="./docs/images/Sub-processes/UV-curing-photos/Curing-station.jpg" width="250" /> |
| UV protective goggles | <img src="./docs/images/Sub-processes/UV-curing-photos/protection-goggles.jpg" width="250" /> |
| Protective gloves | <img src="./docs/images/Sub-processes/Painting-process-photos/disposable-gloves.jpg" width="250" /> |
| Syringe and needle | <img src="./docs/images/Sub-processes/UV-curing-photos/Syringe-plus-needle.jpg" width="250" /> |
| Paper towel | <img src="./docs/images/Sub-processes/UV-curing-photos/Paper-towel.jpg" width="250" /> |
| Cardboard | <img src="./docs/images/Sub-processes/UV-curing-photos/Cardboard.jpg" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| Top shell | 1 | <img src="./docs/images/Assembly-guide-photos/parts/Top shell.jpg" width="250" /> |
| UV resin in bottle | 1 | <img src="./docs/images/Sub-processes/UV-curing-photos/Resin-bottle.jpg" width="250" /> |
| Plastic weld solvent | 1 | <img src="./docs/images/Assembly-guide-photos/Tools/plastic-weld-solvet.png" width="250" /> |

#### Steps

1. Inspect the top shell for any imperfections and use the file to remove any rough edges

2. Inspect the injection molded inserts and make sure everything is properly welded in place.
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
  <img src="./docs/images/Sub-processes/UV-curing-photos/Needle-installation.jpg" width="600" />
  </p>

  - Hold the syringe upwards and press the plunger slowly to remove excess air, always covered by a paper towel
  <p align="center">
  <img src="./docs/images/Sub-processes/UV-curing-photos/Remove-excess-air.jpg" width="600" />
  </p>

  - Be sure that your protective gloves are clean without any remaining resin on them to avoid contaminating the Top-shell

4. Place the top shell upside down and place the cardboard under the slots
  <p align="center">
  <img src="./docs/images/Sub-processes/UV-curing-photos/Cardboard-under-the-shell.jpg" width="600" />
  </p>

5. Direct the needle close and above the LED hole and press the plunger extremely gently and slowly, a tiny drop is enough
  - Be careful as the needle may keep dripping
  - The holes should be perfectly clear, if plastic debris block the holes remove them using tweezers
  <p align="center">
  <img src="./docs/images/Sub-processes/UV-curing-photos/Proper-hight-applying-resin.jpg" width="600" />
  <br>
  <img src="./docs/images/Sub-processes/UV-curing-photos/Properly applied resin.jpg" width="600" />
  </p>

6. After the resin is being applied to 16 holes place the top shell halfway through to the curing station making sure that both LED lamps are pointing to the LED holes
  - You can use a toothpick to gently push the cured resin to make sure it feels solid and therefore is properly cured
  <p align="center">
  <img src="./docs/images/Sub-processes/UV-curing-photos/Curing.jpg" width="600" />
  </p>

## Top shell complete

| Tools | Image |
|-|-|
| 5mm HEX socket driver | <img src="./docs/images/Assembly-guide-photos/Tools/hex-socket-5.jpg" width="250" /> |
| BOSCH screwdrivers | <img src="./docs/images/Assembly-guide-photos/Tools/Bosch-GSR-12V-GSB-120LI.jpg" width="250" /> |
| Heat threaded insert jig (HT1) | <img src="./docs/images/Assembly-guide-photos/Jigs/Heat threaded insert jig (HT1).jpg" width="250" /> |
| Fan blower jig (FB1) | <img src="./docs/images/Assembly-guide-photos/Jigs/Fan blower jig (FB1).jpg" width="250" /> |
| Scissors | PHOTO |

| Parts | Qty | Image |
|-|-|-|
| M3x8mm HEX male to female self threading standoffs | 8 | PHOTO |
| [Magnets complete](#Magnets-complete) | 1 | PHOTO |
| [Fan blower complete](#Fan-blower-complete) | 1 | PHOTO |
| Maxen 7in screen | 1 | <img src="./docs/images/Assembly-guide-photos/parts/7in screen& i2c touchpanel.jpg" width="250" /> |
| Aluminum tape | 1 | PHOTO |

#### Steps

1. Place the top shell up-side-down and install the standoffs, use the heat threaded inserts jig to find the correct locations
  - For BOSCH GSR12V screwdriver use speed **2** - torque **2**
  - For BOSCH GSB120 screwdriver use speed **1** - torque **1** (should be set to 'Screw', not 'Drill' or 'Hammer')

<p align="center">
   <img src="./docs/images/Assembly-guide-photos/instructions/Heatinsearts-jig.jpg" width="600" />
   </p>

2. Insert the magnet to magnet holder with the tape side facing the bottom of the holder

<p align="center">
  <img src="./docs/images/Assembly-guide-photos/instructions/Installing-magnet.jpg" width="600" />
  </p>

3. Repeat the previous step for the remaining magnet holder

4. Use the 'Fan blower jig (FB1)' to install the fan blower in place

<p align="center">
  <img src="./docs/images/Assembly-guide-photos/instructions/fan-aligned-assembled.jpg" width="600" />
</p>

5. Take a screen module (touch panel + display) and carefully remove the double-sided tape protection film from the touchpanel
  - Do not remove the screen protection film
  - The 2 flat cables should be orientated towards the EtcherPro slots

6. Insert the screen in the respective opening and make sure it's properly aligned
  - Make sure the screen is properly attached to the top shell

7. Cut two strips of aluminum tape, roughly 2cm long

8. Turn the shell up-side-down and install the aluminum strips on the bottom corners of the screen

## Top subassembly

| Tools | Image |
|-|-|
| 5mm HEX socket driver | <img src="./docs/images/Assembly-guide-photos/Tools/hex-socket-5.jpg" width="250" /> |
| BOSCH screwdrivers | <img src="./docs/images/Assembly-guide-photos/Tools/Bosch-GSR-12V-GSB-120LI.jpg" width="250" /> |
| Tweezers | <img src="./docs/images/Assembly-guide-photos/Tools/tweezers.jpg" width="250" /> |
| Logo sticker jig (LS1) | <img src="./docs/images/Assembly-guide-photos/Jigs/Logo sticker jig (LS1).jpg" width="250" /> |
| Methylated spirits or IPA alcohol | <img src="./docs/images/Assembly-guide-photos/Tools/methylated-spirit.png" width="250" /> |
| Cotton rug | <img src="./docs/images/Assembly-guide-photos/Tools/Cotton-rug.png" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| [PCBA complete](#PCBA-complete) | 1 |  |
| [Top shell complete](#Top-shell-complete) | 1 |  |
| M3x8mm HEX male to female standoffs | 4 | <img src="./docs/images/Assembly-guide-photos/parts/M3 male-female 6mm standoff.jpg" width="250" /> |
| M3x10mm HEX male to female standoffs | 4 | <img src="./docs/images/Assembly-guide-photos/parts/M3x7mm male-female standoff.jpg" width="250" /> |
| Logo sticker | 1 | <img src="./docs/images/Assembly-guide-photos/parts/Logo sticker.jpg" width="250" /> |

#### Steps

1. Install the mainboard subassembly inside the top shell making sure the adapters sit in the injection molded inserts properly and the PCB holes are aligned with the standoffs
- Make sure that the display ribbon cable has passed through the PCB slot and the touchpanel ribbon cable is folded towards the screen.

<p align="center">
 <img src="./docs/images/Assembly-guide-photos/instructions/ribbon-through-PCB.jpg" width="600" />
 </p>

2. Secure the mainboard using the longer standoffs on the top row and the shorter standoffs on the bottom row
- For BOSCH GSR12V screwdriver use speed **2** - torque **3**
- For BOSCH GSB120 screwdriver use speed **2** - torque **2** (should be set to 'Screw', not 'Drill' or 'Hammer')

<p align="center">
 <img src="./docs/images/Assembly-guide-photos/instructions/mainboard-inside-top-shell.jpg" width="600" />
 </p>

3. Connect the screen ribbon cable to the screen connector
- The screen connector have a small plastic flap that should be lifted up to accept the ribbon cable and then pushed down to secure the cable in place
- Make sure that the ribbon cable is gently pushed all the way in the connector before pushing down the connector flap

<p align="center">
   <img src="./docs/images/Assembly-guide-photos/instructions/Connect-ribbon.jpg" width="600" />
   </p>

<p align="center">
   <img src="./docs/images/Assembly-guide-photos/instructions/Ribbon-flap-down.jpg" width="600" />
   </p>

4. Connect the touchpanel ribbon cable to the touchpanel connector
- The touchpanel connector have a small plastic flap that should be lifted up to accept the ribbon cable and then pushed down to secure the cable in place
- Make sure that the ribbon cable is gently pushed all the way in the connector before pushing down the connector flap

<p align="center">
   <img src="./docs/images/Assembly-guide-photos/instructions/Touchpanel-ribbon.jpg" width="600" />
   </p>

<p align="center">
   <img src="./docs/images/Assembly-guide-photos/instructions/Flap-up.jpg" width="600" />
   </p>

5. Remove the double-sided tape protection layer from the antennas and attach the antennas to the top shell
- Make sure the antennas are securely fastened in place via the double-sided tape and aligned as shown in the picture
- Pay attention not to bend the antenna cable too much
- Make sure the cable is not under tension

<p align="center">
   <img src="./docs/images/Assembly-guide-photos/instructions/antenna-right-place.jpg" width="600" />
   </p>

6. Connect the fan blower's cable to mainboard
- If there is excess cable from the fan blower, fold the cable to reduce its length and secure it with a tie wrap

<p align="center">
   <img src="./docs/images/Assembly-guide-photos/instructions/fan-blower's-cable.jpg" width="600" />
   </p>

7. Using the tweezers, grab a logo sticker without removing the top protective film

8. Use the logo jig to install the sticker

9. Carefully remove the protective layer
- Make sure the logo sticker remains in place
- If there is residue from the sticker, use a rug with a bit of methylated spirits or alcohol to remove it

<p align="center">
  <img src="./docs/images/Assembly-guide-photos/instructions/Logo-sticker-with-jig.jpg" width="600" />
  </p>

## EtcherPro device

| Tools | Image |
|-|-|
| Torx screwdriver no 10 | <img src="./docs/images/Assembly-guide-photos/Tools/torx-10.jpg" width="250" /> |
| BOSCH screwdrivers | <img src="./docs/images/Assembly-guide-photos/Tools/Bosch-GSR-12V-GSB-120LI.jpg" width="250" /> |
| Phillips screwdriver Metrix #2 x 4" CRV Magnetic Phillips Head Screwdriver  | <img src="./docs/images/Assembly-guide-photos/Tools/phillips-screwdriver.jpg" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| [Top subassembly](#Top-subassembly) | 1 | <img src="./docs/images/Assembly-guide-photos/parts/Top-full-assembled.jpg" width="250" /> |
| [Bottom subassembly](#Bottom-subassembly) | 1 | <img src="./docs/images/Assembly-guide-photos/instructions/PSU-plus-AC-cables.jpg" width="250" /> |
| M3x8mm torx countersunk screw | 4 | <img src="./docs/images/Assembly-guide-photos/parts/M3x8mm torx screw.jpg" width="250" /> |

#### Steps

1. Bring the bottom shell next to the top shell and secure the DC cables to the power supply output
- The red cables need to be connected to '+5V'
- The black cables need to be connected to 'GND'

2. Carefully bring the 2 bottom openings of the bottom shell towards the front pegs of the top shell

3. Gently close the device
- Make sure the DC cable is free and unobstructed
- Make sure the 2 x RJ45 connectors sit on the adapters properly (aligned without gaps around)
- Gently pull the connectors downwards if needed
- If the connectors can’t sit in place properly most likely something is misplaced inside the device, inspect all equipment and try again

4. Install the 4 x M3 screws to secure the bottom shell to the top shell
- For BOSCH GSR12V screwdriver, set speed  **1** - torque **1**

<p align="center">
   <img src="./docs/images/Assembly-guide-photos/instructions/Top-Bottom-open-assembled.jpg" width="600" />
   </p>

## EtcherPro in bag

| Parts | Qty | Image |
|-|-|-|
| Getting started sticker | 1 | PHOTO |
| EtcherPro bag | 1 | PHOTO |

#### Steps

1. Install the getting started sticker near the top right corner of the screen

2. Use a cotton rug to wipe the EtcherPro device
- Make sure the rubber feet are in place
- Make sure the screen protection film is in place
- Make sure the device doesn't have any marks or fingerprints

3. Put the device in the bag and fold the bag towards the bottom

## Cable bag subassembly

| Parts | Qty | Image |
|-|-|-|
| Cable bag | 1 | PHOTO |
| Power cable | 1 | <img src="./docs/images/Assembly-guide-photos/parts/Power-cable.jpg" width="250" /> |
| balenaEtcherPro sticker | 1 | PHOTO |
| I am Pro sticker | 1 | PHOTO |

#### Steps

1. Place all items inside the bag and seal it
- There are 4 power cable adapters and one extension cable

## EtcherPro packed

| Tools | Image |
|-|-|
| Packing tape dispenser gun | <img src="./docs/images/Assembly-guide-photos/Tools/tape-dispenser.jpg" width="250" /> |

| Parts | Qty | Image |
|-|-|-|
| [EtcherPro in bag](#EtcherPro-in-bag) | 1 | PHOTO |
| [Cable bag subassembly](#Cable-bag-subassembly) | 1 | PHOTO |
| EtcherPro printed box | 1 | <img src="./docs/images/Assembly-guide-photos/parts/EtcherPro-printed-box.jpg" width="250" /> |
| Box left foam padding | 1 | <img src="./docs/images/Assembly-guide-photos/parts/Box-left-foam.jpg" width="250" /> |
| Box right foam padding | 1 | <img src="./docs/images/Assembly-guide-photos/parts/Box-right-foam.jpg" width="250" /> |
| Packing tape 3M 313 75ΜΜΧ66Μ | 1 | <img src="./docs/images/Assembly-guide-photos/Tools/3M-313-packing-tape.jpg" width="250" /> |

#### Steps

1. Take a flat box and fold the bottom flaps

2. Carefully apply tape across the bottom side of the box to secure the flaps
- Make sure the tape is consistent without wrinkles

3. Place the cable bag subassembly inside the box

4. Attach the left and right foam paddings on the EtcherPro device
- Make sure the EtcherPro bag is tidy in place

5. Place the EtcherPro device with the paddings inside the Box

6. Close the top flaps and carefully apply tape across the top side of the box to secure the flaps
- Make sure the tape is consistent without wrinkles

<p align="center">
   <img src="./docs/images/Assembly-guide-photos/instructions/EP-box-closed.jpg" width="600" />
   </p>

## EtcherPro ready to ship

| Tools | Image |
|-|-|
| Shipping label printer | PHOTO |

| Parts | Qty | Image |
|-|-|-|
| Shipping label paper | 1 | PHOTO |

#### Steps

1. Print the shipping label

2. Attach it on the top side of the box
