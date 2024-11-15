---
marp: true
theme: default
paginate: true
---
<!--
headingDivider: 1
-->

# Markdown
##### 2024/12/10 第1システム部 中山優希

# Markdownとは
軽量で直感的なマークアップ言語*。 
プレーンテキスト形式で気軽に書いた文書からHTMLを生成するために開発された。  
主に技術文書やブログ記事などの作成に使用される。 

*文書の構造やフォーマットを指定するための言語。HTMLやXMLが該当する。


# Markdownの特徴

1. **分かりやすい記法**
2. **複数のエクスポート形式**
3. **資料管理**

# 1. 分かりやすい記法 - HTMLとの比較

 HTMLよりも容易に内容を記述できる。

| 記述内容 | HTML | Markdown |
| :---: | :---: | :---: |
|リンク| <a href="URL">テキスト</a> | \[テキスト](URL)|
|引用| <blockquote>テキスト</blockquote>| > テキスト|
|コードブロック|<pre><code>コード</code></pre>|\```コード```|
|インラインコード|<code>コード</code>	|\`コード`|


# 2. 複数のエクスポート形式
 > HTMLを始め、PDF,PowerPointなどへ変換が可能
 > → 一時的に作成したメモを容易に共有資料に変えられる

# 3. 資料管理
 > バージョン管理、Gitを利用した変更履歴の追跡が容易


# 実演


# 業務におけるMarkdownの利用

 - 文書作成：
 - 
 - 

# Markdownを利用したスライド作成ツール
> ### 1. Marp
>  - 基盤：Markdown
>  - 特徴：リアルタイムプレビュー
>  - 利用：VS Code 拡張機能、NPMパッケージ、デスクトップアプリ
>  - エクスポート：HTML, PDF, PPTX, PNG, JPEG
>  - 備考：アニメーション機能は限定的。カスタマイズに制限あり。
    　　　 PPTXは各ページの背景画像としてレンダリングされるため
    　　　 内容は編集できない。
    　　　 (PDF出力→PPTXに変換すると編集可能)


# Markdownを利用したスライド作成ツール
> ### 2. Reveal.js
>  - 基盤：HTML/CSS
>  - 特徴：自動アニメーション
>  - 利用：NPMパッケージ、CDNから読込み、GitHubからダウンロード
>  - エクスポート：HTML, PDF, JavaScript API
>  - 備考：HTML/CSSの知識が必要


# Markdownを利用したスライド作成ツール
> ### 3. Slidev 
>  - 基盤：Vue.js
>  - 特徴：ホットリロード、コードハイライト
>  - 利用：NPMを使用してプロジェクト作成後、開発サーバを起動
>  - エクスポート：HTML, PDF, PNG
>  - 備考：比較的新しいツール。Vue.js の知識があると良い



# 利用上の注意点

- 概ねどのプラットフォームでも基本的な文法ルールは共通しているが、  
  現時点で公式の標準化団体は存在しない。 
- 体裁を整えるには、別途HTMLタグやCSS、拡張ツール等を利用する必要がある。

# 所感
　使ってみて
　- 一般的な記号を用いて記述するので導入しやすいが、資料としては簡素な
    ものになってしまうため、
  - 


# まとめ
 - Markdownは 
 - 平易な記法で記述できる
 - 各フォーマットへの変換やバージョン管理が容易
 - 


# 参考 
- [Marpのマイナー機能いろいろ](https://zenn.dev/yhatt/scraps/d6004a2455e573)
- [Markdown Tutorial](https://www.markdowntutorial.com/jp/)
- [Markdown練習 - testpage.jp](https://testpage.jp/tool/markdown.php)
