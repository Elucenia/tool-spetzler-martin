<!-- ELUCENIA technical documentation · spetzler-martin · it · no clinical/professional/rights approval -->

# Scala di Spetzler-Martin

[condizioni, fonti e autorizzazioni](https://elucenia.org/it/strumenti/spetzler-martin)

## Come usare

Usi lo strumento nel portale oppure apra index.html tramite un server HTTP locale. Selezioni la lingua, compili i campi ed esegua il calcolo.

## Dati di ingresso e unità

### Diametro massimo del nidus

`tamanho`

- `1` — \< 3 cm
- `2` — 3 a 6 cm
- `3` — \> 6 cm

### Area eloquente adiacente (corteccia sensitivo-motoria, del linguaggio o visiva; ipotalamo, talamo, capsula interna, tronco encefalico, peduncoli cerebellari o nuclei cerebellari profondi)

`eloquente`

### Drenaggio venoso profondo (qualsiasi componente)

`profunda`

## Edizione del metodo

Spetzler–Martin 1986: 3 fattori, grado I–V; gruppi Spetzler–Ponce 2011 A/B/C

## Formula documentata

Dimensione: \< 3 cm = 1, 3 a 6 cm = 2, \> 6 cm = 3 · Area eloquente = 1 · Drenaggio venoso profondo = 1. Grado = somma (I a V).

Spetzler–Ponce (2011): classe A = I e II; B = III; C = IV e V.

## Limiti e popolazione

Classificazione delle MAV cerebrali orientata al rischio chirurgico. La variante locale usa i gradi I–V e il raggruppamento Spetzler-Ponce A/B/C; l’abstract originale del 1986 menziona anche un sesto gruppo. I risultati delle serie chirurgiche non dimostrano prestazioni equivalenti per altre modalità terapeutiche.

## Riferimenti

- [Spetzler RF, Martin NA. A proposed grading system for arteriovenous malformations. J Neurosurg, 1986.](https://doi.org/10.3171/jns.1986.65.4.0476)

- [Spetzler RF, Ponce FA. A 3-tier classification of cerebral arteriovenous malformations. J Neurosurg, 2011.](https://doi.org/10.3171/2010.8.JNS10663)

## Riprodurre i test tecnici

Esegua node test.cjs nella cartella principale di questo repository per ripetere i casi sintetici registrati. Gli input, i risultati attesi e le tolleranze originali sono conservati. I test tecnici non costituiscono validazione clinica.

```sh
node test.cjs
```

tool.json contiene le fonti, l’edizione e l’ambito della revisione. examples.json conserva gli input e i risultati attesi dei casi sintetici; results.json registra i risultati ottenuti.

[Scheda e riferimenti](../tool.json) · [Codice JavaScript](../calculator.js) · [Casi di riferimento](../examples.json) · [results.json](../results.json)

## Revisione e condizioni d’uso

Non è stata effettuata una revisione clinica indipendente.

Questa interfaccia è una traduzione realizzata dagli autori, non un’edizione ufficiale o certificata. Non sono state eseguite la revisione clinica indipendente, la revisione linguistica professionale né la verifica delle autorizzazioni relative ai diritti sugli strumenti.

Risultato della formula o classificazione. Interpretazione, condotta e applicabilità dipendono dalla valutazione professionale e dalla fonte selezionata.

## Licenza e attribuzione

Apache-2.0 si applica solo al codice di ELUCENIA. I diritti su strumenti, pubblicazioni, traduzioni e dati restano ai rispettivi titolari. Conservi LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
