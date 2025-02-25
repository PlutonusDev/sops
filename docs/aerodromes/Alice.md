---
  title: Alice Springs (YBAS)
---

--8<-- "includes/abbreviations.md"

## Positions
| Name | Callsign | Frequency | Login Identifier |
| ---- | -------- | --------- | ---------------- |
| Alice Springs ADC | Alice Tower | 118.300 | AS_TWR |
| Alice Springs ATIS | N/A | 123.000 | YBAS_ATIS |

## Airspace
AS ADC is responsible for the Class D airspace `SFC` to `A045`, as well as the Class C airspace `A045` to `A065`, within the AS CTR.

<figure markdown>
![AD ADC Airspace](img/YBAS_airspace.png){ width="1000" }
  <figcaption>AD ADC Airspace</figcaption>
</figure>

Refer to [Class D Tower Skills](../../controller-skills/classdtwr) for more information.

## Surveillance
AS TWR is permitted to use Surveillance standards for separation. Surveillance coverage can be expected to be available at all levels in the AS CTR.  
For simulation purposes, visual separation is assumed to exist below the cloud base, and within 5nm. Visual separation can still be used to separate from aircraft on an instrument approach, below the cloud base.
## Coordination
### Departures
Departures from YBAS in to ASP Class C will be coordinated when ready for departure.

!!! example
    <span class="hotline">**AS ADC** -> **ASP**</span>: "Next, QFA797"  
    <span class="hotline">**ASP** -> **AS ADC**</span>: "QFA797, Unrestricted"  
    <span class="hotline">**AS ADC** -> **ASP**</span>: "QFA797"

The Standard Assignable level from AS ADC to ASP is the lower of `A070` or the `RFL`, any other level must be prior coordinated.

### Arrivals/Overfliers
ASP will heads-up coordinate all arrivals/overfliers to AS ADC

!!! example
    <span class="hotline">**ASP** -> **AS ADC**</span>: "Via SADEL, QFA1956”  
    <span class="hotline">**AS ADC** -> **ASP**</span>: "QFA1956"  

The Standard Assignable level from ASP to AS ADC is `A080`, any other level must be prior coordinated.