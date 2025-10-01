# Quick Portfolio
簡易的な1ページのポートフォリオサイトと、オフライン動作のQRコード生成ツールです。

## 構成
- `index.html` … 簡易版ポートフォリオ（プロフィール／作品サンプル／連絡先）
- `styles.css` … 体裁
- `assets/avatar-placeholder.svg` … プレースホルダー画像
- `qr-maker.html` … 公開URLからPNGのQRを生成（オフライン可）

## 公開（例：GitHub Pages）
1. GitHubで新規リポジトリを作成（例：`pino-portfolio`）
2. このフォルダ内の4ファイルをアップロード
3. Settings → Pages → Branch を `main / root` にして保存
4. 数分後に `https://<ユーザー名>.github.io/pino-portfolio/` が公開URLになります

## 名刺用QRの作り方
1. 公開URLをコピー
2. `qr-maker.html` をブラウザで開く（ローカルでOK）
3. URLを入力して「生成」→「PNGを保存」
4. デザイン入稿データに貼り付け

## 差し替えポイント
- `index.html` 内の氏名／肩書／紹介文／リンク
- 作品サムネイル（`.thumb` を画像に置換）
