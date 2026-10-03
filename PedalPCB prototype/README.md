# PedalPCB (v01.11.20) FV-1 Development Board 

## Welcome

Hi, welcome to the active repositor of the **FV-1 effects pedal project** by autumn, ethel, and drew.

The objective is to create a modular effects pedal board that can be digitally re-programmed for a wide range of uses and experimentation.

 ![alt text](https://github.com/autumngreenbean/fv-1/blob/main/PedalPCB%20prototype/Images/collage.png?raw=true)

## Status

The project has arrived in the stage of assembly and testing. The board and electronic components are completed and wired (2026-10-01). Once the connections are tested, the endpoint to interface with the **FV-1** chip is near. Hehe!

# Hardware Assembly
## FV-1 Development board

[PedalPCB's (v01.11.20 FV-1 Development Board)](https://docs.pedalpcb.com/project/FV1-Dev.pdf) is discontinued. The documentation here shows a full schematic and wiring guide for the version used in this project. 

Parts used to assemble the board are shown in the above documentation link, but is also available in `/PedalPCB prototype/Components.ods`

## Enclosure
The enclosure is a 5-potentiometer variation, printed out of black PLA. The print files can be found in .stl format [here](https://www.thingiverse.com/thing:4634049).

## Checkpoints (TODO)

0. Modify 3D print enclosure prototype, install components
    - Accomodate power jack diameter
    - Re-position USB-B port lower
    - Ledge only for the usb port for now
    - Note that board is nearly flush with the top edge (looking down), current artificial ledge insert is useless!
1. Modify audio jack prongs to conserve space
2. Shield prototype enclosure with aluminum
3. Wire toggle switch
4. Configure & test 9V power 
5. Power & connect FV-1 chip

### Checkpoints (DONE)

1. Modify 3D print enclosure prototype
    - Smaller hole for bottom jack -> toggle SWITCH
    - Extend ledge reaching to the top nuts
    - USB Type-B hole 0.5" from top right nut (from inside perspective)
    - Get rid of the middle hole below potentiometers 
    - Add hole for 9V power
2. Wire 5x potentiometers
3. Wire stomp switch
4. Populate two development boards
5. Source components

last updated 2026-10-02

