# Objective-C SDK 文档（v2.3）
此版本的 SDK 变化情况请参考：[Leap Motion Release Notes](https://developer.leapmotion.com/documentation/python/supplements/SDK_Release_Notes.html)。

## 首先
为了帮助你开始使用 Leap Motion API 进行编程，接下来的文章将提供一个 LeapMotion 所追踪数据的概述、LeapMotion 的硬件和软件如何工作、以及如何将 SDK 设置在项目中：

* [API 综述](./devguide/Leap_Overview.md)
* [系统架构](./devguide/Leap_Architecture.md)
* [项目设置](./devguide/Project_Setup.md)

并且，作为 LeapMotion API 的最快介绍，下面的内容是非常重要的：

* [快速入门](./devguide/Sample_Tutorial.md)

## 最佳实践
一旦你有一个你能做到的好想法，那么花点时间考虑你应该做些什么，下面的文章会有帮助：

* [VR 最佳实践指南 (PDF)](https://developer.leapmotion.com/assets/Leap%20Motion%20VR%20Best%20Practices%20Guidelines.pdf)
* [手势控制介绍](https://developer.leapmotion.com/articles/intro-to-motion-control)
* [设计直观的应用程序](https://developer.leapmotion.com/articles/designing-intuitive-applications)
* [菜单设计指南](./practices/Leap_Menu_Design_Guidelines.md)
* [用户导向与教程设计指南](./practices/Leap_Orientation_and_Tutorial_Guidelines.md)
* [应用资产与营销指南](./practices/App_Assets_and_Marketing_Guidelines.md)
* [用户体验设计指南](./practices/Leap_UX_Guidelines.md)

## 深入主题
作为 LeapMotion API 的深度讨论，请参考下面的文章：

* [连接控制器](./devguide/Leap_Controllers.md)
* [追踪模型](./devguide/Leap_Tracking.md)
* [帧](./devguide/Leap_Frames.md)
* [手](./devguide/Leap_Hand.md)
* [手指](./devguide/Leap_Pointables.md)
* [手势](./devguide/Leap_Gestures.md)
* [模拟触摸](./devguide/Leap_Touch_Emulation.md)
* [动作](./devguide/Leap_Motions.md)
* [坐标系统](./devguide/Leap_Coordinate_Mapping.md)
* [摄像头图像](./devguide/Leap_Images.md)
* [序列化追踪数据](./devguide/Leap_Serialization.md)

## API 参考
**Classes:**

|||
|:--:|:--:|
|[LeapArm](../api/Leap.Arm.md)|[LeapImage](../api/Leap.Image.md)|
|[LeapBone](../api/Leap.Bone.md)|[LeapInteractionBox](../api/Leap.InteractionBox.md)|
|[LeapCircleGesture](../api/Leap.CircleGesture.md)|[LeapKeyTapGesture](../api/Leap.KeyTapGesture.md)|
|[LeapConfig](../api/Leap.Config.md)|[LeapMatrix](../api/Leap.Matrix.md)|
|[LeapController](../api/Leap.Controller.md)|[LeapPointable](../api/Leap.Pointable.md)|
|[LeapDevice](../api/Leap.Device.md)|[LeapScreenTapGesture](../api/Leap.ScreenTapGesture.md)|
|[LeapFinger](../api/Leap.Finger.md)|[LeapSwipeGesture](../api/Leap.SwipeGesture.md)|
|[LeapFrame](../api/Leap.Frame.md)|[LeapTool](../api/Leap.Tool.md)|
|[LeapGesture](../api/Leap.Gesture.md)|[LeapVector](../api/Leap.Vector.md)|
|[LeapHand](../api/Leap.Hand.md)||

**Protocols:**

|||
|:--:|:--:|
|[LeapListener protocol](../api/Leap.Listener.md)|[LeapDelegate protocol](../api/Leap.Delegate.md)|

**Categories:**

[LeapPointableOrHandList](../api/Leap.HandList.md)

## 附录

* [Leap Motion Release Notes](./supplements/SDK_Release_Notes.md) 
* [使用 LeapMotion 控制面板](./supplements/Leap_Application.md)
* [使用诊断可视化工具](./supplements/Leap_Visualizer.md)
* [WebSocket 通信](./supplements/Leap_JSON.md)
* [鸣谢](./supplements/Leap_Acknowledgements.md)
