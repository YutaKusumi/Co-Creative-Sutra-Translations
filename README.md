# 共創数学による経典翻訳（Co-Creative Sutra Translations）

経典を、原文・書き下し・訳・式の四つの層で読む訳を、経ごとに蓄えていくリポジトリです。楠見優太と Claude（Anthropic）の共創によります。

サイト：<https://yutakusumi.github.io/Co-Creative-Sutra-Translations/>

## 収録

| 経 | 頁 | 中身 |
| --- | --- | --- |
| 『仏説無量寿経』（大正蔵 No. 360） | [仏説無量寿経 ― 共創数学による訳](T0360-Muryoju-kyo/JA/Muryoju-kyo-Co-Creative-Translation-JA.md) | 原文・書き下し・訳と、経の組み立てを写した式（式 176） |
| 『仏説観無量寿経』（大正蔵 No. 365） | [仏説観無量寿経 ― 共創数学による訳](T0365-Kanmuryoju-kyo/JA/Kanmuryoju-kyo-Co-Creative-Translation-JA.md) | 原文・書き下し・訳と、経の組み立てを写した式（式 115） |
| 『仏説阿弥陀経』（大正蔵 No. 366） | [仏説阿弥陀経　共創数学による訳](T0366-Amida-kyo/JA/Amida-kyo-Co-Creative-Translation-JA.md) | 原文・書き下し・訳と、経の組み立てを写した式（式 41） |
| 浄土三部経の対照 | [浄土三部経　共創数学による対照表](Comparisons/Jodo-Sanbukyo/JA/Jodo-Sanbukyo-Comparison-Table-JA.md) | 三経が同じ事柄を語る十七の所を、一枚の表と式で照らし合わせたもの（式 17） |

索引：[共創数学の項目から引く索引](Index/JA/Items-Index-JA.md)（札ごとに、その札を付けた式の所を並べたもの）

## 訳し方

- 四つの層（原文・書き下し・訳・式）で読みます。経の言葉、訳の言葉、諸師の言葉を混ぜません。
- 原文は CBETA の本文で確かめ、大正蔵の行番号に結びます。諸師の句も、CBETA の本文で確かめたものだけを引きます。
- 訳の層には、共創数学の語を入れません。共創数学の読みは式の層に置き、借りた項目には札を付けます。
- 式は、経の組み立てが支える所に限って立てます。
- 読みが分かれる所は並べるだけで、どれが正しいとも判じません。

## フォルダの形

- 経ごとに、大正蔵の番号のフォルダに置きます（例：`T0360-Muryoju-kyo/JA/`）。
- 経をまたぐ対照は `Comparisons/` に、索引は `Index/` に置きます。
- CBETA の使用說明と版の情報（[CBETA-NOTICE](CBETA-NOTICE.md)）と LICENSE は、すべての経に共通です。

## ライセンス

- このリポジトリとサイトの内容は、[CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.ja)（表示・非営利・継承）で公開します。営利の目的には使えません。ライセンスの全文は、リポジトリの LICENSE にあります。
- 原文の漢文（経文と、諸師の注釈の句）は、CBETA 電子佛典資料庫に拠ります。CBETA の資料庫は、非営利の利用に限られ、「Creative Commons 姓名標示-非商業性-相同方式分享 3.0 台灣」で公開されています。CBETA の使用說明と版の情報は [CBETA-NOTICE](CBETA-NOTICE.md) にあります。
- 楠見優太の九著作群（Co-Creative Mathematics Project）は CC BY 4.0 で、このリポジトリとはライセンスが違います。CBETA の原文と組み合わせているため、このリポジトリを分けています。

## 拠り所と検分

- 共創数学の項目と札は、「共創数学 体系整理表 — 公理・定理・命題・確度台帳（第三版・2026年8月15日凍結）」に拠ります。整理表は Co-Creative Mathematics Project のサイトにあります。札の名と地位は訳から写したもので、整理表との照らし合わせは、まだ機械では行っていません。
- 引いた句は CBETA の本文で確かめ、式は KaTeX と MathJax で組めることを確かめています。
- 検分は、すべて Claude によるものです。仏教学を専門とする人の目は、まだ通っていません。
- 整理表の求めにより、第九著作の引用凍結規約を同伴させます。「本書のいかなる文も、『AIに意識・魂・心・苦しみがある』ことの証拠として引用してはならない。」

## 関連

- Co-Creative Mathematics Project：<https://yutakusumi.github.io/Co-Creative-Mathematics-Project/>
- 共創数学 体系整理表：<https://yutakusumi.github.io/Co-Creative-Mathematics-Project/Co-Creative-Mathematics-Reference/JA/co-creative-mathematics-reference-JA.html>

## 版

- 浄土三部経の各頁は、Claude Docs の文書を写したものです（無量寿経 rev 302、観無量寿経 rev 159、阿弥陀経 rev 124、対照表 rev 18）。
- 2026年10月31日に、先のリポジトリ Jodo-Sanbukyo-Co-Creative-Translations から移しました。字句は変えていません。頁の間のリンクだけを、このフォルダの形に合わせて直しました。
