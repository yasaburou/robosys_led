# myled
LEDでSOSのモールス信号を点灯する
# 実行方法
```
$ make
$ sudo insmod myled.ko
$ sudo chmod 666 /dev/myled0
$ echo 1 > /dev/myled0　//実行
$ sudo rmmod myled      //後処理
```
# YouTube
https://youtu.be/NAL_sLcPpQk
