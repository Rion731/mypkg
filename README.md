# robosys2022
ロボットシステム学の練習リポジトリ
 ：このリポジトリにはaveコマンドが含まれている
# aveコマンド
![test](https://github.com/Rion731/mypkg/actions/workflows/test.yml/badge.svg)
* ave:標準入力から受け取った値の平均を返すプログラム
* 使用方法：aveのプログラムをコピーして使用する
* 平均を求めたいときに使用するプログラム
* 標準入力に値を代入するとその値を足し足した回数で割り平均を出力するプログラムである
## ファイルのダウンロード方法
* git cloneでのダウンロード
   * git clone (https://github.com/Rion731/robosys2022.git)
* ZIPファイルでのダウンロード
   * Codeタブをクリックし、左下のDownload ZIPをクリック
## 使用例
* seq 10 | ./ave

  5.5

* seq 5 | ./ave

  3.0
## 必要なソフトウェア
* Python
  *テスト済み: 3.7～3.10
## テスト環境
* Ubuntu
## ライセンス
* このソフトパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されます。
* © 2022 Rion Miura
