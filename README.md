# REDROCK 移动开发部 Android 2023年暑假考核

## 📝写在前面

​	紧张的写课件阶段已经结束，迎来了我们的开发考核！一年来，你们经历了从“Hello World”到能够开发跃动于指尖的APP的成长。每一节课、每一次作业、每一个夜晚，都是你们不懈努力的见证。在这个暑假，你们面临的是新的挑战，也是展示自己的机会。

​	在这一学期里，你们或许经历了艰辛、熬夜、掉头发，但这些都是成长的必经之路。当你打开这个页面，你已经不再和其他人一样了。你已经成为了一名优秀的Android开发者，你拥有着自己的技能和能力，也要有自信和勇气展示自己的成果。

​	最后，我们在心里默默地为你们加油💪，希望你们能够克服紧张和压力，保持专注和耐心，发挥自己的水平和能力，创造出优秀的作品！

## 考核要求

- 考核采用多人开发，两个人一组选择一个选题。建议使用多模块开发，否则合并冲突会让你崩溃。
- 请合理分配团队工作
- 一个选题只能有两个组选择
- **每天至少需要一个commit**
- 个人表现和在团队里的贡献会作为最终评测标准。

## APP 要求

### 基本要求

- API 兼容到 Android6.0（API 24）
- 只能使用 `Kotlin`
- 代码中**重要函数和变量**需要有注释，不要求全部都写

- 完整的 README，必须包含：
  - 每人都需要写一份README
  - APP简要介绍，使用步骤
  - 在团队里所做的工作介绍（所负责的模块、功能、使用步骤等）附 Gif 图片）
  - 使用到的比较重要的技术及知识点
  - 不足之处
  - 心得体会
- 考核期间如果遇到**运行时 bug**，原则上**不能向学长求助**，如果是无法编译问题，百度后仍无法解决则可以在大群里面提问
- 请使用自己擅长的技术，**不熟练就谨慎使用**。
- 因为有 12 天开发 + 3 天改 bug，所以要求谈心时的最终版本无明显闪退 bug（**记得做好断网时的网络请求出错处理**）

### 依赖要求

- 禁止

  使用除以下库外的其他库，可使用的库如下：

  - 所有 `google` 库
  - 所有 `android` 以及 `androidx` 库
  - 所有 `jetbrains` 库（协程包含在这里面）
  - 部分第三方库
    - [`ARouter`](https://github.com/alibaba/ARouter)
    - [`Glide`](https://github.com/bumptech/glide)
    - [`Lottie`](https://lottiefiles.com/blog/working-with-lottie/getting-started-with-lottie-animations-in-android-app)
    - [`Retrofit`](https://github.com/square/retrofit)
    - [`Okhttp`](https://github.com/square/okhttp)
    - [`Gson`](https://github.com/google/gson)
    - [`Rxjava`](https://github.com/ReactiveX/RxJava)
    - [`RxPermissions`](https://github.com/tbruyelle/RxPermissions)：一个权限申请库
    - [`PhotoView`](https://github.com/Baseflow/PhotoView)：一个专门查看图片的库
    - 如果你做的项目需要使用到视频播放的功能，允许使用播放视频的第三方库（因为官方库有坑）
    - 如果对依赖有特殊要求，请在大群里提问
    - 如果使用自己的依赖库，有如下要求
      - 不能是 fork 来的
      - 绝大部分代码是自己所写

- 由于本次考核需要衡量你们接手掌邮的能力，所以**强烈不推荐**使用 `compose`。

- `Banner`（轮播图）请自己实现

### 设计要求

- MVVM 架构，允许在简单网络请求时不设计仓库层
- 需包含网络请求
- 好看的 UI

### 特殊要求

- 需要公开你的仓库，**从考核第一天开始**
- 如果不想公开，可以在私有仓库的情况下把我们设置成贡献者
  - 点击 Settings - Collaborators - Add people
  - 输入以下学长的 github 名字
    - 冉：RQ527
    - 王：uai-uai
- 别忘了前面要求的**每天至少一个commit**

## 考核选题

## 开眼（不考虑登录情况）

接口很凌乱，但能写出来一个完整的 `app`，以下给出一些其他项目，里面包含了部分接口

https://www.wanandroid.com/blog/show/2718

https://github.com/fmtjava/Jetpack_Kotlin_Eyepetizer

详细的接口分析文档：https://github.com/1136535305/Eyepetizer/wiki/开眼-API-接口分析

![img](https://github.com/985892345/Redrock2022-AndroidSummerWork/raw/main/img/%E5%BC%80%E7%9C%BC%E9%83%A8%E5%88%86%E6%8E%A5%E5%8F%A3.png)

由于该接口中会用到视频播放，所以允许使用第三方视频播放开源库（推荐DKVideoPlayer）

### 网易云音乐

接口文档：[网易云音乐 API (why.vin)](http://why.vin:2023/)

音乐播放器和MV播放可使用三方库。

## 其他问题

**考核完后可以回家吗？**

具体询问自己辅导员，通过了这边就可以放人。

**学校让暑假做社会实践怎么办？**

社会实践在暑假留校后就可以在网校开证明，考核没有通过的也能开。

**重要的事情说三遍：**



### 不要熬夜！

## 不要熬夜！

# 不要熬夜！



### 严禁通宵！

## 严禁通宵！

# 严禁通宵！

