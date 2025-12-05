# MP3-Player-PCB Created with KiCad 9
PCB was assembled, everything worked perfectly. Finalizing documentation and presentation is all that's needed...

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
- C++
- KiCad 9
- Various libraries for components:
  - U8g2 (graphics for UI)
  - DFRobotDFPlayerMini (for mp3 player)
  - RTCLib
  
- Gerber File generation for manufacturing (manufactured using JLCPCB)

# Custom Footprints
Footprints were created for the PCB based on the exact physical measurments of the components in mm for accurate pad and pin allignments (2.54 mm spacing between pads)
[special case for the audioJack, spacing for this was ...]

- DS3231 RTC: 22mm X 38.5mm (W X L)
- DF Mini Player:
- SH1107 1.5" OLED display:
- 3 Pin Audio Jack:

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
<img src = "https://github.com/user-attachments/assets/de5ac1a5-788c-4723-8f7f-29442f0c52cb" width = "400" height = "800"/> 
<img src = "https://github.com/user-attachments/assets/a706b393-1d43-4293-a5e2-802f0ad764a5" width = "400" height = "800"/> 

