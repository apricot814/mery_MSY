# Mery構文ファイル CSS3.msy

## 概要
誰か作るだろうと思ったら意外となかったので。もともと内蔵されてるCSSをリッチにする感じで作りました。
うまく動いてくれるといいのですが....  
色を使いすぎた感じがしないでもないので、うまく色分けされないかもしれない。

## マークアップ内容
* @規則
* CSS3プロパティ
* 擬似クラス疑似要素
* CSS3プロパティ
* CSS3プロパティに対する値/関数
* カラーネーム
* HTMLタグ、id、クラス、属性セレクタ
* ベンダープレフィックス/一部の廃止要素・非推奨な表記

## Mery構文ファイルのメモ
* msyファイルでコメントアウトするには`#?サムシング`と書けばいいらしい
* [こちら](http://denspe.blog84.fc2.com/blog-entry-226.html "Mery（テキストエディタ）色分け表示用正規表現の優先順位")によると、優先順位は正規表現の文字列が長い方だそうなので、所々を`\s*`で嵩増ししている。

## CSS3について
* `E:before`でなく、`E::before`と書いたほうが良い。
* `ime-mode`は廃止されたよ


## ライセンス的な
* HTML5タグはucky氏のHTML5構文ファイルを流用したが、spanがのけものになってたので勝手に追加。
* ダブルクォーテーション部分の色分けの正規表現は[こちら](http://www.haijin-boys.com/index.php?fuseaction=discussions.replies&discussion_id=2942 "正規表現で文字列データを検索したい場合。")
* ところどころ抜けてるプロパティがあるかもしれない。


## 著作
[BlackApple](https://github.com/JapaneseBlackApple)

