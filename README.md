
# 1. win32 development envrionment of AS setup

## 1.1 download the [win32/MinGW.7z](https://github.com/parai/asenv/tree/master/win32) and extract to path as "C:\MinGw"

This MinGw has integrated a lot of 3rd party packages, such as GTK/wget/gnutls...etc, better to use this to develop AS. Use other mingw is okay, but you may need to install some AS rely package by yourself.

![mingw path](https://github.com/parai/asenv/blob/master/win32/mingw_path.jpg?raw=true)

## 1.2 add MinGw to environment PATH

![mingw env](https://github.com/parai/asenv/blob/master/win32/mingw_env.jpg?raw=true)

I guess you know how to handle windows environment PATH, for the below instruction, there is no picture showing how to add path to environment PATH.

## 1.3 install python2.7 and scons

* download this [win32 python2.7](https://www.python.org/ftp/python/2.7.14/python-2.7.14.msi) and install it and then add path "C:\Python27\Scripts" to environment PATH

* download the [scons](http://scons.org/pages/download.html) and install it for python 2.7

## 1.4 install python3 and pyQt5

* download this [win32 python3](https://www.python.org/ftp/python/3.6.3/python-3.6.3.exe) and install it.

* dowhload this [win32 pyQt5](https://pypi.python.org/packages/03/03/f42a3f893c4f7b08dfc3f6187b2db5558ee3ca194180bbd8b85b8721e825/PyQt5-5.9.1-5.9.2-cp35.cp36.cp37-none-win32.whl#md5=c88436dda54af7c759fa149d76eeca87) and install it.

* install [bitarray](https://pypi.python.org/packages/0a/da/9f61d28a20c42b4963334efacfd257c85150ede96d0cd2509b37da69da47/bitarray-0.8.1.tar.gz) and [pyserial](https://pypi.python.org/packages/1f/3b/ee6f354bcb1e28a7cd735be98f39ecf80554948284b41e9f7965951befa6/pyserial-3.2.1.tar.gz#md5=7142a421c8b35d2dac6c47c254db023d) for python3 for [as.one.py](https://github.com/parai/as/tree/master/com/as.tool/as.one.py) tool

# 2. prebuild of [asqemu](https://github.com/parai/as/tree/master/com/as.tool/qemu) for ascore arm simulation

* It was possible to build it out through this [PKGBUILD](https://github.com/parai/as/blob/master/com/as.tool/qemu/PKGBUILD) on msys2-w64

## 2.1 install [wpcap](https://www.winpcap.org/install/bin/WinPcap_4_1_3.exe)

## 2.2 download [asqemu](https://github.com/parai/asenv/raw/master/x64/asqemu.zip) and then you can use it directly
