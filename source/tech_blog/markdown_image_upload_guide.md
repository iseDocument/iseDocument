# Markdown 文档插图指南（PicGo + 阿里云 OSS）

> 本文将介绍如何在 Typora 或 VS Code 中快速插入图片，并将图片自动上传到阿里云对象存储（OSS）。

---

## 🌟 效果展示

![插图演示](https://isedocument.oss-cn-beijing.aliyuncs.com/images/2025-05-24.gif)

- 在 Typora 或 VSCode 中**直接粘贴图片**
- 图片**自动上传**至阿里云 OSS
- Markdown 文档中自动插入可外链的图片地址，**可直接在网页或 GitHub 中预览**

---

## 🛠️ 快速配置指南

针对不同编辑器，提供两种主流配置方式：

- **方式一**：Typora 用户（适合喜欢图形界面操作）
- **方式二**：VS Code 用户（适合偏向插件操作）

---

## ✍️ 方式一：Typora 用户（推荐 PicGo GUI 应用）

### 第一步：下载安装 PicGo

1. 前往 GitHub [发布页](https://github.com/Molunerfinn/PicGo/releases)
   （[推荐版本](https://github.com/Molunerfinn/PicGo/releases/tag/v2.3.1)）

2. 下载适用于你的操作系统（Windows/macOS）

3. 安装并运行 PicGo 应用

![下载图示](https://isedocument.oss-cn-beijing.aliyuncs.com/images/20250524172526.png)

---

### 第二步：配置阿里云 OSS 图床

1. 打开 PicGo，进入 `图床设置` › `阿里云 OSS`

![图床设置](https://isedocument.oss-cn-beijing.aliyuncs.com/images/20250524173233.png)

2. 填写以下配置信息，并点击「设为默认图床」：

| 配置项           | 内容                            |
|------------------|----------------------------------|
| AccessKey ID     | LTAI5tLPxQXqBkbrPJQUEC8s         |
| AccessKey Secret | （请联系管理员获取）             |
| Area             | oss-cn-beijing                   |
| Bucket           | isedocument                      |
| Path             | images/                          |

最终设置界面如下：

![OSS 配置图](https://isedocument.oss-cn-beijing.aliyuncs.com/images/20250524173347.png)

---

### 第三步：在 Typora 中启用 PicGo 上传功能

在 Typora 设置中启用「图像上传服务」，选择 PicGo 应用。

![Typora 配置图](https://isedocument.oss-cn-beijing.aliyuncs.com/images/20250524211051.png)

- 设置完成后，你可以在 Typora 中**直接粘贴截图**
- 图片将自动上传至 OSS，Markdown 中插入图片链接

---

## ✍️ 方式二：VS Code 用户（推荐使用 PicGo 插件）

### 第一步：安装 PicGo 插件

1. 打开 VS Code，进入扩展商店  
2. 搜索并安装插件：**PicGo（作者 Spades.S）**

> ⚠️ 注意：这个插件基于 PicGo-Core，不是 PicGo GUI 应用。

---

### 第二步：配置图床信息

插件中图床配置方式与 GUI 应用一致：

- 进入插件设置界面
- 添加 OSS 图床配置信息

![VS Code 配置图](https://isedocument.oss-cn-beijing.aliyuncs.com/images/20250524211749.png)

---

### 第三步：设置快捷键，粘贴即上传

- 可设置上传图片的快捷键（如：`Cmd+Alt+U`）
- 粘贴图片后自动上传至 OSS，并返回图片链接

![快捷键图示](https://isedocument.oss-cn-beijing.aliyuncs.com/images/20250524212101.png)

---

## ✅ 推荐实践

- 将图片统一上传至 `images/` 路径中，方便管理
- 可在文档顶部使用封面图或动图提升可读性
- 避免使用本地路径图片，便于文档在线展示

---

如遇配置问题，可在平台中提 Issue，或联系管理员协助处理。
