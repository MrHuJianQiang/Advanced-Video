# Quick Switch iOS

这个开源示例项目演示了如何使用 Agora视频SDK实现快速切换频道。

## 运行示例程序

首先在 [Agora.io](https://dashboard.agora.io/) 注册账号，并创建自己的测试项目，获取到 AppID。将 AppID 填写进 KeyCenter.swift 对应位置。

然后在 [Agora.io SDK](https://docs.agora.io/cn/Agora%20Platform/downloads) 下载 **视频通话/视频直播 SDK**，解压后将其中的 **AgoraRtcEngineKit.framework** 复制到本项目的 "Quick-Switch" 文件夹下。

最后使用 Xcode 打开 Quick-Switch.xcodeproj，连接 iPhone／iPad 测试设备，设置有效的开发者签名后即可运行。

##使用方法

1. 使用另外四台设备在[OpenLive](https://github.com/AgoraIO/Basic-Video-Broadcasting)分别以主播身份进入 *channel1*, *channel2*, *channel3*, *channel4* 四个频道；
2. 打开本应用，任意选择一个频道进入；
3. 上下滑动切换到其他频道。

## 运行环境

* Xcode 10.0 +
* iOS 10.0 +
* 真机设备，不支持模拟器

## 联系我们

- 完整的 API 文档见 [文档中心](https://docs.agora.io/cn/)
- 如果在集成中遇到问题，你可以到 [开发者社区](https://dev.agora.io/cn/) 提问
- 如果有售前咨询问题，可以拨打 400 632 6626，或加入官方Q群 12742516 提问
- 如果需要售后技术支持，你可以在 [Agora Dashboard](https://dashboard.agora.io) 提交工单
- 如果发现了示例代码的bug，欢迎提交 [issue](https://github.com/AgoraIO/Advanced-Video/issues)

## 代码许可

The MIT License (MIT).
