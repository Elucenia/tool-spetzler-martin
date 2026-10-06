<!-- ELUCENIA technical documentation · spetzler-martin · ja · no clinical/professional/rights approval -->

# Spetzler-Martin分類

[条件・出典・許諾](https://elucenia.org/ja/tools/spetzler-martin)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### ナイダスの最大径

`tamanho`

- `1` — \< 3 cm
- `2` — 3 ～ 6 cm
- `3` — \> 6 cm

### 隣接する重要機能領域（感覚運動・言語・視覚皮質、視床下部、視床、内包、脳幹、小脳脚、小脳深部核）

`eloquente`

### 深部静脈還流（いずれかの部分）

`profunda`

## 方法の版

Spetzler–Martin 1986：3因子、I–V、Spetzler–Ponce 2011のA/B/C

## 記載された計算式

大きさ：\< 3 cm = 1、3～6 cm = 2、\> 6 cm = 3、機能的重要部位 = 1、深部静脈還流 = 1。合計がI～V。

Spetzler–Ponce（2011）：A = I・II、B = III、C = IV・V。

## 限界・対象集団

脳動静脈奇形を、外科的リスクに着目して分類します。ローカル版はI–Vの等級とSpetzler-Ponce A/B/Cの区分を用いますが、1986年の原抄録は第六群にも言及しています。外科的症例シリーズの結果は、他の治療法で同等の性能があることを示すものではありません。

## 参考文献

- [Spetzler RF, Martin NA. A proposed grading system for arteriovenous malformations. J Neurosurg, 1986.](https://doi.org/10.3171/jns.1986.65.4.0476)

- [Spetzler RF, Ponce FA. A 3-tier classification of cerebral arteriovenous malformations. J Neurosurg, 2011.](https://doi.org/10.3171/2010.8.JNS10663)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026

## 記録された結果

以下の情報は、合成例に対する手法の出力を保持したものです。独立した臨床的検証を示すものではありません。

### 1

グレード I（Spetzler-Ponce Aクラス）

クラスA：微小外科的切除が通常推奨される治療です。


### 2

グレード III（Spetzler-Ponce Bクラス）

クラスB：個別化された多モダリティ治療（手術、塞栓術、定位放射線手術）。


### 3

グレード V（Spetzler-Ponce Cクラス）

Cクラス：一般に経過観察；反復出血、進行性欠損、合併動脈瘤、または盗血症状がある場合は治療する。

