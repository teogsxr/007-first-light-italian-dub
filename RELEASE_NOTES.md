# Release notes v0.4

- Copertura pubblicata: `10569/16255` audio, pari al `65.02%`.
- Avanzamento cumulativo interno: `10594/16255`, pari al `65.17%`.
- Asset generati: `10569` WEM, `182.39 MiB` nel manifest mod.
- Pacchetto installabile: `007-first-light-italian-dub-v0.4.zip`, circa `235.76 MiB`.
- Aggiornata la pagina pubblica metodo/casting/video: https://teogsxr.github.io/007-first-light-italian-dub/
- Aggiornato il video gameplay WIP del capitolo 1 con la cattura del 22 giugno 2026 alle 14:11, dopo i fix mirati su apertura, HUD e sottotitoli.
- Prima pagina corretta: rimossa la GIF autoplay a bassa qualita, sostituita con poster statico cliccabile; la pagina pubblica usa il video OBS originale a qualita piena con player controllabile.
- Aggiunto al piano QA del capitolo 1 il controllo di ruolo audio: personaggio foreground, radio/comm e parlato di sottofondo non devono essere confusi nel giudizio di casting o nei report.
- Capitolo 1 in test gameplay ravvicinato: fix mirati su sottotitoli non allineati, testo adattato, timing e frasi troncate.
- Installer aggiornato con supporto append-relocation per `6` WEM che superano lo slot originale.
- Esclusi dal pacchetto pubblico `25` asset preserve/originali: sono tracciati nel cumulativo locale ma non ridistribuiti.
- Aggiornati manifest, progressi per personaggio e audit di ricostruzione WEM.
- Installer agnostico rispetto allo store: procedura guidata Steam/non Steam, `-GamePath`, `game_path.txt`, variabili ambiente e rilevamento da cartelle parent.
- Metodo source-first confermato: voce target approvata, audio sorgente come autorita di recitazione, QA ASR/timing/semantic/runtime/subtitle.
- Non include file originali del gioco.

## Note qualita

La v0.4 non e una localizzazione finale rifinita a mano: e una release WIP giocabile della pipeline automatica. La priorita resta preservare pathos, sincronizzazione, sottotitoli coerenti e sicurezza runtime. Alcune righe possono avere recitazione meno precisa o accento residuo se correggerli avrebbe danneggiato timing/testo o rallentato troppo la copertura.
