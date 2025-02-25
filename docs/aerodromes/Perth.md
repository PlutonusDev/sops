---
  title: Perth (YPPH)
---

--8<-- "includes/abbreviations.md"

## Positions
| Name | Callsign | Frequency | Login ID |
| ---- | -------- | --------- | -------- |
| **Perth ADC** | **Perth Tower** | **127.400** | **PH_TWR** |
| **Perth SMC West** | **Perth Ground** | **121.700** | **PH_GND** |
| Perth SMC East† | Perth Ground | 122.200 | PH-E_GND |
| **Perth ACD** | **Perth Delivery** | **118.550** | **PH_DEL** |
| Perth ATIS | N/A | 123.800 | YPPH_ATIS |

† *Non-standard positions* may only be used in accordance with [VATPAC Ratings and Controller Positions Policy](https://vatpac.org/publications/policies)

## Airspace
PH ADC is not responsible for any airspace by default.

## Runway Selection

### Southwest Plan
- Any combination of Runway 21 and/or 24.
- The ATIS shall notify `EXPECT ILS APPROACH`


**Runway Assignment**

| Feeder Fix | Runway |
| ---------- | ------ |
| JULIM | 21 |
| CONNI | 21 |
| WAVES | 21 |
| BEVLY | 24, 21 (if operationally required) | 
| GRENE | 24 |
| SOLUS | 24 |

### Northeast Plan
- Runway 03 for arrivals.
- Runway 03 for departures via:  
    - AVNEX
    - OTLED
    - MANDU
    - SOLUS
    - KEELS
- Runway 06 for all other departures.

- In the following conditions, ATIS shall notify `EXPECT ILS APPROACH`
    - By night; and/or
    - Cloud base of `A032` or below

## Miscellaneous

### Circuit Training
Circuit training traffic shall be issued SSR code and clearance to operate within circuit area not above `A015`. Circuit training is typically conducted on Runway 03/21.

All circuits are to be conducted to the east of Runway 03/21 (right-hand circuit Runway 03).

### Scenic Flights
When traffic permits, VFR scenic flights over Perth are cleared via VICTOR 65 route (CTE-PCTY-HKE).

### Separation
#### 2400m Reduced Runway Separation Minima
By day, ATC may use 2400m runway separation between aircraft arriving to Runway 03/21. Both aircraft may occupy the runway during application of the [standard](../../controller-skills/sepstandards/#2400m-reduced-runway-separation-minima).

### ATIS Notification of Departure Runway
When both Runway 03 and Runway 06 are nominated as departure runways, broadcast the following:

`RWY 03 FOR DEP VIA OTLED, AVNEX, MANDU, SOLUS AND KEELS. RWY 06 FOR ALL OTHER DEP.`

## Coordination
### PH ADC / PH TCU
#### Auto Release
'Next' coordination is **not** required for aircraft that are:   
    a) Departing from a runway nominated on the ATIS; and  
    b) Assigned the standard assignable level; and  
    c) Assigned a **Procedural SID**

All other aircraft require a 'Next' call to PH TCU.

!!! example
    <span class="hotline">**PH ADC** -> **PH TCU**</span>: "Next, ABC, runway 03"  
    <span class="hotline">**PH TCU** -> **PH ADC**</span>: "ABC, Heading 010, unrestricted"  
    <span class="hotline">**PH ADC** -> **PH TCU**</span>: "Heading 010, ABC"  

    **PH ADC**: "ABC, Assigned heading left 010, Runway 03, Cleared for Takeoff"  
    **ABC**: "Left heading 010, Runway 010, Cleared for Takeoff, ABC"

The PH TCU controller can suspend/resume Auto Release at any time, with the concurrence of **PH ADC**.

The Standard Assignable level from PH ADC to PH TCU is the lower of `A050` or the `RFL`

#### Departures Controller
Refer to [Perth TCU Airspace Division](../../terminal/perth/#airspace-division) for information on airspace divisions when **PHD** is online.

### PH ACD / PH TCU
The controller assuming responsibility of ACD shall give heads-up coordination to the relevant PH TCU controller prior to the issue of the following clearances:  
a) VFR Departures  
b) Aircraft using a runway not on the ATIS

!!! example
    **ABC**: "Perth Delivery, ABC, Requesting a Victor 65 scenic."  
    **PH ACD**: "ABC, Perth Delivery, Standby"  

    <span class="coldline">**PH ACD** -> **PH TCU**</span>: "ABC, Requesting Victor 65 scenic"  
    <span class="coldline">**PH TCU** -> **PH ACD**</span>: "ABC, Cleared Victor 65 scenic"  
    <span class="coldline">**PH ACD** -> **PH TCU**</span>: "Cleared Victor 65 scenic, ABC"   
     
    **PH ACD**: "ABC, Cleared for a victor 65 scenic"  
    **ABC**: "Cleared for a victor 65 scenic, ABC"  