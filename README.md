# kuroneko-sns-trigger

くろねこ工房のSNS自動投稿（非公開リポジトリ）を、毎日決まった時刻に起こすためだけのリポジトリです。

- `.github/workflows/wake.yml` が日本時間 17:40・17:50（予備 18:25・19:25）に動き、毎日の投稿を起動します。
- `.github/workflows/weekly.yml` が毎週日曜 20:00 に動き、手動投稿キット（TikTok・LINE・Lemon8）を作らせます。
- 投稿の文面・店のデータ・各SNSのキーはここにはありません。
- 起動に使うトークン（`AUTOPOST_DISPATCH_TOKEN`）は、投稿側のリポジトリの「Actions の実行」だけができる権限です。
