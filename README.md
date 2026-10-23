# Cardio Visual Learning（循環器・ECG ビジュアル学習）

循環器の構造・血行動態・疾患と、12誘導ECG・不整脈を、アニメーション付きの図で学ぶ個人学習用ツールです。

`index.html` をブラウザで開くだけで使えます。

## ファイル

- `index.html`：循環器・ECG ビジュアル学習（本体）
- `als.html`：Prehospital ALS 学習ノート（AHA 2025 の公開資料をもとにした学習用まとめ。薬剤・気道・ROSC後・アルゴリズム・Systems of Care の5章）

## タブ構成

- **循環器の基礎**：血液循環、弁、心拍出量、刺激伝導系
- **循環器疾患**：心不全、冠動脈疾患・ACS、心筋症、弁膜症、血管疾患、心筋炎・心膜炎
- **ECG**：誘導と電極の位置、不整脈・伝導障害・STEMI
- **練習**：クイズ

## 内容

- 12誘導ECGの位置関係
- 四肢電極・胸部誘導の貼付位置
- augmented leads / Einthoven triangle
- AF, Atrial Flutter, SVT
- AV block（First-degree, Mobitz I / II, Complete AV Block）
- PVC, VT, VF
- RBBB, LBBB
- Inferior / Anterior-Septal / Lateral STEMI
- ECG波形クイズ
- 心臓の中の血液の流れアニメーション（循環器の基礎タブ）
  - 静脈血（青）と動脈血（ピンク）の流れ、4つの弁の開閉、拡張期・収縮期とI音・II音のタイミング
- 循環器疾患の図（循環器疾患タブ）
  - 心筋症：正常・拡張型・肥大型・拘束型を同じ心臓の図で並べ、左心室の動きを比較
  - 弁膜症：大動脈弁狭窄・逆流、僧帽弁狭窄・逆流を、拡張期・収縮期の血液の流れ（点線の矢印）と心臓の変化・心雑音で比較
- 心臓の電気の流れアニメーション（ECGタブ）
  - 血液の流れと同じ心臓の断面図の上で刺激伝導系（洞結節・房室結節・ヒス束・右脚/左脚・プルキンエ線維）を日英併記で表示
  - 正常洞調律と、上記の不整脈・伝導障害すべてについて、電気の流れと心電図（II / V1 / V6）を連動して再生
  - STEMIは前から見た心臓と冠動脈（RCA・LAD・LCx）の図に切り替わり、閉塞部位・梗塞部位と12誘導のST変化を表示
  - 各診断カードの「▶ 電気の流れを見る」から該当アニメーションへ移動

## 図の出典

心臓の断面図（血液の流れ・電気の流れ・冠動脈・心筋症・弁膜症の図）は、Wikimedia Commons の[「Heart diasystole.svg」](https://commons.wikimedia.org/wiki/File:Heart_diasystole.svg)（原画：Wapcaplet、Reytan／ベクター化：Sjef、[CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/) と GFDL 1.2 以降のデュアルライセンス）を改変して使用しています。

改変内容：配色の変更、元の矢印の削除、ラベル・刺激伝導系・冠動脈・病変表示・アニメーションの追加、部屋の形の変更（心筋症・弁膜症）。改変した図は、原図と同じ CC BY-SA 3.0 で提供します。

## 文章の出典

「循環器の基礎」「循環器疾患」タブの文章とクイズは、NHLBI・StatPearls・AHA/ACC・ESC の公開資料をもとに独自にまとめたものです（一覧は「循環器疾患」タブの最後）。ALS ノートは AHA 2025 CPR/ECC Guidelines の公開ページを参照しています。

## 注意

本ツールは個人学習用です。検索エンジンに載らないよう noindex を付けています。診断・治療などの医療判断を目的としたものではありません。
