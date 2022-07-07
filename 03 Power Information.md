Power Information
-----------------

<If cond={['notecarrier-aa', 'notecarrier-ae', 'notecarrier-af', 'notecarrier-al', 'notecarrier-a'].includes(props.notecarrier)}>

All Notecarriers can be powered by connecting directly to the Micro-USB port.
However, most installations will not have USB power available, so several
alternate power options are provided by the various Notecarrier models:

</If> {/*['notecarrier-aa', 'notecarrier-ae', 'notecarrier-af', 'notecarrier-al', 'notecarrier-a']*/}

<If cond={['notecarrier-pi'].includes(props.notecarrier)}>

The Micro-USB port on the Notecarrier-Pi is a data-only port and does not
provide power to the Notecarrier. Make sure to power your project with a
Raspberry Pi, or use an alternate power method, including:

</If> {/*['notecarrier-pi']*/}

<If cond={['notecarrier-aa', 'notecarrier-ae', 'notecarrier-af', 'notecarrier-al', 'notecarrier-a'].includes(props.notecarrier)}>

- attaching a LiPo battery.

  The LiPo battery must be a single-cell 3.7V battery with a 2-pin JST PH
  connector.

- attaching a solar cell (must be accompanied by LiPo).

  The solar charging circuit is designed for use with a 4.5-7V solar panel.

</If> {/*['notecarrier-aa', 'notecarrier-ae', 'notecarrier-af', 'notecarrier-a']*/}

- applying 2.5-5.5VDC to the `V+` pin.\*

<If cond={['notecarrier-af'].includes(props.notecarrier)}>

<Warning>

It is NOT recommended to use the JST connector, on your Feather compatible
device, to supply power to the Notecarrier-AF. Instead it is recommended to
utilize the JST connector, labeled `BATTERY`, on the Notecarrier-AF.

Doing so will provide the following advantages:

1. Reverse voltage protection.
2. Defer to `V+` and `USB` power sources.

</Warning>

</If> {/*['notecarrier-af']*/}

<Warning>

Typical USB ports may only be capable of supplying 500 mA of current, which
might not be enough to power Notecard during a cellular connection.

</Warning>



To Brandon: I think everything here for the broading category applies to the notecarrier-f. the warnings don't apply.

We would suggest not using the JST battery connector on the feather and powering via the Lipo connector on the CARR-F

Attaching a non rechargable battery to the V+ pin



