# Nova 25 - Custom MP3 Player Created with KiCad 9
A fully custom designed MP3 player that provides a clean and compact user interaction expirence. We built this with the goal of making a device that can actually be
used by a consumer on a daily basis. We imitated all the functions a regular MP3 player has but adding our own twist to the idea. We designed the UI with the idea of
having something that's both compact but visually appealing for the user.

This board is meant to operate at 5V via a lithium-ion battery paired with a boost converter to give it the portability feature it needs. The PCB includes custom made symbols
and footprints for each of the components along with labeling and decals along the PCB for both design and clarity.

*created by: Bryan Diaz and Junior Ortega | Focus: Embedded Systems, Hardware and PCB Design*

# Technologies and Components
## Hardware Related
- XIAO ESP32-S3
- DF Mini MP3 Player Module
- SH1107 1.5" OLED display (operates using I2C)
- DS3231 Real Time Clock Module (RTC)
- 4 Pin Tactile Button (X3)
- 3 Pin Audio Jack
- 8 GB Micro SD Card
- 1K OHM Resistor
- Soldering of THT components
- Custom 2 layer PCB (designed in KiCad)

## Software Related
- C++ (Toggle condtions for system features, loading of UI, response to user input based on 3 tactile buttons and cursor positioning)
- KiCad 9 (Schematic capture and board design)
- freeRTOS (task control for handling user input and system design)
- Various libraries for components:
  - U8g2 (graphics for UI)
  - DFRobotDFPlayerMini (for mp3 player)
  - RTCLib
  
- Gerber File generation for manufacturing (manufactured using JLCPCB)

# Custom Footprints
Footprints were created for the PCB based on the exact physical measurments of the components in mm for accurate pad and pin allignments (2.54 mm spacing between pads)
[special case for the audioJack, spacing for this was 9.8mm and 4.9mm for the center pin]

- DS3231 RTC: 22mm X 38.5mm (W X L)
- DF Mini Player: 20.8mm X 20.8mm (W X L)
- SH1107 1.5" OLED display: 34mm X 47mm (W X L)
- 3 Pin Audio Jack: 12mm X 12mm (W X L)

# System Features
## MP3 User System:
- Pause and play of music that's imported onto the micro SD card
- Skipping and Rewinding of current song
- Loop one song feature
- Shuffle music feature
- Adjustable system volume (0-30)

## Displays Current:
+ Current Track Number & Total Tracks loaded onto SD card
+ Date (MM/DD/YYYY)
+ Current Time of day (PST)
+ AM/PM formatted time

## Time Responsive Icons 
+ Morning Icon: 6 AM - 3 PM
+ Afternoon Icon: 4 PM - 6 PM
+ Evening/Night Icon: 7 PM - 5 AM


# System Preview
<img src = "https://github.com/user-attachments/assets/0175e984-8308-4e14-a383-08b61785e83b" width = "400" height = "700"/> 
<img src = "https://github.com/user-attachments/assets/1caa3069-ad71-4998-81eb-c4525bf72be9" width = "400" height = "800"/> 



