
## Menu e barre degli strumenti {# menu-e-barre degli strumenti}

Questo capitolo descrive tutte le voci di menu di _Little Navmap_. Troverai la maggior parte di questa funzionalità anche sulle barre degli strumenti che non sono descritte separatamente. Le combinazioni di tasti sono visibili nelle voci di menu e non sono elencate in questo manuale.

! [Menu e barre degli strumenti di Navmap] (../ images / menutoolbar.jpg "Menu e barre degli strumenti di Navmap")

_ ** Immagine sopra: ** Menu e barre degli strumenti ancorate nelle posizioni predefinite._

### Menu File {# file-menu}

####! [Nuovo piano di volo] (../ images / icons / filenew.png "Nuovo piano di volo") Nuovo piano di volo {# new-flight-plan}

Cancella l'attuale piano di volo.

Devi usare il [Menu contestuale vista tabella risultati ricerca] (SEARCH.md # menu-contesto-ricerca-risultati-tabella-visualizzazione), il [Menu contestuale mappa] (MAPDISPLAY.md # menu-contesto-mappa) o il menu Finestra di dialogo [Descrizione percorso piano di volo] (ROUTEDESCR.md) per creare un piano di volo.

####! [Apri piano di volo] (../ images / icons / fileopen.png "Apri piano di volo") Apri piano di volo {# open-flight-plan}

Apre un PLN FSX, un PLN FS9, un FMS X-Plane o un file del piano di volo FLP. Il tipo di file è determinato dal contenuto e non dall'estensione del file. Vedere [Formati del piano di volo] (FLIGHTPLANFMT.md) per ulteriori informazioni.

Un file del piano di volo aperto verrà ricaricato all'avvio \ (ricaricare e centrare possono essere disattivati nella finestra di dialogo `Opzioni` nella scheda` Avvio` e `Interfaccia utente`).

Le informazioni sulla procedura e la velocità al suolo verranno aggiunte al piano di volo se un file PLN viene salvato da _Little Navmap_. Le informazioni aggiuntive verranno ignorate da FSX o P3D ma consentono di ricaricare tutte le informazioni con _Little Navmap_.

####! [Aggiungi piano di volo] (../ images / icons / fileappend.png "Aggiungi piano di volo") Aggiungi piano di volo {# aggiungi-volo-piano}

Aggiunge partenza, destinazione e tutti i waypoint al piano di volo corrente.

L'uso di "Aggiungi piano di volo" consente di caricare o unire piani di volo completi o frammenti di piani di volo in un nuovo piano. Tutti i waypoint vengono aggiunti alla fine del piano di volo corrente. Quindi è possibile utilizzare le voci del menu contestuale `Elimina tratti selezionati` e` Sposta tratti selezionati su / giù` per disporre i waypoint e gli aeroporti come richiesto. Vedi [Menu contestuale vista tabella piano di volo] (FLIGHTPLAN.md # menu contestuale vista-piano-tabella-volo).

Tutte le procedure di arrivo verranno rimosse quando si aggiunge un piano di volo.

####! [Salva piano di volo] (../ images / icons / filesave.png "Salva piano di volo") Salva piano di volo {# salva-volo-piano}

####! [Salva piano di volo come PLN] (../ images / icons / filesaveas.png "Salva piano di volo come PLN") Salva piano di volo come PLN {# save-flight-plan-as}

Salva il piano di volo in un file PLN FSX / P3D \ (formato XML \). Questo formato con annotazioni consente di salvare tutti gli attributi del piano di volo di * Little Navmap *.

"Salva piano di volo come PLN" modifica il tipo e il nome del file corrente in * Little Navmap *, il che significa che tutti gli ulteriori salvataggi andranno nel nuovo file PLN.

Si consiglia di salvare tutti i piani di volo in questo formato per conservare tutte le informazioni di un piano. Anche quando si utilizza il formato FMS limitato per X-Plane. Vedere [Formati del piano di volo] (FLIGHTPLANFMT.md) per ulteriori informazioni.

_Little Navmap_ consentirà la creazione di piani di volo che possono essere utili come frammenti di piani di volo, ma che sono inutilizzabili dal simulatore di volo. Ciò si verifica se un piano di volo non ha un aeroporto di partenza o di destinazione. Una finestra di avviso verrà visualizzata quando si salva un piano di volo incompleto.

Verrà inoltre visualizzata una finestra di avviso se l'aeroporto di partenza ha posizioni di parcheggio ma nessuna è assegnata nel piano di volo.

Le procedure verranno salvate come annotazione nel file del piano di volo se il piano di volo ne contiene. Ciò non causa problemi ai simulatori e alla maggior parte degli altri programmi. Utilizzare [Esporta piano di volo pulito] (MENUS.md # exporta-pulito-volo-piano) se un programma ha problemi a leggere i file PLN salvati da _Little Navmap_.

Si noti che i waypoint di una procedura non vengono salvati con il piano di volo. Questo non è supportato da FSX o P3D. Utilizzare il GPS, FMC o altri modi per selezionare una procedura sul proprio velivolo.

Anche la velocità di avanzamento impostata viene salvata con il piano di volo.

####! [Salva piano di volo come X-Plane FMS 11] (../ images / icons / saveasfms.png "Salva piano di volo come X-Plane FMS 11") Salva piano di volo come X-Plane FMS 11 {# Salva-volo-piano-come-fms11}

Salva il piano di volo utilizzando il nuovo formato X-Plane FMS 11.

** Questo formato può essere utilizzato solo in X-Plane 11.10 e versioni successive. Non tentare di caricarlo nell'FMS o GPS dell'X-Plane 11.05. Potrebbe causare l'arresto anomalo del simulatore. **

Una finestra di avviso verrà mostrata con sopra l'avviso durante il salvataggio.

Vedere [Formati del piano di volo] (FLIGHTPLANFMT.md) per ulteriori informazioni sulle limitazioni.

Questa funzione modifica il tipo e il nome del file corrente, il che significa che tutti gli altri salvataggi andranno nel nuovo file FMS e il file verrà ricaricato al prossimo avvio.

Conservare i file FMS nella directory "Output / Piani FMS" all'interno della directory X-Plane se si desidera utilizzare il piano di volo in X-Plane GPS, G1000 o FMS.

####! [Salva piano di volo FLP] (../ images / icons / saveasflp.png "Salva piano di volo FLP") Salva piano di volo come FLP {# salva-volo-piano-come-flp}

Esporta l'attuale piano di volo come file FLP utilizzabile da X-Plane FMS, Aerosoft Airbus e altri aeromobili aggiuntivi. Questo formato è limitato, quindi viene visualizzata una finestra di dialogo se vengono rilevate funzionalità non supportate nel piano di volo corrente.

Vedere [Formati del piano di volo] (FLIGHTPLANFMT.md) per ulteriori informazioni sulle limitazioni.

Questa funzione modifica il tipo e il nome del file corrente, il che significa che tutti gli altri salvataggi andranno nel nuovo file FLP e il file verrà ricaricato al prossimo avvio.

Memorizzare i file FLP nella directory "Output / FMS piani" all'interno della directory X-Plane se si desidera caricarli nell'FMS.

####! [Esporta come PLN pulito] (../ images / icons / filesaveclean.png "Esporta come PLN pulito") Esporta come PLN pulito {# esporta-pulito-volo-piano}

Salva un piano di volo senza alcuna procedura o velocizza le annotazioni se i programmi hanno problemi a leggere i file PLN salvati da _Little Navmap_. Questo raramente è necessario.

Come qualsiasi altra funzione di esportazione, questo non cambia il nome e il tipo di file corrente. Ulteriori salvataggi continueranno a utilizzare lo stesso nome e formato di file di prima.

Vedi anche [Formati del piano di volo] (FLIGHTPLANFMT.md).

####! [Esporta piano di volo come X-Plane FMS 3] (../ images / icons / saveasfms.png "Esporta piano di volo come X-Plane FMS 3") Esporta piano di volo come X-Plane FMS 3 {# esporta-volo-piano-come-fms3}

Salva il piano di volo utilizzando il vecchio formato X-Plane FMS 3 che è limitato, ma può essere caricato da X-Plane 10 e X-Plane 11.05. Viene visualizzata una finestra di avviso, se vengono rilevate funzionalità non supportate nel piano di volo corrente.

Vedere [Formati del piano di volo] (FLIGHTPLANFMT.md) per ulteriori informazioni sulle limitazioni.

Questa funzione di esportazione non modifica il nome e il tipo del file corrente. Ulteriori salvataggi utilizzeranno comunque lo stesso nome e formato di file di prima.

Conservare i file FMS nella directory "Output / Piani FMS" all'interno della directory X-Plane se si desidera utilizzare il piano di volo in X-Plane GPS o FMS.

#### Esporta sottomenu {# esporta-sottomenu}

Vedere [Formati del piano di volo] (FLIGHTPLANFMT.md) per informazioni più dettagliate sui formati di esportazione disponibili.

Le funzioni di esportazione non cambiano il nome e il tipo del file corrente. Ulteriori salvataggi utilizzeranno comunque lo stesso nome e formato di file di prima.

##### Esporta piano di volo in FPL per Reality XP GNS {# salva-volo-piano-come-rxpgns}

Salva il piano di volo come file FPL utilizzabile da _Reality XP GNS 530W / 430W V2_.

Le procedure oi rispettivi punti di passaggio non sono inclusi nel file esportato.

La directory predefinita per salvare i piani di volo per le unità GNS è
`C: \ ProgramData \ Garmin \ GNS Trainer Data \ GNS \ FPL`
per tutti i simulatori. La directory verrà creata automaticamente da _Little Navmap_ alla prima esportazione, se non esiste.

Vedi anche [Note sui formati Garmin GFP e FPL] (FLIGHTPLANFMT.md # garmin-notes).

##### Esporta piano di volo come GFP per Reality XP GTN {# salva-volo-piano-come-rxpgtn}

Salva il piano di volo come file GFP utilizzabile dal _Reality XP GTN 750/650 Touch_. Questo formato consente di salvare procedure e vie aeree.

Vedere anche [Note sui formati Garmin GFP e FPL] (FLIGHTPLANFMT.md # garmin-notes) per informazioni sui percorsi e altre osservazioni.

##### Esporta piano di volo come Garmin GTN GFP {# salva-volo-piano-come-gfp}

Esporta il piano di volo in formato GFP utilizzato da _Flight1 GTN 650 / 750_.

Le procedure oi rispettivi punti di passaggio non sono inclusi nel file esportato.

Vedere [Formati del piano di volo] (FLIGHTPLANFMT.md # flight-plan-format-gfp) per ulteriori informazioni su questo formato di esportazione e su come aggirare i waypoint bloccati.

##### Esporta piano di volo come PMDG RTE {# esporta-volo-piano-come-rte}

Esporta il piano di volo corrente come file RTE PMDG.


Le procedure oi rispettivi punti di passaggio non sono inclusi nel file esportato.

##### Esporta piano di volo come TXT {# esporta-volo-piano-come-txt}

Esporta l'attuale piano di volo come file TXT utilizzabile dagli aerei JARDesign o Rotate Simulation

Né le procedure né i rispettivi waypoint sono inclusi nel file esportato.

##### Esporta piano di volo come Majestic Dash FPR {# esporta-volo-piano-come-fpr}

Esporta l'attuale piano di volo per Majestic Software MJC8 Q400. Si noti che l'esportazione è attualmente limitata a un elenco di waypoint.

Il piano di volo deve essere salvato in `YOURSIMULATOR \ SimObjects \ Airplanes \ mjc8q400 \ nav \ route`.

##### Esporta piano di volo come IXEG FPL {# esporta-volo-piano-come-fpl}

Esporta l'attuale piano di volo come file FPL utilizzabile dal classico IXEG Boeing 737.

SID, STAR o procedure di avvicinamento non vengono esportati.

Il file deve essere salvato in `XPLANE \ Aircraft \ X-Aviation \ IXEG 737 Classic \ coroutes`. Potrebbe essere necessario creare la directory manualmente se non esiste.

##### Esporta piano di volo in corte.in per Flight Factor Airbus {# esporta-volo-piano-come-fpl}

Aggiunge il piano di volo a un file di rotte di compagnia `corte.in` nuovo o già presente per l'aereo Airbus Flight Factor.
Il file verrà creato automaticamente se non esiste. In caso contrario, il piano di volo verrà aggiunto al file. Devi rimuovere manualmente il piano di volo dal file `corte.in` con un semplice editor di testo se vuoi sbarazzartene.

La posizione del file dipende dal tipo di aeromobile.

##### Esporta piano di volo come GPX {# esporta-volo-piano-come-gpx}

Esporta l'attuale piano di volo in un file di formato di scambio GPS che può essere letto da Google Earth e dalla maggior parte delle altre applicazioni GIS.

Il piano di volo viene esportato come rotta e la rotta dell'aeromobile in volo come traccia includendo il tempo e l'altitudine del simulatore.

Il percorso ha un'altitudine di partenza e di destinazione e un'altitudine di crociera impostata per tutti i waypoint. I waypoint di tutte le procedure sono inclusi nel file esportato. Si noti che i waypoint non consentiranno di riprodurre tutte le parti di una procedura come le prese o le svolte della procedura.

** Non dimenticare di cancellare la pista dell'aeromobile \ ([Cancella la traccia dell'aereo] (MENUS.md # cancella-aereo-traccia) \) prima del volo, per evitare i vecchi segmenti di pista nel file GPX esportato. Oppure, disabilitare il ricaricamento del percorso nella finestra di dialogo delle opzioni sulla pagina ** `Avvio` **. **

####! [Aggiungi Google Earth KML] (../ images / icons / kmlfileopen.png "Aggiungi Google Earth KML") Aggiungi Google Earth KML {# aggiungi-google-earth-kml}

Consente l'aggiunta di uno o più file KML o KMZ di Google Earth alla visualizzazione della mappa. Tutti i file KML o KMZ aggiunti verranno ricaricati all'avvio. Ricarica e centratura possono essere disattivate ​​nella finestra di dialogo `Opzioni` nella scheda` Avvio` e `Interfaccia utente`.

A causa della varietà di file KML, non è garantito che tutti i file vengano visualizzati correttamente sulla mappa.

####! [Cancella KML di Google Earth dalla mappa] (../ images / icons / cancel.png "Cancella KML di Google Earth dalla mappa") Cancella KML di Google Earth dalla mappa {# cancella-google-earth-kml-dalla -carta geografica}

Rimuove tutti i file KML caricati dalla mappa.

####! [Offline] (../ images / icons / offline.png "Offline") Lavora offline {# lavora-offline}

Interrompe il caricamento dei dati della mappa da Internet. Ciò influisce su _OpenStreetMap_, _OpenTopoMap_ e su tutti gli altri temi delle mappe online, nonché i dati di elevazione.
Un'indicazione rossa "Offline" viene visualizzata nella barra di stato se questa modalità è abilitata.

È necessario riavviare l'applicazione dopo essere tornati online.

###! [Salva mappa come immagine] (../ images / icons / mapsaveasimage.png "Salva mappa come immagine") Salva mappa come immagine {# salva-mappa-come-immagine}

Salva la vista della mappa corrente come file immagine. I formati consentiti sono JPEG, PNG e BMP.

###! [Stampa mappa] (../ images / icons / printmap.png "Stampa mappa") Stampa mappa {# stampa-mappa}

Consente di stampare la vista della mappa corrente. Vedere [Stampa della mappa] (PRINT.md # stampa-la-mappa) per ulteriori informazioni.

###! [Stampa piano di volo] (../ images / icons / printflightplan.png "Stampa piano di volo") Stampa piano di volo {# stampa-volo-piano}

Apre una finestra di dialogo di stampa che consente di selezionare le informazioni relative al piano di volo da stampare. Vedere [Stampa piano di volo mappa] (PRINT.md # stampa-il-piano-volo) per ulteriori informazioni.

###! [Esci] (../ images / icons / application-exit.png "Esci") Esci {# file-esci}

Esce dall'applicazione. Chiederà conferma se c'è un piano di volo modificato.

### Menu del piano di volo {# volo-piano-menu}

####! [Annulla] (../ images / icons / undo.png "Annulla")! [Ripeti] (../ images / icons / redo.png "Ripeti") Annulla / Ripeti {# annulla-ripeti }

Consente di annullare e ripetere tutte le modifiche del piano di volo.

####! [Seleziona una posizione iniziale per la partenza] (../ images / icons / parkingstartset.png "Seleziona una posizione iniziale per la partenza") Seleziona una posizione iniziale per la partenza {# seleziona-una-partenza-posizione-per-partenza}

Un posto di parcheggio \ (gate, rampa o serbatoio di carburante \), pista o eliporto può essere selezionato come posizione di inizio all'aeroporto di partenza. Una posizione di parcheggio può anche essere selezionata nella voce di menu contestuale della mappa [Imposta come partenza piano di volo] (MAPDISPLAY.md # imposta-come-piano-di-partenza-volo) quando si fa clic con il tasto destro su una posizione di parcheggio. Se non viene selezionata alcuna posizione, la fine della pista primaria più lunga viene selezionata automaticamente come inizio.

! [Seleziona la finestra di dialogo Posizione iniziale] (../ images / selectstartposition.jpg "Seleziona la finestra di dialogo Posizione iniziale")


_ ** Immagine sopra: ** La finestra di dialogo per la selezione della posizione iniziale per EDDN._

####! [Modifica piano di volo sulla mappa] (../ images / icons / routeedit.png "Modifica piano di volo sulla mappa") Modifica piano di volo sulla mappa {# modifica-piano-volo-sulla-mappa}

Attiva o disattiva la modalità di modifica del piano di volo sulla mappa. Vedi [Modifica del piano di volo] (MAPFPEDIT.md # modifica del piano di volo mappa).

####! [Nuovo piano di volo dalla descrizione del percorso] (../ images / icons / newroutefromstring.png "Nuovo piano di volo dalla descrizione del percorso") Nuovo piano di volo dalla descrizione del percorso {# nuovo-volo-piano-da-descrizione }

Apre una finestra di dialogo con la descrizione del percorso del piano di volo corrente che consente anche di modificare il piano di volo corrente o inserirne uno nuovo.
[Piano di volo dalla descrizione del percorso] (ROUTEDESCR.md) fornisce ulteriori informazioni su questo argomento.

####! [Copia il percorso del piano di volo negli Appunti] (../ images / icons / routestring.png "Copia il percorso del piano di volo negli Appunti") Copia il percorso del piano di volo negli Appunti {# volo-piano-rotta-appunti}

Copia la descrizione del percorso del piano di volo corrente negli Appunti utilizzando le impostazioni della finestra di dialogo [Piano di volo dalla descrizione del percorso] (ROUTEDESCR.md # piano di volo-da-percorso-descrizione).

####! [Calcola diretto] (../ images / icons / routedirect.png "Calcola diretto") Calcola diretto {# calcola-diretto}

Elimina tutti i waypoint intermedi e collega la partenza e la destinazione utilizzando una grande linea circolare.

È possibile calcolare un piano di volo tra qualsiasi tipo di waypoint, anche waypoint definiti dall'utente \ (fare clic con il tasto destro sulla mappa e selezionare `Aggiungi posizione al piano di volo` per crearne uno \). Ciò consente la creazione di frammenti che possono essere uniti in piani di volo. Ad esempio è possibile utilizzare questa funzione per attraversare il Nord Atlantico con diverse partenze e destinazioni. Questo vale per tutte le modalità di calcolo del piano di volo.

####! [Calcolate la Radionavigazione] (../ images / icons / routeradio.png "Calcolate la  Radionavigazione") Calcolate la Radionavigazione {# calcola-radionavigazione}
Crea un piano di volo che utilizza solo stazioni VOR e NDB come waypoint e cerca di garantire la ricezione di almeno una stazione, lungo l'intero piano di volo. Si noti che le stazioni VOR sono preferite prima delle stazioni NDB e DME, che, se possibile, sono evitate. Il calcolo fallirà se non si trovano abbastanza radio aiuti tra la partenza e la destinazione. Costruisci il piano di volo manualmente se questo è il caso.

Questo calcolo può essere utilizzato anche per creare un frammento del piano di volo tra qualsiasi tipo di waypoint.

####! [Calcola altitudine elevata] (../ images / icons / routehigh.png "Calcola altitudine elevata") Calcola altitudine elevata {# calcola-altitudine elevata}

Utilizza le vie aeree Jet per creare un piano di volo.

I piani di volo calcolati lungo le vie aeree obbediranno a tutte le restrizioni sulle vie aeree come il minimo e l'altitudine. Il programma aderirà anche alle restrizioni di sola andata e di altitudine massima per i navdata basati su X-Plane.

L'altitudine minima risultante viene impostata nel campo dell'altitudine del piano di volo. Il campo di altitudine del piano di volo non viene modificato se non sono state rilevate restrizioni di altitudine lungo il piano di volo.

Una regola est / ovest semplificata viene utilizzata per regolare l'altitudine di crociera su valori pari / dispari \ (questo può essere disattivato nella finestra di dialogo `Opzioni` nella scheda` Piano di volo` \).

Il comportamento predefinito è saltare dall'aeroporto di partenza al successivo waypoint di una via aerea adatta e viceversa per la destinazione. Questo può essere modificato nella finestra di dialogo "Opzioni" nella scheda "Piano di volo" se si preferiscono le stazioni VOR o NDB come punti di transizione alle vie aeree.

La rete delle vie aeree di Flight Simulator non è completa \ (mancano ad esempio le piste del Nord Atlantico - queste cambiano quotidianamente \), quindi il calcolo su grandi aree oceaniche può fallire.

Creare manualmente le vie aeree come soluzione alternativa o utilizzare uno strumento di pianificazione online per ottenere una stringa di rotta, utilizzare l'opzione `Nuovo piano di volo da stringa` per creare il piano di volo.

Questo calcolo può essere utilizzato anche per creare un frammento del piano di volo tra qualsiasi tipo di waypoint.

####! [Calcola bassa altitudine] (../ images / icons / routelow.png "Calcola bassa altitudine") Calcola bassa altitudine {# calcola-bassa altitudine}

Utilizza le vie aeree Victor per creare un piano di volo. Tutto il resto è uguale a "Calcola altitudine elevata".

####! [Calcola in base a una determinata altitudine] (../ images / icons / routealt.png "Calcola in base a una determinata altitudine") Calcola in base a una determinata altitudine {# calcola in base a una determinata altitudine}

Utilizzare il valore nel campo dell'altitudine del piano di volo per trovare un piano di volo lungo le vie aeree Victor e / o Jet. Il calcolo fallirà se il valore dell'altitudine è troppo basso. Tutto il resto è uguale a "Calcola altitudine elevata".

####! [Piano di volo inverso] (../ images / icons / routereverse.png "Piano di volo inverso") Piano di volo inverso {# inverso-volo-piano}

Scambia la partenza e la destinazione e inverte l'ordine di tutti i waypoint intermedi. Viene assegnata una pista predefinita per la nuova posizione di partenza di partenza.

Si noti che questa funzione non considera le vie aeree a senso unico nel database X-Plane e potrebbe comportare un piano di volo non valido.

####! [Regola l'altitudine del piano di volo] (../ images / icons / routeadjustalt.png "Regola l'altitudine del piano di volo") Regola l'altitudine del piano di volo {# regola-volo-piano-alt}

Modifica l'altitudine del piano di volo in base a una regola est / ovest semplificata e al tipo di rotta corrente \ (IFR o VFR \). Arrotonda l'altitudine fino al più vicino valore pari a 1000 piedi \ (o metro \) per i piani di volo occidentali o dispari 1000 piedi \ (o metro \) per i piani di volo orientali. Aggiunge 500 piedi per i piani di volo VFR.

### Menu Mappa {# mappa-menu}

####! [Vai a Home] (../ images / icons / home.png "Vai a Home") Vai a Home {# vai a-home}

Passa all'area di Home impostata utilizzando [Imposta home] (MAPDISPLAY.md # imposta-home) utilizzando la posizione salvata e la distanza di zoom. Il centro dell'area di home è evidenziato da un simbolo! [Simbolo di home] (../immagine / icone / homesymbol.png "Simbolo di home").

####! [Vai al centro per la ricerca della distanza] (../ images / icons / centermark.png "Vai al centro per la ricerca della distanza") Vai al centro per la ricerca della distanza {# vai-al-centro-per-distanza-ricerca}

Vai al punto centrale utilizzato per le ricerche a distanza. Vedi [Imposta centro per la ricerca della distanza] (MAPDISPLAY.md # stabilire-centro-per-distanza-ricerca). Il centro per la ricerca della distanza è evidenziato da un! [Simbolo di ricerca della distanza] (../immagine / icone / segno di distanza. png "Simbolo ricerca distanza").

####! [Centro piano di volo] (../ images / icons / centerroute.png "Centro piano di volo") Piano di volo centra {# centra-volo-piano}

Ingrandisce la mappa \ (se necessario \) per visualizzare l'intero piano di volo sulla mappa.

####! [Centra Aereo] (../ images / icons / centeraircraft.png "Centra Aereo") Centra Aereo {# centra-aereo}

Esegue lo zoom sull'aeromobile dell'utente se collegato direttamente a un simulatore di volo o connesso in remoto tramite [Little Navconnect] (https://albar965.github.io/littlenavconnect.html) e mantiene l'aereo centrato sulla mappa.

Il centraggio dell'aereo può essere modificato nella finestra di dialogo "Opzioni" nella scheda "aereo del simulatore".

####! [Ripristina impostazioni di visualizzazione] (../ images / icons / centeraircraft.png "Ripristina impostazioni di visualizzazione") Ripristina impostazioni di visualizzazione {# ripristina-schermo-settaggi}

Ripristina tutte le impostazioni di visualizzazione della mappa ai valori predefiniti.

! [Ripristina impostazioni interessate] (../ images / resetdisplaysettings.jpg "Ripristina impostazioni interessate")

_ ** Immagine sopra: ** Tutti i pulsanti dello strumento di impostazione evidenziati che sono interessati da _`Ripristina schermo Settaggi` _._

####! [Elimina percorso aereo] (../ images / icons / aircrafttraildelete.png "Elimina percorso aereo") Elimina percorso aereo {# elimina-aereo-percorso}

Rimuove la traccia dell'aeromobile dell'utente. Viene inoltre eliminato durante la connessione a un simulatore di volo. Il percorso viene salvato e verrà ricaricato all'avvio del programma.

####! [Tornare  indietro sulla mappa] (../ images / icons / back.png "Tornare indietro sulla mappa")! [Posizione della mappa in avanti] (../ images / icons / next.png "Posizione della mappa in avanti") Posizione mappa avanti / indietro {# posizione-mappa-indietro-avanti}

Salta avanti o indietro nella cronologia delle posizioni della mappa. La cronologia completa viene salvata e ripristinata all'avvio di _Little Navmap_.

#### Dettagli

#####! [Ulteriori dettagli] (../ images / icons / detailmore.png "Ulteriori dettagli") Ulteriori dettagli {# ulteriori-dettagli}

#####! [Dettagli predefiniti] (../ images / icons / detaildefault.png "Ulteriori dettagli") Dettagli predefiniti {# predefiniti-dettagli}

#####! [Meno dettagli] (../ images / icons / detailless.png "Meno dettagli") Meno dettagli {# meno-dettagli}

Aumenta o diminuisce i dettagli sulla mappa. Maggiori dettagli significano più aeroporti, più radioaiuti, più informazioni di testo e icone più grandi.

Nota che le informazioni sulla mappa verranno troncate se si scelgono troppi dettagli. In questo caso verrà visualizzato un messaggio di avviso rosso nella barra di stato.

Il livello di dettaglio è mostrato nella barra di stato. L'intervallo è da -5 per alcuni dettagli a +5 per la maggior parte dei dettagli.

#### Proiezione {#proiezione}

##### Mercatore {#mercatore}

Una proiezione piatta che offre il movimento più fluido e la mappa più nitida quando si utilizzano temi di mappe online basati su riquadri come _OpenStreetMap_ o _OpenTopoMap_.


##### Sferico {#sferico}

Mostra la terra come un globo che è la proiezione più naturale. Il movimento può tartagliare leggermente quando si utilizzano temi di mappe online basati su riquadri come _OpenStreetMap_ o _OpenTopoMap_. Usa i temi della mappa `Semplice`,` Pianura` o `Atlante` per evitarlo.

Le mappe online possono apparire leggermente sfocate quando si utilizza questa proiezione. Questo è il risultato della conversione dei riquadri di immagini piatte nella visualizzazione sferica.

! [Piccola proiezione sferica Navmap e tema mappa semplice] (../ images / sphericalpolitical.jpg "Piccola proiezione sferica Navmap e tema mappa semplice")

_ ** Immagine sopra: ** Proiezione di mappe sferiche con _`Simple`_ tema della mappa offline selezionato._

#### Tema {#tema}

Tutte le mappe online vengono fornite da servizi gratuiti, pertanto non è possibile garantire velocità di download elevate e disponibilità elevata. In ogni caso è facile rilasciare e installare una nuova provenienza di mappe online senza creare una nuova versione di _Little Navmap_. Vedere [Creazione o aggiunta di temi della mappa] (MAPTHEMES.md) per ulteriori informazioni.

##### OpenStreetMap {#openstreetmap}

Questa è una mappa raster online (ovvero basata su immagini \) che include un'opzione di ombreggiatura delle colline. Nota che l'ombreggiatura _OpenStreetMap_ non copre l'intero globo.

! [OpenStreetMap e ombreggiatura della collina] (../ images / osmhillshading.jpg "OpenStreetMap e ombreggiatura della collina")

_ ** Immagine sopra: ** Visualizzare in un aeroporto italiano usando il tema OpenStreetMap e l'ombreggiatura della collina._

##### OpenMapSurfer {#openmapsurfer}

Il livello [OSM Roads] (http://korona.geog.uni-heidelberg.de) fornito da [Heidelberg University] (http://giscience.uni-hd.de). Questo tema include l'ombreggiatura opzionale della collina, disponibile in tutto il mondo.

Si noti che l'opzione di ombreggiatura della collina di questa mappa è contrassegnata come sperimentale.

I dati della mappa per questa mappa sono forniti dai collaboratori di © [OpenStreetMap] (http://osm.org), resi da [GIScience Research Group @ Heidelberg University] (http://giscience.uni-hd.de) e lo stile della mappa da Maxim Rylov.

[SRTM] (http://srtm.csi.cgiar.org); ASTER GDEM è un prodotto di [METI] (http://www.meti.go.jp/english/index.html) e [NASA] (https://lpdaac.usgs.gov/dataset_discovery/aster/aster_policies).

! [OSM strade and Ombreggiatura collina] (../ images / osmroad.jpg "OSM strade e ombreggiatura collina")

_ ** Immagine sopra: ** Visualizzare in un aeroporto italiano usando il tema OpenMapSurfer e l'ombreggiatura della collina._

##### OpenTopoMap {#opentopomap}

Una mappa raster online che imita una mappa topografica. Include l'ombreggiatura della collina e le linee di contorno dell'elevazione a distanze di zoom inferiori.

I riquadri per questa mappa sono forniti da [OpenTopoMap] (http://www.opentopomap.org).

! [OpenTopoMap] (../ images / otm.jpg "OpenTopoMap")

_ ** Immagine sopra: ** Visualizza sulle Alpi orientali usando il tema OpenTopoMap. Un piano di volo è mostrato a nord delle Alpi ._

##### Stamen Terrain {# stamen-terrain}

Una mappa del terreno con ombreggiatura delle colline e colori naturali della vegetazione. L'ombreggiatura delle colline è disponibile in tutto il mondo.

Mappa tassellata di [Stamen Design] (http://stamen.com), sotto [CC BY 3.0] (http://creativecommons.org/licenses/by/3.0). Dati di [OpenStreetMap] (http://openstreetmap.org), sotto [ODbL] (http://www.openstreetmap.org/copyright).

! [Stamen Terrain] (../ images / stamenterrain.jpg "Stamen Terrain")

_ ** Immagine sopra: ** Visualizza il tema del terreno stamen ._

##### CARTO Light {# carto-light} \ (Novità nella versione 1.4.4 \)

Una mappa molto luminosa chiamata * Positron * che consente di concentrarsi sulle funzioni di aviazione sul display della mappa. La mappa include la stessa opzione di ombreggiatura della collina di _OpenStreetMap_.

Mappa tassellata e stile di [CARTO] (https://carto.com/). Dati di [OpenStreetMap] (http://openstreetmap.org), sotto [ODbL] (http://www.openstreetmap.org/copyright).

##### CARTO Dark {# carto-light} \ (Novità nella versione 1.4.4 \)

Una mappa scura chiamata * Conenuto oscuro oscura*. La mappa include la stessa opzione di ombreggiatura della collina di _OpenStreetMap_.

Mappa tassellata e stile di [CARTO] (https://carto.com/). Dati di [OpenStreetMap] (http://openstreetmap.org), sotto [ODbL] (http://www.openstreetmap.org/copyright).

##### Semplice \ (Offline \) {# semplice-offline}

Questa è una mappa politica che utilizza poligoni colorati del paese. Confini e complessi idrici sono raffigurati grossolani. La mappa inclusa in _Little Navmap_ ha un'opzione per visualizzare i nomi delle città e dei paesi.

##### Piano \ (Offline \) {# piano-offline}

Una mappa molto semplice. La mappa è inclusa in _Little Navmap_ e ha un'opzione per visualizzare i nomi delle città e dei paesi. Confini e complessi idrici sono raffigurati grossolani.

##### Atlas \ (Offline \) {# atlas-offline}

Una mappa molto semplice che include sfumature grossolane delle colline e colori della terra. La mappa è inclusa in _Little Navmap_ e ha un'opzione per visualizzare i nomi delle città e dei paesi. Confini e corpi idrici sono raffigurati grossolani.

#### Airspaces

#####! [Mostra spazi aerei] (../ images / icons / airspace.png "Mostra spazi aerei") Mostra spazi aerei {# mostra-spazi aerei}

Permette di abilitare o disabilitare la visualizzazione di tutti gli spazi aerei con un clic. Utilizzare le voci di menu sotto questo o i pulsanti della barra degli strumenti per visualizzare o nascondere i vari tipi di spazio aereo.

La barra degli strumenti degli spazi aerei contiene pulsanti ciascuno con un menu a discesa che consente di configurare la visualizzazione dello spazio aereo come mostrare o nascondere determinati tipi di spazio aereo. Ogni menu a discesa ha anche una voce `Tutto` e` Niente` per controllare o deselezionare tutti i tipi nel menu.

#####! [ICAO spazi aerei] (../ images / icons / airspaceicao.png "ICAO spazi aerei") ICAO Spaziaerei {# icao-spaziaerei}

Consente la selezione di spazi aerei da Classe A a Classe E.

#####! [FIR spazi aerei] (../ images / icons / airspacefir.png "FIR spazi aerei") FIR Spazi aerei {# fir-spazi aerei}

Consente la selezione degli spazi aerei di Classe F e Classe G o regioni di informazioni di volo.

#####! [Spazi aerei limitati] (../ images / icons / airspacerestr.png "Spazi aerei limitati") Spazi aerei limitati {# limitati-spazi aerei}

Mostra o nascondi MOA \ (area operazioni militari \), spazi riservati, vietati e pericolosi.

#####! [Spazi aerei speciali] (../ images / icons / airspacespec.png "Spazi aerei speciali") Spazi aerei speciali {# speciali-spazi aerei}

Mostra o nascondi avvisi, allarmi e spazi aerei di tirocinio .

#####! [Altri spazi aerei] (../ images / icons / airspaceother.png "Altri spazi aerei") Altri spazi aerei {# altri-spazi aerei}

Mostra o nascondi centro, torre, modalità C e altri spazi aerei.

#####! [Limitazioni dell'altitudine dello spazio aereo] (../ images / icons / airspacealt.png "Limitazioni dell'altitudine dello spazio aereo") Limitazioni dell'altitudine dello spazio aereo {# limiti dello spazio aereo-altitudine}

Consente il filtro della visualizzazione dello spazio aereo in base all'altitudine. Al di sotto o al di sopra di 10.000 piedi o 18.000 piedi, solo spazi aerei che si intersecano con l'altitudine del piano di volo.

####! [Forza visualizzazione aeroporti aggiuntivi] (../ images / icons / airportaddon.png "Forza visualizzazione aeroporti aggiuntivi") visualizzazione  gli aeroporti aggiuntivi {# forza-visualizzazione -aggiuntivi-aeroporti}

Gli aeroporti aggiuntivi vengono sempre visualizzati indipendentemente dalle altre impostazioni della mappa dell'aeroporto se questa opzione è selezionata. Ciò consente di visualizzare solo gli aeroporti aggiuntivi selezionando questa opzione e disabilitando la visualizzazione di aeroporti con piste dure, morbide e vuoti.

####! [Mostra aeroporti con piste dure] (../ images / icons / airport.png "Mostra aeroporti con piste dure") Mostra aeroporti con piste dure {# mostra-aeroporti-con-dure-piste}

Mostra gli aeroporti che hanno almeno una pista con una superficie dura.

####! [Mostra aeroporti con piste morbide] (../ images / icons / airportoft.png "Mostra aeroporti con piste morbide") Mostra aeroporti con piste morbide {# mostra-aeroporti-con-morbide-piste}

Mostra gli aeroporti che hanno solo piste a superficie morbida o solo piste d'acqua. Questo tipo di aeroporto potrebbe essere nascosto sulla mappa a seconda della distanza dello zoom.

####! [Mostra aeroporti vuoti] (../ images / icons / airportempty.png "Mostra aeroporti vuoti") Mostra aeroporti vuoti {# Mostra-vuoti-aeroporti}

Mostra aeroporti vuoti. Questo pulsante o voce di menu, potrebbe non essere visibile a seconda delle impostazioni, nella finestra di dialogo "Opzioni" nella scheda "Visualizzazione mappa". Lo stato di questo pulsante è combinato con gli altri pulsanti dell'aeroporto. Ciò significa, ad esempio: è necessario abilitare la visualizzazione degli aeroporti con superficie morbida e aeroporti vuoti per vedere gli aeroporti privi di contenuto con solo piste morbide.


Un aeroporto vuoto è definito come uno che non ha né parcheggi né piste di rullaggio né aprons e non è un componente aggiuntivo. Questi aeroporti sono trattati diversamente in _Little Navmap_ in quanto sono i più noiosi di tutti gli aeroporti standard. Gli aeroporti vuoti sono disegnati in grigio e dietro tutti gli altri aeroporti sulla mappa.

Gli aeroporti che hanno solo piste d'acqua sono esclusi da questa definizione per evitare occultamenti involontari.

####! [Mostra stazioni VOR] (../ images / icons / vor.png "Mostra stazioni VOR") Mostra stazioni VOR {# mostra-vor-stazioni}

####! [Mostra stazioni NDB] (../ images / icons / ndb.png "Mostra stazioni NDB") Mostra stazioni NDB {# mostra-ndb-stazioni}

####! [Mostra waypoint] (../ images / icons / waypoint.png "Mostra waypoint") Mostra waypoint {# mostra-waypoint}

####! [Mostra alette ILS] (../ images / icons / ils.png "Mostra alette ILS") Mostra alette ILS {# mostra-ils-alette}

####! [Mostra Jet Aerovie] (../ images / icons / airwayjet.png "mostra Jet Aerovie") Show Jet Airways {# show-jet-aerovie}

####! [Mostra Victor aerovie] (../ images / icons / airwayvictor.png "Mostra Victor Aerovie") Mostra Victor Aerovie {# mostra-victor-aerovie}

Mostra o nasconde queste strutture o radioaiuti sulla mappa. I radioaiuti potrebbero essere nascosti sulla mappa a seconda della distanza dello zoom.

####! [Mostra piano di volo] (../ images / icons / route.png "Mostra piano di volo") Mostra piano di volo {# mostra-volo-piano}

Mostra o nasconde il piano di volo. Il piano di volo viene mostrato indipendentemente dalla distanza dello zoom.

####! [Mostra avvicinamenti persi] (../ images / icons / missed.png "Mostra avvicinamenti persi") Mostra avvicinamenti persi {# mostra-Persi-avvicinamenti}

Mostra o nasconde gli avvicinamenti mancati dell'attuale piano di volo. Ciò non influisce sull'anteprima nella scheda di ricerca "Procedure".

** Si noti che questa funzione modifica la sequenza delle tratte del piano di volo attivo: ** La sequenza della tratta attiva si arresterà se la destinazione viene raggiunta e gli avvicinaemnti persi non vengono visualizzati. Altrimenti la sequenza continuerà con l'avvicinamento mancato e l'avanzamento dell'aereo del simulatore mostrerà invece la distanza rimanente alla fine del mancato avvicinamento.

####! [Mostra Aereo] (../ images / icons / aircraft.png "Mostra Aereo") Mostra Aereo {# mostra-aereo}

Mostra l'aereo dell'utente e lo mantiene centrato sulla mappa se collegato al simulatore. L'aereo dell'utente viene sempre mostrato indipendentemente dalla distanza dello zoom.

Un clic sull'aereo dell'utente mostra ulteriori informazioni nella finestra ancorata "Aereo Simulatore".

La centratura dell'aeromobile verrà disattivato quando si utilizza una delle seguenti funzioni:

* Fare doppio clic su una vista tabella o visualizzazione mappa per eseguire lo zoom su un aeroporto o un radioaiuto.
* Voce di menu contestuale "Mostra sulla mappa".
* `Vai a Home` o` vai al centro per la ricera della distanza`.
* collegamento `Mappa` nella finestra ancorata` Informazioni`.
* "Mostra piano di volo". O manualmente in una voce di menu o dopo il caricamento.
* Centrato sul file KML / KMZ di Google Earth dopo il caricamento

Ciò consente una rapida ispezione di un aeroporto o di un radioaiuto durante il volo. Per visualizzare di nuovo l'aereo, utilizzare "Tornare indietro sulla mappa" e abilitare nuovamente "Mostra aereo".

####! [Mostra traccia Aereo] (../ images / icons / aircrafttrail.png "Mostra traccia Aereo") Mostra Traccia Aereo {# mostra-aereo-traccia}

Mostra la traccia dell'aeromobile dell'utente. Il percorso viene sempre mostrato indipendentemente dalla distanza dello zoom. Viene salvato e verrà ricaricato all'avvio del programma.


Il percorso viene eliminato quando ci si collega a un simulatore di volo oppure può essere eliminato manualmente selezionando "Menu principale" - & gt; `Mappa` - & gt; "Elimina traccia aereo". Il percorso viene anche eliminato quando, ad esempio, l'aereo dell'utente salta su grande distanza durante l'assegnazione di un nuovo aeroporto.

I formati del percorso sono limitati per motivi di prestazioni. I punti verranno rimossi dall'inizio quando diventa troppo lungo.

####! [Mostra gli aerei AI e Multiplayer] (../ images / icons / aircraftai.png "Mostra gli aerei AI e Multiplayer")! [Mostra Navi AI e Multiplayer] (../ images / icons / boatai.png "Mostra navi AI e multiplayer") Mostra aerei AI e multiplayer o navi {# mostra-mappa-ai-aerei}

Mostra gli aerei o le navi AI e multiplayer sulla mappa. I veicoli multigiocatore possono essere visualizzati ad es. Sessioni FSCloud, VATSIM o Steam.

Si noti che in X-Plane il traffico navale non è disponibile e le informazioni sugli aerei AI sono limitate.

Un clic sull'aeromobile o sulla nave AI mostra maggiori informazioni nella finestra ancorata ` Aerei Simulatore` nella scheda` AI / Multiplayer`.

I veicoli visualizzati sono limitati dal sistema multiplayer utilizzato. Gli aeromobili multigiocatore scompaiono a seconda della distanza dall'aeromobile dell'utente. Per gli AI in FSX o P3D questo è attualmente di circa 100 miglia nautiche o circa 200 chilometri.

Le navi più piccole vengono generate dal simulatore entro un piccolo raggio attorno all'aeromobile dell'utente.

_Little Navmap_ limita la visualizzazione dei veicoli AI in base alle dimensioni. Zoom ravvicinato per vedere piccoli aerei o barche.

Alla minima distanza di zoom tutti gli aeromobili e le navi vengono disegnati per ridimensionarsi sulla mappa.

####! [Mostra griglia mappa] (../ images / icons / mapgrid.png "Mostra griglia mappa") Mostra griglia mappa {# mostra-mappa-griglia}

Mostra una griglia di latitudine / longitudine e il [meridiano] (https://en.wikipedia.org/wiki/Prime_meridian) e [anti meridiano] (http://en.wikipedia.org/wiki/180th_meridian) \ ( vicino alla linea della data \) sulla mappa.

####! [Mostra nomi di paesi e città] (../ images / icons / cities.png "Mostra nomi di paesi e città") Mostra i nomi di paesi e città {# mostra-paesi-e-città-nomi}

Mostra contea, città e altri punti di interesse. La disponibilità di queste opzioni dipende dal tema della mappa selezionato. Vedi [Tema] (MENUS.md # tema).

####! [Show ombreggiatura colline] (../ images / icons / hillshading.png "mostra ombreggiatura colline") Mostra Ombreggiatura Colline {# mostra-Ombreggiatura Colline}

Mostra l'ombreggiatura della collina sulla mappa. La disponibilità di queste opzioni dipende dal tema della mappa selezionato. Vedi [Tema] (MENUS.md # tema).

### Menu Libreria scenari {# scenari-libreria-menu}

#### Simulatore di volo {# Volo-simulatore}

Viene creata una voce del menu per ogni installazione o database del Simulatore di volo trovato. Queste voci di menu consentono il cambio dei database del volo. La voce di menu è disabilitata se viene trovato un solo simulatore di volo.

Il ciclo AIRAC caricato viene visualizzato solo per X-Plane poiché le informazioni non sono disponibili per i simulatori FSX o P3D.

** Si deve prima impostare il percorso di base nella directory X-Plane nella ** Finestra di dialogo carica libreria scenari ** ** per abilitare la voce di menu X-Plane. **

Questo menu è sincronizzato con la selezione del simulatore nella [Finestra di dialogo carica libreria Scenari] (SCENERY.md # carica-scenari-libreria-dialogo). Una volta caricato correttamente un database, la visualizzazione, il piano di volo e la ricerca passeranno ai dati del simulatore appena caricati.

** Si noti che il programma non impedisce di utilizzare un database di scenari X-Plane durante la connessione a FSX / Prepar3D o viceversa. Otterrai effetti indesiderati come informazioni meteorologiche errate se utilizzi tale impostazione. **

Il programma potrebbe modificare un piano di volo caricato se si passa da un database all'altro. Ciò può accadere se nel piano è impostata una posizione di partenza che non esiste nell'altro database. Fai clic su "Nuovo piano di volo" per evitarlo, prima di cambiare.

#### Navigraph {#navigraph}

Questo sottomenu indica anche il ciclo AIRAC se viene trovato un database Navigraph nella directory del database.

Consultare il capitolo [Database di navigazione] (NAVDATA.md) per ulteriori informazioni su questi database e le tre diverse modalità di visualizzazione mostrate di seguito.

##### Usa Navigraph per tutte le funzioni {# navigraph-tutto}

Ignora completamente il database del simulatore e prende tutte le informazioni dal database Navigraph.

##### Usa Navigraph per radioaiuti e Procedure {# navigraph-radioaiuto-proc}

Questa modalità unisce radioaiuti e altro dal database Navigraph al database del simulatore. Ciò influisce sulla visualizzazione della mappa, su tutte le informazioni e su tutte le finestre di ricerca.

##### Non utilizzare il database di  Navigraph {# navigraph-niente}

Ignora il database Navigraph e mostra solo le informazioni lette dallo scenario del simulatore.

#### Mostra file di database {# mostra-database-files}

Questo apre la directory del database di _Little Navmap_ in un file manager. Vedere [Esecuzione senza installazione del simulatore di volo] (RUNNOSIM.md # in esecuzione senza installazione del simulatore di volo) per ulteriori informazioni sulla copia dei file di database tra computer diversi. Ciò consente a _Little Navmap_ di essere eseguito su un computer remoto \ (ad esempio Windows, Mac o Linux \) utilizzando lo stesso database creato sul computer dove è avviato il simulatore di volo.

####! [Carica libreria scenari] (../ images / icons / database.png "Carica libreria scenari") Carica libreria scenari {# carica-scenari-libreria}

Apre la finestra di dialogo "Carica libreria scenari". Vedere [Finestra di dialogo carica libreria scenari] (SCENERY.md # carica-scenari-libreria-dialogo) per ulteriori informazioni. Questa voce di menu è disabilitata se non viene trovata alcuna installazione del simulatore di volo.

####! [Copia degli spazi aerei nel database X-Plane] (../ images / icons / airspacecopy.png "Copia degli spazi aerei nel database X-Plane") Copia gli spazi aerei nel database X-Plane {# copia-spazi aerei-su- XPLANE}

Ciò consente di copiare le informazioni sullo spazio aereo, da un database FSX o P3D a un database X-Plane. Ciò è necessario poiché X-Plane viene fornito con informazioni limitate sullo spazio aereo.

Tutti gli spazi aerei già caricati da X-Plane vengono eliminati prima della copia. Vedere [ spazi aerei X-Plane ] (SCENERY.md # carica-scenari-libreria-dialogo-xp-spazi aerei) per maggiori informazioni.

Devi prima passare a un database di simulatore FSX o P3D per abilitare questa voce di menu.

Le informazioni sullo spazio aereo vengono eliminate quando si ricarica il database X-Plane. Pertanto, è necessario copiare nuovamente gli spazi aerei dopo il ricaricamento.

### Menu Strumenti {# strumenti-menu}

####! [Connessione al simulatore di volo] (../ images / icons / network.png "Connessione al simulatore di volo") Connessione al simulatore di volo {# volo-simulatore-connessione}

Apre la finestra di dialogo `Connetti` che consente a _Little Navmap_ di connettersi direttamente a un simulatore di volo, al plug-in * Little Xpconnect * X-Plane, o in remoto utilizzando il [Little Navconnect] (https://albar965.github.io/littlenavconnect.html) agente. Vedere [Connessione a un simulatore di volo] (CONNECT.md # connessione a un simulatore di volo) per ulteriori informazioni.

#### Ripristina tutti i messaggi {# ripristina-tutti- i messaggi}

Ciò riattiverà tutte le finestre di dialogo che sono state disabilitate selezionando "Non mostrare più questa finestra" o messaggi simili.

####! [Opzioni] (../ images / icons / settings.png "Opzioni") Opzioni {#opzioni}

Apre la [Finestra di dialogo Opzioni] (OPTIONS.md # finestra di dialogo opzioni).

### Menu Window {# window-menu}

#### copertura mappe {# mappe-coperte}

Consente di nascondere le sovrapposizioni di mappe mobili, come la panoramica in alto a sinistra o la bussola nell'angolo in alto a destra della finestra della mappa.

####! [Cerca] (../ images / icons / searchdock.png "Cerca") Cerca {#cerca}

####! [Piano di volo] (../ images / icons / routedock.png "Piano di volo") Piano di volo {# piano di volo}

####! [Informazioni] (../ images / icons / infodock.png "Informazioni") Informazioni {#informazioni}

####! [Profilo di elevazione del piano di volo] (../ images / icons / profiledock.png "Profilo di elevazione del piano di volo") Profilo di elevazione del piano di volo {# volo-piano-elevazione-profilo}

####! [Aereo simulatore] (../ images / icons / aircraftdock.png "Aereo simulatore") Aereo Simulatore {# simulatore-aereo}

####! [Legenda] (../ images / icons / legenddock.png "Legenda") Legenda {#legenda}

Apre o chiude queste finestre ancorate. La finestra ancorata della mappa non può essere chiusa.

#### Barra degli strumenti principale, Barra degli strumenti della mappa, Barra degli strumenti degli spazi aerei della mappa, Barra degli strumenti delle opzioni della mappa, Barra degli strumenti del piano di volo, Barra degli strumenti della finestra ancorata, Barra di stato {# principale-barra degli strumenti-opzioni}

Mostra o nasconde queste barre degli strumenti e la barra di stato.

#### Ripristina struttura finestra {# ripristina-struttura}

Ripristina la struttura della finestra principale di default. Ciò implica visibilità, posizione e stato di tutte le finestre ancorate e delle barre degli strumenti. Questa funzione può essere utile se una finestra ancorata si perde nelle configurazioni multi monitor.

### Menu di aiuto {#aiuto-menu}

#### ![Contenuti \(Online\)](../images/icons/help.png "Contents \(Online\)") Contenuti \(Online\) {#aiuto-contenuti}

Mostra il manuale  utente online nel browser Web predefinito.

####! [Sommario \ (Offline, PDF \)] (../ images / icons / help.png "Contenuti \ (Offline, PDF \)") Sommario \ (Offline, PDF \) {# aiuto-contenuti -disconnesso}

Mostra il manuale dell'utente PDF incluso nel programma di visualizzazione PDF predefinito.

####! [legenda mappa navigazione] (../ images / icons / help.png "Legenda mappa navigazione") Legenda mappa navigazione{# mappa navigazione-legenda-mappa-legenda}

Mostra la legenda della mappa relativa alla navigazione nella finestra ancorata `Legenda`. Puoi anche accedere alla legenda qui: [Legenda mappa navigazione] (LEGEND.md).

####! [Legenda della mappa per l'attuale tema della mappa] (../ images / icons / help.png "Legenda della mappa per il tema attuale della mappa") Legenda della mappa per il tema attuale della mappa {# mappanavigazione-legenda-mappa-legenda}

Mostra la legenda base che dipende dal tema della mappa nella finestra ancorata `Legenda`. Nota che la legenda non è disponibile per tutti i temi della mappa.

####! [Informazioni su Little Navmap] (../ images / icons / littlenavmap.png "Informazioni su Little Navmap") Informazioni su Little Navmap {# a proposito di-little-navmap}

Mostra la versione e il numero di revisione per _Little Navmap_, contiene anche collegamenti alla directory del database, al file di configurazione, al file di registro e all'indirizzo e-mail dell'autore.

####! [Informazioni su Marble] (../ images / icons / marble.png "Informazioni su Marble") Informazioni su Marble {# a proposito di-marble}

Informazioni sul [congegno di Marble] (https://marble.kde.org) utilizzato per scaricare e mostrare le mappe.

####! [Informazioni su Qt] (../ images / icons / qticon.png "Informazioni su Qt") Informazioni su Qt {# a proposito di -qt}

Informazioni sul [Qt applicazione framework] (https://www.qt.io) utilizzato da _Little Navmap_.

####! [Donate per questo programma] (../ images / icons / about.png "Dontate for this Program") Donate per questo programma {#donate}

Apre la pagina Web delle donazioni nel browser predefinito.

Se desideri mostrare il tuo apprezzamento, puoi effettuare una donazione tramite PayPal.

Le donazioni sono puramente opzionali, ma molto apprezzate.

####! [Controlla aggiornamenti] (../ images / icons / revert.png "Controlla aggiornamenti") Controlla aggiornamenti {# controlla-aggiornamenti}

Consente di verificare manualmente la presenza di aggiornamenti. Questo mostrerà anche gli aggiornamenti che sono stati recentemente ignorati premendo il tasto "Ignora questo aggiornamento" nella finestra di dialogo di notifica.

Vedere [Verifica aggiornamenti] (UPDATE.md) per ulteriori informazioni.


## Barra di Stato {#statusbar}

La barra di stato mostra varie indicazioni \ (da sinistra a destra \):

* Ultima azione o breve aiuto per spiegare una voce di menu o un pulsante della barra degli strumenti.
* Indicatore che mostra i tipi di aeroporto, gli spazi aerei, i radioaiuti o i veicoli AI attualmente visibili sulla mappa. La descrizione comandi fornisce ulteriori dettagli.
  * Verrà visualizzato un messaggio di avviso in rosso `Troppi oggetti` se troppi oggetti vengono visualizzati sulla mappa a causa di un livello di dettaglio troppo elevato. La visualizzazione della mappa sarà incompleta in questo caso.
  * Verrà visualizzato un messaggio rosso "Database vuoto" se il database attualmente selezionato non ha contenuto e deve essere caricato.
* Stato della connessione per una connessione locale o remota. La descrizione comandi fornisce ulteriori dettagli sullo stato come il nome host per le connessioni remote.
  * `Connessione in corso ...`: il programma sta tentando di stabilire una connessione avviata manualmente o automaticamente.
  * `Connesso`: è stata stabilita una connessione.
  * `Disconnesso`: il simulatore o _Little Navconnect_ è uscito.
* Livello di dettaglio della mappa. L'intervallo è compreso tra -5 per alcuni dettagli e +5 per la maggior parte dei dettagli.
* Indicatore di avanzamento del download della mappa online. Questo mostra lo stato del download della mappa corrente. Il testo è preceduto da un'indicazione rossa "Offline" se la modalità offline è abilitata.
  * `Fatto.`: tutti i dati della mappa caricati correttamente.
  * `In attesa dei dati ...`: i dati della mappa mancano nella cache e sono stati richiesti. Ora aspetta una risposta.
  * `In attesa di aggiornamenti ...`: i dati della mappa sono già stati caricati ma sono scaduti dopo due settimane. In attesa di nuovi dati dopo aver richiesto un aggiornamento.
  * `Incompleto.`: download non riuscito. Si noti che l'indicatore di avanzamento può sembrare bloccato nel messaggio "In attesa di dati ..." se non è disponibile l'ombreggiatura di una collina per una regione _OpenStreetMap_, o se si ingrandisce molto vicino quando si utilizzano determinate mappe online.
* Distanza zoom \ (punto di vista dalla superficie terrestre \) in miglia o chilometri nautici.
* Posizione del cursore sulla mappa in gradi / minuti / secondi o gradi decimali latitudine e longitudine a seconda dell'unità selezionata nella finestra di dialogo `Opzioni`. Mostra anche l'altezza del suolo sotto il cursore dopo un breve ritardo se vengono selezionati i dati di elevazione offline [GLOBE] (https://ngdc.noaa.gov/mgg/topo/globe.html).

! [Barra di stato] (../ images / statusbar.jpg "barra di stato")

_ ** Immagine sopra: ** Barra di stato con messaggio sull'ultima azione sul lato sinistro \ (_ `Opzioni modificate.`_ \), lo stato della connessione e una descrizione comandi che indica ciò che è attualmente mostrato sulla mappa. Vengono visualizzate tutte le funzionalità della mappa. Il livello di dettaglio della mappa è invariato e le coordinate della mappa sono mostrate in basso a destra. Anche l'altitudine vicino al  cursore viene mostrata, poiché sono installati i dati di elevazione offline. L'indicatore di avanzamento del download della mappa online mostra _`Fatto`_ che indica che sono state scaricate tutte le tessere della mappa. La distanza di zoom è di 7,8 miglia nautiche.
