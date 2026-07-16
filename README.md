# Simulatore Affitto vs Vendita — Via Solferino 4, Novara

Simulatore interattivo (HTML statico, zero dipendenze) per confrontare i due scenari sull'immobile di via Solferino 4 a Novara: **2 unità ristrutturate (80 + 110 m²) + posto auto in cortile**.

## Uso

Apri `index.html` nel browser. Tutti i parametri sono modificabili e i risultati si ricalcolano in tempo reale:

- **Immobile**: superfici, €/m², valore posto auto
- **Vendita**: provvigione + IVA, spese fisse, regime plusvalenza (esente / tassata 26% con valore di carico e costi ristrutturazione), rendimento del reinvestimento
- **Affitto**: canoni per unità, regime fiscale (cedolare 21%, concordato 3+2 al 10% con IMU ridotta, IRPEF), IMU, manutenzione, assicurazione, sfitto/morosità, agenzia, rivalutazione canoni
- **Confronto pluriennale**: orizzonte, apprezzamento immobile, vendita a fine periodo nello scenario affitto

Output: KPI (valore, netto vendita, affitto netto anno 1, rendimento), verdetto con break-even, grafico del patrimonio nel tempo (con tooltip e vista tabella), metodologia esplicita.

## Note

- Valori nominali, non attualizzati per inflazione.
- Simulazione indicativa: plusvalenza, rendite catastali e aliquote IMU vanno verificate con il commercialista.
- Dati di mercato di riferimento (metà 2026): Novara centro storico ~€2.100–2.380/m² vendita, ~€10,5/m²/mese affitto (Immobiliare.it, mercato-immobiliare.info).
