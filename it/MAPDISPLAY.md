## Visualizzazione mappa {# mappa-visualizzazione}

Vedere la [navigazione traccia sulla Mappa] (LEGEND.md) per dettagli sui vari simboli mostrati sulla mappa.

### Spostamento {#spostammento}

Usa il clic e trascina per spostare la mappa e la rotellina del mouse per ingrandire o ridurre. Puoi anche utilizzare i pulsanti di sovrapposizione sul lato destro della mappa.

In alternativa, utilizza la tastiera per spostarti sulla mappa:

* Tasti cursore: scorrere la mappa
* `+` e `-`: ingrandisce e rimpicciolisce
* `Alt + Sinistra` e` Alt + Destra`: vai avanti o indietro nella cronologia delle posizioni della mappa
* `Ctrl ++` e `Ctrl + -`: aumenta o diminuisce i dettagli
* `Ctrl + Home`: vai alla posizione iniziale
* `Ctrl + Fine`: Vai al centro per la ricerca della distanza

Non dimenticare di attivare la finestra della mappa facendo clic su di essa prima di utilizzare i tasti per spostarti.

### Clic del mouse {# clic del mouse}

Un singolo clic su un aeroporto, radiaiuto, aerovia o uno spazio aereo mostra i dettagli nella finestra ancorata "Informazioni".

Un singolo clic su un velivolo utente, un velivolo AI o un velivolo multiplayer mostra i dettagli nella finestra ancorata "Aereo del simulatore".

Un doppio clic consente di ingrandire da vicino il diagramma dell'aeroporto o il radioaiuto e mostra anche i dettagli nella finestra ancorata "Informazioni". Lo stesso vale per tutti gli aerei o le navi AI o multiplayer.

La funzionalità di doppio clic e singolo clic non funziona per i waypoint del piano di volo o gli aeroporti se la modalità di modifica del piano di volo è abilitata. La modalità di modifica può essere disabilitata usando la barra degli strumenti o il `Menu principale` - & gt; `Piano di volo` - & gt; `Modifica piano di volo sulla mappa`.

La sensibilità del clic del mouse può essere regolata nella finestra di dialogo "Opzioni" nella scheda "Visualizzazione mappa".

### Aereo {#aereo}

L'aereo utente e l'aereo o le navi AI o multiplayer verranno mostrati sulla mappa se il programma è collegato a un simulatore di volo. Il colore indica l'utente o l'intelligenza artificiale o il veicolo multiplayer e la forma del simbolo indica se l'aeromobile è un aereo a pistoni / turbopropulsore, jet, elicottero o nave. Il contorno del simbolo diventa grigio se un aereo è a terra.

Little Navmap limita la visualizzazione dei veicoli AI in base alle dimensioni. Zoom accurato per vedere piccoli aerei o barche

I velivoli AI e multiplayer a terra sono mostrati solo su piccole distanze di zoom per evitare ingombri negli aeroporti. Ciò significa che un aereo AI può scomparire dalla mappa quando atterra su un aeroporto.

Sulla distanza di zoom più bassa tutti gli aeromobili sono disegnati in scala così come i punti di parcheggio, il che significa che puoi facilmente verificare se il tuo aereo si adatta su un piazzale, un parcheggio o una via di rullaggio.

Una freccia gialla del vento ed etichette per la situazione intorno al velivolo dell'utente possono essere visualizzate nel
centro superiore della mappa. Le etichette visualizzate per gli aeromobili possono essere configurate nella finestra di dialogo `Opzioni` nella scheda` Visualizzazione mappa`. Nessuna etichetta viene mostrata per il traffico navale.

Vedere la [mappa della tratta di nvigazione]] (aereo LEGEND.md #) per dettagli sul tipo di aereo.

### Suggerimenti {#suggerimenti}

Passando il mouse sulla mappa verranno visualizzate le descrizioni dei comandi per tutti gli oggetti della mappa, inclusi aeroporti, VOR, NDB, vie aeree, parcheggio, serbatoio di carburante, torri, aeromobili e navi. La descrizione comandi viene troncata e mostra un messaggio "Altro ..." se diventa troppo lungo. In tal caso, ridurre i dettagli o ingrandire.

La sensibilità per la visualizzazione della descrizione comandi può essere regolata nella finestra di dialogo "Opzioni" nella scheda "Visualizzazione mappa".

! [Suggerimento] (../ images / tooltip.jpg "Tooltip")! [Suggerimento spazi aerei] (../ images / tooltipairspace.jpg "Tooltip Airspace")

_ ** Immagini sopra: ** Descrizione comando con informazioni per un aeroporto e un VOR e una descrizione comando con informazioni sugli spazi aerei ._

### In evidenza {#in evidenza}

Aeroporti o radiaiuti selezionati nella tabella del piano di volo o nella tabella dei risultati di ricerca, sono evidenziati sulla mappa, rispettivamente con un anello verde / nero o giallo / nero.

I waypoint selezionati nell'anteprima della procedura sono evidenziati con un anello blu / nero.

Questi anelli di evidenziazione, forniscono tutte le funzionalità degli oggetti della mappa visibili, anche se gli oggetti non vengono mostrati alla distanza dello  zoom corrente \ (l'anello è vuoto \). Ciò consente un doppio clic per ingrandire, un singolo clic per la finestra ancorata delle informazioni e tutte le voci del menu contestuale.

Puoi usare il pulsante "Cancella selezione"! [Cancella selezione] (../ images / icons / clearselection.png "Cancella selezione") nella parte superiore del piano di volo e cerca le finestre per rimuovere eventuali punti salienti della mappa.

### Daigramma dell'aeroporto {# aeroporto-diagramma}

Il display cambierà da una singola icona a un diagramma dello aeroporto se si ingrandisce abbastanza in profondità per un aeroporto. Il diagramma mostra tutte le vie di rullaggio, le posizioni di parcheggio, i gates, le piste e altro ancora.

Il diagramma dell'aeroporto fornisce ulteriori informazioni tramite suggerimento per le posizioni di parcheggio e torre. Un clic destro su una posizione di parcheggio apre il menu di scelta rapida e consente di selezionare la posizione di partenza per l'inizio del piano di volo.

Vedere [mappa della traccia di navigazione] (LEGEND.md # airport-diagram) per dettagli sul diagramma dell'aeroporto.

! [Diagramma dell'aeroporto] (../ images / airportdiagram1.jpg "Airport Diagram")

_ ** Immagine sopra: ** Vista di alto livello del diagramma dell'aeroporto di EDDH._

! [Diagramma dell'aeroporto] (../ images / airportdiagram2.jpg "Airport Diagram")

_ ** Immagine sopra: ** Vista dettagliata del diagramma dell'aeroporto. Mostra le porte blu a destra e alcuni parcheggi verdi per la GA a sinistra. È visibile la  lunga soglia spostata della pista 33. Le linee gialle tratteggiate indicano i percorsi dei taxi.

### Menu contestuale della mappa {# mappa-contestuale-menu}

Il menu contestuale della mappa può essere attivato usando il tasto destro o il tasto menu. Le voci di menu sono abilitate o disabilitate a seconda dell'oggetto selezionato e alcune voci di menu contengono il nome dell'oggetto della mappa selezionato per chiarimenti.

Il menu di scelta rapida della mappa contiene le seguenti voci di menu.

####! [Mostra informazioni] (../ images / icons / globals.png "Mostra informazioni") Mostra informazioni {# mostra-informazioni}

Mostra informazioni dettagliate nella finestra ancorata "Informazioni" per l'aeroporto più vicino, una o più vie aeree, uno o più spazi aerei o tutti i radioaiuti vicino al cursore.

Vedere la [Finestra ancorata informazioni] (INFO.md # finestra-informazioni-finestra) per i dettagli.

####! [Mostra Procedure] (../ images / icons / icons.png "Show Procedures") Mostra Procedure]{# Mostra-Procedure]}

Apre la scheda di ricerca delle procedure della finestra ancorata di ricerca e visualizza tutte le procedure per l'aeroporto.

Vedere [Ricerca procedure] (SEARCHPROCS.md) per ulteriori informazioni.

####! [Misura distanza GC da qui] (../ images / icons / distancemeasure.png "Misura distanza GC da qui") Misura distanza GC da qui {# misura-gc-distanza-da-qui}

Inizia una linea di misurazione al primo clic. Il secondo clic termina la misurazione e mantiene la linea. Tutte le linee di misurazione vengono salvate e verranno ripristinate al successivo avvio.

Puoi usare la tastiera, la rotellina del mouse o le sovrapposizioni della mappa per scorrere e ingrandire mentre trascini una linea.

Fare clic con il tasto destro del mouse, premere il tasto Esc o fare clic all'esterno della finestra della mappa per annullare la modifica della linea di misurazione.

Le linee di misurazione utilizzano miglia nautiche, chilometri o miglia statuarie come unità. I piedi o il metro verranno aggiunti come unità, se le linee sono abbastanza corte. Ciò consente di misurare ad es. distanza di decollo per incroci dei decolli.

Un grande cerchio fornisce la distanza più breve da un punto all'altro sulla terra ma non usa un percorso costante. Per tale motivo la linea di misurazione mostrerà due valori di rotta. Uno per l'inizio e uno per la posizione finale.

La rotta  è sempre indicata in gradi veri, indicato dal suffisso `° T`. Ulteriori informazioni come identificativo o frequenza verranno aggiunte alla linea se la misurazione inizia in un radioaiuto o in un aeroporto.

La larghezza delle linee di misurazione della distanza, può essere modificata nella finestra di dialogo "Opzioni" nella scheda "Visualizzazione mappa".

Vedere [mappa della traccia di navigazione] (LEGEND.md # map-mark) per dettagli sulle linee di misurazione.

####! [Misura la distanza del rombo da qui] (../ images / icons / distancemeasurerhumb.png "Misura la distanza del rombo da qui") Misura la distanza del rombo da qui {# misura-rombo-distanza-da-qui}

Una linea di rombo è una linea di rotta costante e utilizzata tra i waypoint di una via aerea o quando ci  si avvicina a una stazione VOR o NDB. La distanza tra i punti è leggermente più lunga della grande rotta circolare.

Il percorso per una linea romboidale è indicato in gradi magnetici e veri \ (`° ° M`,` ° T` o `° M / T` se i valori di entrambi sono uguali \).

La declinazione magnetica per calcolare la rotta magnetica verrà presa dal file globale `magdec.bgl` all'origine della misurazione.

La declinazione magnetica di un aeroporto o di un radioaiuto verrà utilizzata, se la misurazione inizia in tale punto. Anche in questo caso informazioni aggiuntive come identificativo e frequenza verranno aggiunte alla linea.

Vedere [Declinazione magnetica] (INTRO.md # declinazione magnetica) per le osservazioni su tale argomento.

####! [Rimuovi misurazione della distanza] (../ images / icons / distancemeasureoff.png "Rimuovi misurazione della distanza") Rimuovi misurazione della distanza {# rimuovi-distanza-misurazione}

Questa voce di menu è attiva se si fa clic con il tasto destro alla fine di una linea di misurazione della distanza \ (croce piccola \). Rimuove solo la linea selezionata.

####! [Mostra anelli di distanza] (../ images / icons / rangerings.png "Mostra anelli di distanza") Mostra anelli di distanza {# mostra-distanza-anelli}

Mostra più anelli di intervallo rosso attorno alla posizione cliccata. Il numero e l'itrevallo degli anelli di distanza possono essere modificati nella finestra di dialogo "Opzioni" nella scheda "Visualizzazione mappa". Un'etichetta indica il raggio di ciascun anello in miglia nautiche.
La larghezza di tutti gli anelli di distanza può essere modificata nella finestra di dialogo "Opzioni" nella scheda "Visualizzazione mappa".

####! [Mostra intervallo radioaiuto (../ images / icons / navrange.png "Mostra intervallo radioaiuto") Mostra intervallo radioaiuto {# mostra-radioaiuto-distanza}

Mostra un anello attorno alla radio aiuto cliccato \ (VOR o NDB \) che indica la portata del radioaiuto. Un'etichetta mostra identificativo e frequenza e il colore dell'anello indica il tipo di radioaiuto.

####! [Rimuovi ghiera] (../ images / icons / rangeringoff.png "Rimuovi ghiera") Rimuovi ghiera {# rimuovi-distanza-anello}

La voce di menu è attiva se si fa clic con il pulsante destro del mouse sul punto centrale di un anello di intervallo \ (piccolo cerchio \). Rimuove gli anelli dalla mappa.

####! [Rimuovi tutti gli anelli di distanza e le misure di distanza] (../ images / icons / rangeringsoff.png "Rimuovi tutti gli anelli di distanza e le misure di distanza") Rimuovi tutti gli anelli di distanza e le misure di distanza {# rimuovi-tutti-distanza- misure anelli-e-distanza}

Rimuove tutti gli anelli e le linee di misurazione della distanza dalla mappa.

####! [Imposta come partenza piano di volo] (../ images / icons / airportroutedest.png "Imposta come partenza piano di volo") Imposta come partenza piano di volo {# imposta-come-volo-piano-partenza}

È attivo se il clic si trova in un aeroporto, in una posizione di parcheggio in aeroporto o in un serbatoio del carburante. Sostituirà l'attuale partenza del piano di volo o aggiungerà una nuova partenza se il piano di volo è vuoto.

La pista predefinita verrà utilizzata come posizione iniziale se l'oggetto cliccato è un aeroporto. L'aeroporto e la posizione di parcheggio sostituiranno sia la posizione di partenza che quella di partenza attuale se si fa clic su una posizione di parcheggio all'interno di un diagramma dell'aeroporto.

####! [Imposta come destinazione del piano di volo] (../ images / icons / airportroutestart.png "Imposta come destinazione del piano di volo") Imposta come destinazione del piano di volo {# imposta-come-volo-piano-destinatione}

Questa voce di menu è attiva se il clic si trova in un aeroporto. Sostituirà la destinazione del piano di volo o aggiungerà l'aeroporto se il piano di volo è vuoto.

####! [Aggiungi posizione al piano di volo] (../ images / icons / routeadd.png "Aggiungi posizione al piano di volo") Aggiungi posizione al piano di volo {# aggiungi-posizione-al-volo-piano}


Inserisce l'oggetto cliccato nella tratta del piano di volo più vicina. L'oggetto verrà aggiunto prima della partenza o dopo la destinazione se la posizione cliccata si trova vicino ai punti finali del piano di volo.

Il nome del radioaiuto o dell'aeroporto è mostrato nella voce di menu.

Una posizione definita dall'utente viene aggiunta al piano di volo se nessun aeroporto o radioaiuto è vicino alla posizione cliccata.

####! [Aggiungi posizione al piano di volo] (../ images / icons / routeadd.png "Aggiungi posizione al piano di volo") Aggiungi posizione al piano di volo {# aggiungi-positione-al-volo-piano}

Lo stesso "Aggiungi posizione al piano di volo", ma aggiungerà sempre l'oggetto o la posizione selezionati dopo la destinazione o l'ultimo waypoint del piano di volo.

####! [Elimina dal piano di volo] (../ images / icons / routedeleteleg.png "Elimina dal piano di volo") Elimina dal piano di volo {# delete-from-flight-plan}

Elimina la posizione dell'aeroporto, dal radioaiuto o dell'utente selezionandola dal piano di volo.

####! [Modifica il nome del waypoint utente] (../ images / icons / routestring.png "Modifica il nome del waypoint utente") Modifica il nome del waypoint utente {# modifica-nome-dell'utente-waypoint}

Permette di cambiare il nome di un waypoint definito dall'utente. La lunghezza del nome è limitata a 10 caratteri.

####! [Mostra nella ricerca] (../ images / icons / search.png "Mostra nella ricerca") Mostra nella ricerca {# mostra-nella-ricerca}

Mostra l'aeroporto o il radioaiuto più vicino nella finestra di dialogo di ricerca. I parametri di ricerca correnti vengono ripristinati.

####! [Imposta  il centro per ricerca distanza] (../ images / icons / mark.png "Imposta centro per ricerca distanza") Imposta il centro per ricerca distanza {# imposta-centro-per-distanza-ricerca}

Imposta il punto centrale per la funzione di ricerca della distanza. Vedi [Ricerca a distanza] (SEARCH.md # ricerca-distanza). Il centro per la ricerca della distanza è evidenziato dal simbolo [Simbolo ricerca distanza] (../ images / icons / distancemark.png "Simbolo ricerca distanza").

####! [Imposta Home] (../ images / icons / home.png "Imposta casa") Imposta home {# imposta-home}

Imposta la vista della mappa attualmente visibile come vista principale. Il centro dell'area dell'home è evidenziato da un simbolo! [Simbolo di casa] (../immagine / icone / homesymbol.png "Simbolo di casa").
