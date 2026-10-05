<!-- ELUCENIA technical documentation · spetzler-martin · zh · no clinical/professional/rights approval -->

# Spetzler-Martin 分级

[条件、来源与许可](https://elucenia.org/zh/tools/spetzler-martin)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 血管畸形团最大直径

`tamanho`

- `1` — \< 3 cm
- `2` — 3 至 6 cm
- `3` — \> 6 cm

### 邻近功能重要区（感觉运动、语言或视觉皮质；下丘脑、丘脑、内囊、脑干、小脑脚、小脑深部核团）

`eloquente`

### 深静脉引流（任何部分）

`profunda`

## 方法版本

Spetzler–Martin 1986：3因素，I–V级；Spetzler–Ponce 2011分组A/B/C

## 已记录的公式

大小：\< 3 cm = 1，3至6 cm = 2，\> 6 cm = 3 · 重要功能区 = 1 · 深静脉引流 = 1。等级为总和（I至V）。

Spetzler–Ponce（2011）：A = I、II；B = III；C = IV、V。

## 限制与适用人群

脑动静脉畸形的分级旨在评估手术风险。本地变体采用I–V级及Spetzler-Ponce A/B/C分组；1986年原始摘要还提及第六组。手术病例系列的结果并不能证明其在其他治疗方式中具有同等表现。

## 参考文献

- [Spetzler RF, Martin NA. A proposed grading system for arteriovenous malformations. J Neurosurg, 1986.](https://doi.org/10.3171/jns.1986.65.4.0476)

- [Spetzler RF, Ponce FA. A 3-tier classification of cerebral arteriovenous malformations. J Neurosurg, 2011.](https://doi.org/10.3171/2010.8.JNS10663)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026
