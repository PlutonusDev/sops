---
  title: Albury (YMAY)
---

--8<-- "includes/abbreviations.md"

## Positions
| Name | Callsign | Frequency | Login Identifier |
| ---- | -------- | --------- | ---------------- |
| Albury ADC | Albury Tower | 123.250 | AY_TWR |
| Albury SMC | Albury Ground | 121.800 | AY_GND |
| Albury ATIS | N/A | 133.850 | YMAY_ATIS |

## Airspace
<figure markdown>
![AY ADC Airspace](img/YMAY_airspace.png){ width="700" }
  <figcaption>AY ADC Airspace</figcaption>
</figure>

Refer to [Class D Tower Skills](../../controller-skills/classdtwr) for more information.

## Surveillance
AY ADC is permitted to use Surveillance standards for separation. Surveillance coverage can be expected to be available at all levels in the AY CTR.  
For simulation purposes, visual separation is assumed to exist below the cloud base, and within 5nm of the aerodrome. Visual separation can still be used to separate from aircraft on an instrument approach, below the cloud base.

## Coordination
### Departures
A 'Next' call is made for all aircraft when they are next to depart. AY ADC must inform ELW(BLA) if the aircraft does not depart within **2 minutes** of the next call.

!!! example
    <span class="hotline">**AY ADC** -> **BLA**</span>: "Next, AM324"  
    <span class="hotline">**BLA** -> **AY ADC**</span>: "AM324, Unrestricted"  
    <span class="hotline">**AY ADC** -> **BLA**</span>: "AM324"

The Standard Assignable level from AY TWR to ELW(BLA) is the lower of `A070` or the `RFL`, any other level must be prior coordinated.

### Arrivals/Overfliers
ELW(BLA) will heads-up coordinate all arrivals/overfliers to AY ADC

!!! example
    <span class="hotline">**BLA** -> **AY ADC**</span>: "Via ARRAN1 Arrival, RXA6783”  
    <span class="hotline">**AY ADC** -> **BLA**</span>: "RXA6783"  

The Standard Assignable level from ELW(BLA) to AY ADC is `A080`, any other level must be prior coordinated.