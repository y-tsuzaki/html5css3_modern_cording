# HTML5/CSS3モダンコーディング 吉田真麻著 翔泳社

3つのサイトを作りながらモダンコーディングを学ぶ本。

HTML/CSSを学び直すために進めることにした

## 作ったもの置き場

https://y-tsuzaki.github.io/html5css3_modern_cording/index.html

## Part1 スタンダードレイアウト

- position:absoluteの起点は親要素、変えるためにposition:relativeを使う
- floatさせたらclearfix
  - clearfixというクラスと作ると便利 clear:both
- box-sizing: border-boxにしないとpaddingやborderの分だけboxのサイズが拡大されてしまう
  - `*, *:before, *:after` の全てにborder-boxつけると良い
- nth-ob-type(1)
- nth-of-type(odd) nth-of-type(even)  
-   counter-reset: ranking;
-  content: counter(ranking);
-  counter-increment: ranking;
- 画像の代替テキストをoverflow:hiddenで隠すテクニック
- h1 class="hidden"はいいのか？
- asideは使わないのか？
  - asideは副次的な要素。サイドバー専用のタグではないけど、サイドバーに使うのも間違ってなさそう
    - https://developer.mozilla.org/ja/docs/Web/HTML/Element/aside
