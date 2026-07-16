# simulatore-solferino — istruzioni per Claude

**Scopo**: simulatore HTML statico affitto-vs-vendita per l'immobile di via Solferino 4, Novara (2 unità ristrutturate 80+110 m² + posto auto, intestazione persona fisica, provenienza successione/donazione, ristrutturazione €300k senza bonus fiscali).

- **Repo**: `CryptoPannoz/simulatore-solferino` (pubblica)
- **Deploy**: GitHub Pages da `main` → https://cryptopannoz.github.io/simulatore-solferino/ (push su main = deploy automatico). Zero dipendenze, un solo file.
- **Clasp**: non usato.

## Convenzioni
- Tutto in un unico `index.html` (CSS + JS inline), interfaccia in italiano.
- La logica di calcolo è nella funzione `compute()`; la metodologia mostrata all'utente (sezione `<details>`) va tenuta allineata a ogni modifica dei calcoli.
- Palette grafico: serie Vendita blu / Affitto verde-acqua, con supporto dark mode via `prefers-color-scheme`.
