# MiniMax Bar

<div align="center">

![MiniMax Bar Logo](Resources/AppIcon.png)

**Mac 菜单栏MiniMax配额监控工具**

[English](README_en.md) | [中文](README.md)

</div>

---

## 功能特性

- **实时配额监控** - 在菜单栏显示 MiniMax API 使用情况
- **多种显示风格** - 支持百分比、数字、进度条等多种显示方式
- **多语言支持** - 中文、英文、日语、韩语
- **开机自启** - 可设置开机自动运行
- **配置文件支持** - 支持从 `~/.mmx/config.json` 读取 API Key

## 显示风格

| 风格 | 说明 |
|------|------|
| 百分比 | `80%` |
| 数字 | `800 / 1000` |
| 进度条+百分比 | 带进度条和百分比数字 |
| 进度条+数字 | 带进度条和原始数据 |
| 进度条+数字+百分比 | 完整显示所有信息 |

## 进度条颜色

提供 8 种渐变色可选：

- 晴空蓝 / 靛青 / 碧绿 / 翡翠绿
- 琥珀 / 玫瑰红 / 紫罗兰 / 海洋渐变

## 安装

### 方法一：下载预编译版本

从 [GitHub Releases](https://github.com/aajijifujiji/MiniMaxBar/releases) 下载最新版本。

### 方法二：从源码编译

```bash
# 克隆仓库
git clone https://github.com/aajijifujiji/MiniMaxBar.git
cd MiniMaxBar

# 使用 Xcode 打开
open MiniMaxQuota.xcodeproj

# 在 Xcode 中点击 Build (⌘B) 编译
```

### 方法三：使用 XcodeGen

```bash
# 安装 XcodeGen (如果未安装)
brew install xcodegen

# 生成 Xcode 项目
xcodegen generate

# 编译
xcodebuild -scheme MiniMaxQuota -configuration Release build
```

## 使用方法

### 首次配置

1. 点击菜单栏图标
2. 右键选择 **设置...**
3. 在 **API 设置** 页面输入你的 MiniMax API Key
4. 选择地区（中国或全球）

### 快捷操作

| 操作 | 说明 |
|------|------|
| 左键点击 | 查看所有模型的配额详情 |
| 右键点击 | 打开快捷菜单 |

### 右键菜单

- **设置** - 打开设置面板
- **刷新** - 手动刷新配额数据
- **关于** - 查看版本和作者信息
- **退出** - 退出应用

## 系统要求

- macOS 12.0 (Monterey) 或更高版本

## 技术栈

- Swift 5.9
- SwiftUI
- AppKit

## 作者

**啊啊唧唧孵唧唧**

## 许可证

MIT License

---

<div align="center">

Made with ❤️ for MiniMax users

</div>

