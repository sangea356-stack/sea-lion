
# NewPage

このリポジトリは静的な日本語ランディングページ `NewPage` のサンプルです。

## 内容
- `index.html` — メインの HTML ファイル（日本語）
- `style.css` — スタイルシート
- `README.md` — このガイド

## GitHub Pages に公開する手順（ウェブ UI）
1. GitHub にログインします（あなたのユーザー名: `sangea356-stack`）。
2. 新しいリポジトリを作成します。名前を `NewPage` にしてください（公開リポジトリ）。
3. 作成後、画面の `Add file` → `Upload files` で、`index.html` と `style.css`、`README.md` をアップロードしてコミットします。
4. リポジトリの設定（Settings）を開き、左メニューから **Pages** を選びます。
5. **Source** を `main` ブランチ（または `master`）にして、フォルダは `/ (root)` を選択して **Save** をクリックします。
6. 数分待つと、公開 URL が表示されます（通常は `https://sangea356-stack.github.io/NewPage/`）。

## 代わりに Git コマンドでアップロードする方法
ローカルでリポジトリを作成して push する場合の例：
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin https://github.com/sangea356-stack/NewPage.git
git push -u origin main
```

公開 URL: `https://sangea356-stack.github.io/NewPage/`

問題があれば私が手順を詳しく案内します！
