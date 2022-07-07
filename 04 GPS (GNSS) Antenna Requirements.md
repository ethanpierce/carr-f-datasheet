GPS (GNSS) Antenna Requirements
-------------------------------

All Notecarrier models are designed to support active GPS, and several
Notecarrier models provide built-in antennas ready to be connected to a Cellular
Notecard using the included U.FL cables.

<If cond={['notecarrier-aa', 'notecarrier-ae', 'notecarrier-af', 'notecarrier-al', 'notecarrier-a'].includes(props.notecarrier)}>

### Active GPS Onboard Antenna

The Notecarrier-A models feature built-in, active GPS antennas and are designed
with a sufficient buffer to isolate the antenna and minimize interference with
the other electronics. Notecarrier-A models do NOT support external GPS
antennas.

</If> {/*['notecarrier-aa', 'notecarrier-ae', 'notecarrier-af', 'notecarrier-al', 'notecarrier-a']*/}

<If cond={['notecarrier-b', 'notecarrier-pi'].includes(props.notecarrier)}>

### Active GPS Ready

The Notecarrier-B and Notecarrier-Pi models do not have integrated GPS antennas,
but support active GPS by providing circuitry to enable bias voltage to be
supplied. This functionality is enabled using the `VACT_GPS_OUT` and
`VACT_GPS_IN` pins.

|Pin Name|Pin Description|
|--------|---------------|
|VACT_GPS_IN|Input for active GPS antenna bias voltage|
|VACT_GPS_OUT|Notecard supplied DC bias voltage for active GPS|

The only pin required to support active GPS is `VACT_GPS_IN`, which allows you
to provide a voltage specific to your antenna or application. `VACT_GPS_OUT` is
unnecessary, but can be connected directly to `VACT_GPS_IN` to support an active
GPS antenna that accepts voltages in the 3.3V-4V range\*.

<If cond={props.notecarrier === 'notecarrier-b'}>

The Notecarrier-B has a 0&Omega; resistor connecting the two pins. The resistor
can be removed, allowing you to either utilize a passive GPS antenna, or splice
into the circuit and provide your own bias voltage.

</If> {/* 'notecarrier-b' */}

<If cond={props.notecarrier === 'notecarrier-pi'}>

The Notecarrier-Pi is built to support either an active or passive GPS antenna,
and has a DIP switch to enable you to select your configuration.

</If> {/* 'notecarrier-pi' */}

\*`VACT_GPS_OUT` is only powered when the cellular modem is active.

</If> {/*['notecarrier-b', 'notecarrier-pi']*/}
