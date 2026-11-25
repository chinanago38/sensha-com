# 戦車.com（xn--iour70h.com）作業ルール

GitHub Pages で公開する静的サイト。tools/build.py が tools/content/*.html から全ページを生成する。

## ページの元ファイル
- tools/content/<dir>__<slug>.html → /<dir>/<slug>/（dir：miru 見られる場所・rikuji 陸自の戦車・kyugun 旧日本陸軍の戦車・sekai 世界の戦車・senshasen 戦車戦）。一覧ページは <dir>__index.html → /<dir>/。index.html → /
- 1行目：<title>（末尾「｜戦車.com」）、2行目：meta description（120字以内）、3行目以降：本文HTML
- 本文は `<h1>`、`<p class="updated">最終確認日：2026年11月26日</p>`、導入の `<p>`、そのあと素の `<h2>` 見出しと <p>/<ul>/<h3>/<table>/<dl> だけ（装飾は build.py が付ける）。最初の表は縦型（<th>項目</th><td>値</td>）
- 最後は `<section class="sources"><h2>出典</h2><ul>…</ul></section>`

## 守ること
- 事実は公的・公式の情報源で確かめたものだけ：防衛省・陸上自衛隊・防衛装備庁・防衛研究所、JACAR、国立公文書館、国立国会図書館、自治体、博物館の公式サイト、米国政府の公開資料（米陸軍・NARA など）。Wikipedia・個人ブログ・まとめサイトは使わない
- 確かめられない数字・日付は書かない。資料で違うときはそのことを書く
- 戦争の歴史は中立に。美化も過度な非難もしない
- 1ページ本文3,000文字以上。使い回し・数合わせのページは作らない
- 公式サイトと誤解されない書き方（個人運営・非公式）
