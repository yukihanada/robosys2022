# robosys2022
* ロボットシステム学で使用しているリポジトリです.
* このリポジトリには、plus と multiply というコマンドが含まれます.

![test](https://github.com/yukihanada/robosys2022/actions/workflows/test.yml/badge.svg)

## ダウンロード方法
* ターミナルを開いて、以下のコマンドを実行します.
```
$ git clone https://github.com/yukihanada/robosys2022.git
```
```
$ cd robosys2022
```

## plusコマンド
### 概要
* 標準入力から読み込んだ数字を足して出力します.

### 使い方
```
$ seq n | ./plus
```
* nには任意の値を入力する.

### 使用例
```
$ seq 5 | ./plus
```
* 出力結果は15になる.

## multiplyコマンド
### 概要
* 標準入力から読み込んだ数字を乗算して出力します.

### 使い方
```
$ seq n | ./multiply
```
* nには任意の値を入力する.

### 使用例
```
$ seq 5 | ./multiply
```
* 出力結果は120になる.

## 必要なソフトウェア
* Python 3.7～3.10 (動作確認済み)
* Ubuntu 20.04 (動作確認済み)

## ライセンス
* このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されます.
* このパッケージのコードは、下記のスライド (CC-BY-SA 4.0 by Ryuichi Ueda)のものを、本人の許可を得て自身の著作としたものです.
  * [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* © 2022 Yuki Hanada
