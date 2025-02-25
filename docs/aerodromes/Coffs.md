---
  title: Coffs Harbour (YCFS)
---

--8<-- "includes/abbreviations.md"

## Positions
| Name | Callsign | Frequency | Login Identifier |
| ---- | -------- | --------- | ---------------- |
| Coffs Harbour ADC | Coffs Tower | 118.200 | CFS_TWR |
| Coffs Harbour ATIS | N/A | 130.300 | YCFS_ATIS |

## Airspace
<figure markdown>
![CFS ADC Airspace](img/ycfs_airspace.png){ width="700" }
  <figcaption>CFS ADC Airspace</figcaption>
</figure>

Refer to [Class D Tower Skills](../../controller-skills/classdtwr) for more information.

## Surveillance
CFS ADC is permitted to use Surveillance standards for separation. Surveillance coverage can be expected to be not available below `A028` in the CFS CTR.  
For simulation purposes, visual separation is assumed to exist below the cloud base, and within 5nm. Visual separation can still be used to separate from aircraft on an instrument approach, below the cloud base.

CFS ADC must establish a [Procedural Standard](../../controller-skills/classdtwr/#standards) prior to losing surveillance identification of an aircraft.

!!! caution
    A procedural and/or visual standard **must** be put in place for all aircraft below `A028`.
## Instrument Approaches
Only one aircraft is permitted to conduct an instrument approach at any time, due to limited surveillance coverage. CFS ADC must ensure that all aircraft are procedurally separated from any portion of an instrument approach and missed approach that is conducted below `A028`.  

If required, CFS ADC can pass amended tracking/level instructions to an aircraft for a missed approach for separation purposes, as long as the aircraft can be issued **uninterrupted climb** to the LSALT/MSA once identified.

## Coordination
### Departures
A 'next' call is made for all aircraft when they are next to depart. CFS ADC must inform INL/ARL(MNN) if the aircraft does not depart within **2 minutes** of the next call.

!!! example
    <span class="hotline">**CFS ADC** -> **MNN**</span>: "Next, QJE1573"  
    <span class="hotline">**MNN** -> **CFS ADC**</span>: "QJE1573, Unrestricted"  
    <span class="hotline">**CFS ADC** -> **MNN**</span>: "QJE1573"

The Standard Assignable level from CFS ADC to INL/ARL(MNN) is the lower of `A070` or the `RFL`, any other level must be prior coordinated.
### Arrivals/Overfliers
INL/ARL(MNN) will heads-up coordinate all arrivals/overfliers to CFS ADC.

!!! example
    <span class="hotline">**INL** -> **CFS ADC**</span>: "Via KADSI, RXA6416”  
    <span class="hotline">**CFS ADC** -> **INL**</span>: "RXA6416"  

The Standard Assignable level from INL/ARL(MNN) to CFS ADC is `A080`, any other level must be prior coordinated.