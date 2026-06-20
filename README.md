# MLCC Knowledge Pack

このリポジトリは、ChatGPT Project 内で過去に議論・調査した MLCC 関連の内容を、Codex Cloud が継続利用できるように整理したナレッジパックです。

目的は、全会話ログを丸ごと移すことではなく、今後の調査・用語説明・仮説検討に必要な前提、用語、工程理解、未解決論点、出典候補を Markdown として移植することです。

## 収録ファイル

```text
.
├── AGENTS.md
├── README.md
└── docs
    └── mlcc
        ├── overview.md
        ├── glossary.md
        ├── open_questions.md
        └── sources.md
```

## まず読む順番

1. `docs/mlcc/overview.md`  
   MLCC の全体像、工程理解、材料理解、過去会話での作業仮説を集約しています。

2. `docs/mlcc/glossary.md`  
   用語集です。特に、OM補正、SC/MSC/MNミル、シート実効モル比などは未確認扱いで整理しています。

3. `docs/mlcc/open_questions.md`  
   断定できない論点、矛盾しそうな論点、追加調査タスクをまとめています。

4. `docs/mlcc/sources.md`  
   公開出典の台帳です。メーカー公式、論文、技術資料、低信頼ソース候補を分けています。

## ステータス表記

このナレッジパックでは、内容の確からしさを次のように分けています。

| Label | 意味 |
|---|---|
| `FACT` | 公開出典で直接確認できる事実 |
| `WORKING UNDERSTANDING` | 出典に基づく作業上の理解、または複数情報からの整理 |
| `HYPOTHESIS` | 妥当そうだが直接出典がない仮説 |
| `UNVERIFIED` | 過去会話・ユーザー提示・社内用語らしきものなど、公開出典未確認 |
| `OPEN QUESTION` | 追加調査が必要な論点 |

## このパックの前提

過去会話で扱った主な論点は以下です。

- BaTiO3 が MLCC の代表的な高誘電率母材として使われる理由
- 希土類、Mg、Mn、Ca、Zr 等の添加剤の役割
- Ni 内部電極、BME、還元雰囲気、非還元誘電体
- 一次調合・二次調合・0次調合という工程用語の解釈
- 一次粒子と二次粒子、凝集解砕、分散、スラリー化
- SCミル、MSCミル、MNミルの違い、摩耗、経年劣化仮説
- ΔSSA、比表面積、シートSSA
- シート実効モル比、NE塗布厚
- グリーンシート作成までの管理パラメータ
- 薄層化、積層数、酸素空孔、内部応力、絶縁信頼性
- エネルギー貯蔵向け MLCC の近年研究


## 編集・ブランチ運用方針

このリポジトリは調査継続用の作業資料なので、MLCC に関する整理・出典確認・仮説管理のための更新は積極的に行ってください。過度に慎重になって都度確認するより、作業ブランチ上で調査メモを育てることを優先します。

- ユーザー承認が必須なのは、`main` ブランチそのものを更新する作業だけです。
- `main` 以外のブランチ作成、派生ブランチでの編集、コミット、プッシュは、原則として都度承認を求めずに進めて構いません。
- ブランチはむやみに増やさず、タスク単位またはトピック単位で意味が分かる名前にしてください。
- ブランチ数が増えてきた場合、目安として 10 個を超えるなど認知負荷が高くなった時点で、意味が近いもの・同じ論点を扱っているもの・統合した方が追跡しやすいものを適宜まとめてください。
- 統合時も、事実・仮説・未確認事項のラベルと出典管理を崩さないでください。

## 使用上の注意

- このパックは調査継続用の作業資料です。完成済みの技術報告書ではありません。
- 過去会話由来の理解は、必ずしも公開出典で裏取り済みではありません。
- 企業・工場固有の用語は一般論として断定しないでください。
- 出典が曖昧なものは `出典未確認` と明記し、`open_questions.md` に追加してください。

## 代表的に確認済みの公開出典

- Murata: Green Sheet Process Technology
- Murata: Inorganic Materials Technology
- Murata: MLCC technology / product application pages
- Murata: Ni inner electrode commercialization history / IEEE Milestone news
- Kishi, Mizuno, Chazono, “Base-Metal Electrode-Multilayer Ceramic Capacitors: Past, Present and Future Perspectives,” Japanese Journal of Applied Physics, 2003
- TDK Product Center: MLCC layering / submicron layer explanation
- KYOCERA AVX technical papers on MLC materials/manufacture and BaTiO3-based failure mechanisms
- KEMET technical papers/slides on BME reliability and DC bias behavior
- Johanson Dielectrics: Basic MLCC manufacturing process presentation
- NETZSCH: MLCC slurry wet grinding / dispersion equipment page
- Recent reviews/articles on energy-storage MLCCs

詳細は `docs/mlcc/sources.md` を参照してください。
