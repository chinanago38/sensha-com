# 作業の引き継ぎ（2026-11-26 05:30 時点）

## 戦車.com（sensha-com）
- 公開済み：29ページ（トップ＝次の駐屯地祭3件、駐屯地祭カレンダー、総火演、りっくんランド、陸自4車両、旧日本軍3両、世界5両、戦車戦4、規約5）
- 写真：全コンテンツページに12枚ずつ（サイト全体で重複なし）。tools/fetch_gallery.py が Actions で取得
- 毎日0:07(JST)に Daily rebuild（トップの「次の駐屯地祭」が自動で繰り上がる）

## 駐屯地ガイド：17か所＋一覧を公開済み（2026-11-26 11:20）。カレンダー修正（島松・東千歳）も済み
## （以下は経緯メモ）駐屯地ガイド（/chutonchi/<slug>/）29か所
- 05:50時点で17か所の下書きが完成（tools/drafts/ に退避済み・未公開）：higashichitose iwamizawa bibai makomanai takikawa shimamatsu okadama jinmachi fukushima kasuminome kengun zentsuji toyokawa moriyama kanazawa hisai sabae
- 見送り12か所（公式資料不足）：kitaeniwa minamieniwa abira kutchan shizunai horobetsu shiraoi naebo hakodate toyama fukuoka himeji（倶知安は公式ページが読めなかっただけなので再挑戦の価値あり）
- カレンダー要修正：島松は6/6一般公開・6/7招待者のみ／東千歳は10式・90式と約300両の観閲行進（さきがけ395）
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
