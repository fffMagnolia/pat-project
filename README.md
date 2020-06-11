### 概要

M(MySQL)EAN stackで作成したTODOアプリです。


### フォルダ構成

<pre>
pat-project --- express --- pat <- バックグラウンドを担当
             |
             |
             -- angular --- pat --- src --- proxy.conf.json <- プロキシの設定。/アクセス時にExpressにもリクエストが飛ぶようにしてある
             |                           |
             |                           |
             |                           -- app --- services --- api ... <- プロキシ経由後のリクエストとかを設定
             |
             |
             |
             -- readme.md
</pre>
