<!-- ELUCENIA technical documentation · spetzler-martin · es · no clinical/professional/rights approval -->

# Escala de Spetzler-Martin

[condiciones, fuentes y permisos](https://elucenia.org/es/herramientas/spetzler-martin)

## Cómo usar

Utilice la herramienta en el portal o abra index.html mediante un servidor HTTP local. Seleccione el idioma, complete los campos y calcule.

## Entradas y unidades

### Diámetro máximo del nido

`tamanho`

- `1` — \< 3 cm
- `2` — 3 a 6 cm
- `3` — \> 6 cm

### Área elocuente adyacente (corteza sensitivomotora, del lenguaje o visual; hipotálamo, tálamo, cápsula interna, tronco encefálico, pedúnculos cerebelosos o núcleos cerebelosos profundos)

`eloquente`

### Drenaje venoso profundo (cualquier componente)

`profunda`

## Edición del método

Spetzler–Martin 1986: 3 factores, grado I–V; agrupación Spetzler–Ponce 2011 A/B/C

## Fórmula documentada

Tamaño: \< 3 cm = 1, 3 a 6 cm = 2, \> 6 cm = 3 · Área elocuente = 1 · Drenaje venoso profundo = 1. Grado = suma (I a V).

Spetzler–Ponce (2011): clase A = I y II; B = III; C = IV y V.

## Límites y población

Clasificación de MAV cerebral orientada al riesgo quirúrgico. La variante local utiliza los grados I–V y la agrupación Spetzler-Ponce A/B/C; el resumen original de 1986 también menciona un sexto grupo. Los resultados de series quirúrgicas no demuestran un rendimiento equivalente para otras modalidades de tratamiento.

## Referencias

- [Spetzler RF, Martin NA. A proposed grading system for arteriovenous malformations. J Neurosurg, 1986.](https://doi.org/10.3171/jns.1986.65.4.0476)

- [Spetzler RF, Ponce FA. A 3-tier classification of cerebral arteriovenous malformations. J Neurosurg, 2011.](https://doi.org/10.3171/2010.8.JNS10663)

## Reproducir las pruebas técnicas

Ejecute node test.cjs en el directorio raíz de este repositorio para repetir los casos sintéticos registrados. Se conservan las entradas, los resultados esperados y las tolerancias originales. Las pruebas técnicas no constituyen validación clínica.

```sh
node test.cjs
```

tool.json contiene las fuentes, la edición y el alcance de la revisión. examples.json conserva las entradas y los resultados esperados de los casos sintéticos; results.json registra los resultados obtenidos.

[Ficha y referencias](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referencia](../examples.json) · [results.json](../results.json)

## Revisión y condiciones de uso

No se ha realizado una revisión clínica independiente.

Esta interfaz es una traducción de elaboración propia, no una edición oficial o certificada. No se han realizado la revisión clínica independiente, la revisión lingüística profesional ni la autorización de derechos de los instrumentos.

Resultado de la fórmula o clasificación. La interpretación, la conducta y la aplicabilidad dependen de la evaluación profesional y de la fuente seleccionada.

## Licencia y atribución

Apache-2.0 se aplica únicamente al código de ELUCENIA. Los derechos de los instrumentos, publicaciones, traducciones y datos permanecen en manos de sus respectivos titulares. Conserve LICENSE y NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
