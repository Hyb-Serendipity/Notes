# 小技巧

小技巧

## 1. 切换地区

[https://www.cooleasy.com/publicProxy/](https://www.cooleasy.com/publicProxy/)

[http://free-proxy.cz/zh/proxylist/country/DE/all/ping/all](http://free-proxy.cz/zh/proxylist/country/DE/all/ping/all)

截图 f12 Ctrl+Shift+P capture

## 2. apktool

[https://blog.csdn.net/qq\_27292113/article/details/79931268](https://blog.csdn.net/qq_27292113/article/details/79931268)

apktool.bat

```text
@echo off
if "%PATH_BASE%" == "" set PATH_BASE=%PATH%
set PATH=%CD%;%PATH_BASE%;
chcp 65001 2>nul >nul
java -jar -Duser.language=en -Dfile.encoding=UTF8 "%~dp0\apktool_2.3.1.jar" %*
```

使用ApkTool对apk进行反编译

```text
apktool.bat d -o outDir 111.apk
```

使用ApkTool对apk进行打包

```text
apktool.bat b -o new.apk outDir
```

https://huyaohui.com/2019/03/13/geng-gai-android-apk-bao-ming-da-dao-shuang-kai-shen-zhi-duo-kai-de-mu-de/

https://www.tunefab.tw/youtube/download-youtube-to-mp4.html



