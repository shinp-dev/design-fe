# カリキュラム

## 学習方針

Design FEでは「制作能力」より先に「診断能力」を育てます。

UIを見て、

1. 何を感じたか
2. 何が変わったか
3. どの原則が関係するか
4. なぜその印象になったか
5. 何を守って直すべきか

を順に説明できることを目標にします。

---

## 01 視覚的階層

### 学ぶこと
- 視覚的階層
- フォーカルポイント
- 視覚的ウェイト
- 強調
- 視線誘導
- 情報の優先順位

### できるようになること
「全部同じくらい目立っている」「主役が分からない」を説明できる。

---

## 02 余白とネガティブスペース

### 学ぶこと
- whitespace
- negative space
- padding / marginとの違い
- 情報密度
- 呼吸する空間
- 主役を成立させる空白

### できるようになること
空白を「余っている場所」ではなく、構成要素として扱える。

---

## 03 ゲシュタルト原則

### 学ぶこと
- 近接
- 類同
- 連続
- 閉合
- 共通領域
- 図と地

### できるようになること
人がなぜ要素を同じグループとして見るのかを説明できる。

---

## 04 整列・グリッド・バランス

### 学ぶこと
- alignment
- grid
- baseline
- symmetry / asymmetry
- visual balance
- rhythm
- repetition

### できるようになること
「揃っていない」と「意図的に崩している」を区別する。

---

## 05 タイポグラフィ

### 学ぶこと
- font size
- weight
- line-height
- letter-spacing
- measure
- hierarchy
- line break
- readability / legibility

### できるようになること
文字が「入るか」だけでなく、「読ませ方」を評価できる。

---

## 06 色

### 学ぶこと
- 色相・彩度・明度
- コントラスト
- 配色
- アクセント
- 色による階層化
- 状態表現
- アクセシビリティ

### できるようになること
「色が変」を分解して説明できる。

---

## 07 アフォーダンスとインタラクション

### 学ぶこと
- affordance
- signifier
- feedback
- mapping
- consistency
- hit area
- disabled / selected / pressed state

### できるようになること
押せる・選べる・戻れることが視覚的に伝わるか判断できる。

---

## 08 レスポンシブデザイン

### 学ぶこと
- reflow
- breakpoint
- constraint
- priority
- content preservation
- graceful degradation
- fixed / fluid

### できるようになること
狭い画面で「何を削るか」ではなく「何を守るか」を決められる。

---

## 09 UIレビュー

### 学ぶこと
- 観察と解釈を分ける
- 差分を取る
- 症状と原因を分ける
- 局所最適を疑う
- 変更前の意図を推定する
- 修正の副作用を見る

### できるようになること
「なんか違う」を再現可能なレビューコメントへ変換できる。

---

## 10 AIへのデザイン指示

### 学ぶこと
- reference fidelity
- invariants
- constraints
- forbidden changes
- acceptance criteria
- screenshot comparison
- pixel / geometry based verification

### できるようになること
AIに「改善」させるのではなく、守るべき設計意図を明示して実装させられる。

---

## 11 静的UI契約・インタラクション・演出レイヤー

### 学ぶこと
- 紙プロトタイプを視覚仕様書として使う
- visual bounds / hit bounds
- 契約実装
- 静止画だけでは足りなくなる境界
- state / transition / progress
- component state / SceneState
- keyframe / invariant
- 離散状態と連続状態
- 演出レイヤー
- リッチさとインタラクション複雑性の分離

### できるようになること
静的UIを可能な範囲まで契約化し、動的UIだけを状態設計へ切り替えられる。

また、複数コンポーネントの連動が増えたときに、個別状態のまま扱うかSceneStateへ昇格させるかを判断できる。

背景動画・装飾キャラクター・パーティクル等を、機能やレイアウトから独立した演出として分離できる。

詳細: [../chapters/11-static-contract-interaction-effects.md](../chapters/11-static-contract-interaction-effects.md)

---

# 想定学習レベル

## Level 1: 用語が分かる
用語を見て意味を説明できる。

## Level 2: UIから見つけられる
実際の画面を見て該当する原則を指摘できる。

## Level 3: 原因を説明できる
見た目の問題と原因を結び付けられる。

## Level 4: 修正方針を出せる
局所的な対症療法ではなく、意図を保った修正を提案できる。

## Level 5: AIに指示できる
守るもの・変えてよいもの・検証方法をプロンプトへ落とせる。

Design FEの合格イメージは **Level 4〜5** です。
