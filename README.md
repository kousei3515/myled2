# myled2
LEDを点灯及び点滅させるデバイスドライバです。
使い方は以下のようになっています。

$echo 0 > /dev/myled0　　//LEDライトを点灯

$echo 1 > /dev/myled0　　//LEDライトを消灯

$echo 2 > /dev/myled0　　//LEDライトを1秒間点灯させたら1秒間消灯させる、一連の流れを10回繰り返す。

デモ動画はこちらになります。
https://youtu.be/FMXCgck0axs

