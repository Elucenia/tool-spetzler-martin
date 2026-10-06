<!-- ELUCENIA technical documentation · spetzler-martin · pt-BR · no clinical/professional/rights approval -->

# Escala de Spetzler-Martin

[condições, fontes e permissões](https://elucenia.org/pt-br/ferramentas/spetzler-martin)

## Como usar

Use a ferramenta no portal ou abra index.html em um servidor HTTP local. Selecione o idioma, preencha os campos e calcule.

## Entradas e unidades

### Maior diâmetro do nidus

`tamanho`

- `1` — \< 3 cm
- `2` — 3 a 6 cm
- `3` — \> 6 cm

### Área eloquente adjacente (córtex sensitivo-motor, linguagem ou visual; hipotálamo, tálamo, cápsula interna, tronco, pedúnculos cerebelares, núcleos cerebelares profundos)

`eloquente`

### Drenagem venosa profunda (qualquer componente)

`profunda`

## Edição do método

Spetzler Martin 1986:3 fatores, grau I–V; agrupamento Spetzler Ponce 2011 A/B/C

## Fórmula documentada

Tamanho: \< 3 cm = 1, 3 a 6 cm = 2, \> 6 cm = 3 · Área eloquente = 1 · Drenagem venosa profunda = 1. O grau é a soma (I a V).

Spetzler-Ponce (2011): classe A = graus I e II; classe B = grau III; classe C = graus IV e V.

## Limites e população

Classificação de MAV cerebral voltada ao risco cirúrgico. A variante local usa os graus I–V e o agrupamento Spetzler-Ponce A/B/C; o resumo original de 1986 também menciona um sexto grupo. Os resultados de séries cirúrgicas não demonstram desempenho equivalente para outras modalidades de tratamento.

## Referências

- [Spetzler RF, Martin NA. A proposed grading system for arteriovenous malformations. J Neurosurg, 1986.](https://doi.org/10.3171/jns.1986.65.4.0476)

- [Spetzler RF, Ponce FA. A 3-tier classification of cerebral arteriovenous malformations. J Neurosurg, 2011.](https://doi.org/10.3171/2010.8.JNS10663)

## Reproduzir os testes técnicos

Execute node test.cjs na pasta raiz deste repositório para repetir os casos sintéticos registrados. As entradas, expectativas e tolerâncias originais são preservadas. Testes técnicos não constituem validação clínica.

```sh
node test.cjs
```

tool.json contém fontes, edição e escopo de revisão. examples.json conserva as entradas e expectativas sintéticas; results.json registra os resultados obtidos.

[Ficha e referências](../tool.json) · [Código JavaScript](../calculator.js) · [Casos de referência](../examples.json) · [results.json](../results.json)

## Revisão e condições de uso

Revisão clínica independente não realizada.

Esta interface é uma tradução autoral, não uma edição oficial ou certificada. Revisão clínica independente, revisão linguística profissional e autorização de direitos de instrumentos não foram realizadas.

Resultado da fórmula ou classificação. Interpretação, conduta e aplicabilidade dependem da avaliação profissional e da fonte selecionada.

## Licença e atribuição

Apache-2.0 aplica-se somente ao código da ELUCENIA. Os instrumentos, publicações, traduções e dados mantêm os direitos dos respectivos titulares. Preserve LICENSE e NOTICE.

ELUCENIA · Felipe Guedes · Copyright © 2026

## Resultados documentados

As informações abaixo preservam as saídas do método para exemplos sintéticos. Não constituem validação clínica independente.

### 1

Grau I (classe A de Spetzler-Ponce)

Classe A: a ressecção microcirúrgica costuma ser o tratamento indicado.


### 2

Grau III (classe B de Spetzler-Ponce)

Classe B: tratamento multimodal (cirurgia, embolização, radiocirurgia) individualizado.


### 3

Grau V (classe C de Spetzler-Ponce)

Classe C: em geral, observação; tratar em hemorragias repetidas, déficit progressivo, aneurismas associados ou sintomas de roubo.

