# Robosys_Task1

- 概要

　講義内で作成したデバイスドライバをもとに改造したLEDを4つ点灯させるデバイスドライバ

## 使用した道具
- rasberry Pi ４ modelB
- LED(青緑各２つ)
- ブレッドボード
- ２２０Ω抵抗x4
- ジャンパー線x8

## デモ動画のリンク
- https://youtu.be/c9RqI9lCCIk

## インストール方法
```
$ git clone https://github.com/RouHishinuma/Robosys_Task1.git
```

## 使用方法

```
$ make
$ sudo insmod myled.ko
$ sudo chmod 666 /dev/myled0
```
```
点灯
$ echo 1 > /dev/myled10
消灯
$ echo 0 > /dev/myled10
```

## ライセンス
[GNU General Public License v3.0](https://github.com/RouHishinuma/Robosys_Task1/blob/master/COPYING)


