# mypkg
ROS2の練習リポジトリ
 ：このリポジトリにはtalker.pyとlistener.pyコマンドが含まれている
# talker.pyコマンド
![test](https://github.com/Rion731/mypkg/actions/workflows/test.yml/badge.svg)
* talker.py: 数字をカウントアップしてトピック/countupを通じてlistener.pyにデータを送信するノードである
* メッセージの型は16ビット符号付き整数である

# listener.pyコマンド
* listener.py: /countupからメッセージを受け取り表示するサブスクライバをもつノードである

## 使用例
* 端末1

  ros2 run mypkg talker

* 端末2

 ros2 run mypkg listener

 [INFO] [1672323191.834832600] [listener]: Listen: 37

 [INFO] [1672323192.327138300] [listener]: Listen: 38

 [INFO] [1672323192.826892300] [listener]: Listen: 39

## 必要なソフトウェア
* Python
* ROS2
## テスト環境
* Ubuntu
## ライセンス
* このソフトパッケージは、3条項BSDライセンスの下、再頒布および使用が許可されます。
* © 2022 Rion Miura
