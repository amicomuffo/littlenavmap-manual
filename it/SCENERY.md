
##! [Carica libreria scenari] (../ images / icons / database.png "Carica libreria scenari") Finestra di dialogo Carica libreria scenari {# carica-scenari-libreria-dialogo}

Questa finestra di dialogo consente di caricare i dati della libreria degi scenari da tutti e quattro i simulatori di volo supportati nel database interno _Little Navmap_. La libreria degli scenari da caricare può essere selezionata nella casella a discesa `Simulatore:`.

La finestra di dialogo mostra informazioni sul database attualmente selezionato, incluso il numero di aeroporti caricati, la versione del database e altro.

** Solo FSX e P3D: ** Il percorso di base e il percorso `scenery.cfg` verranno mostrati in due campi modificati di testo per il simulatore attualmente selezionato. Questi campi vengono compilati automaticamente, ma possono essere modificati in qualsiasi altra posizione valida. Tutti i valori vengono salvati per ciascun tipo di simulatore di volo.

** Solo X-Plane: ** X-Plane non può essere riconosciuto automaticamente. Devi selezionare manualmente il percorso di base.
Su Windows può essere un percorso come `C: \ Simulators \ X-Plane 11` dove l'eseguibile è` C: \ Simulators \ X-Plane 11 \ X-Plane.exe`.

Il caricamento di una libreria degli scenari può richiedere da 2 a 15 minuti a seconda della configurazione e della quantità di componenti aggiuntivi degli scenari. Puoi accelerare questa situazione,escludendo le directory che non contengono né i dati dell'aeroporto né quelli di navigazione, nella finestra di dialogo "Opzioni" della scheda "Database della  libreria degli scenari".

Tutti gli aeroporti che non si trovano nella directory "Scenario" predefinito di FSX / P3D o che si trovano nella directory "Scenario personalizzato" di X-Plane sono considerati aeroporti aggiuntivi e verranno evidenziati in modo appropriato. Le directory possono essere escluse da questo comportamento nella finestra di dialogo "Opzioni" nella scheda "Database della libreria degli scenari". Questo può essere utile se i componenti aggiuntivi correggono solo l'elevazione dell'aeroporto e questi aeroporti non devono essere evidenziati sulla mappa usando il testo sottolineato e corsivo.

Vedere [Opzioni] (OPTIONS.md # scenario-libreria-database) per ulteriori informazioni sull'esclusione dello scenario.

Il database della libreria degli scenari precedente verrà ripristinato immediatamente se si annulla il processo di caricamento o se il processo di caricamento fallisce.

Il menu `Scenery Library` - & gt; "Simulatore di volo" è sincronizzato con la selezione del simulatore nella finestra di dialogo. Una volta che un database è caricato correttamente, la visualizzazione, il piano di volo e la ricerca passeranno ai dati del simulatore appena caricati.

Si noti che il numero di aeroporti, radiaiuti e altri oggetti mostrati nella "Libreria degli scenari caricata" differirà dai valori mostrati nella finestra di dialogo di avanzamento, poiché un processo separato rimuove i duplicati dopo il caricamento.

La finestra di dialogo di avanzamento mostra tutti gli oggetti trovati durante il caricamento. La finestra di dialogo "Carica libreria di scenari" mostra il numero di oggetti nel database dopo aver rimosso i duplicati e aver eliminato gli aeroporti di base che sono stati sostituiti da scenari aggiuntivi.


** Solo FSX o P3D: ** Il programma tenta di trovare automaticamente i percorsi di base e i file `Scenery.cfg`. Le posizioni tipiche di `Scenery.cfg` per Windows 7/8/10 sono:

* ** Flight Simulator X: ** `C: \ ProgramData \ Microsoft \ FSX \ Scenery.cfg`
* ** Flight Simulator - Steam Edition: ** `C: \ ProgramData \ Microsoft \ FSX-SE \ Scenery.cfg`
* ** Prepar3D v2: ** `C: \ Users \ YOUR_ACCOUNT_NAME \ AppData \ Roaming \ Lockheed Martin \ Prepar3D v2 \ Scenery.cfg`
* ** Prepar3D v3: ** `C: \ ProgramData \ Lockheed Martin \ Prepar3D v3 \ Scenery.cfg`
* ** Prepar3D v4: ** `C: \ ProgramData \ Lockheed Martin \ Prepar3D v4 \ Scenery.cfg`

Dopo il caricamento viene visualizzata una finestra di dialogo di errore se non è stato possibile leggere alcuni file o non sono state trovate directory. In questo caso, è necessario verificare se gli aeroporti degli scenari interessati vengono visualizzati correttamente e mostrare le informazioni corrette. La finestra di dialogo di errore consente di copiare e incollare il testo formattato, utile per la segnalazione degli errori.

La finestra di dialogo "carica libreria degli scenari" mostra l'ultima volta in cui si carica \ (`Last Update:` \), il programma e la versione del database. Le principali differenze di versione del database mostrano database incompatibili. Il programma chiederà se i database incompatibili possono essere cancellati all'avvio prima di poter ricaricare il database degli scenari. Differenze di database minori mostrano modifiche compatibili in cui si consiglia di ricaricare ma non è richiesto.

### Aeroporti X-Plane e dati di navigazione {# carica-scenari-libreria-dialogo-xp-apt-dati navigazione}

* Little Navmap * legge i dati aeroportuali e radioaiuti dai file `* .dat` di X-Plane. Per verificare una versione di un file è possibile aprirlo in un editor di testo in grado di gestire file di grandi dimensioni. Le prime righe del file saranno simili a:

`` `
UN
1100 generato da WorldEditor 1.6.0r1

1 1549 0 0 0A4 Johnson City STOLport
...
`` `
Il primo numero nella seconda riga è la versione del file. Qui è `1100`.

* Little Navmap * può leggere i seguenti file degli scenari X-Plane:

* ** Aeroporti \ (** `apt.dat` ** \): ** Versione 850 fino a 1100. Comprende aeroporti X-Plane 10 e scenari aggiuntivi. I file più recenti di 1100 potrebbero funzionare ma non sono stati testati.
* ** dati di navigazione \ (** `earth_awy.dat` **, **` earth_fix.dat` ** e ** `earth_nav.dat` ** \): ** Versione 850 fino a 1100. Ciò esclude X- Aereo 10 file radio aiuti. I file più recenti di 1100 potrebbero funzionare ma non sono stati testati.
* ** Procedure \ (** `ICAO.dat` ** nella directory **` CIFP` ** \): ** Tutte le procedure da X-Plane 11.
* ** Spazi aerei\ (** `* .txt` ** \): ** Incluso` usa.txt` e tutti i file in formato OpenAir. Vedi il prossimo capitolo per maggiori informazioni.

Inoltre vengono letti i file `user_fix.dat` e` user_nav.dat` nella directory X-Plane `databse comuni`.

### Spazi aerei X-Plane  {# carica-scenari-libreria-dialogo-xp-spazi aerei}

Tutti i file in [formato di spazio aereo OpenAir] (http://www.winpilot.com/UsersGuide/UserAirspace.asp) verranno caricati durante la lettura della libreria degli scenari X-Plane.

Puoi anche copiare gli spazi aerei da un database FSX o Prepar3D attuale se sei in possesso di questi simulatori. Vedere [Copia degli spazi aerei nel database X-Plane] (MENUS.md # copia-spazi aerei-verso-xplane).

Si noti che i file dello spazio aereo possono contenere errori che potrebbero impedire il caricamento di un file dello spazio aereo. Questi errori gravi vengono segnalati dopo aver caricato la libreria degli scenari. Altri errori che riguardano solo singoli spazi aerei o la geometria sono riportati solo nel file di registro.

X-Plane 11 viene fornito con un singolo file di spazio aereo che può essere trovato in `TUA_DIRECTORY_XPLANE/Risorse / dati predefiniti / spazi aerei / usa.txt`.
File di spazi aerei aggiuntivi possono essere scaricati da [OpenAirspace Directory] (http://www.winpilot.com/openair/index.asp), [Soaring Services] (http://soaringweb.org/), [openAIP] (https : //www.openaip.net/) o [Luftraumdaten Deutschland] (https://www.daec.de/fachbereiche/luftraum-flugbetrieb/luftraumdaten) per esempio.

I file di spazio aereo devono avere un'estensione `.txt` e sono caricati dalle seguenti directory da * Little Navmap *:

* `TUA_DIRECTORY_XPLANE / Risorse / dati predefiniti / spazi aerei`
* `TUA_DIRECTORY_XPLANE / Dati personalizzati / Spazi aerei`
* `TUO_ACCOUNT_NOME / Documenti / Little Navmap / X-Plane Spazi aerei` dove` Documenti` è la directory dei documenti nella tua lingua.

I file possono essere codificati in qualsiasi formato [UTF] (https://en.wikipedia.org/wiki/Unicode#UTF) ma devono avere un [BOM] (https://en.wikipedia.org/wiki/Byte_order_mark) essere riconosciuto correttamente. Altrimenti viene utilizzata la codifica ANSI di Windows \ (`Windows-1252` \). I caratteri speciali come le sfumature o gli accenti non vengono visualizzati correttamente nei nomi se la codifica non è corretta. Tutte le altre funzionalità non sono interessate.

Puoi convertire i file usando qualsiasi editor avanzato come [Notepad ++] (https://notepad-plus-plus.org/) per esempio.

Gli spazi aerei appariranno come duplicati nella mappa se un file dello spazio aereo viene trovato in più di una di queste directory.

** Inserisci i file in `Documenti / Little Navmap / X-Plane  spazi aerei` se trovi che X-Plane ha un crash durante il caricamento di determinati file dello spazio aereo. In questo modo, gli spazi aerei sono almeno disponibili in * Little Navmap * che è più tollerante agli errori. **


### Opzioni della finestra di dialogo carica libreria degli scenari {# carica-scenari-libreria-dialogo-opzioni}

* `Simulatore`: seleziona il simulatore per caricare e mostrare le statistiche del database nell'etichetta sopra.
* `Ripristina percorsi`: ripristina tutti i percorsi ai valori predefiniti.
* `percorso base del simulatore di volo` e` Selezione ... `: il percorso della directory di base del simulatore di volo selezionato. Questa in genere è la directory che contiene `FSX.exe` o` Prepar3D.exe`. Questa è la base per tutti i percorsi relativi trovati nel file `scenery.cfg`.
* `File della configurazione dello scenario` e` Seleziona ... `\ (solo FSX e P3D \): il file` scenery.cfg` del simulatore. È inoltre possibile creare copie del file originale, modificarle rimuovendo o aggiungendo scenari e selezionandoli qui per il caricamento.
* `Leggi voci dello scenario inattive` \ (solo FSX e P3D \): leggerà tutte le voci dello scenario, anche quelle inattive / disabilitate. Questo è utile se usi uno strumento per disabilitare lo scenario prima di volare ma vuoi comunque vedere tutti gli scenari dei componenti aggiuntivi in ​​_Little Navmap_ senza ricaricare.
* `Leggi i pacchetti add-on.xml di Prepar3D` \ (solo P3D v3 e v4 \): se abilitato, legge i pacchetti` add-on.xml` di P3D v4 o v3. Vengono letti dalle sottodirectory di `C: \ Users \ TUONME \ DocumentI \ Prepar3D v4 Files \ add-ons` e` C: \ Users \ TUONOME \ Documenti \ Prepar3D v4 Add-ons`.

* `Carica`: avvia il processo di caricamento del database. È possibile interrompere il processo di caricamento in qualsiasi momento e verrà ripristinato il database precedente. La finestra di dialogo verrà chiusa e il programma passerà a mostrare il database caricato una volta caricato correttamente.
* `Chiudi`: mantiene tutte le impostazioni e le modifiche nella finestra di dialogo e la chiude senza caricare nulla.

! [Finestra di dialogo Carica scenario] (../ images / loadscenery.jpg "Finestra di dialogo Carica scenario")

_ ** Immagine sopra: ** Finestra di dialogo Carica scenario. I dati dello scenario sono già caricati per FSX._

! [Finestra di dialogo di avanzamento dello scenario di caricamento] (../ images / loadsceneryprogress.jpg "Finestra di dialogo di avanzamento dello scenario di caricamento")

_ ** Immagine sopra: ** Finestra di dialogo di avanzamento visualizzata durante il caricamento della libreria degli scenari nel database interno di Little Navmap._
