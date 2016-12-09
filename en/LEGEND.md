# Little Navmap Legend {#little-navmap-legend}

![Little Navmap](../images/littlenavmap.svg "Little Navmap")

All speeds are in knots, distances in nautical miles, altitude in feet. Heading and course are suffixed with °T for true course or °M for magnetic course.

### Map Marks {#map-marks}

| ![Home](../images/legend/home.png) | Center of the home position. |
| --- | --- |
| ![Mark](../images/legend/mark.png) | Center point that will be used for distance searches. |
| ![Flight Plan](../images/legend/route_leg.png) | Flight plan with distance, direction and magnetic course at each leg. |
| ![Flight Plan Departure Position](../images/legend/route_start.png) | Flight plan departure position on airport. Either parking, fuel box, helipad, water or runway. |
| ![Aircraft](../images/legend/aircraft.png)     ![Aircraft](../images/legend/aircraft_text.png) | Current user aircraft position if connected to the flight simulator. Labels include registration number, airline \(if available\), flight number \(if available\), indicated speed, ground speed, magnetic heading, altitude, climb/sink arrow and wind magnetic heading and speed. |
| ![Aircraft](../images/legend/aircraft_ground.png) | User aircraft gray outline on ground. |
| ![Trail](../images/legend/aircraft_track.png) | User aircraft trail if connected to the flight simulator. |
| ![Range](../images/legend/range_rings.png) | Range rings labeled with distance. |
| ![Range VOR](../images/legend/range_vor.png)    ![Range NDB](../images/legend/range_ndb.png) | VOR or NDB range rings labeled with ident and frequency. Color indicates Navaid type. |
| ![Distance GC](../images/legend/distance_gc.png) | [Great circle](https://en.wikipedia.org/wiki/Great-circle_distance) distance and course measurement line indicating length and true heading at start and destination \(usually equal for small distances\). For shorter distances length is also shown in feet. |
| ![Distance Rhumb](../images/legend/distance_rhumb.png) | [Rhumb line](https://en.wikipedia.org/wiki/Rhumb_line) of equal bearing distance measurement indicating distance and true heading. Rhumb lines are used to approach a VOR or NDB or travel along airways. For shorter distances length is also shown in feet. |
| ![Distance VOR](../images/legend/distance_vor.png) | Measurement lines starting from an airport or navaid have the same color and additional ident and frequency labels. Course for rhumb lines will be shown in magnetic if the navaid has a magnetic variation attribute. |
| ![Search Hightlight](../images/legend/highlight_search.png) | A highlighted airport or navaid selected in the search result table. |
| ![Flight Plan Hightlight](../images/legend/highlight_route.png) | A highlighted airport or navaid selected in the flight plan table. |

### Airports {#airports}

Airports having control towers are shown in dark blue others in magenta. Add-on airport names and idents are shown italic and underlined. Airports that are part of the flight plan have a light yellow text background.

The symbol is shown smaller if an airport has no runways. This is the case for some add-on airports that use another technique like photoscenery to display runways.

| ![Large Airport](../images/legend/airport_tower_8000.png)    ![Large Airport](../images/legend/airport_8000.png) | Airports with hard surface runways longer than 8,000 ft. All runways longer than 4,000 ft are shown. Only for lower zoom distances. |
| --- | --- |
| ![Airport with Tower](../images/legend/airport_tower.png)    ![Airport](../images/legend/airport.png) | Airports with hard surface runways. White line shows heading of longest runway. |
| ![Airport with soft runways and Tower](../images/legend/airport_tower_soft.png)    ![Airport with soft Runways](../images/legend/airport_soft.png) | Airports with soft surface runways. |
| ![Airport Empty](../images/legend/airport_empty.png)    ![Airport Empty Soft](../images/legend/airport_empty_soft.png) | Empty airports shown in gray. No taxiways, no parking spots and no aprons. |
| ![Seaplane Base with Tower](../images/legend/airport_tower_water.png)    ![Seaplane Base](../images/legend/airport_water.png) | Seaplane base having only water runways. |
| ![Military Airport with Tower](../images/legend/airport_tower_mil.png)    ![Military Airport](../images/legend/airport_mil.png) | Military airport. |
| ![Heliport](../images/legend/heliport.png) | Heliport having only helipads and no runways. |
| ![Closed Airport with Tower](../images/legend/airport_tower_closed.png)    ![Closed Airport](../images/legend/airport_closed.png) | Abandoned airport. All runways are closed. |
| ![Airport with Fuel](../images/legend/airport_tower_fuel.png)    ![Airport with soft Runways and Fuel](../images/legend/airport_soft_fuel.png) | Airports that have fuel available. |
| ![Airport Text](../images/legend/airport_text.png) | Airport label showing \(if available\): Name, ident, control tower \(CT - 119.550\) and weather service frequencies \(ATIS 127.150 or AWOS/ASOS\), elevation \(152 ft\), availability of lighted runways \(L\), longest runway in ft \* 100 \(7400 ft\) and Unicom frequency \(122.95\). |

### Navaids {#navaids}

Navaids that are part of the flight plan have a light yellow text background.

| ![VORDME](../images/legend/vordme_small.png)    ![VORDME](../images/legend/vordme_large.png) | VOR DME including ident, type \(High, Low or Terminal\) and frequency. Compass rose shows magnetic variation on lower zoom distances. |
| --- | --- |
| ![VOR](../images/legend/vor_small.png)    ![VOR](../images/legend/vor_large.png) | VOR including ident, type and frequency. |
| ![DME](../images/legend/dme.png) | DME including ident, type and frequency. |
| ![NDB](../images/legend/ndb_small.png)    ![NDB](../images/legend/ndb_large.png) | NDB including ident, type \(HH, H, MH or CL - compass locator\) and frequency. |
| ![Waypoint](../images/legend/waypoint.png) | Waypoint with name. |
| ![Waypoint](../images/legend/waypoint_invalid.png) | Invalid airport, waypoint, VOR or NDB that is part of the flight plan but could not be found in the Scenery Database. |
| ![Marker](../images/legend/marker_outer.png)     ![Marker](../images/legend/marker_middle.png)     ![Marker](../images/legend/marker_inner.png) | Marker with type and heading indicated by lens shape. |
| ![Jet Airway](../images/legend/airway_jet.png) | Jet airway with label showing name, type \(Jet or Both\) and minimum altitude. Text depends on zoom distance. |
| ![Victor Airway](../images/legend/airway_victor.png) | Victor airway with label showing name, type \(Victor or Both\) and minimum altitude. Text depends on zoom distance. |

| ![ILS](../images/legend/ils_gs_small.png)      ![ILS](../images/legend/ils_gs.png) ILS with glideslope. Label shows ident, frequency, magnetic heading, glideslope pitch and DME indication if available. |
| --- |
| ![ILS](../images/legend/ils_small.png)      ![ILS](../images/legend/ils_large.png) Localizer. Label shows ident, frequency, magnetic heading and DME indication if available. |

### Airport Diagram {#airport-diagram}

Runway, taxiway, helipad and apron colors indicate surface type. White is used for an unknown or invalid surface type given by an add-on developer.

| ![Runway](../images/legend/runway.png) | Runway with length, width, light indicator \(L\) and surface type. |
| --- | --- |
| ![Runway End](../images/legend/runway_end.png) | Runway end with ident and magnetic heading. |
| ![Runway Threshold](../images/legend/runway_threshold.png) | Displaced threshold. Do not use for landing. |
| ![Runway Overrun](../images/legend/runway_overrun.png) | Overrun area. Do not use for taxi, takeoff or landing. |
| ![Runway Blastpad](../images/legend/runway_blastpad.png) | Blast pad. Do not use for taxi, takeoff or landing. |
| ![Taxiway](../images/legend/taxiway.png) | Taxiway with name. |
| ![Closed Taxiway](../images/legend/closedtaxi.png) | Closed taxiway. |
| ![Taxiway](../images/legend/apron_transparent.png) | Semi transparent dotted aprons and taxiways indicate that no surface is drawn. It might use a photo texture or simply the default background. |
| ![Tower](../images/legend/tower_active.png)    ![Tower](../images/legend/tower_inactive.png) | Tower. Red if a tower frequency is available. Otherwise just view position. |
| ![Fuel](../images/legend/parking_fuel.png) | Fuel |
| ![Parking](../images/legend/parking_ga_ramp.png) | GA ramp with parking number and heading tick mark. |
| ![Parking](../images/legend/parking_gate_no_jetway.png)    ![Parking](../images/legend/parking_gate.png) | Gate with number and heading tick mark. Second ring indicates availability of jetway. |
| ![Parking](../images/legend/parking_ramp_cargo.png) | Cargo ramp |
| ![Parking](../images/legend/parking_mil.png) | Military combat parking or cargo ramp. |
| ![Helipad](../images/legend/helipad.png) | Helipad |

### Elevation Profile Legend {#elevation-profile-legend}

| ![Profile Start](../images/legend/profile_start.png)    ![Profile End](../images/legend/profile_end.png) | Ground with start and destination airport elevation. |
| --- | --- |
| ![Profile Safe Alt](../images/legend/profile_safe_alt.png) | Minimum safe altitude for flight plan. |
| ![Flight Plan Profile](../images/legend/profile_route.png) | Flight plan altitude. |
| ![Aircraft](../images/legend/profile_aircraft.png) | User aircraft if connected to the simulator. Labels are: Altitude, climb/sink arrow, distance flown and distance to destination. |
| ![Trail](../images/legend/profile_track.png) | User aircraft trail if connected to the flight simulator. |

Last update 2016-10-12
