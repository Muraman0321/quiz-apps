# quiz-apps

`quiz-app-builder` スキルが生成した問題演習アプリ（単一HTML）の自動デプロイ先。

- `apps/` 配下に各アプリのHTMLファイルが置かれる。
- `index.html` はデプロイのたびに `scripts/deploy_to_render.py` が自動生成する一覧ページ。
- Renderの静的サイトとしてこのリポジトリを配信している。手動編集は基本不要。
