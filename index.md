---
layout: default
title: Note
description: Note
lang: ja_JP
author: hirahara2021
date: 2021-11-26T17:00+09:00
last_modified_at: 2021-11-26T17:00+09:00
---
<!-- Global site tag (gtag.js) - Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-TD28YG2FQ0"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-TD28YG2FQ0');
</script>

思うがままに何かを書き留めていきます。(最終更新日:{{ page.last_modified_at | date: "%Y年%m月%d日" }})

## 初期設定

|No|内容|
|--|--|
|1|Twitterのアカウントを作成する。|
|2|GitHubのアカウントを作成する。|
|3|SSH Key(OpenSSH)を作成し登録する。|
|4|GitHub上でnote(public)リポジトリを作成する。|
|5|PC上で「作成したnoteリポジトリ」をクローンする。|
|6|gh-pagesブランチを作成し、index.mdを追加してサーバーにPushする。|
|7|GitHub上でGitHub Pagesを開き、gh-paseブランチを設定する。|
|8|Webサイト(`https://hirahara2021.github.io/note/`)が表示されることを確認する。|
|9|PC上でindex.mdの内容を変更してサーバーにPushし、Webサイトに変更が反映されることを確認する。|
|10|Google Analyticsへ登録する(アクセス解析用)|
|11|_config.ymlを修正する(Google Analytics設定等)|
|12|Google Search Consoleへ登録する(SEO対策)|
|13|一旦綺麗にするため、gh-pagesブランチを作り直し、変更分を１コミットにまとめる。|

## 事前準備

|No|内容|
|--|--|
|1|Visual Studio Codeをインストールしておく。|
|2|Visual Studio Code/拡張機能の「Markdown Preview Enhanced」をインストールしておく。|
|*|mdファイルを編集するために使用する。|

## 連絡先

何かあればTwitterの方に連絡ください。

[Twitter](https://twitter.com/hirahara2021)
