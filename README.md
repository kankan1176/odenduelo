# おでん道 鍋の陣 - ODEN DUELLO

おでんの具材を5×5の盤面に並べ、連結パワーで中立ボスや相手の具材に挑むブラウザ対戦ゲームです。ビルド不要で、`index.html` 1ファイルで動作します。

## 遊び方
- 修行【CPU対戦】で難易度（松・竹・梅）を選んで対局します。
- デッキ編成で10枚（合計コスト27以内）を選べます。
- 名前・レート・戦績・デッキ・音量はブラウザの `localStorage` に保存されます。

## GitHub Pages で公開する
1. このフォルダの中身（`index.html` など）をリポジトリの直下に置いて push します。
2. リポジトリの **Settings → Pages** を開きます。
3. **Build and deployment** の Source を **Deploy from a branch** にし、Branch を `main`、フォルダを `/ (root)` にして **Save** します。
4. 数分後に `https://<ユーザー名>.github.io/<リポジトリ名>/` で公開されます。

## 外部依存（CDN）
- Tailwind CSS（`cdn.tailwindcss.com`）
- Tone.js 14.8.49（cdnjs）
- Google Fonts（Shippori Mincho / Inter）

## 既知の制限
- オンライン対戦は未実装です（ボタンは「準備中」表示）。
- 音はブラウザの仕様上、最初のタップ後に鳴り始めます。
