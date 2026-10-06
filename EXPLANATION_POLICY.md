# IMF Article IV 解説方針

このリポジトリでは、IMF Article IV Consultation の公表資料を、単なる要約ではなく、**その国が直面していたマクロ経済上のトレードオフ、IMF staff の診断、当局の反論・補足、Executive Board の評価を切り分けて読める形**で日本語解説する。

## 1. 一次資料を単位ごとに区別する

Article IV の公表パッケージには複数の文書が含まれる。原則として、次を混同しない。

- **Staff Report**: IMF staff の分析・提言。
- **Debt Sustainability Analysis (DSA) / Staff Supplement**: 債務のベースラインとストレス・シナリオ。
- **Staff Statement**: Board 討議直前までに入った新情報によるアップデート。
- **Public Information Notice (PIN)**: Executive Board 討議の要約。staff の意見と Board の最終的な見解は必ずしも同一ではない。
- **Statement by the Executive Director**: 当該国当局側の立場を示す文書。staff の診断に対する異論や政策上の優先順位を確認する。
- **Annex / Statistical Issues**: データの質、制度、IMF・World Bank との関係など、本文の分析を解釈するための制約条件。

解説では、「IMF が言った」と一括りにせず、誰の見解なのかを明記する。

## 2. 解説の中心は economic mechanism に置く

数値を並べるだけでなく、原資料が想定している因果メカニズムを明示する。特に資源国では、

\[
\text{resource revenue boom}
\rightarrow
\text{public spending / liquidity}
\rightarrow
\text{inflation・real appreciation}
\rightarrow
\text{non-resource tradables の競争力}
\rightarrow
\text{将来の税収・外貨獲得力・債務持続可能性}
\]

という連鎖を確認する。

同時に、戦後復興国では、

\[
\text{public investment}
\rightarrow
\text{infrastructure・human capital}
\rightarrow
\text{private-sector productivity}
\rightarrow
\text{non-resource growth}
\]

という反対方向の便益もあるため、**「支出を増やすか減らすか」ではなく、吸収能力、投資収益率、輸入比率、制度能力、実施速度を含むトレードオフ**として説明する。

## 3. staff と当局の争点を明示する

政策対立がある場合は、staff の推奨だけを正解として書かない。例えば財政アンカーについて、

- staff は non-oil primary balance を重視するのか、
- 当局は capital expenditure を別扱いすべきだと考えているのか、
- その違いはどの economic assumption から来るのか、

まで整理する。

Exchange-rate policy でも、インフレ抑制・実質増価への調整と、非資源部門の競争力・ドル化・金融市場の浅さとのトレードオフを分けて書く。

## 4. ベースラインとリスク・シナリオを混同しない

DSA や中期見通しについては、

1. baseline が何を仮定しているか、
2. その仮定が成立すれば何が起きるか、
3. どの仮定が崩れると何が悪化するか、

を分ける。

stress test は「予測」ではなく、脆弱性を示す反実仮想として扱う。特に、低成長、資源輸出減少、財政調整の遅れ、為替変動などのどれが debt dynamics を最も悪化させるかを確認する。

## 5. 数値は economic meaning とセットで使う

主要な数値は、次の用途に限定して本文に残す。

- 景気局面を示す数値
- 政策余地を示す数値
- 資源依存度を示す数値
- staff と当局の争点を示す数値
- ストレス・シナリオの大きさを示す数値

表の全数値を書き写すのではなく、本文の claim を判定するために必要な数値を優先する。

## 6. 当時の資料と後知恵を分離する

原則として、その Article IV が公表された時点で利用可能だった情報だけで文書の論理を再構成する。後年の実績や後続危機を使う場合は、必ず「後年から見た検証」として別節に分ける。

## 7. データ品質を分析の一部として扱う

Statistical Issues で指摘された欠測、遅延、推計依存、対象地域の偏りなどは、単なる付録ではない。成長率、財政収支、外貨準備、実質為替レートなどの評価にどの程度注意が必要かを本文で明示する。

## 8. 各国フォルダの標準構成

各国・各年について、原則として次の2本を作成する。

- \`YYYY-article-iv-detailed.md\`: 原資料の構成に沿った詳細解説。staff / Board / authorities の違い、モデル・シナリオ、重要数値を含む。
- \`YYYY-article-iv-summary.md\`: 初見の読者向けの記事。背景、何が問題だったか、IMF の主張、当局の主張、何を学べるかを短く整理する。

必要に応じて \`README.md\` を置き、同一国の複数年資料を時系列でつなぐ。

---

この方針の目的は、Article IV を「IMF の政策提言集」としてではなく、**特定時点の国のマクロ経済をめぐる診断・政策トレードオフ・不確実性・当局との論争を記録した一次資料**として読むことにある。
