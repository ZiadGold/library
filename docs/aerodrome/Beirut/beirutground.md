# 2. Beirut Ground


## 2.1 General Provisions
Beirut Ground is responsible for handling all ground movement on Rafic Hariri International
Airport’s aerodrome in addition to providing IFR and VFR flights proper clearances based on a valid flight plan, valid route, and flight level.

In the event where the flight plan contains an invalid route or flight level, the ground controller is responsible for correcting the error prior to issuing the clearance.


## 2.2 Departure Clearance

### 2.2.1 IFR Clearance
Beirut Ground issues IFR clearances for departing aircraft stated that they request their clearance
with the following information and under the following conditions:

* A valid flight plan with a valid route and requested flight level according to the direction of flight (eastbound or westbound).
* Callsign
* Aircraft type
* Parking stand
* ATIS information
* Requested flight level
* Destination
* SID

### 2.2.2 IFR Clearance Issuance Format

The IFR clearance shall be expected to be issued in the following format:

* Callsign
* Controller identification (if initial contact)
* Destination
* Departure procedure
* Departure runway
* Flight planned route (identical to “as filed”)
* Initial climb
* Squawk code

!!! example
    **Controller**: “MEA374, BEIRUT GROUND, CLEARED TO JEDDAH VIA THE KAD2D DEPARTURE RUNWAY 21, FLIGHT PLANNED ROUTE, INITIAL CLIMB 5,000 FT, SQUAWK 4301.”

A full readback shall be expected by the ground controller. If the pilot does not report the ATIS
information on initial contact, it shall be passed along with the QNH during the readback correct
phrase.


!!! example
    **Controller**: “MEA374, READBACK CORRECT, INFORMATION ALPHA, QNH 1017, ADVISE WHEN READY FOR PUSHBACK.”

### 2.2.3 Aircrafts Requiring a Reroute

Aircrafts requiring a reroute are typically flight plans with invalid routes. Those flight plans will be
marked with a red or yellow “R” in their flight strip. In some cases, you may notice a red “X”
symbol which indicates that both the route and flight level must be checked.
In the event where the aircraft’s filed route is invalid, aircrafts must be rerouted before issuing
them the clearance. This can be done in one of two methods:
* Private message to the pilot which includes the new full valid route, or the part of the
route which has been modified.
* Issuing the clearance with the reroute over the frequency voice.

!!! example
    **Controller**: “MEA364, BEIRUT GROUND, CLEARED TO JEDDAH VIA THE KAD2D DEPARTURE RUNWAY 21, ELIKA VELOX LAKTO, FLIGHT PLANNED ROUTE, INITIAL CLIMB 5,000 FT, SQUAWK 4301.”

Aircrafts shall be informed of any anomalies in their flight plan as soon as they connect to the
network.


### 2.2.4 Aircrafts Requiring a New Clearance
Aircrafts may need to obtain a fresh clearance under circumstances such as a pilot's request for a particular runway or departure procedure different from the initially granted one, or in response to alterations in weather conditions resulting in changes to the runway setup.


!!! scenario "SCENARIO"
    MEA364 was cleared to Jeddah via the KAD2D departure runway 21 with an initial climb of 5,000 FT and squawk 4301, then the pilot requests KAD2D departure runway 17

Instead of repeating the whole clearance again, the controller may provide a new clearance using
the following format:

!!! solution "SOLUTION"
    **Controller**: “MEA364, RE-CLEARED VIA THE KAD2D DEPARTURE RUNWAY 17, THE REST REMAINS UNCHANGED.”

In situations necessitating updated clearances because of weather and runway configuration changes, all aircraft on the stands and aprons must be issued new clearances in accordance with the previously mentioned format. However, aircraft that have already commenced pushback will adhere to their existing clearances and configuration.

### 2.2.5 Aircrafts Requiring a New Cruise Level
Some aircrafts may request an invalid cruise level with respect to the direction of their flight at heir top of climb. Flight plans with an invalid cruise level will have a red “L” symbol next to their RFL indicating that their cruise level is invalid. In this case, the controller must correct the flight level by issuing a lower flight level by 1,000 FT or an upper flight level according to the pilot’s request. The controller must ensure that the pilot is aware of the modification by either a private message or by communicating to him by voice, or by passing the modification along with the clearance.


!!! example
    **Controller**: “MEA364, BEIRUT GROUND, CLEARED TO JEDDAH VIA THE KAD2D DEPARTURE RUNWAY 21, FLIGHT PLANNED ROUTE, FLIGHT LEVEL 370, INITIAL CLIMB 5,000 FT, SQUAWK 4301.”


## 2.3 Departure Procedures

### 2.3.1 Standard Instrument Departures
Beirut primarily uses Standard Instrument Departures as the main departure procedures. Controllers shall assign the proper SID exit waypoint based on the first enroute waypoint in their flight plan, and the proper procedure identifier based on the selected runway for departure.

All SIDs with an identifier of 2D or 1D, along with BOD1 are valid for runways 17 and 21. SIDs with an identifier of 1E are valid for runway 03. SIDs with an identifier of 2F, along with BOD2 are valid for runways 34 and 35.

| SID   | 21, 17 | 03   | 34, 35 |
|:------|:------:|:----:|:------:|
| KALDE | 2D     | 1E   | 2F     |
| LATEB | 1D     | 1E   | 2F     |
| LEBOR | 1D     | 1E   | 2F     |
| BOD   | 1      | N/A  | 2      |

Runways 03 and 16 are never used for departure, the procedures for 03 exist because back in the days runway 03 was used for departure when runway 34/16 did not exist.

Departures should primarily adhere to the Standard Instrument Departure (SID) routes, avoiding radar vectors whenever feasible. If radar vectors are to be assigned, a specific reason must be provided. Aircraft following the KALDE departure will necessitate radar vectors or direct routing to the exit waypoint of the FIR. For aircraft using the BOD departure, radar vectors or direct routing to the FIR exit waypoint are only required when transitioning via CAK. BOD departures with LATEB and LEBOR transitions do not necessitate radar vectoring.

### 2.3.2 Aircrafts Requiring Radar Vectors
Aircrafts may sometimes require radar vectors if they are unable to accept a Standard Instrument Departure, or if they are using procedural SIDs based on navigational aids such as BOD or KALDE, which require vectors or direct to the first enroute waypoint in their flight plan.

In this case, the flight is given a regular clearance with the SID, then after departure, the enroute or approach controller will issue the flight vectors or direct to the exit waypoint.

!!! example
    **Controller**: “MEA364, PROCEED DIRECT KUKLA, RESUME OWN NAVIGATION.”
!!! example
    **Controller**: “MEA364, FLY HEADING 280 DEGREES, EXPECT RADAR VECTORS TO KUKLA.”

For aircrafts who are unable to accept SIDs, clearance may be issued with radar vectors.

!!! example
    **Controller**: “MEA364, BEIRUT GROUND, CLEARED TO JEDDAH, DEPARTURE RUNWAY 21, EXPECT RADAR VECTORS TO KUKLA AFTER DEPARTURE, FLIGHT PLANNED ROUTE, INITIAL CLIMB 5,000 FT, SQUAWK 4301.”

The tower controller is responsible for issuing the initial heading of the departing aircraft with the take-off clearance.

!!! example
    **Controller**: “MEA123, TURN RIGHT HEADING 220 DEGREES AFTER DEPARTURE, WINDS 210 DEGREES AT 6 KNOTS, RUNWAY 21 CLEARED FOR TAKEOFF

## 2.4 VFR Operations
VFR operations necessitate the submission of a pre-filed flight plan that includes a valid route, except for VFR circuit activities at Beirut's Rafic Hariri International Airport and international VFR departures, for which only a pre-filed plan without a specific route is mandated. VFR circuits at Beirut require light aircrafts to maintain 1,000 ft AGL and 2,000 ft AGL for medium and heavy aircrafts.

VFR operations come with specific limitations, which entail adhering to one of the seven predefined published routes. Furthermore, VFR flights are exclusively authorized for touch-and-go operations at Rayak Airport and Kleyate Airport, provided they maintain an altitude below 1500 feet above ground level (refer to airspaces R4 and R5 in Section 3.5) without engaging in full-stop landings. Notably, VFR departures from Rayak and Kleyate airports are restricted, except in the case of military flights. VFR operations in Rayak and Kleyate receive class C services.

A VFR aircraft does not necessitate requesting clearance, the pilot shall directly request engine startup and approval will be provided based on the validity of his pre-filed flight plan and route.

### 2.4.1 VFR Clearance Format
An aircraft intending to perform VFR operations shall immediately request engine start-up provided they have pre-filed a valid flight plan meeting the conditions stated earlier. The request should follow the format provided in the example below.

!!! example
    **Pilot**: “OD-BWD, TYPE C172 AT STAND N1, WITH INFORMATION A, REQUESTING ENGINE START-UP.”

The expected response from the air traffic controller shall be:

!!! example ""
    **Controller**: “OD-BWD, BEIRUT GROUND, START-UP IS APPROVED, SQUAWK 2501.”

If the ATIS information is not provided, the information with the QNH shall be passed with the approval.

!!! example
    **Controller**: “OD-BWD, BEIRUT GROUND, INFORMATION A, QNH 1017, START-UP IS APPROVED, SQUAWK 2500.”

In the event where the pilot requests taxi immediately, the controller must ensure that the correct transponder code is set, then the QNH and information may be passed prior to the taxi clearance.

!!! example
    **Controller**: “OD-BWD, BEIRUT GROUND, SQUAWK 2501.”

    **Controller**: “OD-BWD, INFORMATION A, QNH 1017, TAXI VIA MIKE, HOLD SHORT AT HOLDING POINT MIKE, RUNWAY 17.”

### 2.4.2 VFR Departure Routes
The table below shows all the 7 valid routes for VFR departures from Beirut.

|       |                           |
| :---------- | :----------------------------------- |
| Route 1       | OLBA DCT BOD DCT DORA DCT JOUNIEH DCT MAIFOUK DCT AMCHIT DCT JOUNIEH DCT DORA BOD DCT OLBA  |
| Route 2       | OLBA DCT DAMOUR DCT BOD DCT DORA DCT JOUNIEH DCT CAK DCT TRIPOLI DCT CAK DCT JOUNIEH DCT DORA DCT BOD DCT OLBA |
| Route 3    | OLBA DCT BOD DCT DORA DCT JOUNIEH DCT TRIPOLI DCT CEDAR DCT TRIPOLI DCT JOUNIEH DCT DORA DCT BOD DCT OLBA |
| Route 4 | OLBA DCT WEST/HDG DCT CHOUIFAT DCT DAIR/EL/KAMAR DCT MAASER/EL/CHOUF DCT AIN/ZEHALTA DCT DHOUR/CHOUWER DCT BEKFAYA DCT DORA DCT BOD DCT OLBA |
| Route 5 | OLBA DCT BOD DCT DORA DCT JOUNIEH DCT AMCHIT DCT TRIPOLI DCT KLEYATE DCT TRIPOLI DCT CAK DCT JOUNIEH DCT DORA DCT BOD DCT OLBA |
| Route 6 | OLBA DCT WEST/HDG DCT CHOUIFAT DCT ALEY DCT DAHER/EL/BAIDAR DCT RAYAK DCT DAHER/EL/BAIDAR DCT BEKFAYA DCT DORA DCT BOD DCT OLBA |
| Route 7 | OLBA DCT WEST/HDG DCT CHOUIFAT DCT ALEY DCT DAHER/EL/BAIDAR DCT RAYAK DCT IAAT DCT DAIR/EL AHMAR DCT OYOUN/ORGHOCH DCT MARJAHINE DCT KLEYATE DCT TRIPOLI DCT CAK DCT JOUNIEH DCT DORA DCT BOD DCT OLBA |

VFR operations at Rayak Airport are exclusively authorized to follow routes 6 and 7.

VFR operations at Kleyate Airport are exclusively allowed to follow routes 5 and 7.

VFR operations at both airports are permitted to utilize only route 7.

Routes must be pre-filed on VATSIM exactly as provided, meaning that "MAASER/EL/CHOUF," for example, should be pre-filed as "MAASER/EL/CHOUF" in the route. It is advisable to directly copy and paste the route as presented onto VATSIM. Since most of these route waypoints do not correspond to actual navigation points, they have been specially created within our system.

When the flight plan route is filed according to these instructions, air traffic controllers will have the ability to view the flight plan route on their radar screens. It's important to note that all these waypoints serve as visual reporting points (VRPs). Consequently, pilots will have the choice of either visually following the designated route or manually entering the waypoints and their coordinates into the aircraft's GPS system to navigate automatically. The latter option will undoubtedly require more time and effort. Please refer to the table below, which contains a comprehensive list of the custom VRPs along with their coordinates.

| VRP Name           | Coordinates             |
|:-------------------:|:------------------------:|
| BOD (Published)     | 33°54'12.7"N 035°28'54.7"E |
| DORA                | 33°53'38.1"N 035°33'5.0"E  |
| JOUNIEH             | 33°58'25.3"N 035°37'11.6"E |
| MAIFOUK             | 34°10'53.3"N 035°46'43.1"E |
| AMCHIT              | 34°8'15.2"N 035°38'39.9"E  |
| DAMOUR              | 33°43'51.0"N 035°27'18.3"E |
| CAK (Published)     | 34°18'1.8"N 035°41'59.6"E  |
| TRIPOLI             | 34°26'10.6"N 035°50'7.0"E  |
| CEDAR (Published)   | 34°17'13.2"N 036°0'4.3"E   |
| WEST/HDG            | 33°50'36.0"N 035°20'38.8"E |
| CHOUIFAT            | 33°48'59.5"N 035°30'57.3"E |
| DAIR/EL/KAMAR       | 33°41'53.6"N 035°33'44.0"E |
| MAASER/EL/CHOUF     | 33°40'3.4"N 035°40'15.4"E  |
| AIN/ZEHALTA         | 33°44'26.8"N 035°41'54.3"E |
| DHOUR/CHOUWER       | 33°54'39.6"N 035°42'37.9"E |
| BEKFAYA             | 33°55'16.3"N 035°40'59.2"E |
| KLEYATE             | 34°34'53.3"N 036°1'0.2"E   |
| ALEY                | 33°48'29.0"N 035°36'21.2"E |
| DAHER/EL/BAIDAR     | 33°48'35.3"N 035°45'57.2"E |
| RAYAK               | 33°51'6.9"N 036°0'52.5"E   |
| IAAT                | 34°2'4.0"N 036°10'30.7"E   |
| DAIR/EL/AHMAR       | 34°7'24.8"N 036°7'46.9"E   |
| OYOUN/ORGHOCH       | 34°15'37.2"N 036°7'46.9"E  |
| MARJAHINE           | 34°28'13.9"N 036°20'8.9"E  |

## 2.5 Pushback Procedures
Beirut Ground issues pushback clearances to all aircrafts ready to push after receiving their respective clearances.

In the event that an aircraft requests pushback without having set a squawk code, the aircraft should be directed to hold its position and set the appropriate transponder code. Once the code is correctly configured, the pushback clearance should be automatically granted without necessitating another request from the pilot.

All aircrafts on gates G9 till G16 are not allowed to push back onto other gates, instead they should push back until reaching taxiway Juliet and face either east or west upon reaching Juliet.

Pushback clearances must contain the stand number of the aircraft, and the pushback phraseology. If the stand number of the aircraft is unknown, it can be ignored.



!!! example
    **Controller**: “MEA201, STAND G21, PUSHBACK APPROVED, FACE EAST ON JULIET.”

Conditional pushback instructions may also be issued if an aircraft is taxiing behind another waiting for pushback.

!!! example
    **Controller**: “MEA217, STAND G11, BEHIND THE COMPANY A332 MEA PASSING LEFT TO RIGHT, PUSHBACK APPROVED, FACE EAST ON JULIET, BEHIND.”

In the event where an aircraft pushing back may block the entrance to the apron, the aircraft may be instructed to stay clear of the entrance.


    

!!! scenario "SCENARIO"
    MEA229 is at gate G7 and is requesting pushback, the controller notices that his pushback on Lima might block taxiway Foxtrot.

!!! solution "SOLUTION"
    **Controller**: “MEA229, STAND G7, PUSHBACK APPROVED, FACE NORTH ON LIMA, LEAVE TAXIWAY FOXTROT FREE TO USE.”

Controllers may gain extra control over the aircraft’s pushback process by instructing the aircraft to pushback and stop near specific points using the term “ABEAM”.

!!! example
    **Controller**: “MEA229, STAND G7, PUSHBACK APPROVED, FACE NORTH ON LIMA, STOP ABEAM TAXIWAY JULIET.”

The most complex pushback phrases can be constructed using the above examples.

## 2.6 Taxi Procedures
Beirut Ground is responsible for issuing taxi clearances to all aircrafts and guiding them from their stand to the holding point of the runway.

Once an aircraft requests taxi, the controller must issue the shortest and most efficient route to the holding point of the runway.

!!! example
    **Controller**: “MEA229, TAXI VIA LIMA AND ALPHA, HOLD SHORT AT HOLDING POINT HOTEL RUNWAY 21.”

All taxiing aircrafts must be handed-off to Beirut Tower prior to reaching their holding point on the runway.

The maximum taxi speed for all aircrafts is 25 knots on taxiways, and 50 knots on runways

### 2.6.1 Managing Taxiway Conflicts

If the controller notices an upcoming collision conflict between two taxiing aircrafts, a give way instruction may be issued to one of the aircrafts.

!!! example
    **Controller**: “MEA229, GIVE WAY TO THE IRAQI 737 PASSING LEFT TO RIGHT.”

The aircraft is expected to stop and give way to the traffic, and once the taxiway is clear, the pilot shall continue taxiing spontaneously. In the case of a close call conflict, an immediate HOLD POSITION instruction may be given. When using HOLD POSITION, the pilot shall immediately stop in his tracks and wait for further instructions to CONTINUE TAXI.

### 2.6.2 Procedural Taxi
Controllers are not enforced to issue procedural taxi instructions to pilots. It is the pilot’s responsibility to familiarise themselves with the charts before connecting on the airport. But in most cases, procedural taxi instructions will be given out of courtesy when the workload and traffic is low.

!!! example "Examples"
    !!! example ""
        **Controller**: “MEA229, TAXI VIA MIKE AND JULIET, HOLD SHORT OF TAXIWAY LIMA.”

        **Controller**: “MEA229, TURN LEFT AND CONTINUE TAXI VIA LIMA AND ALPHA, HOLD SHORT AT HOLDING POINT HOTEL RUNWAY 21.”

        **Controller**: “MEA313, TAKE THE SECOND LEFT ONTO FOXTROT.”

        **Controller**: “PGT1825, MAKE A LEFT 180 DEGREES VIA JULIET TO BE ON TAXIWAY LIMA.”

The procedural taxi instructions can be constructed using common sense

### 2.6.3 Arrival Taxi
Aircrafts arriving from runway 16 and exiting via taxiways November, Kilo, and Alpha should be granted clearance to cross runway 17 by Beirut Tower. Subsequently, after safely crossing the runway, they should establish contact with Beirut Ground for further instructions or guidance.

Pilots may be instructed to park at their stand of choice, or be assigned a specific stand by the ground controller.

!!! example
    **Controller**: “SDR10DL, BEIRUT GROUND, TAXI VIA KILO, LIMA, TO TERMINAL A, STAND OF CHOICE.”

!!! example
    **Controller**:“UAE953, BEIRUT GROUND, TAXI VIA KILO, LIMA, JULIET, TO TERMINAL A, STAND G20.”

### 2.6.4 Runway Backtracking
Runway backtracking in Beirut is rare. But there may be situations where runway backtracking may be required such as an aircraft that has taken a wrong taxiway. The backtracking instruction must include the vacating point where the aircraft shall finish backtracking and vacate the runway.

!!! example
    **Controller**: “QTR426, BACKTRACK RUNWAY 21, VACATE VIA ECHO.”

!!! example
    **Controller**: “QTR426, ENTER RUNWAY 21 VIA ALPHA, BACKTRACK AND VACATE VIA ECHO.”