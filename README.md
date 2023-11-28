# robosys2023

# plusコマンド
[![test](https://github.com/yokkotaku/robosys2023/actions/workflows/test.yml/badge.svg)](https://github.com/yokkotaku/robosys2023/actions/workflows/test.yml)
* 標準入力から読み込んだ数字を足す。

## インストール方法
sshの場合
```
$ git clone git@github.com:yokkotaku/robosys2023.git 
```
httpsの場合
```
$ git clone https://github.com/yokkotaku/robosys2023.git
```

## 使用例
 * seq 10 | ./plus と入力すると、　55　と表示される

   ```
   seq 10 | ./plus
   55
   ```

 * seq 5 > nums でnumsというファイルを作ると　./plus < nums を入力すると、 15 と表示される

   ```
   seq 5 > nums
   ./plus < nums
   15
   ```

## 必要なソフトウェア
* Python
  * テスト済み: 3.7〜3.10

## テスト環境
* Ubuntu22.04


## 著作権・ライセンス
* このソフトウェアパッケージは、3か条項BSDライセンスの下、再頒布および使用が許可されます.
* このパッケージのコードは、下記のスライド（CC-BY-SA 4.0 by Ryuichi Ueda）のものを，本人の許可を得て自身の著作としたものです.
	* [ryuichiueda/my_slides robosys_2022](https://github.com/ryuichiueda/my_slides/tree/master/robosys_2022)
* © 2023 Takumi Yokoo
=======


