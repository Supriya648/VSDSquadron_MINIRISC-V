# VSDSquadron_MINIRISC-V

You have come here to get information regarding the VSDSquadron Mini RISC-V internship projects. During the course of this four-week internship, you will conduct research and become knowledgeable of all pertinent materials in order to gain hands-on experience with Mini RISC-V. Have a wonderful time learning!

# VSDSquadron Mini RISC-V board 

## VSDSquadron Mini RISC-V Development kit
https://www.vlsisystemdesign.com/vsdsquadronmini/
 <p align="center">
<img  width="339" alt="image" src="https://github.com/Supriya648/VSDSquadron_MINIRISC-V/assets/61849924/c1c9a06a-4494-49c8-bb59-f8846417611a">
  
 VSDSquadron Mini top view
 </p>
 

 
  <p align="center">
<img width="387" alt="image" src="https://github.com/Supriya648/VSDSquadron_MINIRISC-V/assets/61849924/39181e97-7de5-4b97-b708-a355a11a4e32">
</p>

# Advanced RISC-V Research and Application Development
## Project : GPS Tracker - IoT based Vehicle Tracking System


### Block Diagram
The ESP32 in this particular case represents the VSDSquadron Mini. 

 <p align="center">
<img width="532" alt="image" src="https://github.com/Supriya648/VSDSquadron_MINIRISC-V/assets/61849924/ea7b02fe-7c6e-4691-bff3-4edcef678379">
</p>

### Interfacing the VSDSquadron mini (replace ESP32) with GPS Module.
 Connecting the VCC and GND of the GPS module to the 3.3V and GND pins of the VSDSquadron Mini. The TX and RX pins of the VSDSquadron Mini are connected to the RX and TX terminals of the GPS module. OLED display Module (SSD1306) is connected to VSDSquadron Mini via I2C mode.  
 ### Interfacing the VSDSquadron mini (replace ESP32) OLED Display
 | OLED PIN | VSDSquadron Mini |
 |----------| -----------------|
  | VCC| 3.3V |
   | GND | GND |
   | SCL | PC2|
   | SDA | PC1|


## Components required
### 1. GPS Module - Neo 6M GPS Module
### 2. OLED Display
### 3. VSDSquadron MINI RISC-V (or ESP32)
### 4. Jumper Wires
### 5. Breadboard 
