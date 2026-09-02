# TurcoFantacalcio V35 — Audit Fix Completo

Versione verificata sul listone `Classic Relative(1).xlsx` del 02/09/2026.

## Database verificato
- 532 giocatori univoci
- 64 Portieri
- 188 Difensori
- 193 Centrocampisti
- 87 Attaccanti

## Correzioni principali
- sostituzione completa del vecchio database: niente più merge con giocatori obsoleti
- nuovo namespace localStorage per evitare dati V34 corrotti/stale
- asta nuova pulita, senza assegnazioni simulate precaricate
- sincronizzazione corretta tra tab P/D/C/A e lista mostrata
- corretto loop ricorsivo nel Coach strategico
- Coach, termometro, Target, MAX e alternative testati sui nuovi dati
- Rose Asta: slot live e rimozione assegnazione funzionanti
- vincoli di 3P/8D/8C/6A e riserva minima di 1 credito mantenuti
- % vittoria normalizzate a 100%
- pulsante `Ripristina Excel` in Gestione Fasce
- badge di integrità DB visibile in Asta Live

Per GitHub Pages, sostituire il file `index.html` del repository con quello presente in questa cartella.
