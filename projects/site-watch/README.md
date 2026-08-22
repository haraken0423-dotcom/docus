# projects/site-watch/

`protocols/site-watch.md` が、`config/watch-sites.md` に登録された各サイトの
直近チェック時点の内容（スナップショット）を保存する場所。

- ファイル名: サイトごとに `<スラッグ>.md`（URLから生成）
- 用途: 次回チェック時にこのファイルと現在のサイト内容を比較し、変化点を検出する
- 手動で編集する必要はない
