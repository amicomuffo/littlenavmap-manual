## Online Networks {#online-networks}

The online network functionality allows to connect to [VATSIM](https://www.vatsim.net), [IVAO](https://ivao.aero), [PilotEdge](https://www.pilotedge.net/) or other online networks which publish `whazzup.txt` files. This covers display of information for centers, clients and servers on the map.

Network specific information like user names, active centers/towers, frequencies, flight plans and much more are displayed world wide without limits like distance to the user aircraft.

Access to online networks can be enabled and configured in the dialog `Options` on tab [Online Flying](OPTIONS.md#online-flying). Predefined options for the well known networks are available as well as freely configurable ones.

**Online network related functionality can be found in the following places:**

* Search dock window, tabs `Online Clients`, `Online Centers` and `Online Server`.
* Information dock window, tabs `Online Clients` and `Online Centers`.
* Options dialog, `Online Flying`.

### Simulator and Online Aircraft Duplicates {#online-networks-duplicates}

_Little Navmap_ fetches data from online networks using an interval of three minutes depending on settings and network.

The program also fetches AI or multiplayer aircraft from the simulator which are updated about two times a second. These aircraft are injected into the simulator by the various online clients so they are visible within the simulator.

Therefore, the user aircraft and other client aircraft can appear duplicated on the map.

_Little Navmap_ tries to remove these duplicates by matching the aircraft registration (simulator) and the client callsign (online network). Aircraft can appear duplicated if this information is not available which is the case for X-Plane. Refer to the configuration of your online network tool how to add this information.

### Map Display {#online-networks-mapdisplay}

#### Clients {#online-networks-clients}

Online network clients or their aircraft are displayed on the map using the ![Online in Flight](../images/icons/aircraft_online.png) symbol. This includes simulator aircraft that were recognized as online network clients.

The user aircraft is always displayed using the yellow ![Small GA](../images/icons/aircraft_small_user.png)  or a similar symbol depending on aircraft type and simulator. Use the `Show in Search` map context menu item to see your own aircraft in the list of online clients.

Information for online aircraft is shown on the tab `Online Clients` in the [Information Dock Window](INFO.md).

All other functionality like context menu, double-click, tooltips, map highlights and other are the same as for the other aircraft.

See [Aircraft and Ships](LEGEND.md#vehicles) in the legend for all symbols.

![Online Network Aircraft](../images/online_aircraft.jpg "Online Network Aircraft")

_**Picture above:** Online network clients/aircraft in search tab, map, tooltip and information window._

#### Centers {#online-networks-centers}

Online centers are displayed as circular airspaces in _Little Navmap_ and provide the same functionality as the other airspaces (tooltips, information and more). They can be enabled  separately from the other airspaces by selecting `Online` as airspace source ([Airspace Source](MENUS.md#airspace-source))

**Note that the circles do not represent the real airspaces and are only used to indicate the presence of an active center, tower, ground or other position.** See next chapter how to assign airspace boundaries to a center.

Detailed information for online centers/airspaces is shown on the tab `Online Centers` in the [Information Dock Window](INFO.md).

The following types are available and can be enabled in the drop down menus on the airspace toolbar or sub menu [Airspaces](MENUS.md#airspaces):

* **Observer:** Circle size is taken from the `Visual Range` value of the center.
* **Flight Information (Center):** Uses `Visual Range`.
* **Delivery (Clearance):** Uses `Visual Range`.
* **Ground:** Shows a circle with a diameter of 10 nm.
* **Tower:** 20 nm circle.
* **Approach:** 40 nm circle.
* **ACC (Center):** Uses `Visual Range`.
* **Departure:** Uses `Visual Range`.

The size of the circle shapes can be changed in the configuration file. See [Online Network Center](CUSTOMIZE.md#customize-online-center).

You can also assign centers to a boundary shape using imported OpenAir airspaces from the user airspace database. See [Online Airspaces](SCENERY.md#load-scenery-library-online-airspaces) for more information about this.

![Customize Online Network Centers](../images/online_center.jpg "Online Network Center")

_**Picture above:** Online network center/ATC in search tab, map, tooltip and information window._

### Online Network Client Search {#search-client}
### Online Network Center Search {#search-center}

The functionality of the search filters in these two tabs and the result tables are similar to the airport and navaid search. See [Search Dock Window](SEARCH.md) for information about search filters, buttons and context menu items.

### Online Server Search {#search-server}

Displays all online servers in a table and has no search functionality. You can use the context menu to copy parts of the result table like the IP address.

