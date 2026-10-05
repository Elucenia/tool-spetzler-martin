<!-- ELUCENIA technical documentation · spetzler-martin · fr · no clinical/professional/rights approval -->

# Échelle de Spetzler-Martin

[conditions, sources et autorisations](https://elucenia.org/fr/outils/spetzler-martin)

## Mode d’emploi

Utilisez l’outil sur le portail ou ouvrez index.html via un serveur HTTP local. Sélectionnez la langue, remplissez les champs et lancez le calcul.

## Données d’entrée et unités

### Plus grand diamètre du nidus

`tamanho`

- `1` — \< 3 cm
- `2` — 3 à 6 cm
- `3` — \> 6 cm

### Zone éloquente adjacente (cortex sensitivo-moteur, du langage ou visuel ; hypothalamus, thalamus, capsule interne, tronc cérébral, pédoncules cérébelleux ou noyaux cérébelleux profonds)

`eloquente`

### Drainage veineux profond (tout composant)

`profunda`

## Édition de la méthode

Spetzler–Martin 1986 : 3 facteurs, degré I–V ; regroupement Spetzler–Ponce 2011 A/B/C

## Formule documentée

Taille : \< 3 cm = 1, 3 à 6 cm = 2, \> 6 cm = 3 · Zone éloquente = 1 · Drainage veineux profond = 1. Degré = somme (I à V).

Spetzler–Ponce (2011) : classe A = I et II ; B = III ; C = IV et V.

## Limites et population

Classification des malformations artérioveineuses cérébrales axée sur le risque chirurgical. La variante locale utilise les grades I–V et le regroupement Spetzler-Ponce A/B/C ; le résumé original de 1986 mentionne aussi un sixième groupe. Les résultats des séries chirurgicales ne démontrent pas une performance équivalente pour d’autres modalités thérapeutiques.

## Références

- [Spetzler RF, Martin NA. A proposed grading system for arteriovenous malformations. J Neurosurg, 1986.](https://doi.org/10.3171/jns.1986.65.4.0476)

- [Spetzler RF, Ponce FA. A 3-tier classification of cerebral arteriovenous malformations. J Neurosurg, 2011.](https://doi.org/10.3171/2010.8.JNS10663)

## Reproduire les tests techniques

Exécutez node test.cjs dans le répertoire racine de ce dépôt pour reproduire les cas synthétiques enregistrés. Les données d’entrée, les résultats attendus et les tolérances d’origine sont conservés. Les tests techniques ne constituent pas une validation clinique.

```sh
node test.cjs
```

tool.json contient les sources, l’édition et le périmètre de la revue. examples.json conserve les données d’entrée et les résultats attendus des cas synthétiques ; results.json consigne les résultats obtenus.

[Fiche et références](../tool.json) · [Code JavaScript](../calculator.js) · [Cas de référence](../examples.json) · [results.json](../results.json)

## Revue et conditions d’utilisation

Aucune révision clinique indépendante n’a été effectuée.

Cette interface est une traduction réalisée par nos soins, et non une édition officielle ou certifiée. La revue clinique indépendante, la révision linguistique professionnelle et l’autorisation des droits sur les instruments n’ont pas été réalisées.

Résultat de la formule ou de la classification. L’interprétation, la conduite et l’applicabilité dépendent de l’évaluation professionnelle et de la source sélectionnée.

## Licence et attribution

Apache-2.0 s’applique uniquement au code d’ELUCENIA. Les droits sur les instruments, publications, traductions et données restent ceux de leurs titulaires respectifs. Conservez LICENSE et NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026
