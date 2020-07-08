## Installazione {#installation}

"Testo evidenziato" viene utilizzato per indicare i nomi di finestre, menu, pulsanti, file o directory.

* Little Navmap * per Windows è un'applicazione a 32 bit ed è stato testato con Windows 7, Windows 8, Windows 10 \ (32-bit e 64-bit \).

Le versioni macOS e Linux sono entrambe a 64 bit e sono state testate con macOS Sierra e Ubuntu Linux.

### In aggiornamento
Elimina tutti i file installati di una versione precedente di _Little Navmap_ prima di installare una nuova versione. Tutti i file dell'archivio ZIP precedente possono essere eliminati poiché le impostazioni sono memorizzate in directory separate \ (tranne [temi mappa personalizzati] (MAPTHEMES.md) \). In ogni caso non unire le directory di installazione.

Non è necessario eliminare la vecchia directory delle impostazioni. Il programma è scritto in modo tale da poter funzionare sempre con vecchi file di impostazioni.

### Finestre
L'installazione di _Little Navmap_ non modifica alcuna voce di registro \ (in Windows \) e comporta una semplice copia di file, pertanto non è necessario un programma di installazione o di installazione.

Non estrarre l'archivio nella cartella `c: \ Programmi \` o `c: \ Programmi (x86) \` poiché ciò richiede privilegi amministrativi per alcune versioni di Windows. Windows mantiene il controllo di queste cartelle, pertanto potrebbero verificarsi altri problemi come file sostituiti o eliminati.

Estrai l'archivio Zip in una cartella come `c: \ Little Navmap`. Quindi avviare il programma facendo doppio clic su `littlenavmap.exe`. Vedere [Primo avvio] (INTRO.md # primo avvio) per ulteriori informazioni sul primo avvio dopo l'installazione.

In alcuni casi è necessario installare il [Aggiornamento per Visual C \ + \ + 2013 e Visual C \ + \ + Pacchetto ridistribuibile] (https://support.microsoft.com/en-us/help/3179560/update-for -Visual-c-2013-e-visual-c-ridistribuibile-package). Installa entrambe le versioni a 32 e 64 bit.
Di solito questo è già installato, poiché molti altri programmi lo richiedono.

_Little Navmap_ è un'applicazione a 32 bit ed è stata testata con Windows 7, Windows 8 e Windows 10 \ (32 bit e 64 bit \). Windows XP non è supportato.


#### Altri simulatori diversi da FSX SP2 {# altri-simulatori-diversi-fsx-sp2}

Questo programma è stato compilato usando semplicemente FSX SP2 \ (no Acceleration \) SimConnect versione 10.0.61259.0.

Potrebbe essere necessario installare una versione precedente di SimConnect se si utilizza _Prepar3D_ o _FSX Steam Edition_. Se non sei sicuro di ciò, prova semplicemente _Little Navmap_. Se fallisce con un messaggio di errore, seguire le istruzioni seguenti:

_ ** Prepar3D ** _: Nella stessa directory di `Prepar3D.exe` è presente una directory` redist \ Interface` \ (normalmente `C: \ Programmi (x86) \ Lockheed Martin \ Prepar3D v3 \ redist \ Interface` \ ). Sono disponibili più versioni datate di SimConnect. Devi installare `FSX-SP2-XPACK.msi` per _Little Navmap_.

_ ** FSX Steam Edition ** _: L'installazione aggiunge la cartella `C: \ Programmi (x86) \ Steam \ SteamApps \ common \ FSX \ SDK \ Core Utilities Kit \ SimConnect SDK \ LegacyInterfaces` dove puoi trovare il datato Interfacce SimConnect.

### Mac OS

Estrarre il file ZIP e copiare l'applicazione `Little Navmap` nella cartella` Applicazioni` o in qualsiasi altra cartella.

### Linux

Estrai l'archivio tar in qualsiasi posto e usa lo script della shell `littlenavmap.sh` per avviare il programma da un terminale:

`bash. / littlenavmap.sh`

### X-Plane

* Little Navmap * può connettersi solo a X-Plane usando anche il plugin * Little Xpconnect * X-Plane che deve essere installato.

Il plug-in * Little Xpconnect * è incluso nell'archivio * Little Navmap * ma può anche essere scaricato separatamente. Vedi il file `README.txt` incluso nella directory` Little Xpconnect` per le istruzioni di installazione.

Il plug-in a 64 bit è disponibile solo per Windows, macOS e Linux.

### Programmi aggiuntivi

L'archivio * Little Navmap * scaricato contiene due directory aggiuntive \ (o applicazioni per macOS \):

`Little Navconnect`: una copia completa del programma che consente le connessioni del simulatore di volo remoto per FSX, P3D e X-Plane.

`Little Xpconnect`: Questo è il plug-in a 64 bit necessario per * Little Navmap * o * Little Navconnect * per connettersi a X-Plane.
