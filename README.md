![KiCad Render](https://raw.githubusercontent.com/RyanWillie/Tic-Tac-Toe-PCB/main/Images/Render.png)

# Tic-Tac-Toe-PCB

A continuation of my Hobby PCB designs is the arduino based Tic Tac Toe circuit, utilising some surface mount components this circuit was aimed to give some practical experience in implementing a microcontroller from scratch utilising the reference design sheets. Using multiplexing each grid is able to light up with an X or a O to indicate who has claimed the tile.

## Component Selection

The main principle of the component selection was to use readily available components with libraries available for easy and quick setup,as well as preferring breakout boards so that the components can be easily salvaged/replaced for other projects when it is not needed. Therefore the microcontroller will be an Arduino nano, and the popular NRF24L01 transciever as the available libary makes connection extremely easy.

## BOM
  - Arduino Nano
  - 72x LED
  - 9 x Switches
  - Crystal
  - Capacitors
  
## Proof of Concept
 No proof of concept was able to be created for this circuit due to the required components that were not on hand.
 

## PCB Design and Manufacturing
![KiCad Schematic](https://raw.githubusercontent.com/RyanWillie/Tic-Tac-Toe-PCB/main/Images/Schematic.png)
The open source program KiCad was used as the design software for the PCB, it is a 2 layer board designed to meet JLCPCB's requirements. As the board is a one off the space and shape requirements are purely to achieve the smallest practical footprint.
