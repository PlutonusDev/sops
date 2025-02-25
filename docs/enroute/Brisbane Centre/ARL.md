---
  title: Armidale (ARL)
---

--8<-- "includes/abbreviations.md"
## Positions

| Name | Callsign | Frequency | Login ID |
| ---- | -------- | --------- | -------- |
| **Armidale** | **Brisbane Centre** | **130.900** | **BN-ARL_CTR** |
| Mudgee† | Brisbane Centre | 133.000 | BN-MDE_CTR |
| Cessnock† | Brisbane Centre | 123.400 | BN-CNK_CTR |
| Manning† | Brisbane Centre | 130.100 | BN-MNN_CTR |
| Maitland† | Brisbane Centre | 132.350 | BN-MLD_CTR |
| Ocean† | Brisbane Centre | 128.600 | BN-OCN_CTR |

† *Non-standard positions* may only be used in accordance with [VATPAC Ratings and Controller Positions Policy](https://vatpac.org/publications/policies)
## Airspace
When **TW ADC** is offline, TW CTR (Class D and C `SFC` to `A085`) reverts to Class G, and is administered by ARL and MDE. Alternatively, ARL (not MDE) may provide a [top-down procedural service](../../../aerodromes/tamworth) if they wish (not recommended).  

When **CFS ADC** is offline, CFS CTR (Class D `SFC` to `A045`) reverts to Class G, and is administered by MNN and INL. MNN is **not permitted** to provide a [top-down procedural service](../../../aerodromes/Coffs), only INL can do this, and they must coordinate with MNN if they are doing so.

<figure markdown>
![Armidale Airspace](../assets/arl.png){ width="700" }
  <figcaption>Armidale Airspace</figcaption>
</figure>

## Sector Responsibilities
### Armidale (ARL) / Manning (MNN)
ARL and MNN are responsible for initial sequencing, issuing STAR Clearances, and issuing initial descent for aircraft bound for YSSY, via BOREE and MEPIL respectively.  
Jet aircraft for YSSY shall be assigned the **BOREE** STAR.  
Non-jet aircraft for YSSY shall be assigned the **MEPIL** STAR.

For Sequencing purposes, MEPIL and BOREE must be considered to be the same STAR. Practically, this means ARL must sequence at least a 2 minute gap between all YSSY arrivals, whether they are arriving via the same feeder fix or not.
### Cessnock (CNK) / Maitland (MLD)
CNK and MLD are responsible for final sequencing for aircraft bound for YSSY, via BOREE and MEPIL respectively.
### Mudgee (MDE)
Just keeping them separated!
### Ocean (OCN)
OCN is responsible for sequencing, issuing STAR Clearances, and issuing descent for aircraft bound for YSSY via MARLN.
## Coordination
### ARL (All) / SY TCU
The Standard Assignable level from ARL(All) to SY TCU is:  
`A100` for aircraft tracking via BOREE or MARLN, and assigned the relevant STAR  
`A090` for aircraft tracking via MEPIL, and assigned the MEPIL STAR  

All other aircraft must be voice coordinated to SY TCU prior to **20nm** from the boundary.

The Standard Assignable level from SY TCU to ARL(All) is the lower of `F280` or the `RFL`, and tracking via a SID terminus.

Refer to [Sydney TCU Airspace Division](../../terminal/sydney/#airspace-division) for information on airspace divisions when **SAS**, **SDN**, **SDS** and/or **SRI** are online.

### ARL (All) / ENR
As per [Standard coordination procedures](../../controller-skills/coordination/#enr-enr), Voiceless, no changes to route or CFL within **50nm** to boundary.

### ARL/MDE/CNK/MNN/MLD/OCN Internal
As per [Standard coordination procedures](../../controller-skills/coordination/#enr-enr), Voiceless, no changes to route or CFL within **50nm** to boundary.

That being said, it is *advised* that ARL(All) gives **Heads-up Coordination** in the following scenarios:   
- MNN to ARL for all aircraft  
- ARL to MNN for all aircraft  
- CNK to MLD for all aircraft  
- MLD to CNK for all aircraft

### ARL/MDE / TW ADC
#### Airspace
When **TW ADC** is online, **ARL** owns the Class C airspace from `A065` upwards. **TW ADC** owns the Class D airspace `SFC` to `A045` and Class C airspace `A045` to `A065`.

#### Departures
Departures from YSTW in to ARL/MDE Class C will be coordinated when ready for departure.

!!! example
    <span class="hotline">**TW ADC** -> **MDE**</span>: "Next, SKV"  
    <span class="hotline">**MDE** -> **TW ADC**</span>: "SKV, Unrestricted"  
    <span class="hotline">**TW ADC** -> **MDE**</span>: "SKV"  

The Standard Assignable level from **TW ADC** to ARL/MDE is the lower of `A070` or the `RFL`.

#### Arrivals
YSTW arrivals shall be heads-up coordinated to **TW ADC** from ARL/MDE prior to **5 mins** from the boundary.

!!! example
    <span class="hotline">**ARL** -> **TW ADC**</span>: "QLK6D, via MATLA DCT STWWD"  
    <span class="hotline">**TW ADC** -> **ARL**</span>: "QLK6D"  

The Standard Assignable level from ARL/MDE to **TW ADC** is `A080`, any other level must be prior coordinated.

### MNN / CFS ADC
#### Airspace
When **CFS ADC** is online, **INL** and **MNN** owns the Class C airspace from A045 upwards, and **CFS ADC** owns the Class D airspace SFC-A045.

#### Departures
Departures from YCFS in to MNN Class C will be coordinated when ready for departure.

!!! example
    <span class="hotline">**CFS ADC** -> **MNN**</span>: "Next, CFH21"  
    <span class="hotline">**MNN** -> **CFS ADC**</span>: "CFH21, Unrestricted"  
    <span class="hotline">**CFS ADC** -> **MNN**</span>: "CFH21"  

The Standard Assignable level from **CFS ADC** to MNN is the lower of `A070` or the `RFL`.

#### Arrivals
YCFS arrivals shall be heads-up coordinated to **CFS ADC** from MNN prior to **5 mins** from the boundary.

!!! example
    <span class="hotline">**MNN** -> **CFS ADC**</span>: "Via KADSI, RXA6438"  
    <span class="hotline">**CFS ADC** -> **MNN**</span>: "RXA6438"  

The Standard Assignable level from MNN to **CFS ADC** is `A080`, any other level must be prior coordinated.

#### Overfliers
Any aircraft that will enter CFS ADC airspace, and not landing at YCFS, must be Heads-up coordinated prior to **5 mins** from the boundary.

!!! example
    <span class="hotline">**MNN** -> **CFS ADC**</span>: "via CFS, GNP, Overflier"  
    <span class="hotline">**CFS ADC** -> **MNN**</span>: "GNP, A030"

### ARL (All) / WLM TCU
#### Airspace
By default, **WLM TCU** owns the airspace within the **R578A-G** restricted areas, unless stated otherwise by ad-hoc release or NOTAM. It is the responsibility of the **WLM TCU** controller to inform ARL(All) of what airspace they are assuming.
#### Departures
Departures from **WLM TCU** in to ARL(All) Class C will be heads-up coordinated.

!!! example
    <span class="hotline">**WLM TCU** -> **MNN**</span>: "Departed YWLM, WGTL33, will be assigned F120"  
    <span class="hotline">**MNN** -> **WLM TCU**</span>: "WGTL33, F120"  

#### Arrivals/Overfliers
All aircraft transiting from ARL(All) to **WLM TCU** must be heads-up coordinated prior to **20nm** from the boundary. Operations within **WLM TCU** are fairly ad-hoc, so there are no standard assignable levels, simply whatever the ARL(All) and **WLM TCU** controller agree on.

!!! example
    <span class="hotline">**MNN** -> **WLM TCU**</span>: "via SANAD, JST458, will be assigned F130"  
    <span class="hotline">**WLM TCU** -> **MNN**</span>: "JST458, F130"  

!!! tip
    To keep it simple and safe, coordinate departures at the Lowest Assignable level over the TCU (eg, with standard WLM TCU configuration, `F130`). You may coordinate other levels with WLM TCU if required for separation purposes.

#### R574 Release
To put it bluntly, the R574 Restricted Area is quite large.

<figure markdown>
![R574 Restricted Area](../../military/img/r574.png){ width="700" }
  <figcaption>R574 Restricted Area</figcaption>
</figure>

It also occupies a lot of airspace that would commonly be used by YSSY arrivals and departures. If YWLM military operations are taking ownership of this airspace, it is good practice to negotiate an airspace release, whether that be a lateral or vertical portion of airspace (or a combination), to enable them to facilitate YSSY arrivals and departures with minimal impact.

### OCN/MNN / TSN/HWE (Oceanic)
As per [Standard coordination procedures](../../controller-skills/coordination/#enr-oceanic), Heads-up coordinate prior to **15 mins** to boundary.