## 内容
上田先生のプログラムを改良しデバイスドライバを作成した。

## 機能
最初の15秒はLEDが交互に点灯し、次の5秒は両方のLEDが点灯し、そのあと両方消灯する。

## 準備するもの
・ラズベリーパイ　4  モデルB 4GB　RAM
・ブレッドボード　SAD-101
・ワイヤージャンパ　（オスオス）×2
・ワイヤージャンパ　（オスメス）×3
・LED×2

## 動作方法
make→sudo insmod myled.ko→sudo chmod 666/dev/myled0→echo 0 >/dev/myled0 

## 製作者
西廣巧

## 協力者
加藤舞子　小村岳都　嶋田雅

## youtube URL
https://youtu.be/JDUlPSItAFY

## ライセンス 
GNU General Public License v3.0
