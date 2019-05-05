# Resume

## 个人信息

- 工作年限: 四年
- 技术`Blog`: https://github.com/Link913/StudyBlog
- 简书: https://www.jianshu.com/u/452e0bd1e30f
- 居住地: 上海

## 个人简介

熟练日常的iOS项目开发, 对工程体系, 架构, 组件解耦依赖都有一定程度的理解. 喜欢研究新技术, 关注`Apple WWDC`. 对`Objc`, `Swift`都有大范围的使用.

## 技能清单

- 语言: 熟练使用`Swift`, `Objc`. 熟悉`C / C ++`, 了解`Ruby`, `Java`.
- `Objc`运行时: 架构设计, `AppDelegate`减负.
- 响应式编程: `ReactiveCocoa`.
- 音视频经验: 了解`FFMpeg`, `SDL`, `GLKit`部分使用.
- 版本管理: `Git`, `SVN`.
- `CI / CD`: `Fastlane`, `travisci`.
- 单元测试: Xcode自带的UT.
- 项目优化: 启动时间, 包体积, 帧率, 路由高聚合升级, 组件解耦实施.

## 工作经历

### DaDaABC(上海赞颢科技) 2018.9 - 2019.5

- 职责: 架构升级, 业务开发, 基础组件开发, 项目优化, `BUG`修复, 路由升级, 自动化打包, 一些新技术的研究储备比如`Protobuf`的接入研究.
- 项目: `DaDaABC家长端`
- 业务线: 有声绘本, 口语练习, 语句跟读, 学习阶段视频编码上传.
- 技术点: 
	- 组件解耦通过依赖注入协议工厂实施.
	- 路由高聚合升级
	- 包体积优化
	- `webView`升级

### 维信金科(上海固浚外派) 2017.1 - 2018.8

- 职责: 业务开发, 接口制定, `BUG`修复.
- 项目: `信用猫(项目已下线)`
- 业务: 小额网贷的收集资料, 授信, 放贷, 还款, 会员体系, 第三方贷款业务对接等.

### 上海乐野 2016.6 - 2017.1

- 职责: 视频编解码模块开发, `App`接入, 音视频推拉流研究, 播放器渲染`YUV420p`研究
- 项目: `kShow手机线上端(离职时已暂停,目前不清楚)`
- 业务: 将硬件上采集的音频结合iphone推流到线上, 并保持音视频同步.

## 开源项目

- `UCRuntimeKit`: https://github.com/TryRuntime/UCRuntimeKit, 一个通过字符串来进行`Runtime`派发的一个安全的工具, 经过了`300`条左右的`UT`测试, 支持异常抛出, 多参数派发, `Block`派发等等.

- `UCAppDelegateReduce`: https://github.com/TryRuntime/UCAppDelegateReduce, 利用`Objc runtime`来减负`AppDelegate`的小工具, 支持`位移枚举`, 不需要`Hard Code`, 且调用过程安全, 依赖`UCRuntimeKit`进行安全派发消息.

- `UCRouterObjc`: https://github.com/TryRuntime/UCRouterObjc, 利用`协议`依赖注入以及`URL`注册来实现解耦项目的一个`Objc`版本.

- `UCRouterSwift`: https://github.com/TryRuntime/UCRouterSwift, 利用`协议`依赖注入以及`URL`注册来实现解耦项目的一个`Swift`版本.