Title: EBPM 関連 GitHub リソース一覧
Date: 2026-08-16
Category: EBPM
Slug: ebpm-github-resources

# EBPM 関連 GitHub リソース一覧

> 最終更新: 2026年8月16日  
> Evidence-Based Policy Making（EBPM）に関連するGitHub上のOSSツール、データセット、手法ライブラリ、知見集約リポジトリなどをカテゴリ別に整理しました。

---

## 1. 因果推論ライブラリ（総合）

| リポジトリ | 説明 | Stars | 言語 | ライセンス |
|-----------|------|-------|------|-----------|
| [py-why/dowhy](https://github.com/py-why/dowhy) | Microsoft主導。因果グラフとポテンシャルアウトカムを統合した因果推論フレームワーク。仮説の明示的モデリングと検証をサポート。 | 8,237 | Python | MIT |
| [py-why/EconML](https://github.com/py-why/EconML) | Microsoft Research。MLと計量経済学を融合した因果推論ツールキット。Double Machine Learningなどの手法を実装。 | - | Python | MIT相当 |
| [uber/causalml](https://github.com/uber/causalml) | Uber。アップリフトモデリングと因果推断のMLアルゴリズム群。政策効果の異質性分析に有用。 | 5,938 | Python | BSD系 |
| [pymc-labs/CausalPy](https://github.com/pymc-labs/CausalPy) | 準実験的な設定での因果推論をベイズアプローチ（PyMC）で実現。DID・回帰不連続・合成制御などに対応。 | 1,135 | Python | Apache-2.0 |
| [BiomedSciAI/causallib](https://github.com/biomedsciai/causallib) | IBM Research。モジュール型の因果推論分析・モデル評価パッケージ。IPW・標準化・T-learnerなど。 | 812 | Python | Apache-2.0 |
| [jakobrunge/tigramite](https://github.com/jakobrunge/tigramite) | 時系列データに特化した因果推論パッケージ。PCMCIなどの手法を実装。パネルデータの因果探索に有用。 | 1,679 | Python | GPL-3.0 |
| [google/tfp-causalimpact](https://github.com/google/tfp-causalimpact) | Google。TensorFlow ProbabilityベースのCausalImpact実装。時系列の介入効果推定。 | 158 | Python | Apache-2.0 |
| [amazon-science/azcausal](https://github.com/amazon-science/azcausal) | Amazon Science。DID・Synthetic DID・Panelデータ分析の統合フレームワーク。 | 46 | Python/R | Apache-2.0 |
| [Sanofi-Public/CImpact](https://github.com/Sanofi-Public/CImpact) | 時系列分析向け因果推論ライブラリ。 | 44 | Python | 独自 |

---

## 2. 差分の差分法（DiD）・合成制御法（SCM）関連

| リポジトリ | 説明 | Stars | 言語 | ライセンス |
|-----------|------|-------|------|-----------|
| [synth-inference/synthdid](https://github.com/synth-inference/synthdid) | Synthetic Difference-in-Differencesの標準的なR実装。Arkhangelsky et al. (2021)。 | 312 | R | BSD-3 |
| [igerber/diff-diff](https://github.com/igerber/diff-diff) | PythonでのDID総合パッケージ。Callaway-Sant'Anna・Synthetic DiD・HonestDiD・event studyをsklearn風APIで提供。 | 274 | Python | MIT |
| [bernardodionisi/differences](https://github.com/bernardodionisi/differences) | PythonでのDID実装。パネルデータの因果推論に特化。 | 114 | Python | GPL-3.0 |
| [Daniel-Pailanir/sdid](https://github.com/Daniel-Pailanir/sdid) | Synthetic Difference-in-DifferencesのStata実装。 | 97 | Stata | GPL-3.0 |
| [yo5uke/coresynth](https://github.com/yo5uke/coresynth) | Rでの高速・統一型合成制御法パッケージ。SCM・SDID・GSC・MCなどを一つのformulaインターフェースで。 | 4 | R/C++ | 独自 |
| [dropout009/sdid_python](https://github.com/dropout009/sdid_python) | Synthetic DiDのPython実装（Jupyter Notebook形式）。 | 17 | Python | - |

---

## 3. 政策学習・政策評価ツール

| リポジトリ | 説明 | Stars | 言語 | ライセンス |
|-----------|------|-------|------|-----------|
| [grf-labs/policytree](https://github.com/grf-labs/policytree) | 二重頑健的経験的厚生最大化に基づく政策学習（ツリー構造）。 | 87 | R/C++ | MIT |
| [oguerrer/ppi](https://github.com/oguerrer/ppi) | Policy Priority Inferenceモデル。エージェントベースシミュレーションでSDGs達成の政策優先度を推定。 | 13 | Python | MIT |
| [KDiazOrdaz/Machine-learning-in-policy-evaluation-new-tools-for-causal-inference](https://github.com/KDiazOrdaz/Machine-learning-in-policy-evaluation-new-tools-for-causal-inference) | 政策評価へのML適用に関する論文付属コード。 | 12 | R | BSD-2 |
| [CausalML/confounding-robust-policy-improvement](https://github.com/CausalML/confounding-robust-policy-improvement) | 観測されていない交絡下でのミニマックス政策学習。 | 4 | Python | - |
| [human-technology-institute/bayesian-causal-policy](https://github.com/human-technology-institute/bayesian-causal-policy) | 政策意思決定のためのベイズ因果探索。 | 1 | Python | Apache-2.0 |
| [human-technology-institute/BAT-for-social-policy](https://github.com/human-technology-institute/BAT-for-social-policy) | 社会政策のためのベイズ適応型試行（Bayesian Adaptive Trials）のシミュレーションコード。 | - | Python | - |

---

## 4. 政策シミュレーション・制度モデリング

| リポジトリ | 説明 | Stars | 言語 | ライセンス |
|-----------|------|-------|------|-----------|
| [openfisca/openfisca-core](https://github.com/openfisca/openfisca-core) | 税制・社会保障制度のマイクロシミュレーションエンジン。"Legislation as Code"を実現。 | 234 | Python | AGPL-3.0 |
| [openfisca/openfisca-policy](https://github.com/openfisca/openfisca-policy) | OpenFiscaの政策指向サーベイシミュレーションヘルパー。 | 0 | Python | - |
| [PolicyEngine/policyengine-app](https://github.com/PolicyEngine/policyengine-app) | 公共政策の影響を計算・可視化するWebアプリ。税制・給付政策のシミュレーション。 | 67 | Python/TS | AGPL-3.0 |
| [PolicyEngine/policyengine.py](https://github.com/PolicyEngine/policyengine.py) | PolicyEngineのPythonパッケージ。税・給付モデルの可視化・分析統合。 | 6 | Python | AGPL-3.0 |
| [STAPM Platform](https://stapm-platform.github.io/) | 公衆衛生政策シミュレーションのための技術基盤。英国Sheffield大学。 | - | R/Python | - |

---

## 5. EBPMデータベース・知見集約

| リポジトリ | 説明 | Stars | 言語 | ライセンス |
|-----------|------|-------|------|-----------|
| [CyberAgentAILab/EBPMDB](https://github.com/CyberAgentAILab/EBPMDB) | 証拠に基づく政策のための研究成果データベース。国内外の政策介入エビデンスをレビュー形式で集約。 | 35 | TypeScript | MIT |
| [nestauk/discovery_policy_atlas](https://github.com/nestauk/discovery_policy_atlas) | AIを活用した政策立案支援ツール（Policy Atlas）。 | 5 | Python/TS | AGPL-3.0 |

---

## 6. 政策文書分析・モニタリングツール

| リポジトリ | 説明 | Stars | 言語 | ライセンス |
|-----------|------|-------|------|-----------|
| [colossus-lab/openarg_backend](https://github.com/colossus-lab/openarg_backend) | アルゼンチン政府オープンデータのAI分析エンジン。マルチエージェント・NL2SQL・セマンティックキャッシング。 | 139 | Python | MIT |
| [policybot-io/UNREDACTED](https://github.com/policybot-io/UNREDACTED) | 国家政府の支出・予算・債務・政策分析・政治家献金モニタリングのAIアプリ。 | 5 | Python/TS | 独自 |
| [AgoraDMV/BillTrax](https://github.com/AgoraDMV/BillTrax) | 米国議会法案のインテリジェンスプラットフォーム。法案テキストの構造化・資金変化追跡・AI要約。 | 1 | Python/TS | - |
| [christian-camille/uk-policy-tracker](https://github.com/christian-camille/uk-policy-tracker) | 英政府・議会APIを取り込んだ政策トラッキングプラットフォーム。NLPエンティティマッチング・グラフ探索。 | 0 | Python/TS | - |
| [DU-CAID/policy-scoring-dashboard](https://github.com/DU-CAID/policy-scoring-dashboard) | 政策文書（PDF/DOCX/TXT）をEBPMの5次元でスコアリングするダッシュボード。 | 0 | Python | MIT |
| [nelabdiel/diff_policies](https://github.com/nelabdiel/diff_policies) | 政策文書の比較分析プラットフォーム。Ollama連携のAI分析機能付き。 | 4 | Python/JS | - |
| [Varnasr/PolicyDhara](https://github.com/Varnasr/PolicyDhara) | インド開発政策の自動更新トラッカー。 | 1 | Astro/JS | MIT |
| [christian-arthur/ai-policy-advisor](https://github.com/christian-arthur/ai-policy-advisor) | ローカルLLMを用いた政策アドバイスのR/Python統合ツール。 | 0 | R/Python | - |

---

## 7. 日本のEBPM・オープンデータ関連

| リポジトリ | 説明 | Stars | 言語 | ライセンス |
|-----------|------|-------|------|-----------|
| [japan-opendata/awesome-japan-opendata](https://github.com/japan-opendata/awesome-japan-opendata) | 日本のオープンデータ情報一覧・まとめ。 | 162 | Markdown | CC-BY-4.0 |
| [CyberAgentAILab/EBPMDB](https://github.com/CyberAgentAILab/EBPMDB) | （重複）日本発のEBPM研究成果データベース。 | 35 | TypeScript | MIT |

### 参考：日本政府・研究機関のEBPM関連ページ
- [内閣府 EBPMへの取組](https://www.cao.go.jp/others/kichou/ebpm/ebpm.html) — 内閣府のEBPM推進体制・各局の取組紹介
- [行政改革推進会議 EBPMの推進](https://www.gyoukaku.go.jp/ebpm/) — 統計データ提供ガイドライン・行政事業レビュー支援
- [社会データ構造化センター 政府統計を用いたEBPM研究プロジェクト](https://csds.rois.ac.jp/research/omd/pj4/) — 公的ミクロデータを活用した因果的Evidenceの発信

---

## 8. その他の関連ツール・フレームワーク

| リポジトリ | 説明 | Stars | 言語 | ライセンス |
|-----------|------|-------|------|-----------|
| [mikepsinn/optimitron](https://github.com/mikepsinn/optimitron/tree/main/packages/opg) | Optimal Policy Generator。因果エビデンス・厚生関数・Bradford Hill基準を用いた政策ランキング・スコアリング。 | - | TypeScript | - |
| [random-walks/factor-factory](https://github.com/random-walks/factor-factory) | ドメイン非依存の因子モデル＋分析パイプラインフレームワーク。DiD・SDID・SCM・RDDなどをプラガブルエンジンで統合。 | 1 | Python | MIT |

---

## カテゴリ別おすすめ（導入優先度）

### まず押さえておきたい「核」ライブラリ
1. **py-why/dowhy** — 因果推論の全体像を学び・実装するのに最適
2. **py-why/EconML** — ML×計量経済学の最先端手法（DML・CATE推定）
3. **uber/causalml** — 政策効果の異質性分析・アップリフトモデリング
4. **pymc-labs/CausalPy** — ベイズ準実験分析の統合環境

### 政策評価の「定番」手法
5. **synth-inference/synthdid** / **igerber/diff-diff** — DiD・Synthetic DiD
6. **grf-labs/policytree** — データ駆動型の政策ルール学習

### 制度シミュレーション
7. **openfisca/openfisca-core** — 制・社会保障の「コード化」
8. **PolicyEngine/policyengine-app** — 政策影響の可視化・市民参加

### 日本のEBPMエコシステム
9. **CyberAgentAILab/EBPMDB** — 日本語の政策エビデンスデータベース
10. **japan-opendata/awesome-japan-opendata** — 国内オープンデータの入口

---

## 補足：EBPMの手法カテゴリと対応ツール

| 手法カテゴリ | 代表的手法 | 対応ツール例 |
|-------------|-----------|-------------|
| ランダム化較試験（RCT） | A/Bテスト・Field Experiment | DoWhy, CausalML |
| 差分の差分法（DiD） | 2×2 DiD, Callaway-Sant'Anna, Synthetic DiD | synthdid, diff-diff, differences, azcausal, CausalPy |
| 合成制御法（SCM） | Abadie et al. SCM, Generalized SCM | coresynth, CausalPy |
| 回帰不連続設計（RDD） | Sharp/Fuzzy RDD | CausalPy, rdrobust (R) |
| マッチング・重み付け | Propensity Score, IPW, Covariate Balancing | causallib, DoWhy, MatchIt (R) |
| 政策学習・最適化 | Policy Tree, Doubly Robust Learning | policytree, EconML, confounding-robust-policy-improvement |
| 構造型モデリング・シミュレーション | マイクロシミュレーション, ABM | OpenFisca, ppi, STAPM |
| 因果探索 | ベイズネット, PCMCI | DoWhy, tigramite |
| 時系列介入分析 | CausalImpact, Interrupted Time Series | tfp-causalimpact, CausalPy, CImpact |

---

*本一覧はGitHub上の公開リポジトリを対象にしています。今後の追加・修正はPull RequestやIssueで歓迎します。*
