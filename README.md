# Nova Profile — Test DISC Comportamentale

Web app offline per calcolare il proprio profilo comportamentale basato sul modello DISC (Rosso, Giallo, Verde, Blu), ispirato al Nova Profile™.

## Caratteristiche

- **44 domande** basate sui tratti DISC classici (Dominance, Influence, Steadiness, Compliance)
- **Doppia misurazione**: Stile Naturale (come sei) e Stile Adattato (come ti comporti)
- **Scala verbale**: Mai → Raramente → A volte → Spesso → Sempre
- **Risultati visivi**: punteggi 0–100 per ogni colore, grafico a barre, colore dominante, interpretazione
- **Nessun server**: funziona offline, zero dipendenze, zero backend
- **Stampa/PDF**: pulsante per esportare il risultato
- **Mobile friendly**: responsive, funziona su iPhone/iPad/Android

## Come usare

1. Apri `index.html` in qualsiasi browser
2. Inserisci il nome (opzionale) o lascia vuoto per "Anonimo"
3. Rispondi a tutte le 44 affermazioni per la sezione **Naturale**
4. Rispondi alle stesse 44 affermazioni per la sezione **Adattato**
5. Visualizza il tuo profilo completo con punteggi e grafico

## Personalizzare le domande

Le domande sono configurabili nell'array `DOMANDE` all'interno di `index.html` (riga ~276).

Ogni domanda ha la struttura:

```js
{ id: 1, text: "Il testo della domanda", color: "rosso" }
```

I colori supportati sono: `rosso`, `giallo`, `verde`, `blu`.

## Tecnologia

- HTML5 + CSS3 + JavaScript (vanilla)
- Canvas API per il grafico
- Zero librerie esterne — funziona anche senza internet

## Nota

Questa web app è una ricostruzione indipendente basata sul modello DISC pubblico. Non è affiliata a Nova Profile™, Nova Global o Bloom Life.
