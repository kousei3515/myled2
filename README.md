# myled2
LEDを点灯及び点滅させるデバイスドライバです。
使い方は以下のようになっています。

$echo 0 > /dev/myled0　　///dev/myled0に0を書き込み、LEDライトを消灯

$echo 1 > /dev/myled0　　///dev/myled0に1を書き込み、LEDライトを点灯

$echo 2 > /dev/myled0　　///dev/myled0LEDライトに2を書き込み、1秒間点灯その後1秒間消灯させる。この一連の流れを10回繰り返す。

デモ動画はこちらになります。
https://youtu.be/FMXCgck0axs

