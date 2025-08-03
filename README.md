# RGB LED 7-Segment Bedside Clock with Ambient Light and Proximity Sensor

<!-- ![Full Board Design Render](images/render.png) -->

## Features
- USB C Port for Power, Comms, and Programming
    - Connects to the ESP32-C3's onboard USB-CDC/JTAG device
- ESP32-C3 Module for control
    - Allows pattern changing over WiFi/Bluetooth, as well as the buttons on the device
- Integrated Ambient Light and Proximity Sensor
    - Allows the clock to be used at night and stay idle unless desired
- 86 Addressable RGB LEDs
    - APA102-style (DotStar) control
    - HD107S-5050
    
## Table Of Contents
- [Features](#features)
- [Bill Of Materials](#bill-of-materials)
- [Part Selection](#part-selection)
- [Case Design](#case-design)
- [Code](#code)
- [Extra Notes](#extra-notes)

<!-- [Schematic](images/???) -->

## Bill of Materials
<!--  
- NAME - FUNC
    - Component: REF
    - Quantity: 
    - [Datasheet]()
    - [DigiKey]()
-->
- Espressif ESP32-C3-MINI-1 - Microcontroller Module w/ WiFi and Bluetooth
    - Component: U1
    - Quantity: 1
    - [Datasheet](https://www.espressif.com/sites/default/files/documentation/esp32-c3-mini-1_datasheet_en.pdf)
    - [DigiKey](https://www.digikey.com/en/products/detail/espressif-systems/ESP32-C3-MINI-1-N4-A/15817506)
- STMicroelectronics USBLC6-2SC6 - USB Data and Power TVS Diode
    - Component: U2
    - Quantity: 1
    - [Datasheet](https://www.st.com/content/ccc/resource/technical/document/datasheet/06/1d/48/9c/6c/20/4a/b2/CD00050750.pdf/files/CD00050750.pdf/jcr:content/translations/en.CD00050750.pdf)
    - [DigiKey](https://www.digikey.com/en/products/detail/stmicroelectronics/USBLC6-2SC6/1040559)
- Vishay VCNL4040M3OE - Combination Ambient Light and Proximity Sensor
    - Component: U3
    - Quantity: 1
    - [Datasheet](https://www.vishay.com/docs/84274/vcnl4040.pdf)
    - [DigiKey](https://www.digikey.com/en/products/detail/vishay-semiconductor-opto-division/VCNL4040M3OE/5171283)
- TI SN74LVC2T45DCTR - Two Channel Fast Level Shifter (from 3V3 MCU to 5V LEDs)
    - Component: U4
    - Quantity: 1
    - [Datasheet](https://www.ti.com/lit/ds/symlink/sn74lvc2t45.pdf)
    - [DigiKey](https://www.digikey.com/en/products/detail/texas-instruments/SN74LVC2T45DCTR/639457)
- Microchip MCP1825ST-3302E/DB - 3V3 Low Noise LDO (500mA)
    - Component: U5
    - Quantity: 1
    - [Datasheet](https://ww1.microchip.com/downloads/en/DeviceDoc/22056b.pdf)
    - [DigiKey](https://www.digikey.com/en/products/detail/microchip-technology/MCP1825ST-3302E-DB/1635518)


## Case Design
<!--  TODO: Case design needs to be updated  -->
<!--  ![Case](images/case.png)  -->
- 3D Printed Chassis

## Code
<!-- Nothing Written Yet -->
- To view all the code, see it [here](code)

## Extra Notes