<!-- ELUCENIA technical documentation · spetzler-martin · de · no clinical/professional/rights approval -->

# Spetzler-Martin-Skala

[Bedingungen, Quellen und Berechtigungen](https://elucenia.org/de/werkzeuge/spetzler-martin)

## Verwendung

Verwenden Sie das Werkzeug im Portal oder öffnen Sie index.html über einen lokalen HTTP-Server. Wählen Sie die Sprache, füllen Sie die Felder aus und berechnen Sie das Ergebnis.

## Eingaben und Einheiten

### Größter Nidusdurchmesser

`tamanho`

- `1` — \< 3 cm
- `2` — 3 bis 6 cm
- `3` — \> 6 cm

### Angrenzendes eloquentes Areal (sensomotorischer, Sprach- oder visueller Kortex; Hypothalamus, Thalamus, innere Kapsel, Hirnstamm, Kleinhirnstiele oder tiefe Kleinhirnkerne)

`eloquente`

### Tiefe venöse Drainage (jeder Anteil)

`profunda`

## Fassung der Methode

Spetzler–Martin 1986: 3 Faktoren, Grad I–V; Spetzler–Ponce 2011 Gruppen A/B/C

## Dokumentierte Formel

Größe: \< 3 cm = 1, 3 bis 6 cm = 2, \> 6 cm = 3 · Eloquentes Gebiet = 1 · Tiefer venöser Abfluss = 1. Grad = Summe (I bis V).

Spetzler–Ponce (2011): A = I und II; B = III; C = IV und V.

## Grenzen und Population

Klassifikation zerebraler arteriovenöser Malformationen mit Bezug auf das Operationsrisiko. Die lokale Variante nutzt Grade I–V und die Spetzler-Ponce-Gruppierung A/B/C; das ursprüngliche Abstract von 1986 erwähnt auch eine sechste Gruppe. Ergebnisse chirurgischer Serien belegen keine gleichwertige Leistung für andere Behandlungsverfahren.

## Referenzen

- [Spetzler RF, Martin NA. A proposed grading system for arteriovenous malformations. J Neurosurg, 1986.](https://doi.org/10.3171/jns.1986.65.4.0476)

- [Spetzler RF, Ponce FA. A 3-tier classification of cerebral arteriovenous malformations. J Neurosurg, 2011.](https://doi.org/10.3171/2010.8.JNS10663)

## Technische Tests reproduzieren

Führen Sie node test.cjs im Stammverzeichnis dieses Repositorys aus, um die dokumentierten synthetischen Fälle zu wiederholen. Ursprüngliche Eingaben, erwartete Ergebnisse und Toleranzen bleiben erhalten. Technische Tests stellen keine klinische Validierung dar.

```sh
node test.cjs
```

tool.json enthält Quellen, Ausgabe und Umfang der Überprüfung. examples.json bewahrt die synthetischen Eingaben und erwarteten Ergebnisse; results.json dokumentiert die tatsächlich erhaltenen Ergebnisse.

[Eintrag und Referenzen](../tool.json) · [JavaScript-Code](../calculator.js) · [Referenzfälle](../examples.json) · [results.json](../results.json)

## Überprüfung und Nutzungsbedingungen

Eine unabhängige klinische Prüfung wurde nicht durchgeführt.

Diese Benutzeroberfläche ist eine selbst erstellte Übersetzung und keine offizielle oder zertifizierte Ausgabe. Eine unabhängige klinische Überprüfung, eine professionelle sprachliche Prüfung und eine Klärung der Rechte an den Instrumenten wurden nicht durchgeführt.

Ergebnis der Formel oder Klassifikation. Interpretation, Vorgehen und Anwendbarkeit hängen von der fachlichen Beurteilung und der ausgewählten Quelle ab.

## Lizenz und Urheberangaben

Apache-2.0 gilt nur für den ELUCENIA-Code. Die Rechte an Instrumenten, Veröffentlichungen, Übersetzungen und Daten verbleiben bei den jeweiligen Rechteinhabern. Bewahren Sie LICENSE und NOTICE auf.

ELUCENIA · Felipe Guedes · Copyright © 2026
