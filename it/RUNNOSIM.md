## Esecuzione senza installazione di Flight Simulator {# esecuzione-senza-volo-simulatore-installazione}

Puoi usare `littlenavmap.exe` su tutti i computer, indipendentemente dal fatto che SimConnect o un simulatore di volo siano installati o meno.

Seguire questi passaggi se si desidera installare _Little Navmap_ su un computer che non contiene alcuna installazione del simulatore di volo, ad esempio, per una configurazione di rete, . Nessuna funzionalità è interessata tranne la capacità della connessione diretta che non è necessaria in questo caso.

Questo scenario viene in genere utilizzato quando ci si collega al simulatore di volo per monitorare l'avanzamento di un volo in remoto.

I piani di volo possono essere creati, caricati e salvati sul computer client. Devi solo assicurarti che questi vengano trasferiti sul computer del simulatore di volo usando condivisioni Windows o con altri mezzi.

Queste istruzioni si applicano anche ai computer Windows, macOS e Linux.

1. Installa _Little Navmap_ sia sul tuo computer in cui si vola che sul computer client senza simulatore.
2. Avviarlo sul computer in cui si vola e generare i database delle librerie di scenari. Vedere sopra [Finestra di dialogo Carica libreria scenari] (SCENERY.md) per ulteriori informazioni.
3. Selezionare "Menu principale" -> "Libreria scenari" -> "Mostra file di database" sul computer in cui si vola. Questo aprirà la directory contenente i file del database in un file manager come Windows Explorer o Apple Finder. Troverai uno o più file di database come `little_navmap_fsx.sqlite`,` little_navmap_p3dv3.sqlite` o `little_navmap_xp11.sqlite`.
4. Esci da _Little Navmap_ sul computer in cui si vola.
5. Avviare _Little Navmap_ sul client / computer remoto e selezionare `Scenery Library` ->` mostra files del database`.
6. Chiudere _Little Navmap_ sul computer client in modo da poter copiare i file del database.
7. Copia i file del database sul tuo computer client usando condivisioni di rete, chiavette USB o tutto quello che tu vuoi. Utilizzare le finestre del file manager aperte tra le procedure sopra.
8. Avviare _Little Navmap_ sul computer client. Il menu "Libreria scenario" dovrebbe contenere una voce per ciascun file di database copiato o nessuna voce se è stato copiato solo un file di database. Le icone dell'aeroporto dovrebbero essere visibili sulla mappa in entrambi i casi. ** Non è necessario ricaricare il database della libreria degli scenari poiché è stato appena copiato un file di database riempito completamente. **

Vedere [Connessione a un simulatore di volo] (CONNECT.md # connessione remota) per informazioni sulle impostazioni di rete.
