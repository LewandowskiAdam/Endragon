# Endragon
Klipper configurations for modified Ender 3 3d-printer
Modifications:
  - installed SKR MINI E3V3 board (klippy firmware from bigtreetech repository, comunications via USB)
  - added Raspberry Pi 2 as Klipper controller (also as secodnary MCU). Also to raspberry is connected external (USB) wifi card
  - secondary Z axis with second motor
  - changed default hotend to Phaetus Dragonfly BMS - https://www.phaetus.com/products/dragonfly-hotend-bms (installed heater - 60W, installed thermistor 104NT-4-R025H42G)
  - changed to microswiss direct drive for Ender 3. Direct drive is modified - milled, so tube from actual extruder part to Dragonfly to be straight. This was necesary due to different construction of hotend.
  - added thermal isolation pad bellow hotbed
  - added BLTouch to head
  - added magnetic print surface
  - gutted all wires, and added new ones (to move all boards away from printer frame, plan for future is to add heated enclosue so all electronics needs to go away)

Planned for near future:
  - desing, print and modify setting for hotend (cooling ducts etc)
  - design and print externall case for electronics and PSU (with standard ender 3 display)
  - rearange wiring (maybe with drag chains)

Planned for further future:
  - add heated enclosure