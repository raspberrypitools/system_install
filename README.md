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

# 2 二次刷系统.

参考:http://www.wangbokun.com/%E7%89%A9%E8%81%94%E7%BD%91/2019/03/18/%E6%A0%91%E8%8E%93%E6%B4%BE.html#12-%E5%AE%89%E8%A3%85%E7%B3%BB%E7%BB%9F
