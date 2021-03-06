# ２０２０年度の高専プロコンは競技部門中止になりました。

２０２０年度の高専プロコンは競技部門中止になりました。
適切な判断だとは思いますが、楽しみにされていた方も多かっただろうだけに残念です。

プロジェクトは塩漬け予定です。
# KosenProcon31
高専OBの個人的な趣味で高専プロコン第３１回の開発しているレポジトリです。私が作成した部分については教育と学習目的での自由な使用を許可しますが、それ以外は元のライセンスに従います。使用の際の責任は一切私にはありません。現状のみで提供、引用元の表示は必要ありません。

## 作成環境・動作環境

* Windows 10
* Visual Studio 2019
* OpenSiv3D 0.4.2
* libcurl

## 検討予定の方針

* 範囲点を取りに行くor陣地点を取りに行く
* 相手の動きを考えるor相手の動きを考えない
* 幅優先探索的な動作をするor各エージェントごとにいい感じの方策を独立にN個（現状９程度）打ち出して競合解決を行う。
* たくさんのガラッと違う方式を試すor一つを並列化などを用いて練り上げる
* エージェントを最初からいっぱい使う（強そう）or保持しておく
* マップの既知性を用いた戦略

## メモ

* ターン時間3～15秒
* ターン数30~100

### 前回と同じ点

* 陣取りゲーム
* 移動方向は８方向＋停留
* 点数は-16から16まで
* 移動・除去等の動作（置いておけば全部動かせる）
* 複数チーム対戦
* 点数の計算方式と勝敗判定

### 前回と異なる点

* 点数の配置に対称性がない
* 城塞と陣地の概念
* 陣地が残る点
* マップの広さ12\*12から24\*24まで（24*24=576）
* エージェント数１チーム6から14まで（多すぎね）
* エージェントは任意のタイミングで置ける（配置）
* マップがすべて既知

## 参考

* 公式 "http://www.procon.gr.jp/"
* 募集要項　"http://www.procon.gr.jp/wp-content/uploads//2020/04/2eddfc1dcddbd516b49effcad6cee2ed.pdf"


