# MLCC Open Questions

このファイルは、過去会話で未解決のまま残っている論点、公開情報で未確認の用語、矛盾し得る作業仮説を管理するためのものです。

## 優先度 High

### 1. OM補正とは何か

- Status: OPEN QUESTION / UNVERIFIED
- Background:
  - ユーザーは「MLCCにおけるOM補正とは何か。先に1次混合で入れたものを除去するための何かか」と質問した。
  - 公開検索では MLCC 文脈の `OM補正` / `OM correction` に明確な該当が見つかっていない。
- Candidate interpretations:
  - Organic Material 補正
  - Oxide Material 補正
  - Oxide Mole / Oxide Molar 補正
  - Over-milling 補正
  - 社内略語
- Why important:
  - 調合工程、モル比、焼成後組成、または有機物量管理に関わる可能性がある。
- Required evidence:
  - 社内資料の用語定義
  - 特許・論文・製造資料での類似語
  - 工程表上の位置づけ
- Current answer policy:
  - 断定禁止。`出典未確認` と明記する。

### 2. 一次調合・二次調合の正確な工程境界

- Status: OPEN QUESTION / UNVERIFIED
- Background:
  - 過去会話では、一次調合は粉体・添加剤・溶媒・分散剤の初期分散、二次調合はバインダー・可塑剤等を加えた塗工用スラリー調整ではないかと整理した。
- Conflict / ambiguity:
  - 企業・工場ごとに工程名が異なる可能性がある。
  - 「一次」「二次」が添加剤投入順なのか、ミル処理段階なのか、有機成分投入段階なのか不明。
- Required evidence:
  - 公開特許の工程記述
  - MLCC スラリー製造論文
  - 装置メーカー資料
  - 社内工程表
- Current answer policy:
  - 一般工程フローは説明可。ただし一次/二次の名称対応は未確認扱い。

### 3. 0次調合という用語は実在するか

- Status: OPEN QUESTION / UNVERIFIED
- Background:
  - ユーザーが「0次調合という言葉があるらしい。本当にそういう言葉があるか」と質問。
- Candidate meanings:
  - 原料粉体合成後の前処理
  - 添加剤母液・プレミックス作成
  - BaTiO3 と副成分の予備混合
  - 一次調合前の粉砕・分級・表面処理
  - 完全に社内用語
- Required evidence:
  - 日本語特許検索
  - 製造工程資料
  - 社内用語集
- Current answer policy:
  - 出典未確認。一般用語として扱わない。

### 4. SCミル / MSCミル / MNミルの正確な装置定義

- Status: OPEN QUESTION / UNVERIFIED
- Background:
  - 過去会話では、SCミル、MSCミル、MNミルの違い、摩耗、経年劣化速度、導入履歴を議論。
  - SC/MSC は低信頼ブログに短 L/D 型・循環分散・ビーズ偏り抑制の説明があるが、公式出典では未確認。
  - MNミルは未確認。
- Key questions:
  - それぞれの正式名称は何か。
  - 装置メーカーはどこか。
  - 構造差は、縦型/横型、タンク形状、L/D、ロータ、セパレータ、循環方式、メディア径のどれか。
  - MLCC 誘電体スラリー用なのか、Ni電極ペースト用なのか。
- Required evidence:
  - メーカー公式カタログ
  - 特許
  - 学会発表
  - 装置仕様書
  - 社内設備台帳
- Current answer policy:
  - SC/MSC/MN の差は仮説としてのみ扱う。

### 5. MSCミルの方が摩耗・経年劣化が速いのか

- Status: OPEN QUESTION / HYPOTHESIS
- Hypothesis A:
  - MSC が微小メディア・高せん断・高接触頻度を使う場合、部材・メディア摩耗、発熱、コンタミが速い可能性がある。
- Hypothesis B:
  - 短 L/D 設計・ビーズ偏り抑制により、局所過負荷・異常摩耗を抑えられる可能性がある。
- Required data:
  - メディア径
  - メディア材質
  - ロータ/ライナー材質
  - 周速
  - 処理量
  - 処理時間
  - 粘度
  - 洗浄頻度
  - 摩耗粉分析
  - 導入時期
  - メンテナンス履歴
- Current answer policy:
  - 「MSC側が速い」とは断定しない。比較条件なしの摩耗速度比較は不成立。

## 優先度 Medium

### 6. ΔSSA の正式定義・計算式・管理目的

- Status: OPEN QUESTION / UNVERIFIED
- Working understanding:
  - 処理前後の比表面積変化量。
- Key questions:
  - ΔSSA = 処理後SSA - 処理前SSA か。
  - 粉体基準か、スラリー乾燥物基準か、シート基準か。
  - どの処理前後を比較するか。一次調合前後、二次調合前後、ミル前後、シート前後など。
  - 管理値は上限・下限・目標範囲のどれか。
- Current answer policy:
  - 分散指標と粒子損傷指標の両面を説明する。

### 7. シートSSAとは何を測っているか

- Status: OPEN QUESTION / UNVERIFIED
- Candidate definitions:
  - シート形成に使う誘電体粉体の SSA
  - スラリー中固形分の SSA
  - 乾燥グリーンシートを再粉砕して測る SSA
  - シート用配合に換算した理論 SSA
- Required evidence:
  - 測定SOP
  - 品質管理表
  - 工程管理項目の定義
- Current answer policy:
  - 出典未確認。粉体SSAとの違いを断定しない。

### 8. シート実効モル比の計算式

- Status: OPEN QUESTION / UNVERIFIED
- Working hypothesis:
  - Aサイト/Bサイト比、例 `(Ba + Ca) / (Ti + Zr)` のような指標。
- Key questions:
  - どの元素を numerator / denominator に含めるか。
  - 希土類、Mg、Mn、Si/glass はどう扱うか。
  - 酸化物換算なのか元素モル換算なのか。
  - 揮発・ロス・補正を含むか。
  - 焼成後ではなくグリーンシート時点の管理値なのか。
- Current answer policy:
  - 「実効」という語が補正済み投入比・測定値・設計値のいずれを指すか未確認とする。

### 9. NE塗布厚の正式意味

- Status: OPEN QUESTION / UNVERIFIED
- Working hypothesis:
  - `NE = Nickel Electrode`、内部電極ペーストの印刷・塗布厚。
- Key questions:
  - グリーン時点の湿潤厚みか、乾燥後厚みか、焼成後電極厚みか。
  - 塗布厚、印刷厚、乾燥膜厚、電極連続性のどれを指すか。
  - 誘電体スラリー側のパラメータとどのように連携するか。
- Required evidence:
  - 工程管理表
  - 印刷工程仕様
  - Ni paste 関連特許

### 10. 一次粒子を壊さず二次粒子だけをほぐす具体条件

- Status: OPEN QUESTION / WORKING UNDERSTANDING
- Working understanding:
  - 目的は凝集解砕・分散であり、一次粒子の結晶性や形状を過度に壊さないこと。
- Key variables:
  - メディア径
  - メディア材質
  - 周速
  - 滞留時間
  - 循環回数
  - 分散剤
  - 固形分濃度
  - 温度
  - 粘度
- Required evidence:
  - 粉体分散論文
  - MLCC スラリー特許
  - ミルメーカー資料
  - SEM/TEM/BET/粒度分布の評価事例

### 11. Ba/Ca/Mg 置換に関する Murata 公開情報

- Status: OPEN QUESTION
- Background:
  - 過去会話で、Murata が Ba の一部を Ca や Mg で置換する技術の公知情報を理解したいという論点があった。
- Current source basis:
  - Kishi et al. 2003 は CaO と A-site excess、Ti site、アクセプタ効果を説明。
  - Murata 技術ページは希土類、MgO、MnO、BaZrO3 等を含む誘電体材料設計を説明。
- Unresolved:
  - Murata 固有の「BaをCaやMgで置換」という表現に対応する論文・特許・技術資料を特定できていない。
- Required evidence:
  - Murata 特許
  - Murata 技術論文
  - 著者・所属が Murata の学術論文

## 優先度 Low / 調査拡張

### 12. MLCC の製造過程の歴史的発展

- Status: OPEN QUESTION / PARTIAL
- Known:
  - Ni 内部電極の商用化・BME 化、薄層化、高積層化は確認済み。
- Need:
  - 年表化
  - メーカー別の工程革新
  - サイズ・容量・層厚・積層数の定量変遷

### 13. 最新研究成果の読み分け

- Status: OPEN QUESTION / PARTIAL
- Need:
  - エネルギー貯蔵向け MLCC 研究と、通常 MLCC 量産工程研究を分ける。
  - lead-free high entropy, relaxor ferroelectric, BNT/NN/ST, BaTiO3-based などを、用途別に分類する。

### 14. 信頼性メカニズムの定量整理

- Status: OPEN QUESTION / PARTIAL
- Need:
  - 酸素空孔移動
  - 絶縁抵抗劣化
  - HALT
  - 温度加速・電圧加速
  - ABD/TRA
  - 粒界障壁
  - 電極端部電界集中
  - 内部応力

### 15. 工程パラメータと最終特性の因果整理

- Status: OPEN QUESTION
- Need:
  - 粉体粒径 → シート厚み → 焼結粒径 → 誘電率 / IR / DCバイアス / 信頼性
  - ΔSSA → 分散状態 → 欠陥密度 → リーク / 絶縁破壊
  - NE塗布厚 → 電極連続性 → ESR / 容量 / 短絡
  - 焼成雰囲気 → 酸素空孔 → IR / 寿命

## 調査時の推奨検索語

```text
MLCC BaTiO3 MgO rare earth dopant reliability oxygen vacancy
MLCC nonreducible dielectric Ni internal electrode BaTiO3 CaO
MLCC green sheet slurry dispersion binder solvent BaTiO3
MLCC slurry bead mill dispersion particle size SSA
MLCC dielectric slurry specific surface area ΔSSA
MLCC sheet molar ratio Ba Ti Ca Zr
MLCC nickel electrode paste thickness green sheet
SC mill MSC mill bead mill L/D ratio micro beads dispersion
MLCC OM correction oxide molar correction organic material correction
MLCC manufacturing process tape casting screen printing lamination firing
```
