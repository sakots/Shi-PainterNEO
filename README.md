# Shi-PainterNEO

お絵かきペインター Shi-Painter (©2000-2004しぃちゃん) をhtml5化するプロジェクトです。  
作者行方不明のため、許諾は取っていません。  

しぃちゃんのホームページ（Vector）  
[http://hp.vector.co.jp/authors/VA016309/](http://hp.vector.co.jp/authors/VA016309/)

PaintBBSのHTML5化ができるんだから、しぃぺいんたーもできるんじゃない？ということでやってみます。

-> [neo](https://github.com/funige/neo/)

あとあれ。cheerpjのロード待ち時間が長いのでなんとかしたかった。

## 対応環境

Chrome/FireFox/Safari/Edge iOS(Mobile Safari)
※ 最新のバージョンのみ

Windowsで線がうまく引けない場合は、以下をお試しください

- Chromeを使う
- wacomのタブレットを使用している場合は「デジタルインク(WindowsInk)を使用する」をオフにする

Firefox(59以降？)はタブレット関係のバグがあるらしく、線が乱れることがあるようです。
マルチプロセスを切ると症状が解消されるかもしれません。（about:configでbrowser.tabs.remote.autostartをFalse）

Chrome(80以降？)で横に長い線を引くとジェスチャーと誤認識される場合は、chrome://flags/#overscroll-history-navigation でジェスチャーを無効にするといいかもしれません。

## お絵かき掲示板の設置方法について

新しくお絵かき掲示板を設置したい方には、ROISの利用をお勧めします。

- [お絵かきBBSラボ](https://dev.oekakibbs.net/) - ROIS

POTI-boardももしかしたら対応するかもしれません。

- [POTI-board改公式サイト](https://pbbs.sakura.ne.jp/poti/) - POTI-board EVO

## 履歴

### [2021/07/05]

- プロジェクト開始
- とりあえずVue.jsつかってみるかー
