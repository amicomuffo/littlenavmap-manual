
##! [Opzioni] (../ images / icons / settings.png "Opzioni") Finestra di dialogo Opzioni {# opzioni-finestra di dialogo}

La maggior parte delle opzioni sono autoesplicative e le descrizioni dei comandi contengono spiegazioni più dettagliate se applicabile.

È possibile verificare immediatamente l'effetto delle modifiche sulla visualizzazione della mappa spostando la finestra di dialogo
`Opzioni` a lato e premendo` Applica`.

Il pulsante "Ripristina predefiniti" ripristina le opzioni di questa finestra di default. Altri settaggi,come la visualizzazione della mappa, le viste della tabella o le posizioni della finestra ancorata non sono interessate. Per ripristinare completamente tutte le impostazioni salvate vedi [Risoluzione dei problemi] (APPENDIX.md # risoluzione dei problemi).

### Avvio {#Avvio}

Permette di personalizzare ciò che deve essere caricato e mostrato all'avvio di _Little Navmap_.

È inoltre possibile configurare la frequenza di controllo e delle reti degli aggiornamenti automatici. Vedere [Verifica aggiornamenti] (UPDATE.md) per ulteriori informazioni.

### Interfaccia utente {# utente-interfaccia}

Dispone di opzioni per le dimensioni del testo nelle finestre di informazione e nel piano di volo, nonché nella tabella dei risultati della ricerca.

Puoi anche cambiare lo stile generale per l'interfaccia grafica dell'utente. Gli stili dell'interfaccia utente contengono una modalità "Notte" che può essere utilizzata per i voli notturni in stanze buie. Puoi anche oscurare la mappa e la visualizzazione del profilo altimetrico.

Non è necessario un riavvio, ma è consigliato dopo aver modificato uno stile.

I colori per gli stili `Fusione` e` Notte` possono essere cambiati modificando i file di configurazione. Vedere [Personalizzare] (CUSTOMIZE.md) per ulteriori informazioni.

Questa scheda contiene anche opzioni per forzare la lingua del programma e le impostazioni locali \ (numero, formato data e ora \) in inglese se non si desidera usare un'interfaccia utente tradotta.

! [Interfaccia utente] (../ images / optionsui.jpg "Interfaccia utente")

_ ** Immagine sopra: ** Scheda `Interfaccia utente` usando lo stile` Notte`._

### Mappa {#map}

Opzioni di personalizzazione relative alla mappa. Permette di impostare la sensibilità del clic, le distanze dello zoom e altro.

### Visualizzazione mappa {# mappa-visualizzazione}

Questa scheda contiene opzioni per  le dimensioni del simbolo e del testo, del piano di volo e  dei colori delle tracce dell'aereo ed altro.

Il lato destro della scheda contiene una struttura ad albero che consente di selezionare le schede di testo che dovrebbero essere mostrate negli aeroporti, velivoli utente e velivoli AI / multiplayer.

! [Visualizzazione mappa] (../ images / optionmapdisplay.jpg "Visualizzazione mappa")

_ ** Immagine sopra: ** Scheda `Visualizzazione mappa`._

### Unità {#unità}

Puoi modificare tutte le unità utilizzate da _Little Navmap_ in questa scheda, tra nautica, imperiale e metrica.
Sono possibili impostazioni miste come metro per l'altitudine e miglia nautiche per  la distanza.

Si noti che tutti i numeri utilizzati nel programma non vengono convertiti quando si cambiano unità. Questo significa che avrai
un buffer di altitudine minima di 1000 metri, dopo aver modificato l'impostazione "Altitudine ed elevazione" da piedi a metro.
Questo vale anche per l'altitudine del piano di volo. Pertanto, non dimenticare di adattare questi numeri dopo aver cambiato unità.


### Aereo del simulatore {# simulatore-aereo}

Permette di cambiare vari aspetti relativamente alla visualizzazione dell'aereo dell'utente. Tutte le impostazioni che determinano una visualizzazione più fluida degli aerei useranno più CPU e possono potenzialmente provocare balbettamenti nel simulatore.

### Cache e file {#cache}

#### Visualizzazione mappa {# cache-mappa-visualizzazione}

Qui è possibile modificare la dimensione dello cache nella RAM e sul disco. Questi cache vengono utilizzati per memorizzare le tessere delle immagini scaricate dalle mappe online come _OpenStreetMap_, _OpenMapSurfer_ o _OpenTopoMap_.

Tutte le tessere dell'immagine scadono dopo due settimane e verranno ricaricate dai servizi online.

Si noti che una riduzione delle dimensioni o la cancellazione dello cache del disco viene eseguita in background e può richiedere del tempo.

Lo cache RAM ha una dimensione minima di 100 MB e una dimensione massima di 2 GB.

Lo cache del disco ha una dimensione minima di 500 MB e una dimensione massima di 8 GB.

#### Profilo di elevazione del piano di volo {# cache-elevazione}

La parte inferiore di questa scheda consente di installare i dati di elevazione scaricabili liberamente [GLOBE - Global Land One-km Base Elevation Project] (https://ngdc.noaa.gov/mgg/topo/globe.html).

Scarica l'archivio ZIP dal link nella finestra di dialogo ed estrailo. Seleziona la directory estratta usando `Seleziona directory GLOBE ...` in modo che punti ai file da `a10g` a` p10g`. L'avviso nella finestra di dialogo mostrerà un errore se il percorso non è valido.

! [GLOBE Dati di elevazione] (../ images / optionelevation.jpg "GLOBE Elevation Data")

_ ** Immagine sopra: ** Scheda `Cache e file` con i dati di elevazione GLOBE correttamente selezionati ._

### Piano di volo {# piano di volo}

Qui puoi impostare le preferenze per il calcolo del piano di volo o adeguare la regola empirica per la visualizzazione del top of descend.

### Meteo {#meteo}
È possibile selezionare le varie sorgenti meteorologiche che dovrebbero essere visualizzate nella finestra ancorata "Informazioni" o nella mappa suggerimenti.

Il genere meteorologico `Flight Simulator` visualizzerà il meteo dalla connessione FSX o P3D o dal file meteorologico X-Planes` METAR.rwx`.

_Active Sky_ può essere selezionato solo se _Active Sky Next_, _AS16_ o _Active Sky for Prepar3D v4_ sono installati o il file meteorologico è dierttamente selezionato. La selezione diretta del file meteorologico _Active Sky_ può essere utile se si esegue un'installazione in rete. Utilizzare le condivisioni di Windows o un servizio cloud per ottenere l'accesso al file sul computer remoto.

Gli URL del tempo NOAA e VATSIM possono essere modificati se si desidera utilizzare un'altra fonte o i servizi cambiano gli URL.

I pulsanti di prova per i servizi meteorologici online possono anche essere utilizzati per scoprire se _Little Navmap_ può connettersi a Internet. Controlla le impostazioni del firewall se falliscono.

! [Opzioni meteo] (../ images / optionsweather.jpg "Opzioni meteo")

_ ** Immagine sopra: ** Scheda `Meteo` con file meteo Active Sky selezionato manualmente su una condivisione di rete._

### Database delle librerie di scenari {# scenerio-libreria-database}

Consente di configurare il caricamento del database della libreria degli scenari.

Si noti che questi percorsi si applicano a tutti i simulatori di volo, FSX, P3D e X-Plane.

È necessario ricaricare il database degli scenari per consentire alle modifiche di
avere effetto.


#### Seleziona Percorsi da escludere dal caricamento {# scenery-library-database_exclude}

Tutte le directory, incluse quelle secondarie in questo elenco, verranno omesse durante il caricamento dello scenario
libreria nel database _Little Navmap_. È inoltre possibile utilizzare questo elenco per accelerare il caricamento del database
se si escludono directory che non contengono aeroporti o navaidi (classe di terra, dati di elevazione e altri).

#### Seleziona Percorsi per escludere il riconoscimento del componente aggiuntivo {# scenery-library-database_exclude-add-on}

Tutti i dati di scenario che si trovano al di fuori della directory `Scenery` del simulatore di volo di base sono considerati un componente aggiuntivo e lo saranno
evidenziato sulla mappa e considerato anche durante la ricerca di componenti aggiuntivi.

È possibile utilizzare questo elenco per modificare questo comportamento.

I componenti aggiuntivi, come _Orbx FTX Vector_ o _fsAerodata_, aggiungono file di scenari che correggono determinati aspetti
di aeroporti come elevazione, varianza magnetica o altro. Tutti questi aeroporti saranno riconosciuti come aeroporti aggiuntivi
poiché tutti i loro file non sono memorizzati nella directory `Scenery` del simulatore di volo di base.

Inserire la directory corrispondente in questo elenco per evitare l'evidenziazione indesiderata di questi aeroporti come componenti aggiuntivi.

! [Database di librerie di scenari] (../ images / optionscenery.jpg "Database di librerie di scenari")

_ ** Immagine sopra: ** Scheda `Database libreria scenario` con tre directory escluse dal caricamento e due directory escluse dal riconoscimento del componente aggiuntivo ._

#### Esempi

A condizione che il simulatore sia installato in `C: \ Games \ FSX`.

##### ORBX Vector

Escludere le directory seguenti dal riconoscimento dei componenti aggiuntivi. Non escluderli dal caricamento poiché vedrai altitudini aeroportuali errate.

* `C:\Games\FSX\ORBX\FTX_VECTOR\FTX_VECTOR_AEC`
* `C:\Games\FSX\ORBX\FTX_VECTOR\FTX_VECTOR_APT`


##### Flight1 Ultimate Terrain Europe


#### Esempi

A condizione che il simulatore sia installato in `C: \ Games \ FSX`.

##### ORBX Vector

Escludere le directory seguenti dal riconoscimento dei componenti aggiuntivi. Non escluderli dal caricamento poiché vedrai altitudini aeroportuali errate.

* `C: \ Games \ FSX \ ORBX \ FTX_VECTOR \ FTX_VECTOR_AEC`
* `C: \ Games \ FSX \ ORBX \ FTX_VECTOR \ FTX_VECTOR_APT`


##### Flight1 Ultimate Terrain Europe

Escludere queste directory dal caricamento per accelerare il processo:

* `C:\Games\FSX\Scenery\UtEurAirports`
* `C:\Games\FSX\Scenery\UtEurGP`
* `C:\Games\FSX\Scenery\UtEurLights`
* `C:\Games\FSX\Scenery\UtEurRail`
* `C:\Games\FSX\Scenery\UtEurStream`
* `C:\Games\FSX\Scenery\UtEurWater`

##### ORBX Regions

Escludere queste directory dal caricamento:

* `C:\Games\FSX\ORBX\FTX_NZ\FTX_NZSI_07_MESH`
* `C:\Games\FSX\ORBX\FTX_NA\FTX_NA_CRM07_MESH`
* `C:\Games\FSX\ORBX\FTX_NA\FTX_NA_NRM07_MESH`
* `C:\Games\FSX\ORBX\FTX_NA\FTX_NA_PNW07_MESH`
* `C:\Games\FSX\ORBX\FTX_NA\FTX_NA_PFJ07_MESH`
