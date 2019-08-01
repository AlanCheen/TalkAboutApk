# 聊聊 APK 相关代码



Clone 项目到本地，cd 到项目目录即可。



### 手机运行 Dex



```shell
adb push classes.dex /sdcard/
adb shell
cd sdcard
dalvikvm -cp classes.dex Hello
```







### 热修复



