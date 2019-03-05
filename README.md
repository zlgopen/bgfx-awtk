# bgfx-awtk

bgfx用在awtk平台的版本

##目录对应顺序

* 1.bgfx-awtk <---> awtk/3rd/bgfx
* 2.nanovg <---> awtk/3rd/nanovg
* 3.SConstruct <---> awtk/SConstruct
* 4.SConscript <---> awtk/3rd/bgfx/SConscript
* 5.src <---> awtk/src

##bgfx对应bx和bimg版本

* 1.bgfx:https://github.com/bkaradzic/bgfx.git   SHA-1: 52a5ca839c32c15968905c4584b8025e17881125
* 2.bx：https://github.com/bkaradzic/bx.git  SHA-1: 5c17a7d678a26fd3d9f9ca08a5285b7caf487678
* 3.bimg：https://github.com/bkaradzic/bimg.git  SHA-1: 4efac57133387b7d345c7d551c699b11891fd053
* 4.awtk：https://github.com/zlgopen/awtk.git  SHA-1: d46441f5ee1f6a6d1c027b498a83775818d87b6d

##编译
* 1.克隆awtk工程到本地，然后克隆bgfx、bx和bimg这三个库到awtk/3rd/bgfx
* 2.将文件拷贝到awtk对应的目录下使用scons命令进行编译。
