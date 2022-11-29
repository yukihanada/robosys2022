# robosys2022
![test](https://github.com/yukihanada/robosys2022/actions/workflows/test.yml/badge.svg)
# コマンド
* plus
  * 標準入力から読み込んだ数字を足す.
* multiply
  * 標準入力から読み込んだ数字を掛ける.

## ダウンロード方法
1. ダウンロードしたいディレクトリでリポジトリをクローンする.
```
git clone https://github.com/yukihanada/robosys2022.git
```
2. robosys2022に移動してコマンドを実行する.
```
cd robosys2022
```

## plusコマンド
* 使い方
```
seq n | ./plus
```
nには任意の値を入力する.

* 使用例
```
seq 5 | ./plus
```
出力結果は15になる.

## multiplyコマンド
* 使い方
```
seq n | ./multiply
```
nには任意の値を入力する.

* 使用例
```
seq 5 | ./multiply
```
出力結果は120になる.

## 必要なソフトウェア
* Python 3.7～3.10

## 動作確認済み環境
* Ubuntu 20.04

## ライセンス
* このソフトウェアパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されます.
* このパッケージのコードは、下記のスライド (CC-BY-SA 4.0 by Ryuichi Ueda)のものを、本人の許可を得て自身の著作としたものです.
  * [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* © 2022 Yuki Hanada
