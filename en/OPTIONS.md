## ![Options](../images/icons/settings.png "Options") Options Dialog {#options-dialog}

Most options are self explaining and tooltips contain more detailed explanations if applicable.

Tip: You can immediately check the effect of your changes on the map display by moving the dialog
`Options` to the side and pressing `Apply`.

The button `Restore Defaults` only restores the options of this dialog back to default. Other
settings like map display, table views or dock window positions are not affected. To reset all
saved settings completely see [Troubleshoot](APPENDIX.md#troubleshoot).

### Startup {#starup}

Allows to customize what should be loaded and shown on starup of _Little Navmap_.

### User Interface {#user-interface}

Has options vor text sizes in information windows and flight plan as well as the search result table.

You can also change the overall style for the graphical user interface. The user interface styles
contain a `Night` mode that can be used for night flights in dark rooms. You can also dim the map and
elevation profile display.

Note that a restart is not needed but recommended after changing a style.

### Map {#map}

Has map related customization options. Allows to set the click sensitvity, zoom distances and more.

### Map Display {#map-display}

This tab contains options for symbol and text sizes, flight plan and aircraft trail colors and more.

The right side of the tab contains a tree that allows to select the text labels that should be shown at
airports, user aircraft and AI/multiplayer aircraft.

### Units {#units}

You can change all units that are used by _Little Navmap_ on this tab between nautical, imperial and metric.
Mixed settings like meter for altitude and nautical miles for distance are possible.

Note that any numbers used in the program are not converted when changing units. That means that you will
have a minimum altitude buffer of 1000 meter after changing the setting `Altitude and Elevation' from feet to meter.
This also applies to flight plan altitude. Therefore, do not forget to adapt these numbers after changing units.

### Simulator Aircraft {#simulator-aircraft}

Allows to change various aspects around the display of the user aircraft.
All settings resulting in a more fluid aircraft display will use more CPU and can potentially induce stutters
in the simulator.

### Cache {#cache}

Here you can change the cache size in RAM and on disk. These caches are used to store the downloaded images tiles
from the online maps like the _OpenStreetMap_, _OpenMapSurfer_  or _OpenTopoMap_.

All image tiles expire after two weeks.

Note that a reduction of size or erasing the disk cache is done in background and can take a while.

### Flight Plan {#flight-plan}

Here you can set preferences for flight plan calculation or adjust the rule of thumb for the top of descent display.

### Weather {#weather}

You can select the various weather sources that should be shown in the `Information` dock window or in the map
tooltips.

_Active Sky_ can only be selected if _Active Sky Next_ or _AS16_ is installed.

The URLs of the NOAA and VATSIM weather can be modified if you like to use another source or the services
change the URLs.

### Scenery Library Database {#scenery-library-database}

Allows to configure the loading of the scenery library database.

You have to reload the scenery database in order for the changes to
take effect.

#### `Select Paths to exclude from loading`

All directories that are added to this list are excluded from loading. You can use this to speed up the loading
process by adding directories that contain only elevation data for example.

#### `Select Paths to exclude add-on recognition`

All scenery data that is found outside of the base flight simulator `Scenery` directory is considered an add-on and will be
highlighted on the map and considered during search for add-on.

Some add-ons, like _Orbx FTX Vector_ or _fsAerodata_ add scenery files that correct certain aspects
of airports like elevation, magnetic variance or others. All these airports will be recognized as add-on airports
since all their files are not stored in the base flight simulator `Scenery` directory.

To avoid unwanted highlighting of these airports as add-ons on the map add the corrponding directory to this list.