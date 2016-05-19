# Lame
lame
WAV音频文件转码为MP3格式
从网上找到lame的静态库包，发现不支持64位和模拟器，自己去官网下载了源码后，重新生成flat静态包（支持x86/armv7/arm64），具体可以使用  lipo -info *.a查看。
