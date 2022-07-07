## Package Configuration

<If cond={props.notecarrier === 'notecarrier-aa'}>

### Notecarrier-AA (Antenna + AA Battery Harness)

Notecarrier-AA (CARR-AA) is designed for building battery-powered wireless
applications.

![Notecarrier-AA (front)](/images/hardware/notecarrier/CARR_AA_front.jpg)
![Notecarrier-AA (back)](/images/hardware/notecarrier/CARR_AA_back.jpg)

- Pre-soldered female
  [Notecarrier-AA 22-pin header](#notecarrier-aa-22-pin-header) for easy access to
  Notecard edge connector pins.
- [Notecard edge connector socket](https://www.digikey.com/en/products/detail/amphenol-icc-fci/MDT420E01001/5810336)
  and [mounting screw receptacle](https://www.digikey.com/en/products/detail/w-rth-elektronik/9774025151R/5320683).
- Micro-USB port to power Notecarrier and provide a USB Serial command interface
  to Notecard.
- Onboard cellular/Wi-Fi and active GPS antennas.
- External [Nano-SIM](https://en.wikipedia.org/wiki/SIM_card#4FF) slot for
  additional carrier connectivity.
- Pre-soldered case for 3 AA batteries (not included).

</If> {/* 'notecarrier-aa' */}

<If cond={props.notecarrier === 'notecarrier-ae'}>

### Notecarrier-AE (Antenna + Embedded Design)

Notecarrier-AE (CARR-AE) is designed for embedding the Notecard and Notecarrier
directly into your product.

![Notecarrier-AE (front)](/images/hardware/notecarrier/CARR_AE_front.jpg)
![Notecarrier-AE (back)](/images/hardware/notecarrier/CARR_AE_back.jpg)

- Uses the [Notecarrier-AE 22-pin header](#notecarrier-ae-22-pin-header).
- [Notecard edge connector socket](https://www.digikey.com/en/products/detail/amphenol-icc-fci/MDT420E01001/5810336)
  and [mounting screw receptacle](https://www.digikey.com/en/products/detail/w-rth-elektronik/9774025151R/5320683).
- Micro-USB port to power Notecarrier and provide a USB Serial command interface
  to Notecard.
- Onboard cellular/Wi-Fi and active GPS antennas.
- Castellated edge connector can be soldered directly onto a product PCB.

</If> {/* 'notecarrier-ae' */}

<If cond={props.notecarrier === 'notecarrier-af'}>

### Notecarrier-AF (Antenna + Adafruit Feather Socket)

Notecarrier-AF (CARR-AF) is designed for drop-in development with any Adafruit
Feather or compatible microcontroller. It includes two female pin headers
(12-pin and 16-pin) for directly plugging in a Feather compatible board. It also
includes Grove and Stemma I2C ports for attaching external peripherals to your
project.

[View in Store](https://shop.blues.io/products/feather-starter-kit)

![Notecarrier-AF (front)](/images/hardware/notecarrier/CARR_AF_front.jpg)

- Adafruit Feather compatible header socket.
- Breadboard compatible
  [Notecarrier-AF 13-pin header](#notecarrier-af-13-pin-header).
- Breadboard compatible 24-pin Adafruit Feather breakout header.
- [Notecard edge connector socket](https://www.digikey.com/en/products/detail/amphenol-icc-fci/MDT420E01001/5810336)
  and [mounting screw receptacle](https://www.digikey.com/en/products/detail/w-rth-elektronik/9774025151R/5320683).
- Micro-USB port to power Notecarrier and provide a USB Serial command interface
  to Notecard.
- Onboard cellular/Wi-Fi and active GPS antennas.
- External [Nano-SIM](https://en.wikipedia.org/wiki/SIM_card#4FF) slot for
  additional carrier connectivity.
- 2 Seeed Studio Grove I2C ports for attaching external peripherals to your
  project.
- JST PH connector for a LiPo battery.
- JST PH connector for a solar panel.
- JST SH 3.3V I2C port (Adafruit STEMMA QT and Sparkfun QWiic compatible).
- Battery slide switch to disconnect battery when not in use.
- Momentary button connected to Feather B0 pin.

#### Feather Connector Pin Usage

| Pin Name | Dedicated | Description      |
| :------: | :-------: | :--------------- |
|   RST    |     N     | Reset            |
|   BAT    |     Y     | 3v3 supply       |
|    EN    |     N     | Module enable    |
|   SDA    |     N     | I2C Data         |
|   SCL    |     N     | I2C Clock        |
|    B0    |     N     | Momentary button |

<Note>

BAT pin is not connected directly to VBAT pin on the Notecarrier AF pin out. It is supplied by the onboard 3v3 voltage regulator. See [schematics](https://github.com/blues/note-hardware/tree/master/Notecarrier-AF) for more detailed information.

</Note>

</If> {/* 'notecarrier-af' */}

<If cond={props.notecarrier === 'notecarrier-al'}>

### Notecarrier-AL (Antenna + LiPo Battery Connector)

Notecarrier-AL (CARR-AL) is designed for building battery-powered wireless
applications.

![Notecarrier-AL (front)](/images/hardware/notecarrier/CARR_AL_front.png)
![Notecarrier-AL (back)](/images/hardware/notecarrier/CARR_AL_back.jpg)

- Pre-soldered female
  [Notecarrier-AL 22-pin header](#notecarrier-al-22-pin-header) for easy access to
  Notecard edge connector pins.
- [Notecard edge connector socket](https://www.digikey.com/en/products/detail/amphenol-icc-fci/MDT420E01001/5810336)
  and [mounting screw receptacle](https://www.digikey.com/en/products/detail/w-rth-elektronik/9774025151R/5320683).
- Micro-USB port to power Notecarrier and provide a USB Serial command interface
  to Notecard.
- Onboard cellular/Wi-Fi and active GPS antennas.
- External [Nano-SIM](https://en.wikipedia.org/wiki/SIM_card#4FF) slot for
  additional carrier connectivity.
- JST PH connector for a LiPo battery.
- JST PH connector for a solar panel.

</If> {/* 'notecarrier-al' */}

<If cond={props.notecarrier === 'notecarrier-a'}>

### Notecarrier-A (LiPo, Solar, and Qwiic Connectors)

Notecarrier-A (CARR-A) is designed for building battery-powered wireless
applications.

[View in Store](https://shop.blues.io/products/carr-al)

![Notecarrier-A (front)](/images/hardware/notecarrier/CARR_A_front.jpg)
![Notecarrier-A (back)](/images/hardware/notecarrier/CARR_A_back.jpg)

- Pre-soldered female
  [Notecarrier-A 22-pin header](#notecarrier-a-22-pin-header) for easy access to
  Notecard edge connector pins.
- [Notecard edge connector socket](https://www.digikey.com/en/products/detail/amphenol-icc-fci/MDT420E01001/5810336)
  and [mounting screw receptacle](https://www.digikey.com/en/products/detail/w-rth-elektronik/9774025151R/5320683).
- Micro-USB port to power Notecarrier and provide a USB Serial command interface
  to Notecard.
- Onboard cellular/Wi-Fi and active GPS antennas.
- External [Nano-SIM](https://en.wikipedia.org/wiki/SIM_card#4FF) slot for
  additional carrier connectivity.
- JST PH connector for a LiPo battery.
- JST PH connector for a solar panel.
- Two Qwiic connectors for connecting I2C peripherals.

</If> {/* 'notecarrier-a' */}

<If cond={props.notecarrier === 'notecarrier-b'}>

### Notecarrier-B (Breadboard)

Notecarrier-B (CARR-B) is designed for building highly customized hardware
solutions.

[View in Store](https://shop.blues.io/products/carr-b)

![Notecarrier-B (back)](/images/hardware/notecarrier/CARR_B_back.jpg)
![Notecarrier-B (front)](/images/hardware/notecarrier/CARR_B_front.jpg)

- Pre-soldered male
  [Notecarrier-B dual 9-pin headers](#notecarrier-b-dual-9-pin-headers) for easy access to
  Notecard edge connector pins.
- [Notecard edge connector socket](https://www.digikey.com/en/products/detail/amphenol-icc-fci/MDT420E01001/5810336)
  and [mounting screw receptacle](https://www.digikey.com/en/products/detail/w-rth-elektronik/9774025151R/5320683).
- Micro-USB port to power Notecarrier and provide a USB Serial command interface
  to Notecard.
- Requires user provided U.FL cellular/Wi-Fi antenna and optional U.FL active
  GPS antenna.

</If> {/* 'notecarrier-b' */}

<If cond={props.notecarrier === 'notecarrier-pi'}>

### Notecarrier-Pi (Raspberry Pi Hat)

Notecarrier-Pi (CARR-PI) is designed for drop-in development with a Raspberry Pi
or compatible Single Board Computer. This Notecard must be powered by a
Raspberry Pi or compatible SBC.

[View in Store](https://shop.blues.io/products/carr-pi)

![Notecarrier-Pi (front)](/images/hardware/notecarrier/CARR_PI_front.jpg)
![Notecarrier-Pi (back)](/images/hardware/notecarrier/CARR_PI_back.jpg)

- Pre-soldered stackable 40-pin header for plugging directly into a Raspberry Pi
  and stacking additional Pi hats.
- [Notecard edge connector socket](https://www.digikey.com/en/products/detail/amphenol-icc-fci/MDT420E01001/5810336)
  and [mounting screw receptacle](https://www.digikey.com/en/products/detail/w-rth-elektronik/9774025151R/5320683).
- Micro-USB port to power Notecarrier and provide a USB Serial command interface
  to Notecard.
- External [Nano-SIM](https://en.wikipedia.org/wiki/SIM_card#4FF) slot for
  additional carrier connectivity.
- 1 Grove I2C port for attaching external peripherals to your project.
- DIP switches (shown below) to configure diagnostic serial port, attention pin,
  and active GPS support.
- Requires user provided U.FL cellular/Wi-Fi antenna and optional U.FL active
  GPS antenna.

<Warning>

Due to the power requirements of the Notecard, some Raspberry Pi 2 and 3 models
include a current-limiting fuse that will power-cycle the device when the
Notecard's modem is on and transmitting. To avoid these issues,
we recommend using only Raspberry Pi 4 devices with the Notecard and Notecarrier
Pi.

</Warning>

</If> {/* 'notecarrier-pi' */}

<If cond={props.notecarrier === 'notecarrier-af'}>

### Notecarrier-F (Outboard DFU + Adafruit Feather Socket)

Notecarrier-F (CARR-F) is designed for drop-in development with any Adafruit
Feather or compatible microcontroller. It includes two female pin headers
(12-pin and 16-pin) for directly plugging in a Feather compatible board. This board supports outboard DFU functionality when combined with the Swan-F/Swan-E.  It has the ability to have hats designed for the CARR-F attached. The feather can be surface mounted onto the CARR-F or mounted through the through hole pins. It also
includes Stemma I2C ports for attaching external peripherals to your
project.

[View in Store](https://shop.blues.io/products/notecarrier-f)

![Notecarrier-AF (front)](/images/hardware/notecarrier/CARR_AF_front.jpg)

- Adafruit Feather compatible header socket. Dfu features compatible with Swan
- Through hole mount Swan-F or Surface mount Blues Swan-E
- Mount Hats on the top or bottom of the Notecarrier-F
- [Notecard edge connector socket](https://www.digikey.com/en/products/detail/amphenol-icc-fci/MDT420E01001/5810336)
  and [mounting screw receptacle](https://www.digikey.com/en/products/detail/w-rth-elektronik/9774025151R/5320683).
- Micro-USB port to power Notecarrier and provide a USB Serial command interface
  to Notecard.
- Requires external antenna (link to antenna here :) 
- External [Nano-SIM](https://en.wikipedia.org/wiki/SIM_card#4FF) slot for
  additional carrier connectivity.
- JST PH connector for a LiPo battery.
- JST PH connector for a solar panel.
- JST PH connector on for Primary Cell Battery or DC input on V+
- 2x  JST SH 3.3V I2C port (Adafruit STEMMA QT and Sparkfun QWiic compatible).
- I2C Level shifter isolating Notecard power draw from feather.
- Momentary button for user functionality connected to Feather B0 pin.
- Active/Passive GPS toggle switch
- Outboard DFU enable + disable switch with Blues Swan
- Ultra Low power Attention pin switch enable

#### Feather Connector Pin Usage

| Pin Name | Dedicated | Description      |
| :------: | :-------: | :--------------- |
|   RST    |     N     | Reset            |
|   BAT    |     Y     | 3v3 supply       |
|    EN    |     N     | Module enable    |
|   SDA    |     N     | I2C Data         |
|   SCL    |     N     | I2C Clock        |
|    B0    |     N     | Momentary button |



</If> {/* 'notecarrier-f' */}