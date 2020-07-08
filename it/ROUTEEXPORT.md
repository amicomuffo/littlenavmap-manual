
## Esportazione online del piano di volo {# volo-piano-online-esportazione}

Questa finestra di dialogo viene visualizzata quando si esporta un piano di volo per i client di rete online utilizzando le voci del menu di esportazione
[FPL \ (IvAp o X-IvAp \)] (MENU.md # flight-plan-formati-ivap) o [VFP \ (vPilot \)] (https://www.vatsim.net/pilots/software).

Alcuni campi di input potrebbero essere nascosti a seconda del formato.

I campi che contengono informazioni che non possono essere estratte dal piano di volo corrente vengono salvati tra le
sessioni \ (es. "Pilota in comando" o "Equipaggiamento").

Altri campi di input in questa finestra di dialogo vengono estratti dal piano di volo corrente. I campi possono essere regolati manualmente e non vengono salvati tra le sessioni.
Questi sono:

* `Regole di volo`: dal piano di volo corrente. `IFR` o` VFR` per VFP e `I` o` V` per FPL. Cambialo manualmente se necessario.
* `Tipo di aereo`: dall'attuale prestazione dell'aereo \ ([Aircraft Performance] (AIRCRAFTPERF.md) \).
* `Partenza`: primo waypoint nel piano di volo. \ ([Piano di volo - Finestra ancorata] (FLIGHTPLAN.md) \).
* `Destinazione`: ultimo waypoint nel piano di volo.
* `Rotta`: generata dai waypoints del piano di volo, vie aeree, SID e STAR. \ ([Descrizione rotta piano di volo] (ROUTEDESCR.md) \).
* "Altitudine di crociera": presa dal piano di volo. Altitudine di crociera in piedi.
* "velocità vera dell'aria": dalle attuali prestazioni della velocità in crociera dell'aeromobile.
* "Ora di partenza": utilizza l'ora UTC corrente come impostazione predefinita. Adattarlo se necessario.
* `Effettivo`: orario di partenza effettivo. Utilizza lo stesso tempo predefinito di cui sopra. Adattarlo se necessario.
* `In rotta`: tempo di viaggio calcolato dal piano di volo e dalle prestazioni attuali dell'aereo.
* `Autonomia`: utilizza lo stesso valore predefinito di cui sopra. Adattarlo se necessario.

Pulsanti ###

* `OK`: salva i campi rilevanti per la sessione successiva e apre la finestra di dialogo 'Salva con nome'.
* `Annulla`: ignora tutte le modifiche e chiude la finestra di dialogo.
* `Resetta`: Annulla tutte le modifiche apportate dall'apertura della finestra di dialogo.
* `Aiuto`: mostra questa pagina di aiuto in linea.

! [Finestra di dialogo di esportazione online del piano di volo] (../ images / routeexport.jpg "Finestra di dialogo di esportazione online del piano di volo")

_ ** Immagine sopra: ** Finestra di dialogo di esportazione online del piano di volo per VATSIM vPilot._
