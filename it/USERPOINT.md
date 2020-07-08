
## Waypoint definiti dall'utente {#punti dell'utente}

Waypoint definiti dall'utente \ (o punti dell'utente \) ​​consentono di aggiungere, modificare, cercare, esportare e importare segnalibri, punti di interesse, waypoint e altro. Puoi scegliere liberamente quali tipi vuoi vedere come icone sulla mappa.

! [Panoramica dei waypoint definiti dall'utente] (../ images / userpoint_overview.jpg "Panoramica dei waypoint definiti dall'utente")

_ ** Immagine sopra: ** Una panoramica della funzionalità punto dell'utente che mostra le informazioni sulla finestra ancorata di sinistra, i punti utente evidenziati sulla mappa, i punti utente selezionati nella finestra di ricerca sulla destra e il menu a discesa aperto facendo clic sull'icona del punto utente nella finestra ancorata._

## Ricerca waypoint definita dall'utente {# punti utente-ricerca}

La funzionalità dei filtri di ricerca e della tabella dei risultati è simile alla ricerca aeroportuale e radio aiuto. Vedi [finestra ancorata di ricerca] (SEARCH.md) per informazioni su filtri e pulsanti di ricerca.

Ulteriori voci e pulsanti del menu di scelta rapida consentono di aggiungere, modificare ed eliminare i punti utente.

### Pulsanti principali e voci di menu aggiuntive {# punti utente-principali-bottoni}

Vedere [Menu contestuale Visualizza tabella risultati di ricerca] (SEARCH.md # menu risultati-ricerca-vista-tabella-contesto-menu) per una descrizione delle voci comuni del menu contestuale in tutte le finestre di ricerca.

####! [Aggiungi punto utente] (../ images / icons / userdata_add.png "Aggiungi punto utente") Aggiungi Punto utente {# punti utente-aggiungi}

Aggiungi un waypoint definito dall'utente ai dati utente.

Alcuni campi della nuova finestra di dialogo punto utente vengono compilati automaticamente in base a un punto utente selezionato o, se non è stato selezionato nulla nella tabella dei risultati della ricerca, in base alle aggiunte precedenti. Ciò consente di aggiungere rapidamente punti utente simili al database senza la necessità di reinserire tutte le informazioni.

Si noti che è necessario aggiungere le coordinate manualmente se le finestre di dialogo partono vuote, ovvero non è stato selezionato nulla nella tabella dei risultati.Per evitare ciò, aggiungi i punti utente con il menu di scelta rapida della mappa [Aggiungi punto utente] (MAPDISPLAY.md # aggiungi-punto utente)  e impostare automaticamente le coordinate.

Per maggiori informazioni vedi sotto nella finestra di dialogo aggiungi.

####! [Modifica punto utente] (../ images / icons / userdata_edit.png "Modifica punto utente") Modifica punto utente {# punti utente-modifica}

Aprire la finestra di dialogo modifica per uno o più punti utente.

La finestra di dialogo modifica mostra una colonna di caselle di controllo sul lato destro se è selezionato più di un punto utente. Questi consentono di scegliere i campi da modificare.

Vedi sotto per maggiori informazioni sulla finestra di dialogo aggiungi.

####! [Elimina punto utente] (../ images / icons / userdata_delete.png "Elimina punto utente") Elimina punto utente {# punti utente-cancella}

Rimuovere i punti utente selezionati in seguito ad una finestra di dialogo di conferma.

####! [Reimposta ricerca] (../ images / icons / clear.png "Reimposta ricerca") Reimposta ricerca {# punti utente-ripristina-cerca}

Cancella i filtri di ricerca e ripristina la visualizzazione di tutte le voci nella vista tabella dei risultati di ricerca.
#### ![Pulisci selezione](../images/icons/clearselection.png "pulisci selezione") Pulisci selezione {#punti utente-pulisci-selezione}


Deseleziona tutte le voci selezionate nella tabella e rimuovi tutti i cerchi evidenziati dalla mappa.

####! [Aiuto] (../ images / icons / help.png "Help") Aiuto {# punti utente-aiuto}

Visualizza un rapido aiuto nella descrizione comandi. Fare clic per aprire questo capitolo del manuale nel browser predefinito.

####! [Pulsante Menu] (../ images / icons / menubutton.png "Pulsante Menu") Pulsante Menu {# punti utente-menu}

Pulsante del menu a discesa che consente di nascondere o mostrare le opzioni di ricerca.

Il menu a discesa prefigura le voci di menu con un indicatore di cambiamento `*` per mostrare che la relativa riga del filtro ha delle modifiche.

### finestra di dialogo aggiungi punto utente {# punti utente-dialogo-aggiungi}

La finestra di dialogo viene visualizzata quando si seleziona [Aggiungi punto utente] (MAPDISPLAY.md # aggiungi-punto utente)! [Aggiungi punto utente] (../ images / icons / userdata_add.png "Aggiungi punto utente") nel menu contestuale della mappa, utilizzando il pulsante in alto nella scheda di ricerca del punto utente o selezionando `Aggiungi punto utente` dal menu contestuale nella tabella dei risultati di ricerca.

La finestra di dialogo verrà riempita automaticamente in base al contesto della mappa selezionato, alla selezione nella tabella dei risultati della ricerca o alle aggiunte precedenti.

" il tipo" può essere selezionato da un elenco a discesa o immesso liberamente.

Il campo "Descrizione" consente il testo su più righe e caratteri speciali. La formattazione come corsivo o grassetto non è supportata.

I collegamenti sono riconosciuti nel campo "Descrizione" e possono essere aperti nella finestra ancorata "Informazioni" nella scheda "radio aiuti" che viene visualizzata dopo aver fatto clic su un punto utente o selezionando "Mostra informazioni" in uno dei menu di scelta rapida. I normali collegamenti Web come `http: // www.example.com` o` https: // www.example.com` sono riconosciuti oltre ai collegamenti a directory o file come `file: /// C: / Projekte / atools` su Windows o `file: /// home / alex / Aircraft_Notes.txt` su macOS o Linux.

Il campo "Visibile da" consente di definire la visibilità sulla mappa in base alla distanza dello zoom. La distanza dello zoom \ (distanza del punto di vista dalla superficie terrestre \) per la vista della mappa corrente è mostrata nella [Barra di stato] (MENUS.md # barra di stato). Il punto utente sarà visibile per tutte le distanze dello zoom inferiori al valore in "Visibile da". Il valore massimo è 3000 nm e il valore minimo è 1 nm.

Coordinate valide sono necessarie per confermare la finestra di dialogo. Vedere [Coordinate Formati] (COORDINATES.md # coordinate-formati) per una descrizione dettagliata dei formati delle coordinate riconosciuti. Un'etichetta sotto le coordinate visualizza le coordinate analizzate o un messaggio di errore nel caso in cui le coordinate non possano essere analizzate.

Tutti gli altri campi di testo sono facoltativi e possono essere lasciati vuoti.


Il punto utente viene rimosso al successivo avvio di _Little Navmap_ quando `Punto utente temporaneo. Elimina all'avvio successivo. È selezionato.

Il pulsante "Ripristina" cancella tutti i campi ad eccezione delle coordinate e imposta il tipo di punto utente sul "Segnalibro".

! [Aggiungi finestra di dialogo per waypoint definiti dall'utente] (../ images / userpoint_add.jpg "Aggiungi finestra di dialogo per waypoint definiti dall'utente")

_ ** Immagine sopra: ** Aggiungi finestra di dialogo che è stata riempita automaticamente dal contesto. L'utente ha fatto clic con il pulsante destro del mouse su un aeroporto e ha selezionato _`Aggiungi l'aeroporto punto utente Francoforte come principale (EDDF) `_._

#### Finestra di dialogo Modifica punti utente {# punti utente-dialogo-modifica}

##### Un singolo punto utente

La finestra di dialogo modifica mostra gli stessi campi di modifica della finestra di dialogo utilizzata per aggiungere i punti utente sopra.

Dati aggiuntivi aggiuntivi mostrati in fondo:

* ** Ultima modifica: ** Data e ora di importazione, creazione o modifica.
* ** Importato da file: ** File e percorso del file sorgente dall'importazione CSV, X-Plane o Garmin. È possibile filtrare la ricerca punto utente per questo nome.
* ** Punto utente  temporaneo: verrà eliminato al prossimo avvio. ** Indica che il punto utente è temporaneo.

Il pulsante "Ripristina" annulla tutte le modifiche manuali e riporta tutti i campi al loro stato originale.

! [Modifica la finestra di dialogo per un waypoint definito dall'utente] (../ images / userpoint_edit.jpg "Modifica la finestra di dialogo per un waypoint definito dall'utente")

_ ** Immagine sopra: ** Modifica la finestra di dialogo per un singolo punto utente._

##### Punti utente multipli

Se è stato selezionato più di un punto utente per la modifica, la finestra di dialogo di modifica mostra una colonna di caselle di controllo sul lato destro.

Se selezionato, il campo a sinistra viene sbloccato e qualsiasi testo inserito verrà assegnato al rispettivo campo in tutti i punti utente selezionati. I campi non selezionati non verranno modificati per nessuno dei punti utente.

In combinazione con la potente funzione di ricerca, ciò consente modifiche in blocco come la correzione di un'area non valida e la modifica simultanea dell'intervallo di visibilità per i punti utente interessati:

1. Cerca tutti i punti utente con la regione non valida.
2. Selezionare tutti i punti utente risultanti, ad es. facendo clic su uno dei punti utente tra i risultati della ricerca e premendo `Ctrl + A` o facendo clic sull'angolo in alto a sinistra dell'intestazione della colonna.
3. Fare clic con il tasto destro su uno dei punti utente evidenziati e selezionare "Modifica punti utente" dal menu contestuale.
4. Fare clic sulla casella di controllo a destra del campo "Regione:" e modificare la regione.
5. Fare clic sulla casella di controllo a destra del campo "Visibile da:" e regolare il valore.
6. Fare clic su "OK".

! [Modifica la finestra di dialogo per i waypoint definiti dall'utente] (../ images / userpoint_edit_bulk.jpg "Modifica la finestra di dialogo per i waypoint definiti dall'utente")

_ ** Immagine sopra: ** Modifica la finestra di dialogo per più di un punto utente. I campi _`Regione`_ e _`Visibile da`_ verranno modificati per tutti i punti selezionati. Tutti gli altri campi rimangono invariati._

### Tipologie {# punti utente-tipologie}

Il tipo di punto utente può essere qualsiasi stringa di testo. Se il testo corrisponde a una voce dell'elenco seguente, viene utilizzata l'icona appropriata. Altrimenti, viene usata l'icona  "Sconosciuto"! [Sconosciuto] (../ images / icons / userpoint_Unknown.png "Sconosciuto").

Tipologie e icone possono essere personalizzate e possono essere aggiunte nuove tipologie. Vedere [Icone categoria punti utente] (CUSTOMIZE.md # personalizza-icone-punto-utente) per informazioni su come eseguire questa operazione.

Alcuni tipi vengono utilizzati come valori predefiniti quando si aggiungono nuovi punti utente. Questo dipende dal contesto, ovvero da cosa si trovava sotto il cursore quando si fa clic con il tasto destro sulla mappa.

** Nota che per ora i tipi di punti utente non possono essere tradotti in altre lingue. **

*! [Aeroporto] (../ images / icons / userpoint_Airport.png "Aeroporto") ** Aeroporto **: impostazione predefinita quando si crea un punto utente in cima a un aeroporto.
*! [pista di atterraggio] (../ images / icons / userpoint_Airstrip.png "pista di atterraggio") **Pista di atterraggio **
*! [Segnalibro] (../ images / icons / userpoint_Bookmark.png "Segnalibro") ** Segnalibro **: tipo predefinito per i nuovi punti utente.
*! [Cabina] (../ images / icons / userpoint_Cabin.png "Cabina") ** Cabina **
*! [Chiuso] (../ images / icons / userpoint_Closed.png "Chiuso") ** Aeroporto chiuso **
*! [Errore] (../ images / icons / userpoint_Error.png "Errore") ** Errore **
*! [bandiera] (../ images / icons / userpoint_Flag.png "bandiera") ** Bandiera **
*! [Eliporto] (../ images / icons / userpoint_Helipad.png "Eliporto") ** Eliporto **
*! [Posizione] (../ images / icons / userpoint_Location.png "Posizione") ** Posizione **
*! [Registro] (../ images / icons / userpoint_Logbook.png "Registro") ** Registro **: Tipo di voci del registro aggiunte automaticamente per il decollo e l'atterraggio. Vedere la voce di menu [Crea voci del registro] (MENUS.md # dati utente-menu-creare-logbook).
*! [Marcatore] (../ images / icons / userpoint_Marker.png "Marcatore") ** Marcatore **
*! [Montagna] (../ images / icons / userpoint_Mountain.png "Montagna") ** Montagna **
*! [Ostacolo] (../ images / icons / userpoint_Obstacle.png "Ostacolo") ** Ostacolo **
*! [Spillo] (../ images / icons / userpoint_Pin.png "Spillo") ** Spillo **
*! [POI] (../ images / icons / userpoint_POI.png "POI") ** POI **
*! [aerporto marittimo] (../ images / icons / userpoint_Seaport.png "aeroporto marittimo") ** Aeroporto marittimo **
*! [Sconosciuto] (../ images / icons / userpoint_Unknown.png "Sconosciuto") ** Sconosciuto **: digitare il nome "Sconosciuto" e tutti i tipi che non corrispondono ai tipi predefiniti in questo elenco.
*! [VRP] (../ images / icons / userpoint_VRP.png "VRP") ** VRP **: punto di segnalazione visiva.
*! [Waypoint] (../ images / icons / userpoint_Waypoint.png "Waypoint") ** Waypoint **: impostazione predefinita quando si crea un punto utente sopra un radio aiuto.

## CSV formato dei dati {# punti utente-csv}

Il formato dei dati CSV è allineato al formato già utilizzato nella comunità del simulatore di volo e in altre applicazioni.

Ogni riga nel file rappresenta un waypoint definito dall'utente.

I campi minimi per l'importazione sono `Tipo`,` Nome`, `Identificativo`,` Latitudine` e `Longitudine`. Solo "Latitude" e "Longitude" devono essere riempiti, il resto può essere vuoto.

Tutti i dodici campi vengono salvati quando si esportano punti utente come CSV. Inoltre, il campo multilinea `Descrizione` è racchiuso tra virgolette, se necessario, e mantiene le interruzioni di riga.

Il formato numerico inglese \ (punto `.` come separatore decimale \) viene utilizzato in importazione ed esportazione per consentire lo scambio di file su computer con impostazioni di lingua e impostazioni internazionali diverse.

_Little Navmap_ utilizza la codifica [UTF-8] (https://en.wikipedia.org/wiki/UTF-8) durante la lettura e la scrittura di file. Questo è rilevante solo se usi caratteri speciali come dieresi, accenti o altri. Altrimenti la codifica non ha importanza.

Se un'applicazione non riesce a caricare un file CSV esportato da _Little Navmap_, utilizzare [_LibreOffice Calc_] (https://www.libreoffice.org), _Microsoft Excel_ o qualsiasi altro software per fogli di calcolo in grado di leggere e scrivere file CSV per adattare il file esportato nel formato previsto da tale applicazione.

Vedi [Valori separati da virgola] (https://en.wikipedia.org/wiki/Comma-separated_values) in Wikipedia per informazioni dettagliate sul formato.

** Esempio per un userpoint minimo assoluto costituito solo da coordinate: **

`` `
,,, 49.0219993591,7.8840069771
`` `
"Visibile da" verrà impostato sul valore predefinito di 250 nm e il punto utente verrà mostrato usando l'icona "Sconosciuto"! [Sconosciuto] (../ images / icons / userpoint_Unknown.png "Sconosciuto") dopo l'importazione.

** Esempio per un record minimo di userpoint con tipo ** `Montagna` **, identificativo e nome per l'importazione: **

`` `
Montagna, Mio punto d'interesse, MYPOI, 49.0219993591,7.8840069771
`` `
"Visibile da" verrà impostato sul valore predefinito di 250 nm dopo l'importazione.

** Esempio per un userpoint esportato con tipo ** `Montagna` ** e tutti i campi impostati: **

`` `
Montagna, Il mio punto di interesse, MYPOI, 49.0219993591,7.8840069771,1200,2.0085027218, "Vista, Interessante, Punto", "Punto interessante" "Eselsberg" "- bella vista", ED, 250,2018-05-17T17: 44: 26,864
`` `

Prendi nota di seguenti problemi quando analizzi i file CSV: Nel campo `Tag`, l'elenco` "Visualizza, Interessante, Punto" `è racchiuso tra virgolette poiché contiene virgole. La descrizione del campo "Punto interessante" "Eselsberg" "- bella vista" `è racchiusa tra virgolette doppie poiché il testo stesso contiene una coppia di virgolette doppie (` `" Eselsberg "`) che sono, a loro volta, sfuggite a un'altra doppia virgoletta ogni.


#### Campi CSV

| Posizione | Nome | richiesto | Vuoto ammesso | Commento |
| -------- | -------------------- | ------- | ------------ | -------------------------------------------------- -------------------------------------------------- -------------------------------------------------- ------------------------ |
| 1        | Digita | Sì | Sì | Uno dei tipi predefiniti o definiti dall'utente. L'icona per "Sconosciuto" viene utilizzata se il tipo non corrisponde a uno dei tipi noti. |

| 2 | Nome | Sì | Sì | Campo libero da usare. Utilizzato per l'esportazione Garmin. |

| 3 | Ident| Sì | Sì | Richiesto solo per l'esportazione Garmin e X-Plane. Deve essere un identificatore univoco valido con un massimo di cinque caratteri per queste esportazioni. |

| 4 | Latitudine | Sì | No | Intervallo da -90 a 90 gradi usando punto `.` come separatore decimale

| 5 | Longitudine | Sì | No | Intervallo da -180 a 180 gradi usando punto `.` come separatore decimale. |
| 6 | Altitudine | No | Sì | Deve essere un numero valido se utilizzato. L'unità è sempre in piedi.  |                                                                                                                 
| 7 | Varianza magnetica | No | Sì | Ignorato all'importazione e impostato su un valore calcolato valido per l'esportazione. |

| 8 | Tag | No | Sì | Campo libero da usare. La GUI non ha una ricerca di tag speciale. |

| 9 | Descrizione | No | Sì | Campo libero da usare che consente interruzioni di riga. ||

| 10 | Regione | No | Sì | Regione ICAO a due lettere di un punto utente o waypoint. Utilizzato per l'esportazione di X-Plane. Sostituito con il valore predefinito `ZZ` sull'esportazione del piano X se vuoto. |

| 11 | Visibile da | No | Sì | Definisce da quale distanza di zoom in miglia nautiche \ (mostrato in [Barra di stato] (MENUS.md # barra di stato) \) il punto utente è visibile. Impostato su 250 nm se vuoto durante l'importazione. |

| 12 | Data / ora ultimo aggiornamento | No | Sì | Data e ora ISO dell'ultima modifica. Il formato è indipendente dalle impostazioni del formato della data di sistema. Formato: `AAAA-MM-GGTHH: mm: ss`. Esempio: `2018-03-28T22: 06: 16.763`. Non modificabile nella GUI

### X-Plane user_fix.dat Formato dati {# punti utente-xplane}

Ciò consente di leggere e scrivere il file `user_fix.dat` di X-Plane per waypoint definiti dall'utente. Il file non esiste di default e deve essere salvato in `XPLANE / Dati personalizzati / user_fix.dat`.  

Il formato è descritto da _Laminar Research_ in un file PDF che può essere scaricato qui: [XP-FIX1101-Spec.pdf] (https://developer.x-plane.com/wp-content/uploads/2016/10/XP -FIX1101-Spec.pdf).

Il file è costituito da un'intestazione e da un numero di righe per le correzioni dell'utente. Ogni riga ha cinque colonne separate da spazi o caratteri di tabulazione.

Ci sono cinque colonne di dati nel file:

1. Latitudine
2. Longitudine
3. Identificativo
4. Ident. Aeroporto
5. Regione

** Esempio per ** `user_fix.dat` **: **
`` `

|Versione 1101 - ciclo dati 1704, build 20170325, FixXP1101 dei metadati. NoCopyright (c) 2017 achwodu

 50.88166700 12.58666700 PACEC ENRT ZZ
-36.29987335 174.71089172 N0008 NZNI ZZ
99
`` `

** Si noti che, sebbene i waypoint definiti dall'utente non vengano visualizzati sulla mappa del piano X, possono essere selezionati e utilizzati per costruire piani di volo nel GPS e FMS di base del piano X. **


#### Importazione

** Riga di esempio da ** `user_fix.dat` ** sopra: **

`50.88166700 12.58666700 PACEC ENRT ZZ`

* Le coordinate vengono lette nelle coordinate _piccole Navmap_ punto utente.
* La correzione identificativo `PACEC` viene letta nel campo ** Identificativo ** in _Little Navmap_.
* L'aeroporto di correzione `ENRT` \ (in rotta: nessun aeroporto qui \) viene letto nel campo ** Etichetta ** in _Little Navmap_.
* La regione `ZZ` \ (non valida o nessuna regione \) viene letta nel campo ** Regione ** in _Little Navmap_.
* ** Tipo ** sarà impostato su `Waypoint`! [Waypoint] (../ images / icons / userpoint_Waypoint.png" Waypoint ") per tutte le correzioni importate.

#### Esportare

Il mapping è uguale a quello per l'importazione.

* Identificativo per correggere l'identificativo.
* Etichettaper correggere l'aeroporto.
* Regione per correggere la regione.

Tutti gli altri campi vengono ignorati.

L'identificativo è regolato per abbinare una combinazione di massimo cinque cifre e lettere. Un identificativo generato viene utilizzato se ciò non è possibile o l'identificativo è vuoto.

L'aeroporto di Fix è sempre "ENRT" durante l'esportazione.

La regione viene regolata per una combinazione di due cifre e lettere. ZZ viene usato se ciò non è possibile o la regione è vuota.

** L'identificativo deve essere univoco in ** `user_fix.dat` **. Pertanto si consiglia di impostare manualmente un identificativo univoco per ciascun waypoint o di lasciare il campo vuoto in modo che ** _ Little Navmap _ ** possa generare un identificativo durante l'esportazione. **


### Garmin user.wpt Formato dati {# punti utente-garmin}

Il file waypoint utente Garmin è un file CSV. Ogni riga nel file rappresenta un waypoint utente unico.

Nel file devono essere presenti quattro colonne di dati:

1. Identificazione waypoint
2. Nome o descrizione del waypoint
3. Latitudine
4. Longitudine

** Esempio di un file ** `user.wpt` **: **```

MTHOOD,MT HOOD PEAK,45.3723,-121.69783
CRTRLK,CRATER LAKE,42.94683,-122.11083
2WTER,2NM WEST TERRACINA,41.28140000,13.20110000
1NSAL,1NM NORTH SALERNO TOWN,40.69640000,14.78500000
```


L'identificatore del waypoint può essere composto da un massimo di 10 numeri o lettere maiuscole, ma la GTN abbrevia il nome dei primi 6 caratteri. Non è possibile utilizzare caratteri o simboli speciali. _Little Navmap_ regola l'identificativo di conseguenza.

Il nome del waypoint può essere composto da un massimo di 25 numeri, lettere maiuscole, spazi o caratteri `/` barra in avanti. Il nome viene visualizzato quando si selezionano i waypoint per fornire un contesto aggiuntivo al pilota. _Little Navmap_ regola il nome in base alle limitazioni.

#### Importazione

** Riga di esempio da ** `user.wpt` ** sopra: **

`MTHOOD, MT HOOD PEAK, 45.3723, -121.69783`

* L'identificativo `MTHOOD` viene letto nel campo ** Identificativo ** in _Little Navmap_.
* Il nome `MT HOOD PEAK` viene letto nel campo ** Nome ** in _Little Navmap_.
* Le coordinate vengono lette nelle coordinate _piccole Navmap_ punto utente.
* ** Tipo ** sarà impostato su `Waypoint`! [Waypoint] (../ images / icons / userpoint_Waypoint.png" Waypoint ") per tutti i waypoint importati.

#### Esportare

La mappatura dei campi è uguale all'importazione, ma tutti i campi sono adeguati alle limitazioni.

Nota: se un waypoint importato finisce per trovarsi entro 0,001 ° di latitudine e longitudine di un waypoint utente esistente nella GTN, il waypoint e il nome esistenti verranno riutilizzati.

#### Esporta XML per il compilatore BGL di FSX / P3D {# punti utente-bgl}

Questa opzione di esportazione crea un file XML che può essere compilato in un file BGL contenente waypoint.

I campi regione e identifcativo sono richiesti per questa opzione di esportazione. Se la regione è vuota o altrimenti non viene utilizzato `ZZ`. Tutti i waypoint sono di tipo `NAMED`.

Consultare la documentazione dell'SDK di Prepar3D per informazioni su come compilare e aggiungere il BGL al simulatore.

**Esempio:**
`` `xml
<? xml version = "1.0" encoding = "UTF-8"?>
<Versione FSData = "9.0" xmlns: xsi = "http://www.w3.org/2001/XMLSchema-instance" xsi: noNamespaceSchemaLocation = "bglcomp.xsd">
    <! - Creato da Little Navmap versione 2.0.1.beta (revisione 2b14e14) il 2018 05 17T12: 24: 36 ->
   <Waypoint lat = "47.40833282" lon = "15.21500015" waypointType = "NAMED" waypointRegion = "ZZ" magvar = "4.02111530" waypointIdent = "WHISK" />
   <Waypoint lat = "47.39666748" lon = "15.29833317" waypointType = "NAMED" waypointRegion = "ZZ" magvar = "4.01835251" waypointIdent = "SIERR" />
</ FSData>
`` `

### File di backup del database {# punto utente-dati-formato}

_Little Navmap_ crea un backup completo del database ad ogni avvio poiché la funzionalità di annullamento non è disponibile per i punti utente.

È inoltre possibile utilizzare l'esportazione CSV per creare manualmente i backup poiché il CSV consente di esportare l'intero set di dati.

Vedere [Dati utente] (FILES.md # dati utente) per informazioni sui file di backup del database.
