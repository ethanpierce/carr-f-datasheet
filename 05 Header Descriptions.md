## Header Descriptions

<If cond={['notecarrier-aa', 'notecarrier-ae', 'notecarrier-al', 'notecarrier-a'].includes(props.notecarrier)}>

<If cond={props.notecarrier === 'notecarrier-aa'}>

### Notecarrier-AA 22-Pin Header

[Samtec CES-122-01-T-S](https://www.digikey.com/en/products/detail/samtec-inc/CES-122-01-T-S/1104152)

</If> {/* 'notecarrier-aa' */}

<If cond={props.notecarrier === 'notecarrier-ae'}>

### Notecarrier-AE 22-Pin Header

[Samtec CES-122-01-T-S](https://www.digikey.com/en/products/detail/samtec-inc/CES-122-01-T-S/1104152)

</If> {/* 'notecarrier-ae' */}

<If cond={props.notecarrier === 'notecarrier-al'}>

### Notecarrier-AL 22-Pin Header

[Samtec CES-122-01-T-S](https://www.digikey.com/en/products/detail/samtec-inc/CES-122-01-T-S/1104152)

</If> {/* 'notecarrier-al' */}

<If cond={props.notecarrier === 'notecarrier-a'}>

### Notecarrier-A 22-Pin Header

[Samtec CES-122-01-T-S](https://www.digikey.com/en/products/detail/samtec-inc/CES-122-01-T-S/1104152)

</If> {/* 'notecarrier-a' */}

| Pin Name | Direction | Usage                                                                                                                                                                                                                                                      |
| :------: | :-------: | :--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| &LT;VUSB |  IN/OUT   | Access to VUSB pin of the USB jack                                                                                                                                                                                                                         |
| &LT;BAT  |  IN/OUT   | Access to battery voltage                                                                                                                                                                                                                                  |
| &LT;MAIN |    OUT    | Access to Notecard supply voltage                                                                                                                                                                                                                          |
| &LT;VIO  |    OUT    | Reference voltage for digital I/O                                                                                                                                                                                                                          |
|          |           |                                                                                                                                                                                                                                                            |
|    V+    |    IN     | 2.5-5.5V, <8uA idle, <500mA typical, 2A surge max (GPRS)                                                                                                                                                                                                   |
|   GND    |    IN     | Ground                                                                                                                                                                                                                                                     |
|    EN    |    IN     | >1.1v will power on the module, used for main product ON/OFF and for when product is being shipped to ensure that there is no communications attempted. If USB is active as power source, this pin is ignored, else it is required to be tied high or low. |
|   RST    |    IN     | >0.8v pulse will cause hard-reset of the module. This pin is internally pulled low, so NC is acceptable.                                                                                                                                                   |
|          |           |                                                                                                                                                                                                                                                            |
|   SCL    |  IN/OUT   | I2C clock request interface                                                                                                                                                                                                                                |
|   SDA    |  IN/OUT   | I2C data request interface\*                                                                                                                                                                                                                               |
|   ATTN   |    OUT    | Configurable interrupt signal                                                                                                                                                                                                                              |
|  AUXEN   |  IN/OUT   | API-selectable alternate [modes of operation]                                                                                                                                                                                                              |
|  AUXRX   |  IN/OUT   | API-selectable alternate [modes of operation]                                                                                                                                                                                                              |
|  AUXTX   |  IN/OUT   | API-selectable alternate [modes of operation]                                                                                                                                                                                                              |
|   AUX1   |  IN/OUT   | API-selectable alternate [modes of operation]                                                                                                                                                                                                              |
|   AUX2   |  IN/OUT   | API-selectable alternate [modes of operation]                                                                                                                                                                                                              |
|   AUX3   |  IN/OUT   | API-selectable alternate [modes of operation]                                                                                                                                                                                                              |
|   AUX4   |  IN/OUT   | API-selectable alternate [modes of operation]                                                                                                                                                                                                              |
|    RX    |    IN     | UART serial receive request interface                                                                                                                                                                                                                      |
|    TX    |    OUT    | UART serial transmit request interface                                                                                                                                                                                                                     |

</If> {/* ['notecarrier-aa', 'notecarrier-ae', 'notecarrier-al', 'notecarrier-a'] */}

<If cond={props.notecarrier === 'notecarrier-af'}>

### Notecarrier-AF 13-Pin Header

| Pin Name  | Direction | Usage                                                 |
| :-------: | :-------: | :---------------------------------------------------- |
|   AUX1    |  IN/OUT   | Access to alternate [modes of operation]              |
|   AUX2    |  IN/OUT   | Access to alternate [modes of operation]              |
|   AUX3    |  IN/OUT   | Access to alternate [modes of operation]              |
|   AUX4    |  IN/OUT   | Access to alternate [modes of operation]              |
|   AUXRX   |    IN     | Diagnostic Interface                                  |
|   AUXTX   |    OUT    | Diagnostic Interface                                  |
|   AUXEN   |    IN     | Enable diagnostics                                    |
|   ATTN    |    OUT    | Configurable interrupt signal                         |
|   VUSB    |  IN/OUT   | Access to VUSB pin of the USB jack                    |
|   VBAT    |  IN/OUT   | Access to battery voltage                             |
|  &LT;3V3  |    OUT    | Access to 3.3V supply voltage                         |
| &LT;VMAIN |    OUT    | Access to either VUSB or VBAT, whichever is available |
|    GND    |    IN     | Ground                                                |

#### Adafruit Feather 24-Pin Breakout Header

| Pin Name | Direction | Usage                                        |
| :------: | :-------: | :------------------------------------------- |
|   RST    |    IN     | Active-high reset                            |
|    EN    |    IN     | Module enable                                |
|   SDA    |  IN/OUT   | I2C bus data                                 |
|   SCL    |  IN/OUT   | I2C bus clock                                |
|    5     |  IN/OUT   | Digital input pin 5                          |
|    6     |  IN/OUT   | Digital input pin 6                          |
|    9     |  IN/OUT   | Digital input pin 9                          |
|    10    |  IN/OUT   | Digital input pin 10                         |
|    11    |  IN/OUT   | Digital input pin 11                         |
|    12    |  IN/OUT   | Digital input pin 12                         |
|    13    |  IN/OUT   | Digital input pin 13                         |
|    B0    |    IN     | Button pin 0                                 |
|    TX    |    OUT    | UART serial transmit                         |
|    RX    |    IN     | UART serial receive                          |
|   MISO   |    IN     | SPI Main In Secondary Out                    |
|   MOSI   |    OUT    | SPI Main Out Secondary In                    |
|   SCK    |    OUT    | SPI clock                                    |
|    A5    |    IN     | Analog input pin 5                           |
|    A4    |    IN     | Analog input pin 4                           |
|    A3    |    IN     | Analog input pin 3                           |
|    A2    |    IN     | Analog input pin 2                           |
|    A1    |    IN     | Analog input pin 1                           |
|    A0    |    IN     | Analog input pin 0                           |
|   AREF   |    IN     | Analog REFerence voltage (max input voltage) |

</If> {/* 'notecarrier-af' */}

<If cond={props.notecarrier === 'notecarrier-b'}>

### Notecarrier-B Dual 9-pin Headers

| Pin Name | Direction | Usage                                    |     |                                                    Usage | Direction | Pin Name |
| :------: | :-------: | :--------------------------------------- | --- | -------------------------------------------------------: | :-------: | :------: |
|   AUX1   |  IN/OUT   | Access to alternate [modes of operation] |     |                    UART serial receive request interface |    IN     |    RX    |
|   AUX2   |  IN/OUT   | Access to alternate [modes of operation] |     |                   UART serial transmit request interface |    OUT    |    TX    |
|   AUX3   |  IN/OUT   | Access to alternate [modes of operation] |     |                             I2C data request interface\* |  IN/OUT   |   SDA    |
|   AUX4   |  IN/OUT   | Access to alternate [modes of operation] |     |                              I2C clock request interface |  IN/OUT   |   SCL    |
|  AUXEN   |    IN     | Enable diagnostics                       |     |                            Configurable interrupt signal |    OUT    |   ATTN   |
|  AUXRX   |    IN     | Diagnostic interface                     |     |                                        Active-high reset |    IN     |   RST    |
|  AUXTX   |    OUT    | Diagnostic interface                     |     |                                            Module enable |    IN     |    EN    |
|   VUSB   |  IN/OUT   | Access to VUSB pin of the USB jack       |     | 2.5-5.5V, <8uA idle, <500mA typical, 2A surge max (GPRS) |    IN     |    V+    |
|   VIO    |    OUT    | Reference voltage for digital I/O        |     |                                                   Ground |    IN     |   GND    |

</If> {/* 'notecarrier-b' */}

<If cond={props.notecarrier === 'notecarrier-pi'}>

### Notecarrier-Pi 40-Pin Header

Notecarrier-Pi is configured as a Pi Hat. As such, the Notecarrier-Pi follows
the standard 40-pin Raspberry Pi Model B+ layout.

<Note>

The Raspberry Pi [40-pin GPIO connector](https://www.adafruit.com/product/2223)
used has 0.64mm square pins.

</Note>

#### Pi 40-pin Header Pin Usage

| Pin # | Pin Name | Dedicated | Description                   |
| :---: | :------: | :-------: | :---------------------------- |
|   1   |   3V3    |     N     | 3.3VDC power                  |
|   2   |    5V    |     N     | 5VDC power                    |
|   3   |   SDA    |     N     | I2C data                      |
|   4   |    5V    |     N     | 5VDC power                    |
|   5   |   SCL    |     N     | I2C clock                     |
|   6   |   GND    |     N     | Ground                        |
|   8   |  AUX_RX  | Y/N (DIP) | Auxilliary receive            |
|   9   |   GND    |     N     | Ground                        |
|  10   |  AUX_TX  | Y/N (DIP) | Auxilliary transmit           |
|  14   |   GND    |     N     | Ground                        |
|  20   |   GND    |     N     | Ground                        |
|  25   |   GND    |     N     | Ground                        |
|  30   |   GND    |     N     | Ground                        |
|  31   |   ATTN   | Y/N (DIP) | Configurable interrupt signal |
|  34   |   GND    |     N     | Ground                        |
|  39   |   GND    |     N     | Ground                        |

#### DIP Switches

There are three DIP switches are located on the back side of the board. The
switches are used to reserve exclusive access to the GPIO pins.

![Notecarrier-Pi DIP switches](/images/hardware/notecarrier/pi-dips.png)

1. `ACTIVE GPS` - When turned `ON`, applies 3.9VDC to the center conductor of
   the Notecard GPS antenna connector to power the low-noise amplifier (LNA) of an
   active GPS antenna. This switch must be `OFF` if Notecard is used with a passive
   GPS antenna! However, we recommend an active antenna for best performance.

2. `SERIAL TXRX` - When turned `ON`, enables serial communication with Notecard
   via Notecard `AUX_RX` and `AUX_TX` via Raspberry Pi GPIOs 14 and 15 (Pins 8 and
   10). Typical applications will use I2C for Notecard interactions, with this AUX
   serial port providing useful debugging features for developers.

3. `ATTN` - When turned `ON`, connects Notecard ATTN to Raspberry Pi GPIO 6 (Pin
   31).

</If> {/* 'notecarrier-pi' */}

[modes of operation]: /reference/notecard-api/card-requests#card-aux


### Notecarrier-F 24-Pin Header Left Side (J10) 

|Pin Number | Pin Name  | Direction | Usage |
|:-------: | :-------: | :-------: | :---------------------------------------------------- |
|1 |F_3V3|OUT| 3.3V Feather Regulator|
|2 |N_VUSB |IN/OUT| Access to VUSB pin of the USB port |
|3 |VBAT |IN/OUT| Access to battery voltage |
|4 |&LT;VMAIN |OUT| Access to either N_VUSB or VBAT or V+ or SOLAR, whichever is available |
|5 |N_VIO |OUT| 3.3V regulator for the Notecard MCU and reference for Digial I/O |
|6 | ||  |