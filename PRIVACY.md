# 隐私政策 / Privacy Policy

**最后更新：2026-09-18**

扩展名称：图随文走 — Markdown 带图导入（CSDN）

## 一句话

**本扩展不收集、不存储、不传输任何用户数据。**

## 详细说明

### 收集的数据

无。

本扩展没有账号体系，没有后端服务器，没有任何统计、埋点或崩溃上报，也不加载任何远程
代码。它不读取浏览历史、Cookie、密码、表单内容或剪贴板。

### 权限

`manifest.json` 中没有 `permissions` 字段，也没有 `host_permissions` 字段。

唯一的运行范围是一条内容脚本，仅作用于 `https://editor.csdn.net/*`。在其他任何网站上，
本扩展不运行、不加载、不做任何事。

### 你选择的文件怎么被处理

当你主动点击「导入 MD（自动传图）」并选择文件时：

- `.md` 文件在你自己的浏览器里被读取为文本，**不离开你的设备**，只用于写入你当前
  正在编辑的那篇 CSDN 草稿。
- 你一并选中的本地图片，会通过 CSDN 编辑器自身的图片上传功能上传到 CSDN 的图床
  （`i-blog.csdnimg.cn`）。这与你手动把图片粘贴进 CSDN 编辑器的行为完全一致，数据接收方
  是 CSDN，不是本扩展的开发者。
- 若你的 Markdown 里引用了外部图片链接，浏览器会直接向该图片地址发起请求以取回图片，
  再按上一条上传给 CSDN。请求由你的浏览器直接发出，不经过任何第三方中转。

上述过程只在你每次主动点击后发生一次，不在后台进行。

### 数据的出售或转让

不存在。没有数据被收集，因此也没有数据可被出售、转让或用于与功能无关的用途。

### 第三方

本扩展不引入任何第三方 SDK、分析服务或广告。

它与 CSDN 官方没有任何关联，未获其授权或认可，仅通过公开的网页界面与 CSDN 的编辑器
交互。「CSDN」是其各自所有者的商标。

### 源代码

全部代码开源，可自行审阅：

https://github.com/wangsen2020/csdn-md-importer

License: MIT

### 联系方式

有隐私相关的疑问，请在上述仓库提 Issue。

---

# Privacy Policy (English)

**Last updated: 2026-09-18**

This extension **does not collect, store, or transmit any user data.**

It has no accounts, no backend server, no analytics, no telemetry, and loads no remote
code. It declares no `permissions` and no `host_permissions` in its manifest; its only
runtime scope is a single content script limited to `https://editor.csdn.net/*`.

When you explicitly choose files via the import action, the Markdown file is read locally
in your browser and never leaves your device. Images you select are uploaded through
CSDN's own built-in image-upload feature to CSDN's image host — identical to pasting an
image into the CSDN editor yourself. The recipient is CSDN, not the developer of this
extension. No data is sold or transferred to third parties, because none is collected.

This extension is not affiliated with, authorized, or endorsed by CSDN.

Source code (MIT): https://github.com/wangsen2020/csdn-md-importer
