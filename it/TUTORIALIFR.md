
## Creazione di un piano di volo IFR con procedure di avvicinamento {# guida-ifr}

Questo guida ti mostrerà come creare un piano di volo IFR più complesso che includa le procedure di avvicinamento. Presenta la funzionalità di ricerca avanzata dell'aeroporto e il calcolo automatico del piano di volo.

Mentre questa guida sembra piuttosto lunga, di solito è una questione di mezzo minuto per ottenere un piano di volo se sai dove andare. Lo sforzo di pianificazione mostrato qui è più grande per evidenziare alcune delle funzionalità più avanzate del programma.

Dovresti almeno leggere il tutorial VFR [Costruire un piano di volo VFR] (TUTORIALVFR.md).

Il piano di volo attraverserà il Regno Unito utilizzando un velivolo abilitato all'IFR. La sua portata massima dovrebbe essere superiore a 600 miglia nautiche comprese le riserve e un'altitudine di crociera di 10.000 piedi.

In questa guida non approfondirò le procedure dettagliate di pianificazione del carburante. Questa è un'altra storia per un'altra volta.

La guida presuppone i seguenti presupposti:

* Hai lasciato il tuo aereo a "Bembridge (EGHJ)" alla fine dell'ultimo volo o trattalo come base di partenza.
* Non sai dove vuoi volare oggi.
* Conosci i requisiti per il tuo aereo:
 * autonomia
 * Lunghezza minima della pista
 * Piste difficili
 * Hai bisogno di un  posto dove parcheggiare a destinazione
 * Carburante per tornare indietro

 ### Ricerca pulita {# guida-ifr-pulita}

 Vai alla finestra ancorata "Cerca" e segui i passaggi seguenti:

 * Fai clic distruggi nella tabella dei risultati e seleziona "Ripristina ricerca"! [Ripristina ricerca] (../ images / icons / clear.png) per sbarazzarsi di tutti i criteri di ricerca che possono influenzare la domanda.
 * Fai clic sul pulsante menu! [Pulsante menu] (../ images / icons / menubutton.png) e  sui servizi che i gruppi di ricerca `Strutture`,` Pista`, `Parcheggio` e` Distanza dal segno` siano controllati. Deseleziona tutti gli altri che non ti servono.

 ! [Prepara ricerca] (../ images / tutorial / ifrsearchprep.jpg)

 ### Assegna partenza {# tutorial-ifr-assegnare-partenza}

 Ora cerca l'aeroporto di partenza:

 * Inserisci `EGHJ` nel campo di ricerca` Codice ICAO` in alto a sinistra \ (la causa non ha importanza \).
 * Fare clic con il tasto destro del mouse sull'aeroporto nella tabella dei risultati.
 * Scegli `Imposta come partenza piano di volo`! [Imposta come partenza piano di volo] (../ images / icons / airportroutestart.png). Ciò assegnerà una pista predefinita come posizione iniziale.

 ! [Assegna partenza] (../ images / tutorial / ifrseldeparture.jpg)

 Il tuo piano di volo ha una voce ora. Questo è già sufficiente se si desidera seguire uno schema e si desidera visualizzare informazioni su distanza, velocità e tempo per l'aeroporto.

 Partire da una piattaforma non è del tutto realistico. Selezioniamo una posizione di parcheggio:

 * Vai a `Piano di volo` - & gt; "Seleziona una posizione iniziale per la partenza"! [Seleziona una posizione iniziale per la partenza] (../ images / icons / parkingstartset.png).
 * Scegli una delle posizioni di  rampa piccola GA.
 * Fai clic su "Ok" e la posizione verrà evidenziata sulla mappa.

 ! [Assegna parcheggio] (../ images / tutorial / ifrselparking.jpg)

 In alternativa puoi anche selezionare la posizione iniziale direttamente dal menu contestuale della mappa come descritto nella [guida VFR] (TUTORIALVFR.md).

 Vedi anche [Imposta come partenza piano di volo] (MAPDISPLAY.md # set-as-flight-plan-partenza)


 ### Cerca la destinazione {# guida-ifr-cerca-destinazione}

 Ora cerca un aeroporto di destinazione adatto:

 * Fare nuovamente clic con il tasto destro su `EGHJ` nei risultati della ricerca.
 * Seleziona "Imposta centro per ricerca distanza"! [Imposta centro per ricerca distanza] (../ images / icons / mark.png). Puoi anche farlo sulla mappa. Questo è il punto centrale per la ricerca spaziale.
 * Cancella il campo di ricerca "Codice ICAO" ora \ (è un errore comune lasciare i campi di testo pieni quando si eseguono ricerche distanti che ti daranno una tabella vuota di risultati\).

 Ora cercheremo gli aeroporti che si trovano nel raggio di azione dell'aeromobile ma non troppo vicini. Inoltre, devono essere soddisfatti alcuni criteri, come avere luoghi di parcheggio adatti all'aeromobile e una pista abbastanza lunga.

 Puoi anche trovare aeroporti nell'autonomia dell'aereo utilizzando gli anelli di distanza, dove puoi fare clic con il tasto destro del mouse sulla mappa del tuo aeroporto di partenza e selezionare "Mostra anelli di distanza"! [Mostra anelli di distanza] (../ images / icons / rangerings.png) , sebbene questa funzione non consenta filtri dettagliati dell'aeroporto.

 Useremo la ricerca spaziale anziché gli anelli di distanza poiché vorremmo vedere solo aeroporti adatti per i nostri aerei.


 Controlla quanto segue nella scheda di ricerca dell'aeroporto:

 1. `Classificazione`: vorremmo ottenere aeroporti che siano componenti aggiuntivi o che abbiano requisiti dello scenario di base, come piste di rullaggio, parcheggi e altro ancora. Tutto il resto è barboso.
 2. "Procedure": mostra solo gli aeroporti che dispongono di procedure per ravvivare un pò 'l'avvicinamento.
 3. Deseleziona `Militare` e` Chiuso` \ (fai clic due volte sulle caselle di controllo \): questo restituirà solo gli aeroporti civili ed eviterà gli aeroporti che hanno tutte le piste chiuse.
 4. Controlla anche "Avgas" in modo da poter fare il pieno per il nostro viaggio di ritorno e non aver bisogno di carburante per una pista vicina.
 5. Nella casella combinata "Qualsiasi o nessuna rampa" selezionare "Almeno GA piccola". Ciò includerà solo gli aeroporti che abbiano nei  risultati parcheggi adeguati.
 6. Nella casella combinata `qualsiasi superficie` selezionare` qualunque che sia dura` per evitare che gli aeroporti abbiano solo piste a superficie morbida.
 7. Seleziona una lunghezza minima della pista di 2.500 piedi per il tuo aereo nel campo `Piste:` `Min:`.

 Vedi anche [Finestra ancorata di ricerca - Aeroporti e radioaiuti] (SEARCH.md).

 Puoi anche limitare la lunghezza massima della pista se stai cercando una piccola sfida di atterraggio, ma non ora.

 Il risultato della ricerca cambia al volo mentre si eseguono tutte queste regolazioni, sebbene non ci siamo ancora:

 * Seleziona `Distanza:` per attivare la ricerca spaziale.
 * Modifica la distanza massima in 600 e il minimo in 400 miglia nautiche \ (per evitare salti brevi \). La tabella dei risultati verrà ora aggiornata con un piccolo ritardo poiché la ricerca della distanza è più complessa.
 * Per trovare solo gli aeroporti a nord della tua posizione, seleziona "Nord" nella casella combinata "Qualsiasi direzione". Si noti che il risultato della ricerca viene ordinato per distanza con l'aeroporto più vicino per primo.
 * Scegli un aeroporto per il tuo viaggio. Usiamo `Wick (EGPC)` per questa guida.

 *! [Cerca destinazione] (../ images / tutorial / ifrsearchdest.jpg)
 * Fare clic destro su Wick nella tabella dei risultati.
 * Seleziona "Mostra informazioni"! [Mostra informazioni] (../ images / icons / globals.png). Questo riempirà le schede nella finestra ancorata "Informazioni".
 * Seleziona la scheda "Meteo" e cerca la direzione del vento per avere un'idea della pista di atterraggio prevista. Avvia AS16 o Active Sky Next se li stai usando.

 Per questa guida supponiamo che i venti favoriscano la pista 13.

 Vedi anche [Meteo] (WEATHER.md).

 ### Seleziona una procedura di avvicinamento {# guida-ifr-seleziona-avvicinamento}

 Selezioneremo una procedura di avvicinaemnto ora:

 * Torna al risultato della ricerca.
 * Fare nuovamente clic con il tasto destro del mouse sull'aeroporto Wick. Seleziona "Mostra Procedure"! [Mostra Procedure] (../ images / icons / approach.png). Verrà visualizzata la scheda di ricerca della procedura.
 * Scegli `Runway 13` nella casella combinata` tutte le piste` per vedere solo gli avvicinamenti per la 13.
 * Seleziona `Espandi tutto` nel menu contestuale per vedere anche le transizioni per ciascun avvicinamento.
 * Scegli `Avvicinamento VORDME 13 FD13` usando` Transizione (tutta) WIK10` poiché prevediamo di atterrare sulla pista 13 e arrivare da sud.

 L'etichetta superiore nella ricerca della procedura mostra `Wick (EGPC) Avvicinamento VORDME 13 FD13 Transizione (tutta) WIK10` per l'avvicinamento selezionato e / o la transizione. Puoi anche vedere un'anteprima sulla mappa.

 ! [Albero di ricerca procedure] (../ images / tutorial / ifrprocselect.jpg)

 Fare clic con il tasto destro sulla transizione e selezionare "Mostra avvicinamento e transizione sulla mappa"! [Mostra avvicinamento e transizione sulla mappa] (../ images / icons / showonmap.png). Questo centrerà la procedura sulla mappa. È possibile passare il mouse sopra i waypoint dell'avvicinamento per visualizzare ulteriori informazioni in un suggerimento. È inoltre possibile fare clic sulle parti nella struttura della procedura per visualizzare i rispettivi punti iniziale e finale.

 ! [Anteprima procedura] (../ images / tutorial / ifrprocpreview.jpg)

 La procedura sembra sufficientemente complicata da presentare un avvicinamento interessante.

 Ulteriori informazioni sulla ricerca delle procedure: [Finestra ancorata di ricerca - Procedure] (SEARCHPROCS.md). Vedi anche [Procedure] (APPROACHES.md) per informazioni generali sulle procedure.

 Se ti piace quello che vedi, fai di nuovo clic con il tasto destro sulla transizione e seleziona "Usa EGPC, avvicinamento e Transizione come Destinazione"! [Usa EGPC e Avvicinamento e Transizione come Destinazione] (../ images / icons / routeadd.png).

 Questo farà due cose:

 1. Aggiungi Wick come aeroporto di destinazione al piano di volo. Qualsiasi destinazione precedente nel piano di volo verrà sostituita.
 2. Aggiungi l'avvicinamento e la sua transizione al piano di volo. Le parti della procedura usano un colore blu scuro e le parti dell' avvicinamento mancate usano un colore rosso scuro nella tabella del piano di volo. Il piano di volo lungo il tragitto è nero. Ancora una volta, qualsiasi procedura precedente viene sostituita con questa nuova.

 ** Informazioni sull'aggiunta di transizione e avvicinamenti: ** Avvicinamenti e transizioni sono strettamente correlati, come è già indicato dalla struttura ad albero nella scheda di ricerca della procedura. È possibile aggiungere un avvicinameto da solo, ma una transizione appartiene sempre a un avvicinamento.

 Devi selezionare la transizione per aggiungere o mostrare sia l'avvicinamento che la transizione.


 ### Calcola un piano di volo {# guida-ifr-calcola-piano di volo}

 Ora abbiamo l'aeroporto di partenza, una procedura di avvicinamento e la destinazione tutti collegati da una linea. La prossima è la parte in rotta del piano di volo:

 * Impostare `IFR` come tipo di piano di volo nella finestra ancorata` Piano di volo`. Ciò consente al calcolo automatico del piano di volo di regolare l'altitudine della crociera.
 * Fai clic su `Piano di volo` - & gt; "Calcola bassa altitudine"! [Calcola bassa altitudine] (../ images / icons / routelow.png) per iniziare il calcolo automatico del piano di volo per le aerovie Victor. Il calcolo creerà una rotta dal tuo aeroporto di partenza al fix iniziale della transizione.

 L'altitudine di crociera del piano di volo viene regolata automaticamente in base alla regola emisferica \ (la regola può essere modificata in `Strumenti` - & gt;` Opzioni`! [Opzioni] (../immagine / icone / impostazioni.png) nella scheda ` Piano di volo` \), i limiti di altitudine delle aerovie e il tipo di piano di volo \ (`VFR` o` IFR` \). È possibile visualizzare l'altitudine minima per ciascun segmento delle aerovie nella tabella del piano di volo nella colonna "Restrizione".

 L'altitudine può anche essere regolata in base alla regola emisferica facendo clic su "Piano di volo" - & gt; "Regola l'altitudine del piano di volo"! [Regola l'altitudine del piano di volo] (../ images / icons / routeadjustalt.png).

 Ora l'altitudine minima di 16.000 piedi è un po 'troppo alta.

 Pertanto, prova un metodo di calcolo alternativo che limiti la tua altitudine di crociera:

 * Inserisci 10.000 piedi nel campo "Altitudine del piano di volo".
 * Fai clic su `Piano di volo` - & gt; "Calcola in base alla determinata altitudine"! [Calcola in base alla determinata altitudine] (../ images / icons / routealt.png). Ciò comporterà un piano di volo che utilizza solo le aerovie con un'altitudine minima inferiore o uguale a 10.000 piedi. Si noti che è possibile ottenere un mix di aerovie Victor e Jet a seconda dell'altitudine utilizzata. Il calcolo potrebbe anche fallire se si imposta un'altitudine di crociera troppo bassa.

 ! [Calcola piano di volo] (../ images / tutorial / ifrcalcalt.jpg)

 Utilizza questo piano di volo per ora.

 Salva il piano usando `File` - & gt; "Salva piano di volo"! [Salva piano di volo] (../ images / icons / filesave.png). Il programma di solito trova la directory giusta per i piani di volo e fornisce un nome ragionevole per impostazione predefinita.

I waypoint della procedura di avvicinamento non vengono salvati nel piano di volo. Devi selezionare l'avvicinamento nel tuo GPS o FMC nel simulatore o pilotarlo con radio aiuti e un cronometro.

 Ciò che _Little Navmap_ salva nel PLN sono i nomi delle procedure che consentono al programma di ripristinare l'avvicinamento durante il caricamento del file PLN.

 L'etichetta superiore nella finestra ancorata del piano di volo riporta ora:

 `` `None
 Bembridge (EGHJ) Parking 1, Ramp GA Small to Wick (EGPC)
 Via WIK10 e VORDME FD13 fino alla pista 13
 517 nm, 5 h 10 m, bassa altitudine
 `` `
 Regola la velocità al suolo nella finestra ancorata del piano di volo in base all'aereo  utilizzato per ottenere una stima del tempo migliore.

 Il piano potrebbe avere un aspetto diverso, a seconda che si utilizzino aggiornamenti radioaiuti o dati di navigazione di serie.

 ! [Piano di volo] (../ images / tutorial / ifrflightplan.jpg)

 Ora puoi verificare se passi attraverso gli spazi aerei:

 * Abilita gli spazi aerei selezionando "Mappa" - & gt; `Airspaces` - & gt; `Show Airspaces`! [mostra spazi aerei] (../ images / icons / airspace.png) se non lo hai già fatto.
 * Controlla `Mappa` - & gt; `spazi aerei` - & gt; "All'altitudine di crociera del piano di volo"! [All'altitudine di crociera del piano di volo] (../ images / icons / airspaceroutealt.png) nel menu o nel pulsante del menu della barra degli strumenti.

 ! [Seleziona spazi aerei] (../ images / tutorial / ifrairspacesel.jpg)

 Questo mostrerà solo gli spazi aerei sulla mappa che sono rilevanti per la tua altitudine di crociera. Puoi anche selezionare "Solo sotto i 10000 piedi" per vedere tutti gli spazi aerei rilevanti nella fase di salita o discesa. Utilizza i suggerimenti sulla mappa per ottenere informazioni su spazi aerei come tipo, altitudine minima e massima.

 ! [Spazi aerei] (../ images / tutorial / ifrairspaces.jpg)


 ### Volando {# guida-ifr-volando}

 Apri la finestra di dialogo `Connetti` usando` Strumenti` - & gt; "Connessione al simulatore di volo"! [Connessione al simulatore di volo] (../ images / icons / network.png) e controlla se è selezionato "Connetti automaticamente". Abilita, in caso contrario.

 _Litte Navmap_ troverà il simulatore indipendentemente dal fatto che sia già stato avviato o che venga avviato in seguito. Fai clic su "Connetti".

 Vedi anche [Collegamento a un simulatore di volo] (CONNECT.md).

 Abilita `Mappa` - & gt; "centra aereo"! [Nuovo piano di volo] (../ images / icons / centeraircraft.png). La mappa salterà sull'aereo del simulatore e la manterrà centrata. Ciò accadrà solo se viene caricato un volo attivo, ovvero il simulatore non si trova nella schermata di apertura.

 Avvia il simulatore se non lo hai già fatto, carica il piano di volo e vola.

 ### Top of Descent {# Guida-ifr-top-of-descent}

 Un'indicazione del Top of Descend viene visualizzata sulla mappa e nel profilo altimetrico che mostra anche la distanza dal Top of Descend alla destinazione. Questo numero include la distanza dalle procedure di avvicinamento \ (esclusi i circuiti di attesa \).

 Si noti che le restrizioni  di altitudine non sono ancora considerate nel calcolo del Topo of Descend.

 Puoi cambiare la regola di discesa in `Strumenti` - & gt; `Opzioni`! [Opzioni] (../ images / icons / settings.png) nella scheda` Piano di volo`. L'impostazione predefinita è 3 miglia nautiche per 1.000 piedi.

 ! [ Indicatore Top of Descent] (../ images / tutorial / ifrtod.jpg)

 La scheda "Progresso" nella finestra ancorata "Aereo del simulatore" mostrerà la distanza del Top of Descend nella sezione "Progresso del piano di volo":

 | Progresso del piano di volo |
 | --- | --- |
 | Alla destinazione: | 74 nm |
 | Ora e data: | 21.05.17 12:33 UTC |
 | Ora locale: | 14: 33 CEST |
 | ** Da TOD a destinazione: ** | ** 64 nm ** |
 | ** al Top of Descend: ** | ** 10,1 nm ** |

 La sezione `Altitudine` mostrerà la deviazione del percorso verticale dopo aver superato il Topo of Descend:

 | Altitude |
 | --- | --- |
 | Indicato: | 5.090 ft |
 | Effettivo: | 5.051 ft |
 | sopra terra: | 5.051 ft |
 | Altitudine al suolo: | 0 ft |
 | ** Dev. Percorso verticale :******-511 ft sotto ▲ ** |

### Procedure di modifica {# guida-ifr-modifica-procedura}

 Ora il tempo è cambiato e richiede un avvicinamento alla pista 31:

 * Fare clic con il tasto destro del mouse sull'aeroporto di destinazione nella parte inferiore della tabella del piano di volo.
 * Scegli "mostra procedure"! [mostra Procedure] (../ images / icons / approach.png).
 * Quindi cambia il filtro della pista in `Pista 31`.
 * Espandi l'avvicinamento VORDME 31 per vedere la transizione.
 * Seleziona la transizione.

 L'etichetta nella parte superiore della finestra ora mostra "Avvicinamento VORDME 31 FD31 Transizione (tutta) CHINN".

 * Fare clic con il tasto destro sulla transizione selezionata.
 * Scegli `Usa EGPC e avvicinamento e transizione come destinazione`! [Usa EGPC e Avvicinamento e transizione come destinazione] (../ images / icons / routeadd.png) dal menu contestuale che sostituirà la procedura corrente nel tuo piano di volo con quello nuovo.

 L'etichetta superiore nella finestra ancorata del piano di volo riporta ora:

 `` `None
 Bembridge (EGHJ) Parking 1, Ramp GA Small to Wick (EGPC)
 Via CHINN e VORDME FD31 fino alla pista 31
 526 nm, 5 h 15 m, bassa altitudine
 `` `

 Per eliminare completamente una procedura:

 * Selezionare una parte della procedura nella tabella del piano di volo.
 * Fare clic con il pulsante destro del mouse e selezionare "Elimina tratta o procedura selezionata"! [Elimina tratta o procedura selezionata] (../ images / icons / routedeleteleg.png) per rimuovere l'intera procedura. In alternativa, premere il tasto `Canc`.

 Se l'ATC ti autorizza alla correzione iniziale della procedura:

 1. Elimina eventuali waypoint intermedi tra la posizione corrente del tuo aereo e la correzione iniziale della procedura: fai clic con il pulsante destro del mouse nella tabella del piano di volo e seleziona "Elimina tratta o procedura selezionata"! [Elimina tratta o procedura selezionata] (../immagine / icone /routedeleteleg.png) per tutti i waypoint tra la posizione corrente dell'aereo e la correzione iniziale o l'inizio della procedura. Evita di eliminare il tuo avvicinamento \ (puoi anche fare clic con il pulsante destro del mouse su un waypoint del piano di volo sulla mappa ed eliminarlo dal menu di scelta rapida \).
 3. Quindi fai clic con il pulsante destro del mouse sul tuo aereo sulla mappa e seleziona "Aggiungi posizione al piano di volo"! [Aggiungi posizione al piano di volo] (../ images / icons / routeadd.png).

 Ciò fornirà una connessione diretta dalla posizione corrente del tuo aereo all'inizio della procedura che puoi utilizzare per ottenere la rotta e la distanza dalla correzione iniziale.

 Sotto: dopo aver modificato la procedura di avvicinamento e aggiunto al piano di volo un waypoint definito dall'utente nella posizione dell'aereo. Ora otteniamo indicazioni di rotta e altitudine per una tratta diretta verso l'inizio della transizione \ (43 nm e 314 gradi di rotta magnetica \).

 ! [Avvicinamento modificato] (../ images / tutorial / ifrapproach.jpg)

 ### Andati persi {# guida-ifr-andati-persi}

 Consiglio di nascondere gli avvicinamenti persi sulla mappa deselezionando "Mappa" - & gt; "Mostra avvicinamenti persi"! [Mostra avvicinamenti persi] (../ images / icons / missed.png "Mostra avvicinamenti persi"). Questo aiuta a sgombrare la visualizzazione della mappa.

 * ** Se l'avvicinamento mancato non viene visualizzato: ** La finestra di avanzamento mostra distanza e tempo a destinazione. L'attivazione della tratta successiva \ (mostrata in colore magenta \) si interromperà se viene raggiunta la destinazione \ (ovvero la soglia della pista \), anche quando si supera la soglia.
 * ** Se viene mostrato il mancato avvicinamento e l'aeromobile supera la soglia della pista: ** Viene attivata la prima tratta dell'avvicinamento mancato e l'avanzamento del velivolo del simulatore visualizzerà la distanza rimanente al termine della procedura persa.
