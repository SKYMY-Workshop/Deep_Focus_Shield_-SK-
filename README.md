# 🛡️ Deep Focus Shield

SNS依存防止のために、短時間で消費される中毒性コンテンツを自動的にブロックし、深い集中力を保つことをサポートします

## 機能

### 共通機能（すべてのサイトに適用）
- ✅ グレースケールモード（色彩による脳への報酬刺激をカット）
- ✅ 曜日・時間帯による制限（複数時間帯設定可能）
- ✅ 常時ON機能
- ✅ ダークモード対応

### YouTube
- ✅ Shortsの非表示
- ✅ ホーム画面を登録チャンネルへリダイレクト
- ✅ 関連動画の非表示（動画再生ページ右側）
- ✅ コメントを非表示

### Twitter/X
- ✅ デフォルトのTLを「フォロー中」に変更
- ✅ おすすめ（For you）タブの非表示
- ✅ トレンドの非表示（デフォルトON）
- ✅ 動画の自動再生停止

### TikTok
- ✅ サイト全体をブロック（デフォルトON）


## 📸 プレビュー / Preview

<p align="center">
  <img src="https://github.com/SKYMY-Workshop/Deep_Focus_Shield_-SK-/blob/main/popup-preview_v1.0.0.png?raw=true" width="480" alt="Deep Focus Shield UI Preview">
</p>


## 🔽 Install / ダウンロード

👉 最新版はこちら：
https://github.com/SKYMY-Workshop/Deep_Focus_Shield_-SK-/releases

## インストール方法

1. このリポジトリをダウンロード（上記ダウンロードページ内のAssets -> Deep_Focus_Shield_*.*.*.zipをダウンロード）して解凍
2. Chromeブラウザのアドレスバーに `chrome://extensions/` と入力
3. 右上の「デベロッパーモード」をONにする
4. 左上の「パッケージ化されていない拡張機能を読み込む」をクリックし、解凍したフォルダを選択（この時に指定したフォルダから移動すると動作しなくなるので、マイドキュメントやProgramFilesなどの任意のフォルダに保存した上で指定してください。）
5. Cheromeのアドレスバーの少し右にあるパズルのピースをクリックしDeep_Focus_Shieldの右の推しピンのマークをクリック
6. アドレスバーの右にDeep_Focus_Shieldが表示されるようになるので、必要に応じて必要な機能を操作する。

## アンインストール方法

1. Cheromeのアドレスバーの少し右にあるパズルのピースをクリックし、一番下の拡張機能を管理を押す。
2. 拡張機能一覧から🛡️ Deep Focus Shield を見つけ、削除ボタンを押す。
3. インストールの手順4の時に任意の場所に保存したフォルダを削除する。 

## 🛠️ Support / サポート

不具合報告・機能提案はこちら：
https://github.com/SKYMY-Workshop/Deep_Focus_Shield_-SK-/issues

## ファイル構成

```
deep-focus-shield/
├── manifest.json
├── popup.html
├── popup.css
├── popup.js
├── background.js
├── youtube-content.js
├── youtube-style.css
├── twitter-content.js
├── twitter-style.css
├── icon16.png
├── icon48.png
└── icon128.png
```

## デフォルト設定について

最大限の効果を得るため、以下の機能がデフォルトでONになっています：
- 共通機能: 常にON（全機能を常時有効化）
- YouTube: Shorts非表示、ホームリダイレクト、関連動画非表示、コメント非表示
- Twitter: トレンド非表示
- TikTok: サイトブロック

## 更新履歴
- v1.0.0-beta 初回プレリリース

## 📜 License

MIT License. 詳細は [LICENSE](./LICENSE) を参照してください。

本拡張は完全オープンソースです。
コードはすべて公開され、いつでも検証可能です

---



