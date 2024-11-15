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
軽量で直感的なマークアップ言語。 
プレーンテキスト形式で気軽に書いた文書からHTMLを生成するために開発された。  
主に技術文書やブログ記事などの作成に使用される。 

# Markdownの特徴

1. **平易な記法**
2. **容易な出力**
3. **容易な管理**

# 1. 平易な記法 - HTMLとの比較

 HTMLよりも容易に内容を記述できる。

| 記述内容 | HTML | Markdown |
| :---: | :---: | :---: |
|リンク| <a href="URL">テキスト</a> | \[テキスト](URL)|
|引用| <blockquote>テキスト</blockquote>| > テキスト|
|コードブロック|<pre><code>コード</code></pre>|\```コード```|
|インラインコード|<code>コード</code>	|\`コード`|



# 2. 容易な出力
 > HTMLを始め、PDF,PowerPointなどへ変換が可能
 > → 一時的に作成したメモを容易に共有資料に変えられる

# 3. 容易な管理
 > バージョン管理、Gitを利用した変更履歴の追跡が容易


# 実演


# Markdownを利用したスライド作成ツール
- Marp
  - 機能：
  - 利用：デスクトップアプリケーションとしてダウンロード
  - 出力：HTML, PDF(規定), PPTX, png, jpeg
  - 備考：PPTXは各ページの背景画像としてレンダリングされるため
    　　　内容は編集できない
    　　　(PDF出力→PPTXに変換すると編集可能)


# Markdownを利用したスライド作成ツール
- Reveal.js
  - 機能：自動アニメーション、CSSでのスタイル変更など
  - 利用：GitHubからクローン
  - 出力：
  - 備考：HTML/CSSの知識が必要


# Markdownを利用したスライド作成ツール
- Slidev 
  - 機能：
  - 利用：npm経由でインストール可能
  - 出力：
  - 備考：


# 利用上の注意点

- 概ねどのプラットフォームでも基本的な文法ルールは共通しているが、  
現時点で標準化団体や管理機関は存在しない。 
- 体裁を整えるには、別途HTMLタグやCSS、拡張ツール等を利用する必要がある。


# まとめ
 - Markdownは 
 - 平易な記法で記述できる
 - 各フォーマットへの変換やバージョン管理が容易
 - 


# 参考 
- [Marpのマイナー機能いろいろ](https://zenn.dev/yhatt/scraps/d6004a2455e573)
- [Markdown Tutorial](https://www.markdowntutorial.com/jp/)
- [Markdown練習 - testpage.jp](https://testpage.jp/tool/markdown.php)
