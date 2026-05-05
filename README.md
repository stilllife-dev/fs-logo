# FS//LOGO Professional

**FS//LOGO Professional** は、フォントセレクターです。
ローカルフォントをブラウズし、グリフ（字形）の細部と併せて一覧するために設計されています。

### 🖼 Preview
<img width="2632" height="1542" alt="img" src="https://github.com/user-attachments/assets/8300cb3a-4778-4147-9814-7d3a4d4d2480" />

---

### 🚀 主な機能 / Features

* **Local Font Sync**: あなたのMac/PCにインストールされている全てのフォントをブラウザ上で高速同期します。
* **Typography Analysis**:
    * **Blur**: 文字をぼかし、細部を無視して書体を選定。重心や塊としての視認性を確認できます。
    * **Spacing**: 字間調整による字間の変化を表示。
    * **Guidelines**: x-heightとBaselineを可視化し、書体の重心を計測。
* **Pixel-Perfect Loupe**: `canvas` 描画による、精密なグリフの拡大鏡（ルーペ）機能。
* **Selected Items**: お気に入りの書体をキープし、ウェイト（ファミリー）ごとに管理。
* **One-Click Copy**: 制作ソフト（Illustrator等）への移行をスムーズにする、フォント名のクイックコピー。

---

## Demo
https://stilllife-dev.github.io/fs-logo/

---

### 💻 推奨環境 / Recommended Environment

* **Browser**: **Google Chrome** (最新版) または Chromium系ブラウザ
    * ※ `Local Font Access API` を使用しているため、SafariやFirefoxでは動作しません。
* **Hardware**: **Apple Silicon (M1以降)** 搭載のMacを推奨
    * フォントをリアルタイムにレンダリング・加工するため、高スペックなGPU環境で真価を発揮します。

---

### ⚠️ 使用上の注意 / Precautions

* **アクセス許可**: 起動時にブラウザから「ローカルフォントへのアクセス」を求められます。許可しないとフォントが表示されません。
* **プライバシー**: このアプリはサーバーにフォントやテキストデータを送信しません。すべてあなたのローカル環境内で完結します。
* **データ保存**: 「お気に入り（Selected Items）」の情報は、ブラウザの `LocalStorage` に保存されます。キャッシュをクリアするとデータもリセットされるためご注意ください。

---

### 📖 使い方 / How to Use

1.  `index.html` をブラウザで開きます。
2.  右上の **[SYNC FONTS]** をクリックして、あなたのフォントライブラリを同期します。
3.  上部の入力欄に、検証したい文字（ロゴの候補文字など）を入力します。
4.  `Size` / `Spacing` / `Blur` などのコントローラーで、書体の「声色」を確認します。
5.  気に入った書体は **★** を押してセレクト。サイドバーでウェイトを最終決定します。
6.  **[COPY]** ボタンでフォント名をコピーし、デザイン制作ソフトへ。

© 2026 stilllife / Produced by Sugawara "Finding your story with you."
