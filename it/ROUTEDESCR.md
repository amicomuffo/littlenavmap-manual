## Descrizione del percorso del piano di volo {# volo-piano-da-rotta-descrizione}

Questa finestra di dialogo consente di creare un piano di volo da una descrizione del percorso man mano che vengono generati o forniti
da vari servizi online.

Una volta aperto, mostrerà la descrizione del percorso per il piano di volo corrente che contiene anche informazioni sulla velocità e sull'altitudine di crociera, se abilitata.

La parte superiore della finestra di dialogo, mostra il campo di input della descrizione del percorso e la parte inferiore mostra eventuali messaggi, avvisi o errori che si verificano durante la lettura.

Il pulsante menu! [Pulsante menu] (../ images / icons / menubutton.png "Pulsante menu") fornisce un menu a discesa che può essere utilizzato per personalizzare la stringa di percorso generata.

Il parser di descrizione proverà a utilizzare la maggior numero possibile della rotta anche se parti del piano di volo
come waypoint o vie aeree non possono essere trovati o i nomi sono ambigui. Verranno visualizzati avvisi nel campo dell' output inferiore, se questo è il caso.

Per i piani di volo estesi può accadere che vengano aggiunti waypoint lontani se i nomi non sono univoci. Rimuovere questi manualmente se necessario.

Molti waypoint e vie aeree non saranno trovati se le descrizioni della rotta dalle ultime fonti AIRAC, sono usate unitamente ai dati di base del simulatore di volo del 2005. Si consiglia di utilizzare un aggiornamento dei dati di navigazione per lo scenario di base quando si leggono le descrizioni dei percorsi da fonti online come [RouteFinder] (http://rfinder.asalink.net/), [Volo online Pianificatore] (http://onlineflightplanner.org/), [SimBrief] (https://www.simbrief.com) o [SkyVector] (https://skyvector.com).

Altrimenti, utilizzare un ciclo AIRAC dai servizi online più vicino all'età dei dati di navigazione del simulatore di volo alla fine del 2005 se non è un'opzione, un aggiornamento dei dati di navigazione .

Si noti che anche i piani di volo calcolati in _Little Navmap_, in alcuni casi, non possono essere riconvertiti esattamente. Ciò accade a causa di ambiguità sul radioaiuto, come stazioni NDB e VOR con gli stessi nomi o errori nei dati di origine.

La velocità e l'altitudine di crociera vengono utilizzate per creare il piano di volo, se indicato. In caso contrario, l'altitudine di crociera viene determinata automaticamente dal tipo di piano di volo \ (IFR o VFR \) e dall'altitudine minima dei segmenti delle vie aeree utilizzate.

Le procedure SID e STAR richiedono un aggiornamento di dati di navigazione ad eccezione di X-Plane che è già dotato di un database di navigazione completo.

! [Finestra di dialogo Descrizione percorso] (../ images / routedescr.jpg "Finestra di dialogo Descrizione percorso")

_ ** Immagine sopra: ** Una descrizione del percorso che è stata letta correttamente con alcuni avvertimenti sugli elementi ignorati. Impossibile trovare il waypoint _`LLL`_. Velocità, altitudine, SID e STAR sono stati riconosciuti. La velocità al suolo di 433 nodi viene calcolata in base al numero di mach 0.74 e alle condizioni atmosferiche standard.


Pulsanti ### {#pulsanti}

* `Negli Appunti`: Copia la descrizione corrente come testo normale negli Appunti.
* "Dagli Appunti": inserisce il testo dagli Appunti nel campo di input. Il testo inserito viene convertito in maiuscolo e tutti i caratteri non validi vengono rimossi dal testo.
* "Aggiorna dal piano di volo": crea nuovamente la stringa di rotta dal piano di volo corrente. Utilizzare questo dopo aver modificato le impostazioni con il pulsante del menu a discesa.
* `Leggi descrizione percorso`: legge la descrizione del percorso e stampa eventuali messaggi, avvisi ed errori nel campo di output inferiore. L'attuale piano di volo non è interessato da questa azione.
* `IFR` /` VFR`: definisce il tipo di piano di volo generato e l'altitudine di crociera determinata automaticamente.
* ** Pulsante Menu **! [Pulsante Menu] (../ images / icons / menubutton.png "Pulsante Menu"):
  * `Aggiungi aeroporto di partenza e di destinazione`: Nota che disabilitare questa opzione comporterà una stringa di rotta che non può essere riletta in un piano di volo.
  * `Aggiungi istruzioni DCT (diretto )`: aggiungi` DCT` per tutte le connessioni dirette al waypoint nel piano di volo.
  * `Aggiungi velocità di crociera e istruzioni altitudine`: aggiunge l'altitudine di crociera dal piano di volo e la velocità al suolo come impostato nella finestra ancorata del piano di volo.
  * `Aggiungi SID e STAR`: aggiungi i nomi SID e STAR se ne vengono utilizzati uno per la partenza o l'arrivo.
  * `Aggiungi SID e STAR` generici: aggiungi le parole chiave` SID` e `STAR` generiche se non sono stati selezionati SID e / o STAR reali.
  * `Aggiungi waypoint anziché Aerovie`: non inserisce nomi di aerovie ma utilizza solo waypoint.
* "Crea piano di volo": chiude la finestra di dialogo e crea un nuovo piano di volo per la descrizione del percorso analizzata e sostituisce il piano corrente. Devi fare clic su "Leggi la descrizione del percorso" prima di creare un piano di volo.

### Formato {#formato}

La descrizione del percorso deve seguire le regole di formato seguenti:

`DA [ETD] [SPEEDALT] [SID] [. TRANS] [ENROUTE] [STAR] [. TRANS] A [ETA] [ALTERNATES]`

Tutti gli elementi tra parentesi quadre sono opzionali.

`DA` e `A`: questi sono gli identificativi richiesti di 3 o 4 lettere per gli aeroporti di partenza e di destinazione.

Esempi: `KEAT`,` CYPU`, `S16`.

"ALTERNATI": gli aeroporti alternati sono opzionali e vengono semplicemente aggiunti al piano di volo. Gli alternati non possono essere utilizzati in combinazione con una procedura di avvicinamento.

`SPEEDALT`: una voce opzionale che contiene la velocità e l'altitudine di crociera. Vedi sotto per un dettaglio.

`ENROUTE`: questo è un elenco di` WAYPOINT` o `AIRWAYWAYPOINT` che formano il piano di volo effettivo. La prima voce deve essere un aeroporto, waypoint, VOR o NDB.

`WAYPOINT`: un waypoint, VOR, NDB, aeroporto o coordinate definite dall'utente. Vedi sotto per i dettagli sulle coordinate. Un waypoint può essere preceduto da "DCT" per indicare una connessione diretta che non utilizza una via aerea. I waypoint possono essere suffissati con un valore `/ SPEEDALT` opzionale sebbene questo sia ignorato.

Esempi: `TAU`,` BOMBI`, `AST`,` CL`, `EDDF`.

`AIRWAYWAYPOINT`: vie aeree e waypoint finale sulle vie aeree sono separate da uno spazio.

Esempi: `V495 CONDI`,` V338 YVR`, `V330 TRENA`.

`SID.TRANS` e` STAR.TRANS`: Entrambe le parole `SID` o` STAR` o SID realie, STAR e nomi delle transizioni dove la transizione opzionale è separata da un `.`. Le parole chiave generiche `SID` e` STAR` creano una connessione diretta alla parte di rotta.

Esempi: `RDHK2.HOLLE`,` OHIO3.LFK`, `RDHK2`,` OHIO3`.

#### Funzionalità non supportate

`ETD` e` ETA`: l'orario di partenza e di arrivo a quattro cifre associato all'identificativo dell'aeroporto viene ignorato.

`WAYPOINT.SPEEDALT`: Ad esempio` BOMBI / N0090A060`. I cambi di altitudine ai waypoint non sono supportati e ignorati durante la lettura.

#### Velocità e altitudine {# velocità-e-altitudine}

Velocità di crociera al suolo e livello di crociera non sono  separati da uno spazio.

La velocità è preceduta da:

"K": chilometri orari seguiti da un valore di quattro cifre.

"N": nodi seguiti da un valore di quattro cifre.

`M`: Mach seguito da un valore di tre cifre. Il valore di mach viene convertito in nodi velocità del suolo ipotizzando condizioni atmosferiche standard all'altitudine di volo.

L'altitudine è preceduta da:

`F`: livello di volo in tre cifre.

`S`: livello di volo metrico in tre cifre di decine di metri.

"A": altitudine in centinaia di piedi in tre cifre.

`M`: altitudine in decine di metro a quattro cifre.

Esempi:

`N0410F310` 410 nodi al livello di volo 310.

`M071F320` Mach 0.71 al livello di volo 320.

`K0790M0710` 790 chilometri orari a 7100 metri.

#### Coordinate {#coordinate}

Le coordinate possono essere fornite in diversi formati:

** Solo gradi ** \ (7 caratteri \): due cifre e indicatore nord / sud più tre cifre e indicatore est / ovest.

Esempio: `51N010E`

** Gradi e minuti ** \ (11 caratteri \): due cifre gradi, due cifre per minuti e indicatore nord / sud.
Quindi tre cifre per gradi, due cifre per minuti e indicatore est / ovest.

Esempio: `4010N03822W`.

** Gradi, minuti e secondi ** \ (15 caratteri \): due cifre gradi, due cifre per minuti, due cifre per secondi e indicatore nord / sud.
Quindi tre cifre per gradi, due cifre per minuti, due cifre per secondi e indicatore est / ovest. Questo formato è utilizzato da
[SkyVector] (https://skyvector.com) per esempio.

Esempio: `481200N0112842E`.

** Punti di traccia del Nord Atlantico ** \ (NAT \). Due cifre gradi nord e due cifre gradi ovest seguite dal carattere "N".

Esempio: `5010N`.

** Paia di waypoint coordinate ** con gradi e minuti come sopra e prefissate con l'indicatore nord / sud e est / ovest.

Esempi: `N4200 W02000` o` N4200 / W02000`.

** Formato Garmin GFP ** \ (13 caratteri \) indicatore nord / sud, due cifre gradi, tre cifre per minuti di 10. Quindi indicatore est / ovest, tre cifre gradi, tre cifre minuti di 10. Questo formato è utilizzato da il _Flight1 GTN 650 / 750_.

Esempio: `N48194W123096`


### Esempi di descrizione del piano di volo {#esempi}

Francoforte sul Meno \ (EDDF \) a Fiumicino \ (LIRF \):

**Connessione diretta:**


`EDDF LIRF` or `EDDF DCT LIRF`.

** da VOR a VOR:**

`EDDF FRD KPT BOA CMP LIRF`.

* Come sopra con orario di partenza \ (** `ETD` ** \) e orario di arrivo \ (**` ETA` ** \) che verranno ignorati entrambi: **

`EDDF1200 FRD KPT BOA CMP LIRF1300`.

** Come sopra al livello di volo 310 a 410 nodi: **

`EDDF N0410F310 DCT FRD DCT KPT DCT BOA DCT CMP DCT LIRF`

** Uso delle vie aeree Jet: **

`EDDF ASKIK T844 KOVAN UL608 TEDGO UL607 UTABA UM738 NATAG Y740 LORLO M738 AMTEL M727 TAQ LIRF`

** Come sopra al livello di volo 310 a mach 0,71 con velocità e altitudine aggiuntive a ** `NATAG` ** che verranno ignorate: **

`EDDF M071F310 SID ASKIK T844 KOVAN UL608 TEDGO UL607 UTABA UM738 NATAG / M069F350 Y740 LORLO M738 AMTEL M727 TAQ STAR LIRF`

** Waypoint definiti dall'utente con notazione gradi / minuti e un aeroporto alternato** `LIRE`:

`EDDF N0174F255 4732N00950E 4627N01019E 4450N01103E LIRF LIRE`

** Piano di volo che utilizza le procedure SID e STAR con transizioni: **

`KPWA RDHK2.HOLLE ATOKA J25 FUZ J33 CRIED J50 LFK OHIO3.LFK KHOU`

** Piano di volo utilizzando le parole chiave generiche SID e STAR: **

`KPWA SID ATOKA J25 FUZ J33 CRIED J50 LFK STAR KHOU`
