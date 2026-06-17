# あとでやること（TODO）

## アクセス解析（訪問者数を自分だけ見られるようにする）
- ステータス: **保留中**（最終的には付けたい）
- 方法: GoatCounter（無料・プライバシー配慮・自分専用ダッシュボード）
- 再開のしかた:
  1. https://www.goatcounter.com/signup で登録（Code は `freetimes`）
  2. 管理ページ: https://freetimes.goatcounter.com
  3. `index.html` の末尾にある「【あとで付ける】アクセス解析」コメントの中の
     `<script ...goatcounter...>` 2行のコメントを外す
  4. もし Code を `freetimes` 以外にした場合は、その名前に合わせてタグの URL を直す
- 補足: 自分のアクセスを数えない設定（`?goatcounter-ignore` など）も合わせて案内する
