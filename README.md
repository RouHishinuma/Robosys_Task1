# Robosys_Task1

## 概要
LEDを4つ点灯させるデバイスドライバ

## 使用した道具
- rasberry Pi ４ modelB
- LED(青緑各２つ)
- ブレッドボード
- ２２０Ω抵抗x4
- ジャンパー線x8

## デモ動画のリンク
- https://youtu.be/c9RqI9lCCIk

## インストール方法



## 使用方法

```
$ make
$ sudo insmod myled1.ko
$ sudo chmod 666 /dev/myled10
```
```
点灯
$ echo 1 > /dev/myled10
消灯
$ echo 0 > /dev/myled10
```

## ライセンス


