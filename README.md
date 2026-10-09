# カンジブラスター

漢字を書くほど強く・かっこよくなる、小学生向けのブロック風サバイバーシューター。
ブラウザだけで動きます（iPad 推奨）。

- 小学1〜3年の漢字 440字（学年別漢字配当表）
- 画面に書いた漢字を、書き順データと照合してその場で判定（サーバー・アカウント不要）
- 新しい字・復習・予習を自動で出題（間隔をあけた復習）
- 7つの世界、54種のモンスター＋ボス、ずかん、きがえ

## 遊び方
`index.html` を GitHub Pages などで公開し、iPad の Safari で開いて「共有 → ホーム画面に追加」するとアプリのように使えます。
記録はそれぞれのブラウザ内（localStorage）に保存されます。

## 出典・ライセンス
- 書き順データ: [KanjiVG](https://kanjivg.tagaini.net) © Ulrich Apel — [CC BY-SA 3.0](https://creativecommons.org/licenses/by-sa/3.0/)
  （`index.html` 内の `KSTROKE` は KanjiVG を点列に変換したものです。このデータ部分は CC BY-SA 3.0 に従います）
- 3D描画: [three.js](https://threejs.org) r128（MIT, cdnjs から読み込み）
- フォント: Google Fonts（Dela Gothic One, Zen Maru Gothic, Klee One / SIL OFL）
