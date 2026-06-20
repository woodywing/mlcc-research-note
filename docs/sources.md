# MLCC Sources

このファイルは、MLCC 調査で使う公開出典の台帳です。各出典について、信頼度、使える論点、注意点を残します。

## Source status labels

- `primary-corporate`: メーカー公式ページ・公式技術資料
- `primary-paper`: 査読論文・学術誌・DOI あり
- `technical-paper`: メーカー技術資料・白書・プレゼン資料
- `patent`: 特許
- `secondary`: 解説記事・ブログ・まとめ
- `low-confidence`: 出典不明瞭、非公式、検証用の入口に限定

---

## S-MURATA-GREEN-SHEET

- Title: Green Sheet Process Technology
- Type: primary-corporate
- Organization: Murata Manufacturing
- URL: https://corporate.murata.com/en-global/technology/technology-platform/production-technology/green-sheet-process
- Accessed: 2026-06-20
- Useful for:
  - MLCC のグリーンシート工程
  - スラリー混合・分散
  - シート形成
  - 内部電極印刷
  - 積層、プレス
  - 薄層・高精度積層の重要性
- Key points:
  - グリーンシートは、セラミック粉体と有機バインダーを含む薄い未焼成シート。
  - Murata のグリーンシートプロセスは、slurry mixing and dispersion, sheet forming, internal electrode printing, sheet lamination, pressing を含む。
  - MLCC ではセラミックシートと金属電極を交互に積層し、総電極面積が容量に関係する。
- Notes:
  - 公式の概要説明として強い。
  - 個別の調合条件・添加剤・ミル詳細は載っていない。

## S-MURATA-INORGANIC-MATERIALS

- Title: Inorganic Materials Technology
- Type: primary-corporate
- Organization: Murata Manufacturing
- URL: https://corporate.murata.com/technology/technology-platform/materials-technology/inorganic-materials
- Accessed: 2026-06-20
- Useful for:
  - BaTiO3 誘電体材料
  - 粒径・組成・微構造制御
  - micronization, firing, core-shell structure
- Key points:
  - BaTiO3 誘電体材料では、粒径、組成、微構造の精密制御が重要。
  - 高純度粉末のサブミクロン化、成形、精密焼成により、安定した電気特性・耐熱性を得るという説明がある。
- Notes:
  - 公式ページだが、詳細組成や工程条件は抽象度が高い。

## S-MURATA-MLCC-LINEUP

- Title: High Reliability and High Performance Enabled by Murata’s Multilayer Ceramic Capacitor (MLCC) Lineup
- Type: primary-corporate
- Organization: Murata Manufacturing
- URL: https://corporate.murata.com/en-global/technology/technology-applications/ceramiccapacitor
- Accessed: 2026-06-20
- Useful for:
  - MLCC の基本構造
  - 用途分野
  - 材料・設計・生産技術の統合
  - 製品ラインアップ
- Key points:
  - MLCC はセラミック誘電体層と電極層を交互に積層した部品。
  - Murata は材料技術、生産技術、設計提案、垂直統合製造を強みとして説明。
- Notes:
  - 製品紹介寄り。工程・材料の詳細確認には他ソースが必要。

## S-MURATA-IEEE-MILESTONE-NI

- Title: Murata Awarded IEEE Milestone: Contributing to the Development of Industry with the Commercialization of Multilayer Ceramic Capacitors Using Nickel Inner Electrodes
- Type: primary-corporate
- Organization: Murata Manufacturing
- URL: https://corporate.murata.com/newsroom/news/company/general/2024/0308
- Accessed: 2026-06-20
- Useful for:
  - Ni 内部電極の歴史
  - BME 化の背景
  - 低酸素濃度焼成の必要性
- Key points:
  - 初期 MLCC は貴金属内部電極を使い高コストだった。
  - Ni を使うためには金属酸化を避ける低酸素濃度で焼成できる誘電体材料が必要だった。
  - Murata は Ni-MLCC を 1973 年に開発し、1982 年に量産開始と説明している。
- Notes:
  - 歴史説明として有用。技術メカニズムは Kishi et al. と合わせる。

## S-MURATA-AGING-FAQ

- Title: What is the mechanism of the changing of the capacitance of ceramic capacitors over time?
- Type: primary-corporate
- Organization: Murata Manufacturing
- URL: https://www.murata.com/en-global/support/faqs/capacitor/ceramiccapacitor/char/0013
- Accessed: 2026-06-20
- Useful for:
  - BaTiO3 のペロブスカイト構造
  - キュリー温度
  - 強誘電性
  - エージング特性
- Key points:
  - 高誘電率セラミックコンデンサでは BaTiO3 が主成分として使われる。
  - BaTiO3 はキュリー温度以上で立方晶、以下で正方晶。
  - 自発分極・ドメインと容量経時変化が説明されている。
- Notes:
  - 基礎説明として有用。

## S-MURATA-DIELECTRIC-MATERIALS

- Title: Development of Dielectric Materials for Monolithic Ceramic Capacitors for Compact High-Capacitance Devices and Power Electronics
- Type: primary-corporate / technical article
- Organization: Murata Manufacturing
- URL: https://corporate.murata.com/technology/techmag/metamorphosis17/paper/02
- Accessed: 2026-06-20
- Useful for:
  - 希土類添加
  - MgO, MnO, glass 成分を含む組成例
  - Gd の BaTiO3 固溶、キュリー点シフト
  - 高温・高電圧向け信頼性
- Key points:
  - BaTiO3-Rare earth oxide-MgO-MnO-Li/Al/Ti/Si/O-glass のような組成例が示される。
  - Gd は Dy/Y と比べ BaTiO3 に固溶しやすく、キュリー点を低温側へシフトする説明がある。
  - BaZrO3 添加による温度特性改善が説明される。
- Notes:
  - Murata 固有の材料設計理解に重要。
  - ただし論文というより企業技術紹介。

## S-TDK-MLCC-PRODUCT-CENTER

- Title: Multilayer Ceramic Chip Capacitors
- Type: primary-corporate
- Organization: TDK
- URL: https://product.tdk.com/en/products/capacitor/ceramic/mlcc/index.html
- Accessed: 2026-06-20
- Useful for:
  - 小型・大容量化
  - 粒子微細化
  - 高精度積層
  - 1000層、サブミクロン層
- Key points:
  - TDK は MLCC の小型・大容量化に、材料技術、粒子微細化、誘電体・電極層の精密配置、1000層規模の積層、サブミクロン層厚を説明している。
- Notes:
  - 現代的な薄層化・高積層化の概要ソースとして有用。

## S-KISHI-2003-BME

- Title: Base-Metal Electrode-Multilayer Ceramic Capacitors: Past, Present and Future Perspectives
- Authors: Hiroshi Kishi, Youichi Mizuno, Hirokazu Chazono
- Journal: Japanese Journal of Applied Physics, 42, pp.1-15, 2003
- Type: primary-paper / invited review
- URL: https://www.jsap.or.jp/jsapi/Pdf/Number08/04_InvitedReviewPaper.pdf
- Accessed: 2026-06-20
- Useful for:
  - BME/Ni-MLCC の歴史
  - 非還元誘電体
  - BaTiO3 系添加剤
  - 希土類ドープ
  - MnO/Cr2O3 アクセプタ
  - CaO と A-site excess
  - 薄層化、積層数、容量式
  - 信頼性、酸素空孔
- Key points:
  - Pd 価格上昇や低コスト化を背景に、Ni/Cu などの base metal electrode への移行が進んだ。
  - Ni 内部電極には還元雰囲気焼成に耐える非還元 BaTiO3 系誘電体が必要。
  - 1990年代後半〜2000年代初頭に、誘電体層 2 µm 程度、500層以上、例として 1.8 µm・700層の X7R 100µF Ni-MLCC が示される。
  - MnO/Cr2O3 のアクセプタ添加、CaO、希土類酸化物が説明される。
- Notes:
  - このパックで最重要の学術レビュー。
  - 古い資料なので最新性能値としては使わず、歴史・機構理解の基礎に使う。

## S-KYOCERA-AVX-MLC-MATERIALS

- Title: Multilayer Ceramic Capacitors Materials and Manufacture
- Author: Manfred Kahn
- Type: technical-paper
- Organization: KYOCERA AVX
- URL: https://www.kyocera-avx.com/docs/techinfo/CeramicCapacitors/mlcmat.pdf
- Accessed: 2026-06-20
- Useful for:
  - MLC/MLCC の構造
  - BaTiO3 系誘電体
  - 温度特性と粒径
  - 材料・製造の概要
- Key points:
  - MLC capacitor は offset/interleaved planar electrodes を持つ monolithic block と説明。
  - BaTiO3 の高誘電率、量産性、温湿度耐性が説明される。
- Notes:
  - メーカー技術資料。詳細工程条件より基礎説明向き。

## S-KYOCERA-AVX-BATIO3-FAILURE

- Title: Conduction and Failure Mechanisms in Barium Titanate Based Ceramics Under Highly Accelerated Conditions
- Authors: B. S. Rawal, N. H. Chan
- Type: technical-paper
- Organization: KYOCERA AVX
- URL: https://www.kyocera-avx.com/docs/techinfo/CeramicCapacitors/barium.pdf
- Accessed: 2026-06-20
- Useful for:
  - BaTiO3 系 MLC の導通・故障メカニズム
  - ABD / TRA
  - 電圧加速、温度加速
  - 信頼性スクリーニング
- Key points:
  - ABD と TRA の二つの故障モードを整理。
  - ABD は delamination, cracks, thin spots などの外因性欠陥に関連。
  - TRA は electronic disorders, grain boundaries, second phase などの内因性要因に関連。
- Notes:
  - 古い可能性はあるが、故障メカニズムの基礎説明として有用。

## S-KEMET-LOW-VOLTAGE-DC

- Title: Ceramic Capacitors – Low Voltage DC
- Presenter / Organization: Wilmer Companioni, KEMET Electronics Corporation
- Type: technical-paper / presentation
- URL: https://www.psma.com/sites/default/files/uploads/files/Ceramic%20Capacitors%20%E2%80%93%20Low%20Voltage%20DC%20%28Wilmer%20Companioni%2C%20KEMET%20Electronics%20Corporation%29.pdf
- Accessed: 2026-06-20
- Useful for:
  - DC bias
  - Class II/III の電圧係数
  - BaTiO3 の相・分極の基礎図解
- Key points:
  - BaTiO3 の cubic/tetragonal と dipole 生成の説明がある。
  - Class II/III の DC bias, voltage coefficient の視覚説明に有用。
- Notes:
  - プレゼン資料。詳細な出典としては論文と併用する。

## S-KEMET-BME-HIGH-RELIABILITY

- Title: Base-Metal Electrode (BME) Ceramic Capacitors for High Reliability Applications
- Authors: Abhijit Gurav, Craig Scruggs, Richard Turner, Travis Ashburn
- Organization: KEMET Electronics Corporation
- Type: technical-paper
- URL: https://escies.org/download/webDocumentFile?id=60907
- Accessed: 2026-06-20
- Useful for:
  - BME C0G / X7R
  - 高信頼用途
  - BME と PME の比較
  - 高信頼性アプリケーション
- Key points:
  - BME technology の成長、Ni を含む base metal electrode、材料・プロセス・信頼性の進展が説明される。
  - BME C0G は CaZrO3-based linear dielectric material と説明される。
- Notes:
  - KEMET の技術資料。メーカー視点。

## S-JOHANSON-BASICS

- Title: Basics of Ceramic Chip Capacitors
- Organization: Johanson Dielectrics
- Type: technical-presentation
- URL: https://www.johansondielectrics.com/docs/3964/basics-of-ceramic-chip-capacitors.pdf
- Accessed: 2026-06-20
- Useful for:
  - MLCC 基本構造
  - 工程フロー
  - テープキャスト、スクリーン印刷、積層、焼成、端子、めっき
  - X7R/Y5V/NP0 の基礎
  - DC bias / aging の基礎説明
- Key points:
  - Ceramic powder → ceramic slurry → tape casting → screen printing → stacking → lamination → cutting → firing → termination → plating → testing の流れ。
  - Ni plating は termination と tin plating の間の barrier layer、tin は nickel 酸化防止と説明。
- Notes:
  - 基礎学習資料。詳細な工程条件や最新性能値には使わない。

## S-NETZSCH-MLCC-GRINDING

- Title: Multilayer Ceramic Capacitors
- Type: primary-corporate / equipment vendor
- Organization: NETZSCH Grinding & Dispersing
- URL: https://grinding.netzsch.com/en/chemicals-minerals/nano-applications/ceramic-multilayer-capacitors-mlcc
- Accessed: 2026-06-20
- Useful for:
  - MLCC 用スラリーの湿式粉砕・分散
  - TiO2 / BaTiO3 suspensions
  - バインダーとの混合
  - LMZ, Zeta RS など装置例
- Key points:
  - MLCC 原料は TiO2 や BaTiO3 の微細粉・添加剤の suspension として説明される。
  - スラリー製造に湿式粉砕・分散機が使われる。
- Notes:
  - 装置メーカーのマーケティングページ。粒径などの数値は一般事実として断定せず、装置選定・分散工程の入口情報として使う。

## S-TISTORY-SC-MSC-MILL

- Title: (Dispersion) 최신 매체 교반형 Mill
- Type: secondary / low-confidence
- URL: https://prd2021.tistory.com/27
- Accessed: 2026-06-20
- Useful for:
  - SC Mill / MSC Mill という語の公開ウェブ上の手掛かり
  - L/D 比、ビーズ偏り、ビーズパッキング、短 L/D、循環プロセスの仮説立案
- Key points:
  - 通常ミル L/D ≈ 3 に対し、SC/MSC は L/D = 1/3 とする説明がある。
  - 小径 media、圧力損失、ビーズ偏り、再凝集、摩耗・発熱リスクの議論がある。
  - MSC は粒子や分散剤へのダメージを抑え、再凝集を抑制するという説明がある。
- Notes:
  - 非公式ブログ。低信頼。
  - 公式装置メーカー資料、特許、論文で裏取りするまで、事実として扱わない。

## S-MDPI-FAILURE-OVERVIEW

- Title: Multilayer Ceramic Capacitors: An Overview of Failure Mechanisms, Perspectives, and Challenges
- Authors: K. Laadjal et al.
- Journal: Electronics, 2023
- Type: primary-paper / review, but MDPI
- URL: https://www.mdpi.com/2079-9292/12/6/1297
- Accessed: 2026-06-20
- Useful for:
  - MLCC failure mechanisms overview
  - 参考文献リスト
  - エネルギー貯蔵 MLCC などの関連文献探索
- Key points:
  - Failure mechanisms, perspectives, challenges を概説。
  - 多くの関連文献を辿る入口として使える。
- Notes:
  - MDPI 論文のため、一次の機構説明には Kishi, KYOCERA AVX, 個別論文を優先する。

## S-CHEN-2025-ENERGY-STORAGE-REVIEW

- Title: Research progress on multilayer ceramic capacitors for energy storage: review
- Authors: Shiqi Chen, Yiwen Ding, Haowen Mu, Wukui Tian, Xiaoling Deng, Rongli Gao, et al.
- Journal: Journal of Materials Science: Materials in Electronics, 36, Article 77, 2025
- Type: primary-paper / review
- DOI: 10.1007/s10854-024-14004-2
- URL: https://link.springer.com/article/10.1007/s10854-024-14004-2
- Accessed: 2026-06-20
- Useful for:
  - エネルギー貯蔵向け MLCC の研究進展
  - lead-based / lead-free の分類
  - 課題と将来展望
- Key points:
  - 2025年公開のエネルギー貯蔵 MLCC review。
- Notes:
  - 通常 MLCC の量産プロセス理解とは用途が異なるため、混同しない。

## S-NATURE-2025-GLOBAL-OPTIMIZED-MLCC

- Title: Global-optimized energy storage performance in multilayer ferroelectric ceramic capacitors
- Journal: Nature Communications, 2025
- Type: primary-paper
- URL: https://www.nature.com/articles/s41467-024-55491-5
- Accessed: 2026-06-20
- Useful for:
  - エネルギー貯蔵 MLCC の最新研究
  - MLCC prototype device
  - recoverable energy density, efficiency, discharge performance
- Key points:
  - MLCC デバイスで高い energy storage property を示す。
  - 実験と phase-field simulation を組み合わせた設計戦略。
- Notes:
  - 通常量産 MLCC とは用途・評価指標が異なる。

## S-NATURE-2025-HIGH-ENTROPY-BATIO3

- Title: High-entropy engineered BaTiO3-based ceramic capacitors with greatly enhanced high-temperature energy storage performance
- Journal: Nature Communications, 2025
- Type: primary-paper
- URL: https://www.nature.com/articles/s41467-025-56195-0
- Accessed: 2026-06-20
- Useful for:
  - BaTiO3 系高エントロピー誘電体
  - 高温エネルギー貯蔵性能
  - high-temperature applications
- Key points:
  - 高エントロピー BaTiO3 系 relaxor ceramic により、高温・広温度範囲でのエネルギー貯蔵性能を狙う。
- Notes:
  - 研究論文。量産 MLCC の一般工程へ直結させない。

## S-ZHAO-2021-LEAD-FREE-ENERGY-STORAGE

- Title: Perspectives and challenges for lead-free energy-storage multilayer ceramic capacitors
- Journal: Journal of Advanced Ceramics, 2021
- Type: primary-paper / review
- URL: https://link.springer.com/article/10.1007/s40145-021-0516-8
- Accessed: 2026-06-20
- Useful for:
  - lead-free energy-storage MLCC
  - エネルギー貯蔵 MLCC の課題整理
  - 2025 review 以前の重要レビュー
- Notes:
  - エネルギー貯蔵用途。通常 MLCC との混同注意。

## Patent / additional source candidates

### S-PATENT-WO2013145423A1

- Title: Laminated ceramic capacitor and method for producing same
- Type: patent
- URL: https://patents.google.com/patent/WO2013145423A1/en
- Useful for:
  - dielectric raw material powder finer than about 100 nm
  - green sheet and internal electrode planarization
- Notes:
  - 特許は実施例・請求範囲の読み方に注意。一般技術として断定しない。

### S-PATENT-CN111627698A

- Title: Nickel inner electrode slurry for MLCC
- Type: patent
- URL: https://patents.google.com/patent/CN111627698A/en
- Useful for:
  - Ni 内部電極ペースト / スラリー
  - flake nickel powder, dispersant, polymer resin, organic solvent
- Notes:
  - NE塗布厚や Ni 電極ペーストの理解に使える可能性。

## Sources to find next

以下は未解決論点に対して追加で探すべき出典。

| Need | Desired source |
|---|---|
| OM補正 | 社内用語集、特許、日本語工程資料、酸化物換算・有機物補正関連資料 |
| 0次調合 | 日本語特許、工程表、MLCC スラリー製造資料 |
| SC/MSC/MNミル | 装置メーカー公式資料、型式カタログ、特許、学会発表 |
| ΔSSA | MLCC スラリー、粉体分散、BET、粒度分布、ミル処理論文 |
| シート実効モル比 | BaTiO3 系配合設計、A/B site ratio、oxide molar ratio、グリーンシート組成管理資料 |
| NE塗布厚 | Ni internal electrode paste printing thickness, green sheet electrode printing, electrode continuity 論文・特許 |
| Murata Ca/Mg 置換 | Murata 特許、Murata 著者論文、BME-MLCC BaTiO3 Ca/Mg doped dielectric |
