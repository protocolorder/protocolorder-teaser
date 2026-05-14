# Protocol Order Teaser Site

GDDと添付バナー／アイコンの世界観に合わせて作成した静的ティザーサイトです。

## 構成

- `index.html` — ティザーサイト本体
- `whitepaper.html` — Hashranホワイトペーパー（ゲーム内架空仕様書）
- `styles.css` — レイアウト、レスポンシブ、ネオンSF表現、ホワイトペーパー用スタイル
- `script.js` — ヘッダー制御、スクロール演出、星空Canvas
- `assets/protocol-order-banner.jpeg` — 添付バナー
- `assets/protocol-order-icon.jpeg` — 添付アイコン
- `assets/favicon.ico` — favicon
- `assets/apple-touch-icon.png` — Apple Touch Icon
- `assets/favicon-512.png` — 大判アイコン

## 反映内容

- YouTube動画リンクは削除し、ボタンを「Gameplay準備中」のdisabled状態に変更
- 公式Xリンク `http://x.com/ProtocolOrder` を掲載
- faviconを追加
- Hashranホワイトペーパーの個別ページを追加
- ホワイトペーパー内に、HashranおよびHASRNTKが架空設定であり実在プロジェクトと無関係である旨の注意書きを追加

## 公開方法

このフォルダの中身をそのまま GitHub Pages / Netlify / Vercel / 任意の静的ホスティングへアップロードできます。
外部ライブラリは使用していません。

## 変更推奨箇所

- Steamページ公開後のCTA追加
- Release Plan の日付・表現
- Contact メールアドレス


## v3変更点
- Hashran Whitepaperページの目次をsticky化。
- PCでは左サイドバー追随、スマホ/タブレットでは上部横スクロール型の追随目次に変更。
- 目次が画面高を超える場合は目次内部のみスクロール可能。

## v5変更点

- index.html のRelease Planに、初期リリース対応言語（日本語・英語）、初期リリース配信予定国（日本・アメリカ）、対応OS（Windows / macOS）を追加。
- styles.css?v=5 に更新。

## v4変更点
- `main { overflow: hidden; }` がsticky挙動を阻害し得るため、Whitepaperページでは `main` / `content-section` / `whitepaper-layout` を `overflow: visible` に上書き。
- Whitepaperページの目次をPCでは左サイドバーsticky、980px以下では上部stickyの横スクロール目次として再調整。
- `styles.css?v=4` をHTML側に指定し、既存CSSキャッシュの影響を回避。
- index.html の Release Plan から創風提出用Vertical Slice項目を削除。

## v6 changes

- Release Plan下段の「2027 Feb / Soft Launch」「2027 May / v1.0 Release」を中央寄せに変更。
- 下段2カードの幅を上段3カード（Languages / Regions / Operating Systems）と同一幅に調整。
- CSSキャッシュ対策として `styles.css?v=6` に更新。


## v7変更点

- index.html に「Related Research」セクションを追加。
- noteで執筆中のビットコイン論考マガジンへの外部リンクを追加。
- 当該noteはProtocol Order本編ではなく、ブロックチェーンを投資文脈以外で解釈するための関連プロジェクトとして位置付ける旨を明記。
- 投資助言・価格予想を目的としない旨を明記。
- フッターにも関連noteマガジンへのリンクを追加。
- CSSキャッシュ対策として styles.css?v=7 に更新。
