# HTML5/CSS3モダンコーディング 吉田真麻著 翔泳社

3つのサイトを作りながらモダンコーディングを学ぶ本。

HTML/CSSを学び直すために進めることにした

## Part1 スタンダードレイアウト

- position:absoluteの起点は親要素、変えるためにposition:relativeを使う
- floatさせたらclearfix
  - clearfixというクラスと作ると便利 clear:both
- box-sizing: border-boxにしないとpaddingやborderの分だけboxのサイズが拡大されてしまう
  - `*, *:before, *:after` の全てにborder-boxつけると良い
- nth-ob-type(1)
- nth-of-type(odd) nth-of-type(even)  
