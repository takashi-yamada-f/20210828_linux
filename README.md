# Linuxディストリビューションについて

## 【１】Linuxの出現

* Linux用語事典 [UNIX]
<br>https://atmarkit.itmedia.co.jp/aig/03linux/unix.htmlbr
<br>まずは、Linuxの原型になったUnixについてから。

* 【入門】BSDとSystemVの違い
<br>https://www.mtioutput.com/entry/differ-bsd-systemv
<br>GNU/Linuxの位置を記した、図に注目。

* Linux用語事典 [GNU（GNU is Not UNIX）]
<br>https://atmarkit.itmedia.co.jp/aig/03linux/gnu.html
<br>こうして、OSSのUnixのクローンが作られていきました。
<br>OSが無償化されることによって、インターネット革命が強力に推進されていきます。

* Linux用語事典 [Linux]
<br>https://atmarkit.itmedia.co.jp/aig/03linux/linux.html
<br>Linuxカーネルを使っているものが、Linuxになります。

* 【10分でわかるかもしれない】シェル（shell）とは？ | CCT-recruit
<br>https://recruit.cct-inc.co.jp/tecblog/os/shell/

## 【２】Linuxディストリビューション

<br>Linuxカーネルだけでは何もできない。シェルや色々なソフトウェアがあって、はじめてOSとして機能します。
<br>そうしたセットがディストリビューションです。

* Linuxディストリビューション
<br>https://ja.wikipedia.org/wiki/Linux%E3%83%87%E3%82%A3%E3%82%B9%E3%83%88%E3%83%AA%E3%83%93%E3%83%A5%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3
<br>爆発的に様々なディストリビューションが現れたことが分かりますね。

* Linuxディストリビューションの系統図 - GIGAZINE
<br>https://gigazine.net/news/20060827_linux_distributions/
<br>主要どころは、こんなところか。

## 【３】三大ディストリビューション
それぞれ、パッケージ管理に特徴があります。

* Red Hat Enterprise Linux - Wikipedia
<br>https://ja.wikipedia.org/wiki/Red_Hat_Enterprise_Linux
<br>RPM Package Manager - Wikipedia
<br>https://ja.wikipedia.org/wiki/RPM_Package_Manager

* Debian - Wikipedia
<br>https://ja.wikipedia.org/wiki/Debian
<br>Linuxコマンド【 apt-get 】パッケージの操作・管理 - Linux入門 - Webkaru
<br>https://webkaru.net/linux/apt-get-command/

* CentOS - Wikipedia
<br>https://ja.wikipedia.org/wiki/CentOS
<br>【初心者でもわかる】yumコマンドの使い方とリポジトリの追加方法
<br>https://eng-entrance.com/linux-package-yum
<br>CentOS8からは、yumの進化版dnfが導入され、それでパッケージを行います。

## 【４】VagrantでCentOS8環境を作ってみる

* (Windows) VagrantでCentOS8を構築してSSH接続する  |  ポケットコード
<br>https://pocketcode.net/virtualbox-vagrant-centos8

* (MAC)【設定方法】VagrantとVirtualBoxでCentOS8の仮想環境をサクッと構築する手順 | とあるクリエイターのエンジニアブログ
<br>https://t-cr.jp/memo/e3179c884d698261

* dnfコマンドの使い方 - Qiita
<br>https://qiita.com/hana_shin/items/25f8f4167666cb7fa5b9

## 【５】最近のTOPIC

* Amazon Linux は何系のディストリビューションに該当するのか AWS導入開発支援
<br>https://www.acrovision.jp/service/aws/?p=653
<br>CentOS7を基にしている模様。

* CentOS Streamへのシフトでうろたえないための手引き
<br>https://zenn.dev/koduki/articles/26eb2df8109a39
<br>まだ、身の回りに事例がない。Awsなども合わせて、動向を注視したほうがよいかも。

# Porxyについて

* WEBプロキシとは？ 仕組みや機能・メリットについて解説｜SECU LABO（セキュ ラボ）｜株式会社網屋
<br>https://www.amiya.co.jp/column/web_proxy_20200911.html
<br>種類を押さえておきましょう。
* フォワードプロキシ
* キャッシュサーバ
* 透過型プロキシ
* リバースプロキシ

以上
