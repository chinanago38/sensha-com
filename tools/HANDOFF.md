# 作業の引き継ぎ（2026-11-26 05:30 時点）

## 戦車.com（sensha-com）
- 公開済み：29ページ（トップ＝次の駐屯地祭3件、駐屯地祭カレンダー、総火演、りっくんランド、陸自4車両、旧日本軍3両、世界5両、戦車戦4、規約5）
- 写真：全コンテンツページに12枚ずつ（サイト全体で重複なし）。tools/fetch_gallery.py が Actions で取得
- 毎日0:07(JST)に Daily rebuild（トップの「次の駐屯地祭」が自動で繰り上がる）

## 作成中：駐屯地ガイド（/chutonchi/<slug>/）29か所
- 書き手が tools/content/chutonchi__<slug>.html を作成中（作業環境のローカル。未pushの可能性あり）
- slug 一覧は tools/build.py の GARRISON。カレンダーの駐屯地名は、ページが完成すると自動でリンクされる
- 残り作業：
  1. tools/content/chutonchi__*.html を確認（本文3,000字以上・日付は公式どおり・姫路は「予定」扱い）
  2. tools/content/chutonchi__index.html（駐屯地ガイド一覧、3,000字以上）を作る
  3. 足りない駐屯地は書き足す
  4. python3 tools/build.py → push（IndexNowは自動）
  5. 12月上旬：2027年 降下訓練始め・冬〜春の記念行事の公式発表を確認してカレンダーへ追加

## 護衛艦.com（goeikan-com）：145ページで一区切り
## そのほか
- seikanmassage.jp 管理画面のスマホ表示（右側メインを全幅に）：コードの場所が不明。リポジトリ名かファイルが必要
- YouTube（ちんあなご）：切り抜き動画は非公開（削除しない）→ クリエイターサポートで再審査（期限 約12/16）
