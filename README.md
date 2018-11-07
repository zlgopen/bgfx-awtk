# bgfx-awtk

bgfx用在awtk平台的版本

##目录对应顺序

* 1.bgfx-awtk <---> awtk/3rd/bgfx
* 2.nanovg <---> awtk/3rd/nanovg
* 3.SConstruct <---> awtk/SConstruct
* 4.SConscript <---> awtk/3rd/bgfx/SConscript

##bgfx对应bx和bimg版本

* 1.bgfx:https://github.com/bkaradzic/bgfx.git   SHA-1: 52a5ca839c32c15968905c4584b8025e17881125
* 2.bx：https://github.com/bkaradzic/bx.git  SHA-1: 5c17a7d678a26fd3d9f9ca08a5285b7caf487678
* 3.bimg：https://github.com/bkaradzic/bimg.git  SHA-1: 4efac57133387b7d345c7d551c699b11891fd053

##编译
* 1.使用scons编译时需要克隆bgfx、bx和bimg这三个库到awtk/3rd/bgfx目录下一起编译
