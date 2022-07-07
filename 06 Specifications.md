## Specifications

### Electrical Characteristics

#### DC Characteristics

<If cond={!['notecarrier-af', 'notecarrier-al', 'notecarrier-a'].includes(props.notecarrier)}>

| Description    | Minimum | Maximum | Unit |
| -------------- | :-----: | :-----: | :--: |
| Supply Voltage |   2.5   |   5.5   |  V   |
| Supply Current |   500   |  2000   |  mA  |

</If> {/* NOT ['notecarrier-af', 'notecarrier-al', 'notecarrier-a']*/}

<If cond={['notecarrier-af'].includes(props.notecarrier)}>

| Description                 | Minimum | Maximum | Unit |
| --------------------------- | :-----: | :-----: | :--: |
| Supply Voltage              |   2.5   |   5.5   |  V   |
| Supply Current\*            |    -    |    -    |  mA  |
| Solar JST Charging Range\** |   3.94  |   7.18  |  V   |

\*See the individual [Notecard](/hardware/notecard-datasheet) and Feather board
datasheets for more details.

</If> {/*['notecarrier-af']*/}

<If cond={['notecarrier-al', 'notecarrier-a'].includes(props.notecarrier)}>

| Description                 | Minimum | Maximum | Unit |
| --------------------------- | :-----: | :-----: | :--: |
| Supply Voltage              |   2.5   |   5.5   |  V   |
| Supply Current              |   500   |  2000   |  mA  |
| Solar JST Charging Range\** |   3.94  |   7.18  |  V   |

</If> {/*['notecarrier-al', 'notecarrier-a']*/}

<If cond={['notecarrier-af', 'notecarrier-al', 'notecarrier-a'].includes(props.notecarrier)}>

\*\*For detailed information regarding the solar charging circuit calculations
and behavior, please refer to the [Blues Notecarrier-A Series Solar JST
Input](/hardware/application-notes/notecarrier-a-series-solar-jst-input/)
application note.

</If> {/*['notecarrier-af', 'notecarrier-al', 'notecarrier-a']*/}

#### Absolute Maximum Ratings

<If cond={!['notecarrier-af', 'notecarrier-al', 'notecarrier-a'].includes(props.notecarrier)}>

| Description         | Minimum | Maximum |  Unit  |
| ------------------- | :-----: | :-----: | :----: |
| Storage temperature |   -35   |    70   | &deg;C |

</If> {/* NOT ['notecarrier-af', 'notecarrier-al']*/}

<If cond={['notecarrier-af', 'notecarrier-al', 'notecarrier-a'].includes(props.notecarrier)}>

| Description             | Minimum | Maximum |  Unit  |
| ----------------------- | :-----: | :-----: | :----: |
| Storage temperature     |  -35    |   70    | &deg;C |
| Solar JST Voltage       |    0    |   18.18 |   V    |
| Solar JST Input Current |    -    | 1250    |   mA   |

</If> {/*['notecarrier-af', 'notecarrier-al', 'notecarrier-a']*/}

<Note>

Actual values may vary based on local conditions such as atmospheric conditions
and distance to the cell tower.

</Note>
