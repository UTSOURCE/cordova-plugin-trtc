# cordova-plugin-trtc

腾讯实时音视频(TRTC)封装cordova插件 (示例)

具体原生项目参考tencent的demo, 源码大部分从这里搬运:

[https://github.com/zhaoyang21cn/Android_TRTC](https://github.com/zhaoyang21cn/Android_TRTC)


[https://github.com/zhaoyang21cn/iOS_TRTC](https://github.com/zhaoyang21cn/iOS_TRTC)

iOS的sdk需要自己添加到src/ios/libs下, 可以从官网获取




先clone一个cordova-plugin-trtc文件夹到项目的plugins文件夹下面, 然后shell跑一下
cordova platform rm ios
cordova plugin add cordova-plugin-trtc --variable APP_ID="你的appid"
cordova platform add ios
cordova build ios
android同理
