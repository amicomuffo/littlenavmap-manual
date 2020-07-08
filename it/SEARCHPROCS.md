#! [Cerca] (../ images / icons / searchdock.png "Cerca") Finestra ancorata di ricerca - Procedure {# ricerca-ancorata-finestra}

La scheda "Procedure" consente di visualizzare in anteprima e aggiungere procedure di avvicinamento e di partenza al piano di volo. Le procedure di un aeroporto selezionato sono organizzate in un albero che indica le dipendenze tra avvicinamenti e transizioni.

Si noti che i nomi SID e STAR sono limitati a 5 caratteri in FSX e P3D a causa di una limitazione nel formato di file BGL. I nomi vengono quindi leggermente modificati.

** Vedi il ** [** Procedure **] (APPROACHES.md # delete-selected-legs) ** capitolo di questo manuale per maggiori dettagli. **

Le tappe della procedura vengono visualizzate quando un nodo della procedura viene espanso nella struttura. Le procedure possono essere filtrate per pista e tipo.

Fare clic con il tasto destro su una procedura per ottenere più opzioni nel menu contestuale. Ciò consente il centraggio della mappa o l'aggiunta della procedura al piano di volo.

Utilizzare il menu di scelta rapida della tabella dei piani di volo per rimuovere le procedure come qualsiasi altro waypoint. Vedere [Elimina tappe o procedure selezionate] (FLIGHTPLAN.md # cancella-selzionate-tappe).

Le tratte della procedura sono evidenziate in rosso se uno o più radioaiuti non posono  essere stati risolti. Verrà visualizzata una finestra di avviso se si tenta di aggiungere questa procedura a un piano di volo.

! [Tabella di ricerca dei risultati del radioaiuto] (../ images / procedureearch.jpg "Tabella della ricerca dei risultati del radioaiuto")

_ ** Immagine sopra: ** Mostra una transizione e un avvicinamento RNAV. L'inizio e il punto finale di una tratta della transizione sono evidenziati sulla mappa.


### Albero delle procedure {# procedure-albero}

Le parti sono mostrate in blu scuro mentre quelle mancate di avvicinamento sono mostrate in colore rosso scuro.

Il testo in grassetto rosso indica un errore nella tratta. La procedura è incompleta e non dovrebbe essere utilizzata in un piano di volo.

* "Descrizione": descrizione della procedura o istruzione di volo per le tratte della procedura.
* `Corso ° M`: percorso magnetico per una tratta.
* `Dist. / Time`: distanza del tempo di volo per una tratta. I circuiti di attesa possono avere un tempo per le tratte in minuti o una distanza per le tratte in miglia nautiche.
* `Ident`: Identificativo del fix iniziale o nome della procedura. Correggi il nome per le tratte.
* "Restrizione": altitudine minima per il segmento delle aerovie in rotta, procedura di restrizione di alitudine o limite di velocità della procedura. Un `/` separa la limitazione di altitudine e velocità. Le seguenti restrizioni di altitudine esistono per le procedure:
  * ** Solo numero: ** Vola ad altitudine o velocità. Esempio: `5.400` o` 210`.
  * ** Prefisso ** `A`: vola o un'altitudine o una velocità superiore. Esempio: `A 1.800`.
  * ** Prefisso ** `B`: vola a un'altitudine o una velocità inferiore. Esempio: `B 10.000` o` B 220`.
  * ** Portata: ** Vola a un'altitudine superiore ad uno ed inferiore a due. Esempio: `A 8.000, B 10.000`.
  * ** Altitudine e limite di velocità: ** Valori separati da `/`. Esempio: `A 8.000, B 10.000 / B220`.
  * ** Solo limite di velocità: ** Un prefisso `/` indica nessuna altitudine ma una limitazione di velocità. Esempio: `/ B250`.
* `Osservazioni`: mostra il sorvolo, la direzione di svolta o il relativo radioaiuto per una parte della procedura.

### Pulsanti in alto {# pulsanti in alto}

#### filtro tipo \ (Tutte le procedure \) {# procedure-filtro-tipo}

Il filtro tipo non è disponibile per un database di serie FSX o P3D. È necessario un aggiornamento dei dati di navigazione per ottenere le procedure SID e STAR.

Questo filtro è sempre disponibile per un database X-Plane che contiene SID e STAR già nei dati di serie.

Il filtro tipo consente le seguenti selezioni:

* `Tutte le procedure`: SID, STAR e avvicinamenti
* `Procedure di partenza`: solo SID
* `Procedure di arrivo`: STAR e avvicinamenti
* `Solo avvicinamenti e transizioni`: nessuna SID e nessuna STAR

Le rispettive transizioni sono sempre mostrate.

#### Filtro pista \ (Tutte le piste \) {# procedura-filtro-pista}

Questo filtro è sempre disponibile e aiuta a trovare le procedure per una determinata pista di partenza o di arrivo.

####! [Cancella selezione] (../ images / icons / clearselection.png "Cancella selezione") Cancella selezione {# cancella-selezione}

Deseleziona tutte le voci nella tabella e rimuove anche eventuali punti salienti dalla mappa.


####! [Aiuto] (../ images / icons / help.png "Aiuto") Aiuto {#help}

Apre questo capitolo della guida nel browser predefinito.

### Menu contestuale dell'albero delle procedure {# procedura-contesto-menu}

####! [Mostra sulla mappa] (../ images / icons / showonmap.png "Mostra sulla mappa") Mostra sulla mappa {# procedura-mostra-sulla-mappa}

Centra la mappa sulla procedura selezionata.

####! [Inserisci nel piano di volo / Usa come destinazione / Usa come partenza] (../ images / icons / routeadd.png "Inserisci nel piano di volo / Usa come destinazione / Usa come partenza") Inserisci nel piano di volo / Usa come destinazione / Usa come partenza {# procedure-inserire}

Il testo e la funzionalità di questa voce del menu dipendono dal tipo di procedura selezionata e se la procedura dell'aeroporto è anche la partenza o la destinazione del piano di volo corrente.

Utilizzare il menu di scelta rapida della tabella del piano di volo per rimuovere le procedure. Vedere [Elimina tratte o procedure selezionate] (FLIGHTPLAN.md # cancella-selezionate-tratte).

La procedura corrispondente \ (avvcinamento, SID e STAR \) viene aggiunta o sostituita anche se viene selezionata una transizione.

`Inserisci ... nel piano di volo`:

Questa voce di menu aggiungerà la procedura selezionata al piano di volo corrente. Una procedura dello stesso tipo \ (SID, STAR o avvicinamento con o senza transizione \) verrà sostituita se già presente nel piano di volo.

"Usa ... come destinazione" o "Usa ... come partenza":

Ciò aggiungerà o sostituirà l'aeroporto di destinazione o di partenza e aggiungerà la procedura selezionata.

L'aeroporto di partenza o di destinazione viene aggiunto anche al piano di volo se il piano di volo è vuoto.

#### Espandi tutto Comprimi tutto

Espande tutte le procedure in modo che le loro tratte e transizioni vengano mostrate o comprimano l'albero.

####! [Ripristina ricerca] (../ images / icons / clear.png "Ripristina ricerca") Ripristina ricerca {# ripristina-ricerca}

Cancella i filtri di ricerca e mostra di nuovo tutte le procedure nella struttura.

####! [Cancella selezione] (../ images / icons / clearselection.png "Cancella selezione") Cancella selezione {# cancella-selezione}

Deseleziona la procedura attualmente selezionata e rimuove anche l'anteprima dalla mappa.

####! [Ripristina visualizzazione] (../ images / icons / cleartable.png "Ripristina vista") Ripristina vista {# ripristina-vista}

Ripristina l'ordine delle colonne e la larghezza delle colonne ai valori predefiniti.
