# oneko
 
 onekoは、マウスカーソルを追うネコを表示するためのソフトウェアです。生成されたバイナリ`oneko`を実行することにより、
マウスカーソルに合わせて行動するデスクトップ マスコットを表示することができます。ﾆｬｰｵ。

## ビルド手順

　このソフトウェアのソースは、debianのリポジトリ`http://ftp.debian.org/debian/pool/main/o/oneko/oneko_1.2.sakura.6.orig.tar.gz`から取得されたものであり、それらのミラーです。しかしながら、このソースはLinuxにおいて不必要な（あるいはふさわしくない）項目が削除されており、改変無しではバイナリが生成できないものとなっています。これは、削除された項目の為の改変無しで`oneko`バイナリを生成できるようにしたものです。

 - ビルドに必要なライブラリ郡の取得

` $ sudo apt install libx11-dev libxext-dev gcc `

 - Makefileの生成

` $ xmkmf `

 - ビルド

` $ make `
　
 これにより、実行可能なonekoバイナリが生成されます。

## 著者

* オリジナルである"xneko"は、 Masayuki Koba氏によって書かれました。
* "oneko"は、Tatsuya Kato氏によって"xneko"を改善することにより作られました。
* さらに、以下の方が編集・改善を行っております。
  - John Lerchey氏
  - Eric Anderson氏
  - Toshihiro Kanda氏
  - Kiichiroh Mukose氏

* オリジナルのoneko-sakuraは、以下より入手することができます。
[1]: http://www.daidouji.com/oneko/

## ライセンス

フリーソフトウェア財団によると、onekoはパブリックドメイン ソフトウェアです。これらはREADMEで示されています。
[1]: https://directory.fsf.org/wiki/Oneko#tab=Details

