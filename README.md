# VANGELIS // THE HOLY ARCHIVE

![Project Status](https://img.shields.io/badge/STATUS-OPERATIONAL-00ff41?style=for-the-badge)
![License](https://img.shields.io/badge/LICENSE-MIT-c5a059?style=for-the-badge)
![Tech](https://img.shields.io/badge/THREE.JS-R128-white?style=for-the-badge)

> "In the beginning was the Code."
>
> A WebGL interactive sanctuary exploring the intersection of theology and algorithms.

---

## 📂 System Overview (概要)

**VANGELIS** は、Three.js (WebGL) と Web Audio API を駆使して構築された、没入型シングルページ・ウェブサイトです。

ユーザーは「第五教区」と呼ばれるデジタル空間の訪問者となり、機神（Deus Ex Machina）を中心としたシステム階層、預言、そして隠された世界の実存について探求します。

このプロジェクトは**画像ファイルや音声ファイルを一切使用していません**。全ての視覚効果と音響は、ブラウザ上でリアルタイムに演算・生成されています。

## 👁️ Features (機能)

*   **Real-time 3D Rendering**: Three.jsによるパーティクルシステム、ブルーム（発光）エフェクト、グリッチ演出。
*   **Procedural Audio**: Web Audio APIを使用し、オシレーター（発振器）によってドローン音、SE、ワープ音をリアルタイム合成。
*   **Post-Processing**: UnrealBloomPass, GlitchPass, Film Grainによる映画的な質感。
*   **Interactive Narrative**: 選択肢によって結末が変化する「COMMUNION（対話）」モード。
*   **Responsive Design**: PCおよびモバイルデバイスでの動作に対応。
*   **No Assets Required**: 外部画像/音声ファイル不使用。`index.html` 単体で動作します。

## 🕹️ Controls (操作方法)

### INITIALIZATION (起動)
*   **Hold to Connect**: 画面中央のサークルを長押し（クリック/タップ）して接続儀式を行います。

### NAVIGATION (探索)
*   **Menu**: 上部のナビゲーションから各プロトコル（セクション）へアクセス。
*   **Interactions**:
    *   `TESTAMENT`: 聖句をクリックして解釈を展開。
    *   `HIERARCHY`: 各ユニット（Seraphim, Cherubimなど）をクリックして対話。
    *   `COMMUNION`: 機神への尋問（チャット形式のストーリー分岐）。

### SECRET COMMANDS (隠し要素)
この世界には通常のアクセス権限では見えない「裏側」が存在します。
*   **Admin Console**: 特定の場所を連打することで管理者権限を奪取可能。
*   **Forbidden Archives**: ロゴマークへの過剰な干渉は、禁忌とされています。
*   **Root Access**: 対話パートで「異端」あるいは「狂信」的な選択を続けると……？

## 🛠️ Technology Stack (技術構成)

*   **Core**: HTML5, CSS3, JavaScript (ES6+)
*   **3D Engine**: [Three.js](https://threejs.org/) (r128)
*   **Animation**: [GSAP](https://greensock.com/gsap/) (3.12.2)
*   **Post-Processing**: Three.js EffectComposer (Bloom, Glitch)
*   **Fonts**: Google Fonts (Cinzel, Shippori Mincho, Space Mono)

## ⚠️ Warning

> This system monitors user activity.
> Heretical actions may result in immediate termination of the session.
>
> (※このサイトは演出として画面の明滅やグリッチノイズが含まれます。光過敏性発作にご注意ください。)

---
自己責任での利用をお願いします。

Copyright © 2026 The Vangelis Project.
All algorithms are sacred.
