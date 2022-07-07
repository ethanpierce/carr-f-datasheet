Cellular Antenna Requirements
-------------------------------



### Cellular Antenna Requirements

The Notecarrier-F requires an external Cellular and GPS antenna to be attached to the notecard in order to establish connectivity and GPS functionality. Below is a list of antenna recommendations.

## 4.0 Antennas

| **Notecard SKU**                  | **Description**                                              | **Modem Datasheet Link**                                     |
| :-------------------------------- | :----------------------------------------------------------- | :----------------------------------------------------------- |
| NOTE-NBGL-*                       | Narrow-band global coverage: LTE Cat-M, NB-IoT, GSM          | [Quectel BG95-M3 10](https://www.quectel.com/UploadFile/Product/Quectel_BG95_Series_LPWA_Specification_V1.5.pdf) |
| NOTE-NBNA-*                       | Narrowband North America coverage: LTE Cat-M                 | [Quectel BG95-M1 10](https://www.quectel.com/UploadFile/Product/Quectel_BG95_Series_LPWA_Specification_V1.5.pdf) |
| NOTE-WBEX-*                       | Wideband Europe, Middle East, Asia coverage: LTE Cat-1, WCDMA, GSM | [Quectel EG91-EX 6](https://www.quectel.com/UploadFile/Product/Quectel_EG91_LTE_Standard_Specification_V1.9.pdf) |
| NOTE-WBNA-*                       | Wideband North America coverage: LTE Cat-1, WCDMA            | [Quectel EG91-NAX 6](https://www.quectel.com/UploadFile/Product/Quectel_EG91_LTE_Standard_Specification_V1.9.pdf) |
| * designates all SKU of that type |                                                              |                                                              |

**Antennas we have used successfully across our product line**

##### LTE CAT-1 / CAT-M / Nb-IoT / GSM

| **Vendor/Part Number**                   | **Description**                         |
| :--------------------------------------- | :-------------------------------------- |
| Pulse W3796                              | surface mount component                 |
| Maximus FXUB66                           | flexible printed circuit single-channel |
| Molex 2091420180                         | flexible printed circuit single-channel |
| Taoglas MFX3.07.0150C (Cat-M/NBIoT Only) | flexible printed circuit single-channel |
| Taoglas FXUB63.07.0150C                  | flexible printed circuit single-channel |
| Pulse W6112B0100                         | flexible printed circuit dual-channel   |
| Taoglas MA256.A.LBI.001                  | dual channel + active GPS               |

## Diversity Antenna for Wideband Notecards

NOTE-WBEX and NOTE-WBNA have two U.FL cellular antenna connectors. You must connect an antenna to the MAIN connector. The purpose of the DIV connector is to use LTE Cat1 antenna diversity to improve reception in applications where the antennas see reflected copies of the received signal, such as in a basement. A connection to the DIV connector is optional and is only necessary when a single MAIN antenna does not perform adequately.
