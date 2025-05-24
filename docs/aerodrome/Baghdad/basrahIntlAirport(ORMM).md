# 4. Basrah Intl Airport (ORMM)
## 4.1. Particulars

### 4.1.1. Aerodrome Description

Basrah International Airport is the second largest international airport in Iraq, located in South Iraq. The airport is also used as a military base.

### 4.1.2. Aerodrome Geographical Data

| **Data**              | **Value**              |
|-----------------------|------------------------|
| ARP Coordinates       | N30°32.9' E47°39.7'    |
| Elevation at ARP      | 11 feet                |
| Magnetic Variation    | 3° East                |

### 4.1.3. Radio Navigation & Landing Aids

| **Type**     | **Ident** | **Name**  | **Frequency** | **Remarks**                                                    |
|--------------|-----------|-----------|---------------|----------------------------------------------------------------|
| VOR/DME      | BSR       | BASRAH    | 112.3 MHz     |                                                                |
| ILS/LOC 32   | I-BIA     | -         | 111.7 MHz     | ILS CAT I                                                      |
| ILS/LOC 14   | I-BSR     | -         | 111.3 MHz     | Seemingly not in use due to a lack of published ILS chart.     |

### 4.1.4. Runways

| **Runway** | **Runway Dimension** | **MAG BRG**    | **Threshold Elevation** |
|------------|----------------------|----------------|--------------------------|
| 14         | 4007 x 45 m          | 135°           | 10 feet                  |
| 32         | 4007 x 45 m          | 315°           | 10 feet                  |


## 4.2. General Aerodrome procedures

Not much is known about Basrah airport, likely due to military presence at the airport. It is a simple airport with one runway, a small civil terminal apron and a cargo apron, with a total of 12 gates. The airport has a GMC position (ORMM_GND), an ADC position (ORMM_TWR) and a TMA position (ORMM_APP).

### 4.2.1. Preferential Runway System.
The preferential runway is runway 32, as it has a published ILS approach procedure, unlike runway 14.

### 4.2.2. IFR Procedures
All departures are assigned an IFR clearance with an omni-directional departure. IFR departures always file the Basrah VOR (BSR) as their first waypoint in the clearance, followed by a direct to one of the following waypoints to join their flight-planned route:

* ALPET (North/Southwest/West)
* KODAV (North/East)
* SIDAD (South)

As is the procedure for all IFR departures in Iraq, ADC (ORMM_TWR) needs to get a release for departure from ORMM_APP, in addition to departure instructions for the heading and initial climb to maintain after departure.

## 4.3. TMA procedures
The TMA position for Basrah airport is ORMM_APP and forms a part of the Ali TMA, together with ORNI_APP. As with all approach positions, its radio-telephony callsign is “Baghdad Approach'' and controls traffic in the Ali TMA from 1,500ft to FL235, excluding the north section of the TMA, when ORNI_APP is online. An important note to this position is that when ORNI_APP is offline, ORMM_APP assumes control of the whole Ali TMA, which includes the underlying ORNI airport. IFR departures from Basrah need to be radar-vectored to their first fix of departure.

### 4.3.1. IFR Arrivals
IFR arrivals into Basrah need to be radar-vectored for either an ILS or Localiser approach for RWY32 or a VOR/DME approach for runway 32 or runway 14. A visual approach may also be assigned, especially if runway 14 is in use. IFR arrivals following a charted approach procedure may be cleared direct to “WOGET”, which is the initial approach fix for all 3 charted approaches. This waypoint is located abeam the airport to its west and follows an ARC DME towards the respective final approach course.

### 4.3.2. Coordination with Kuwait
Departures via SIDAD are assigned FL230 and direct to SIDAD to join their flight plan, before being transferred to Kuwait Control (not Baghdad). Similarly, Basrah arrivals via TASMI are transferred directly from Kuwait to ORMM_APP.