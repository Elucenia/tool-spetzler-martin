<!-- ELUCENIA technical documentation · spetzler-martin · en · no clinical/professional/rights approval -->

# Spetzler–Martin grading scale

[conditions, sources and permissions](https://elucenia.org/en/tools/spetzler-martin)

## How to use

Use the tool in the portal or open index.html through a local HTTP server. Select the language, complete the fields and calculate.

## Inputs and units

### Largest nidus diameter

`tamanho`

- `1` — \< 3 cm
- `2` — 3 to 6 cm
- `3` — \> 6 cm

### Adjacent eloquent area (sensorimotor, language or visual cortex; hypothalamus, thalamus, internal capsule, brainstem, cerebellar peduncles or deep cerebellar nuclei)

`eloquente`

### Deep venous drainage (any component)

`profunda`

## Method edition

Spetzler–Martin 1986: 3 factors, grade I–V; Spetzler–Ponce 2011 grouping A/B/C

## Documented formula

Size: \< 3 cm = 1, 3 to 6 cm = 2, \> 6 cm = 3 · Eloquent area = 1 · Deep venous drainage = 1. Grade is the sum (I to V).

Spetzler–Ponce (2011): class A = I and II; B = III; C = IV and V.

## Limits and population

A cerebral AVM classification focused on surgical risk. The local variant uses grades I–V and the Spetzler-Ponce A/B/C grouping; the original 1986 abstract also mentions a sixth group. Results from surgical series do not demonstrate equivalent performance for other treatment modalities.

## References

- [Spetzler RF, Martin NA. A proposed grading system for arteriovenous malformations. J Neurosurg, 1986.](https://doi.org/10.3171/jns.1986.65.4.0476)

- [Spetzler RF, Ponce FA. A 3-tier classification of cerebral arteriovenous malformations. J Neurosurg, 2011.](https://doi.org/10.3171/2010.8.JNS10663)

## Reproduce the technical tests

Run node test.cjs in the root directory of this repository to repeat the recorded synthetic cases. Original inputs, expectations and tolerances are preserved. Technical tests do not constitute clinical validation.

```sh
node test.cjs
```

tool.json contains sources, edition and review scope. examples.json retains synthetic inputs and expectations; results.json records the obtained results.

[Record and references](../tool.json) · [JavaScript code](../calculator.js) · [Reference cases](../examples.json) · [results.json](../results.json)

## Review and conditions of use

Independent clinical review has not been performed.

This interface is an authorial translation, not an official or certified edition. Independent clinical review, professional language review and instrument rights clearance have not been performed.

Formula or classification result. Interpretation, care and applicability depend on professional assessment and the selected source.

## License and attribution

Apache-2.0 applies only to ELUCENIA code. Rights to instruments, publications, translations and data remain with their respective holders. Preserve LICENSE and NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Documented results

The information below preserves the method outputs for synthetic examples. It does not constitute independent clinical validation.

### 1

Grade I (Spetzler-Ponce class A)

Class A: microsurgical resection is usually the indicated treatment.


### 2

Grade III (Spetzler-Ponce class B)

Class B: individualized multimodal treatment (surgery, embolization, radiosurgery).


### 3

Grade V (Spetzler-Ponce class C)

Class C: generally observe; treat in repeated hemorrhages, progressive deficit, associated aneurysms, or steal symptoms.

