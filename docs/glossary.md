# MLCC Glossary

この用語集は、過去会話で扱った MLCC 関連語を、確度付きで整理したものです。

## ステータス凡例

- `FACT`: 公開出典で直接確認できる
- `WORKING UNDERSTANDING`: 出典に基づく作業理解
- `HYPOTHESIS`: 直接出典なしの仮説
- `UNVERIFIED`: 出典未確認。社内用語・文脈依存の可能性あり
- `OPEN QUESTION`: 追加調査が必要

---

## MLCC

- Status: FACT
- Definition: Multilayer Ceramic Capacitor。セラミック誘電体層と金属電極層を交互に積層したコンデンサ。
- Notes: 内部電極が左右の端子に交互接続され、多数の小容量コンデンサが並列化された構造と理解できる。
- Sources: `S-KISHI-2003-BME`, `S-KYOCERA-AVX-MLC-MATERIALS`, `S-JOHANSON-BASICS`

## 誘電体層

- Status: FACT
- Definition: MLCC 内で電荷を蓄える電界が形成されるセラミック層。
- Notes: 高容量化には薄層化が効くが、薄層化に伴い欠陥・絶縁信頼性・電極連続性への要求が厳しくなる。
- Sources: `S-KISHI-2003-BME`, `S-TDK-MLCC-PRODUCT-CENTER`

## 内部電極

- Status: FACT
- Definition: 誘電体層の間に形成される金属電極。BME-MLCC では Ni が代表例。
- Notes: 内部電極は左右の端子に交互に接続される。
- Sources: `S-KISHI-2003-BME`, `S-MURATA-GREEN-SHEET`, `S-MURATA-IEEE-MILESTONE-NI`

## 外部電極 / 端子電極

- Status: FACT
- Definition: MLCC チップ両端に形成され、内部電極と外部回路を接続する電極。
- Notes: 一般的には端子形成後に Ni めっき、Sn めっきなどが行われる。Ni はバリア、Sn ははんだ付け性に関係する。
- Sources: `S-JOHANSON-BASICS`

## BaTiO3 / チタン酸バリウム

- Status: FACT
- Definition: 高誘電率系 MLCC の代表的な主成分。ペロブスカイト構造を持つ強誘電体材料。
- Notes: キュリー温度以上で立方晶、以下で正方晶となり、自発分極と容量特性に関わる。
- Sources: `S-MURATA-AGING-FAQ`, `S-KEMET-LOW-VOLTAGE-DC`, `S-KYOCERA-AVX-MLC-MATERIALS`

## 母材

- Status: WORKING UNDERSTANDING
- Definition: MLCC 文脈では、添加剤を入れる前の主たる誘電体材料、典型的には BaTiO3 系材料を指すと理解する。
- Notes: 「母材」は一般材料工学の matrix/base material に近いが、社内文脈では対象範囲が異なる可能性がある。
- Sources: `S-MURATA-INORGANIC-MATERIALS`, `S-MURATA-AGING-FAQ`

## 添加剤 / ドーパント

- Status: FACT / WORKING UNDERSTANDING
- Definition: BaTiO3 系誘電体に少量または一定量添加され、温度特性、信頼性、焼結、還元耐性、粒成長、酸素空孔などを制御する成分。
- Examples: MnO, Cr2O3, CaO, MgO, 希土類酸化物, BaZrO3, glass 成分など。
- Sources: `S-KISHI-2003-BME`, `S-MURATA-DIELECTRIC-MATERIALS`

## 希土類添加

- Status: FACT
- Definition: Dy, Ho, Er, Y, Gd などの希土類酸化物を BaTiO3 系に添加する設計。
- Notes: BME/Ni-MLCC の非還元誘電体、信頼性、コアシェル構造、絶縁性に関係する。
- Sources: `S-KISHI-2003-BME`, `S-MURATA-DIELECTRIC-MATERIALS`

## MgO

- Status: FACT / WORKING UNDERSTANDING
- Definition: Murata の材料例や Kishi et al. の BaTiO3-MgO-R2O3 系で見られる添加成分。
- Notes: 役割は組成・サイト占有・希土類との組合せに依存する。単独で「何のため」と断定しない。
- Sources: `S-KISHI-2003-BME`, `S-MURATA-DIELECTRIC-MATERIALS`

## MnO / Mn 添加

- Status: FACT
- Definition: BaTiO3 系非還元誘電体で、アクセプタ的に働き絶縁抵抗低下を抑える文脈で扱われる添加剤。
- Notes: Kishi et al. 2003 では MnO や Cr2O3 のアクセプタ添加が説明されている。
- Sources: `S-KISHI-2003-BME`

## CaO / Ca 置換

- Status: FACT / OPEN QUESTION
- Definition: Kishi et al. 2003 では、A-site excess 条件下で CaO が TiO2 site に入り、MnO に似たアクセプタとして働く説明がある。
- Notes: ユーザーが関心を持っていた「Murata が Ba の一部を Ca や Mg で置換する技術」と完全に同じかは未確認。特許・論文調査が必要。
- Sources: `S-KISHI-2003-BME`

## BaZrO3 / Zr

- Status: FACT / WORKING UNDERSTANDING
- Definition: BaTiO3 系誘電体における温度特性・相挙動・固溶状態調整に関係する候補成分。
- Notes: Murata 誘電体材料ページでは、Gd 添加 BaTiO3 に BaZrO3 を加えることで温度特性改善を検討した説明がある。
- Sources: `S-MURATA-DIELECTRIC-MATERIALS`

## シフター

- Status: UNVERIFIED
- Definition: 過去会話では、BaTiO3 系誘電体の誘電率ピーク・相転移温度をずらす添加成分として整理した。
- Notes: MLCC 業界の一般用語か、社内用語か未確認。出典未確認。
- Sources: 出典未確認

## デプレッサー

- Status: UNVERIFIED
- Definition: 過去会話では、誘電率ピークを抑えて温度特性を平坦化する添加成分として整理した。
- Notes: MLCC 業界の一般用語か、社内用語か未確認。出典未確認。
- Sources: 出典未確認

## BME

- Status: FACT
- Definition: Base Metal Electrode。Ni や Cu などの卑金属を内部電極に使う MLCC 技術。
- Notes: Pd 等の貴金属に比べコスト低減に寄与するが、Ni 酸化を避けるため還元雰囲気焼成と非還元誘電体が必要。
- Sources: `S-KISHI-2003-BME`, `S-MURATA-IEEE-MILESTONE-NI`, `S-KEMET-BME-HIGH-RELIABILITY`

## 非還元誘電体

- Status: FACT
- Definition: 還元雰囲気で焼成しても絶縁抵抗低下を抑えられる BaTiO3 系誘電体。
- Notes: Ni 内部電極 MLCC の実現に重要。
- Sources: `S-KISHI-2003-BME`

## 還元雰囲気

- Status: FACT / WORKING UNDERSTANDING
- Definition: Ni などの卑金属内部電極を酸化させないための低酸素濃度・還元性の焼成雰囲気。
- Notes: 誘電体側では酸素空孔や電子伝導による絶縁低下を抑える材料設計が必要。
- Sources: `S-MURATA-IEEE-MILESTONE-NI`, `S-KISHI-2003-BME`

## 酸素空孔

- Status: FACT / WORKING UNDERSTANDING
- Definition: 酸素サイトの欠陥。BaTiO3 系誘電体では還元、ドーパント、リーク、絶縁劣化、信頼性と関係する。
- Notes: 過去会話では薄層化に伴う信頼性懸念として重視。
- Sources: `S-KISHI-2003-BME`, `S-MDPI-FAILURE-OVERVIEW`

## 一次粒子

- Status: WORKING UNDERSTANDING
- Definition: 粉体を構成する最小に近い粒子単位。BaTiO3 粉体では結晶性・粒径・表面状態が重要。
- Notes: 分散工程で壊したくない対象として扱った。
- Sources: 一般粉体工学として妥当。MLCC 固有の出典は要追加。

## 二次粒子

- Status: WORKING UNDERSTANDING
- Definition: 一次粒子が凝集した集合体。
- Notes: スラリー化では二次粒子をほぐし、一次粒子を過度に壊さないことが理想という作業理解。
- Sources: 一般粉体工学として妥当。MLCC 固有の出典は要追加。

## 誘電体スラリー

- Status: FACT / WORKING UNDERSTANDING
- Definition: BaTiO3 等のセラミック粉体を溶媒、バインダー、分散剤などと混ぜた、シート成形前の液状材料。
- Notes: 分散状態、粘度、固形分、欠陥がグリーンシート品質に効く。
- Sources: `S-MURATA-GREEN-SHEET`, `S-JOHANSON-BASICS`, `S-NETZSCH-MLCC-GRINDING`

## グリーンシート

- Status: FACT
- Definition: 焼成前の薄いセラミックシート。セラミック粉体と有機バインダーを含む。
- Notes: MLCC の誘電体層の前駆体。薄く均一に形成し、電極印刷・積層する。
- Sources: `S-MURATA-GREEN-SHEET`, `S-JOHANSON-BASICS`

## 一次調合

- Status: UNVERIFIED
- Definition: 過去会話では、粉体・添加剤・溶媒・分散剤などの初期混合・分散工程ではないかと推定。
- Notes: 社内工程名の可能性がある。公開情報で工程名として未確認。
- Sources: 出典未確認

## 二次調合

- Status: UNVERIFIED
- Definition: 過去会話では、一次調合後にバインダー・可塑剤などを加え、塗工可能なスラリーへ調整する工程ではないかと推定。
- Notes: 社内工程名の可能性がある。公開情報で工程名として未確認。
- Sources: 出典未確認

## 0次調合

- Status: OPEN QUESTION / UNVERIFIED
- Definition: ユーザーが聞いた用語。粉体合成・前処理・予備混合・添加剤母液作成などの可能性があるが未確認。
- Notes: 公開情報で一般用語として確認できていない。社内用語の可能性が高い。
- Sources: 出典未確認

## OM補正

- Status: OPEN QUESTION / UNVERIFIED
- Definition: MLCC 文脈でユーザーが質問した用語。過去会話では「一次混合で入れたものを除去するための何かか」と問題提起された。
- Possible interpretations:
  - Organic Material 補正
  - Oxide Material / Oxide Mole 補正
  - Oxide molar ratio 補正
  - Over-milling 補正
  - 社内略語
- Notes: 公開検索では MLCC 文脈で明確な該当なし。断定禁止。
- Sources: 出典未確認

## SSA / 比表面積

- Status: FACT / WORKING UNDERSTANDING
- Definition: Specific Surface Area。単位質量あたりの表面積。
- Notes: 粉体粒径、表面状態、分散剤必要量、焼結性、凝集解砕状態に関係する。
- Sources: 一般粉体工学として確立。MLCC 固有の管理値は出典未確認。

## ΔSSA

- Status: UNVERIFIED / WORKING UNDERSTANDING
- Definition: 処理前後の SSA 変化量として整理。
- Notes: 凝集解砕で増える可能性がある一方、過大なら一次粒子損傷・微粉化の懸念。社内定義・計算式・管理閾値は未確認。
- Sources: 出典未確認

## シートSSA

- Status: UNVERIFIED
- Definition: 誘電体グリーンシート側、またはシート化前後の粉体・固形分の比表面積指標と推定。
- Notes: 測定対象が粉体なのか、スラリー乾燥物なのか、シート粉砕物なのか未確認。
- Sources: 出典未確認

## シート実効モル比

- Status: UNVERIFIED / HYPOTHESIS
- Definition: 誘電体グリーンシート中で実際に効く Aサイト/Bサイトのモル比、例 `(Ba + Ca) / (Ti + Zr)` のような指標ではないかと推定。
- Notes: 社内計算式が重要。単純な原料投入比ではなく、揮発、ロス、補正、添加剤換算を含む可能性がある。
- Sources: 出典未確認

## NE塗布厚

- Status: UNVERIFIED / HYPOTHESIS
- Definition: `NE = Nickel Electrode` と見て、Ni 内部電極ペーストの塗布厚・印刷厚と推定。
- Notes: 正式略語か未確認。誘電体調合というより、電極印刷工程に近い管理項目と考える。
- Sources: 出典未確認

## SCミル

- Status: UNVERIFIED / HYPOTHESIS
- Definition: 媒体撹拌型ミル、短 L/D、循環分散、ビーズ偏り抑制に関係する可能性がある。
- Notes: 低信頼の韓国語ブログに SC Mill の説明あり。公式出典未確認。
- Sources: `S-TISTORY-SC-MSC-MILL` は低信頼候補。要公式裏取り。

## MSCミル

- Status: UNVERIFIED / HYPOTHESIS
- Definition: SCミルより微小メディア・ナノ分散・低ダメージ分散に関係する可能性がある。
- Notes: 摩耗が速い仮説と、短 L/D により局所過負荷を抑える仮説が併存。断定不可。
- Sources: `S-TISTORY-SC-MSC-MILL` は低信頼候補。要公式裏取り。

## MNミル

- Status: OPEN QUESTION / UNVERIFIED
- Definition: 過去会話で出たミル名。公開出典未確認。
- Notes: 装置名、型式、略称、社内呼称のいずれか不明。
- Sources: 出典未確認

## ビーズミル / 媒体撹拌型ミル

- Status: FACT / WORKING UNDERSTANDING
- Definition: ビーズなどの媒体を撹拌し、粉体の粉砕・凝集解砕・分散を行う装置群。
- Notes: MLCC スラリーの湿式粉砕・分散装置として NETZSCH などのメーカーが用途を示している。
- Sources: `S-NETZSCH-MLCC-GRINDING`

## ビーズパッキング

- Status: WORKING UNDERSTANDING / UNVERIFIED
- Definition: スラリー流れや圧力損失によりビーズが偏り、局所的な過負荷・発熱・摩耗・分散不均一を招く現象として整理。
- Notes: SC/MSC ミル説明に出てくるが、公式出典未確認。
- Sources: `S-TISTORY-SC-MSC-MILL` は低信頼候補。

## コアシェル構造

- Status: FACT / WORKING UNDERSTANDING
- Definition: BaTiO3 粒子や焼結粒子において、中心部と周辺部で組成・相・ドーパント濃度が異なる微構造。
- Notes: 温度特性、信頼性、希土類ドープ、薄層 MLCC と関係する。
- Sources: `S-MURATA-INORGANIC-MATERIALS`, `S-KISHI-2003-BME`

## DCバイアス特性

- Status: FACT
- Definition: 印加 DC 電圧により実効静電容量が低下する特性。Class II/III セラミックで重要。
- Notes: BaTiO3 系の分極・ドメイン挙動に関係する。実装上、定格容量だけでなく使用電圧での実効容量を見る必要がある。
- Sources: `S-KEMET-LOW-VOLTAGE-DC`, `S-JOHANSON-BASICS`

## エージング特性

- Status: FACT
- Definition: 高誘電率セラミックコンデンサで、時間経過とともに容量が低下する現象。
- Notes: Murata FAQ は BaTiO3 の強誘電性・キュリー温度・ドメインと関連づけて説明している。
- Sources: `S-MURATA-AGING-FAQ`

## ABD

- Status: FACT
- Definition: Avalanche Breakdown。KYOCERA AVX 資料で扱われる故障モードの一つ。
- Notes: 外因性欠陥、例として層間剥離、クラック、薄い箇所などに関連付けられている。
- Sources: `S-KYOCERA-AVX-BATIO3-FAILURE`

## TRA

- Status: FACT
- Definition: Thermal Runaway。KYOCERA AVX 資料で扱われる故障モードの一つ。
- Notes: 漏れ電流の増加、自己発熱、内因性欠陥などに関係する。
- Sources: `S-KYOCERA-AVX-BATIO3-FAILURE`
