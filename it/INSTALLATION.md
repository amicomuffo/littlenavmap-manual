## Installazione  {#installation}

`Il testo evidenziato` viene utilizzato per indicare i nomi di finestre, menu, pulsanti, file o directory.

*Little Navmap* per Windows è un'applicazione a 32 bit ed è stato testato con Windows 7, Windows 8, Windows 10 (32 bit e 64 bit).

Le versioni macOS e Linux sono entrambe a 64 bit e sono state testate con macOS Sierra e Ubuntu Linux.


### In aggiornamento
Eliminare tutti i file installati di una precedente versione di Little Navmap prima di installare una nuova versione. Tutti i file dal precedente archivio ZIP può essere eliminato poiché le impostazioni sono memorizzate in directory separate \(eccetto[custom map themes](MAPTHEMES.md)\). In ogni caso non unire le directory di installazione.
on è necessario eliminare la vecchia directory delle impostazioni. Il programma è scritto in modo tale da poter funzionare sempre con i vecchi file di impostazioni.


### Finestre
L'installazione di of _Little Navmap_ does not change any registry entries \(in Windows\) non modifica alcuna voce del registro \(in Windows\) e comporta quindi una semplice copia dei file non è richiesto un programma di installazione o installatore.

Non estrarre l'archivio nella directory `c:\Program Files\` or `c:\Program Files (x86)\`  poiché ciò richiede privilegi amministrativi. Windows mantiene il controllo di queste directory, pertanto potrebbero verificarsi altri problemi come la sostituzione o file cancellati.

Estrai l'archivio Zip in una directory come `c:\Little Navmap`. Quindi avvia il programma facendo un doppio click su `littlenavmap.exe`. See [First Start](INTRO.md#first-start) per ulteriori informazioni sul primo avvio dopo l'installazione.

In qualche caso devi installare  [Update for Visual C\+\+ 2013 and Visual C\+\+ Redistributable Package](https://support.microsoft.com/en-us/help/3179560/update-for-visual-c-2013-and-visual-c-redistributable-package). Installa entrambe le versioni a 32 e 64 bit.
Di solito questa è già installata poiché molti altri programmi lo richiedono.

_Little Navmap_ è un'applicazione a 32 bit ed è stato testato con Windows 7, Windows 8 e Windows 10 (32 bit e 64 bit).
XP non è supportato.


#### Simulatori diversi da FSX SP2 {#other-simulators-than-fsx-sp2}

Questo programma è stato compilato utilizzando la semplice versione\(no Acceleration\) di SimConnect 10.0.61259.0 di FSX SP2.

Potrebbe essere necessario installare una versione precedente di SimConnect se si utilizza_Prepar3D_ or _FSX Steam Edition_. Se non sei sicuro di questo, prova semplicemente Little Navmap. Se fallisce con un messaggio di errore, seguire le istruzioni seguenti:

_**Prepar3D**_: Nella stessa directory di `Prepar3D.exe` è presente una directory `redist\Interface` \(normalmente `C:\Program Files (x86)\Lockheed Martin\Prepar3D v3\redist\Interface`\). Sono disponibili più versioni obsolete di SimConnect. Devi installare `FSX-SP2-XPACK.msi` per _Little Navmap_.

_**FSX Steam Edition**_: l'installazione aggiunge la directory `C:\Program Files (x86)\Steam\SteamApps\common\FSX\SDK\Core Utilities Kit\SimConnect SDK\LegacyInterfaces` in cui è possibile trovare le interfacce obsolete di SimConnect.

### macOS

Estrarre il file ZIP e copia l'applicazione  `Little Navmap` nella cartella`Applications` o in qualsiasi altra cartella.

### Linux

estrarre l'archivo tar in qualsiasi posto e avvia e usa l'eseguibile the `littlenavmap.sh` per far partire il programma da un terminale:

`bash ./littlenavmap.sh`

### X-Plane

*Little Navmap* può connettersi a Xplane usanod il pluging *Little Xpconnect* X-Plane che deve essere installato.

Il lugin *Little Xpconnect* è inclsuo nell'archivio *Little Navmap* ma può anche essere scaricato separatamente. Vedi il
`README.txt` nella directory `Little Xpconnect` per le istruzioni di installazione.

The plugin a 64-bit è disponibile solo per Windows, macOS and Linux.

### Programmi aggiuntivi

L'archivio scaricato *Little Navmap* contiene due directory addizionali \(or applications for macOS\):

`Little Navconnect`:  Una copia completa del programma che consente le connessioni del simulatore di volo remoto per FSX, P3D and 
X-Plane.

`Little Xpconnect`:  Questo è il plugin a 64-bit plugin necessario per consentire a *Little Navmap* o *Little Navconnect* di connettersi a  X-Plane.
