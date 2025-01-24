# harmonyOS

## 基础学习

1. 开发环境构建 DevEco Studio 的使用
2. ArkTS 语法介绍
    a. 类型和函数
    b. 类class定义
    c. 接口和泛型
    d. 空安全和模块
    e. 声明式UI语法
3. 鸿蒙应用程序框架 UIAbility 介绍使用
    a. 应用创建状态
    b. 应用ui加载状态
    c. 应用处于前台或后台
    d. 应用销毁态
4. ArkUI
    a. 基础组件：Text、image、TextInput、Button、LoadingProgress、资源引用类型
    b. 容器组件：Column、Row 主轴和交叉轴
    c. 列表组件：List、Grid、长列表性能优化
    d. 页签组件：tabs、布局模式、自定义样式
5. 页面状态管理
    a. 父子组件状态装饰器：@State、@Prop、@Link
    b. 后台组件状态装饰器：@Provide和@Consume、@Observed和@ObjectLink
    c. Video组件：加载本地视频、播放网络视频、video控制器使用
    d. 应用弹窗：警告弹窗、文本弹窗、日期选择弹窗、自定义弹窗
6. 网络数据访问
    a. http，状态码、请求头、请求参数
7. 应用本地数据保存
    a. 用户首选项和运作机制
    b. 首选项接口：保存、获取、键查询、持久化、删除
   
## 进阶

1. Stage模型
    a. AbilityStage
    b. UIAbility启动模式
    c. Stage模型程序包结构
    d. HSP动态共享包：使用场景、约束限制、开发和使用
    e. HAR静态共享包：实现多个模块或多个工程间共享Arkui组件、资源
2. 动画和转场
    a. 动效场景设计：特征动效、转场动效、手势动效、微动效、插画动效
    b. 动画能力选型：系统能力、资源调用、第三方库
    c. 转场场景设计：转场动效、转场场景、场景解构
    d. 转场场景开发：转场能力、动画能力
3. Web组件：使用webview组件来显示控制网页
    a. Web组件加载本地网页资源，加载在线网页
    b. webView使用：WebViewController，ArkTS调用H5
4. 媒体（音视频）
5. 数据安全（加解密）
    a. 使用security接口实现各种加解密
    b. 使用cert接口实现对签名数据进行校验
    c. 使用cryptoFramework实现对文本文件进行加解密、签名和验证签名
    d. 使用Cipher对象实现字符串加解密算法、例如RSA、AES等加密算法
6. 文件与分享
    a. 了解沙箱和picker
7. 应用通知与提醒
    a. 通知表现形式和接口
    b. 创建通知、设置通知通道、创建通知组、为通知添加行为意图
    c. 后台代理提醒:倒计时类、日历类、闹钟类
8. Native适配来开发
    a. Node-APi
9. 三方库使用
    a. 如果获取第三方库
    b. ui库、网络库、动画库、其他类别
    c. 使用开元第三方库lottie”
    d. 移植三方库
10. HarmonyOS SDK 开放能力简介
11. 应用质量测试
12. 鸿蒙应用/元服务上架

## HarmonyOS SDK 开放能力集

1. AppGallery Connect
    a. 如何在 AppGallery Connect 上创建应用
    b. 如何配置指纹证书
    c. 如何调用华为帐号服务的 API 接口
2. 应用内支付服务
3. 推送服务
4. 位置服务
5. 扫码服务
6. 游戏登录服务
7. 通用文字识别
8. 华为支付服务
9. 地图服务
