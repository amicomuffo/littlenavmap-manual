##! [Profilo di elevazione del piano di volo] (../ images / icons / profiledock.png "Profilo di elevazione del piano di volo") Finestra ancorata del profilo di elevazione del piano di volo {# volo-piano-elevazione-profilo-ancorata-finestra}

Questa finestra ancorata mostra l'elevazione al suolo e l'altitudine di crociera del piano di volo insieme per tutti i waypoint del piano di volo. È disponibile solo quando viene caricato un piano di volo. Verrà mostrato anche l'aereo dell'utente se _Little Navmap_ è collegato al simulatore.

L'elaborazione dell'elevazione viene eseguita in background poiché i dati devono essere scaricati e il calcolo della CPU è intenso. Pertanto, l'aggiornamento della visualizzazione dell'elevazione può richiedere da alcuni secondi a mezzo minuto. Questo aggiornamento in background viene avviato dopo aver creato o modificato il piano di volo o quando sono stati scaricati nuovi dati di elevazione. La visualizzazione verrà aggiornato di conseguenza ogni volta che saranno disponibili nuovi dati.

Chiudi la finestra "Profilo di elevazione del piano di volo" se ritieni che ciò causi problemi di prestazioni o scatti. Tutti gli aggiornamenti si interromperanno una volta chiusa la finestra.

Tenete presente che il display di elevazione copre solo il piano di volo e non cambierà la rappresentazione se si scende dal piano di volo con l'aereo del simulatore.

Il piano di volo viene mostrato solo a livello di crociera e nel segmento di discesa. Tuttavia, vedrai il tuo aereo utente e il percorso arrampicarsi e scendere.

### Dati di elevazione online {# volo-piano-elevazione-profilo-online}

Si noti che i dati di elevazione online non coprono tutti i paesi e attualmente terminano a 60 gradi a nord. I dati contengono molti errori noti.

Il calcolo dei punti di elevazione online è limitato ai segmenti del piano di volo non più lunghi di 2000 miglia nautiche per evitare sovraccarichi.
Aggiungi altri waypoint o calcola un piano di volo per evitare questa limitazione.

### Dati di elevazione offline {# volo-piano-elevazione-profilo-offline}

L'utilizzo dei dati di elevazione [GLOBE - Global Land One-km Base Elevation Project] liberamente scaricabili (https://ngdc.noaa.gov/mgg/topo/globe.html) presenta numerosi vantaggi:
* Aggiornamenti più rapidi
* Copertura mondiale
* Nessun errore noto
* Visualizzazione dell'altitudine sotto il cursore nella barra di stato

Vedere la finestra di dialogo [Cache e file] (OPTIONS.md # cache-elevazione) nella finestra di dialogo delle opzioni per istruzioni su come scaricare e installare i dati GLOBE.


# Finestra profilo {# volo-paano-prospetto-profilo-finestra}

Ulteriori informazioni sono visualizzate in un'etichetta nella parte superiore della finestra se il mouse è posizionato sul diagramma.
Anche la posizione corrispondente all'interno del piano di volo è evidenziata sulla mappa.

Le seguenti informazioni sono visualizzate nell'etichetta superiore se collegata al simulatore di volo con una sessione attiva:

* Distanza dall'aeromobile dell'utente alla destinazione del piano di volo
* Distanza dalla top of descend

Inoltre, le informazioni seguenti sono mostrate nell'etichetta superiore quando si passa il mouse sul diagramma:

* Da e verso waypoint
* Distanza dalla partenza e alla destinazione dalla posizione del cursore del mouse.
* Elevazione terreno alla posizione del cursore.
* Altitudine di crociera del piano di volo sopra terra.
* Altitudine sicura per la tratta del piano di volo corrente nella posizione di sorvolo.

Per ulteriori informazioni, consultare la scheda "Navmap" nella finestra ancorata "Legenda" o
[Leg Map Nav] (LEGEND.md # elevazione-profilo-legenda) per i dettagli.

! [Profilo di elevazione del piano di volo] (../ images / profile.jpg "Profilo di elevazione del piano di volo")
_ ** Immagine sopra: ** Profilo di elevazione del piano di volo con linea che indica la posizione di sorvolo del mouse. Le linee arancioni mostrano l'altitudine minima di sicurezza per i segmenti del piano di volo. Il top of descend è mostrata nella parte in alto a destra della finestra.
