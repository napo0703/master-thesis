# IoT時代の共有情報視覚化システムの研究

Research on an information visualization system for the IoT age

[論文PDF](https://napo0703.github.io/master-thesis/main.pdf)

## 概要

全世界のセンサ情報やユーザの気分などを一覧表示したり投稿したりできるシステム『わかるらんど』を提案する．ニュースや天気予報のようなリアルタイム情報を並べて一覧表示する「情報ダッシュボード」の利用が広まっているが，利用できる情報の種類は限られており，ユーザが情報を投稿して共有することはできない．『わかるらんど』は，単純で強力なWeb上の情報共有システム「WebLinda」上に構築された汎用的な情報共有/視覚化システムであり，ユーザの気分を表明したり，チャット文字列を投稿したり，センサ情報やWeb上の情報を表示したり，ネット上のあらゆる情報を投稿/共有して一覧表示することできる．『わかるらんど』の利用により，情報ダッシュボードとSNSやチャットシステムを簡単に統合的に利用することができる．本論文では，『わかるらんど』の思想及び利用経験について述べ，応用について考察する.

## Abstract

We propose a new information visualization system “WakaruLand” that can show various real-world information including sensing data, information on the Web, people’s activities and feelings, etc. Although information dashboard systems are getting popular these days, they can display limited sets of information provided by the services, and people cannot freely add data sources or post arbitrary information related to them. Using WakaruLand, people can easily create new data sources and post their activities and feelings using the WebLinda system running on a Web server, using a simple and powerful communication protocol based on Linda. We show how we can use WakaruLand for various applications including information dashboard, visualization of users’ status, etc.

## わかるらんど

https://github.com/napo0703/wakaruland

## PDFの生成

```
  % make
```

または

```
  % platex -kanji=utf8 main
  % pbibtex -kanji=utf8 main
  % platex -kanji=utf8 main
  % platex -kanji=utf8 main
  % dvipdfmx -p a4 main
  % open main.pdf
```