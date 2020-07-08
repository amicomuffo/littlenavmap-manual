
## Reti online {# online-reti}

La funzionalità di rete online consente di connettersi a [VATSIM] (https://www.vatsim.net), [IVAO] (https://ivao.aero) o altre reti online che pubblicano file `whazzup.txt`. Questo copre la visualizzazione di informazioni per centri di controllo, client e server sulla mappa.

Informazioni specifiche della rete come nomi utente, centri di controllo / torri attive, frequenze, piani di volo e molto altro, vengono visualizzati in tutto il mondo senza limiti, come la distanza dall'aereo dell'utente.

** Si noti che tutte le schede della finestra, le voci di menu e i pulsanti della barra degli strumenti correlati sono nascosti se le reti online sono disabilitate, che è l'impostazione predefinita. **

L'accesso alle reti online può essere abilitato e configurato nella finestra di dialogo `Opzioni` nella scheda [Volare online] (OPTIONS.md # volo online). Sono disponibili opzioni predefinite per le reti ben note e configurabili liberamente.

! [Panoramica delle funzioni di rete online] (../ images / online_overview.jpg "Panoramica delle funzioni di rete online")

_ ** Immagine sopra: ** Una panoramica di tutte le finestre, schede e pulsanti relativi alla rete online ._

### simulatori e aeromobili duplicati online {# online-reti-duplicati}

_Little Navmap_ recupera i dati dalle reti online utilizzando un intervallo di tre minuti a seconda delle impostazioni e della rete.

Il programma recupera anche i velivoli AI o multiplayer dal simulatore che vengono aggiornati circa due volte al secondo. Questi aeromobili vengono immessi nel simulatore dai vari client online in modo che siano visibili all'interno del simulatore.

Pertanto, l'aereo utente e altri aeromobili del client possono apparire duplicati sulla mappa.

_Little Navmap_ tenta di rimuovere questi duplicati abbinando la registrazione dell'aereo \ (simulatore \) e il nominativo del client \ (rete online \). L'aereo può apparire duplicato se questa informazione non è disponibile, come nel caso di X-Plane. Fai riferimento alla configurazione dello strumento della propria rete online su come aggiungere queste informazioni.


### Visualizzazione mappa {# online-reti-mostra mappa}

#### Client {# online-reti-client}

I client della rete online o i loro aereo vengono visualizzati sulla mappa usando il simbolo! [Online in volo] (../ images / icons / aircraft_online.png). Ciò include l'aereo del simulatore riconosciuto come client di rete online.

L'aereo dell'utente viene sempre visualizzato utilizzando il giallo! [GA piccolo] (../ images / icons / aircraft_small_user.png) o un simbolo simile a seconda del tipo di aereo e del simulatore. Utilizza la voce di menu di scelta rapida della mappa "Mostra nella ricerca" per vedere il tuo aereo nell'elenco dei client online.

Le informazioni per gli aeromobili online sono visualizzate nella scheda "Client online" nella [Finestra ancorata informativa] (INFO.md).

Tutte le altre funzionalità come menu di scelta rapida, doppio clic, descrizioni comandi, punti salienti della mappa e altro, sono le stesse dell'altro aereo.

Vedi [Aerei e navi] (veicoli LEGEND.md #) nella legenda per tutti i simboli.

! [Aerei di rete online] (../ images / online_aircraft.jpg "Aerei di rete online")

_ ** Immagine sopra: ** Client / aeromobili della rete online nella scheda di ricerca, mappa, descrizione comandi e finestra informazioni ._


#### Centri di controllo {# online-reti-centri di controllo}

I centri di controllo online vengono visualizzati come spazi aerei circolari in _Little Navmap_ e offrono le stesse funzionalità degli altri spazi aerei \ (suggerimenti, informazioni e altro \). Possono essere abilitati separatamente dagli altri spazi aerei usando il pulsante! [Mostra spazi aerei di reti online] (../ images / icons / airspaceonline.png "Mostra spazi aerei di reti online") o la voce di menu [Mostra spazi aerei di rete online] (MENU. md # mostra-on-line-spazi aerei).

** Si noti che i cerchi non rappresentano gli spazi aerei reali e vengono utilizzati solo per indicare la presenza di un centro attivo, torre, terra o altra posizione. **

Informazioni dettagliate per i centri / gli spazi aerei online sono riportate nella scheda "Centri online" nella [Finestra ancorata d'informazione] (INFO.md).

Sono disponibili i seguenti generi e possono essere abilitati nei menu a discesa sulla barra degli strumenti dello spazio aereo o nel sottomenu [Airspaces] (MENUS.md # airspaces):

* ** Osservatore: ** La dimensione del cerchio è presa dal valore "Campo visivo" del centro.
* ** Informazioni sul volo \ (Centro di controllo \): ** Usa `Raggio visivo`.
* ** Delivery \ (autorizzazione \): ** Utilizza `Raggio visivo`.
* ** Terra: ** Mostra un cerchio con un diametro di 10 nm.
* ** Torre: ** cerchio da 20 nm.
* ** Avvicinamento: ** cerchio da 40 nm.
* ** ACC \ (Centro \): ** Usa `Raggio visivo`.
* ** Partenza: ** Usa `Raggio visivo`.

La dimensione delle forme del cerchio può essere modificata nel file di configurazione. Vedi [Centro reti online] (CUSTOMIZE.md # personalizza-centro-online).

! [Personalizza i centri di rete online] (../ images / online_center.jpg "Centro di rete online")

_ ** Immagine sopra: ** Centro di rete online / ATC nella scheda di ricerca, mappa, descrizione comandi e finestra informazioni ._

### Ricerca client di rete online {# ricerca-client}

### Ricerca centro di rete online {# ricerca-center}

La funzionalità dei filtri di ricerca in queste due schede e le tabelle dei risultati sono simili alla ricerca aeroportuale e radioaiuto. Vedi [cerca finestra ancorata] (SEARCH.md) per informazioni su filtri di ricerca, pulsanti e voci del menu contestuale.

### Ricerca server online {# ricerca-server}

Visualizza tutti i server online in una tabella e non ha funzionalità di ricerca. È possibile utilizzare il menu di scelta rapida per copiare parti della tabella dei risultati come l'indirizzo IP.
