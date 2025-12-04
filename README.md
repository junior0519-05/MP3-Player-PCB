# MP3-Player-PCB
PCB was assembled, everything worked perfectly. Finalizing documentation and presentation is all that's needed...

# Technologies and Components
## Hardware Related
- XIAO ESP32-S3
- DF Mini MP3 Player Module
- SH1107 1.5" OLED display
- DS3231 Real Time Clock Module (RTC)
- 4 Pin Tactile Button (X3)
- 3 Pin Audio Jack
- 1K OHM Resistor
- Soldering of THT components
- 3.7V 1500mAh lipo battery
- IP5306 (Boost converter & lipo battery charger)
- Toggle switch (used for power off and on of device)

## Software Related

# Custom Footprints
Footprints were created for the PCB based on the exact physical measurments of the components in mm for accurate pad and pin allignments (2.54 mm spacing between pads)

- DS3231 RTC: 22mm X 38.5mm (W X L)

# System Features
## Displays Current:
+ AM/PM formatted time (PST)
+ Date (MM/DD/YYYY)


## Time Responsive Icons 
+ Morning Icon: 6 AM - 3 PM
+ Afternoon Icon: 4 PM - 6 PM
+ Evening/Night Icon: 7 PM - 5 AM
