# system_install

# 1 img


```
https://www.raspberrypi.org/downloads/raspbian/

下载:Raspbian Buster Lite
2020-02-13-raspbian-buster-lite

#解压
unzip 2020-02-13-raspbian-buster-lite.zip

#unmount boot分区
diskutil unmount /dev/disk3s1

#dd命令写入系统到sd卡
time sudo dd bs=4m if=2020-02-13-raspbian-buster-lite.img  of=/dev/disk3
```
