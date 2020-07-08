
## Meteo {#meteo}

_Little Navmap_ può visualizzare METAR da diverse fonti:

* FSX o P3D se collegato. Questo vale anche per le impostazioni di rete.
* Meteo in tempo reale X-Plane dal file `METAR.rwx`. Non quando si utilizzano le impostazioni di rete.
* Servizio meteo online [NOAA] (http://www.weather.gov)
* Servizio meteorologico online della rete [VATSIM] (http://www.vatsim.net)
* [HiFi Simulation Technologies] (http://www.hifisimtech.com):
  * _Active Sky Next_ \ (ASN \)
  * _AS16_
  * _Active Sky for Prepar3D v4_ \ (ASP4 \)

È possibile definire nella finestra di dialogo `Opzioni` sulla scheda` Meteo` quali fonti vengono utilizzate per visualizzare le informazioni METAR in suggerimenti o la scheda `Meteo` nella finestra ancorata` Informazioni`.

Devi impostare il percorso di base per X-Plane nella finestra di dialogo "Carica libreria di scenari" per abilitare la lettura del file meteorologico. Alcune funzioni come le regioni di file meteorologici creati manualmente non sono supportate.

I METAR sono mostrati nelle descrizioni degli aeroporti e nella scheda panoramica "Aeroporto". Le informazioni meteo decodificate per tutte le fonti sono disponibili nella scheda "Meteo".

** Note sul tempo di X-Plane: **
* Little Navmap * può leggere solo il file `METAR.rwx` di X-Plane che contiene il meteo online scaricato. Il programma non è in grado di leggere situazioni meteorologiche personalizzate da X-Plane. * Little Navmap * ha accesso al clima locale intorno all'aeromobile solo se si utilizza una situazione meteorologica personalizzata. Ciò può comportare la situazione in cui si utilizza il meteo personalizzato e * Little Navmap * visualizza ancora informazioni da un vecchio file meteorologico scaricato.

! [Scheda meteo] (../ images / weather.jpg "Scheda meteo")

_ ** Immagine sopra: ** Informazioni meteo decodificate da due fonti online. Il simulatore di volo non è collegato._

### Simulatore di volo

Le informazioni meteorologiche da un simulatore di volo o dal file `METAR.rwx` del piano X possono essere visualizzate in tre tipi per METAR e tempo decodificato che dipende dall'aeroporto selezionato:

* `Stazione`: l'aeroporto ha una stazione meteorologica. Questa è l'indicazione meteorologica più precisa.
* `Più vicino`: l'aeroporto selezionato non ha una stazione meteorologica e il tempo più vicino è stato recuperato. L'identificativo della stazione più vicina è mostrata nel METAR e nella scheda meteo decodificata. La stazione meteorologica più vicina non è necessariamente un aeroporto.
* `Interpolato` \ (non per piano X \): il tempo viene interpolato dal simulatore di volo usando le tre stazioni più vicine. Questa è di solito l'unica opzione disponibile sugli aeroporti che sono lontani dall'aeromobile dell'utente. L'identificativo dell'aeroporto cliccato viene utilizzato nel rapporto METAR per questo tipo di bollettino meteorologico.

Il meteo del simulatore di volo viene aggiornato ogni 15 secondi per rilevare le modifiche nel tema meteo.

* Little Navmap * guarda il file `METAR.rwx` di X-Plane per le modifiche e applicherà immediatamente gli aggiornamenti.

Si noti che il tempo più vicino non rappresenterà necessariamente il tempo sulla stazione cliccata a causa dell'interpolazione tra più stazioni che viene eseguita dal simulatore.

### Online - NOAA and VATSIM


Il tempo online da entrambe le fonti viene aggiornato ogni 10 minuti.

### Active Sky

Tutti i programmi _Active Sky_ vengono riconosciuti automaticamente all'avvio per ciascun simulatore.
I file `current_wx_snapshot.txt` e` activeflightplanwx.txt` vengono caricati e monitorati per le modifiche. Il tempo verrà ricaricato e aggiornato nella visualizzazione delle informazioni se necessario.

Puoi anche selezionare manualmente il file `current_wx_snapshot.txt`. In tal caso il
I METAR di questo file vengono visualizzati per tutti i simulatori di volo installati. `Activeflightplanwx.txt` verrà caricato dalla stessa directory.

La selezione manuale dei file può anche essere utile se una nuova versione di _Active Sky_ non è ancora supportata da _Little Navmap_.

Il tempo di partenza e quello di destinazione verranno visualizzati se un piano di volo viene caricato in uno dei Programmi _Active Sky_. Un suffisso "Destinazione" o "Partenza" indicherà l'utilizzo del tempo del piano di volo Active Sky nella scheda "Meteo". Ciò fornisce agli utenti di _Active Sky_ le indicazioni meteorologiche più precise per la partenza e la destinazione.

Si noti che l'indicazione di `Partenza` o` Destinazione` dipende interamente dal piano di volo caricato in _Active Sky_ e non dal piano di volo in _Little Navmap_.
