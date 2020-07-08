
# Database di navigazione

_Little Navmap_ può utilizzare fino a due database in parallelo:

1. ** Database del simulatore: ** Creato leggendo la libreria di scenari di FSX, P3D o X-Plane.
2. ** Database di navigazione: ** Fornito da Navigraph. Non deve essere compilato e può essere aggiornato da Navigraph _FMS Data Manager_.

_Little Navmap_ è fornito in bundle con un database di navigazione di un recente ciclo AIRAC, abilitato per impostazione predefinita.

** Vedi [Installa aggiornamenti Navigraph] (https://albar965.github.io/littlenavmap_navigraph.html) sulla mia home page per informazioni su come aggiornare i dati di navigazione di ** _ Little Navmap _ **. **

È possibile selezionare tre modalità di visualizzazione dal menu "Libreria scenario", come mostrato di seguito.

## Usa Navigraph per tutte le funzionalità {# navigraph-tutto}

Utilizza solo informazioni dal database Navigraph.

Si noti che le informazioni sull'aeroporto sono limitate in questa modalità. Ciò significa che non sono disponibili piazzali, piste di rullaggio, posizioni di parcheggio, informazioni sulla superficie della pista e informazioni sul carburante. Inoltre, potrebbero mancare aeroporti più piccoli.

Il layout della pista potrebbe non corrispondere al layout della pista nel simulatore se si utilizza uno scenario di base o uno vecchio aeroporto.

Un vantaggio di questa modalità è che le procedure di avvicinamento corrispondono sempre al layout della pista dell'aeroporto.

## Non utilizzare il database di Navigraph {# navigraph-no}

Ignora completamente il database Navigraph e mostra solo le informazioni lette dallo scenario del simulatore.

## Usa Navigraph per radioaiuti e procedure {# navigraph-radioaiuti-procedure}

Modalità predefinita dopo l'installazione o l'aggiornamento di _Little Navmap_.

Questa modalità unisce radioaiuti e altre funzionalità dal database Navigraph al database del simulatore. Ciò influisce sulla visualizzazione della mappa, su tutte le finestre informative e su tutte le finestre di ricerca.

Le seguenti funzioni sono tratte dal database del simulatore quando si utilizza questa modalità:

* Aeroporti \ (anche `Cerca` finestra ancorata, scheda` Aeroporto` \)
* aprons
* Taxiway
* Posizioni di parcheggio
* Frequenze COM
* ILS

Le seguenti funzionalità sono tratte dal database Navigraph:

* radioaiuti \ (waypoint / intersezioni, VOR, NDB, marker \) che riguardano:
 * Finestra di ricerca `Cerca`, scheda` radioaiuti`
 * Calcolo del piano di volo
 * Descrizione del percorso
* Procedure \ (avvicinamenti, SID e STAR \). Questo riguarda:
 * Finestra di ricerca `Cerca`, scheda` Procedure`
 * Caricamento e visualizzazione delle procedure dai piani di volo.
* Airways
* Spazi aerei

### Limitazioni in questa modalità

* _Little Navmap_ ignora eventuali disallineamenti tra procedure e piste a causa degli aggiornamenti dell'aeroporto e non visualizzerà un avviso. Aggiorna un aeroporto utilizzando scenari payware o freeware se scopri che una procedura di avvicinamento o di partenza non inizia alla fine della pista di un aeroporto.
* Le procedure non possono essere riconosciute quando si seleziona "Mostra procedure" nel menu, se un aeroporto ha cambiato il suo identificativo ICAO\ (es. "Kulik Lake": l'identificativo è cambiata da "LKK" a "PAKL" \). Se si sospetta un caso del genere, utilizzare la modalità "Usa Navigraph per tutte le funzioni" per ottenere le procedure per l'aeroporto.
* La ricerca "Procedure" nell'aeroporto, considera solo le procedure disponibili nel simulatore. Passa a "Utilizzare Navigraph per tutte le funzionalità" per cercare aeroporti che dispongono di procedure del database Navigraph.
* Il posizionamento o la presenza ILS potrebbero non corrispondere alle procedure di avvicinamento se un aeroporto ha un nuovo ILS che non è presente nello scenario di base o in una componente aggiuntivo di un vecchio scenario. In questo caso può vedere un avvicinamento ILS senza stazione ILS. Passa a "Usa Navigraph per tutte le funzioni" per superare questa limitazione.

L'uso dell'aggiornamento _fsAerodata_ navdata consentirà di mitigare o addirittura rimuovere tutte le limitazioni di cui sopra poiché porterà lo scenario del simulatore allo stesso stato del database Navigraph.

! [Mancata corrispondenza della procedura di avvicinamento] (../ images / procedure_mismatch.jpg "Mancata corrispondenza della procedura di avvicinamento")

_ ** Immagine sopra: ** Un esempio estremo di disallineamento della pista / procedura. L'avvicinamento del ciclo del database Navigraph 1707 termina sulla pista non visibile 09 mentre lo scenario obsoleto di FSX mostra l'aeroporto nella posizione sbagliata. EDVK è stato ricostruito a nord di Calden nel 2013. Il backgound OpenStreetMap mostra il nuovo aeroporto._
