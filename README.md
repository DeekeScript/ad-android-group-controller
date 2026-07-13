# DeekeHub —— 新一代 Android 自动化云平台
<img src='https://home.deeke.top/Index/githubStatistic?name=github-ad-android-group-controller' width=0 height=0 />

> **让 Android 自动化，从“控制一台手机”，升级到“管理成千上万台设备”。**

> 产品试用，请访问 [https://hub.deeke.cn](https://hub.deeke.cn)

![GitHub stars](https://img.shields.io/github/stars/your-repo?style=flat-square)
![License](https://img.shields.io/badge/license-MIT-blue.svg)
![Platform](https://img.shields.io/badge/platform-Android-green.svg)
![JavaScript](https://img.shields.io/badge/script-JavaScript-yellow.svg)

---

## 📖 项目简介

2026年的今天，Android 自动化技术已经非常成熟。

无论是 AccessibilityService、OCR、图像识别、模拟点击、远程控制、脚本执行……市面上已经有很多优秀的解决方案。

但是，当真正进入企业项目后，我们发现新的问题才刚刚开始。

例如：

- 一百台手机如何统一管理？
- 如何批量执行脚本？
- 如何远程查看手机画面？
- 如何给不同客户分配设备？
- 如何管理脚本版本？
- 如何让运营人员不会编程也能使用？
- 如何统计设备在线状态？
- 如何查看脚本执行日志？
- 如何支持 SaaS、多租户、权限管理？

这些问题，已经不是"自动化脚本"能够解决的。

它需要的是一个真正的 **Android 自动化平台**。

于是，便有了 **DeekeHub**。

---


# 在线演示

[https://www.bilibili.com/video/BV1AvNV6sEux](https://www.bilibili.com/video/BV1AvNV6sEux)

---

# 为什么先有 DeekeScript？

在 DeekeHub 出现之前，我们已经持续维护 Android 自动化框架 **DeekeScript** 多年。

DeekeScript 是整个 DeekeHub 的核心运行引擎。

所有脚本最终都会运行在 DeekeScript Runtime 中。

可以理解为：

```
JavaScript
      │
      ▼
 DeekeScript Runtime
      │
      ▼
 Android 系统能力
      │
      ▼
 Accessibility
 OCR
 图像识别
 HTTP
 WebSocket
 文件系统
 多线程
 定时任务
......
```

开发者只需要编写 JavaScript。

复杂的 Android API 已经全部封装。

相比直接开发 Android App，开发效率大幅提升（亲测，效率提升5-10倍）。

---

# 为什么还要做 DeekeHub？

如果说：

DeekeScript 解决的是：

> **"如何开发自动化脚本？"**

那么 DeekeHub 解决的是：

> **"如何管理所有自动化脚本？"**

当设备数量达到几十台、几百台甚至几千台的时候。

真正困难的已经不是写脚本。

而是：

- 如何管理设备？
- 如何批量执行？
- 如何查看日志？
- 如何远程维护？
- 如何控制权限？
- 如何多人协作？

于是，我们把所有能力全部云平台化。

这就是 DeekeHub。

---

# 🚀 DeekeHub 能做什么？

## 📱 设备管理

统一管理所有 Android 设备。

支持：

- 在线状态
- 网络状态
- 品牌型号
- 分组管理
- 标签管理
- 搜索
- 批量操作

无需 ADB。

无需 USB。

设备联网即可管理（私有化也支持局域网部署）。

---

## 🖥 远程实时查看

支持实时查看 Android 设备画面。

适用于：

- 远程维护
- 调试脚本
- 客户演示
- 在线巡检

采用低带宽实时传输。

支持不同画质模式。

让远程查看更加流畅。

---

## ⚡ 批量执行

真正做到：

一次操作。

全部设备执行。

例如：

- 批量安装 APK
- 批量更新脚本
- 批量启动任务
- 批量停止任务
- 批量重启设备

真正释放人工。

---

## 📜 脚本管理

脚本统一管理。

支持：

- 在线上传
- 多版本管理
- 灰度发布
- 批量下发
- 在线更新

不用再一台台复制脚本。

---

## 👥 权限系统

支持企业级权限管理。

例如：

- 超级管理员
- 开发人员
- 运营人员

不同角色拥有不同权限。

非常适合商业项目。

---

## 📊 日志中心

脚本执行过程全部记录。

包括：

- 执行日志
- 错误日志
- 历史记录
- 在线状态
- 运行统计

真正做到可追踪。

---

## 🌐 开放接口

所有核心能力均可通过 API 调用。

方便集成：

- ERP
- CRM
- OA
- SaaS
- 企业内部系统

---

# 🏗 平台架构

```
                        DeekeHub
                  ┌───────────────────┐
                  │  Web 管理后台      │
                  ├───────────────────┤
                  │  任务管理          │
                  │  脚本管理          │
                  │  设备管理          |
                  |  角色管理          │
                  │  日志中心          │
                  │  API              │
                  └─────────┬─────────┘
                            │
             WebSocket / HTTP / LiveKit
                            │
        ┌───────────────────┼────────────────────┐
        │                   │                    │
    Android             Android             Android
      Device              Device              Device
        │                   │                    │
  DeekeScript        DeekeScript        DeekeScript
        │                   │                    │
Accessibility      OCR      图像识别     自动化任务
```

---

# 💡 为什么选择 DeekeHub？

因为它不仅仅是一个脚本平台。

更是一个完整的 Android 自动化基础设施。

它能够帮助企业完成：

✅ 自动化开发

✅ 自动化部署

✅ 自动化管理

✅ 自动化运维

✅ 自动化监控

真正形成完整闭环。

---

# 🎯 典型应用场景

适用于：

- Android 自动化
- 企业自动化办公
- APP 自动测试
- 云手机管理
- 手机农场
- SaaS 平台
- AI Agent 执行平台
- 批量设备管理
- Android 远程运维
- 企业内部工具

---

# ⭐ 为什么 DeekeScript 值得了解？

很多人第一次接触 Android 自动化。

都会直接开始研究：

- AccessibilityService
- MediaProjection
- OCR
- OpenCV
- 图像识别
- 手势模拟
- Socket
- WebSocket

实际上。

这些能力 DeekeScript 已经全部封装。

开发者只需要关注：

> **业务逻辑。**

而不是 Android 底层。

这也是 DeekeScript 多年来持续优化的目标。

---

# 🚀 我们正在持续完善

未来计划持续加入：

- AI Agent
- 工作流编排
- 插件市场
- 多节点调度
- SDK
- Docker 一键部署
- 更多开放 API
- 更多设备管理能力

欢迎一起交流，共同完善生态。

---

# 🌍 官方网站

**DeekeHub**

👉 https://hub.deeke.cn

---

# 📚 DeekeScript官方文档

👉 https://doc.deeke.cn

---

# ❤️ 如果这个项目对你有所帮助

欢迎点一个 **⭐ Star**。

你的支持，将是 DeekeHub 和 DeekeScript 持续迭代最大的动力。

---

# 📢 写在最后

我们一直认为：

> **未来的 Android，不应该是一台一台去操作。**

而应该像服务器一样：

- 可编程
- 可管理
- 可监控
- 可扩展
- 可协作

DeekeScript 负责让开发更简单。

DeekeHub 负责让管理更高效。

希望它能够帮助更多开发者，把更多时间留给真正有价值的事情。


### 进群交流

![deekeHub开发群](image.png)

> 如需联系作者本人，请访问[https://hub.deeke.cn](https://hub.deeke.cn)
