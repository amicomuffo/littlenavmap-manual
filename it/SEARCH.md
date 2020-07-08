
##! [Cerca] (../ images / icons / searchdock.png "Cerca") Finestra ancorata di ricerca - Aeroporti e radioaiuti {# cerca-ancorata-finestra}

Le schede di ricerca aeroporto e radiaiuto contengono più file di filtri di ricerca che possono essere attivati ​​e disattivati ​​con il menu a discesa sul pulsante del menu! [Pulsante Menu] (../ images / icons / menubutton.png "Pulsante Menu") su in alto a destra.

Il menu a discesa prefissa le voci del menu con un indicatore di cambiamento `*` per mostrare che la relativa riga del filtro ha delle modifiche. Puoi usarlo per scoprire perché una ricerca non fornisce i risultati attesi.

** Se non si ottengono i risultati previsti o nessun risultato, utilizzare la voce di menu `Ripristina ricerca` o premere` Ctrl + R` per cancellare tutti i criteri di ricerca. **

I filtri sono definiti da vari controlli che sono per lo più autoesplicativi. Solo i filtri di testo e le caselle di controllo a tre stati come "illuminato", "Avvicinamento" o "Chiuso" necessitano di alcune osservazioni aggiuntive sotto.

Tutti i filtri possono essere usati insieme dove tutte le condizioni devono essere soddisfatte \ (`e` operate \). Tutti i filtri tranne il filtro di ricerca della distanza vengono applicati immediatamente. La ricerca della distanza viene applicata dopo un breve ritardo per ogni modifica.

Una descrizione comandi sul pulsante di aiuto blu in alto a destra, mostra informazioni sulla ricerca.

### Filtri di testo {# filtri di testo}

Lo standard è cercare voci che iniziano con il testo inserito.

Il segnaposto `*` sta per qualsiasi testo. Una volta che un "*" è incluso nel periodo, la ricerca standard \ (inizio corrispondenza del testo \) non viene più utilizzata. In tal caso potrebbe essere necessario aggiungere un `*` alla fine del periodo di ricerca e ottenere il risultato previsto.

La ricerca viene annullata \ (trova tutte le voci che non corrispondono \) se il primo carattere in una casella di ricerca è un `-`.

Si noti che tutto quanto sopra non si applica ai campi numerici come `Piste: Min` o` Altitudine: Max`.

### Caselle di controllo tre stati {# tre-stati-caelle di controllo}

Questi sono utilizzati per filtrare gli aeroporti in base alla presenza di determinate strutture o proprietà.

Di seguito sono riportati gli stati come sono mostrati in Windows 10:

* ** Casella nera: ** La condizione è ignorata.
* ** Selezionato: ** La condizione deve corrispondere.
* ** Casella vuota: ** La condizione non deve corrispondere.

I colori e l'aspetto di queste caselle di controllo variano in base al tema e al sistema operativo. Quindi al posto del grigio potrebbe essere usato un altro colore \ (riempimento rosso su Linux o un `-` per macOS \).

### Ricerca a distanza {# distanza-ricerca}

Questa funzione consente di combinare tutte le altre opzioni di ricerca con una semplice ricerca spaziale.

La casella di controllo "Distanza" deve essere selezionata per abilitare questa ricerca. Il risultato includerà solo aeroporti o radioaiuti che si trovano all'interno della gamma minima e massima di miglia nautiche dal centro di ricerca. Ciò ti consente di cercare rapidamente una destinazione che si trova all'interno del raggio del tuo aereo e soddisfa altri criteri come avere piste illuminate e carburante.

Il centro per la ricerca della distanza è evidenziato dal simbolo [Simbolo ricerca distanza] (../ images / icons / distancemark.png "Simbolo ricerca distanza").

Per limitare ulteriormente la ricerca, è possibile selezionare una direzione \ (Nord, Est, Sud e Ovest \).

Controllare il menu a discesa per l'indicatore di modifica `*` e i campi di ricerca per l'eventuale testo rimanente se la ricerca della distanza non fornisce risultati inaspettati o. Usa `Ripristina ricerca` nel menu contestuale della tabella dei risultati o premi` Ctrl + R` per cancellare tutti i criteri di ricerca.

! [Ricerca a distanza complessa] (../ images / complexsearch.jpg "Ricerca a distanza complessa")

_ ** Immagine sopra Una ricerca complessa a distanza: ** Trova tutti gli aeroporti entro una distanza compresa tra 200 e 400 miglia nautiche da Francoforte \ (EDDF \). Gli aeroporti dovrebbero avere un rating superiore a 0 e avere almeno una pista illuminata. Sono esclusi gli aeroporti militari e quelli chiusi. Gli aeroporti risultanti vengono evidenziati sulla mappa selezionandoli nella tabella dei risultati della ricerca.

! [Ricerca complessa di scenari] (../ images / complexsearch2.jpg "Ricerca complessa di scenari")

_ ** Immagine sopra Una ricerca complessa di scenari: ** Questo esempio mostra come trovare scenari aggiuntivi specifici usando il campo di ricerca "Percorso scenario". Questo mostra tutti gli aeroporti dello scenario aggiuntivo Orbx Nuova Zelanda Isola del Sud che hanno le piste illuminate._

### Visualizza tabella risultati ricerca {# ricerca-risultati-tabella-vista}

Tutti gli elementi selezionati nella vista tabella verranno evidenziati sulla mappa usando un cerchio nero / giallo. Vedi [punti salienti] (MAPDISPLAY.md # punti salienti) per maggiori informazioni. È possibile la selezione multipla usando `Shift + Click` o` Ctrl + Click`.

#### Intestazione {# tabella-vista}

L'intestazione di tutte le viste della tabella consente la seguente alterazione:

* ** Fai clic sull'angolo in alto a sinistra dell'intestazione della colonna: ** Seleziona tutte le righe risultanti.
* ** Fai clic sull'intestazione di una colonna: ** Ordina crescente o decrescente \ (solo per le tabelle dei risultati di ricerca - non per la tabella dei piani di volo \).
* ** Fare clic e trascinare sull'intestazione della colonna: ** Cambia ordine della colonna.
* ** Doppio clic sul bordo della colonna: ** Adatta automaticamente le dimensioni della colonna al contenuto.
* ** Fare clic e trascinare sul bordo della colonna: ** Cambia larghezza colonna.
* ** Fai clic nello spazio vuoto sotto tutte le righe: ** Deseleziona tutte le voci e rimuovi i punti salienti.

Quanto sopra, si applica a tutte le viste delle tabelle nel programma e in parte anche alla vista ad albero della ricerca della procedura.

Il programma salva l'ordinamento, le larghezze delle colonne e le posizioni fino a quando nel menu contestuale non viene selezionato "Ripristina vista".

! [ricerca dell'aeroporto, Tabella dei risultati ] (../ images / airportearchtable.jpg "ricerca dell'aeroporto, Tabella dei risultati")

_ ** Immagine sopra: ** Tabella dei risultati di ricerca dell'aeroporto. Tutte le opzioni di ricerca aggiuntive vengono nascoste utilizzando il menu a discesa del pulsante di menu in alto a destra._

! [Tabella dei risultati della ricerca radioaiuto] (../ images / navaidsearchtable.jpg "Tabella dei risultati della ricerca radioaiuto")

_ ** Immagine sopra: ** Ricerca radioaiuto limitata alla regione ICAO * `LI` * \ (Italia \) e stazioni VOR, VORTAC e TACAN che hanno un raggio di oltre 100 miglia nautiche ._

#### Clic del mouse {# mouse-clicks-0}

Un doppio clic su una voce nella vista tabella mostra un diagramma dell'aeroporto o ingrandisce il radioaiuto. Inoltre, i dettagli sono mostrati nella finestra ancorata "Informazioni". Un singolo clic seleziona un oggetto e lo evidenzia sulla mappa usando un cerchio nero / giallo.


### Pulsanti in alto {# pulsanti in alto}

####! [Ripristina ricerca] (../ images / icons / clear.png "Ripristina ricerca") Ripristina ricerca {# ripristina -ricerca}

Cancella i filtri di ricerca e mostra nuovamente tutte le voci nella vista tabella dei risultati della ricerca.

####! [Cancella selezione] (../ images / icons / clearselection.png "Cancella selezione") Cancella selezione {# cancella-selezione}

Deseleziona tutte le voci nella tabella e rimuove anche eventuali anelli dei punti salienti dalla mappa.

####! [Help] (../ images / icons / help.png "Help") Aiuto {#aiuto}

Mostra una guida rapida nella descrizione comandi e apre questo capitolo della guida nel browser predefinito al clic.

####! [Pulsante Menu] (../ images / icons / menubutton.png "Pulsante Menu") Pulsante Menu {#menu}

Pulsante del menu a discesa che consente di nascondere o mostrare le opzioni di ricerca.

Il menu a discesa prefigura le voci di menu con un indicatore di cambio `*` per mostrare che la relativa riga del filtro ha delle modifiche. Puoi usarlo per scoprire perché una ricerca non fornisce i risultati previsti.

### Risultato della tabella di ricerca del menu contestuale  {# ricerca-risultato-tabella-vista-contestuale-menu}

####! [Mostra informazioni] (../ images / icons / globals.png "Mostra informazioni") Mostra informazioni {# mostra-informazioni-0}

Come il [Menu contestuale della mappa] (MAPDISPLAY.md # menu contestuale della mappa).

####! [mostra Procedure] (../ images / icons / icons.png "mostra Procedure") mostra Procedure {# mostra-procedure}

Apre la scheda di ricerca delle procedure della finestra ancorata di ricerca e visualizza tutte le procedure per l'aeroporto.

Vedere [Ricerca procedure] (SEARCHPROCS.md) per ulteriori informazioni.

####! [Mostra sulla mappa] (../ images / icons / showonmap.png "Mostra sulla mappa") Mostra sulla mappa {# mostra-sulla-mappa}

Mostra il diagramma dell'aeroporto o ingrandisce il radioaiuto sulla mappa.

####! [Filtra per voci incluso] (../ images / icons / filter-add.png "Filtra per voci incluso")! [Filtra per voci escluse] (../ Immagini / icone / filtro-rimuovi. png "Filtra per voci escluse") Filtra per voci incluso / escluso {# filtro per voci-incluso-escluso}

Utilizza il testo del campo sotto il cursore e imposta il filtro di ricerca per una ricerca inclusa o esclusa. Questo è abilitato solo per le colonne di testo.

####! [Ripristina ricerca] (../ images / icons / clear.png "Ripristina ricerca") Ripristina ricerca {# ripristina-ricerca}

Cancella i filtri di ricerca e mostra nuovamente tutte le voci nella tabella di rcerca dei risultati.


####! [Mostra tutto] (../ images / icons / load-all.png "Mostra tutto") Mostra tutto {# mostra-tutto}
La vista tabella non mostra inizialmente tutte le voci per giustificazioni delle prestazioni. Questa voce di menu consente di caricare e mostrare l'intero risultato della ricerca. La vista torna al numero limitato di voci dopo che un filtro di ricerca è modificato o l'ordinamento è cambiato.   
 Il numero di tutte le voci visibili e selezionate è mostrato nella parte inferiore della scheda.

Tieni presente che la visualizzazione di tutti i radioaiuti e gli aeroporti può richiedere del tempo, soprattutto se vengono evidenziati sulla mappa quando si seleziona tutto nei risultati di ricerca. Il programma non si arresta in modo anomalo ma richiede alcuni secondi per evidenziare tutto sulla mappa.

####! [Mostra anelli di portata] (../ images / icons / rangerings.png "Mostra anelli di portata") Mostra anelli di portata {# mostra-portata-anelli-0}

####! [Mostra intervallo di radioaiuto] (../ images / icons / navrange.png "Mostra intervallo di radioaiuto") Mostra intervallo di radioaiuto {# mostra-radioaiuto-portata-0}

####! [Rimuovi tutti gli anelli di portata e le misure della distanza] (../ images / icons / rangeringsoff.png "Rimuovi tutti gli anelli di portata e le misure della distanza") Rimuovi tutti gli anelli di portata e le misure della distanza {# rimuovi-tutti-portata- anelli-e-distanza-misure-0}

####! [Imposta come partenza piano di volo] (../ images / icons / airportroutedest.png "Imposta come partenza piano di volo") Imposta come partenza piano di volo {# imposta-come-volo-piano-partenza-0}

####! [Imposta come destinazione del piano di volo] (../ images / icons / airportroutestart.png "Imposta come destinazione del piano di volo") Imposta come destinazione del piano di volo {# imposta-come-volo-piano-destinazione-0}

####! [Aggiungi posizione al piano di volo] (../ images / icons / routeadd.png "Aggiungi posizione al piano di volo") Aggiungi posizione al piano di volo {# aggiungi-posizione-al-volo-piano-0}
####! [Aggiungi posizione al piano di volo] (../ images / icons / routeadd.png "Aggiungi posizione al piano di volo") Aggiungi posizione al piano di volo {# aggiungi-posizione-al-volo-piano-0}

come il [Menu contestuale della mappa] (MAPDISPLAY.md # menu contestuale della mappa).

####! [Copia] (../ images / icons / copy.png "Copia") Copia {#copia}
Copia le voci selezionate in formato CSV negli Appunti. Questo considererà le modifiche alla vista tabella come l'ordine delle colonne e l'ordinamento. Il CSV include una riga di intestazione.

#### Seleziona tutto {# seleziona-tutto}

Seleziona tutte le voci visibili. Per selezionare tutte le voci disponibili è necessario utilizzare prima la funzione "Mostra tutto".

####! [Cancella selezione] (../ images / icons / clearselection.png "Cancella selezione") Cancella selezione {# cancella-selezione}

Deseleziona tutte le voci nella tabella e rimuove anche gli anelli di evidenziazione dalla mappa.

####! [Ripristina vista] (../ images / icons / cleartable.png "Ripristina vista") Ripristina vista {# ripristina-vista}

Ripristina il criterio di ordinamento, l'ordine delle colonne e la larghezza delle colonne ai valori predefiniti.

####! [Imposta centro per ricerca della distanza] (../ images / icons / mark.png "Imposta centro per ricerca della distanza") Imposta centro per ricerca della distanza {# imposta-centro-per-distanza-ricerca-0}

Come il [Menu contestuale della mappa] (MAPDISPLAY.md # menu contestuale della mappa).
