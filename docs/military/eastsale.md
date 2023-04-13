---
  title: East Sale TCU
---

--8<-- "includes/abbreviations.md"

| Name               | Callsign       | Frequency        | Login Identifier              |
| ------------------ | -------------- | ---------------- | --------------------------------------|
| East Sale Approach  | Sale Approach | 123.300 | ES_APP  |
| East Sale ADC | Sale Tower  | 118.300 | ES_TWR  |
| East Sale SMC | Sale Ground | 127.250 | ES_GND  |
| East Sale ACD | Sale Delivery | 134.100 | ES_DEL  |
| East Sale ATIS  | | 125.400 | YMES_ATIS |

## Airspace
### Default
By default, ES APP owns all of the R359 Restricted Areas, detailed below:

- R359A (`SFC`-`A060`)
- R359B (`A010`-`A060`)
- R359C (`A060`-`F210`)
- R359D (`A040`-`F210`)
- R359E (`A060`-`F210`)
- R359F (`A040`-`F210`)
- R359G (`A060`-`F210`)
- R359H (`F210`-`F450`)

### Classification
All airspace owned by ES TCU when online is reclassified to **Class C**. All civil aircraft will receive a **Class C** air traffic service, and all military aircraft are to receive a **Class D** separation service.

### Separation Services
The following table summarises the separation that shall be provided by ES TCU:

| Flight Rules  | Separated From  | Traffic Information only  |
| ------------- | --------------  | ------------------------  |
| Military IFR  | Military IFR, Civil IFR, Civil VFR, All SVFR  | Military VFR  |
| Military VFR  | Civil IFR | Civil VFR, Military IFR, Military VFR, All SVFR |
| SVFR __due CLD__  | Civil IFR, Military IFR, SVFR __due VIS__ | Military VFR, Civil VFR, SVFR __due CLD__ |
| SVFR __due VIS__  | Civil IFR, Military IFR, All SVFR | Civil VFR, Military VFR |

### Tower
When ES TCU is offline, the airspace within the R359A and R359B Restricted Areas is owned by ES ADC (`SFC`-`A060`), and is **Class C**.

When EN ADC is offline, ES ADC is responsible for the Class C airspaces in the "Coffin" (`SFC`-`A015`), and in the "South East Quadrant" (`SFC`-`A020`).

### Surveillance
ES ADC is permitted to use Surveillance standards for separation. Surveillance coverage can be expected to be available at all levels in the ES ADC airspace.
For simulation purposes, visual separation is assumed to exist below the cloud base, and within 5nm of the aerodrome. Visual separation can still be used to separate from aircraft on an instrument approach, below the cloud base.

!!! note
    Additional charts to the AIP may be found in the RAAF TERMA document, available towards the bottom of [RAAF AIP page](https://ais-af.airforce.gov.au/australian-aip){target=new}

## Circuit Areas


## Training Areas

There are 16 training areas (`A`-`H` and `S`-`Z`), which are generally defined by:

1. Interior Training Areas - A, B, C, D, E, F, G, H
2. Exterior Training Areas - S, T, U, V, W, X, Y, Z

The exterior training areas consist of an "inner" (12-20NM) and "outer" (20-35NM) section. These sections have been established to streamline a standard restriction often imposed by ATC for achieving traffic management goals.

!!! tip
    Clearances for training areas follow standard [Coded Clearances](#clearances)

## Lanes

Within R359, there are 16 distinct training areas separated by 8 lanes. These lanes serve as departure/arrival paths for aircraft traveling to or from the external training areas and/or designated routes for entering and exiting R359. The lanes are determined by GNSS waypoints located at 12, 35, and 50 NM (YMES AD).

!!! important
    To standardize and prevent conflicts in training area operations, lanes are assigned as either inbound or outbound. However, they can be used as needed when instructed by ATC. If lane tracking is necessary, ATC must indicate the lane or the GNSS waypoint on a lane as part of the airways clearance.

### **Outbound**

Designated for outbound tracking:

| Track Name    | Routing   | Bearing |
| ------------- | --------- | ------- |
| Northern Lane | LEKEM - GONED - LANOS | 359 bearaing |
| Eastern Lane  | VEMDA - KADRU - TAVET | 090 bearing |
| Southern Lane | SABAX - LUTUK - NOLOX | 180 bearing |
| Western Lane  | DUGAD - LERKO - DUNNE | 270 bearing (V434) |

### **Inbound**

Designated for inbound tracking:

| Track Name    | Routing   | Bearing |
| ------------- | --------- | ------- |
| Lakes Lane | GIPPS - TODIV - OMBOR | 049 bearaing (W297) |
| Bass Lane  | PUKIM - REMOT - KIGAG | 135 bearing |
| Strezlecki Lane | RUPOD - PARNU - TEBUM | 224 bearing |
| Avon Lane  | ENBUD - UPSAL - AKVIN | 315 bearing |

### Vertical Dimensions

Lanes extend from `SFC` *or base or Restricted Area*, whichever is greater, to `F160`.

### Longford Lane
Longford Lane is active at all times R259 is active.

### Princes Route
Princes Route is active at all times R259 is active.

## Aerodrome
### Standard Taxi Routes

## Radio Etiquitte
### Clearances
In order to make ATC clearances and pilot read-backs more efficient, coded clearances are employed to authorize aircraft access to training zones, special use airspace, operational areas, or particular activities.

**Training Areas** - airways clearances will be in the form of:

(C/S), CLEARED (TRAINING AREA)

!!! example
    <span>**ROLR126** -> **ES TCU**</span>: "Sale Tower, g'day, ROLR126 with B requesting clearance to training area Hotel"  
    <span>**ES TCU** -> **ROLR126**</span>: "ROLR126, Sale Tower, g'day, cleared Hotel"

**ESL and WSL Circuit Areas** - airways clearances will be in the form of:

"(C/S), CLEARED EAST/WEST SALE CIRCUIT AREA"

!!! example
    <span>**RGNT91** -> **ES TCU**</span>: "Sale Tower, g'day, RGNT126 with F requesting circuits West Sale."  
    <span>**ES TCU** -> **RGNT91**</span>: "RGNT126, Sale Tower, g'day, cleared West Sale circuit area"

## Coordination
### ES TCU / ELW(All)

#### Airspace
Due to the variable nature of the ES TCU airspace, ES APP shall coordinate to the relevant ENR exactly what airspace is being released, upon either ELW(All) or ES APP logging on.

#### Departures
Due to the nature of ES TCU operations, and the proximity to busy YMML airspace, all north- and west-bound departures shall be heads-up coordinated to ELW(All) prior to **10nm** from the boundary. Practically, this will need to be completed as soon as possible, ie, as soon as the aircraft becomes identified on departure.

!!! example
    <span class="coldline">**ES TCU** -> **ELW**</span>: "via MNG, ROLR399, will be assigned F200"  
    <span class="coldline">**ELW** -> **ES TCU**</span>: "ROLR399, F200"

!!! tip
    To keep it simple and safe, coordinate departures at the Highest Assignable level within your airspace (eg, with standard ES TCU configuration, FXXX to the N/E/S/W). You may coordinate other levels with ELW(All) if required for separation purposes.

### ES TCU / ES ADC
#### Departures
!!! important
    East Sale does **not** utilise autorelease. **All** aircraft must be 'Next' coordinated with ES ADC.

A 'Next' call is made for all aircraft when they are next to depart. ES ADC must inform ES TCU if the aircraft does not depart within **2 minutes** of the next call.

!!! example
    <span class="hotline">**ES ADC** -> **ES TCU**</span>: "Next, ROLR121"  
    <span class="hotline">**ES TCU** -> **ES ADC**</span>: "ROLR121"

The Standard Assignable level from ES ADC to ES TCU is the lower of `A050` or the `RFL`, and assigned a SID. Any other aircraft must be heads-up coordinated in full.

!!! example
    <span class="hotline">**ES ADC** -> **ES TCU**</span>: "Next, EVY13C"  
    <span class="hotline">**ES TCU** -> **ES ADC**</span>: "EVY13C, A080"  
    <span class="hotline">**ES ADC** -> **ES TCU**</span>: "A080, EVY13C"

#### Arrivals/Overfliers
ES TCU must heads-up coordinate all arrivals and overfliers to ES ADC prior to handoff. Practically, this needs to be done as soon as possible, ie, as soon as WLM TCU receives coordination on the aircraft.

!!! example
    <span class="hotline">**ES TCU** -> **ES ADC**</span>: "via ESL, ZULU, close formation of 3, do you have any restrictions or requirements?”  
    <span class="hotline">**ES ADC** -> **ES TCU**</span>: "ZULU, no frequency requirements, A040"

Aircraft with ADES YMES shall be cleared for the approach prior to handoff.

!!! example
    <span class="hotline">**ES TCU** -> **ES ADC**</span>: "via MESWP for the RNP RWY 09, RGNT622”  
    <span class="hotline">**ES ADC** -> **ES TCU**</span>: "RGNT622"

## Miscellaneous
### Circuit Operations
VFR aircraft that will operate only in ADCs airspace shall be assigned SSR code 0100

Circuit altitude will depend on the type of aircraft. Assign circuit altitudes for the following aircraft types:

1. Military Jet - `A020`
2. Civil Jet - `A015`
3. Non-jet - `A010`

The circuit direction for runways 04 and 27 are right hand only.