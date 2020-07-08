
## Modifica del piano di volo della mappa {# mappa-volo-piano-modifica}

La modalità tascina e rilascia del piano di volo è attivata per impostazione predefinita, ma può essere disabilitata utilizzando la barra degli strumenti o `Menu principale` ->` Piano di volo` -> `Modifica piano di volo sulla mappa`.

È possibile utilizzare la tastiera, la rotellina del mouse o le sovrapposizioni della mappa per scorrere e ingrandire durante la modifica del percorso.

Si noti che il trascinamento ed il rilasciamento del piano di volo si basa sul presupposto che esiste già una connessione diretta tra partenza e destinazione.

Seleziona sempre prima la partenza e la destinazione se desideri costruire manualmente il tuo piano di volo. Ciò collegherà entrambi i punti con una grande linea circolare. Sulla base di questa linea puoi iniziare ad aggiungere radioaiuti al tuo piano di volo.

Si noti che non è possibile la selezione delle vie aeree.

Il cursore si trasformerà in una croce! [Cursor Cross] (../ images / cursorcross.png) se un nuovo radioaiuto può essere aggiunto a una tratta. Un cursore! [Cursor Move] (../ images / cursormove.png) verrà mostrato se un radioaiuto presente può essere sostituito da un altro o se una posizione dell'utente può essere spostata.

Sono disponibili le seguenti funzionalità:

* ** Fare clic su una tratta del piano di volo: ** Inizia la modifica e aggiunge un nuovo waypoint a seconda di dove viene effettuato il clic successivo:
 * ** Su un singolo aeroporto e radioaiuto: ** L'oggetto è inserito nel segmento del piano di volo.
 * ** Su più aeroporti o radioaiuti: ** Viene visualizzato un menu che consente di selezionare l'oggetto da inserire.
 * ** Nessun aeroporto e nessun radioaiuto: ** Una posizione definita dall'utente viene inserita nel piano di volo.
* ** Fare clic sul waypoint: ** Inizia la modifica e sostituisce il waypoint cliccato con un oggetto a seconda di dove viene fatto il clic successivo:
  * ** Su un singolo aeroporto e radioaiuto ** L'oggetto sostituisce il waypoint cliccato.
  * ** Su più aeroporti o radioaiuti: ** Viene visualizzato un menu che consente di selezionare l'oggetto che deve sostituire il waypoint cliccato.
  * ** Nessun aeroporto e nessun radioaiuto: ** Una posizione definita dall'utente sostituisce il waypoint.
* ** Fare clic su partenza o destinazione: ** Sostituisce la partenza o la destinazione con un oggetto a seconda di dove viene effettuato il clic successivo:
 * ** Su un singolo aeroporto: ** L'aeroporto sostituisce la partenza o la destinazione. Una pista di default viene assegnata come posizione di partenza se questa viene sostituita con un nuovo aeroporto.
 * ** Su un radioaiuto: ** L'oggetto sostituisce la partenza o la destinazione che risulta in un piano di volo non valido. Il piano di volo può essere salvato e caricato (verrà mostrato un avviso) ma non è utilizzabile da Flight Simulator.
 * ** Su più aeroporti o navaidi: ** Viene visualizzato un menu che consente di selezionare l'oggetto che sostituisce la partenza o la destinazione.
 * ** Nessun aeroporto e nessun radioaiuto: ** Una posizione definita dall'utente sostituisce il waypoint con conseguente piano di volo non valido.
* ** Clic destro, premendo il tasto Esc o qualsiasi clic all'esterno della finestra della mappa: ** Annulla l'operazione corrente.

** Limitazioni in caso di utilizzo delle procedure: ** Non è possibile aggiungere radioaiuti nelle procedure o tra le procedure né eliminare le fasi di esse. Il cursore non cambierà forma quando si passa con il mouse su una procedura. Non è consentito:
* Aggiungere un waypoint tra l'aeroporto di partenza e SID.
* Aggiungere un waypoint tra STAR o avvicinamento e aeroporto di destinazione.
* Aggiungere un waypoint tra STAR e avvicinamento o transizione.
* Spostare o rimuovere il primo o l'ultimo waypoint di una procedura.
Tutte le procedure di partenza o di destinazione vengono rimosse se l'aeroporto di partenza o di destinazione viene spostato o sostituito. Lo stesso vale se i waypoint vengono anteposti o aggiunti dopo la partenza o la destinazione.

! [Modifica piano di volo] (../ images / fpedit.jpg "Modifica piano di volo")

_ ** Immagine sopra: ** Inserimento di un radioaiuto in una tratta del piano di volo facendo clic e spostando la linea della tratta. Viene mostrato un suggerimento per il radioaiuto._

! [Modifica piano di volo] (../ images / fpedit2.jpg "Modifica piano di volo")

_ ** Immagine sopra: ** Sostituzione di VOR TRA nel piano di volo con un altro semplicemente facendo clic e spostando il waypoint TRA su KLO. Viene visualizzato un menu di selezione per il chiarimento delle ambiguità.
