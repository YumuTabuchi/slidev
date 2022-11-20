---
# try also 'default' to start simple
theme: seriph
# random image from a curated Unsplash collection by Anthony
# like them? see https://unsplash.com/collections/94734566/slidev
background: https://source.unsplash.com/collection/94734566/1920x1080
# apply any windi css classes to the current slide
class: 'text-center'
# https://sli.dev/custom/highlighters.html
highlighter: shiki
# show line numbers in code blocks
lineNumbers: false
# some information about the slides, markdown enabled
info: |
  ## Slidev Starter Template
  Presentation slides for developers.

  Learn more at [Sli.dev](https://sli.dev)
# persist drawings in exports and build
drawings:
  persist: false
# use UnoCSS (experimental)
css: unocss
---

# アイデア具現化プチ共有会（仮）

<div class="pt-12">
  <span @click="$slidev.nav.next" class="px-2 py-1 rounded cursor-pointer" hover="bg-white bg-opacity-10">
    Press Space for next page <carbon:arrow-right class="inline"/>
  </span>
</div>


<!--
アイデア具現化プチ共有会（仮）
-->

---


# 自己紹介
##


（後で記載）


<!-- 

 -->

---


# イントロ
##


プログラミングできるようになったし、何か作ってみたい

そう思ったことはありませんか？

<div class="w-100 mx-auto"> 
<img class="inline w-70" src="/img/computer_tokui_boy.png">
</div>
<!-- 

 -->

---

# イントロ
##

でも実際にやってみると、躓きポイントがたくさんある。。


例えば

* そもそも作るもののアイデアが思いつかない
* 環境構築でエラーが発生して、解決できなかった
* 完成する前に飽きてしまった

などなど

<div class="w-100 mx-auto"> 
<img class="inline w-40" src="/img/question_head_gakuzen_boy.png">
</div>
<!-- 

 -->

---

# イントロ
##

本会は何か作りたい/作ってみた人を対象にした、ナレッジ・ティップス共有会です。
* カジュアル目ではあるが、仕事とも共通する要素はあるはず
* 一方的な発表ではなく、参加者からの質問や情報共有もたくさんしてほしい
<div class="w-100 mx-auto"> 
<img class="inline w-70" src="/img/kaigi_man_woman.png">
</div>
<!-- 

 -->

---

# アジェンダ

1. 自分が作ったもの紹介
2. ナレッジ・チップスの共有
   1. アイデア
   2. 設計
   3. 実装
   4. モチベーション
<!-- 

 -->

---

# 1. 自分が作ったもの紹介

何？

ロケットリーグというゲームの分析ツール（Webアプリ&ゲームのMod）

<div class="w-100 mx-auto"> 
<img class="inline w-100" src="/img/RocketLeague.jpg">
</div>

ジャンプやロケット飛行ができる車を操作してサッカーするゲーム。
<!-- 

 -->

---

# 1. 自分が作ったもの紹介

何ができる？

* 地域別にプロプレイヤーの分析ができる

* 見たいシーンを検索して、そのシーンだけ自動再生できる
<!-- 

 -->

---

# 1. 自分が作ったもの紹介


<iframe src="http://localhost:3000" height="400" width="900"></iframe>

<!-- 

 -->

---

# 1. 自分が作ったもの紹介


<video src="/img/RLLab.mp4" width="600" controls></video>

<!-- 

 -->

---

# 1. 自分が作ったもの紹介
言語

* 事前の解析: Python
* Webアプリ: React (JavaScript)
* ゲームのMod: C++
<!-- 

 -->

---

# 1. 自分が作ったもの紹介
仕組み

（構成図）
<!-- 

 -->

---

# 2. ナレッジ、チップスの共有
流れ

各躓きポイントについて、以下の流れで進める

1. 具体例
2. 参加者からの質問・共有
3. まとめ
<!-- 

 -->

---

# 2.1 アイデア
具体例: 特定のグループ内で役に立つものを考える

自分の趣味であるゲームで何か作れないか考えた

最近Valorantなどのゲームでデータアナリストがいるという話を耳にしていたので、ロケットリーグでも同じようなことができないか考えた。

（詳細記載）

<!-- 

 -->

---

# 2.1 アイデア
具体例: 現状やニーズを調査する

プロプレイヤーやコーチにtwitterで直接相談し、需要がありそうだと分かった。

（詳細記載）

<!-- 

 -->

---

# 2.1 アイデア
具体例: 他の分野を参考に

valorantのデータアナリストの配信を聞いたり、スポーツアナリティクスコミュニティのLTを聞いたり

（詳細記載）
<!-- 

 -->

---

# 2.1 アイデア
その他

以下も大事
* twitterでバズりそうなもの考える
* 気分転換したりノートに考えを書き出す


（詳細記載）
<!-- 

 -->

---

# 2.1 アイデア
参加者からの質問・共有

<!-- 

 -->

---

# 2.1 アイデア
まとめ

* 課題・ニーズを見つける・聞く
* 既存のサービスをもとに発想する（オズボーンの発想法）
* 日ごろから新しいサービスに触れる
* 気分転換やアウトプット・相談などによって、新たな気づきを得る


<!-- 

 -->

---

# 2.2 設計
具体例: 大枠の方針設計

既存のツールについて、仕組みを調べた

（詳細記載）

<!-- 

 -->

---

# 2.2 設計
具体例: 利用するサービスの選定

利用するホスティングサービスやDBについて検討した

（詳細記載）

<!-- 

 -->

---

# 2.2 設計
参加者からの質問・共有

<!-- 

 -->

---

# 2.2 設計
まとめ
* 既存のサービスの仕組みを参考にする
* 各実現案について、メリットデメリットを列挙し自分の要件と照らし合わせて、選択する
（詳細記載）

<!-- 

 -->

---

# 2.3 実装
具体例: デバッガを使う

意図通りの実装にならないときに、VSCodeのデバッガを使いながらトライアンドエラーで実装

（詳細記載）

<!-- 

 -->

---

# 2.3 実装
具体例: 人に聞く

Discordサーバで質問した。

（詳細記載）

<!-- 

 -->

---

# 2.3 実装
その他

* googleで検索
* 問題の切り分け
* 英語ができる

（詳細記載）

<!-- 

 -->

---

# 2.3 実装
参加者からの質問・共有

<!-- 

 -->

---

# 2.3 実装
まとめ

（詳細記載）

<!-- 

 -->

---

# 2.4 モチベーション
具体例: 過程の共有

twitterなどで作っている過程を共有する

（詳細記載）

<!-- 

 -->

---

# 2.4 モチベーション
具体例: シンプルに

機能を詰め込みすぎず、できるだけシンプルにする

（詳細記載）

<!-- 

 -->

---

# 2.4 モチベーション
具体例: アナリティクス

アクセス分析などをして使ってもらえていることを実感する

（詳細記載）

<!-- 

 -->

---

# 2.4 モチベーション
参加者からの質問・共有

<!-- 

 -->

---

# 2.4 モチベーション
まとめ

（詳細記載）

<!-- 

 -->

---
